<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Роман | Backend Developer</title>
  <link rel="preconnect" href="https://fonts.googleapis.com ">
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg-gradient: linear-gradient(135deg, #6441A5, #2A0F47);
      --neon-purple: #a259ff;
      --text-color: white;
      --card-bg: rgba(0, 0, 0, 0.6);
    }

    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background: var(--bg-gradient);
      color: var(--text-color);
      line-height: 1.6;
      overflow-x: hidden;
    }

    .container {
      max-width: 900px;
      margin: auto;
      padding: 40px 20px;
      text-align: center;
    }

    h1 {
      font-size: 2.5rem;
      animation: flicker 2s infinite;
    }

    @keyframes flicker {
      0%, 18%, 22%, 25%, 53%, 57%, 100% { opacity: 1; }
      20%, 24%, 55% { opacity: 0.4; }
    }

    img.logo {
      border-radius: 12px;
      box-shadow: 0 0 10px var(--neon-purple);
      transition: transform 0.3s ease;
    }

    img.logo:hover {
      transform: scale(1.05);
    }

    a {
      text-decoration: none;
    }

    .badge {
      margin: 10px;
    }

    .section {
      background: var(--card-bg);
      padding: 25px;
      border-radius: 12px;
      margin: 30px 0;
      box-shadow: 0 0 15px var(--neon-purple);
      backdrop-filter: blur(10px);
    }

    .tech-icons {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 15px;
    }

    .tech-icons img {
      transition: transform 0.3s;
    }

    .tech-icons img:hover {
      transform: scale(1.2) rotate(5deg);
    }

    .joke-card {
      margin-top: 20px;
      border: 2px dashed var(--neon-purple);
      border-radius: 12px;
      padding: 15px;
    }

    footer {
      font-size: 0.9rem;
      margin-top: 40px;
      color: #ccc;
    }

    @media (max-width: 600px) {
      h1 {
        font-size: 1.8rem;
      }

      .tech-icons {
        justify-content: center;
      }
    }
  </style>
</head>

<body>
  <div class="container">
    <img src=" https://i.pinimg.com/originals/00/d3/c4/00d3c4fa3400cdce4f9bddd236e43de5.gif "
         alt="Twitch guy agrees" class="logo" width="100%" />

    <h1>Добро пожаловать на мою страничку 👋</h1>

    <div>
      <a href="https://www.youtube.com/channel/UC_ZTc_Ip4ZilZ-s-m-g4Glg " target="_blank">
        <img src="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&style=for-the-badge"
             class="badge" alt="youtube logo">
      </a>
    </div>

    <div>
      <img src=" https://visitor-badge.laobi.icu/badge?page_id=romanstalinist.romanstalinist"
           alt="stats info" class="badge" />
    </div>

    <div class="section">
      <h3>👩‍💻 Обо мне</h3>
      <p>
        Привет, я начинающий Backend-разработчик, владею ООП языками C#, Java, PHP и имею опыт работы с реляционными базами данных, включая MsSql и MySql. Я стремлюсь к постоянному развитию своих навыков и готов к новым вызовам в сфере разработки программного обеспечения! 💻🚀
      </p>
    </div>

    <div class="section">
      <h3 align="left">🛠 Технологии:</h3>
      <div class="tech-icons">
        <img src=" https://skillicons.dev/icons?i=cs" height="40" alt="c# logo">
        <img src=" https://skillicons.dev/icons?i=net" height="40" alt="dotnet logo">
        <img src=" https://skillicons.dev/icons?i=java" height="40" alt="java logo">
        <img src=" https://skillicons.dev/icons?i=spring" height="40" alt="spring logo">
        <img src=" https://skillicons.dev/icons?i=hibernate" height="40" alt="hibernate logo">
        <img src=" https://skillicons.dev/icons?i=php" height="40" alt="php logo">
        <img src=" https://skillicons.dev/icons?i=mysql" height="40" alt="mysql logo">
        <img src=" https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg " height="40" alt="html5 logo">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg " height="40" alt="css3 logo">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg " height="40" alt="javascript logo">
        <img src="https://skillicons.dev/icons?i=py" height="40" alt="python logo">
      </div>
    </div>

    <div class="joke-card">
      <img src=" https://readme-jokes.vercel.app/api " alt="Jokes Card" width="100%">
    </div>

    <div class="section">
      <h3>📌 Немного обо мне:</h3>
      <ul style="text-align: left; list-style: inside;">
        <li>🔭 В данный момент я работаю над <code>TwitchDescriptionUpdater</code></li>
        <li>🌱 В данный момент я изучаю <code>Chrome Extensions</code></li>
        <li>👯 Я хотел бы скооперироваться с <code>никем</code></li>
        <li>🤔 Мне нужна помощь с <code>ничем</code></li>
        <li>📬 Как до меня достучаться: <a href="https://t.me/roma_sharper " target="_blank">Telegram</a></li>
        <li>😄 Местоимения: он / его</li>
        <li>⚡ Забавный факт: Инфаркты чаще случаются в понедельник.</li>
      </ul>
    </div>

    <footer>
      &copy; Роман | GitHub Profile Page | Powered by 🔥
    </footer>
  </div>
</body>
</html>
