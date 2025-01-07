<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Introduction</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
  <style>
    /* Animation for image scaling on hover */
    @keyframes scaleImage {
      0% {
        transform: scale(1);
      }
      50% {
        transform: scale(1.1);
      }
      100% {
        transform: scale(1);
      }
    }

    img {
      transition: transform 0.3s ease;
    }

    img:hover {
      animation: scaleImage 0.6s ease forwards;
    }

    /* Animation for text fade-in */
    @keyframes fadeIn {
      0% {
        opacity: 0;
      }
      100% {
        opacity: 1;
      }
    }

    h1 {
      animation: fadeIn 2s ease-out;
    }

    /* Animation for badges sliding in */
    @keyframes slideIn {
      0% {
        opacity: 0;
        transform: translateX(-50px);
      }
      100% {
        opacity: 1;
        transform: translateX(0);
      }
    }

    div img {
      animation: slideIn 1s ease-out forwards;
    }

    /* Add some margin to each section for clarity */
    h1, h3, p {
      margin-bottom: 20px;
    }
  </style>
</head>
<body>
  <div align="center" class="animate__animated animate__fadeIn">
    <img height="150" src="https://camo.githubusercontent.com/62da68eb62b1e5f175f7d1f0191dd89a653d7908feb22d37d4a0ab07365d6791/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f4d3967624264396e6244724f5475314d71782f67697068792e676966" />
  </div>

  <div align="center">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="linkedin logo" class="animate__animated animate__slideInLeft" />
    <img src="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="youtube logo" class="animate__animated animate__slideInLeft animate__delay-1s" />
    <img src="https://img.shields.io/static/v1?message=Twitter&logo=twitter&label=&color=1DA1F2&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="twitter logo" class="animate__animated animate__slideInLeft animate__delay-2s" />
  </div>

  <h1 align="center" class="animate__animated animate__fadeIn animate__delay-3s">
    ✨ Hello, World! I’m Tahsina Tanvin<br>
    🌟 Dreamer. Creator. Problem-Solver.<br><br>
    I’m a Computer Science and Engineering student passionate about blending creativity with technology to build innovative solutions. From designing seamless user experiences to diving into complex algorithms, I find joy in every step of the development process.
  </h1>

  <h3 align="left" class="animate__animated animate__fadeIn animate__delay-4s">👩‍💻  About Me</h3>

  <p align="left" class="animate__animated animate__fadeIn animate__delay-5s">
    🔭 I’m working as a student and developer, exploring various tech projects and honing my skills in full-stack development.<br>
    📚 I'm currently learning advanced React.js, MongoDB, and Firebase to enhance my project development capabilities.<br>
    ⚡ In my free time, I enjoy exploring new tech tools, watching movies, and contributing to side projects like FeedbackLoop and GadgetHaven.
  </p>

  <h3 align="left" class="animate__animated animate__fadeIn animate__delay-6s">🛠 Language and tools</h3>

  <div align="left">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain-wordmark.svg" height="40" alt="firebase logo" />
    <img width="12" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="html5 logo" />
    <img width="12" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="css3 logo" />
    <img width="12" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original-wordmark.svg" height="40" alt="tailwindcss logo" />
    <img width="12" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo" />
    <img width="12" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" alt="react logo" />
    <img width="12" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" height="40" alt="mongodb logo" />
  </div>

  <h3 align="left" class="animate__animated animate__fadeIn animate__delay-7s">🔥   My Stats :</h3>

  <div align="left">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo" />
    <img width="12" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="typescript logo" />
    <img width="12" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" alt="react logo" />
    <img width="12" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jest/jest-plain.svg" height="40" alt="jest logo" />
    <img width="12" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/storybook/storybook-original.svg" height="40" alt="storybook logo" />
  </div>
</body>
</html>
