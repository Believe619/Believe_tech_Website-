<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Believe Tech | Website Design</title>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  background: #07111f;
  color: white;
  min-height: 100vh;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 22px 8%;
  background: #0b1728;
  border-bottom: 1px solid #1c3048;
}

.logo {
  font-size: 24px;
  font-weight: bold;
  color: #58a6ff;
}

nav a {
  color: white;
  text-decoration: none;
  margin-left: 20px;
}

.hero {
  min-height: 85vh;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 40px;
  padding: 60px 8%;
}

.text {
  max-width: 600px;
}

.text h1 {
  font-size: clamp(42px, 7vw, 75px);
  line-height: 1.05;
  margin-bottom: 20px;
}

.text h1 span {
  color: #58a6ff;
}

.text p {
  font-size: 20px;
  color: #b8c7d9;
  margin-bottom: 30px;
}

.typing {
  color: #58a6ff;
  font-size: 24px;
  font-weight: bold;
  border-right: 3px solid #58a6ff;
  white-space: nowrap;
  overflow: hidden;
  width: 0;
  animation: typing 4s steps(30) infinite alternate,
             blink .7s infinite;
}

@keyframes typing {
  from { width: 0; }
  to { width: 100%; }
}

@keyframes blink {
  50% { border-color: transparent; }
}

.buttons a {
  display: inline-block;
  padding: 14px 25px;
  margin-right: 10px;
  border-radius: 30px;
  text-decoration: none;
  font-weight: bold;
  background: #58a6ff;
  color: #07111f;
}

.buttons a:last-child {
  background: transparent;
  border: 1px solid #58a6ff;
  color: white;
}

/* PERSON WRITING */

.scene {
  width: 360px;
  height: 390px;
  position: relative;
  flex-shrink: 0;
}

.person {
  position: absolute;
  left: 105px;
  top: 45px;
  width: 150px;
  height: 230px;
}

/* head */
.head {
  position: absolute;
  left: 48px;
  top: 0;
  width: 70px;
  height: 75px;
  background: #d99b70;
  border-radius: 50%;
  z-index: 3;
}

/* hair */
.hair {
  position: absolute;
  left: 43px;
  top: -7px;
  width: 80px;
  height: 45px;
  background: #20252d;
  border-radius: 50% 50% 35% 35%;
  z-index: 4;
}

/* body */
.body {
  position: absolute;
  left: 25px;
  top: 65px;
  width: 120px;
  height: 135px;
  background: #2878d0;
  border-radius: 35px 35px 10px 10px;
  z-index: 2;
}

/* arm */
.arm {
  position: absolute;
  width: 105px;
  height: 25px;
  background: #d99b70;
  border-radius: 20px;
  top: 120px;
  left: 5px;
  transform: rotate(25deg);
  transform-origin: right center;
  z-index: 5;
  animation: writing 0.7s infinite alternate ease-in-out;
}

@keyframes writing {
  from { transform: rotate(22deg); }
  to { transform: rotate(32deg); }
}

/* hand */
.hand {
  position: absolute;
  width: 22px;
  height: 22px;
  background: #d99b70;
  border-radius: 50%;
  top: 142px;
  left: -3px;
  z-index: 6;
}

/* desk */
.desk {
  position: absolute;
  bottom: 75px;
  left: 20px;
  width: 320px;
  height: 25px;
  background: #8b5a35;
  border-radius: 8px;
}

/* laptop */
.laptop {
  position: absolute;
  bottom: 100px;
  left: 110px;
  width: 150px;
  height: 90px;
  background: #172536;
  border: 6px solid #52677e;
  border-radius: 8px;
  transform: perspective(300px) rotateX(-8deg);
}

.screen-text {
  color: #58a6ff;
  font-size: 13px;
  padding: 15px 10px;
  line-height: 1.4;
}

/* chair */
.chair {
  position: absolute;
  bottom: 55px;
  left: 75px;
  width: 210px;
  height: 25px;
  background: #26384e;
  border-radius: 20px;
}

.glow {
  position: absolute;
  width: 280px;
  height: 280px;
  left: 40px;
  top: 40px;
  border-radius: 50%;
  background: #1677ff;
  opacity: .12;
  filter: blur(40px);
}

footer {
  text-align: center;
  padding: 25px;
  color: #71849b;
}

@media (max-width: 800px) {

  header {
    padding: 20px;
  }

  nav {
    display: none;
  }

  .hero {
    flex-direction: column;
    text-align: center;
    padding: 45px 20px;
  }

  .text {
    width: 100%;
  }

  .typing {
    margin: auto;
    font-size: 19px;
  }

  .scene {
    transform: scale(.85);
    margin-top: -10px;
  }

  .buttons a {
    margin-bottom: 10px;
  }
}
</style>
</head>

<body>

<header>
  <div class="logo">Believe Tech</div>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero" id="home">

  <div class="text">

    <div class="typing">
      Welcome to Believe Tech
    </div>

    <h1>
      We Build <span>Digital</span> Ideas.
    </h1>

    <p>
      Creative website design, technology and digital solutions
      made with passion.
    </p>

    <div class="buttons">
      <a href="#about">Explore</a>
      <a href="#contact">Contact Me</a>
    </div>

  </div>

  <div class="scene">

    <div class="glow"></div>

    <div class="person">

      <div class="hair"></div>
      <div class="head"></div>
      <div class="body"></div>

      <div class="arm"></div>
      <div class="hand"></div>

    </div>

    <div class="laptop">
      <div class="screen-text">
        &gt; Believe Tech<br>
        &gt; Creating...<br>
        &gt; Website Ready_
      </div>
    </div>

    <div class="desk"></div>
    <div class="chair"></div>

  </div>

</section>

<section id="about" style="padding:70px 8%; text-align:center;">
  <h2 style="font-size:40px; margin-bottom:15px;">
    About Believe Tech
  </h2>

  <p style="color:#b8c7d9; font-size:18px;">
    We turn ideas into beautiful digital experiences.
  </p>
</section>

<section id="contact" style="padding:70px 8%; text-align:center;">
  <h2 style="font-size:40px; margin-bottom:15px;">
    Let's Work Together
  </h2>

  <p style="color:#b8c7d9; font-size:18px;">
    Have an idea? Believe it. Build it.
  </p>
</section>

<footer>
  © 2026 Believe Tech. All rights reserved.
</footer>

</body>
</html>
