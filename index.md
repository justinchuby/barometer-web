---
layout: default
title: Barometer for Watch
---

<style>
  .hero {
    text-align: center;
    padding: 60px 20px;
    background: linear-gradient(135deg, #eb863b 0%, #d4622a 50%, #b84a1c 100%);
    border-radius: 20px;
    margin: 20px 0;
    color: white;
  }

  .hero h1 {
    font-size: 3rem;
    margin-bottom: 10px;
    font-weight: 700;
  }

  .hero .tagline {
    font-size: 1.3rem;
    opacity: 0.9;
    margin-bottom: 30px;
  }

  .app-icon {
    width: 120px;
    height: 120px;
    border-radius: 26px;
    margin-bottom: 20px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.3);
  }

  .links-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    margin: 40px 0;
  }

  .link-card {
    background: white;
    border-radius: 16px;
    padding: 30px;
    width: 280px;
    box-shadow: 0 4px 20px rgba(0,0,0,0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    text-decoration: none;
    color: inherit;
  }

  .link-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 30px rgba(235,134,59,0.3);
  }

  .link-card .icon {
    font-size: 2.5rem;
    margin-bottom: 15px;
  }

  .link-card h3 {
    margin: 0 0 10px 0;
    color: #eb863b;
    font-size: 1.3rem;
  }

  .link-card p {
    margin: 0;
    color: #666;
    font-size: 0.95rem;
    line-height: 1.5;
  }

  .appstore-badge {
    display: inline-block;
    margin-top: 20px;
  }

  .appstore-badge img {
    height: 50px;
  }

  .footer {
    text-align: center;
    padding: 40px 20px;
    color: #888;
    font-size: 0.9rem;
  }

  .footer a {
    color: #eb863b;
    text-decoration: none;
  }

  .footer a:hover {
    text-decoration: underline;
  }

  @media (max-width: 600px) {
    .hero h1 {
      font-size: 2rem;
    }
    .link-card {
      width: 100%;
    }
  }
</style>

<div class="hero">
  <img src="icon.png" alt="Barometer App Icon" class="app-icon">
  <h1>Barometer for Watch</h1>
  <p class="tagline">Atmospheric pressure right on your wrist</p>
  <a href="https://apps.apple.com/us/app/barometer-for-watch/id1448485995" class="appstore-badge">
    <img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store">
  </a>
</div>

<div class="links-container">
  <a href="https://barometer.justinchuby.com/feedback" class="link-card">
    <div class="icon">💬</div>
    <h3>Send Feedback</h3>
    <p>Have suggestions or questions? We'd love to hear from you. Share your thoughts and help us improve.</p>
  </a>

  <a href="https://github.com/justinchuby/barometer-project/issues" class="link-card">
    <div class="icon"><svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 24 24" fill="#333"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/></svg></div>
    <h3>Report Issues on GitHub</h3>
    <p>You can also open an issue on GitHub for bugs and feature requests.</p>
  </a>
</div>

<div class="footer">
  <p>Made with ❤️ for Apple Watch users</p>
  <p><a href="/privacy-policy">Privacy Policy</a></p>
</div>
