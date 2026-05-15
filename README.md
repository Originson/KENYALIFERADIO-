<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kenya Life Radio</title>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family: Arial, sans-serif;
}

body{
  background:#060606;
  color:white;
}

/* HEADER */
header{
  text-align:center;
  padding:25px 15px;
  background:linear-gradient(90deg, #ff0000, #111, #ff0000);
}

/* LOGO */
.logo img{
  width:130px;
  border-radius:12px;
  box-shadow:0 0 25px red;
  animation: float 3s ease-in-out infinite;
}

@keyframes float{
  0%,100%{transform:translateY(0);}
  50%{transform:translateY(-10px);}
}

/* FLOAT LIVE BUTTON */
.live-float{
  position:fixed;
  bottom:20px;
  right:20px;
  background:red;
  color:white;
  padding:14px 18px;
  border-radius:50px;
  font-weight:bold;
  box-shadow:0 0 20px red;
  z-index:999;
  text-decoration:none;
}

/* PLAYER BOX */
.player{
  max-width:650px;
  margin:20px auto;
  background:#111;
  padding:20px;
  border-radius:15px;
  box-shadow:0 0 20px red;
  text-align:center;
}

audio{
  width:100%;
  margin-top:10px;
}

/* SECTIONS */
.section{
  padding:25px;
  text-align:center;
}

/* DJ GRID */
.dj-grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(150px,1fr));
  gap:15px;
  max-width:900px;
  margin:0 auto;
}

.dj{
  background:#1a1a1a;
  padding:15px;
  border-radius:15px;
  box-shadow:0 0 10px #ff0000;
}

.dj img{
  width:100%;
  border-radius:10px;
}

/* SCHEDULE */
.schedule{
  max-width:600px;
  margin:0 auto;
  background:#111;
  padding:20px;
  border-radius:15px;
  box-shadow:0 0 15px red;
}

/* BUTTONS */
button{
  padding:10px 18px;
  border:none;
  border-radius:25px;
  margin:5px;
  font-weight:bold;
  cursor:pointer;
  background:red;
  color:white;
}

/* FOOTER */
footer{
  text-align:center;
  padding:15px;
  color:#aaa;
  margin-top:20px;
}
</style>
</head>

<body>

<!-- FLOATING LIVE BUTTON -->
<a class="live-float" href="https://goliveafrica.media/live/1/KENYALIFERADIO" target="_blank">
🔴 LIVE
</a>

<!-- HEADER -->
<header>

  <div class="logo">
    <img src="kenya-life-radio-logo.png" alt="Kenya Life Radio Logo">
  </div>

  <h1>Kenya Life Radio</h1>
  <p>LIVE THE MUSIC • LIVE THE VIBE • LIVE THE LIFE</p>

</header>

<!-- LIVE PLAYER -->
<div class="player">

  <h2>🔴 LIVE ON AIR</h2>

  <audio controls autoplay>
    <source src="https://goliveafrica.media/live/1/KENYALIFERADIO">
    Your browser does not support audio playback.
  </audio>

  <p style="font-size:12px;color:#aaa;margin-top:10px;">
    If stream doesn’t play, click LIVE button above
  </p>

</div>

<!-- SHOWS -->
<div class="section">
  <h2>🔥 Featured Shows</h2>
  <p>🎙 Morning Drive — Motivation & Energy</p>
  <p>🎵 Afrobeat Vibes — African Hits All Day</p>
  <p>🌙 Night Chill — Relaxing Music Flow</p>
</div>

<!-- DJ SECTION -->
<div class="section">
  <h2>🎧 Meet Our DJs</h2>

  <div class="dj-grid">

    <div class="dj">
      <img src="dj1.jpg" alt="DJ 1">
      <h3>DJ King</h3>
    </div>

    <div class="dj">
      <img src="dj2.jpg" alt="DJ 2">
      <h3>DJ Queen</h3>
    </div>

    <div class="dj">
      <img src="dj3.jpg" alt="DJ 3">
      <h3>DJ Blaze</h3>
    </div>

  </div>
</div>

<!-- SCHEDULE -->
<div class="section">
  <h2>📅 Live Schedule</h2>

  <div class="schedule">
    <p>06:00 AM — Morning Drive</p>
    <p>12:00 PM — Afrobeat Vibes</p>
    <p>06:00 PM — Evening Mix</p>
    <p>10:00 PM — Night Chill</p>
  </div>
</div>

<!-- DONATION -->
<div class="section">
  <h2>💚 Support Kenya Life Radio</h2>

  <button>KSh 100</button>
  <button>KSh 200</button>
  <button>KSh 500</button>
  <button>KSh 1,000</button>
  <button>KSh 5,000</button>
  <button>KSh 10,000</button>
</div>

<!-- CONTACT -->
<div class="section">
  <h2>📞 Contact Us</h2>
  <p>WhatsApp: +254725822639</p>
  <p>Email: info@kenyaliferadio.com</p>
</div>

<footer>
  © 2026 Kenya Life Radio — All Rights Reserved
</footer>

</body>
</html>
