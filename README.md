
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Title</title>
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
        }

        /* Emoji border around the whole website */
        body::before {
            content: "🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸"; 
            display: block;
            text-align: center;
            font-size: 20px;
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
        }
        body::after {
            content: "🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸🎀🌸"; 
            display: block;
            text-align: center;
            font-size: 20px;
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
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
</head>
<body>

    <h1>Yollo</h1>
    <p>This is your <br> first website!</p>

</body>
</html>
