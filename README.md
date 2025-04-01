<!-- Favicon (Make sure favicon-32x32.png is in the same folder as this file) -->
<link rel="icon" type="image/png" href="favicon-32x32.png">

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
