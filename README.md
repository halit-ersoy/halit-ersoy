<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Profile Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #ff6b6b, #f5af19);
      color: #fff;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .profile-container {
      text-align: center;
      background-color: rgba(0, 0, 0, 0.8);
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.5);
      max-width: 600px;
      animation: fadeIn 2s ease-in-out;
      margin-top: 80px;
    }

    h1 {
      font-size: 2.5em;
      margin: 10px 0;
    }

    h3 {
      font-size: 1.5em;
      margin: 5px 0 20px;
      color: #f5af19;
    }

    p img, .icons img {
      margin: 10px;
      transition: transform 0.3s ease;
    }

    p img:hover, .icons img:hover {
      transform: scale(1.2);
    }

    .contact a img {
      margin: 0 5px;
      filter: grayscale(1);
      transition: filter 0.3s ease, transform 0.3s ease;
    }

    .contact a img:hover {
      filter: grayscale(0);
      transform: scale(1.1);
    }

    @keyframes fadeIn {
      0% { opacity: 0; }
      100% { opacity: 1; }
    }

    .stats img {
      margin: 15px 0;
      width: 100%;
      max-width: 450px;
      border-radius: 10px;
      box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.4);
    }
  </style>
</head>
<body>
  <div class="profile-container">
    <h1>Hi 👋, I'm Pelin KONAK</h1>
    <h3>A passionate app developer from Türkiye</h3>

    <p>
      <img src="https://komarev.com/ghpvc/?username=pelinkonak&label=Profile%20views&color=ff6b6b&style=flat" alt="pelinkonak" />
    </p>

    <p>🔭 I’m currently working on <strong>Kotlin</strong></p>
    <p>📫 How to reach me: <strong>pelin.konak928@gmail.com</strong></p>

    <h3>Connect with me:</h3>
    <p class="contact">
      <a href="https://linkedin.com/in/pelin konak" target="blank">
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="pelin konak" height="30" width="40" />
      </a>
      <a href="https://instagram.com/peliinkonak" target="blank">
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="peliinkonak" height="30" width="40" />
      </a>
      <a href="https://discord.gg/pelko._." target="blank">
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="pelko._." height="30" width="40" />
      </a>
    </p>

    <h3>Languages and Tools:</h3>
    <p class="icons">
      <a href="https://developer.android.com" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40" />
      </a>
      <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer">
        <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40" />
      </a>
      <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40" />
      </a>
      <a href="https://www.w3schools.com/cs/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40" />
      </a>
      <a href="https://www.java.com" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40" />
      </a>
      <a href="https://kotlinlang.org" target="_blank" rel="noreferrer">
        <img src="https://www.vectorlogo.zone/logos/kotlinlang/kotlinlang-icon.svg" alt="kotlin" width="40" height="40" />
      </a>
      <a href="https://www.microsoft.com/en-us/sql-server" target="_blank" rel="noreferrer">
        <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="mssql" width="40" height="40" />
      </a>
      <a href="https://www.python.org" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40" />
      </a>
    </p>

    <div class="stats">
      <img src="https://github-readme-stats.vercel.app/api/top-langs?username=pelinkonak&show_icons=true&locale=en&layout=compact" alt="pelinkonak" />
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=pelinkonak&" alt="pelinkonak" />
    </div>

    <img src="https://github.com/pelinkonak/pelinkonak/blob/output/github-contribution-grid-snake.gif" alt="snake gif" style="margin-top: 20px;" />
  </div>
</body>
</html>
