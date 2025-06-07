<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Gourav Saini | Data Analyst Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
  <style>
    @keyframes fadeInUp {
      0% {opacity: 0; transform: translateY(20px);}
      100% {opacity: 1; transform: translateY(0);}
    }
    @keyframes bounce {
      0%, 100% {transform: translateY(0);}
      50% {transform: translateY(-5px);}
    }
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }
    body {
      background: url('https://www.transparenttextures.com/patterns/cubes.png'), linear-gradient(to right, #0f2027, #203a43, #2c5364);
      background-attachment: fixed;
      background-size: cover;
      color: #fff;
      line-height: 1.6;
    }
    header {
      background: rgba(26, 46, 70, 0.9);
      padding: 2rem;
      text-align: center;
    }
    header img.photo {
      border-radius: 50%;
      width: 120px;
    }
    header h1 {
      font-size: 2.5rem;
      color: #00bcd4;
      animation: fadeInUp 1s ease-in-out;
    }
    header p {
      font-size: 1.2rem;
      margin-top: 0.5rem;
      animation: fadeInUp 1.5s ease-in-out;
    }
    nav {
      background: #12263a;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: 500;
    }
    nav a:hover {
      color: #00bcd4;
    }
    section {
      padding: 4rem 2rem;
      max-width: 1000px;
      margin: auto;
      background-color: rgba(0, 0, 0, 0.5);
      border-radius: 12px;
    }
    h2 {
      color: #00bcd4;
      margin-bottom: 1rem;
    }
    .skills div, .projects div {
      background: #1c2f48;
      padding: 1rem;
      margin: 1rem 0;
      border-radius: 8px;
    }
    .resume, .contact {
      text-align: center;
    }
    .btn {
      display: inline-block;
      margin: 1rem 0.5rem;
      padding: 0.75rem 1.5rem;
      background: #00bcd4;
      color: #000;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      transition: transform 0.3s ease;
      animation: fadeInUp 2s ease-in-out;
    }
    footer {
      text-align: center;
      padding: 2rem;
      background: #12263a;
    }
  .btn:hover {
      transform: scale(1.05);
      animation: bounce 0.6s infinite;
    }

</style>
</head>
<body>
  <header>
    <div style="font-size: 1rem; color: #ffd700; background-color: #1f354e; padding: 0.5rem; border-radius: 6px; max-width: 300px; margin: 0 auto 1rem;">
      🌟 LinkedIn Influencer | 10,000+ Followers
    </div>
    
    <h1>Gourav Saini</h1>
    <p>Data Analyst | Python Developer | Power BI Specialist</p>
    <a href="#projects" class="btn">View Projects</a>
    <a href="mailto:gouravsaini23feb@gmail.com" class="btn">✉️ Email Me</a>
    <a href="https://wa.me/919759730090" class="btn" target="_blank"> WhatsApp </a>
    <a href="https://www.linkedin.com/in/gaurav-saini-6040052bb?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" class="btn" target="_blank">👤 LinkedIn</a>
  </header>
  <nav>
    <a href="#about">About Me</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#resume">Resume</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>I am a passionate data analyst currently in my 3rd year of B.Tech at COER University, Roorkee. I specialize in Python programming, data manipulation, and interactive dashboards using Power BI. With a strong foundation in data science and visualization, I aspire to solve real-world problems through data insights.</p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <div>
      <h3>Data Analysis</h3>
      <p>Python (Pandas, NumPy), SQL</p>
    </div>
    <div>
      <h3>Data Visualization</h3>
      <p>Power BI, Matplotlib, Seaborn</p>
    </div>
    <div>
      <h3>Soft Skills</h3>
      <p>Problem-solving, Communication, Critical Thinking</p>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div>
      <h3>Flight Delay Prediction</h3>
      <p>Analyzed and predicted flight delays using historical data. Tools: Python, Pandas, Matplotlib.</p>
    </div>
    <div>
      <h3>Sales Dashboard</h3>
      <p>Created an interactive Power BI dashboard to visualize sales metrics across regions.</p>
    </div>
    <div>
      <h3>Library Management System</h3>
      <p>Developed a Tkinter-based Python GUI application for managing library records.</p>
    </div>
  </section>

  <section id="resume">
    <h2>Achievements</h2>
    <div class="resume">
      <ul style="list-style-type: disc; padding-left: 20px;">
        <li>Featured on LinkedIn as a top student influencer with 10,000+ followers</li>
        <li>Completed Data Analytics Internship using Python, SQL, and Tableau</li>
        <li>Delivered a talk on Data Visualization at a university tech fest</li>
        <li>Developed automation tools for class scheduling and data processing</li>
      </ul>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <div class="contact">
      <p><strong>Phone:</strong> 9759730090</p>
      <p><strong>Email:</strong> <a href="mailto:gouravsaini23feb@gmail.com" style="color:#00bcd4">gouravsaini23feb@gmail.com</a></p>
      <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/gaurav-saini-6040052bb?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" style="color:#00bcd4">linkedin.com/in/gaurav-saini</a></p>
      <p><strong>GitHub:</strong> <a href="https://github.com/gouravsaini" style="color:#00bcd4">github.com/gouravsaini</a></p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Gourav Saini | All Rights Reserved</p>
  </footer>
</body>
</html>
