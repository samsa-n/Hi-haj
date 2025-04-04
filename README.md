# Hi-haj
Ne diakujte
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Розрахунок додаткових виплат за дотримання тверезості</title>
    <style>
        body {
            background-color: #000;
            color: #fff;
            text-align: center;
            font-family: Arial, sans-serif;
            overflow: hidden;
        }
        .smiley {
            position: absolute;
            font-size: 2rem;
            animation: pop 3s infinite;
        }
        @keyframes pop {
            0% { transform: scale(1); opacity: 1; }
            50% { transform: scale(1.5); opacity: 0.5; }
            100% { transform: scale(1); opacity: 1; }
        }
    </style>
</head>
<body>
    <h1>Додаткові виплати за тверезий стан військовослужбовця</h1>
    <p>Завантаження даних...</p>
    <script>
        function spawnSmiley() {
            let smiley = document.createElement("div");
            smiley.innerText = "🤣";
            smiley.classList.add("smiley");
            smiley.style.left = Math.random() * window.innerWidth + "px";
            smiley.style.top = Math.random() * window.innerHeight + "px";
            document.body.appendChild(smiley);
            setTimeout(() => smiley.remove(), 3000);
        }
        setInterval(spawnSmiley, 300);
    </script>
</body>
</html>
