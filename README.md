<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selamat Ulang Tahun Kakak Rose!</title>
    <style>
        /* Reset dan Font */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        @import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Quicksand:wght@400;600&display=swap');
        
        body {
            font-family: 'Quicksand', sans-serif;
            background-color: #fff5f5;
            color: #333;
            line-height: 1.6;
        }
        
        /* Layout Utama */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        /* Header */
        header {
            text-align: center;
            padding: 30px 0;
            background: linear-gradient(135deg, #ff9a9e 0%, #fad0c4 100%);
            border-radius: 10px;
            margin-bottom: 30px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }
        
        h1 {
            font-family: 'Dancing Script', cursive;
            font-size: 3.5rem;
            color: #d23669;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
        }
        
        .subtitle {
            font-size: 1.2rem;
            color: #666;
            font-weight: 600;
        }
        
        /* Cake Section */
        .cake-section {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-bottom: 40px;
        }
        
        .cake-image {
            width: 100%;
            max-width: 600px;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 10px 25px rgba(0,0,0,0.15);
            margin-bottom: 20px;
            background: #fff;
            padding: 20px;
        }
        
        .cake-image img {
            width: 100%;
            border-radius: 10px;
            display: block;
        }
        
        .cake-description {
            text-align: center;
            max-width: 800px;
            padding: 20px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.05);
        }
        
        .cake-description h2 {
            color: #d23669;
            margin-bottom: 15px;
            font-family: 'Dancing Script', cursive;
            font-size: 2.2rem;
        }
        
        .cake-description p {
            margin-bottom: 15px;
            font-size: 1.1rem;
        }
        
        /* Countdown */
        .countdown {
            text-align: center;
            margin: 30px 0;
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
        }
        
        .countdown h2 {
            color: #d23669;
            margin-bottom: 15px;
            font-family: 'Dancing Script', cursive;
            font-size: 2.2rem;
        }
        
        .date-box {
            display: inline-block;
            margin: 0 10px;
            padding: 15px;
            background: linear-gradient(135deg, #fbc2eb 0%, #a6c1ee 100%);
            border-radius: 8px;
            color: white;
            font-weight: 600;
            font-size: 1.3rem;
            min-width: 100px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }
        
        /* Wish Section */
        .wish-section {
            text-align: center;
            padding: 40px 20px;
            background: linear-gradient(135deg, #a1c4fd 0%, #c2e9fb 100%);
            border-radius: 10px;
            color: white;
        }
        
        .wish-section h2 {
            font-family: 'Dancing Script', cursive;
            font-size: 2.5rem;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
        }
        
        .wish-message {
            font-size: 1.2rem;
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.8;
        }
        
        /* Footer */
        footer {
            text-align: center;
            margin-top: 30px;
            padding: 20px;
            color: #666;
            font-size: 0.9rem;
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }
            
            .date-box {
                margin: 5px;
                min-width: 80px;
                font-size: 1rem;
                padding: 10px;
            }
            
            .cake-image {
                padding: 10px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Selamat Ulang Tahun Kakak Rose!</h1>
            <p class="subtitle">15 Juli · Hari yang Istimewa untukmu</p>
        </header>
        
        <section class="cake-section">
            <div class="cake-image">
                <img src="file_00000000755c622f834d8eb55614307b.png" alt="Kue ulang tahun mewah tiga tingkat berwarna pink dan putih dengan dekorasi bunga gula dan lilin angka di atasnya, diselimuti buttercream halus dengan pinggiran hiasan kerang" />
            </div>
            
            <div class="cake-description">
                <h2>Kue Spesial untuk Kakak Rose</h2>
                <p>Kue ini dibuat dengan penuh cinta hanya untuk merayakan hari spesialmu. Setiap lapisan melambangkan tahun-tahun kebahagiaan yang telah kau lewati dan banyak tahun indah yang akan datang.</p>
                <p>Rasa vanilla dan red velvet yang lembut dengan isian selai stroberi segar - karena kau pantas mendapatkan yang terbaik di hari istimewamu ini!</p>
            </div>
        </section>
        
        <section class="countdown">
            <h2>Menunggumu di:</h2>
            <div>
                <span class="date-box">15</span>
                <span class="date-box">Juli</span>
                <span class="date-box">2025</span>
            </div>
        </section>
        
        <section class="wish-section">
            <h2>Pesan untuk Kakak Rose</h2>
            <div class="wish-message">
                <p>Kakak Rose, di hari ulang tahunmu ini, kami ingin mengucapkan terima kasih untuk semua cinta dan kebahagiaan yang kau berikan. Semoga tahun ini membawa lebih banyak tawa, petualangan, dan pencapaian dalam hidupmu.</p>
                <p>Kau adalah berkat bagi keluarga dan semua yang mengenalmu. Selamat merayakan hari spesialmu dengan penuh sukacita!</p>
            </div>
        </section>
        
        <footer>
            <p>Dibuat dengan ❤ oleh navis untuk Kakak Rose tercinta</p>
        </footer>
    </div>
</body>
</html>
