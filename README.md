<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Eid Mubarak</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
            color: white;
            text-align: center;
        }

        .container {
            margin-top: 100px;
        }

        h1 {
            font-size: 60px;
            color: #ffd700;
            text-shadow: 2px 2px 10px #000;
        }

        p {
            font-size: 22px;
            margin-top: 20px;
        }

        .moon {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            background: #ffd700;
            position: relative;
            margin: 40px auto;
            box-shadow: 0 0 30px #ffd700;
        }

        .moon::after {
            content: "";
            width: 120px;
            height: 120px;
            background: #2c5364;
            border-radius: 50%;
            position: absolute;
            top: -10px;
            left: 20px;
        }

        .btn {
            margin-top: 30px;
            padding: 12px 25px;
            background: #ffd700;
            color: black;
            border: none;
            border-radius: 25px;
            font-size: 18px;
            cursor: pointer;
            transition: 0.3s;
        }

        .btn:hover {
            background: white;
            color: black;
        }

        footer {
            margin-top: 80px;
            font-size: 14px;
            opacity: 0.7;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="moon"></div>

        <h1>Eid Mubarak 🌙</h1>

        <p>
            Allah aapki zindagi ko khushiyon se bhar de,<br>
            aur aapki har dua qubool ho. Ameen!
        </p>

        <button class="btn" onclick="alert('Eid Mubarak! 🎉')">
            Send Wishes
        </button>
    </div>

    <footer>
        Made with ❤️ for Eid Celebration
    </footer>

</body>
</html>
