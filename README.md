<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صفحة ويب بسيطة</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            direction: rtl;
            text-align: right;
        }
        header, footer {
            background-color: #f8f8f8;
            padding: 10px;
            text-align: center;
        }
        main {
            padding: 20px;
        }
        nav {
            margin: 10px 0;
        }
        nav a {
            margin: 0 10px;
            text-decoration: none;
            color: #333;
        }
    </style>
</head>
<body>
    <header>
        <h1>مرحباً بكم في صفحتي</h1>
    </header>
    <nav>
        <a href="#home">الرئيسية</a>
        <a href="#about">من نحن</a>
        <a href="#contact">اتصل بنا</a>
    </nav>
    <main>
        <section id="home">
            <h2>الرئيسية</h2>
            <p>هذه هي الصفحة الرئيسية لموقعنا. نحن سعداء بزيارتك.</p>
        </section>
        <section id="about">
            <h2>من نحن</h2>
            <p>نحن شركة تقدم خدمات مميزة لعملائنا.</p>
        </section>
        <section id="contact">
            <h2>اتصل بنا</h2>
            <p>يمكنك التواصل معنا عبر البريد الإلكتروني example@example.com.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 جميع الحقوق محفوظة</p>
    </footer>
</body>
</html>
