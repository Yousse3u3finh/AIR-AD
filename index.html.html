<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>A.I.RΘAD – Intelligent Road Control</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!-- Icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<!-- Font -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
*{box-sizing:border-box}
body{
  margin:0;
  font-family:'Poppins',sans-serif;
  background:radial-gradient(circle at top,#0a1f2d,#020b11);
  color:#fff;
  overflow-x:hidden;
}

/* HEADER */
header{
  text-align:center;
  padding:30px;
}
header h1{
  font-size:3rem;
  letter-spacing:4px;
  animation: glow 2s infinite alternate;
}
@keyframes glow{
  from{text-shadow:0 0 10px #00eaff;}
  to{text-shadow:0 0 25px #00eaff;}
}

/* CONTAINER */
.dashboard{
  max-width:1200px;
  margin:auto;
  padding:20px;
}

/* GRID */
.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:25px;
}

/* CARD */
.card{
  background:rgba(255,255,255,0.07);
  border-radius:20px;
  padding:25px;
  position:relative;
  overflow:hidden;
  transition:0.4s;
}
.card:hover{
  transform:translateY(-8px) scale(1.03);
  box-shadow:0 20px 40px rgba(0,234,255,0.3);
}

/* ICON */
.icon{
  font-size:45px;
  margin-bottom:15px;
  animation: float 3s ease-in-out infinite;
}
@keyframes float{
  0%,100%{transform:translateY(0)}
  50%{transform:translateY(-10px)}
}

/* STATUS COLORS */
.green{color:#00ff9d}
.red{color:#ff4d4d}
.yellow{color:#ffc107}
.blue{color:#00eaff}

/* LIVE PULSE */
.pulse::after{
  content:'';
  position:absolute;
  width:15px;height:15px;
  background:#00ff9d;
  border-radius:50%;
  top:20px;right:20px;
  animation:pulse 1.5s infinite;
}
@keyframes pulse{
  0%{transform:scale(1);opacity:1}
  100%{transform:scale(3);opacity:0}
}

/* MAP */
#map{
  height:350px;
  margin-top:40px;
  border-radius:20px;
  overflow:hidden;
  box-shadow:0 0 40px rgba(0,234,255,0.3);
}

/* FOOTER */
footer{
  text-align:center;
  padding:20px;
  opacity:0.6;
  font-size:14px;
}
</style>
</head>

<body>

<header>
  <h1>A.I.RΘAD</h1>
  <p>AI-powered Adaptive Intelligent Road System</p>
</header>

<div class="dashboard">
  <div class="grid">

    <div class="card pulse">
      <i class="fas fa-route icon green"></i>
      <h3>Smart Routing</h3>
      <p>Automatically selects least congested routes.</p>
    </div>

    <div class="card">
      <i class="fas fa-cloud-sun-rain icon yellow"></i>
      <h3>Weather Status</h3>
      <p>Live conditions determine safe road usage.</p>
    </div>

    <div class="card">
      <i class="fas fa-ambulance icon red" id="ambulanceIcon"></i>
      <h3>Ambulance Detection</h3>
      <p id="ambulanceStatus">No ambulance nearby</p>
    </div>

    <div class="card">
      <i class="fas fa-car-crash icon red"></i>
      <h3>Accident Alert</h3>
      <p>Instant rerouting & warnings.</p>
    </div>

    <div class="card">
      <i class="fas fa-walkie-talkie icon blue"></i>
      <h3>Driver Communication</h3>
      <p>Vehicle-to-vehicle alerts within 150m.</p>
    </div>

    <div class="card">
      <i class="fas fa-map-marker-alt icon green"></i>
      <h3>Nearest Safe Location</h3>
      <p>Guides drivers to optimal escape routes.</p>
    </div>

  </div>

  <div id="map"></div>
</div>

<footer>
  Click once anywhere to activate A.I.RΘAD notifications
</footer>

<script>
/* GOOGLE MAP */
function initMap(){
  const cairo={lat:30.0444,lng:31.2357};
  const map=new google.maps.Map(document.getElementById("map"),{
    zoom:12,
    center:cairo
  });
  new google.maps.Marker({position:cairo,map});
}
initMap();

/* NOTIFICATIONS */
let started=false;
document.body.addEventListener("click",()=>{
  if(started)return;
  if(Notification.permission!=="granted"){
    Notification.requestPermission().then(p=>{
      if(p==="granted"){
        started=true;
        notifyLoop();
      }
    });
  }
});

function notifyLoop(){
  setInterval(()=>{
    new Notification("A.I.RΘAD Alert",{
      body:getMessage(),
      icon:"https://cdn-icons-png.flaticon.com/512/854/854894.png"
    });
    simulateAmbulance();
  },30000);
}

function getMessage(){
  const msgs=[
    "🚑 Ambulance approaching – clear the lane",
    "⚠️ Accident detected ahead",
    "🌧 Weather warning – drive carefully",
    "🟢 Traffic flow improved",
    "📍 Nearest safe route updated"
  ];
  return msgs[Math.floor(Math.random()*msgs.length)];
}

/* AMBULANCE SIMULATION */
function simulateAmbulance(){
  const icon=document.getElementById("ambulanceIcon");
  const status=document.getElementById("ambulanceStatus");
  const active=Math.random()>0.5;
  if(active){
    icon.classList.add("pulse");
    status.textContent="Ambulance passing now!";
  }else{
    icon.classList.remove("pulse");
    status.textContent="No ambulance nearby";
  }
}
</script>

<!-- Google Maps API -->
<script src="https://maps.googleapis.com/maps/api/js?key=YOUR_GOOGLE_MAPS_API_KEY"></script>

</body>
</html>
