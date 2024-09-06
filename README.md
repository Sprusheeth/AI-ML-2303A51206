[lab1]https://github.com/Sprusheeth/AI-ML-2303A51206/blob/main/lab01.ipynb
<br>
[lab2]https://github.com/Sprusheeth/AI-ML-2303A51206/blob/main/lab2AIML.ipynb
<br>
[lab3 A* Algorithm]https://github.com/Sprusheeth/AI-ML-2303A51206/blob/main/lab2A_Algorithm_OR_Graph_Search.ipynb
<br>
[lab3 A* 2]https://github.com/Sprusheeth/AI-ML-2303A51206/blob/main/LAB_03.ipynb
<br>
[lab4]https://github.com/Sprusheeth/AI-ML-2303A51206/blob/main/lab4AIML.ipynb
<br>
[lab4code2]https://github.com/Sprusheeth/AI-ML-2303A51206/blob/main/lab4AIML2.ipynb<br>
[lab5]https://github.com/Sprusheeth/AI-ML-2303A51206/blob/main/lab5_AIML.ipynb

<h1>(NOTE:- Lab2,lab3 A* Algorithm,lab3 A* 2, All three labs code is same I have completed lab 3 code in a lab 2 itself)</h1>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sprusheeth Rao - Resume</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            height: 100%;
            background: #1a1a1a;
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            animation: bg-animation 10s infinite alternate;
            box-sizing: border-box;
        }

        @keyframes bg-animation {
            0% {background-color: #1a1a1a;}
            50% {background-color: #333;}
            100% {background-color: #555;}
        }

        .container {
            width: 90%;
            max-width: 1000px;
            background: #262626;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.8);
            display: flex;
            flex-wrap: wrap;
            overflow: hidden;
        }

        .profile-side, .content-side {
            box-sizing: border-box;
            padding: 20px;
        }

        .profile-side {
            width: 100%;
            max-width: 300px;
            background-color: #151515;
            text-align: center;
            color: #fff;
            position: relative;
        }

        .profile-side::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
            z-index: 1;
        }

        .profile-picture {
            position: relative;
            z-index: 2;
        }

        .profile-picture img {
            border-radius: 10px;
            width: 100%;
            max-width: 200px;
            height: auto;
            object-fit: cover;
            border: 5px solid #e63946;
            box-shadow: 0 0 15px rgba(230, 57, 70, 0.5);
            margin-bottom: 20px;
        }

        .profile-side h1, .profile-side h2 {
            margin: 10px 0;
            z-index: 2;
            position: relative;
        }

        .profile-side h1 {
            font-size: 2em;
            color: #e63946;
        }

        .profile-side h2 {
            font-size: 1.2em;
            color: #fff;
        }

        .social-links {
            margin-top: 20px;
            z-index: 2;
            position: relative;
            display: flex;
            justify-content: center;
            gap: 10px;
        }

        .social-links a {
            color: #fff;
            font-size: 20px;
            text-decoration: none;
        }

        .social-links a.facebook::before {
            content: "📘";
        }

        .social-links a.instagram::before {
            content: "📷";
        }

        .social-links a.linkedin::before {
            content: "🔗";
        }

        .content-side {
            width: calc(100% - 300px);
            padding: 20px 40px;
            color: #e5e5e5;
        }

        @media(max-width: 768px) {
            .container {
                flex-direction: column;
                align-items: center;
            }

            .profile-side, .content-side {
                width: 100%;
                max-width: 100%;
                padding: 20px;
            }

            .profile-side {
                max-width: none;
            }

            .content-side {
                padding: 20px;
            }
        }

        h3 {
            color: #e63946;
            margin-bottom: 15px;
        }

        ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        ul li {
            margin-bottom: 10px;
            color: #ccc;
        }

        .buttons {
            margin-top: 20px;
            text-align: center;
        }

        .buttons a {
            text-decoration: none;
            padding: 10px 20px;
            border-radius: 50px;
            border: 2px solid #e63946;
            color: #e63946;
            font-weight: bold;
            transition: all 0.3s ease;
            display: inline-block;
        }

        .buttons a:hover {
            background-color: #e63946;
            color: white;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="profile-side">
            <div class="profile-picture">
                <img src="spru.jpg" alt="Profile Picture">
            </div>
            <h1>Sprusheeth Rao</h1>
            <h2>B.Tech Second Year, SR University</h2>
            <div class="social-links">
                <a href="https://www.facebook.com/yourprofile" target="_blank" class="facebook"></a>
                <a href=https://www.instagram.com/sprusheeth_rao/ target="_blank" class="instagram"></a>
                <a href="https://www.linkedin.com/in/yourprofile" target="_blank" class="linkedin"></a>
            </div>
            <p>To leverage my skills in software development and problem-solving as a B.Tech second-year student at SR University. I aim to contribute to innovative projects while gaining hands-on experience in the field of Computer Science and Engineering.</p>
        </div>
        <div class="content-side">
            <h3>Education</h3>
            <ul>
                <li>Bachelor of Technology, SR University, Second Year (2023-2027)</li>
                <li>Completed Higher Secondary Schooling with 90% in Science Stream</li>
                <li>Completed Secondary Schooling with 92% overall</li>
            </ul>

            <h3>Skills</h3>
            <ul>
                <li>Programming Languages: Python, JavaScript, HTML, CSS</li>
                <li>Web Development: React, Node.js, Bootstrap</li>
                <li>Database Management: MySQL, MongoDB</li>
                <li>Version Control: Git, GitHub</li>
                <li>Problem-Solving and Algorithms</li>
            </ul>

            <h3>Personal Details</h3>
            <ul>
                <li>Address: 1-8-598, National Highway 163, Balasamudram, Hanamkonda, Telangana 506001, India</li>
                <li>Phone: +91 9490799234</li>
                <li>Email: sprusheeth@gmail.com (2303A51206@sru.edu.in)</li>
                <li>Date of Birth: August 12, 2005</li>
                <li>Languages Known: English, Hindi, Telugu</li>
            </ul>

            <div class="buttons">
                <a href="#">Download CV</a>
                <a href="mailto:sprusheeth@gmail.com">Contact</a>
                <a href="assignment2.html">Alternate</a>
            </div>
        </div>
    </div>
</body>
</html>
