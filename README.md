# My.bio
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой первый сайт</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Segoe UI', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: #fff;
        }
        .container {
            background: rgba(255,255,255,0.15);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 40px 25px;
            width: 90%;
            max-width: 400px;
            border: 1px solid rgba(255,255,255,0.2);
        }
        .emoji { font-size: 4rem; margin-bottom: 15px; }
        h1 { font-size: 2rem; margin-bottom: 10px; }
        p { opacity: 0.9; margin-bottom: 25px; line-height: 1.5; }
        .btn {
            display: inline-block;
            padding: 14px 35px;
            background: #fff;
            color: #764ba2;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            font-size: 1rem;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="emoji">🚀</div>
        <h1>Мой сайт в интернете!</h1>
        <p>Я создал и опубликовал этот сайт прямо с телефона. Это было просто!</p>
        <a class="btn" href="#">Привет, мир!</a>
    </div>
</body>
</html>
