<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Air Algérie Virtual</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="icon" type="image/png" href="https://cdn.discordapp.com/attachments/1377572968766636084/1378723450352570408/IMG_1513.png?ex=68498146&is=68482fc6&hm=765d245a39ec43facee5887a97831bb2b81dbdee74d55dbeca063f38a5caeaf3&">
  <style>
    :root {
      --primary: #D10000;
      --background: #f9f9f9;
      --foreground: #111;
      --card: #fff;
      --muted: #666;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
      background: var(--background);
      color: var(--foreground);
      line-height: 1.6;
    }

    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background: #ffffffcc;
      backdrop-filter: blur(8px);
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 2rem;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
      z-index: 1000;
    }

    nav .logo {
      font-size: 1.5rem;
      font-weight: 700;
      color: var(--primary);
    }

    nav .menu a {
      margin-left: 1.5rem;
      color: var(--foreground);
      text-decoration: none;
      font-weight: 500;
    }

    header {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: linear-gradient(to right, #ffffff, #f3f3f3);
      text-align: center;
      padding: 0 1rem;
    }

    header h1 {
      font-size: 3rem;
      color: var(--primary);
    }

    header p {
      font-size: 1.2rem;
      color: var(--muted);
      margin-top: 0.5rem;
      max-width: 600px;
    }

    .hero-buttons {
      margin-top: 2rem;
    }

    .hero-buttons a {
      display: inline-block;
      margin: 0 0.5rem;
      padding: 0.9rem 1.8rem;
      border-radius: 8px;
      background: var(--primary);
      color: #fff;
      font-weight: 600;
      text-decoration: none;
      transition: all 0.3s ease;
    }

    .hero-buttons a:hover {
      background: #a90000;
    }

    main {
      max-width: 1100px;
      margin: auto;
      padding: 4rem 1rem;
    }

    section {
      margin-bottom: 4rem;
    }

    section h2 {
      font-size: 2rem;
      color: var(--primary);
      margin-bottom: 1rem;
      text-align: center;
    }

    .card {
      background: var(--card);
      padding: 2rem;
      border-radius: 1rem;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
      max-width: 900px;
      margin: auto;
      text-align: center;
    }

    .login-buttons {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 1rem;
      margin-top: 2rem;
    }

    .login-buttons a {
      display: inline-block;
      padding: 0.8rem 1.6rem;
      border-radius: 8px;
      font-weight: 600;
      text-decoration: none;
      color: white;
      transition: all 0.3s ease;
    }

    .discord-login { background: #5865F2; }
    .google-login { background: #DB4437; }
    .roblox-login { background: #1B1B1B; }

    .discord-login:hover { background: #4a54d1; }
    .google-login:hover { background: #c33c2f; }
    .roblox-login:hover { background: #000; }

    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: var(--muted);
      background: #f1f1f1;
    }

    footer a {
      color: var(--primary);
      text-decoration: none;
    }
  </style>
</head>
<body>
  <nav>
    <div class="logo">
      Air Algérie Virtual
          <img src="https://cdn.discordapp.com/attachments/1377572968766636084/1378723450352570408/IMG_1513.png?ex=68498146&is=68482fc6&hm=765d245a39ec43facee5887a97831bb2b81dbdee74d55dbeca063f38a5caeaf3&" alt="Air Algérie Logo" style="height: 100px; vertical-align: middle;">
    </div>
    <div class="menu">
      <a href="https://pfairalgerie.github.io/about-us">About us</a>
      <a href="https://docs.google.com/forms/d/e/1FAIpQLSeSU6jRU8JJxhzyL3fPdLJoVWvxGWTxCGp31fw0HexZLQc0TQ/viewform?usp=header">Become a Pilot</a>
      <a href="mailto:pfairalgerievirtual@gmail.com">Contact</a>
        <a href="https://discord.gg/ZmpVNbRecK" target="_blank">Discord</a>
        <a href="https://pfairalgerie.github.io/rules/" targer="_blank">Server's Rules</a>
    </div>
  </nav>

  <header>
    <h1>Welcome to Air Algérie Virtual</h1>
    <p>Experience the skies of Algeria in the most immersive and professional way possible. Join our virtual airline and take flight with purpose.</p>
    <div class="hero-buttons">
      <a href="https://discord.gg/ZmpVNbRecK" target="_blank">Join Discord</a>
      <a href="https://docs.google.com/forms/d/e/1FAIpQLSeSU6jRU8JJxhzyL3fPdLJoVWvxGWTxCGp31fw0HexZLQc0TQ/viewform?usp=header">Apply Now</a>
    </div>
  </header>

  <main>
    <section id="about">
      <h2>About Us</h2>
      <div class="card">
        <p>Air Algérie Virtual replicates the real-world operations of Algeria's national airline on Roblox. We offer a high-quality experience with a realistic fleet, scheduled flights, and a vibrant pilot community.</p>
      </div>
    </section>

    <section id="apply">
      <h2>Pilot Recruitment</h2>
      <div class="card">
        <p>We’re looking for dedicated and passionate virtual pilots. Join our team to get access to training, events, and exclusive pilot resources.</p>
        <p style="margin-top: 1.5rem;"><a href="https://docs.google.com/forms/d/e/1FAIpQLSeSU6jRU8JJxhzyL3fPdLJoVWvxGWTxCGp31fw0HexZLQc0TQ/viewform?usp=header" style="background: var(--primary); color: white; padding: 0.8rem 1.5rem; border-radius: 10px; text-decoration: none;">Apply Now For Pilot !</a></p>
      </div>
    </section>
      </div>
    </section>
  </main>

  <footer>
    <p>Contact us at <a href="mailto:pfairalgerievirtual@gmail.com">pfairalgerievirtual@gmail.com</a> — <a href="https://discord.gg/ZmpVNbRecK">Join Discord</a></p>
    <p>&copy; 2025 Air Algérie Virtual- All Right Reserved</p>
  </footer>
</body>
</html>
