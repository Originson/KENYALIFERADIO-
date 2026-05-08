<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Kenya Life Radio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Poppins',sans-serif;
    background:#050505;
    color:white;
    overflow-x:hidden;
}

/* BACKGROUND ANIMATION */

body::before{
    content:"";
    position:fixed;
    width:100%;
    height:100%;
    background:
    radial-gradient(circle at top left, rgba(255,0,0,0.15), transparent 30%),
    radial-gradient(circle at bottom right, rgba(0,255,0,0.15), transparent 30%);
    z-index:-1;
    animation:bgMove 10s infinite alternate;
}

@keyframes bgMove{
    from{transform:scale(1);}
    to{transform:scale(1.1);}
}

.app{
    max-width:430px;
    margin:auto;
    min-height:100vh;
    background:#0b0f1a;
    box-shadow:0 0 40px rgba(0,0,0,0.8);
}

/* HEADER */

.topbar{
    display:flex;
    align-items:center;
    justify-content:space-between;
    padding:15px;
    background:#101828;
    border-bottom:2px solid red;
    position:sticky;
    top:0;
    z-index:999;
}

.brand{
    display:flex;
    align-items:center;
    gap:12px;
}

.logo{
    width:60px;
    height:60px;
    border-radius:50%;
    object-fit:cover;
    border:2px solid #00ff55;
    box-shadow:0 0 20px rgba(0,255,85,0.6);
}

.station-name{
    font-size:18px;
    font-weight:700;
}

.live{
    color:red;
    font-size:12px;
    animation:pulse 1s infinite;
}

@keyframes pulse{
    0%{opacity:1;}
    50%{opacity:0.4;}
    100%{opacity:1;}
}

/* HERO */

.hero{
    text-align:center;
    padding:20px;
}

.cover{
    width:100%;
    border-radius:20px;
    margin-top:10px;
    box-shadow:0 0 25px rgba(255,0,0,0.4);
    animation:float 4s ease-in-out infinite;
}

@keyframes float{
    0%{transform:translateY(0px);}
    50%{transform:translateY(-8px);}
    100%{transform:translateY(0px);}
}

.hero h1{
    margin-top:20px;
    font-size:30px;
    font-weight:700;
}

.tagline{
    color:#00ff55;
    margin-top:10px;
    font-size:14px;
}

/* BUTTONS */

.btn{
    display:block;
    margin:15px auto;
    padding:16px;
    width:90%;
    border-radius:16px;
    font-weight:700;
    text-decoration:none;
    text-align:center;
    transition:0.3s;
    font-size:16px;
}

.btn:hover{
    transform:scale(1.04);
}

.listen{
    background:linear-gradient(90deg,#ff0000,#00ff55);
    color:white;
    box-shadow:0 0 20px rgba(255,0,0,0.5);
}

.youtube{
    background:#ff0033;
    color:white;
}

audio{
    width:90%;
    margin-top:10px;
}

/* SECTION */

.section{
    padding:20px;
}

.section-title{
    text-align:center;
    margin-bottom:20px;
    font-size:22px;
    color:#00ff55;
}

/* SHOWS */

.card{
    background:#121b2f;
    padding:15px;
    margin-bottom:15px;
    border-radius:15px;
    text-align:center;
    border:1px solid #1d2a44;
    transition:0.3s;
}

.card:hover{
    transform:translateY(-5px);
    border-color:red;
}

/* DONATION GRID */

.donation-grid{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:12px;
}

.donate-btn{
    background:linear-gradient(135deg,#00ff99,#00b36b);
    padding:15px;
    border-radius:15px;
    text-align:center;
    text-decoration:none;
    color:#000;
    font-weight:700;
    transition:0.3s;
    box-shadow:0 0 15px rgba(0,255,153,0.25);
}

.donate-btn:hover{
    transform:scale(1.05);
}

/* CONTACT */

.contact{
    text-align:center;
    padding:20px;
    line-height:2;
}

.contact a{
    color:#00ff55;
    text-decoration:none;
}

/* FOOTER */

footer{
    text-align:center;
    padding:20px;
    color:#888;
    font-size:12px;
    background:#0d1422;
    margin-top:20px;
}

</style>
</head>

<body>

<div class="app">

<!-- TOPBAR -->

<div class="topbar">

<div class="brand">

<!-- LOGO IMAGE -->
<img src="kenya-life-logo.png" class="logo">

<div>
<div class="station-name">Kenya Life Radio</div>
<div class="live">● LIVE ON AIR</div>
</div>

</div>

</div>

<!-- HERO -->

<div class="hero">

<!-- COVER PHOTO -->
<img src="kenya-life-cover.jpg" class="cover">

<h1>KENYA LIFE RADIO</h1>

<div class="tagline">
LIVE THE MUSIC • LIVE THE VIBE • LIVE THE LIFE
</div>

<!-- LIVE BUTTON -->

<a class="btn listen"
href="https://goliveafrica.media/live/1/KENYALIFERADIO"
target="_blank">

▶ LISTEN LIVE NOW

</a>

<!-- AUTO PLAY PLAYER -->

<audio controls autoplay>
<source src="https://goliveafrica.media/live/1/KENYALIFERADIO" type="audio/mpeg">
</audio>

<!-- YOUTUBE -->

<a class="btn youtube"
href="https://www.youtube.com/@KingsandQueensStudios"
target="_blank">

🎥 WATCH ON YOUTUBE

</a>

</div>

<!-- SHOWS -->

<div class="section">

<div class="section-title">
🔥 Featured Shows
</div>

<div class="card">
🎙 Morning Drive
</div>

<div class="card">
🎵 Afrobeat Vibes
</div>

<div class="card">
🌙 Night Chill
</div>

</div>

<!-- DONATION SECTION -->

<div class="section">

<div class="section-title">
💚 Support Kenya Life Radio
</div>

<div class="donation-grid">

<a class="donate-btn" href="tel:*334*1*100*0725822639#">
KSh 100
</a>

<a class="donate-btn" href="tel:*334*1*200*0725822639#">
KSh 200
</a>

<a class="donate-btn" href="tel:*334*1*500*0725822639#">
KSh 500
</a>

<a class="donate-btn" href="tel:*334*1*1000*0725822639#">
KSh 1,000
</a>

<a class="donate-btn" href="tel:*334*1*2000*0725822639#">
KSh 2,000
</a>

<a class="donate-btn" href="tel:*334*1*5000*0725822639#">
KSh 5,000
</a>

<a class="donate-btn" href="tel:*334*1*10000*0725822639#">
KSh 10,000
</a>

<a class="donate-btn" href="tel:*334*1*50000*0725822639#">
KSh 50,000
</a>

</div>

</div>

<!-- CONTACT -->

<div class="contact">

📞 WhatsApp:
<a href="https://wa.me/254725822639">
+254725822639
</a>

<br>

📧 info@kenyaliferadio.com

</div>

<footer>

© 2026 Kenya Life Radio — All Rights Reserved

</footer>

</div>

</body>
</html>
