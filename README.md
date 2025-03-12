<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Cute Website</title>
    <style>
        body {
            background-image: url('https://th.bing.com/th/id/R.668eec52e2f90f9e517c65905a846704?rik=ADT3vRLOgC1syg&pid=ImgRaw&r=0');
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            background-color: #f6adc6;
            font-family: 'Lucida Handwriting', cursive;
            padding: 50px;
            margin: 0;
            position: relative;
        }

        h1 {
            text-align: center;
            color: #ff1493;
            font-size: 32px;
        }

        p {
            color: #145A32;
            background-color: rgba(255, 240, 245, 0.8);
            padding: 15px;
            border-radius: 15px;
            border: 2px solid #ff85a2;
            text-align: center;
            width: 50%;
            margin: 20px auto;
            font-size: 18px;
            box-shadow: 0 0 10px #ff66b2;
        }

        .toggle-btn {
            display: block;
            margin: 20px auto;
            padding: 10px 20px;
            background-color: #ff85a2;
            color: white;
            font-size: 16px;
            border: none;
            cursor: pointer;
            border-radius: 10px;
        }

        .nav {
            text-align: center;
            margin-bottom: 20px;
        }

        .nav a {
            text-decoration: none;
            color: white;
            background: #ff1493;
            padding: 10px 15px;
            border-radius: 10px;
            margin: 5px;
            display: inline-block;
        }
    </style>
</head>
<body>
    <div class="nav">
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
        <a href="shop.html">Shop</a>
    </div>
    
    <h1>Yollo</h1>
    <p id="text-box">This is your <br> first website!</p>
    <button class="toggle-btn" onclick="togglePosition()">Move Up/Down</button>
    
    <script>
        let moved = false;
        function togglePosition() {
            let textBox = document.getElementById('text-box');
            if (moved) {
                textBox.style.transform = 'translateY(0px)';
            } else {
                textBox.style.transform = 'translateY(50px)';
            }
            moved = !moved;
        }
    </script>
</body>
</html>
