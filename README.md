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

        .content {
            display: none;
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

        .content.active {
            display: block;
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

        .nav button {
            text-decoration: none;
            color: white;
            background: #ff1493;
            padding: 10px 15px;
            border-radius: 10px;
            margin: 5px;
            display: inline-block;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="nav">
        <button onclick="showPage('home')">Home</button>
        <button onclick="showPage('about')">About</button>
        <button onclick="showPage('shop')">Shop</button>
    </div>
    
    <h1>Yollo</h1>
    
    <div id="home" class="content active">This is your first website!</div>
    <div id="about" class="content">Welcome to the About section!</div>
    <div id="shop" class="content">Check out our cute shop!</div>
    
    <button class="toggle-btn" onclick="togglePosition()">Move Up/Down</button>
    
    <script>
        let moved = false;
        function togglePosition() {
            let activePage = document.querySelector('.content.active');
            if (moved) {
                activePage.style.transform = 'translateY(0px)';
            } else {
                activePage.style.transform = 'translateY(50px)';
            }
            moved = !moved;
        }

        function showPage(pageId) {
            let pages = document.querySelectorAll('.content');
            pages.forEach(page => page.classList.remove('active'));
            document.getElementById(pageId).classList.add('active');
        }
    </script>
</body>
</html>
