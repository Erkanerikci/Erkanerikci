<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Neon Effect</title>
  <style>
    body {
      background-color: #0d1117;
      color: white;
      font-family: Arial, sans-serif;
      text-align: center;
    }

    h2, h3 {
      color: #fff;
      text-shadow: 0 0 5px #0ff, 0 0 10px #0ff, 0 0 20px #0ff;
    }

    .neon-box {
      display: inline-block;
      padding: 15px 25px;
      margin: 10px auto;
      color: white;
      border-radius: 10px;
      font-size: 18px;
      text-shadow: 0 0 5px #fff, 0 0 10px #0ff, 0 0 20px #0ff;
      background: rgba(255, 255, 255, 0.1);
      box-shadow: 0 0 10px #0ff, 0 0 20px #0ff, 0 0 30px #0ff, 0 0 40px #0ff;
    }

    .neon-link {
      display: inline-block;
      color: #0ff;
      text-decoration: none;
      padding: 8px 20px;
      border: 2px solid #0ff;
      border-radius: 5px;
      font-size: 18px;
      box-shadow: 0 0 5px #0ff, 0 0 10px #0ff, 0 0 20px #0ff;
      transition: 0.3s;
    }

    .neon-link:hover {
      box-shadow: 0 0 10px #0ff, 0 0 30px #0ff, 0 0 50px #0ff;
      transform: scale(1.1);
    }
  </style>
</head>
<body>

  <h2>👋 Hi, I’m @Erkan</h2>
  <h3>💻 I am working on Python, Dart, Flutter, MSSQL, Java, C#, HTML, CSS, JavaScript.</h3>
  <h3>📧 How to reach me: erkanerikci123@gmail.com</h3>
  <h3>🏫 I am a student at Kastamonu University.</h3>

  <div class="neon-box">
    <p>💻 GitHub Stats</p>
    <img src="https://github-readme-stats.vercel.app/api?username=Erkanerikci&theme=dracula" alt="stats graph" />
  </div>

  <div class="neon-box">
    <p>🔥 Languages</p>
    <img src="https://github-readme-stats.vercel.app/api/top-langs?username=Erkanerikci&layout=compact&theme=dracula" alt="languages graph" />
  </div>

  <div>
    <a class="neon-link" href="https://www.instagram.com/__erkanerikci0/?hl=tr" target="_blank">Instagram</a>
    <a class="neon-link" href="mailto:erkanerikci123@gmail.com" target="_blank">Gmail</a>
    <a class="neon-link" href="https://www.linkedin.com/in/erkan-erikci-5212562aa/" target="_blank">LinkedIn</a>
  </div>

</body>
</html>
