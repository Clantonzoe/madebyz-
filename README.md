<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Cute Website</title>
    <link rel="icon" type="image/png" href="https://github.githubassets.com/assets/yolo-default-be0bbff04951.png">
    <style>
        /* Website background settings */
        body {
            background-image: url('https://th.bing.com/th/id/R.668eec52e2f90f9e517c65905a846704?rik=ADT3vRLOgC1syg&pid=ImgRaw&r=0');
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            background-color: #f6adc6; /* Nadeshiko Pink as fallback */
            font-family: 'Lucida Handwriting', cursive;
            margin: 0;
            padding: 0;
        }

        /* Navigation bar styling */
        nav ul {
            list-style-type: none;
            padding: 0;
            text-align: center;
            background-color: rgba(255, 240, 245, 0.8);
            margin: 0;
            font-family: 'Pacifico', cursive;
        }

        nav ul li {
            display: inline;
            margin: 10px;
        }

        nav ul li a {
            text-decoration: none;
            color: #ff1493; /* Hot pink color */
            font-size: 30px;
            padding: 10px 20px;
        }

        /* Section Styling */
        .section {
            padding: 50px 20px;
            text-align: center;
            color: #ff1493;
        }

        /* Products section styling */
        .gallery {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            margin-top: 30px;
        }

        .product {
            text-align: center;
            width: 250px;
        }

        .product img {
            width: 100%;
            max-width: 200px;
            border-radius: 15px;
            box-shadow: 0 0 10px #ff66b2;
        }

        .product h3 {
            color: #ff1493;
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
            box-shadow: 0 0 5px #ff66b2;
        }

        /* Wallpapers Sections */
        #phone-wallpapers {
            background-color: rgba(255, 240, 245, 0.8);
        }

        #phone-wallpapers img {
            width: 100%;
            max-width: 400px;
            margin: 20px auto;
            display: block;
            border-radius: 15px;
        }

        #tablet-computer-wallpapers {
            background-color: rgba(255, 240, 245, 0.8);
        }

        #tablet-computer-wallpapers img {
            width: 100%;
            max-width: 800px;
            margin: 20px auto;
            display: block;
            border-radius: 15px;
        }

        /* Contact Section */
        #contact {
            background-color: rgba(255, 240, 245, 0.8);
        }

        /* Smooth Scrolling */
        html {
            scroll-behavior: smooth;
        }
    </style>
</head>
<body>

    <!-- Navigation Links with Hearts -->
    <nav>
        <ul>
            <li><a href="#phone-wallpapers">💗 Phone Wallpapers</a></li>
            <li><a href="#tablet-computer-wallpapers">💗 Tablet & Computer Wallpapers</a></li>
            <li><a href="#products">💗 Products</a></li>
            <li><a href="#contact">💗 Contact Us</a></li>
        </ul>
    </nav>

    <!-- Phone Wallpapers Section -->
    <div id="phone-wallpapers" class="section">
        <h1>Phone Wallpapers 💖</h1>
        <p>Here are some cute wallpapers for your phone! 📱✨</p>
        <img src="https://i.pinimg.com/736x/ec/77/25/ec772572084f3669a1d93ec4ac07f480.jpg" alt="Ochaco Uraraka pink phone wallpaper">
        <p>🌺 Ochaco Uraraka pink phone wallpaper 🌺</p>
    </div>

    <!-- Tablet & Computer Wallpapers Section -->
    <div id="tablet-computer-wallpapers" class="section">
        <h1>Tablet & Computer Wallpapers 💖</h1>
        <p>Here are some wallpapers perfect for your tablet or computer! 💻✨</p>
        <img src="https://wallpaperaccess.com/full/1167293.jpg" alt="Pink Aesthetic Tablet Wallpaper">
        <img src="https://wallpapercave.com/wp/wp10497374.jpg" alt="Cute Room Tablet Wallpaper">
    </div>

    <!-- Products Section -->
    <div id="products" class="section">
        <h1>Our Cute Products 💖</h1>
        <div class="gallery">
            <div class="product">
                <img src="https://th.bing.com/th/id/R.1c6e1a5b560d3ec587e3880887bc53ff?rik=wyTBAYKA7bpmUg&riu=http%3a%2f%2fimages5.fanpop.com%2fimage%2fphotos%2f25600000%2fHello-Kitty-Sitting-hello-kitty-25604546-1210-1429.jpg&ehk=XFvh1tuK1a095ImwQYh02IJ1p5UxyX%2fk5JdMnGn306Y%3d&risl=&pid=ImgRaw&r=0" alt="Hello Kitty">
                <h3>💖 Hello Kitty Plushie 💖</h3>
                <p>The softest and cutest Hello Kitty plush, perfect for cuddles! 🎀</p>
            </div>
            <!-- Add more products here -->
        </div>
    </div>

    <!-- Contact Section -->
    <div id="contact" class="section">
        <h1>Contact Us 💌</h1>
        <p>If you have any questions, feel free to reach out! 🌸</p>
        <!-- Contact info or form goes here -->
    </div>

</body>
</html>
