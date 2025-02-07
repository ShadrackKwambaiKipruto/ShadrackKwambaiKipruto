<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile Clone - Shadrack Kwambai Kipruto</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            background: linear-gradient(to right, green, yellow, purple, white, red, pink, black);
            font-family: Arial, sans-serif;
            text-align: center;
            color: white;
        }
        .profile img {
            width: 150px;
            border-radius: 50%;
            margin-top: 20px;
        }
        .repositories .repo {
            background: rgba(0, 0, 0, 0.8);
            padding: 15px;
            margin: 15px;
            border-radius: 10px;
            color: white;
        }
        .repo img {
            width: 100%;
            border-radius: 5px;
        }
        a {
            color: yellow;
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <div class="profile">
            <img src="profile.jpg" alt="Profile Picture">
            <h1>Shadrack Kwambai Kipruto</h1>
            <p>Data Analyst | SQL | Python | Tableau | Power BI</p>
            <a href="https://github.com/shadrackkipruto" target="_blank">View My GitHub Profile</a>
        </div>
    </header>
    
    <main>
        <section class="about">
            <h2>About Me</h2>
            <p>Passionate Data Analyst with experience in data visualization, statistical modeling, and business intelligence. Skilled in Python, SQL, and Tableau.</p>
        </section>
        
        <section class="repositories">
            <h2>Repositories</h2>
            <div class="repo">
                <h3>Data Visualization Project</h3>
                <p>A Tableau dashboard analyzing customer behavior trends.</p>
                <img src="dataviz.png" alt="Data Visualization Project">
                <a href="https://github.com/shadrackkipruto/dataviz" target="_blank">View Repo</a>
            </div>
            <div class="repo">
                <h3>SQL Data Cleaning</h3>
                <p>A collection of SQL queries to clean and optimize datasets.</p>
                <img src="sqlcleaning.png" alt="SQL Data Cleaning">
                <a href="https://github.com/shadrackkipruto/sqlcleaning" target="_blank">View Repo</a>
            </div>
        </section>
        
        <section class="skills">
            <h2>Skills</h2>
            <ul>
                <li>Python</li>
                <li>SQL</li>
                <li>Tableau</li>
                <li>Power BI</li>
                <li>Excel</li>
            </ul>
        </section>
    </main>
    
    <script src="script.js"></script>
</body>
</html>
