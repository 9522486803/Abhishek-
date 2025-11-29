#<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Personal Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #f4f4f4;
        }
        header {
            background: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
            background: white;
        }
        img.profile {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            display: block;
            margin: 10px auto;
        }
        h2 {
            border-bottom: 2px solid #333;
            padding-bottom: 5px;
        }
        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #aaa;
            border-radius: 5px;
        }
        form button {
            padding: 10px 20px;
            border: none;
            background: #333;
            color: white;
            cursor: pointer;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 15px;
            margin-top: 20px;
            background: #333;
            color: #fff;
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Name</h1>
    </header>

    <div class="container">
        <img src="your-photo.jpg" alt="Profile Picture" class="profile" />
        <p>Hello! I am [Your Name], a passionate learner and aspiring developer. This is my personal website showcasing my background, skills, and projects.</p>

        <h2>Education</h2>
        <ul>
            <li>High School – XYZ School</li>
            <li>Diploma/B.Tech – ABC Institute</li>
        </ul>

        <h2>Skills</h2>
        <ul>
            <li>HTML, CSS, JavaScript</li>
            <li>C/C++ / Python</li>
            <li>Basic Electronics, Circuits</li>
        </ul>

        <h2>Projects</h2>
        <ul>
            <li>Project 1 – Description here</li>
            <li>Project 2 – Description here</li>
            <li>Project 3 – Description here</li>
        </ul>

        <h2>Contact Me</h2>
        <form>
            <input type="text" placeholder="Your Name" required />
            <input type="email" placeholder="Your Email" required />
            <textarea rows="5" placeholder="Your Message"></textarea>
            <button type="submit">Send</button>
        </form>
    </div>

    <footer>
        <p>© 2025 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>
