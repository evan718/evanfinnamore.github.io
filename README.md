<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home | Evan Finnamore Counselling Services</title>
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;500;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary-color: #4A90E2;
      --secondary-color: #67B26F;
      --text-color: #2C3E50;
      --background-color: #F8FAFC;
      --accent-light: #E3F2FD;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Open Sans', sans-serif;
      line-height: 1.6;
      color: var(--text-color);
      background-color: var(--background-color);
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 20px;
    }

    header {
      background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
      color: white;
      padding: 1rem 0;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }

    header h1 {
      margin-bottom: 1rem;
      font-size: 2rem;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 2rem;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: 500;
      transition: opacity 0.3s ease;
    }

    nav a:hover {
      opacity: 0.8;
    }

    main {
      padding: 3rem 0;
    }

    .hero-section {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 4rem;
      align-items: center;
      margin-bottom: 4rem;
    }

    .hero-content h2 {
      font-size: 2.5rem;
      margin-bottom: 1.5rem;
      color: var(--primary-color);
    }

    .hero-content p {
      font-size: 1.1rem;
      margin-bottom: 2rem;
      color: var(--text-color);
    }

    .cta-button {
      display: inline-block;
      padding: 1rem 2rem;
      background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
      color: white;
      text-decoration: none;
      border-radius: 30px;
      font-weight: 500;
      transition: transform 0.3s ease;
    }

    .cta-button:hover {
      transform: translateY(-2px);
    }

    .features {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 2rem;
      margin-top: 4rem;
    }

    .feature-card {
      background: white;
      padding: 2rem;
      border-radius: 10px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      text-align: center;
    }

    .feature-icon {
      width: 60px;
      height: 60px;
      margin-bottom: 1rem;
    }

    footer {
      background-color: var(--text-color);
      color: white;
      padding: 2rem 0;
      margin-top: 4rem;
    }

    @media (max-width: 768px) {
      .hero-section {
        grid-template-columns: 1fr;
        text-align: center;
      }

      .features {
        grid-template-columns: 1fr;
      }

      nav ul {
        flex-direction: column;
        gap: 1rem;
        text-align: center;
      }
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <div class="container">
      <h1>Evan Finnamore Counselling Services</h1>
      <nav>
        <ul>
          <li><a href="./index.html">Home</a></li>
          <li><a href="./about.html">About Me</a></li>
          <li><a href="./services.html">Services</a></li>
          <li><a href="./appointment.html">Book Appointment</a></li>
          <li><a href="./links.html">Useful Links</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Main Content -->
  <main>
    <div class="container">
      <section class="hero-section">
        <div class="hero-content">
          <h2>Begin Your Journey to Wellbeing</h2>
          <p>Welcome to a safe and supportive space where you can explore your thoughts, feelings, and experiences. I'm here to help you navigate life's challenges and discover your path to personal growth and emotional wellness.</p>
          <a href="./appointment.html" class="cta-button">Book Your Session</a>
        </div>
        <div class="hero-image">
          <svg viewBox="0 0 400 300" xmlns="http://www.w3.org/2000/svg">
            <!-- Calming Nature Scene -->
            <defs>
              <linearGradient id="skyGradient" x1="0%" y1="0%" x2="0%" y2="100%">
                <stop offset="0%" style="stop-color:#87CEEB;stop-opacity:1" />
                <stop offset="100%" style="stop-color:#E0F7FA;stop-opacity:1" />
              </linearGradient>
              <linearGradient id="sunGradient" x1="0%" y1="0%" x2="100%" y2="100%">
                <stop offset="0%" style="stop-color:#FFD700;stop-opacity:1" />
                <stop offset="100%" style="stop-color:#FFA726;stop-opacity:1" />
              </linearGradient>
            </defs>
            
            <!-- Sky -->
            <rect width="400" height="300" fill="url(#skyGradient)" />
            
            <!-- Sun -->
            <circle cx="300" cy="80" r="40" fill="url(#sunGradient)" />
            
            <!-- Mountains -->
            <path d="M0 150 L150 50 L300 150 L400 100 L400 300 L0 300 Z" fill="#67B26F" opacity="0.8" />
            <path d="M0 200 L200 100 L400 200 L400 300 L0 300 Z" fill="#4A90E2" opacity="0.6" />
            
            <!-- Trees -->
            <g transform="translate(50,150)">
              <rect x="-5" y="0" width="10" height="30" fill="#5D4037" />
              <path d="M-20 0 L0 -30 L20 0 Z" fill="#67B26F" />
            </g>
            <g transform="translate(100,170)">
              <rect x="-5" y="0" width="10" height="30" fill="#5D4037" />
              <path d="M-20 0 L0 -30 L20 0 Z" fill="#4A90E2" />
            </g>
            
            <!-- Peaceful Lake -->
            <path d="M0 220 Q200 200 400 220 L400 300 L0 300 Z" fill="#4A90E2" opacity="0.3" />
          </svg>
        </div>
      </section>

      <section class="features">
        <div class="feature-card">
          <svg class="feature-icon" viewBox="0 0 60 60" xmlns="http://www.w3.org/2000/svg">
            <circle cx="30" cy="30" r="25" fill="#E3F2FD" />
            <path d="M20 30 L25 35 L40 20" stroke="#4A90E2" stroke-width="3" fill="none" />
          </svg>
          <h3>Safe Space</h3>
          <p>A confidential and judgment-free environment for your personal growth journey.</p>
        </div>
        <div class="feature-card">
          <svg class="feature-icon" viewBox="0 0 60 60" xmlns="http://www.w3.org/2000/svg">
            <circle cx="30" cy="30" r="25" fill="#E3F2FD" />
            <path d="M30 15 L30 45 M15 30 L45 30" stroke="#67B26F" stroke-width="3" />
          </svg>
          <h3>Professional Support</h3>
          <p>Evidence-based therapeutic approaches tailored to your unique needs.</p>
        </div>
        <div class="feature-card">
          <svg class="feature-icon" viewBox="0 0 60 60" xmlns="http://www.w3.org/2000/svg">
            <circle cx="30" cy="30" r="25" fill="#E3F2FD" />
            <path d="M20 35 Q30 20 40 35" stroke="#4A90E2" stroke-width="3" fill="none" />
          </svg>
          <h3>Personal Growth</h3>
          <p>Develop skills and insights to navigate life's challenges with confidence.</p>
        </div>
      </section>
    </div>
  </main>

  <!-- Footer -->
  <footer>
    <div class="container">
      <p>&copy; 2024 Evan Finnamore Counselling Services. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>
