<div class="profile-card">
  <div class="avatar"></div>
  <h1 class="accent">Mintberry Crunch</h1>
  <h2>Retro Aesthetic / Aero / Metro</h2>
  <p class="bio">Digital playground for code and nostalgia. I build things with glassy UI, pastel vibes, and a hint of early 2000s internet aesthetics.</p>
  <div class="buttons">
    <a href="#" class="btn">Projects</a>
    <a href="#" class="btn">GitHub Repos</a>
    <a href="#" class="btn">Blog</a>
  </div>
  <div class="socials">
    <a href="#">F</a>
    <a href="#">T</a>
    <a href="#">I</a>
  </div>
</div>

<style>
/* === Mintberry Crunch Retro 2000s Theme === */

/* General Reset & Body */
body {
    background: linear-gradient(135deg, #c2f0f0 0%, #a7e6d9 100%);
    font-family: 'Segoe UI', 'Arial', sans-serif;
    color: #1a1a1a;
    display: flex;
    justify-content: center;
    align-items: flex-start;
    min-height: 100vh;
    padding: 50px 20px;
}

/* Profile Card Container */
.profile-card {
    width: 360px;
    padding: 30px 25px;
    background: rgba(255, 255, 255, 0.15);
    border: 1px solid rgba(255, 255, 255, 0.35);
    border-radius: 15px;
    backdrop-filter: blur(12px);
    box-shadow: 0 8px 30px rgba(0, 0, 0, 0.25);
    text-align: center;
    position: relative;
}

/* Avatar */
.profile-card .avatar {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    border: 4px solid rgba(255,255,255,0.4);
    margin-bottom: 15px;
    background: url('https://i.imgur.com/jK0B3Vp.png') center/cover no-repeat;
    box-shadow: 0 0 12px rgba(0,0,0,0.2);
}

/* Header / Name */
.profile-card h1 {
    font-family: 'Impact', 'Arial Black', sans-serif;
    font-size: 26px;
    color: #1a1a1a;
    margin-bottom: 10px;
    text-shadow: 1px 1px #fff, -1px -1px #a7e6d9;
}

/* Subtitle / Tagline */
.profile-card h2 {
    font-family: 'Verdana', sans-serif;
    font-size: 14px;
    color: #555;
    letter-spacing: 1px;
    margin-bottom: 20px;
}

/* Bio Text */
.profile-card .bio {
    font-size: 13px;
    line-height: 1.5;
    margin-bottom: 25px;
    color: #1a1a1a;
}

/* Glassy Buttons */
.profile-card .buttons {
    display: flex;
    flex-direction: column;
    gap: 12px;
}

.profile-card .btn {
    display: block;
    padding: 10px 15px;
    border-radius: 10px;
    border: 1px solid rgba(255,255,255,0.4);
    backdrop-filter: blur(10px);
    background: rgba(255, 255, 255, 0.2);
    color: #1a1a1a;
    font-weight: bold;
    font-size: 14px;
    text-decoration: none;
    transition: 0.3s;
    box-shadow: 0 4px 15px rgba(0,0,0,0.15);
}

.profile-card .btn:hover {
    background: rgba(255, 255, 255, 0.35);
    box-shadow: 0 6px 20px rgba(0,0,0,0.25);
    transform: translateY(-2px);
}

/* Accent Color */
.profile-card .accent {
    color: #7ee8fa;
    text-shadow: 1px 1px #fff;
}

/* Footer / Social Links */
.profile-card .socials {
    margin-top: 20px;
    display: flex;
    justify-content: center;
    gap: 15px;
}

.profile-card .socials a {
    display: block;
    width: 30px;
    height: 30px;
    border-radius: 6px;
    background: rgba(255,255,255,0.2);
    backdrop-filter: blur(8px);
    border: 1px solid rgba(255,255,255,0.3);
    text-align: center;
    line-height: 30px;
    color: #1a1a1a;
    font-weight: bold;
    text-decoration: none;
    transition: 0.3s;
}

.profile-card .socials a:hover {
    background: rgba(255,255,255,0.35);
    transform: translateY(-2px);
}

/* 2000s Pixel Border / Extra Vibe */
.profile-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0; bottom: 0;
    border: 2px dashed rgba(255,255,255,0.25);
    border-radius: 15px;
    pointer-events: none;
}

/* Optional retro glow effect on hover */
.profile-card:hover {
    box-shadow: 0 10px 40px rgba(0,0,0,0.35);
}
</style>
