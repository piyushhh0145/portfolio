<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Piyush | Business Analytics Portfolio</title>
  <link rel="icon" href="https://cdn-icons-png.flaticon.com/512/2830/2830300.png" type="image/png">
  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    /* Global Styles */
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #f6d365, #fda085);
      color: #333;
      scroll-behavior: smooth;
      overflow-x: hidden;
    }
    a { 
      text-decoration: none; 
      color: inherit;
    }
    
    /* Sticky Navigation */
    nav {
      position: sticky;
      top: 0;
      background: rgba(0, 123, 255, 0.9);
      padding: 15px 30px;
      z-index: 1000;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      font-weight: 600;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: #ffeb3b;
    }
    
    /* Header with Enhanced Style */
    header {
      background: linear-gradient(135deg, rgba(0,123,255,0.8), rgba(0,200,255,0.8));
      color: #fff;
      padding: 60px 20px;
      text-align: center;
      position: relative;
      overflow: hidden;
      box-shadow: inset 0 0 50px rgba(0,0,0,0.2);
    }
    header h1 {
      font-size: 3.5em;
      margin: 0;
      text-shadow: 2px 2px 8px rgba(0,0,0,0.3);
    }
    header p {
      font-size: 1.3em;
      margin-top: 15px;
      text-shadow: 1px 1px 6px rgba(0,0,0,0.25);
    }
    
    /* Animated Background Elements */
    .bubble {
      position: absolute;
      background: rgba(255, 255, 255, 0.3);
      border-radius: 50%;
      animation: rise 12s infinite ease-in;
      bottom: -150px;
    }
    @keyframes rise {
      0% {
        transform: translateY(0) scale(0.5);
        opacity: 0;
      }
      50% {
        opacity: 0.9;
      }
      100% {
        transform: translateY(-800px) scale(1);
        opacity: 0;
      }
    }
    .bubble:nth-child(1) { left: 10%; width: 45px; height: 45px; animation-duration: 14s; }
    .bubble:nth-child(2) { left: 30%; width: 25px; height: 25px; animation-duration: 12s; animation-delay: 2s; }
    .bubble:nth-child(3) { left: 50%; width: 35px; height: 35px; animation-duration: 16s; animation-delay: 4s; }
    .bubble:nth-child(4) { left: 70%; width: 30px; height: 30px; animation-duration: 13s; animation-delay: 1s; }
    .bubble:nth-child(5) { left: 90%; width: 40px; height: 40px; animation-duration: 15s; animation-delay: 3s; }
    
    /* Section Styles */
    section {
      padding: 40px;
      max-width: 1000px;
      margin: 40px auto;
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 8px 16px rgba(0,0,0,0.15);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    section:hover {
      transform: translateY(-8px);
      box-shadow: 0 12px 24px rgba(0,0,0,0.25);
    }
    h2, h3 {
      color: #007bff;
    }
    
    /* Button Styling */
    .btn {
      display: inline-block;
      padding: 14px 24px;
      background: #007bff;
      color: #fff;
      border: none;
      border-radius: 30px;
      font-size: 1em;
      cursor: pointer;
      transition: background 0.3s ease, transform 0.3s ease;
      margin-top: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.15);
    }
    .btn:hover {
      background: #0056b3;
      transform: scale(1.05);
    }
    
    /* Hidden Content Sections */
    .more-content {
      display: none;
      margin-top: 25px;
      border-top: 1px solid #ddd;
      padding-top: 25px;
      color: #555;
    }
    
    /* Profile Image in About Section */
    .profile-image {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 5px solid #007bff;
      margin: 20px auto;
      display: block;
    }
    
    /* Contact Styles */
    .contact a {
      color: #007bff;
      font-weight: 600;
    }
    
    /* Footer */
    footer {
      background: rgba(0, 123, 255, 0.9);
      color: #fff;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
    }
    
    /* Responsive Media Queries */
    @media (max-width: 768px) {
      header h1 { font-size: 2.8em; }
      nav { flex-direction: column; }
      nav a { margin: 8px 0; }
    }
  </style>
</head>
<body>
  <!-- Navigation -->
  <nav>
    <div class="logo"><a href="#">Piyush Portfolio</a></div>
    <div class="menu">
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#experience">Experience</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>
  
  <!-- Header with Animated Bubbles -->
  <header>
    <h1>Transforming Data into Business Growth</h1>
    <p>Delivering actionable insights through analytical expertise</p>
    <div class="bubbles">
      <div class="bubble"></div>
      <div class="bubble"></div>
      <div class="bubble"></div>
      <div class="bubble"></div>
      <div class="bubble"></div>
    </div>
  </header>
  
  <!-- About Section with Collapsible Details and Profile Image -->
  <section id="about">
    <h2>About Me</h2>
    <!-- Profile Image -->
    <img src="IMG_20241202_204858.jpg" alt="Piyush's Profile Image" class="profile-image">
    <p>I'm Piyush, a dedicated Business Analytics student with global exposure (MRU x IoA-UK). Skilled in Python, Power BI, Tableau, and Advanced Excel, I excel at transforming data into strategic business decisions. I am passionate about leveraging analytics to drive growth and innovation.</p>
    <button class="btn" onclick="toggleContent('moreAbout', this)">Learn More</button>
    <div id="moreAbout" class="more-content">
      <h3>Qualifications & Background</h3>
      <p><strong>BBA in Business Analytics (2022-2025)</strong><br>
         Manav Rachna University | IoA-UK Partnership<br>
         Current CGPA: 6.87</p>
      <p><strong>12th Grade - CBSE</strong><br>
         K.L. Mehta School, 2021<br>
         Percentage: 75%</p>
      <p>These credentials have equipped me with a strong analytical foundation and a global perspective, empowering me to deliver data-driven solutions and support strategic decision-making.</p>
    </div>
  </section>
  
  <!-- Projects Section with Collapsible Details -->
  <section id="projects">
    <h2>My Projects</h2>
    <p>Explore my projects where I combine data analysis with innovative design to create powerful solutions.</p>
    <button class="btn" onclick="toggleContent('moreProjects', this)">View Projects</button>
    <div id="moreProjects" class="more-content">
      <h3>Project Details</h3>
      <p><strong>Diversity Analytics Dashboard | Power BI</strong><br>
         Developed a dashboard to analyze gender distribution, tenure, and performance. Delivered insights to leadership using Power BI visuals.</p>
      <p><strong>Voice-Activated Personal Assistant | Python</strong><br>
         Built a voice assistant to automate tasks using NLP and speech libraries.</p>
      <div style="margin-top: 20px;">
        <a class="btn" href="DIVERSITY%20DASHBOARD(HRA).pbix" download="DIVERSITY_DASHBOARD.pbix">Download Power BI Project</a>
        <a class="btn" href="jarvis.py" download="jarvis.py">Download Voice Assistant Project</a>
      </div>
    </div>
  </section>
  
  <!-- Work Experience Section with Collapsible Details -->
  <section id="experience">
    <h2>Work Experience</h2>
    <p>A snapshot of my professional experience and internships.</p>
    <button class="btn" onclick="toggleContent('moreExperience', this)">View Experience</button>
    <div id="moreExperience" class="more-content">
      <h3>Data Entry Intern | Sharma Associates</h3>
      <p><em>June 2024 - July 2024</em></p>
      <ul>
        <li>Streamlined data workflows and improved reporting accuracy.</li>
        <li>Implemented validation checks to enhance data integrity.</li>
        <li>Collaborated with teams to optimize client data records.</li>
      </ul>
    </div>
  </section>
  
  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <p>Feel free to reach out to discuss opportunities or collaborations.</p>
    <p class="contact">
      Email: <a href="mailto:piyushagarwal123344@gmail.com">piyushagarwal123344@gmail.com</a><br>
      Phone: <strong>9667645410</strong>
    </p>
    <div style="margin-top: 15px;">
      <button class="btn" onclick="window.location.href='mailto:piyushagarwal123344@gmail.com'">Get in Touch</button>
      <a class="btn" href="Piyush_Resume.pdf" download="Piyush_Resume.pdf">Download Resume</a>
    </div>
  </section>
  
  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Piyush | All Rights Reserved</p>
  </footer>
  
  <!-- JavaScript for Toggle Functionality -->
  <script>
    function toggleContent(id, btn) {
      var content = document.getElementById(id);
      if (content.style.display === "block") {
        content.style.display = "none";
        if (id === 'moreAbout') {
          btn.textContent = "Learn More";
        } else if (id === 'moreProjects') {
          btn.textContent = "View Projects";
        } else if (id === 'moreExperience') {
          btn.textContent = "View Experience";
        }
      } else {
        content.style.display = "block";
        btn.textContent = "Show Less";
      }
    }
  </script>
</body>
</html>
