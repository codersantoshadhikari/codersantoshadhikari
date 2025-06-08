<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Portfolio of Santosh Adhikari, Senior Mobile App Developer and Technical Founder at SMAIT Technology.">
  <meta name="keywords" content="Santosh Adhikari, Mobile App Developer, Flutter, React Native, Unity, SMAIT Technology">
  <meta name="author" content="Santosh Adhikari">
  <title>Santosh Adhikari | Senior Mobile App Developer</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }

    body {
      background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
      color: #333;
      line-height: 1.6;
      padding: 20px;
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
    }

    h1, h2, h3 {
      color: #1a1a1a;
      margin-bottom: 20px;
    }

    h1 {
      font-size: 2.5rem;
      font-weight: 700;
    }

    h2 {
      font-size: 1.8rem;
      font-weight: 600;
    }

    .hero {
      text-align: center;
      padding: 50px 0;
      background: #00C4B4;
      color: white;
      border-radius: 10px;
      margin-bottom: 40px;
      animation: fadeIn 1s ease-in;
    }

    .hero img {
      border-radius: 50%;
      width: 150px;
      height: 150px;
      object-fit: cover;
      margin-bottom: 20px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    }

    .badges, .social-links {
      display: flex;
      gap: 10px;
      justify-content: center;
      flex-wrap: wrap;
      margin: 20px 0;
    }

    .badges a, .social-links a {
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .badges a:hover, .social-links a:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    }

    .section {
      background: white;
      border-radius: 10px;
      padding: 30px;
      margin-bottom: 40px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
      animation: slideIn 0.5s ease-in;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: #f9f9f9;
      padding: 20px;
      border-radius: 8px;
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.15);
    }

    .tech-stack img {
      width: 32px;
      height: 32px;
      margin: 5px;
      transition: transform 0.3s ease;
    }

    .tech-stack img:hover {
      transform: scale(1.2);
    }

    .cta-button {
      display: inline-block;
      padding: 12px 24px;
      background: #FF6F61;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      transition: background 0.3s ease;
    }

    .cta-button:hover {
      background: #e55a4e;
    }

    .footer {
      text-align: center;
      padding: 20px;
      background: #1a1a1a;
      color: white;
      border-radius: 10px;
      margin-top: 40px;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes slideIn {
      from { transform: translateY(20px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    @media (max-width: 768px) {
      h1 { font-size: 2rem; }
      h2 { font-size: 1.5rem; }
      .hero img { width: 120px; height: 120px; }
      .grid { grid-template-columns: 1fr; }
    }

    @media (prefers-color-scheme: dark) {
      body {
        background: linear-gradient(135deg, #2c3e50 0%, #4ca1af 100%);
        color: #e0e0e0;
      }

      h1, h2, h3 { color: #e0e0e0; }
      .section { background: #2c2c2c; }
      .card { background: #3a3a3a; }
      .footer { background: #121212; }
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Hero Section -->
    <div class="hero">
      <img src="https://via.placeholder.com/150" alt="Santosh Adhikari Profile Picture">
      <h1>Santosh Adhikari</h1>
      <h2>Senior Mobile App Developer & Technical Founder</h2>
      <div class="badges">
        <a href="https://santoshadhikari.info.np"><img src="https://img.shields.io/badge/🌐_Portfolio-00C4B4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio"></a>
        <a href="https://play.google.com/store/apps/dev?id=8310692885659472367"><img src="https://img.shields.io/badge/📱_Play_Store-414141?style=for-the-badge&logo=google-play&logoColor=white" alt="Play Store"></a>
        <a href="https://www.smaittechnology.com.np"><img src="https://img.shields.io/badge/🚀_SMAIT_Technology-FF6F61?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Company"></a>
      </div>
    </div>

    <!-- Professional Profile -->
    <div class="section">
      <h2>👨‍💻 Professional Profile</h2>
      <p><strong>Innovative Software Developer</strong> with <strong>6+ years</strong> of specialized experience in mobile application development. As <strong>Founder of SMAIT Technology</strong>, I've led the creation of <strong>60+ applications</strong> with <strong>15+ currently published</strong> on app stores. My passion lies in building technical solutions that bridge digital innovation with real-world impact.</p>
      <h3>Core Competencies:</h3>
      <ul>
        <li>Mobile App Development (Flutter, React Native, Kotlin)</li>
        <li>Full-Stack Development (Node.js, Firebase, MongoDB)</li>
        <li>Game Development (Unity, Ludo Game Specialist)</li>
        <li>Ethical Hacking & Security (MBA–

Certified)</li>
        <li>Startup Leadership & Technical Management</li>
      </ul>
    </div>

    <!-- Key Achievements -->
    <div class="section">
      <h2>🏆 Key Achievements</h2>
      <div class="grid">
        <div class="card">
          <h3>🚀 Published Applications</h3>
          <p>Developed <strong>60+ applications</strong>, with <strong>15+ live</strong> on Play Store/App Store. Featured <strong>Ludo gaming application</strong> with 10K+ downloads.</p>
        </div>
        <div class="card">
          <h3>🎓 Education & Certification</h3>
          <p><strong>MBA in Ethical Hacking</strong> - Cybersecurity Specialization. Certified in <strong>Flutter</strong> and <strong>React Native</strong>. Committed to continuous learning in emerging technologies.</p>
        </div>
        <div class="card">
          <h3>🏢 SMAIT Technology</h3>
          <p>Founded and scaled a tech startup focused on innovating games, apps, and software solutions, building a smarter digital world.</p>
        </div>
      </div>
    </div>

    <!-- Featured Project -->
    <div class="section">
      <h2>🎮 Featured Project: Ludo Game</h2>
      <a href="https://play.google.com/store/apps/details?id=np.smaittechnology.ludo"><img src="https://img.shields.io/badge/🎮_Ludo_Game-FF6F61?style=for-the-badge&logo=google-play&logoColor=white" alt="Ludo Game"></a>
      <p><strong>Key Features:</strong></p>
      <ul>
        <li>Multiplayer online gameplay</li>
        <li>Smooth 60FPS performance</li>
        <li>Secure authentication system</li>
        <li>Real-time matchmaking</li>
      </ul>
      <p><strong>Technologies Used:</strong> Unity, Firebase Realtime Database, Google Play Services, In-app Purchases</p>
    </div>

    <!-- Technical Stack -->
    <div class="section">
      <h2>🛠️ Technical Stack</h2>
      <div class="grid tech-stack">
        <div><img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="Flutter"> Flutter</div>
        <div><img src="https://reactnative.dev/img/header_logo.svg" alt="React Native"> React Native</div>
        <div><img src="https://www.vectorlogo.zone/logos/kotlinlang/kotlinlang-icon.svg" alt="Kotlin"> Kotlin</div>
        <div><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/unity/unity-original.svg" alt="Unity"> Unity</div>
        <div><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="C#"> C#</div>
        <div><img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="Firebase"> Firebase</div>
        <div><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js"> Node.js</div>
        <div><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" alt="MongoDB"> MongoDB</div>
        <div><img src="https://img.shields.io/badge/Ethical_Hacking-FF6F61?style=flat-square&logo=lock&logoColor=white" alt="Ethical Hacking"> Ethical Hacking</div>
      </div>
    </div>

    <!-- Why Work With Me -->
    <div class="section">
      <h2>🌟 Why Work With Me?</h2>
      <ul>
        <li><strong>Proven Track Record:</strong> 60+ successful applications</li>
        <li><strong>Full-Cycle Development:</strong> From concept to publication</li>
        <li><strong>Security-Focused:</strong> MBA in Ethical Hacking ensures secure apps</li>
        <li><strong>User-Centric Design:</strong> Apps with high retention rates</li>
        <li><strong>Technical Leadership:</strong> Founder managing development teams</li>
      </ul>
    </div>

    <!-- Let's Connect -->
    <div class="section">
      <h2>📬 Let's Connect</h2>
      <p>I'm always open to discussing new projects, creative ideas, or opportunities to collaborate.</p>
      <div class="social-links">
        <a href="mailto:santosh.ad215@gmail.com"><img src="https://img.shields.io/badge/✉️_Email-FF6F61?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
        <a href="https://www.linkedin.com/in/santosh-adhikari-b24324265/"><img src="https://img.shields.io/badge/💼_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
        <a href="https://play.google.com/store/apps/dev?id=8310692885659472367"><img src="https://img.shields.io/badge/📱_Play_Store-414141?style=for-the-badge&logo=google-play&logoColor=white" alt="Play Store"></a>
        <a href="https://x.com/santosh215"><img src="https://img.shields.io/badge/🐦_X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"></a>
        <a href="https://www.instagram.com/codersantoshadhikari/"><img src="https://img.shields.io/badge/📸_Instagram-F35369?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a>
      </div>
    </div>

    <!-- Support Me -->
    <div class="section">
      <h2>❤️ Support Me</h2>
      <div class="grid">
        <a href="https://www.buymeacoffee.com/santosh215" class="cta-button">Buy Me a Coffee</a>
        <a href="https://www.ko-fi.com/santosh215" class="cta-button">Support on Ko-fi</a>
      </div>
    </div>

    <!-- Footer -->
    <div class="footer">
      <p>&copy; 2025 Santosh Adhikari. All rights reserved.</p>
    </div>
  </div>
</body>
</html>
