<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Анашым, туған күніңізбен!</title>
    <style>
        @keyframes backgroundAnimation {
            0% { background-color: #ffebcd; }
            50% { background-color: #ffe4b5; }
            100% { background-color: #ffdab9; }
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes heartAnimation {
            0% { transform: scale(1); opacity: 1; }
            50% { transform: scale(1.2); opacity: 0.7; }
            100% { transform: scale(1); opacity: 1; }
        }

        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            animation: backgroundAnimation 5s infinite alternate;
            padding: 50px;
        }

        h1 {
            font-size: 40px;
            color: #d2691e;
            animation: fadeIn 2s ease-in-out;
        }

        p {
            font-size: 24px;
            color: #8b4513;
            animation: fadeIn 3s ease-in-out;
        }

        .hearts {
            position: relative;
            display: inline-block;
            margin-top: 20px;
        }

        .heart {
            position: absolute;
            width: 30px;
            height: 30px;
            background-color: red;
            clip-path: polygon(50% 15%, 100% 40%, 80% 100%, 50% 80%, 20% 100%, 0 40%);
            animation: heartAnimation 1.5s infinite alternate;
        }

        .heart:nth-child(1) { left: -40px; top: 0; animation-delay: 0.3s; }
        .heart:nth-child(2) { left: 0; top: -20px; animation-delay: 0.6s; }
        .heart:nth-child(3) { left: 40px; top: 0; animation-delay: 0.9s; }

    </style>
</head>
<body>
    <h1>Анашым, туған күніңізбен құттықтаймын!</h1>
    <p>Сізге ұзақ ғұмыр, зор денсаулық, бақ-береке тілеймін!</p>
    <p>Әр күніңіз қуаныш пен махаббатқа толы болсын!</p>
    
    <div class="hearts">
        <div class="heart"></div>
        <div class="heart"></div>
        <div class="heart"></div>
    </div>
</body>
</html>
.
hb.html
.
https://github.com/vgjyf/Birthday-site.git
