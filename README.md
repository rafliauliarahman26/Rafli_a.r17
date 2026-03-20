<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selamat Idul Fitri 🌙</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Poppins', sans-serif;
            /* Gradient Warna Kebanggaan Barca */
            background: linear-gradient(135deg, #004d98 0%, #a50044 100%);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
            color: white;
        }

        .container {
            text-align: center;
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(15px);
            padding: 40px 20px;
            border-radius: 20px;
            border: 3px solid #edbb00; /* Garis Emas */
            box-shadow: 0 15px 35px rgba(0,0,0,0.4);
            max-width: 350px;
            width: 90%;
            animation: fadeIn 1.5s ease-in-out;
        }

        .logo-barca {
            width: 100px;
            filter: drop-shadow(0 0 10px rgba(237, 187, 0, 0.5));
            margin-bottom: 20px;
        }

        h1 {
            font-size: 2.2rem;
            margin: 0;
            color: #edbb00;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        h2 {
            font-weight: 400;
            margin-top: 5px;
            font-size: 1.1rem;
        }

        .pesan {
            margin: 25px 0;
            font-size: 1rem;
            line-height: 1.6;
            color: #f1f1f1;
        }

        .btn-klik {
            display: inline-block;
            padding: 12px 30px;
            background-color: #edbb00;
            color: #004d98;
            text-decoration: none;
            font-weight: bold;
            border-radius: 50px;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }

        .btn-klik:hover {
            transform: translateY(-3px);
            background-color: white;
            box-shadow: 0 8px 20px rgba(0,0,0,0.3);
        }

        /* Animasi Sederhana */
        @keyframes fadeIn {
            from { opacity: 0; transform: scale(0.9); }
            to { opacity: 1; transform: scale(1); }
        }

        /* Hiasan Bintang */
        .stars {
            position: absolute;
            top: 0; left: 0; width: 100%; height: 100%;
            pointer-events: none;
            background: url('https://www.transparenttextures.com/patterns/stardust.png');
            opacity: 0.3;
        }
    </style>
</head>
<body>

    <div class="stars"></div>

    <div class="container">
        <img src="https://upload.wikimedia.org/wikipedia/en/thumb/4/47/FC_Barcelona_logo.svg/1200px-FC_Barcelona_logo.svg.png" alt="Barca Logo" class="logo-barca">
        
        <h1>Selamat Idul Fitri</h1>
        <h2>1447 Hijriah</h2>

        <div class="pesan">
            "Suci hati di hari yang fitri. Mohon maaf lahir dan batin atas segala khilaf. Semoga keberkahan selalu menyertai kita semua."
        </div>

        <a href="https://wa.me/?text=Selamat%20Idul%20Fitri!%20Cek%20ucapan%20dari%20saya%20di%20sini" class="btn-klik">Kirim Balasan 💌</a>
        
        <p style="font-size: 0.8rem; margin-top: 20px; opacity: 0.7;">Visca el Barça! 🔵🔴</p>
    </div>

</body>
</html>

