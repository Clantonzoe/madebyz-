
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Cute Product Shop 🎀</title>
<link rel="icon" type="image/x-icon" href="https://th.bing.com/th/id/R.04a3403bd8a45887c85b8edaaeb4cd1c?rik=ImF%2bvdp%2bC3ONQA&pid=ImgRaw&r=0">

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
    
    <!-- Material Symbols (Optional for Icons) -->
    <style>
        .material-symbols-outlined {
            font-variation-settings:
            'FILL' 0,
            'wght' 400,
            'GRAD' 0,
            'opsz' 24;
        }
    </style>

    <!-- 🎀 Website Styling -->
    <style>
        :root {
            --pink-main: #ff1493;
            --pink-light: #fff0f5;
            --pink-glow: #ff66b2;
            --background-color: #f6adc6;
            --text-green: #145A32;
        }

        body {
            background: url('https://th.bing.com/th/id/R.668eec52e2f90f9e517c65905a846704?rik=ADT3vRLOgC1syg&pid=ImgRaw&r=0') no-repeat center center fixed;
            background-size: cover;
            background-color: var(--background-color);
            font-family: 'Lucida Handwriting', cursive;
            padding: 50px;
            margin: 0;
            border: 10px solid transparent;
            background-clip: padding-box;
            position: relative;
        }

        /* Emoji Borders */
        body::before, body::after {
            content: "🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸";
            display: block;
            text-align: center;
            font-size: 20px;
            position: absolute;
            left: 0;
            width: 100%;
            color: var(--pink-main);
            z-index: 100;
        }

        body::before {
            top: 0;
        }

        body::after {
            position: fixed;
            bottom: 0;
        }

        @media (max-width: 1024px) {
            body::before, body::after {
                content: "🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸";
                font-size: 18px;
            }
        }

        @media (max-width: 600px) {
            body::before, body::after {
                content: "🎀🌸🎀🌸🎀🌸";
                font-size: 16px;
            }
        }

        /* Navigation Bar */
        nav {
            background-color: rgba(255, 182, 193, 0.9);
            padding: 10px 20px;
            text-align: center;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
        }

        nav a {
            text-decoration: none;
            color: var(--pink-main);
            font-size: 18px;
            margin: 0 15px;
            font-family: 'Pacifico', cursive;
        }

        nav a:hover {
            color: var(--pink-glow);
            text-decoration: underline;
        }

        /* Titles & Paragraphs */
        h1 {
            text-align: center;
            color: var(--pink-main);
            font-size: 32px;
        }

        p {
            color: var(--text-green);
            background-color: rgba(255, 240, 245, 0.8);
            padding: 15px;
            border-radius: 15px;
            border: 2px solid #ff85a2;
            text-align: center;
            width: 50%;
            margin: 20px auto;
            font-size: 18px;
            box-shadow: 0 0 10px var(--pink-glow);
        }

        /* Products Gallery */
        .gallery {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            margin-top: 40px;
        }

        .product {
            text-align: center;
            width: 250px;
        }

        .product img {
            width: 100%;
            border-radius: 15px;
            box-shadow: 0 0 10px var(--pink-glow);
        }

        .product h3 {
            color: var(--pink-main);
            font-size: 22px;
            font-family: 'Pacifico', cursive;
            margin-top: 10px;
        }

        .product p {
            color: #ff69b4;
            background-color: rgba(255, 240, 245, 0.8);
            padding: 15px;
            border-radius: 15px;
            font-size: 20px;
            font-family: 'Pacifico', cursive;
            box-shadow: 0 0 5px var(--pink-glow);
        }
    </style>
</head>
<body>

    <!-- Navigation -->
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#products">Products</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Products Section -->
    <section id="products">
        <h1>Our Cute Products 💖</h1>
        <div class="gallery">
            <div class="product">
                <img src="https://th.bing.com/th/id/R.1c6e1a5b560d3ec587e3880887bc53ff?rik=wyTBAYKA7bpmUg&riu=http%3a%2f%2fimages5.fanpop.com%2fimage%2fphotos%2f25600000%2fHello-Kitty-Sitting-hello-kitty-25604546-1210-1429.jpg&ehk=XFvh1tuK1a095ImwQYh02IJ1p5UxyX%2fk5JdMnGn306Y%3d&risl=&pid=ImgRaw&r=0" alt="Hello Kitty Plush">
                <h3>💖 Hello Kitty Plushie 💖</h3>
                <p>The softest and cutest Hello Kitty plush, perfect for cuddles! 🎀</p>
            </div>

            <div class="product">
                <img src="https://wallpaperaccess.com/full/1167293.jpg" alt="Pink Aesthetic Wallpaper">
                <h3>🌸 Dreamy Aesthetic Wallpaper 🌸</h3>
                <p>Transform your room with this beautiful soft pink aesthetic vibe! ✨</p>
            </div>

            <div class="product">
                <img src="https://wallpapercave.com/wp/wp10497374.jpg" alt="Pastel Bedroom">
                <h3>🎀 Cozy Pastel Bedroom 🎀</h3>
                <p>Get inspired by this super cozy pastel bedroom setup! So dreamy~ ☁️</p>
            </div>
        </div>
    </section>

</body>
</html>
