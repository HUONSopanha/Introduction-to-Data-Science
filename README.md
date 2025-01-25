<!DOCTYPE html>
<html class="no-js" lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - Diabetes Blog</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css?family=Poppins:200i,300,300i,400,400i,500,500i,600,600i,700,700i,800,800i,900,900i&display=swap" rel="stylesheet">
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <!-- Font Awesome CSS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <style>
        /* Global Styles */
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
        }

        /* Header Styles */
        header {
            background-color: #ffffff;
            padding: 20px 0;
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 999;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .header-container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            display: flex;
            align-items: center;
        }

        .logo img {
            width: 100px;
            height: auto;
            margin-right: 20px;
        }

        .logo img[alt="Logo 2"] {
            width: 150px; /* Increase the width as desired */
            height: auto; /* This will maintain the aspect ratio */
        }


        .school-name {
            font-size: 24px;
            font-weight: bold;
            color: #00358A;
            margin-bottom: 5px;
        }

        .department-name {
            font-size: 18px;
            font-weight: bold;
            color: #E53535;
        }

        .menu {
            display: flex;
            justify-content: center;
        }

        .menu ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
        }

        .menu ul li {
            margin: 0 20px;
        }

        .menu ul li a {
            color: #333;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        .menu ul li a:hover {
            color: #ffd700;
        }

        /* Content Styles */
        .content-container {
            max-width: 800px;
            margin: 180px auto 120px;
            padding: 40px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 30px rgba(0, 0, 0, 0.1);
        }

        .team-member {
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-bottom: 20px;
            border-bottom: 1px solid #ccc;
            padding-bottom: 20px;
         }

        .team-member .member-info {
            flex: 1;
            margin-right: 20px;
        }

        .team-member .member-image {
            flex: 0 0 auto;
            max-width: 300px;
        }

        .team-member .member-image img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }

        h1 {
            color: #007bff;
            text-align: center;
            margin-bottom: 100px;
        }

        /* Responsive Styles */
        @media (max-width: 768px) {
            .header-container {
                flex-direction: column;
                align-items: center;
            }

            .logo {
                margin-bottom: 100px;
            }

            .menu ul {
                flex-direction: column;
                align-items: center;
            }

            .menu ul li {
                margin: 10px 0;
            }

            .content-container {
                margin-top: 180px;
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="header-container">
            <div class="logo">
                <img src="https://upload.wikimedia.org/wikipedia/en/f/f7/Institute_of_Technology_of_Cambodia_logo.png" alt="Logo 1">
                <div>
                    <div class="school-name">Institute of Technology of Cambodia</div>
                    <div class="department-name">Department of Applied Mathematics and Statistics</div>
                </div>
                <img src="https://th.bing.com/th/id/OIP.9_NVZh7wq2gK-GMTE8mDKQHaGF?rs=1&pid=ImgDetMain" alt="Logo 2">
            </div>
            <nav class="menu">
                <ul>
                    <li><a href="/">Home</a></li>
                    <li><a href="/diabetes_blog/">Diabetes Blog</a></li>
                    <li><a href="/about_us/">About Us</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="content-container">
        <h1>About Us</h1>
        <p style="text-align: justify;">   We are junior students from the Department of Applied Mathematics and Statistics at the Institute of Technology of Cambodia. This project represents the culmination of our efforts in two key areas: Object-Oriented Programming and Introduction to Data Science.</p>
        <p style="text-align: justify;">  Our primary objective is to develop a predictive model for assessing the likelihood of diabetes using machine learning techniques applied to existing data. To enhance user experience, we are creating a user-friendly interface that allows individuals to input essential health information, including glucose levels, skin thickness, insulin levels, body mass index (BMI), age, and the number of pregnancies. This interface is being developed using Django and Python, enabling the construction of a robust and efficient web application.</p>
        <p style="text-align: justify;">   We would like to express our profound gratitude to our esteemed lecturers, Dr. Phauk Sokkhey, our Introduction to Data Science lecturer, and Mr. Ngin Kimlong, our Object-Oriented Programming lecturer. Their invaluable support, guidance, and expertise have significantly contributed to the success of this project.</p>
        <hr>
        <h2 style="text-align: center;">Team Members</h2>
        
    <div class="team-member">
        <div class="member-info">
            <strong>Huon Sophana</strong>
            <p>ID: e20220209</p>
            <p>Position:</p>
            <ul>
                
                <li>Project Manager (OOP)</li>
                
                <li>Data Engineer (IDS)</li>
                
            </ul>
            <p>Contact:</p>
            <ul>
                
                <li>Telegram: <a href="https://t.me/Loid168">https://t.me/Loid168</a></li>
                
                <li>Email: <a href="sopanhahuon@gmail.com">sopanhahuon@gmail.com</a></li>
                
            </ul>
        </div>
        <div class="member-image">
        
             
            <img src="https://i.imgur.com/ixZ4lq9.jpeg" alt="Huon Sophana">
            
    
        </div>
    </div>

    <div class="team-member">
        <div class="member-info">
            <strong>HANG Muykhorng</strong>
            <p>ID: e20220166</p>
            <p>Position:</p>
            <ul>
                
                <li>Frontend Developer (OOP)</li>
                
                <li>Data Analyst (IDS)</li>
                
            </ul>
            <p>Contact:</p>
            <ul>
                
                <li>Telegram: <a href=" https://t.me/Muykhorng"> https://t.me/Muykhorng</a></li>
                
                <li>Email: <a href="muykhorng520@gmail.com">muykhorng520@gmail.com</a></li>
                
            </ul>
        </div>
        <div class="member-image">
        
             
            <img src="https://i.imgur.com/N27II4C.jpeg" alt="HANG Muykhorng">
            
    
        </div>
    </div>

    <div class="team-member">
        <div class="member-info">
            <strong>HUN Sopheak</strong>
            <p>ID: e20220446</p>
            <p>Position:</p>
            <ul>
                
                <li>Backend Developer (OOP)</li>
                
                <li>Project Manager (IDS)</li>
                
            </ul>
            <p>Contact:</p>
            <ul>
                
                <li>Telegram: <a href="https://t.me/sofia_desu">https://t.me/sofia_desu</a></li>
                
                <li>Email: <a href="sopheakhun593@gmail.com">sopheakhun593@gmail.com</a></li>
                
            </ul>
        </div>
        <div class="member-image">
        
             
            <img src="https://i.imgur.com/eASiCUQ.jpeg" alt="HUN Sopheak">
            
    
        </div>
    </div>

    <div class="team-member">
        <div class="member-info">
            <strong>CHHOUK Phalthunin</strong>
            <p>ID: e20220467</p>
            <p>Position:</p>
            <ul>
                
                <li>Backend Developer (OOP)</li>
                
                <li>Document Specialist (IDS)</li>
                
            </ul>
            <p>Contact:</p>
            <ul>
                
                <li>Telegram: <a href="https://t.me/Phalthunin">https://t.me/Phalthunin</a></li>
                
                <li>Email: <a href="phalthunin@gmail.com">phalthunin@gmail.com</a></li>
                
            </ul>
        </div>
        <div class="member-image">
        
             
            <img src="https://i.imgur.com/dgTinKp.jpeg" alt="CHHOUK Phalthunin">
            
    
        </div>
    </div>

    <div class="team-member">
        <div class="member-info">
            <strong>CHOEURN Brospov</strong>
            <p>ID: 20221157</p>
            <p>Position:</p>
            <ul>
                
                <li>UI/UX (OOP)</li>
                
                <li>Data Collector(IDS)</li>
                
            </ul>
            <p>Contact:</p>
            <ul>
                
                <li>Telegram: <a href="https://t.me/fong_enjoyeasylife">https://t.me/fong_enjoyeasylife</a></li>
                
                <li>Email: <a href="brozzpov15022000@gmail.com">brozzpov15022000@gmail.com</a></li>
                
            </ul>
        </div>
        <div class="member-image">
        
             
            <img src="https://i.imgur.com/nJhCgm7.jpeg" alt="CHOEURN Brospov">
            
    
        </div>
    </div>

</body>
</html>


