<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Netflix Style Resume - Priyanka Rakhonde</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;500;700&display=swap" rel="stylesheet" />
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: #000;
      color: white;
      font-family: 'Roboto', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .resume-container {
      width: 1280px;
      height: 720px; /* 16:9 ratio */
      background: linear-gradient(135deg, #0d0d0d 60%, #e50914);
      display: flex;
      border-radius: 16px;
      box-shadow: 0 0 60px rgba(229, 9, 20, 0.5);
      overflow: hidden;
    }

    .left-panel {
      width: 30%;
      background: #111;
      padding: 20px;
      text-align: center;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .profile-pic {
      width: 180px;
      height: 180px;
      border-radius: 15px;
      object-fit: cover;
      border: 3px solid #e50914;
      margin: 0 auto 20px;
    }

    .name {
      font-size: 22px;
      font-weight: 700;
      color: #fff;
      margin-top: 10px;
    }

    .location {
      font-size: 14px;
      color: #aaa;
      margin-bottom: 10px;
    }

    .contact-info p, .socials a {
      font-size: 14px;
      color: #ccc;
      margin: 6px 0;
    }

    .contact-info i, .socials i {
      color: #e50914;
      margin-right: 6px;
    }

    .socials a {
      text-decoration: none;
      display: inline-block;
      margin: 5px;
    }

    .right-panel {
      width: 70%;
      padding: 30px 40px;
      overflow-y: auto;
    }

    .section {
      margin-bottom: 18px;
    }

    .section h2 {
      color: #e50914;
      font-size: 18px;
      margin-bottom: 8px;
      border-bottom: 1px solid #e50914;
      display: inline-block;
      padding-bottom: 2px;
    }

    .section ul {
      padding-left: 20px;
      font-size: 15px;
    }

    .section ul li {
      margin-bottom: 5px;
    }

    .certificates span {
      display: inline-block;
      background: #e50914;
      color: white;
      padding: 4px 10px;
      border-radius: 5px;
      font-size: 13px;
      margin: 3px;
    }

    .languages i {
      color: #e50914;
      margin-right: 8px;
    }

    /* Scrollbar styling for overflow */
    .right-panel::-webkit-scrollbar {
      width: 8px;
    }

    .right-panel::-webkit-scrollbar-thumb {
      background: #e50914;
      border-radius: 10px;
    }
  </style>
</head>
<body>

  <div class="resume-container">
    
    <!-- Left Panel -->
    <div class="left-panel">
      <div>
        <img src="your-photo.jpg" alt="Priyanka Rakhonde" class="profile-pic" />
        <div class="name">Priyanka Sadanand Rakhonde</div>
        <div class="location"><i class="fas fa-map-marker-alt"></i> Akola, Maharashtra, India</div>
      </div>

      <div class="contact-info">
        <p><i class="fas fa-envelope"></i> priyanka@email.com</p>
        <p><i class="fas fa-phone"></i> +91 98765 43210</p>
        <p><i class="fab fa-linkedin"></i> linkedin.com/in/priyanka</p>
        <p><i class="fab fa-instagram"></i> @priyanka_r</p>
      </div>
    </div>

    <!-- Right Panel -->
    <div class="right-panel">
      
      <div class="section">
        <h2>🎓 Education</h2>
        <ul>
          <li>Currently pursuing BE in IT - College of Engineering & Technology, Akola</li>
          <li>12th - 80%</li>
          <li>10th - 96%</li>
        </ul>
      </div>

      <div class="section">
        <h2>💻 Technical Skills</h2>
        <ul>
          <li>C Programming</li>
          <li>C++</li>
          <li>Java</li>
          <li>Stack Development</li>
          <li>SQL</li>
        </ul>
      </div>

      <div class="section">
        <h2>🧠 Soft Skills</h2>
        <ul>
          <li>Communication</li>
          <li>Leadership</li>
          <li>Teamwork</li>
          <li>Problem Solving</li>
          <li>CR of class for 4 years</li>
        </ul>
      </div>

      <div class="section">
        <h2>📜 Certificates</h2>
        <div class="certificates">
          <span>Googler</span>
          <span>H2O</span>
          <span>Movie Mania</span>
        </div>
      </div>

      <div class="section">
        <h2>🎯 Hobbies & Passion</h2>
        <ul>
          <li>Travelling</li>
          <li>Exploring New Things</li>
          <li>Reading</li>
          <li>Dancing</li>
          <li>Teaching</li>
        </ul>
      </div>

      <div class="section languages">
        <h2>🌐 Languages</h2>
        <p><i class="fas fa-language"></i> English, Hindi, Marathi</p>
      </div>
    </div>

  </div>

</body>
</html># HTML-
I have learn about HTML 
