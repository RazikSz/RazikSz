<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Raziek Sz | Profile</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      background: radial-gradient(circle at top, #1a1b26 0%, #0d1117 100%);
      color: #c9d1d9;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      line-height: 1.6;
      padding: 30px 15px;
      display: flex;
      justify-content: center;
    }

    .container {
      max-width: 820px;
      width: 100%;
      background: rgba(22, 27, 34, 0.85);
      backdrop-filter: blur(10px);
      border: 1px solid #30363d;
      border-radius: 16px;
      padding: 35px 25px;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
    }

    h1, h2, h3 {
      color: #58a6ff;
      text-align: center;
      margin-bottom: 15px;
      font-weight: 700;
    }

    .subtitle {
      text-align: center;
      margin-bottom: 25px;
    }

    .avatar-wrapper {
      text-align: center;
      margin: 20px 0;
    }

    .avatar {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #58a6ff;
      box-shadow: 0 0 20px rgba(88, 166, 255, 0.4);
      transition: transform 0.3s ease;
    }

    .avatar:hover {
      transform: scale(1.05);
    }

    /* Kartu Informasi (Intro & Profile) */
    .cards-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 20px;
      margin: 25px 0;
    }

    @media (max-width: 650px) {
      .cards-grid {
        grid-template-columns: 1fr;
      }
    }

    .card {
      background: #161b22;
      border: 1px solid #30363d;
      border-radius: 12px;
      padding: 18px;
      position: relative;
    }

    .card h4 {
      color: #ff7b72;
      margin-bottom: 10px;
      display: flex;
      align-items: center;
      gap: 8px;
    }

    pre {
      background: #0d1117;
      border-radius: 8px;
      padding: 12px;
      font-family: 'Fira Code', 'Courier New', monospace;
      font-size: 13px;
      color: #79c0ff;
      overflow-x: auto;
      border: 1px solid #21262d;
    }

    /* Badges & Social Links */
    .badge-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
      margin: 15px 0 30px;
    }

    .badge-container a {
      transition: transform 0.2s ease;
    }

    .badge-container a:hover {
      transform: translateY(-3px);
    }

    /* Tech Stack Icons */
    .skills-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 14px;
      padding: 10px;
      background: #0d1117;
      border-radius: 12px;
      border: 1px solid #21262d;
      margin-bottom: 30px;
    }

    .skills-container img {
      transition: transform 0.2s;
    }

    .skills-container img:hover {
      transform: scale(1.15);
    }

    /* Music Grid */
    .music-container {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 15px;
      margin: 15px 0 25px;
    }

    @media (max-width: 550px) {
      .music-container {
        grid-template-columns: 1fr;
      }
    }

    .music-card {
      background: #0d1117;
      border: 1px solid #30363d;
      border-radius: 10px;
      padding: 12px;
      display: flex;
      align-items: center;
      gap: 12px;
      text-decoration: none;
      color: inherit;
      transition: border-color 0.2s, background 0.2s;
    }

    .music-card:hover {
      border-color: #58a6ff;
      background: #161b22;
    }

    .music-card img {
      border-radius: 6px;
      width: 50px;
      height: 50px;
      object-fit: cover;
    }

    .music-info {
      display: flex;
      flex-direction: column;
    }

    .music-title {
      font-size: 14px;
      font-weight: 600;
      color: #f0f6fc;
    }

    .music-sub {
      font-size: 12px;
      color: #8b949e;
    }

    /* GitHub Stats */
    .stats-container {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 12px;
      margin: 20px 0;
    }

    .stats-container img {
      max-width: 100%;
      height: auto;
    }

    .divider {
      height: 1px;
      background: #30363d;
      margin: 35px 0;
      border: none;
    }

    .gif-center {
      text-align: center;
      margin: 15px 0;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>
      Hi, I'm Raziek Sz 
      <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35" alt="wave" style="vertical-align: middle;">
    </h1>

    <div class="avatar-wrapper">
      <img src="https://files.catbox.moe/h73x0c.jpg" alt="Profile Picture" class="avatar">
    </div>

    <div class="subtitle">
      <a href="https://github.com/RazikSz/readme-typing-svg">
        <img src="https://readme-typing-svg.herokuapp.com?lines=Im+Creator;But+I+will+Keep+Learning;I%20|%20Like%20|%20CODING%20:);lets%20study;Together%20HEHEHE%20:)%20:)&center=true&width=500&height=50" alt="Typing SVG" />
      </a>
    </div>

    <div class="cards-grid">
      <div class="card">
        <h4>💓 Introduction</h4>
        <pre>
Intro = {
  "Name": "A.Raziek.R",
  "Status": "Learning, Playing",
  "Address": "Jakarta Barat, Indonesia",
  "Birthday": "September - 15"
}

// Big Thanks To:
// - Allah SWT
// - All Helpers
// - The Last Generation & Friends</pre>
      </div>

      <div class="card">
        <h4>⚡ Quick Profile</h4>
        <pre>
Hostname   : RaziekSzz
Hobbies    : Watch Anime & Gamer
Best Anime : Gotoubun No Hanayome
Location   : Indonesia, West Jakarta
Domain     : rziekszz.netlify.app</pre>
        <div style="text-align: right; margin-top: 10px;">
          <img src="https://media.tenor.com/qLVgTQhZ4JoAAAAi/ehe-aha.gif" width="70" alt="chibi gif">
        </div>
      </div>
    </div>

    <hr class="divider">

    <h2>🌏 Connect With Me</h2>
    <div class="badge-container">
      <a href="https://www.instagram.com/rziek_sz" target="_blank">
        <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/>
      </a>
      <a href="https://www.youtube.com/@ZkrEdtz" target="_blank">
        <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube"/>
      </a>
      <a href="https://wa.me/6287885873325" target="_blank">
        <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"/>
      </a>
      <a href="https://t.me/Szzzzzkr" target="_blank">
        <img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/>
      </a>
    </div>

    <div class="gif-center">
      <img src="https://media1.tenor.com/m/oXkW9LLAGG8AAAAC/oshi-no-ko-head-bob.gif" width="120" alt="oshi no ko">
    </div>

    <h2>🎵 My Favorite Songs</h2>
    <div class="music-container">
      <a class="music-card" href="https://music.youtube.com/watch?v=oXZcuHIR5ko" target="_blank">
        <img src="https://img.youtube.com/vi/oXZcuHIR5ko/hqdefault.jpg" alt="LOVE 2000 Cover">
        <div class="music-info">
          <span class="music-title">LOVE 2000</span>
          <span class="music-sub">YouTube Music</span>
        </div>
      </a>

      <a class="music-card" href="https://music.youtube.com/watch?v=ObvC7QEuqXY" target="_blank">
        <img src="https://img.youtube.com/vi/ObvC7QEuqXY/hqdefault.jpg" alt="Jinsei Easy Cover">
        <div class="music-info">
          <span class="music-title">人生イージー</span>
          <span class="music-sub">YouTube Music</span>
        </div>
      </a>
    </div>

    <h3>🎧 Spotify Playing</h3>
    <div class="gif-center">
      <img src="https://now-playing-on-spotify.vercel.app/api/spotify" alt="Spotify Now Playing" style="max-width: 100%; border-radius: 8px;" />
    </div>

    <hr class="divider">

    <h2>🛠️ Languages & Tools</h2>
    <div class="skills-container">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" width="40" height="40"/>
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" width="40" height="40"/>
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="40" height="40"/>
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="Bootstrap" width="40" height="40"/>
      <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="Tailwind" width="40" height="40"/>
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React" width="40" height="40"/>
      <img src="https://reactnative.dev/img/header_logo.svg" alt="React Native" width="40" height="40"/>
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redux/redux-original.svg" alt="Redux" width="40" height="40"/>
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="NodeJS" width="40" height="40"/>
      <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="NextJS" width="40" height="40"/>
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40"/>
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++" width="40" height="40"/>
      <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" width="40" height="40"/>
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" width="40" height="40"/>
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux" width="40" height="40"/>
    </div>

    <h2>📉 GitHub Activity</h2>
    <div class="stats-container">
      <img src="https://github-readme-stats.vercel.app/api?username=RazikSz&layout=compact&show_icons=true&theme=tokyonight&hide_border=true" alt="Github Stats" />
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RazikSz&layout=compact&theme=tokyonight&hide_border=true" alt="Top Langs" />
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=RazikSz&theme=tokyonight&hide_border=true" alt="Streak Stats" />
    </div>

    <hr class="divider">

    <div class="gif-center">
      <h3>🙏 Thank you for visiting!</h3>
      <img src="https://media1.tenor.com/m/p_Wua847HAYAAAAd/hanamaru-kindergarten-anime.gif" width="240" alt="thank you gif" style="border-radius: 12px; margin-top: 10px;">
    </div>
  </div>

</body>
</html>
