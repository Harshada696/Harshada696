<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Harshada Mundwadkar | Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: #f5f5f5;
      overflow-x: hidden;
    }

    .container {
      text-align: center;
      padding: 60px 20px;
      animation: fadeIn 1.5s ease-in-out;
    }

    .typing {
      font-weight: bold;
      font-size: 24px;
      white-space: nowrap;
      overflow: hidden;
      border-right: 3px solid #FF6F61;
      width: 0;
      animation: typing 4s steps(40, end), blink 0.75s step-end infinite;
      margin: auto;
      max-width: 90vw;
    }

    @keyframes typing {
      from { width: 0; }
      to { width: 100%; }
    }

    @keyframes blink {
      50% { border-color: transparent; }
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .tech-stack img {
      margin: 5px;
      transition: transform 0.3s ease;
    }

    .tech-stack img:hover {
      transform: scale(1.1);
    }

    .github-graph {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      margin: 20px 0;
    }

    .block {
      width: 12px;
      height: 12px;
      margin: 2px;
      background-color: #3fbaeb;
      border-radius: 2px;
      animation: pulse 2s infinite;
    }

    @keyframes pulse {
      0%, 100% { opacity: 0.3; }
      50% { opacity: 1; }
    }

    .section-title {
      font-size: 22px;
      margin: 30px 0 15px;
      color: #FFD166;
    }

    .connect a {
      margin: 0 10px;
      text-decoration: none;
    }

    .connect img:hover {
      transform: scale(1.1);
    }
  </style>
</head>
<body>

<div class="container">
  <h1>👩‍💻 Harshada Mundwadkar</h1>
  <div class="typing">Building smart tech with heart 💡 | Web Dev • AI • Cloud</div>

  <p style="max-width: 700px; margin: 20px auto; font-size: 17px; line-height: 1.7;">
    I'm a <strong>B.Tech CS student</strong> passionate about full-stack development, AI, and real-world automation. I create interactive tools, cloud-backed systems, and smart apps using tech like React, Node.js, Python, Firebase & AWS.
  </p>

  <div class="section-title">⚙️ Tech Stack</div>
  <div class="tech-stack">
    <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=white" />
    <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" />
    <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
    <img src="https://img.shields.io/badge/MySQL-00758F?style=flat-square&logo=mysql&logoColor=white" />
    <img src="https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white" />
    <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=java&logoColor=white" />
    <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=white" />
  </div>

  <div class="section-title">📊 GitHub Activity Vibes</div>
  <div class="github-graph">
    <!-- Simulated GitHub contribution blocks -->
    <div class="block" style="animation-delay: 0s;"></div>
    <div class="block" style="animation-delay: 0.2s;"></div>
    <div class="block" style="animation-delay: 0.4s;"></div>
    <div class="block" style="animation-delay: 0.6s;"></div>
    <div class="block" style="animation-delay: 0.8s;"></div>
    <div class="block" style="animation-delay: 1s;"></div>
    <div class="block" style="animation-delay: 1.2s;"></div>
    <div class="block" style="animation-delay: 1.4s;"></div>
  </div>

  <div class="section-title">🌱 Highlights</div>
  <p style="max-width: 700px; margin: auto; font-size: 16px; line-height: 1.8;">
    🎥 Built an AI-enhanced YouTube clone for video summarization.<br>
    📘 Created a resource-rich student portal for 250+ users.<br>
    🧪 CNN-powered fruit disease detector (90%+ accuracy).<br>
    🤖 Arduino robot that detects and cleans surfaces.<br>
    💡 Certified by IIT Bombay, NPTEL & AWS.
  </p>

  <div class="section-title">📬 Connect With Me</div>
  <div class="connect">
    <a href="https://www.linkedin.com/in/harshadamundwadkar-tech-student" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin" />
    </a>
    <a href="mailto:harshadamundwadkar@gmail.com">
      <img src="https://img.shields.io/badge/Gmail-Email-red?style=flat-square&logo=gmail&logoColor=white" />
    </a>
    <a href="https://github.com/Harshada696" target="_blank">
      <img src="https://img.shields.io/badge/GitHub-Follow-black?style=flat-square&logo=github" />
    </a>
  </div>

  <p style="margin-top: 20px; font-size: 15px;">
    📱 <b>+91-8329056365</b><br>
    🧠 “Code is the closest thing we have to a superpower.”
  </p>
</div>

</body>
</html>
