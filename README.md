<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Oday Hmydat - Cybersecurity Professional</title>
    <style>
        /* Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f5f7fa;
            color: #333;
            line-height: 1.6;
            padding: 20px;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: white;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            overflow: hidden;
        }
        
        /* Header Styles */
        header {
            background: linear-gradient(135deg, #1a2a6c, #2a3a7c);
            color: white;
            padding: 30px;
            text-align: center;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            font-weight: 700;
        }
        
        .contact-info {
            font-size: 1.1rem;
            margin-top: 15px;
        }
        
        .contact-info a {
            color: white;
            text-decoration: none;
        }
        
        .contact-info a:hover {
            text-decoration: underline;
        }
        
        /* Section Styles */
        section {
            padding: 25px 30px;
            border-bottom: 1px solid #eaeaea;
        }
        
        h2 {
            color: #1a2a6c;
            font-size: 1.5rem;
            margin-bottom: 15px;
            padding-bottom: 8px;
            border-bottom: 2px solid #eaeaea;
        }
        
        h3 {
            font-size: 1.2rem;
            margin-top: 15px;
            margin-bottom: 5px;
            color: #2a3a7c;
        }
        
        p {
            margin-bottom: 10px;
        }
        
        ul {
            list-style-type: none;
            padding-left: 5px;
        }
        
        li {
            margin-bottom: 8px;
            padding-left: 15px;
            position: relative;
        }
        
        li:before {
            content: "•";
            color: #1a2a6c;
            font-weight: bold;
            position: absolute;
            left: 0;
        }
        
        /* Skills Grid */
        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 15px;
        }
        
        .skill-category {
            margin-bottom: 15px;
        }
        
        .skill-category h4 {
            color: #1a2a6c;
            margin-bottom: 8px;
            font-size: 1.1rem;
        }
        
        /* Experience Section */
        .job {
            margin-bottom: 20px;
        }
        
        .job-header {
            display: flex;
            justify-content: space-between;
            margin-bottom: 5px;
        }
        
        .job-title {
            font-weight: 600;
            color: #2a3a7c;
        }
        
        .job-date {
            color: #666;
            font-style: italic;
        }
        
        .job-company {
            color: #444;
            margin-bottom: 8px;
        }
        
        /* Footer */
        footer {
            text-align: center;
            padding: 15px;
            color: #666;
            font-size: 0.9rem;
        }
        
        /* Print Styles */
        @media print {
            body {
                background: white;
                padding: 0;
            }
            
            .container {
                box-shadow: none;
                border-radius: 0;
            }
            
            section {
                page-break-inside: avoid;
            }
            
            .no-print {
                display: none;
            }
        }
        
        /* Responsive Design */
        @media (max-width: 768px) {
            .job-header {
                flex-direction: column;
            }
            
            .skills-container {
                grid-template-columns: 1fr;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            section {
                padding: 20px;
            }
        }
        
        /* ATS Optimization Styles */
        .ats-keywords {
            display: none;
        }
        
        /* Call to Action */
        .cta-section {
            text-align: center;
            background-color: #f0f4f8;
            padding: 20px;
        }
        
        .cta-button {
            display: inline-block;
            background: #1a2a6c;
            color: white;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: 600;
            margin: 10px 5px;
            transition: background 0.3s;
        }
        
        .cta-button:hover {
            background: #2a3a7c;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Oday Hmydat</h1>
            <div class="contact-info">
                Koura District, Irbid, Jordan | +962 780 545 668 | 
                <a href="mailto:odyhmydat@gmail.com">odyhmydat@gmail.com</a> | 
                <a href="https://linkedin.com/in/oday-hmydat" target="_blank">linkedin.com/in/oday-hmydat</a>
            </div>
        </header>
        
        <!-- Hidden ATS Keywords -->
        <div class="ats-keywords">
            SOC Analyst, Cybersecurity, Network Security, Incident Response, Threat Detection, 
            Digital Forensics, SIEM, EDR, Cisco CCNA, Python, Linux, Vulnerability Management, 
            IT Support, Troubleshooting, Deep Learning, NLP, CUDA, Security Operations Center
        </div>
        
        <section id="summary">
            <h2>Professional Summary</h2>
            <p>Aspiring SOC Analyst with a solid foundation in network security, incident response principles, and AI-driven threat detection. Proven ability to troubleshoot complex technical issues and manage IT infrastructure, enhanced by certifications from Cisco (CCNA, Cyber Threat Management) and NVIDIA (Deep Learning, NLP). Seeking to apply analytical and technical skills to safeguard digital assets in an entry-level SOC or cybersecurity analyst role.</p>
        </section>
        
        <section id="skills">
            <h2>Technical Skills</h2>
            <div class="skills-container">
                <div class="skill-category">
                    <h4>SOC & Cybersecurity</h4>
                    <ul>
                        <li>Threat Detection</li>
                        <li>Incident Response</li>
                        <li>Digital Forensics</li>
                        <li>Vulnerability Management</li>
                        <li>SIEM Fundamentals</li>
                        <li>EDR Fundamentals</li>
                        <li>Network Defense</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h4>Networking</h4>
                    <ul>
                        <li>Cisco CCNA</li>
                        <li>TCP/IP</li>
                        <li>VLANs & ACLs</li>
                        <li>Routing & Switching</li>
                        <li>Network Security</li>
                        <li>Cisco IOS</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h4>Programming & Scripting</h4>
                    <ul>
                        <li>Python</li>
                        <li>CUDA C/C++</li>
                        <li>Bash</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h4>Operating Systems</h4>
                    <ul>
                        <li>Linux (Kali)</li>
                        <li>Windows Server</li>
                        <li>Windows</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h4>AI & Deep Learning</h4>
                    <ul>
                        <li>Transformer-Based NLP</li>
                        <li>Neural Networks</li>
                        <li>Multi-GPU Programming</li>
                        <li>Deep Learning Fundamentals</li>
                    </ul>
                </div>
            </div>
        </section>
        
        <section id="certifications">
            <h2>Certifications</h2>
            <ul>
                <li><strong>Cyber Threat Management</strong> | Cisco Networking Academy | 2023</li>
                <li><strong>CCNA: Introduction to Networks</strong> | Cisco Networking Academy | 2023</li>
                <li><strong>CCNA: Switching, Routing, and Wireless Essentials</strong> | Cisco Networking Academy | 2023</li>
                <li><strong>CCNA: Enterprise Networking, Security, and Automation</strong> | Cisco Networking Academy | 2023</li>
                <li><strong>Building Transformer-Based Natural Language Processing Applications</strong> | NVIDIA Deep Learning Institute | 2025</li>
                <li><strong>Fundamentals of Deep Learning</strong> | NVIDIA Deep Learning Institute | 2024</li>
                <li><strong>Fundamentals of Accelerated Computing with CUDA C/C++</strong> | NVIDIA Deep Learning Institute | 2024</li>
            </ul>
        </section>
        
        <section id="experience">
            <h2>Professional Experience</h2>
            
            <div class="job">
                <div class="job-header">
                    <div class="job-title">Data Entry Assistant</div>
                    <div class="job-date">April 2023 – Present</div>
                </div>
                <div class="job-company">Computer and Information Center, Yarmouk University | Irbid, Jordan</div>
                <ul>
                    <li>Enhanced data management system efficiency by 20% by implementing systematic updates and new technologies, improving data integrity and access for university operations</li>
                    <li>Maintained and validated over 1,000 student records with a 99.9% accuracy rate, demonstrating meticulous attention to detail</li>
                </ul>
            </div>
            
            <div class="job">
                <div class="job-header">
                    <div class="job-title">IT Support Specialist</div>
                    <div class="job-date">April 2023 – June 2024</div>
                </div>
                <div class="job-company">Computer Centre, Yarmouk University | Irbid, Jordan</div>
                <ul>
                    <li>Resolved 500+ technical incidents for students and faculty, including password resets, email access, and network connectivity issues, developing strong troubleshooting and customer service skills</li>
                    <li>Assisted students in accessing and navigating external learning platforms like Cisco Networking Academy, supporting their educational journey and technical proficiency</li>
                </ul>
            </div>
        </section>
        
        <section id="education">
            <h2>Education</h2>
            <h3>Bachelor of Science in Cybersecurity</h3>
            <p>Yarmouk University | Irbid, Jordan</p>
            <p>September 2022 – September 2026 (Expected)</p>
            <ul>
                <li>Relevant Coursework: Network Security, Digital Forensics, Operating Systems Security, Ethical Hacking Principles</li>
            </ul>
        </section>
        
        <section class="cta-section">
            <h2>Get In Touch</h2>
            <p>I'm currently seeking SOC Analyst, Cybersecurity Intern, or IT Security Specialist opportunities.</p>
            <a href="mailto:odyhmydat@gmail.com" class="cta-button">Email Me</a>
            <a href="https://linkedin.com/in/oday-hmydat" target="_blank" class="cta-button">View LinkedIn</a>
            <a href="#" onclick="window.print()" class="cta-button no-print">Print CV</a>
        </section>
        
        <footer>
            <p>References available upon request</p>
        </footer>
    </div>
    
    <script>
        // Simple script to enhance user experience
        document.addEventListener('DOMContentLoaded', function() {
            // Add smooth scrolling for anchor links
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function (e) {
                    e.preventDefault();
                    document.querySelector(this.getAttribute('href')).scrollIntoView({
                        behavior: 'smooth'
                    });
                });
            });
            
            // Print functionality
            const printButton = document.querySelector('.cta-button[onclick]');
            if (printButton) {
                printButton.addEventListener('click', function() {
                    window.print();
                });
            }
        });
    </script>
</body>
</html>
