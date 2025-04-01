<!-- Favicon (Make sure favicon-32x32.png is in the same folder as this file) -->
<link rel="icon" type="image/png" href="favicon-32x32.png">

<style>
    /* Website background settings */
    body {
        background-image: url('https://th.bing.com/th/id/R.668eec52e2f90f9e517c65905a846704?rik=ADT3vRLOgC1syg&pid=ImgRaw&r=0');
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        background-color: #f6adc6;
        font-family: 'Lucida Handwriting', cursive;
        margin: 0;
        padding: 50px;
    }

    /* Emoji border around the whole website */
    body::before, body::after {
        content: "🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸";
        display: block;
        text-align: center;
        font-size: 20px;
        position: absolute;
        left: 0;
        width: 100%;
        color: #ff69b4;
    }

    body::before {
        top: 0;
    }

    body::after {
        position: fixed;
        bottom: 0;
    }

    /* Title styling */
    h1 {
        text-align: center;
        color: #ff1493;
        font-size: 32px;
    }

    /* Section styling */
    .section {
        text-align: center;
        margin-top: 100px;
        padding: 50px;
    }

    /* Button styling */
    .scroll-button {
        display: block;
        width: 200px;
        margin: 20px auto;
        padding: 10px;
        background-color: #ff85a2;
        color: white;
        border: none;
        border-radius: 15px;
        font-size: 18px;
        cursor: pointer;
        box-shadow: 0 0 10px #ff66b2;
    }

    /* Image gallery */
    .gallery {
        display: flex;
        justify-content: center;
        gap: 20px;
        flex-wrap: wrap;
        margin-top: 50px;
    }

    .gallery img {
        width: 250px;
        height: auto;
        border-radius: 15px;
        box-shadow: 0 0 10px #ff66b2;
    }
</style>

<!-- Main Section -->
<h1>Welcome to My Cute Website! 🎀</h1>
<p class="section">Scroll down to see the products! ⬇️</p>

<!-- Scroll Button -->
<button class="scroll-button" onclick="document.getElementById('products').scrollIntoView({behavior: 'smooth'});">
    View Products 🎀
</button>

<!-- Products Section (Images Lower on the Page) -->
<div id="products" class="section">
    <h1>Our Cute Products 💖</h1>
    <div class="gallery">
        <img src="https://th.bing.com/th/id/R.1c6e1a5b560d3ec587e3880887bc53ff?rik=wyTBAYKA7bpmUg&riu=http%3a%2f%2fimages5.fanpop.com%2fimage%2fphotos%2f25600000%2fHello-Kitty-Sitting-hello-kitty-25604546-1210-1429.jpg&ehk=XFvh1tuK1a095ImwQYh02IJ1p5UxyX%2fk5JdMnGn306Y%3d&risl=&pid=ImgRaw&r=0" alt="Hello Kitty">
        <img src="https://wallpaperaccess.com/full/1167293.jpg" alt="Pink Aesthetic">
        <img src="https://wallpapercave.com/wp/wp10497374.jpg" alt="Cute Room">
    </div>
</div>
