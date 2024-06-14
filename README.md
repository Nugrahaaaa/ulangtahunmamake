<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selamat Ulang Tahun!</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #FF0080;
            font-family: 'Arial', sans-serif;
        }

        .container {
            text-align: center;
            background-color: pink;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
        }

        h2 {
            color: #373A40;
            padding-top: 30vh;
        }

        .birthday-image-container {
            position: relative;
            display: inline-block;
        }

        .birthday-image {
            width: 70%;
            max-width: 300px;
            height: auto;
            border-radius: 15px;
            /* margin: 20px auto; */
            z-index: 1;
        }
        .message {
            margin: 20px 0;
            color: #FFFFFF;
            background-color: rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            font-family: 'calibri', sans-serif;
        }

        button {
            background-color: #FF69B4;
            color: black;
            border: none;
            padding: 10px 20px;
            font-size: 1em;
            cursor: pointer;
            border-radius: 5px;
            margin-top: 20px;
        }

        button:hover {
            background-color: #e65a50;
        }

        audio {
            display: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Selamat Ulang Tahun <br> MAMAKE</h2>
        <div class="birthday-image-container">
            <img src="mamah2.jpg" alt="Gambar Ulang Tahun" class="birthday-image">
            <div class="flower-frame"></div>
        </div>
        <p class="message">
            Semoga hari hari mamake dipenuhi <br> dengan kebahagiaan.
        </p>
        <p class="message">
            semoga panjang umur ya mamake <br> dan diberi keberkahan umur.
        </p>
        <p class="message">
            Semoga selalu murah rezeki <br> dan rezeki yang berkah.
        </p>
        <p class="message">
            Selamat ulang tahun mamake!
        </p>
        <p class="message">
            Puter mamake lagunya <br> biar ngerasa balik lagi ke masa kecil mamake hehe.
        </p>
        <button onclick="playAudio()">Putar audio</button>
        <audio id="birthday-audio" src="Lagu Ulang Tahun Anak _ Selamat Ulang Tahun (192 kbps).mp3"></audio>
    </div>
    <script>
        function playAudio() {
            var audio = document.getElementById('birthday-audio');
            audio.play();
        }
    </script>
</body>
</html>
