<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Бронювання місць у кафе</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 15px;
            font-size: 24px;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        .cafe-list {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .cafe {
            background: white;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            width: 30%;
        }
        .cafe img {
            width: 100%;
            border-radius: 8px;
        }
        .cafe button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            width: 100%;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>Бронювання місць у кафе</header>
    <div class="container">
        <h2>Оберіть кафе</h2>
        <div class="cafe-list">
            <div class="cafe">
                <img src="cafe1.jpg" alt="Кафе 1">
                <h3>Кафе "Мрія"</h3>
                <p>Адреса: вул. Центральна, 15</p>
                <button>Забронювати</button>
            </div>
            <div class="cafe">
                <img src="cafe2.jpg" alt="Кафе 2">
                <h3>Кафе "Сонце"</h3>
                <p>Адреса: вул. Лісова, 22</p>
                <button>Забронювати</button>
            </div>
            <div class="cafe">
                <img src="cafe3.jpg" alt="Кафе 3">
                <h3>Кафе "Латте"</h3>
                <p>Адреса: вул. Шевченка, 10</p>
                <button>Забронювати</button>
            </div>
        </div>
    </div>
</body>
</html>
