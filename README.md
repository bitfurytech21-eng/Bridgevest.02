<svg width="100" height="100" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
  <rect width="100" height="100" fill="#0d0f1a"/>
  <text x="50%" y="55%" font-size="40" fill="#00bfff" font-family="Arial" text-anchor="middle">B</text>
</svg>
<!-- login.html --><!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bridgevest Login</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <div class="auth-container">
    <h2>Login to Bridgevest</h2>
    <form>
      <input type="email" placeholder="Email" required>
      <input type="password" placeholder="Password" required>
      <button class="btn" type="submit">Login</button>
    </form>
    <p>Don't have an account? <a href="signup.html">Sign up</a></p>
  </div>
</body>
</html><!-- signup.html --><!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bridgevest Sign Up</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <div class="auth-container">
    <h2>Create Your Account</h2>
    <form>
      <input type="text" placeholder="Full Name" required>
      <input type="email" placeholder="Email" required>
      <input type="password" placeholder="Password" required>
      <button class="btn" type="submit">Sign Up</button>
    </form>
    <p>Already have an account? <a href="login.html">Login</a></p>
  </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bridgevest | Your Bridge to Smarter Crypto Investing</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;500;700&display=swap');
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: #0a0a0f;
      color: #e5e5e5;
      line-height: 1.6;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 60px;
      background: rgba(10, 10, 15, 0.9);
      border-bottom: 1px solid rgba(0, 255, 255, 0.15);
    }
    header h1 {
      color: #00baff;
      font-weight: 700;
      letter-spacing: 1px;
    }
    nav a {
      color: #e5e5e5;
      text-decoration: none;
      margin: 0 15px;
      font-weight: 500;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #00baff;
    }
    .hero {
      text-align: center;
      padding: 120px 20px;
      background: linear-gradient(180deg, #0a0a0f 0%, #08121a 100%);
    }
    .hero h2 {
      font-size: 2.8rem;
      color: #00baff;
      margin-bottom: 20px;
    }
    .hero p {
      max-width: 650px;
      margin: 0 auto 40px;
      color: #b0b0b0;
      font-size: 1.1rem;
    }
    .cta-btn {
      background: #00baff;
      color: #0a0a0f;
      border: none;
      padding: 14px 40px;
      font-size: 1rem;
      font-weight: 600;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s;
    }
    .cta-btn:hover {
      background: #0092cc;
    }
    section {
      padding: 80px 20px;
      max-width: 1100px;
      margin: auto;
    }
    section h3 {
      color: #00baff;
      font-size: 2rem;
      margin-bottom: 20px;
    }
    .features, .how-it-works {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
    }
    .feature-box {
      background: #11151d;
      border-radius: 10px;
      padding: 30px;
      border: 1px solid rgba(0, 255, 255, 0.1);
      transition: transform 0.3s;
    }
    .feature-box:hover {
      transform: translateY(-5px);
      border-color: #00baff;
    }
    footer {
      text-align: center;
      padding: 40px;
      border-top: 1px solid rgba(0, 255, 255, 0.1);
      color: #888;
      font-size: 0.9rem;
    }
    @media(max-width: 768px) {
      header {
        flex-direction: column;
        padding: 20px;
      }
      nav {
        margin-top: 10px;
      }
      .hero h2 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Bridgevest</h1>
    <nav>
      <a href="#how">How It Works</a>
      <a href="#features">Features</a>
      <a href="#why">Why Nigeria</a>
      <a href="#faq">FAQ</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Your Bridge to Smarter Crypto Investing</h2>
    <p>Bridgevest simplifies DeFi trading with AI-powered automation, smart contracts, and copy trading tools built on Solana — giving you secure, effortless crypto earnings.</p>
    <button class="cta-btn" onclick="scrollToLearn()">Learn More</button>
  </section>

  <section id="how">
    <h3>How Bridgevest Works</h3>
    <div class="how-it-works">
      <div class="feature-box">
        <h4>AI Trading Agents</h4>
        <p>Our AI agents analyze real-time market data, predict profitable trends, and execute trades automatically based on your preferences.</p>
      </div>
      <div class="feature-box">
        <h4>Smart Contracts</h4>
        <p>Bridgevest’s Solana-based smart contracts keep your funds secure and auditable — ensuring only you control your assets.</p>
      </div>
      <div class="feature-box">
        <h4>Time-Lock Security</h4>
        <p>Every contract modification includes a 72-hour time lock for added transparency and protection against unauthorized actions.</p>
      </div>
    </div>
  </section>

  <section id="features">
    <h3>Key Features</h3>
    <div class="features">
      <div class="feature-box">
        <h4>Copy Trading</h4>
        <p>Follow and replicate the strategies of top-performing investors effortlessly to boost your potential returns.</p>
      </div>
      <div class="feature-box">
        <h4>Profit Forecasting</h4>
        <p>AI-driven forecasting tools help you understand potential outcomes and stay ahead of market shifts.</p>
      </div>
      <div class="feature-box">
        <h4>User-Friendly Interface</h4>
        <p>Designed for all experience levels, Bridgevest’s intuitive dashboard simplifies complex trading decisions.</p>
      </div>
    </div>
  </section>

  <section id="why">
    <h3>Why Bridgevest for Nigerians</h3>
    <p>Nigeria is one of the fastest-growing crypto markets. Bridgevest provides a safe, automated, and transparent trading platform that fits perfectly into your busy lifestyle — allowing your investments to grow while you focus on what matters most.</p>
  </section>

  <section id="faq">
    <h3>Frequently Asked Questions</h3>
    <p><strong>Q:</strong> Do I need to monitor trades constantly?<br><strong>A:</strong> No, your AI agent handles trades automatically while keeping you informed of results.</p>
    <p><strong>Q:</strong> Are my funds secure?<br><strong>A:</strong> Yes, thanks to Solana smart contracts and time-lock features.</p>
  </section>

  <section id="contact">
    <h3>Contact & Support</h3>
    <p>Need assistance? Reach us at <a href="mailto:support@bridgevest.io" style="color:#00baff;">support@bridgevest.io</a></p>
  </section>

  <footer>
    © 2025 Bridgevest. All rights reserved. | Built on Solana Blockchain
  </footer>

  <script>
    function scrollToLearn() {
      document.querySelector("#how").scrollIntoView({ behavior: 'smooth' });
    }
  </script>
</body>
</html>
