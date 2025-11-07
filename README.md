<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>PagePal - Academic Resource Exchange</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(120deg, #e0eaff 0%, #f9f9ff 100%);
            color: #222;
        }
        .header {
            text-align: center;
            margin-top: 30px;
        }
        .logo {
            width: 100px;
            margin: 0 auto;
        }
        .tagline {
            font-size: 1.1rem;
            color: #5680e9;
            margin-bottom: 10px;
        }
        .container {
            display: flex;
        }
        .sidebar {
            width: 220px;
            min-height: 100vh;
            background: linear-gradient(180deg, #f5fcff 60%, #eaf6fb 100%);
            padding: 32px 12px 24px 18px;
            box-shadow: 0 0 8px #cceaff22;
            display: flex;
            flex-direction: column;
            align-items: flex-start;
            position: fixed;
            top: 0; left: 0;
            height: 100vh;
        }
        .menu {
            width: 100%;
            margin-bottom: 30px;
        }
        .menu label {
            font-weight: bold;
            font-size: 1.09rem;
            margin-bottom: 9px;
            display: inline-block;
        }
        .menu a {
            display: flex;
            align-items: center;
            padding: 8px 0 8px 16px;
            text-decoration: none;
            font-size: 1rem;
            color: #3a506b;
            border-radius: 8px;
            margin-bottom: 1px;
            transition: background 0.15s;
        }
        .menu a:hover {
            background: #e1eaff;
        }
        .book-sticker {
            width: 28px; height: 28px;
            margin-right: 9px;
        }
        .main-content {
            margin-left: 250px;
            padding: 36px 30px 60px 30px;
            width: 100%;
        }
        .subject-distribution {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 25px;
        }
        .subject-card {
            background: #fafaff;
            border-radius: 12px;
            box-shadow: 0 2px 10px #d6e4f51c;
            padding: 18px 24px;
            min-width: 150px;
            max-width: 200px;
            margin-bottom: 12px;
            text-align: center;
        }
        .subject-card .emoji {
            font-size: 1.6rem;
            margin-bottom: 6px;
        }
        .pyq-section {
            margin-top: 36px;
        }
        .pyq-list {
            display: flex;
            gap: 22px;
            margin-top: 10px;
        }
        .pyq-card {
            background: #e3ecff;
            border-radius: 10px;
            padding: 14px 20px;
            box-shadow: 0 1px 4px #a3aed122;
        }
        .contact-box {
            position: fixed;
            left: 0;
            bottom: 0;
            margin: 0 0 18px 24px;
            background: #f2fbff;
            border-radius: 15px 15px 0 0;
            padding: 19px 18px;
            box-shadow: 0 0 10px #cde0ff44;
            font-size: 0.97rem;
        }
        a {
            color: #4276d8;
        }
        @media (max-width: 1000px) {
            .container { flex-direction: column; }
            .sidebar { position: static; width: 100vw; min-height: initial; height: auto; flex-direction: row; }
            .main-content { margin-left: 0; }
            .contact-box { display: none; }
        }
    </style>
</head>
<body>
    <div class="header">
        <img src="Screenshot-2025-11-08-01.34.10.jpg" alt="PagePal Logo" class="logo">
        <div class="tagline">India’s Most Student-Friendly Academic Resource Exchange</div>
    </div>
    <div class="container">
        <nav class="sidebar">
            <div class="menu">
                <label>Universities</label>
                <a href="#"><span class="book-sticker">🏫</span>Delhi University</a>
                <a href="#"><span class="book-sticker">🏫</span>Mumbai University</a>
                <a href="#"><span class="book-sticker">🏫</span>Lucknow University</a>
            </div>
            <div class="menu">
                <label>Subjects</label>
                <a href="#"><span class="book-sticker">📘</span>Macroeconomics</a>
                <a href="#"><span class="book-sticker">📗</span>Stats</a>
                <a href="#"><span class="book-sticker">📒</span>Accounts</a>
                <a href="#"><span class="book-sticker">📙</span>Physics</a>
                <a href="#"><span class="book-sticker">📔</span>Chemistry</a>
                <a href="#"><span class="book-sticker">📕</span>Bio</a>
                <a href="#"><span class="book-sticker">📚</span>Maths</a>
            </div>
        </nav>
        <main class="main-content">
            <h2>Subject Distribution</h2>
            <div class="subject-distribution">
                <div class="subject-card"><div class="emoji">📘</div>Macroeconomics Resources</div>
                <div class="subject-card"><div class="emoji">📗</div>Stats Resources</div>
                <div class="subject-card"><div class="emoji">📒</div>Accounts Resources</div>
                <div class="subject-card"><div class="emoji">📙</div>Physics Resources</div>
                <div class="subject-card"><div class="emoji">📔</div>Chemistry Resources</div>
                <div class="subject-card"><div class="emoji">📕</div>Bio Resources</div>
                <div class="subject-card"><div class="emoji">📚</div>Maths Resources</div>
            </div>
            <div class="pyq-section">
                <h3>Previous Year Questions (PYQs)</h3>
                <div class="pyq-list">
                    <div class="pyq-card">Delhi University PYQs</div>
                    <div class="pyq-card">Mumbai University PYQs</div>
                    <div class="pyq-card">Lucknow University PYQs</div>
                </div>
            </div>
        </main>
        <div class="contact-box">
            <strong>Contact</strong><br>
            Founder: Amrit Yadav<br>
            Email: <a href="mailto:starkaa099@gmail.com">starkaa099@gmail.com</a><br>
            LinkedIn: <a href="https://www.linkedin.com/in/amrit-yadav-b29637359" target="_blank">www.linkedin.com/in/amrit-yadav-b29637359</a>
        </div>
    </div>
</body>
</html>
