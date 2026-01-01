<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>MODREN AGE SYMBOL</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0f172a;
      color: white;
      text-align: center;
    }

    section {
      padding: 60px 20px;
    }

   h1 {
  font-size: 38px;
  margin-bottom: 10px;
  letter-spacing: 3px;
}

    h2 {
      margin-bottom: 15px;
    }

    p {
      max-width: 600px;
      margin: auto;
      line-height: 1.6;
      color: #d1d5db;
    }

    .team p {
      margin: 8px 0;
    }

    footer {
      background: #020617;
      padding: 20px;
      font-size: 14px;
      color: #9ca3af;
    }
    .logo {
  font-size: 64px;
  font-weight: bold;
  letter-spacing: 6px;
  color: #38bdf8;
  margin-bottom: 10px;
}nav {
  display: flex;
  align-items: center;
  padding: 15px 30px;
  background: #020617;
}

.nav-logo {
  font-size: 22px;
  font-weight: bold;
  color: #38bdf8;
  letter-spacing: 3px;
}

/* Hero */
.hero {
  padding: 80px 20px;
}

/* Logo Circle */
.logo-circle {
  width: 150px;
  height: 150px;
  margin: 0 auto 25px;
  border-radius: 50%;

  /* Glass + Glow */
  background: rgba(56, 189, 248, 0.1);
  backdrop-filter: blur(10px);
  border: 2px solid rgba(56, 189, 248, 0.8);
  box-shadow:
    0 0 25px rgba(56, 189, 248, 0.6),
    0 0 60px rgba(56, 189, 248, 0.4);

  display: flex;
  align-items: center;
  justify-content: center;

  font-size: 48px;
  font-weight: bold;
  letter-spacing: 8px;
  color: #38bdf8;

  transition: all 0.4s ease;
  animation: pulse 3s infinite;
}.logo-circle:hover {
  transform: scale(1.1) rotate(2deg);
  color: #ffffff;
  box-shadow:
    0 0 40px rgba(56, 189, 248, 1),
    0 0 90px rgba(56, 189, 248, 0.9);
}
@keyframes pulse {
  0% {
    box-shadow:
      0 0 20px rgba(56, 189, 248, 0.4),
      0 0 40px rgba(56, 189, 248, 0.2);
  }
  50% {
    box-shadow:
      0 0 40px rgba(56, 189, 248, 0.9),
      0 0 80px rgba(56, 189, 248, 0.6);
  }
  100% {
    box-shadow:
      0 0 20px rgba(56, 189, 248, 0.4),
      0 0 40px rgba(56, 189, 248, 0.2);
  }
}
/* Animation */
@keyframes float {
  0% { transform: translateY(0); }
  50% { transform: translateY(-8px); }
  100% { transform: translateY(0); }
}
  </style>
</head>

<body>
<nav>
  <div class="nav-logo">MAS</div>
</nav>
  <!-- Hero -->
 <section class="hero">
  <div class="logo-circle">MAS</div>
  <h1>MODREN AGE SYMBOL</h1>
  <p>Shaping the future of modern technology</p>
</section>

  <!-- About -->
  <section>
    <h2>Who We Are</h2>
    <p>
      We are a young tech-oriented group driven by innovation and creativity.
      Our goal is to build modern ideas and solutions that shape the future.
    </p>
  </section>

  <!-- Vision -->
  <section>
    <h2>Our Vision</h2>
    <p>
      To create modern technology projects that combine simplicity,
      creativity, and real impact.
    </p>
  </section>

  <!-- Team -->
  <section class="team">
    <h2>Our Team</h2>
    <p>Founder / Team Lead</p>
    <p>Developer</p>
    <p>Designer</p>
    <p>Tech Support</p>
    <p>Content & Ideas</p>
  </section>

  <!-- Contact -->
  <section>
    <h2>Contact</h2>
    <p>contact@modrenagesymbol.com</p>
    <p>Coming Soon</p>
  </section>

  <footer>
    © 2026 MODREN AGE SYMBOL — All rights reserved
  </footer>

</body>
</html>
