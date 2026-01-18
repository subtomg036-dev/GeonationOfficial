<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Geonation SMP – Official Server</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box}
body{
  font-family:'Inter',sans-serif;
  background:#0e1f19;
  color:#fff;
  line-height:1.6;
  scroll-behavior:smooth;
}

/* NAVBAR */
nav{
  position:fixed;top:0;left:0;width:100%;height:80px;
  background:#0b3a2b;
  display:flex;align-items:center;justify-content:space-between;
  padding:0 48px;z-index:1000
}
nav a{color:#b6ffe6;text-decoration:none;font-weight:600;margin-right:24px}
nav .logo{font-weight:800;font-size:22px}

/* HERO */
.hero{
  min-height:80vh;
  background:linear-gradient(180deg,#00ff99,#0077ff);
  display:flex;align-items:center;justify-content:center;
  text-align:center;padding-top:120px
}
.hero h1{font-size:64px}
.hero p{margin-top:20px;font-size:20px}
.hero .cta{
  margin-top:40px;display:flex;justify-content:center;gap:20px;flex-wrap:wrap
}
.hero .cta div{
  background:#0b3a2b;padding:18px 34px;border-radius:10px;font-weight:700
}

/* SECTIONS */
section{padding:120px 60px}
section h2{font-size:44px;margin-bottom:70px;text-align:center}

/* GAMEMODES */
.gamemodes{
  display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
  gap:40px;margin-bottom:80px
}
.mode{
  background:#102e23;padding:50px;border-radius:22px;
  border:2px solid #00ff99;transition:.3s
}
.mode:hover{transform:translateY(-12px)}

/* RANKS */
.ranks{
  display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
  gap:35px;margin-bottom:80px
}
.rank{
  padding:32px;border-radius:16px;
  background:#0c251d;font-weight:600;transition:.3s;cursor:default
}
.rank:hover{transform:translateY(-10px)}
.elite{border-left:6px solid #00ffff}
.admin{border-left:6px solid #ff4444}
.helper{border-left:6px solid #33ff99}
.warrior{border-left:6px solid #ffaa00}
.hero-r{border-left:6px solid #aa66ff}
.media{border-left:6px solid #00ccff}
.member{border-left:6px solid #ffffff}
.rank h3{font-size:26px;margin-bottom:15px}
.rank p{opacity:.85}

/* STATUS */
.status{
  display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
  gap:30px;margin-bottom:80px
}
.status div{
  background:#102e23;padding:34px;border-radius:18px
}

/* FOOTER */
footer{padding:100px 40px;background:#071611;text-align:center;color:#9fffd7}

@media(max-width:900px){
  nav{padding:0 20px}
  section{padding:100px 30px}
  .hero h1{font-size:44px}
}
</style>
</head>
<body>

<nav>
  <div class="logo">GEONATION</div>
  <div>
    <a href="#play">Home</a>
    <a href="#gamemodes">Gamemodes</a>
    <a href="#ranks">Ranks</a>
    <a href="https://discord.gg/34VAZTR8" target="_blank">Discord</a>
    <a href="https://www.tiktok.com/@mc_itzzmg" target="_blank">TikTok</a>
  </div>
</nav>

<div class="hero" id="play">
  <div>
    <h1>GEONATION SMP</h1>
    <p>The ultimate Georgian Minecraft server</p>
    <div class="cta">
      <div>🟢 Online</div>
      <div>Version 1.21</div>
      <div>IP: Geonation.aternos.me</div>
    </div>
  </div>
</div>

<section id="gamemodes">
<h2>Gamemodes</h2>
<div class="gamemodes">
  <div class="mode">🔥 LifeSteal</div>
  <div class="mode">🌍 Survival</div>
  <div class="mode">🧱 OneBlock</div>
  <div class="mode">⚔️ Kit-PvP</div>
</div>
</section>

<section id="ranks">
<h2>Ranks</h2>
<div class="ranks">
  <div class="rank elite">💎 <h3>Elite</h3><p>Premium powers and perks</p></div>
  <div class="rank admin">🛑 <h3>Admin</h3><p>Server management rank</p></div>
  <div class="rank helper">🛠 <h3>Helper</h3><p>Help and support players</p></div>
  <div class="rank warrior">⚔️ <h3>Warrior</h3><p>Combat focused abilities</p></div>
  <div class="rank hero-r">🦸 <h3>Hero</h3><p>Special hero abilities</p></div>
  <div class="rank media">🎥 <h3>Media</h3><p>Content creator rank</p></div>
  <div class="rank member">👤 <h3>Member</h3><p>Default server rank</p></div>
  <div class="rank member">👤 <h3>Member</h3><p>Default server rank</p></div>
</div>
</section>

<section id="status">
<h2>Server Status</h2>
<div class="status">
  <div>🟢 Online</div>
  <div>Version: 1.21</div>
  <div>IP: Geonation.aternos.me</div>
</div>
</section>

<footer>
© 2026 Geonation SMP • All ranks visible on one page
</footer>

</body>
</html>
