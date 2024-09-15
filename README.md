<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ahmed Samy's CV</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            animation: fadeIn 1s;
        }
        h1, h2, h3 {
            color: #007bff;
        }
        h1 {
            font-size: 2.5em;
            text-align: center;
            margin-bottom: 10px;
        }
        p, ul {
            line-height: 1.6;
        }
        ul {
            padding-left: 20px;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        .section {
            margin-bottom: 20px;
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
    </style>
</head>
<body>
    <div class="container">
        <h1>Ahmed Samy</h1>
        <p>Email: <a href="mailto:ahmedsami2772@gmail.com">ahmedsami2772@gmail.com</a></p>
        <p>Phone: 01115749326</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/ahmed-samy2772/">Profile</a></p>

        <div class="section">
            <h2>Summary</h2>
            <p>Coming from a technical educational background with a Bachelor of Commerce (Accounting) and landed an Account Assistant (Sales) through Training and recruitment. Worked with 10 cross-functional teams and coordinated with various business partners toward the successful growth of an e-commerce company.</p>
        </div>

        <div class="section">
            <h2>Professional Experience</h2>
            <h3>Amazon</h3>
            <p><strong>Account Representative</strong> | 01/2024 – Present | Cairo, Egypt</p>
            <ul>
                <li>Expanding working across different projects and leading business projects.</li>
            </ul>
            <p><strong>Account Assistant</strong> | 06/2022 – Present | Cairo, Egypt</p>
            <ul>
                <li>Conducted a detailed analysis of account deactivation trends on the EG marketplace, reducing future deactivations by 40%.</li>
                <li>Resolved 200+ enforced accounts through thorough audits.</li>
                <li>Delivered analyses to drive +70% retention for terminated sellers.</li>
            </ul>
        </div>

        <div class="section">
            <h3>Al-Hassan Foundation</h3>
            <p><strong>Training and Recruitment Coordinator</strong> | 01/2021 – 06/2022 | Giza</p>
            <ul>
                <li>Managed a process re-engineering project to improve service processes.</li>
                <li>Coordinated between service providers and beneficiaries.</li>
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
                <li>Excellent computer literacy (Microsoft Office)</li>
                <li>Active listening and cognitive flexibility</li>
                <li>Public speaking and event speaking</li>
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
