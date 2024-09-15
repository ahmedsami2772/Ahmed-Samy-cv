<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ahmed Samy's CV</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f0f0f0;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            animation: fadeIn 1s ease-in-out;
        }
        h1, h2, h3 {
            color: #007bff;
            margin-bottom: 10px;
        }
        h1 {
            font-size: 2.5em;
            text-align: center;
        }
        p, ul {
            line-height: 1.6;
            margin: 10px 0;
        }
        ul {
            padding-left: 20px;
        }
        a {
            color: #007bff;
            text-decoration: none;
            transition: color 0.3s;
        }
        a:hover {
            color: #0056b3;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        .section {
            margin-bottom: 30px;
            animation: slideIn 0.5s forwards;
            opacity: 0;
        }
        @keyframes slideIn {
            from {
                transform: translateY(20px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }
        .section:nth-child(odd) {
            animation-delay: 0.2s;
        }
        .section:nth-child(even) {
            animation-delay: 0.4s;
        }
        .contact-info {
            text-align: center;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Ahmed Samy</h1>
        <div class="contact-info">
            <p>Email: <a href="mailto:ahmedsami2772@gmail.com">ahmedsami2772@gmail.com</a></p>
            <p>Phone: <a href="tel:01115749326">01115749326</a></p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/ahmed-samy2772/">Profile</a></p>
        </div>

        <div class="section">
            <h2>Summary</h2>
            <p>Technical background with a Bachelor of Commerce (Accounting). Experienced in account management and e-commerce coordination. Passionate about career growth and contributing to team success.</p>
        </div>

        <div class="section">
            <h2>Professional Experience</h2>
            <h3>Amazon</h3>
            <p><strong>Account Representative</strong> | 01/2024 – Present | Cairo, Egypt</p>
            <ul>
                <li>Leading diverse projects and expanding business initiatives.</li>
            </ul>
            <p><strong>Account Assistant</strong> | 06/2022 – Present | Cairo, Egypt</p>
            <ul>
                <li>Analyzed account deactivation trends, reducing future issues by 40%.</li>
                <li>Resolved over 200 enforced accounts through detailed audits.</li>
                <li>Improved seller retention rates by delivering actionable insights.</li>
            </ul>
        </div>

        <div class="section">
            <h3>Al-Hassan Foundation</h3>
            <p><strong>Training and Recruitment Coordinator</strong> | 01/2021 – 06/2022 | Giza</p>
            <ul>
                <li>Implemented process re-engineering to streamline services.</li>
                <li>Coordinated effectively between service providers and beneficiaries.</li>
            </ul>
        </div>

        <div class="section">
            <h2>Education</h2>
            <p><strong>Sales and Marketing Diploma</strong> | AUC | 07/2023 – 03/2024</p>
            <p><strong>MBA</strong> | RB College | 2021 – 2022</p>
            <p><strong>Bachelor in Commerce</strong> | Helwan University | 2018 – 2021</p>
        </div>

        <div class="section">
            <h2>Skills</h2>
            <ul>
                <li>Proficient in Microsoft Office Suite</li>
                <li>Strong active listening and cognitive flexibility</li>
                <li>Effective public speaking and presentation skills</li>
            </ul>
        </div>

        <div class="section">
            <h2>Languages</h2>
            <p>English, Arabic</p>
        </div>

        <div class="section">
            <h2>Personal Information</h2>
            <p>Date of Birth: 01/10/1999</p>
            <p>Military Status: Exempted</p>
            <p>Health Case: Wheelchair user</p>
        </div>
    </div>
</body>
</html>
