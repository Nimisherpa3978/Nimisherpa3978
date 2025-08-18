<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nimi Sherpa | Portfolio</title>
  <style>
    *,
    *::after,
    *::before {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body, html {
      height: 100%;
      font-family: 'Arial', sans-serif;
    }

    .bg {
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100dvh;
      background-color: black;
      background-image: url('https://20essentials.github.io/project-000-128/assets/n1.avif');
      background-position: center;
      background-size: cover;
      position: relative;
      overflow: hidden;
      padding: 20px;
    }

    .inner {
      z-index: 1;
      mix-blend-mode: overlay;
      inset: 0;
      position: absolute;
      animation: moveInner 10s ease infinite alternate;
    }

    @keyframes moveInner {
      0%   { background-color: #f0f; }
      25%  { background-color: #0f0; }
      50%  { background-color: #00f; }
      75%  { background-color: #f00; }
      100% { background-color: #ff0; }
    }

    .content {
      position: relative;
      z-index: 2;
      max-width: 1000px;
      background: rgba(0, 0, 0, 0.6);
      padding: 30px;
      border-radius: 12px;
      color: #f2f2f2;
    }

    .content h1,
    .content h3 {
      text-align: center;
      margin-bottom: 10px;
    }

    .content img[alt="coding"] {
      float: right;
      width: 300px;
      max-width: 100%;
      margin: 10px;
      border-radius: 8px;
    }

    .socials a img,
    .tools a img {
      transition: transform 0.3s ease;
    }

    .socials a:hover img,
    .tools a:hover img {
      transform: scale(1.2);
    }

    .tools, .socials {
      margin: 20px 0;
    }

    .stats img {
      max-width: 100%;
    }
  </style>
</head>
<body>

  <main class="bg">
    <aside class="inner"></aside>

    <div class="content">
      <h1>Hi 👋, I'm Nimi Sherpa</h1>
      <h3>A Data Science Enthusiast</h3>

      <img src="https://user-images.githubusercontent.com/55389276/140866485-8fb1c876-9a8f-4d6a-98dc-08c4981eaf70.gif" alt="coding" />

      <p>
        <img src="https://komarev.com/ghpvc/?username=nimisherpa3978&label=Profile%20views&color=0e75b6&style=flat" alt="nimisherpa3978" />
      </p>

      <ul>
        <li>🔭 I’m currently learning <strong>Data Science with Python</strong></li>
        <li>🌱 I’m exploring <strong>Machine Learning and Web Development</strong></li>
        <li>👯 I’m looking to collaborate on <strong>open-source and data projects</strong></li>
        <li>💬 Ask me about <strong>Python, C++, HTML/CSS, JavaScript</strong></li>
        <li>⚡ Fun fact: <strong>I am funny! 😄</strong></li>
      </ul>

      <hr />

      <h3>Connect with me:</h3>
      <p class="socials">
        <a href="https://www.linkedin.com/in/nimi-sherpa-1b78732b6" target="_blank">
          <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="nimi-sherpa" height="30" width="40" />
        </a>
        <a href="https://discord.com/users/nimi20801001" target="_blank">
          <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="nimi20801001" height="30" width="40" />
        </a>
      </p>

      <hr />

      <h3>Languages and Tools:</h3>
      <p class="tools">
        <a href="https://www.cprogramming.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40" /></a>
        <a href="https://www.w3schools.com/cpp/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40" /></a>
        <a href="https://www.python.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40" /></a>
        <a href="https://www.w3.org/html/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40" /></a>
        <a href="https://www.w3schools.com/css/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40" /></a>
        <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40" /></a>
        <a href="https://www.mysql.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40" /></a>
        <a href="https://reactjs.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40" /></a>
        <a href="https://nodejs.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40" /></a>
        <a href="https://www.djangoproject.com/" target="_blank"><img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="40" height="40" /></a>
        <a href="https://developer.android.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40" /></a>
        <a href="https://www.figma.com/" target="_blank"><img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40" /></a>
        <a href="https://git-scm.com/" target="_blank"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40" /></a>
      </p>

      <hr />

      <div class="stats">
        <img src="https://github-readme-stats.vercel.app/api/top-langs?username=nimisherpa3978&show_icons=true&locale=en&layout=compact" alt="Top Languages" />
        <br /><br />
        <img src="https://github-readme-stats.vercel.app/api?username=nimisherpa3978&show_icons=true&locale=en" alt="GitHub Stats" />
      </div>
    </div>
  </main>

</body>
