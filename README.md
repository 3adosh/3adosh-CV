<html lang="en-GB">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Oday Hmydat - Professional Web CV</title>
  <style>
    :root {
      --primary-color: #1a3a6e; /* أزرق داكن مفتح قليلاً */
      --secondary-color: #2a4a8a; /* أزرق داكن */
      --header-bg: #1a3a6e; /* لون خلفية الهيدر */
      --white: #ffffff;
      --light-bg: #f8f9fa;
      --dark-text: #333333; /* لون النص الأساسي */
      --light-text: #777777;
    }
    
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: var(--light-bg);
      color: var(--dark-text);
      line-height: 1.6;
      padding: 0;
      margin: 0;
    }
    
    .container {
      max-width: 850px;
      margin: 40px auto;
      background: white;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
      border-radius: 8px;
      overflow: hidden;
    }
    
    .header {
      background-color: var(--header-bg);
      padding: 30px 40px;
    }
    
    .header h1 {
      margin: 0;
      font-size: 2.2em;
      color: var(--white); /* الاسم باللون الأبيض */
    }
    
    .header .contact-info {
      margin-top: 15px;
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      color: var(--white);
    }
    
    .header .contact-info span {
      display: flex;
      align-items: center;
      gap: 8px;
    }
    
    .header .contact-info i {
      color: var(--white);
    }
    
    .header .contact-info a {
      color: var(--white);
      text-decoration: underline;
    }
    
    .content {
      padding: 30px 40px;
    }
    
    h2 {
      color: var(--primary-color);
      border-bottom: 2px solid var(--primary-color);
      padding-bottom: 8px;
      margin-top: 30px;
      font-size: 1.5em;
    }
    
    .section {
      margin-bottom: 25px;
    }
    
    .job, .education {
      margin-bottom: 20px;
    }
    
    .job-title, .degree {
      font-weight: bold;
      font-size: 1.1em;
      color: var(--primary-color);
    }
    
    .company, .university {
      font-weight: bold;
    }
    
    .date {
      color: var(--light-text);
      font-style: italic;
      font-size: 0.9em;
    }
    
    ul {
      padding-left: 20px;
    }
    
    li {
      margin-bottom: 8px;
    }
    
    a {
      color: var(--secondary-color);
      text-decoration: none;
      transition: color 0.3s;
    }
    
    a:hover {
      color: var(--primary-color);
      text-decoration: underline;
    }
    
    .skills-container {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }
    
    .skill {
      background-color: var(--light-bg);
      padding: 5px 12px;
      border-radius: 15px;
      font-size: 0.9em;
      border: 1px solid #e0e0e0;
    }
    
    .certification {
      margin-bottom: 10px;
    }
    
    .certification .issuer {
      font-weight: bold;
      color: var(--primary-color);
    }
    
    .download-btn {
      display: inline-block;
      background-color: var(--primary-color);
      color: white;
      padding: 10px 20px;
      border-radius: 5px;
      margin-top: 10px;
      transition: background-color 0.3s;
    }
    
    .download-btn:hover {
      background-color: var(--secondary-color);
    }
    
    .download-btn i {
      margin-right: 8px;
    }
    
    @media (max-width: 768px) {
      .container {
        margin: 0;
        border-radius: 0;
      }
      
      .header, .content {
        padding: 20px;
      }
    }
  </style>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
  <div class="container">
    <div class="header">
      <h1>Oday Hmydat</h1>
      <div class="contact-info">
        <span><i class="fas fa-map-marker-alt"></i> Koura District, Irbid, Jordan</span>
        <span><i class="fas fa-phone"></i> +962 780 545 668</span>
        <span><i class="fas fa-envelope"></i> odyhmydat@gmail.com</span>
        <span><i class="fab fa-linkedin"></i> <a href="https://linkedin.com/in/oday-hmydat" target="_blank">linkedin.com/in/oday-hmydat</a></span>
      </div>
    </div>
    
    <div class="content">
      <!-- باقي المحتوى يبقى كما هو بدون تغيير -->
      <div class="section">
        <h2>Objective</h2>
        <p>
          Detail-oriented Cybersecurity student (Third Cohort – Yarmouk University) with strong data entry and troubleshooting skills, and certifications in Cisco and NVIDIA technologies. Looking to leverage my abilities to support IT operations and improve organisational systems.
        </p>
      </div>
      
      <div class="section">
        <h2>Education</h2>
        <div class="education">
          <div class="degree">Bachelor of Cybersecurity</div>
          <div class="university">Yarmouk University</div>
          <div class="date">Expected Graduation: 2025</div>
        </div>
      </div>
      
      <div class="section">
        <h2>Experience</h2>
        <div class="job">
          <div class="job-title">Data Entry Assistant</div>
          <div class="company">Yarmouk University</div>
          <div class="date">Apr 2023 – Present</div>
          <ul>
            <li>Improved system efficiency by 20% via new technologies.</li>
            <li>Entered and managed 1,000+ student records accurately.</li>
          </ul>
        </div>
        
        <div class="job">
          <div class="job-title">Problem Analyst</div>
          <div class="company">Yarmouk University</div>
          <div class="date">Apr 2023 – Jun 2024</div>
          <ul>
            <li>Resolved 500+ student issues including password recovery and access support.</li>
            <li>Supported Cisco e-learning access and troubleshooting.</li>
          </ul>
        </div>
      </div>
      
      <div class="section">
        <h2>Certifications</h2>
        <div class="certification">
          <div class="cert-name">CCNA: Introduction to Networks</div>
          <div class="issuer">Cisco (Jun 2025)</div>
        </div>
        <div class="certification">
          <div class="cert-name">CCNA: Switching, Routing, and Wireless Essentials</div>
          <div class="issuer">Cisco (Jun 2025)</div>
        </div>
        <div class="certification">
          <div class="cert-name">CCNA: Enterprise Networking, Security, and Automation</div>
          <div class="issuer">Cisco (Jun 2025)</div>
        </div>
        <div class="certification">
          <div class="cert-name">Fundamentals of Deep Learning</div>
          <div class="issuer">NVIDIA (Dec 2024)</div>
        </div>
        <div class="certification">
          <div class="cert-name">Building Transformer-Based NLP Applications</div>
          <div class="issuer">NVIDIA (May 2025)</div>
        </div>
        <div class="certification">
          <div class="cert-name">Accelerating CUDA C++ with Multiple GPUs</div>
          <div class="issuer">NVIDIA (Jan 2024)</div>
        </div>
        <div class="certification">
          <div class="cert-name">Fundamentals of Accelerated Computing with CUDA</div>
          <div class="issuer">NVIDIA (Jan 2024)</div>
        </div>
        <div class="certification">
          <div class="cert-name">Data Entry Skills</div>
          <div class="issuer">Udemy</div>
        </div>
      </div>
      
      <div class="section">
        <h2>Skills</h2>
        <div class="skills-container">
          <span class="skill">Advanced Excel</span>
          <span class="skill">Microsoft Office</span>
          <span class="skill">Google Workspace</span>
          <span class="skill">IT Support</span>
          <span class="skill">Troubleshooting</span>
          <span class="skill">Linux (Kali GNOME)</span>
          <span class="skill">Cisco Packet Tracer</span>
          <span class="skill">ChatGPT for productivity</span>
          <span class="skill">Communication</span>
          <span class="skill">Time Management</span>
        </div>
      </div>
      
      <div class="section">
        <h2>Achievements</h2>
        <ul>
          <li>Enhanced data system efficiency by 20% at Yarmouk University.</li>
          <li>Recognised for excellent student technical support and issue resolution.</li>
        </ul>
      </div>
      
      <div class="section">
        <h2>Download CV</h2>
        <a href="Oday-Hmydat-CV.pdf" download class="download-btn">
          <i class="fas fa-file-pdf"></i> Download PDF CV
        </a>
      </div>
    </div>
  </div>
</body>
</html>
