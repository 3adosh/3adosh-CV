<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Oday Hmydat CV</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-image: url('IMG_20240311_175844_752.jpg'); 
            background-size: cover;
            background-repeat: no-repeat;  
            margin: 0;
            padding: 20px;
            transition: background-color 0.5s;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background-color: rgba(255, 255, 255, 0.8); 
            border: 2px solid grey;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 1s, transform 1s;
        }
        h1, h2 {
            color: #333;
            transition: transform 0.5s;
        }
        .section {
            margin-bottom: 20px;
        }
        .contact-info {
            display: grid;
            grid-template-columns: 1fr auto;
            align-items: center;
            margin-bottom: 20px;
        }
        .contact-info .details {
            padding-right: 20px;
        }
        .experience, .skills, .achievements {
            border: 1px solid #ddd;
            padding: 15px;
            background-color: #f9f9f9;
            margin-bottom: 20px;
            cursor: pointer;
        }
        .profile-picture {
            width: 300px;  
            height: 300px;
            border-radius: 50%;
            object-fit: cover;
            justify-self: end;  
            transition: transform 0.3s; 
        }
        .profile-picture:hover {
            transform: scale(1.1); 
        }
        .popup {
            display: none;
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background-color: white;
            border: 2px solid grey;
            padding: 20px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.3);
            z-index: 1000;
        }
        .overlay {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
            z-index: 500;
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

        <div class="section experience" onclick="showPopup('Experience Details', 'Details about my experience and roles.')">
            <h2>Experience</h2>
            <p><strong>Data Entry Assistant</strong></p>
            <p>Computer and Information Center, Yarmouk University</p>
            <p>Contributed to improving the data management system by 20% through implementing updates and new technologies.</p>

            <p><strong>Problem Analyst</strong></p>
            <p>Computer Centre, Yarmouk University</p>
            <p>Resolved usage errors for students and assisted with external courses like Cisco.</p>
        </div>

        <div class="section skills" onclick="showPopup('Skills Details', 'Details about my skills.')">
            <h2>Skills</h2>
            <ul>
                <li>Proficient in Microsoft Office Suite</li>
                <li>Data Analysis</li>
                <li>IT Troubleshooting</li>
            </ul>
        </div>

        <div class="section achievements" onclick="showPopup('Achievements Details', 'Details about my achievements.')">
            <h2>Achievements</h2>
            <p>Contributed to improving the data management system by 20%.</p>
        </div>
    </div>

    <div class="overlay" id="overlay" onclick="hidePopup()"></div>
    <div class="popup" id="popup">
        <h2 id="popup-title"></h2>
        <p id="popup-content"></p>
        <button onclick="hidePopup()">Close</button>
    </div>

    <script>
        window.onload = function() {
            const container = document.getElementById('container');
            container.style.opacity = 1;
            container.style.transform = 'translateY(0)';
        };

        window.onscroll = function() {
            const scrollY = window.scrollY;
            document.body.style.backgroundColor = `rgba(255, 255, 255, ${Math.min(scrollY / 1000, 0.8)})`;
        };

        function showPopup(title, content) {
            document.getElementById('popup-title').innerText = title;
            document.getElementById('popup-content').innerText = content;
            document.getElementById('popup').style.display = 'block';
            document.getElementById('overlay').style.display = 'block';
        }

        function hidePopup() {
            document.getElementById('popup').style.display = 'none';
            document.getElementById('overlay').style.display = 'none';
        }
    </script>
</body>
</html>
