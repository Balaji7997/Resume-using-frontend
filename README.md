<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>KODIPALLI BALAJI - Resume</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Arial, sans-serif;
      transition: background-color 0.3s ease;
    }

    body {
      background-color: #87CEEB;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 20px;
    }

    body.dark-mode {
      background-color: #000;
    }

    .resume-container {
      background-color: white;
      max-width: 800px;
      width: 100%;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }

    .header-container {
      display: flex;
      justify-content: space-between;
      align-items: flex-start;
      margin-bottom: 20px;
      flex-wrap: wrap;
    }

    .profile-pic {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #f0f0f0;
      box-shadow: 0 3px 10px rgba(0,0,0,0.1);
    }

    h1 {
      color: #87CEEB;
      margin-bottom: 8px;
      font-size: 28px;
      font-weight: 600;
    }

    h2 {
      color: #87CEEB;
      margin: 25px 0 12px 0;
      padding-bottom: 5px;
      border-bottom: 2px solid #f0f0f0;
      font-size: 20px;
      font-weight: 500;
    }

    .contact-info {
      margin-bottom: 5px;
      font-size: 14px;
      color: #555;
    }

    ul {
      margin-left: 20px;
    }

    li {
      margin-bottom: 8px;
      line-height: 1.5;
      color: #333;
    }

    p {
      margin-bottom: 15px;
      color: #333;
    }

    a {
      color: #3a7bd5;
      text-decoration: none;
      font-weight: 500;
    }

    a:hover {
      text-decoration: underline;
    }

    .theme-toggle {
      position: fixed;
      bottom: 20px;
      right: 20px;
      padding: 10px 15px;
      background-color: #333;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
      z-index: 100;
    }

    body.dark-mode .theme-toggle {
      background-color: #87CEEB;
      color: #333;
    }

    @media (max-width: 600px) {
      .header-container {
        flex-direction: column-reverse;
        align-items: center;
        gap: 15px;
      }

      .profile-pic {
        width: 100px;
        height: 100px;
      }

      .resume-container {
        padding: 20px;
      }
    }
  </style>
</head>
<body>

  <div class="resume-container">
    <div class="header-container">
      <div>
        <h1>KODIPALLI BALAJI</h1>
        <div class="contact-info">
          Email: <a href="mailto:kodipallibalaji3@gmail.com">kodipallibalaji3@gmail.com</a><br>
          Phone: 9912550974<br>
          Location: Bhimavaram, India
        </div>
      </div>
      <!-- ✅ Correct image placement -->
      <img src="https://i.ibb.co/VYgWQ41S/Whats-App-Image-2025-07-03-at-20-02-42-91119d04.jpg" alt="KODIPALLI BALAJI" class="profile-pic">
    </div>

    <h2>About Me</h2>
    <p>I am passionate about building innovative solutions using AI and expanding my knowledge in web technologies.</p>

    <h2>Skills</h2>
    <ul>
      <li><strong>Languages:</strong> JavaScript, Python, Java</li>
      <li><strong>Databases:</strong> MySQL</li>
      <li><strong>Tools:</strong> VS Code</li>
    </ul>

    <h2>Projects</h2>
    <ul>
      <li><strong>Frontend:</strong> Created a travel booking website with a unique idea and modern design.</li>
      <li><strong>Sign Language Converter:</strong> Built a model using Machine Learning and Deep Learning to convert hand gestures into text.</li>
      <li><strong>Product Demand Prediction:</strong> Developed a Machine Learning model to predict product demand based on historical data.</li>
    </ul>

    <h2>Certifications</h2>
    <ul>
      <li>Cisco - Introduction to Cybersecurity</li>
    </ul>

    <h2>Hobbies</h2>
    <ul>
      <li>Exploring unique and interesting tech topics</li>
      <li>Participating in coding challenges</li>
      <li>Experimenting with AI tools</li>
    </ul>

    <h2>Contact</h2>
    <p>
      Email: <a href="mailto:kodipallibalaji3@gmail.com">kodipallibalaji3@gmail.com</a><br>
      GitHub: <a href="https://github.com/Balaji7997" target="_blank">https://github.com/Balaji7997</a>
    </p>
  </div>

  <button class="theme-toggle" id="themeToggle">Dark Mode</button>

  <script>
    const themeToggle = document.getElementById('themeToggle');
    const body = document.body;

    themeToggle.addEventListener('click', function () {
      body.classList.toggle('dark-mode');
      themeToggle.textContent = body.classList.contains('dark-mode') ? 'Light Mode' : 'Dark Mode';
    });
  </script>

</body>
</html>
# Resume-using-frontend
