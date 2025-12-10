<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Surya Teknisi Premium | Spesialis Service HP Surabaya Garansi 90 Hari</title>
    
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    
    <style>
        /* ===================================================================
           1. CORE & GLOBAL STYLES 
        =================================================================== */
        :root {
            --primary-color: #004a99; 
            --secondary-color: #ffb700; 
            --danger-color: #c72c41; 
            --success-color: #208e43;
            --text-color: #212529; 
            --bg-light: #f0f0f0; 
            --bg-white: #ffffff;
            --shadow-subtle: 0 8px 25px rgba(0, 0, 0, 0.08);
            --shadow-lift: 0 15px 35px rgba(0, 0, 0, 0.15); 
        }

        body {
            font-family: 'Poppins', Arial, sans-serif; 
            margin: 0; 
            padding: 0; 
            background-color: var(--bg-light); 
            color: var(--text-color); 
            line-height: 1.6; 
            scroll-behavior: smooth;
        }
        .container {
            max-width: 1100px; 
            margin: 40px auto; 
            padding: 0 25px;
        }
        .section {
            background-color: var(--bg-white); 
            padding: 60px; 
            margin-bottom: 40px; 
            border-radius: 20px; 
            box-shadow: var(--shadow-subtle); 
        }
        .section h2 {
            color: var(--primary-color); 
            border-bottom: 3px solid var(--secondary-color); 
            padding-bottom: 12px; 
            margin-bottom: 50px; 
            font-size: 2.2em; 
            font-weight: 700; 
            text-align: center;
        }
        
        /* 2. NAVBAR */
        .navbar {
            background-color: var(--primary-color); 
            padding: 18px 0;
            position: sticky; top: 0; z-index: 1000;
        }
        .navbar-content {
            max-width: 1100px; 
            margin: 0 auto; 
            padding: 0 25px;
            display: flex;
            justify-content: space-between; 
            align-items: center;
            flex-direction: row; 
        }
        .nav-links {
            display: flex;
            justify-content: center; 
            flex-grow: 1; 
        }
        .nav-links a {
            color: white; 
            text-decoration: none; 
            font-weight: 600; 
            margin: 0 15px; 
            padding-bottom: 5px;
            position: relative;
            transition: color 0.3s;
        }
        .navbar-logo {
            font-size: 1.6em;
            font-weight: 800; 
            color: white !important;
            text-decoration: none; 
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.4);
            display: flex;
            align-items: center;
            gap: 8px; 
        }
        .navbar-logo .logo-brand {
            color: var(--secondary-color); 
        }
        .navbar-logo i {
            font-size: 1.2em;
            color: var(--secondary-color);
        }
        
        /* Hamburger Menu (Sembunyikan di Desktop) */
        .hamburger-menu {
            display: none; 
            font-size: 1.5em;
            color: white;
            cursor: pointer;
        }

        @media (min-width: 769px) {
             .navbar-content {
                justify-content: space-between; 
                flex-direction: row;
                gap: 10px;
            }
        }

        /* HEADER */
        .header-parallax {
            background: linear-gradient(135deg, rgba(0, 74, 153, 0.95) 0%, rgba(0, 100, 200, 0.95) 100%), url('https://via.placeholder.com/1600x600?text=Modern+HP+Repair+Background'); 
            color: #ffffff; 
            padding: 140px 0; 
            background-attachment: fixed;
            text-align: center; 
        }
        .header-content {
            max-width: 800px; 
            margin: 0 auto; 
        }
        .header-content h1 {
            margin-top: 0; 
        }

        /* WARANTY BOX */
        .warranty-box {
            padding: 20px 40px;
            margin-bottom: 40px;
            background-color: var(--secondary-color);
            color: var(--text-color);
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(255, 183, 0, 0.3);
            text-align: center;
        }
        .warranty-box h3 {
            margin: 0 0 5px 0;
            font-weight: 700;
            color: var(--primary-color);
            font-size: 1.5em;
        }
        .warranty-box p {
            margin: 0;
            font-size: 1.1em;
        }


        /* LAYANAN GRID DAN ANIMASI */
        .layanan-grid {
             display: grid; 
             grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); 
             gap: 25px; 
        }
        .layanan-item {
            border: 1px solid #e9ecef; 
            background-color: #fcfcfc;
            border-radius: 15px;
            min-height: 260px; 
            display: flex;
            flex-direction: column;
            justify-content: flex-start;
            align-items: center;
            padding: 30px 20px; 
            transition: all 0.3s;
            text-align: center; 
            cursor: pointer; 
        }
        .layanan-item:hover {
            box-shadow: var(--shadow-lift); 
            transform: translateY(-5px); 
            background-color: var(--primary-color); 
        }
        .layanan-item:hover h3, 
        .layanan-item:hover p {
            color: white; 
        }
        .layanan-item i {
            font-size: 3.5em; 
            color: var(--primary-color);
            margin-bottom: 15px;
            transition: color 0.3s;
        }
        .layanan-item:hover i {
            color: var(--secondary-color); 
        }
        .layanan-cta-button {
            display: block;
            width: fit-content;
            margin: 40px auto 0 auto; 
            padding: 18px 50px;
            background-color: var(--success-color); 
            color: white !important;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 700;
            font-size: 1.3em; 
            text-transform: uppercase;
            letter-spacing: 1px;
            box-shadow: 0 8px 20px rgba(32, 142, 67, 0.4);
            transition: background-color 0.3s, transform 0.3s;
        }
        .layanan-cta-button:hover {
            background-color: #179c3f; 
            transform: scale(1.05); 
        }
        
        /* ===================================================================
           PRICE SECTION STYLING
        =================================================================== */
        .price-tabs-container { 
            text-align: center;
            margin-bottom: 30px;
        }
        .price-tab-button {
            padding: 10px 25px;
            margin: 0 5px 15px 5px;
            border: 2px solid var(--primary-color); 
            border-radius: 50px;
            background-color: var(--bg-white); 
            color: var(--primary-color); 
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            font-size: 1em;
            text-transform: uppercase;
            outline: none; 
        }
        .price-tab-button:hover {
            background-color: var(--primary-color);
            color: white;
            box-shadow: 0 4px 10px rgba(0, 74, 153, 0.2);
        }
        .price-tab-button.active {
            background-color: var(--primary-color);
            color: white;
            box-shadow: 0 4px 15px rgba(0, 74, 153, 0.4);
            transform: translateY(-2px);
        }
        .price-content {
            display: none;
            overflow-x: auto; 
        }
        .price-content.active {
            display: block;
        }
        .price-content table {
            margin: 0 auto; 
            max-width: 800px;
            width: 100%;
            border-collapse: collapse;
        }
        .price-content th, .price-content td {
            padding: 15px;
            text-align: left;
            border-bottom: 1px solid #dee2e6;
        }
        .price-content th {
            background-color: var(--primary-color); 
            color: white;
            text-transform: uppercase;
            font-weight: 700;
        }
        .price-content tr:nth-child(even) { 
            background-color: #f8f9fa;
        }
        .price-highlight {
            font-weight: 700;
            color: var(--danger-color); 
        }


        /* ===================================================================
           PROCESS FLOW STYLING 
        =================================================================== */
        .process-flow {
            display: flex;
            justify-content: space-around;
            align-items: flex-start;
            position: relative;
            padding-top: 50px; 
            margin-top: 40px;
        }
        .process-flow::before {
            content: '';
            position: absolute;
            top: 65px; 
            left: 10%;
            right: 10%;
            height: 6px; 
            background: linear-gradient(to right, #e0e0e0, var(--secondary-color), #e0e0e0); 
            border-radius: 3px;
            z-index: 1; 
        }
        .step {
            flex-basis: 22%; 
            text-align: center;
            position: relative;
            z-index: 2; 
            padding: 10px;
            transition: transform 0.3s ease-in-out;
        }
        .step:hover {
            transform: translateY(-8px);
        }
        .step-icon {
            width: 80px; 
            height: 80px;
            background: linear-gradient(135deg, var(--primary-color) 0%, #007bff 100%); 
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 0 auto 15px auto;
            box-shadow: 0 8px 25px rgba(0, 74, 153, 0.4); 
            border: 6px solid var(--bg-white); 
            transition: all 0.3s;
        }
        .step:nth-child(even) .step-icon {
            background: linear-gradient(135deg, var(--secondary-color) 0%, #ffc107 100%);
            box-shadow: 0 8px 25px rgba(255, 183, 0, 0.5); 
        }
        .step-icon i {
            color: white;
            font-size: 2.2em;
            transition: all 0.5s;
        }
        
        /* Animasi: Hanya ikon gear (langkah 3) yang berputar */
        .step:nth-child(3) .step-icon i {
            animation: rotate-icon 4s infinite linear;
        }
        @keyframes rotate-icon {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }
        
        /* Animasi KHUSUS untuk Langkah 4 (Quality Check) */
        .step:nth-child(4) .step-icon i {
            animation: pulse-check 2s infinite ease-in-out;
        }
        @keyframes pulse-check {
            0% { transform: scale(1); }
            50% { transform: scale(1.15); color: var(--success-color); } 
            100% { transform: scale(1); }
        }

        .step h4 {
            color: var(--primary-color);
            font-weight: 700;
            font-size: 1.2em;
            margin-bottom: 5px;
            margin-top: 15px; 
        }


        /* ===================================================================
           DELIVERY PROMO STYLING 
        =================================================================== */
        .delivery-promo {
            background: linear-gradient(90deg, var(--primary-color) 0%, #0060c0 100%); 
            color: white; 
            padding: 50px 30px; 
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 74, 153, 0.5); 
            margin-bottom: 40px;
            text-align: center;
        }
        .delivery-promo h3 {
            font-size: 2.2em; 
            font-weight: 800;
            color: var(--secondary-color); 
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.3);
        }
        .delivery-promo p {
            font-size: 1.2em; 
            max-width: 700px;
            margin: 15px auto 30px auto;
            color: #f0f0f0; 
        }
        .delivery-promo .delivery-icon-large {
            font-size: 4.5em; 
            color: var(--secondary-color);
            margin-bottom: 15px;
            display: block;
            animation: pulse-icon 2s infinite, bounce-icon 3s ease-in-out infinite; 
        }
        @keyframes pulse-icon {0% { transform: scale(1); } 50% { transform: scale(1.05); } 100% { transform: scale(1); }}
        @keyframes bounce-icon {0%, 100% { transform: translateY(0); } 50% { transform: translateY(-10px); }}
        .delivery-promo a {
            display: inline-block;
            padding: 15px 40px;
            background-color: var(--success-color); 
            color: white !important;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 700;
            transition: background-color 0.3s, transform 0.3s;
            text-transform: uppercase;
            box-shadow: 0 4px 10px rgba(32, 142, 67, 0.5);
        }
        .delivery-promo a:hover {
            background-color: #179c3f;
            transform: scale(1.05);
        }


        /* ===================================================================
           FOOTER & FAB WA STYLES 
        =================================================================== */
        footer {
            background-color: var(--primary-color); 
            color: white; 
            padding: 30px 20px; 
            font-size: 1em; 
            text-align: center; 
            margin-top: 40px; 
            border-radius: 15px;
        }
        footer p {
            margin: 5px 0;
        }
        footer a {
            color: var(--secondary-color); 
            text-decoration: none;
            font-weight: 700; 
            transition: color 0.3s;
        }
        footer a:hover {
            color: #ffd866; 
            text-decoration: underline;
        }
        
        .fab-container {position: fixed; bottom: 20px; right: 20px; z-index: 1000;}
        .fab {display: block; width: 60px; height: 60px; background-color: var(--success-color); color: white; border-radius: 50%; text-align: center; line-height: 60px; font-size: 2.2em; box-shadow: 0 4px 15px rgba(32, 142, 67, 0.6); transition: transform 0.3s ease;}
        .fab:hover {transform: scale(1.15); }


        /* ===================================================================
           RESPONSIVE MOBILE DESIGN (Max 768px)
        =================================================================== */
        @media (max-width: 768px) {
            
            /* Global Adjustments */
            .container { margin: 20px auto; padding: 0 15px; }
            .section { padding: 30px 20px; }
            .section h2 { font-size: 1.8em; margin-bottom: 30px; }
            
            /* FIX UTAMA: Navbar Mobile - Gunakan Hamburger */
            .navbar { padding: 15px 0; }
            .navbar-content { 
                flex-direction: row; 
                justify-content: space-between; 
                align-items: center; 
            }
            .hamburger-menu {
                display: block; /* Tampilkan Hamburger di mobile */
            }
            .nav-links { 
                /* Menyembunyikan dan memposisikan menu di mobile */
                display: none; 
                position: absolute;
                top: 55px; /* Kurangi tinggi untuk mobile */
                left: 0;
                right: 0;
                background-color: var(--primary-color);
                flex-direction: column;
                text-align: center;
                box-shadow: 0 8px 15px rgba(0, 0, 0, 0.4);
                padding: 10px 0;
                z-index: 999;
            }
            .nav-links.active {
                display: flex; /* Tampilkan menu saat aktif */
            }
            .nav-links a { 
                margin: 10px 0; 
                padding: 10px 0;
                width: 100%;
                border-bottom: 1px solid rgba(255, 255, 255, 0.1);
            }
            .nav-links a:last-child {
                border-bottom: none;
            }

            /* Header Adjustment: Kurangi padding header agar konten cepat terlihat */
            .header-parallax { 
                padding: 50px 0; /* Jauh lebih kecil di mobile */
            }
            .header-content h1 { font-size: 1.8em; }
            .header-content p { font-size: 1em; }

            /* Delivery Promo Adjustment */
            .delivery-promo { padding: 30px 15px; }
            .delivery-promo h3 { font-size: 1.6em; }
            .delivery-promo p { font-size: 1em; }
            .delivery-promo a { padding: 12px 30px; font-size: 1em; }
            
            /* Price Table Adjustment */
            .price-tabs-container { display: flex; flex-wrap: wrap; justify-content: center; gap: 5px; }
            .price-tab-button { flex: 1 1 45%; margin: 5px 0; }
            .price-content { overflow-x: auto; -webkit-overflow-scrolling: touch; }
            .price-content table { min-width: 500px; }

            /* Process Flow Adjustment: Ubah menjadi vertikal di mobile */
            .process-flow {
                flex-direction: column;
                padding-top: 0;
            }
            .process-flow::before {
                top: 0;
                left: 30px; 
                bottom: 0;
                width: 6px; 
                right: auto;
                height: 100%;
                background: linear-gradient(to bottom, #e0e0e0, var(--secondary-color), #e0e0e0); 
            }
            .step {
                flex-basis: 100%;
                text-align: left;
                display: flex;
                align-items: center;
                gap: 20px;
                padding: 20px 0;
            }
            .step-icon {
                margin: 0;
                flex-shrink: 0; 
            }
            
            /* Testimonial Adjustment */
            .testimonial-grid { flex-direction: column; gap: 15px; }
            .testimonial-card { max-width: 100%; }

            /* Pengetahuan Wajib Layout */
            div[style*="display: flex;"] { flex-direction: column; }
            div[style*="border-left: 5px solid"] { margin-bottom: 15px; }
            
            /* FAB WA */
            .fab { width: 50px; height: 50px; line-height: 50px; font-size: 1.8em; }

            /* Footer Responsive */
            footer {
                padding: 20px 15px;
                font-size: 0.9em;
            }
        }
    </style>
</head>
<body>

    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        AOS.init({
            duration: 900, 
            once: true, 
            disable: 'phone' 
        });
    </script>

    <div class="navbar">
        <div class="navbar-content">
            <a href="#" class="navbar-logo">
                <i class="fa-solid fa-screwdriver-wrench"></i> <span class="logo-brand">SURYA</span> TEKNISI
            </a>

            <div class="hamburger-menu" id="hamburger-btn">
                <i class="fa-solid fa-bars"></i>
            </div>
            <div class="nav-links" id="nav-links">
                <a href="#layanan">Layanan</a>
                <a href="#harga">Harga</a>
                <a href="#delivery">Antar Jemput</a>
                <a href="#proses">Proses</a>
                <a href="#testimoni">Testimoni</a>
                <a href="#kontak">Kontak</a>
            </div>
        </div>
    </div>

    <div class="header-parallax">
        <div class="header-content" data-aos="fade-down">
            <h1>SOLUSI SERVICE HP PROFESIONAL</h1>
            <p>Spesialis Diagnosa Mainboard & Perbaikan Premium, Garansi Hingga 90 Hari.</p>
            <a href="#delivery" style="display: inline-block; margin-top: 25px; padding: 14px 40px; background-color: var(--secondary-color); color: var(--text-color); text-decoration: none; border-radius: 50px; font-weight: 700; transition: all 0.3s;">ANTAR JEMPUT GRATIS SURABAYA!</a>
        </div>
    </div>

    <div class="container">
        <section class="warranty-box" data-aos="zoom-in">
            <h3>⭐ Jaminan Garansi Resmi Hingga 90 Hari!</h3>
            <p>Kami hanya menggunakan suku cadang berkualitas dan memberikan ketenangan pikiran dengan garansi purna jual.</p>
        </section>

        <section class="section" id="layanan" data-aos="fade-up">
            <h2>✨ Layanan Inti Kami</h2>
            <p style="text-align: center; margin-bottom: 40px; color: #555;">Klik pada layanan yang diinginkan untuk memulai reservasi cepat via WhatsApp, atau gunakan tombol di bawah.</p>
            <div class="layanan-grid">
                
                <div class="layanan-item" onclick="openWhatsApp('layar')" data-aos="fade-up" data-aos-delay="100">
                    <i class="fa-solid fa-mobile-screen"></i>
                    <div class="layanan-item-content"><h3>Ganti Layar/LCD Original</h3><p>Pergantian layar retak, pecah, *blank*, atau *ghost touch*.</p></div>
                </div>
                
                <div class="layanan-item" onclick="openWhatsApp('mainboard')" data-aos="fade-up" data-aos-delay="200">
                    <i class="fa-solid fa-microchip"></i>
                    <div class="layanan-item-content"><h3>Servis Mainboard (Mikrosoldering)</h3><p>Perbaikan tingkat lanjut untuk HP mati total, *bootloop*, atau kerusakan IC.</p></div>
                </div>
                
                <div class="layanan-item" onclick="openWhatsApp('baterai')" data-aos="fade-up" data-aos-delay="300">
                    <i class="fa-solid fa-battery-full"></i>
                    <div class="layanan-item-content"><h3>Baterai & Pengisian Daya</h3><p>Mengganti baterai kembung/boros dan perbaikan jalur IC *charging*.</p></div>
                </div>
            </div>
            
            <a href="https://wa.me/6285198331549?text=Halo%2C%20saya%20ingin%20membuat%20reservasi%20service%20HP.%20Mohon%20bantuannya%20untuk%20diagnosa." 
               target="_blank" 
               class="layanan-cta-button" 
               data-aos="zoom-in" data-aos-delay="400">
                <i class="fa-brands fa-whatsapp"></i> Mulai Reservasi Sekarang
            </a>

        </section>

        <section id="delivery" class="delivery-promo" data-aos="flip-down">
            <i class="fa-solid fa-truck-fast delivery-icon-large"></i> 
            <h3>🚀 EKSLUSIF SURABAYA! JEMPUT & ANTAR BALIK 100% GRATIS!</h3>
            <p>Tidak perlu repot keluar rumah! Teknisi kami akan menjemput perangkat Anda dengan aman dan mengantarkannya kembali setelah service selesai. **Hemat Waktu, Tanpa Biaya Tambahan, Tinggal Duduk Santai!**</p>
            <a href="https://wa.me/6285198331549?text=Saya%20ingin%20memanfaatkan%20layanan%20antar%20jemput%20gratis%20untuk%20service%20HP%20di%20Surabaya." 
               target="_blank">
               <i class="fa-brands fa-whatsapp"></i> Klik untuk Jadwalkan Penjemputan Cepat
            </a>
        </section>

        <section class="section" id="harga" data-aos="fade-right">
            <h2>💰 Daftar Harga Service Transparan</h2>
            <p style="text-align: center; color: #555; margin-bottom: 25px;">Pilih kategori perangkat Anda untuk melihat perkiraan harga:</p>
            
            <div class="price-tabs-container" data-aos="fade-in">
                <button class="price-tab-button active" onclick="showPrice('iphone', this)">Apple iPhone</button>
                <button class="price-tab-button" onclick="showPrice('android', this)">Android Premium</button>
                <button class="price-tab-button" onclick="showPrice('ic', this)">Mikrosoldering (IC)</button>
            </div>

            <div id="iphone" class="price-content active" data-aos="fade-up">
                <table><thead><tr><th colspan="2">Apple iPhone (LCD, Baterai & Face ID)</th></tr></thead>
                    <tbody>
                        <tr><td>Ganti LCD iPhone 15 Pro Max</td><td class="price-highlight">Mulai Rp 1.100.000</td></tr>
                        <tr><td>Ganti LCD iPhone 13 Pro</td><td class="price-highlight">Mulai Rp 550.000</td></tr>
                        <tr><td>Ganti LCD iPhone 11</td><td class="price-highlight">Rp 450.000</td></tr>
                        <tr><td>Ganti Baterai iPhone 14</td><td class="price-highlight">Rp 550.000</td></tr>
                        <tr><td>Ganti Baterai iPhone 12</td><td class="price-highlight">Rp 400.000</td></tr>
                        <tr><td>Perbaikan Face ID (Model X ke atas)</td><td class="price-highlight">Mulai Rp 800.000</td></tr>
                    </tbody>
                </table>
            </div>
            <div id="android" class="price-content" data-aos="fade-up">
                 <table><thead><tr><th colspan="2">Android Premium (Samsung, Xiaomi, dll.)</th></tr></thead>
                 <tbody>
                    <tr><td>Ganti LCD Samsung S23 Ultra</td><td class="price-highlight">Mulai Rp 2.000.000</td></tr>
                    <tr><td>Ganti LCD Samsung S21 Ultra</td><td class="price-highlight">Mulai Rp 1.500.000</td></tr>
                    <tr><td>Perbaikan/Ganti Kaca Belakang (Backdoor)</td><td class="price-highlight">Mulai Rp 100.000</td></tr>
                    <tr><td>Ganti Baterai Xiaomi 12 Pro</td><td class="price-highlight">Mulai Rp 200.000</td></tr>
                    <tr><td>Ganti Baterai Samsung A Series</td><td class="price-highlight">Mulai Rp 150.000</td></tr>
                 </tbody>
                 </table>
            </div>
            <div id="ic" class="price-content" data-aos="fade-up">
                 <table><thead><tr><th colspan="2">Mikrosoldering & Servis Fungsional</th></tr></thead>
                 <tbody>
                    <tr><td>Perbaikan IC Power (HP Mati Total)</td><td class="price-highlight">Mulai Rp 600.000</td></tr>
                    <tr><td>Perbaikan Jalur Charging/Port</td><td class="price-highlight">Mulai Rp 350.000</td></tr>
                    <tr><td>Ganti/Perbaikan IC Kamera Belakang</td><td class="price-highlight">Mulai Rp 450.000</td></tr>
                    <tr><td>Perbaikan Kerusakan Cairan (Water Damage)</td><td class="price-highlight">Konsultasi</td></tr>
                    <tr><td>Ganti Modul Speaker & Mic</td><td class="price-highlight">Mulai Rp 250.000</td></tr>
                 </tbody>
                 </table>
            </div>
            <p style="text-align: center; font-size: 0.9em; color: #888; margin-top: 30px;">*Harga estimasi dan dapat berubah. Selalu hubungi kami untuk diagnosa dan harga final.</p>
        </section>

        <section class="section" id="proses" data-aos="fade-up">
            <h2>🔍 Transparansi Proses Service</h2>
            <p style="text-align: center; color: #555;">Kami menjamin proses kerja yang cepat dan transparan dari awal hingga akhir. Khusus area Surabaya, langkah 1 dan 4 dilakukan oleh kurir profesional kami.</p>
            
            <div class="process-flow">
                
                <div class="step" data-aos="zoom-in" data-aos-delay="50">
                    <div class="step-icon"><i class="fa-solid fa-calendar-check"></i></div>
                    <h4>1. Jadwal & Penjemputan Kurir</h4>
                    <p>Jadwalkan, Kurir kami menjemput perangkat di lokasi Anda (Surabaya Free).</p>
                </div>
                
                <div class="step" data-aos="zoom-in" data-aos-delay="200">
                    <div class="step-icon"><i class="fa-solid fa-microscope"></i></div>
                    <h4>2. Diagnosa Mendalam</h4>
                    <p>Pengujian komponen (Hardware & Software) untuk menentukan akar masalah di workshop.</p>
                </div>
                
                <div class="step" data-aos="zoom-in" data-aos-delay="350">
                    <div class="step-icon"><i class="fa-solid fa-gear"></i></div>
                    <h4>3. Proses Perbaikan</h4>
                    <p>Eksekusi perbaikan dengan suku cadang berkualitas dan teknisi berpengalaman.</p>
                </div>
                
                <div class="step" data-aos="zoom-in" data-aos-delay="500">
                    <div class="step-icon"><i class="fa-solid fa-shield-halved"></i></div>
                    <h4>4. Quality Check & Pengantaran</h4>
                    <p>Pengujian fungsi menyeluruh, lalu diantar kembali ke lokasi Anda (Surabaya Free).</p>
                </div>
                
            </div>
        </section>

        <section class="section" id="testimoni" data-aos="fade-left">
            <h2>🗣️ Apa Kata Pelanggan Kami?</h2>
            <p style="text-align: center; margin-bottom: 30px; color: #555;">Kumpulan ulasan nyata dari pelanggan yang puas dengan layanan kami.</p>
            <div class="testimonial-grid">
                <div class="testimonial-card" data-aos="zoom-in-up" data-aos-delay="100"><p>"Service LCD iPhone 11 di sini **cepat sekali, hanya 1 jam** dan hasilnya mulus! Garansi juga jelas."</p><h4>- Bima S. (Jakarta)</h4></div>
                <div class="testimonial-card" data-aos="zoom-in-up" data-aos-delay="200"><p>"HP saya mati total kena air. Diservis di Surya Teknisi **akhirnya nyala lagi**. Data-data aman. Rekomen!"</p><h4>- Risa M. (Surabaya)</h4></div>
                <div class="testimonial-card" data-aos="zoom-in-up" data-aos-delay="300"><p>"Ganti baterai Xiaomi jadi **awet lagi**. Pelayanan ramah dan harganya transparan sesuai janji."</p><h4>- Agus P. (Bandung)</h4></div>
            </div>
        </section>
        
        <section class="section" data-aos="fade-up">
             <h2>🧠 Pengetahuan Wajib Pengguna HP</h2>
            <div style="display: flex; gap: 25px; flex-wrap: wrap; justify-content: center;">
                <div style="flex: 1; padding: 25px; border-radius: 8px; background-color: #f7f9fc; border-left: 5px solid var(--primary-color); min-width: 300px; text-align: left;" data-aos="fade-right">
                    <h3><i class="fa-solid fa-code"></i> Kerusakan Software</h3>
                    <p>Melibatkan sistem operasi. Seringkali dapat diselesaikan tanpa mengganti *spare part*.</p>
                    <ul><li>Masalah Umum: *Bootloop*, Lupa Sandi/PIN, *Virus*, HP *Hang* total.</li></ul>
                </div>
                <div style="flex: 1; padding: 25px; border-radius: 8px; background-color: #f7f9fc; border-left: 5px solid var(--danger-color); min-width: 300px; text-align: left;" data-aos="fade-left">
                    <h3><i class="fa-solid fa-box"></i> Kerusakan Hardware</h3>
                    <p>Melibatkan komponen fisik. Memerlukan penggantian suku cadang atau perbaikan *motherboard*.</p>
                    <ul><li>Masalah Umum: Layar retak, *Water Damage*, IC Power mati, *speaker* pecah.</li></ul>
                </div>
            </div>
        </section>

    </div> 
    
    <footer id="kontak" data-aos="fade-up">
        <p>Surya Teknisi &copy; 2025 | Keahlian, Kejujuran, dan Garansi adalah Prioritas Kami.</p>
        <p>Hubungi Kami: <a href="tel:085198331549">0851 9833 1549</a> | Alamat Workshop: Surabaya</p>
    </footer>

    <div class="fab-container">
        <a href="https://wa.me/6285198331549" target="_blank" class="fab"><i class="fa-brands fa-whatsapp"></i></a>
    </div>

    <script>
        // --- FUNGSI TOGGLE MENU MOBILE ---
        document.getElementById('hamburger-btn').addEventListener('click', function() {
            document.getElementById('nav-links').classList.toggle('active');
        });

        // Tutup menu jika link diklik (agar setelah navigasi, menu tertutup)
        document.querySelectorAll('.nav-links a').forEach(link => {
            link.addEventListener('click', function() {
                // Hanya tutup menu jika layar adalah mobile (opsional, tapi disarankan)
                if (window.innerWidth <= 768) {
                    document.getElementById('nav-links').classList.remove('active');
                }
            });
        });
        
        // --- FUNGSI TAB HARGA ---
        function showPrice(tabId, element) {
            const contents = document.querySelectorAll('.price-content');
            contents.forEach(content => content.classList.remove('active'));
            const buttons = document.querySelectorAll('.price-tab-button');
            buttons.forEach(button => button.classList.remove('active'));

            document.getElementById(tabId).classList.add('active');
            if (element) element.classList.add('active');
        }

        // --- FUNGSI OPEN WHATSAPP DENGAN PESAN OTOMATIS ---
        
        const serviceMap = {
            layar: "Reservasi Ganti Layar/LCD Original. Tolong infokan tipe HP saya: ",
            mainboard: "Reservasi Servis Mainboard (Mikrosoldering). Tolong infokan tipe HP saya: ",
            baterai: "Reservasi Baterai & Pengisian Daya. Tolong infokan tipe HP saya: "
        };

        function openWhatsApp(serviceId) {
            const waNumber = '6285198331549'; 
            const message = encodeURIComponent(serviceMap[serviceId]);
            window.open(`https://wa.me/${waNumber}?text=${message}`, '_blank');
        }

        // Inisialisasi: Aktifkan tab iPhone saat halaman dimuat
        document.addEventListener('DOMContentLoaded', () => {
            const iphoneButton = document.querySelector('.price-tab-button[onclick*="iphone"]');
            if(iphoneButton) showPrice('iphone', iphoneButton);
        });
    </script>
</body>
</html>
