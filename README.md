<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>User Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #f0f2f5;
            color: #333;
            line-height: 1.6;
        }

        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
        }

        .profile-card {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            padding: 30px;
        }

        .profile-header {
            text-align: center;
            margin-bottom: 30px;
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 20px;
        }

        .name {
            font-size: 28px;
            font-weight: bold;
            color: #1a73e8;
        }

        .title {
            font-size: 18px;
            color: #666;
            margin-top: 5px;
        }

        .bio {
            text-align: center;
            margin: 20px 0;
            color: #444;
        }

        .info-section {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin-top: 30px;
        }

        .info-item {
            background-color: #f8f9fa;
            padding: 15px;
            border-radius: 8px;
        }

        .info-label {
            font-weight: bold;
            color: #1a73e8;
            margin-bottom: 5px;
        }

        .social-links {
            text-align: center;
            margin-top: 30px;
        }

        .social-links a {
            color: #1a73e8;
            text-decoration: none;
            margin: 0 10px;
            font-size: 16px;
        }

        .social-links a:hover {
            text-decoration: underline;
        }

        @media (max-width: 600px) {
            .info-section {
                grid-template-columns: 1fr;
            }
            
            .container {
                margin: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="profile-card">
            <div class="profile-header">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT8VbvTvQFYrD7AYI3IKB8rdP-vvYm2LkBl-w&s" alt="Profile Picture" class="profile-img">
                <h1 class="name">Suruthi S</h1>
                <p class="title">Web Developer</p>
            </div>

            <div class="bio">
                <p>Hello! I'm a passionate web developer with 5 years of experience creating beautiful and functional websites.</p>
            </div>

            <div class="info-section">
                <div class="info-item">
                    <div class="info-label">Email</div>
                    <div>suruthisankar64@gmail.com</div>
                </div>
                <div class="info-item">
                    <div class="info-label">Location</div>
                    <div>Theni, Tamil Nadu,India </div>
                </div>
                <div class="info-item">
                    <div class="info-label">Phone</div>
                    <div>6374472458</div>
                </div>
                <div class="info-item">
                    <div class="info-label">Joined</div>
                    <div>March 2025</div>
                </div>
            </div>

            <div class="social-links">
                <a href="https://www.linkedin.com/in/suruthi-sankar-97855b2a2?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">LinkedIn</a>
                <a href="https://github.com/SuruthiSankar">GitHub</a> 
            </div>
        </div>
    </div>
</body>
</html>
