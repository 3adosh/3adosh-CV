<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Oday Hmydat CV</title>
    <style>
        body {
            font-family: 'Open Sans', sans-serif;
            background-image: url('IMG_20240311_175844_752.jpg'); 
            background-size: cover;
            background-repeat: no-repeat;  
            margin: 0;
            padding: 20px;
            transition: background-color 0.5s;
            color: #333;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            background-color: rgba(255, 255, 255, 0.95);
            border: 1px solid #ccc;
            padding: 20px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 1s, transform 1s;
        }
        h1, h2 {
            color: #2c3e50;
            text-align: center;
        }
        .section {
            margin-bottom: 20px;
        }
        .contact-info {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .contact-info .details {
            padding-right: 20px;
        }
        .experience, .skills, .achievements, .certifications {
            border: 1px solid #ddd;
            padding: 15px;
            background-color: #f9f9f9;
            margin-bottom: 20px;
        }
        .profile-picture {
            width: 150px;  
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            transition: transform 0.3s; 
        }
        .profile-picture:hover {
            transform: scale(1.1); 
        }
        .certification-img {
            width: 100%;
            max-width: 400px;
            margin-top: 10px;
            border-radius: 10px;
        }
        a {
            text-decoration: none;
            color: #3498db;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container" id="container">
        <h1>Oday Hmydat</h1>
        <div class="contact-info">
            <div class="details">
                <p><strong>Location:</strong> Koura District, Irbid, Jordan</p>
                <p><strong>Phone:</strong> +962 780 545 668</p>
                <p><strong>Email:</strong> <a href="mailto:odyhmydat@gmail.com">odyhmydat@gmail.com</a></p>
            </div>
            <img src="IMG_20240311_175844_752.jpg" alt="Profile Picture" class="profile-picture" id="profilePic">
        </div>

        <div class="section education">
            <h2>Education</h2>
            <p><strong>Yarmouk University</strong></p>
            <p>Cybersecurity, Third Cohort</p>
            <p>Expected Graduation: 2025</p>
        </div>

        <div class="section experience">
            <h2>Experience</h2>
            <p><strong>Data Entry Assistant</strong></p>
            <p>Computer and Information Center, Yarmouk University</p>
            <p>Contributed to improving the data management system by 20% through implementing updates and new technologies.</p>

            <p><strong>Problem Analyst</strong></p>
            <p>Computer Centre, Yarmouk University</p>
            <p>Resolved usage errors for students and assisted with external courses like Cisco.</p>
        </div>

        <div class="section skills">
            <h2>Skills</h2>
            <ul>
                <li>Proficient in Microsoft Office Suite</li>
                <li>Data Analysis</li>
                <li>IT Troubleshooting</li>
            </ul>
        </div>

        <div class="section achievements">
            <h2>Achievements</h2>
            <p>Contributed to improving the data management system by 20%.</p>
        </div>

        <div class="section certifications">
            <h2>Certifications</h2>
            <p><strong>Udemy Certification: Advanced Data Entry Skills from Scratch</strong></p>
            <p>This certification confirms the successful completion of the "Data Entry Skills: A Complete Data Entry Course from Scratch" on 09/26/2024, as instructed by Data Tutors on Udemy.</p>
            <a href="https://udemy-certificate.s3.amazonaws.com/image/UC-7dc80fa7-a40a-4518-b675-f8fe77164c64.jpg?v=1727304543000" target="_blank">
                <img src="https://udemy-certificate.s3.amazonaws.com/image/UC-7dc80fa7-a40a-4518-b675-f8fe77164c64.jpg?v=1727304543000" alt="Udemy Certificate" class="certification-img">
            </a>
        </div>

        <p>Download PDF: <a href="path-to-your-cv.pdf" target="_blank">Click here</a></p>
    </div>

    <script>
        window.onload = function() {
            const container = document.getElementById('container');
            container.style.opacity = 1;
            container.style.transform = 'translateY(0)';
        };

        window.onscroll = function() {
            const scrollY = window.scrollY;
            document.body.style.backgroundColor = `rgba(0, 0, 0, ${Math.min(scrollY / 1000, 0.8)})`;
        };
    </script>
</body>
</html>
