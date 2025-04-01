<!-- Favicon (Make sure favicon image is in the same folder as this file) -->
<link rel="icon" type="image/png" href="https://github.githubassets.com/assets/yolo-default-be0bbff04951.png">
<style>
    /* Website background settings */
    body {
        background-image: url('https://th.bing.com/th/id/R.668eec52e2f90f9e517c65905a846704?rik=ADT3vRLOgC1syg&pid=ImgRaw&r=0');
        background-size: cover; /* Makes sure image fills the whole page */
        background-position: center;
        background-repeat: no-repeat;
        background-color: #f6adc6; /* Nadeshiko Pink */
        font-family: 'Lucida Handwriting', cursive; /* Cute font */
        padding: 50px; /* Creates space for the border */
        position: relative;
        margin: 0;
        border: 10px solid transparent; /* Invisible border to make space for the emoji border */
        background-clip: padding-box; /* Makes sure the background is behind the border */
    }

    /* Emoji border around the whole website (Default for big screens) */
    body::before, body::after {
        content: "🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸";
        display: block;
        text-align: center;
        font-size: 20px;
        position: absolute;
        left: 0;
        width: 100%;
        color: #ff69b4;
    }

    /* Top border */
    body::before {
        top: 0;
    }

    /* Bottom border fixed to the very bottom */
    body::after {
        content: "🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸";
        display: block;
        text-align: center;
        font-size: 20px;
        position: fixed;  /* Keeps it at the very bottom */
        left: 0;
        width: 100%;
        bottom: 0;  /* Sticks it to the bottom */
        color: #ff69b4;
    }

    /* Responsive Emoji Border Adjustments */
    @media (max-width: 1024px) {  /* Tablets */
        body::before, body::after {
            content: "🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸";
            font-size: 18px; /* Slightly smaller emojis */
        }
    }

    @media (max-width: 600px) {  /* Phones */
        body::before, body::after {
            content: "🎀🌸🎀🌸🎀🌸";
            font-size: 16px; /* Even smaller emojis */
        }
    }

    /* Title (h1) styling */
    h1 {
        text-align: center;
        color: #ff1493; /* Hot pink title */
        font-size: 32px;
    }

    /* Fix the text box background & add rounded edges */
    p {
        color: #145A32;
        background-color: rgba(255, 240, 245, 0.8); /* Soft pinkish-white with slight transparency */
        padding: 15px;
        border-radius: 15px; /* Smooth, rounded edges */
        border: 2px solid #ff85a2; /* Cute pink border */
        text-align: center;
        width: 50%;
        margin: 20px auto; /* Centers it */
        font-size: 18px;
        box-shadow: 0 0 10px #ff66b2; /* Soft glowing effect */
    }
</style>

<!-- Google Font for Cursive Text -->
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">

<!-- Products Section -->
<div id="products" class="section">
    <h1>Our Cute Products 💖</h1>
    <div class="gallery">
        <div class="product">
            <img src="https://th.bing.com/th/id/R.1c6e1a5b560d3ec587e3880887bc53ff?rik=wyTBAYKA7bpmUg&riu=http%3a%2f%2fimages5.fanpop.com%2fimage%2fphotos%2f25600000%2fHello-Kitty-Sitting-hello-kitty-25604546-1210-1429.jpg&ehk=XFvh1tuK1a095ImwQYh02IJ1p5UxyX%2fk5JdMnGn306Y%3d&risl=&pid=ImgRaw&r=0" alt="Hello Kitty">
            <h3>💖 Hello Kitty Plushie 💖</h3>
            <p>The softest and cutest Hello Kitty plush, perfect for cuddles! 🎀</p>
        </div>
        
        <div class="product">
            <img src="https://wallpaperaccess.com/full/1167293.jpg" alt="Pink Aesthetic">
            <h3>🌸 Dreamy Aesthetic Wallpaper 🌸</h3>
            <p>Transform your room with this beautiful soft pink aesthetic vibe! ✨</p>
        </div>
        
        <div class="product">
            <img src="https://wallpapercave.com/wp/wp10497374.jpg" alt="Cute Room">
            <h3>🎀 Cozy Pastel Bedroom 🎀</h3>
            <p>Get inspired by this super cozy pastel bedroom setup! So dreamy~ ☁️</p>
        </div>
    </div>
</div>

<style>
    /* Ensure background stays */
    body {
        background-image: url('https://th.bing.com/th/id/R.668eec52e2f90f9e517c65905a846704?rik=ADT3vRLOgC1syg&pid=ImgRaw&r=0');
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        background-color: #f6adc6;
        font-family: 'Lucida Handwriting', cursive;
        padding: 50px;
        position: relative;
        margin: 0;
        border: 10px solid transparent;
        background-clip: padding-box;
    }

    /* Products section styling */
    .gallery {
        display: flex;
        justify-content: center;
        gap: 20px;
        flex-wrap: wrap;
        margin-top: 50px;
    }

    .product {
        text-align: center;
        width: 250px;
    }

    .product img {
        width: 100%;
        border-radius: 15px;
        box-shadow: 0 0 10px #ff66b2;
    }

    .product h3 {
        color: #ff1493;
        font-size: 22px;
        font-family: 'Pacifico', cursive; /* Cursive font */
        margin-top: 10px;
    }

    .product p {
        color: #ff69b4; /* Pink text color */
        background-color: rgba(255, 240, 245, 0.8);
        padding: 15px;
        border-radius: 15px;
        font-size: 20px; /* Bigger text */
        font-family: 'Pacifico', cursive; /* Cursive font */
        box-shadow: 0 0 5px #ff66b2;
    }
</style>
