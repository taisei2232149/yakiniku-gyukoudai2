<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>焼肉牛工大</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff5e6;
            color: #333;
        }
        header {
            background-color: #c0392b;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        .container {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }
        .menu {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .menu-item {
            border: 1px solid #ddd;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 300px;
            background-color: white;
            text-align: center;
        }
        .menu-item img {
            width: 100%;
            height: auto;
        }
        .menu-item h3 {
            margin: 10px 0;
            color: #c0392b;
        }
        .menu-item p {
            margin: 10px;
            color: #555;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>焼肉牛工大</h1>
        <p>最高の焼肉体験を提供します！</p>
    </header>
    <div class="container">
        <h2>おすすめメニュー</h2>
        <div class="menu">
            <div class="menu-item">
                <img src="images/menu1.jpg" alt="特選カルビ">
                <h3>特選カルビ</h3>
                <p>柔らかくジューシーな一品です。</p>
            </div>
            <div class="menu-item">
                <img src="images/menu2.jpg" alt="上タン塩">
                <h3>上タン塩</h3>
                <p>さっぱりした味わいの塩タン。</p>
            </div>
            <div class="menu-item">
                <img src="images/menu3.jpg" alt="石焼ビビンバ">
                <h3>石焼ビビンバ</h3>
                <p>ご飯と具材の香ばしさが絶妙。</p>
            </div>
        </div>
    </div>
    <footer>
        <p>© 2024 焼肉牛工大. All Rights Reserved.</p>
    </footer>
</body>
</html>
