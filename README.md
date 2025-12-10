<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Surya Teknisi Premium | Spesialis Service HP Surabaya Garansi 90 Hari</title>
    
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    
    <style>
        /* ===================================================================
           1. CORE & GLOBAL STYLES (DARK MODE)
        =================================================================== */
        :root {
            --bg-dark: #121212; /* Background Hitam Murni */
            --bg-card: #1e1e1e; /* Background Card */
            --primary-color: #bb86fc; /* Biru/Ungu Aksen (Modern) */
            --secondary-color: #ffc107; /* Kuning Kontras (Aksen Utama) */
            --text-light: #e0e0e0; 
            --text-accent: #ffffff; 
            --shadow-dark: 0 4px 15px rgba(0, 0, 0, 0.4);
            --shadow-lift: 0 10px 30px rgba(0, 0, 0, 0.8); 
        }

        body {
            font-family: 'Roboto', Arial, sans-serif; 
            margin: 0; 
            padding: 0; 
            background-color: var(--bg-dark); 
            color: var(--text-light); 
            line-height: 1.6; 
            scroll-behavior: smooth;
        }
        .container {
            max-width: 1200px; 
            margin: 0 auto; 
            padding: 0 25px;
        }
        .section {
            padding: 80px 0; 
        }
        .section-box {
            background-color: var(--bg-card); 
            border-radius: 12px; 
            box-shadow: var(--shadow-dark);
            padding: 50px;
            margin-bottom: 40px;
        }
        .section h2 {
            font-size: 2.5em; 
            font-weight: 900; 
            color: var(--text-accent);
            text-align: center;
            margin-bottom: 10px;
        }
        .section p.sub-heading {
            text-align: center;
            color: var(--text-light);
            font-size: 1.1em;
            margin-bottom: 50px;
        }
        
        /* 2. NAVBAR (MINIMALIS) */
        .navbar {
            background-color: var(--bg-card); 
            border-bottom: 1px solid rgba(255, 255, 255, 0.05);
            padding: 15px 0;
            position: sticky; top: 0; z-index: 1000;
            box-shadow: var(--shadow-dark);
        }
        .navbar-content {
            display: flex;
            justify-content: space-between; 
            align-items: center;
            max-width: 1200px; 
            margin: 0 auto;
            padding: 0 25px; 
        }
        .nav-links {
            display: flex;
            gap: 20px; 
        }
        .nav-links a {
            color: var(--text-light); 
            text-decoration: none; 
            font-weight: 500; 
            padding: 5px 10px; 
            transition: color 0.3s;
        }
        .nav-links a:hover {
            color: var(--secondary-color);
        }
        .navbar-logo {
            font-size: 1.6em;
            font-weight: 900; 
            color: var(--text-accent) !important;
            text-decoration: none; 
            display: flex;
            align-items: center;
            gap: 8px; 
        }
        .navbar-logo .logo-brand {
            color: var(--secondary-color); 
        }
        
        /* Hamburger Menu */
        .hamburger-menu {
            display: none; 
            font-size: 1.8em;
            color: var(--secondary-color);
            cursor: pointer;
        }

        /* 3. HEADER (FOKUS & TEBAL) */
        .header-section {
            background: var(--bg-dark);
            color: var(--text-accent); 
            padding: 150px 0; 
            text-align: center; 
            border-bottom: 2px solid var(--primary-color);
        }
        .header-content h1 {
            font-size: 4em; 
            font-weight: 900;
            margin-top: 0; 
            line-height: 1.1;
        }
        .header-content p {
            font-size: 1.4em; 
            margin: 20px 0 40px 0;
            color: var(--text-light);
        }
        .header-cta-button {
            display: inline-block;
            padding: 16px 50px;
            background-color: var(--secondary-color); 
            color: var(--bg-dark) !important;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 700;
            font-size: 1.2em; 
            transition: all 0.3s;
            box-shadow: 0 0 20px rgba(255, 193, 7, 0.5);
            text-transform: uppercase;
        }
        .header-cta-button:hover {
            background-color: var(--primary-color);
            color: white !important;
            box-shadow: 0 0 25px rgba(187, 134, 252, 0.7);
            transform: scale(1.05);
        }
        
        /* 4. KEUNGGULAN (MODERN SLABS) */
        .keunggulan-grid {
            display: flex;
            justify-content: space-around;
            gap: 30px;
            margin-top: -80px; 
            position: relative;
            z-index: 10;
        }
        .keunggulan-item {
            background-color: var(--bg-card);
            padding: 30px;
            border-radius: 12px;
            text-align: center;
            flex-basis: 30%;
            box-shadow: var(--shadow-dark);
            border: 1px solid var(--primary-color);
            transition: transform 0.3s;
        }
        .keunggulan-item:hover {
            transform: translateY(-8px);
            border-color: var(--secondary-color);
        }
        .keunggulan-item i {
            font-size: 2.8em;
            color: var(--secondary-color);
            margin-bottom: 15px;
        }
        .keunggulan-item h3 {
            font-size: 1.4em;
            font-weight: 700;
            color: var(--text-accent);
        }

        /* 5. LAYANAN GRID */
        .layanan-grid {
             display: grid; 
             grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); 
             gap: 25px; 
             text-align: center;
        }
        .layanan-item {
            background-color: var(--bg-card);
            border-radius: 10px;
            padding: 30px 20px; 
            transition: all 0.3s;
            cursor: pointer; 
            box-shadow: var(--shadow-dark);
            border-bottom: 3px solid var(--primary-color); 
        }
        .layanan-item:hover {
            box-shadow: var(--shadow-lift);
            transform: scale(1.02); 
            border-color: var(--secondary-color);
        }
        .layanan-item i {
            font-size: 3em; 
            color: var(--secondary-color);
            margin-bottom: 15px;
        }
        .layanan-item h3 {
            font-size: 1.3em;
            font-weight: 700;
            color: var(--text-accent);
        }
        
        /* 6. PROSES SERVICE */
        .process-flow {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            position: relative;
            padding: 50px 10px 20px 10px; 
        }
        .process-flow::before {
            content: '';
            position: absolute;
            top: 70px; 
            left: 10%;
            right: 10%;
            height: 3px; 
            background: var(--primary-color); 
            z-index: 1; 
        }
        .step {
            flex-basis: 23%; 
            text-align: center;
            position: relative;
            z-index: 2; 
        }
        .step-icon {
            width: 65px; 
            height: 65px;
            background-color: var(--bg-card);
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 0 auto 15px auto;
            box-shadow: 0 0 10px rgba(255, 193, 7, 0.4); 
            border: 3px solid var(--secondary-color); 
        }
        .step-icon i {
            color: var(--primary-color);
            font-size: 1.5em;
        }
        .step h4 {
            color: var(--secondary-color);
            font-weight: 700;
            font-size: 1.1em;
            margin-bottom: 5px;
        }
        .step p {
            font-size: 0.9em;
            color: var(--text-light);
        }

        /* 7. PRICE TABLE */
        /* Menggunakan styling dark mode untuk tabel */
        .price-tab-button {
            padding: 10px 25px;
            margin: 0 5px 15px 5px;
            border: 2px solid var(--primary-color); 
            border-radius: 50px;
            background-color: var(--bg-card); 
            color: var(--text-light); 
            font-weight: 500;
            cursor: pointer;
            transition: all 0.3s;
        }
        .price-tab-button:hover {
            background-color: var(--primary-color);
            color: white;
        }
        .price-tab-button.active {
            background-color: var(--secondary-color);
            color: var(--bg-dark);
            font-weight: 700;
            border-color: var(--secondary-color);
            transform: translateY(-2px);
        }
        .price-content table {
            width: 100%;
            border-collapse: collapse;
            max-width: 800px;
            margin: 0 auto;
        }
        .price-content th, .price-content td {
            padding: 15px;
            text-align: left;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }
        .price-content th {
            background-color: var(--bg-dark); 
            color: var(--secondary-color);
            text-transform: uppercase;
        }
        .price-content tr:nth-child(even) { 
            background-color: rgba(255, 255, 255, 0.05);
        }
        .price-highlight {
            font-weight: 700;
            color: var(--primary-color); 
        }

        /* 8. TESTIMONIAL */
        .testimonial-grid {
            display: flex;
            gap: 25px;
            justify-content: center;
        }
        .testimonial-card {
            flex: 1;
            padding: 25px;
            background-color: var(--bg-dark);
            border-radius: 10px;
            box-shadow: var(--shadow-dark);
            text-align: center;
            border-left: 5px solid var(--secondary-color);
            transition: transform 0.3s;
        }
        .testimonial-card i {
            color: var(--primary-color);
            font-size: 1.5em;
            margin-bottom: 10px;
        }
        .testimonial-card h4 {
            color: var(--secondary-color);
        }


        /* 9. PROMO ANTAR JEMPUT */
        .delivery-promo {
            background: linear-gradient(90deg, var(--secondary-color) 0%, #ffdb60 100%);
            color: var(--bg-dark); 
            padding: 40px 30px; 
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 0 20px rgba(255, 193, 7, 0.7);
        }
        .delivery-promo h3 {
            font-size: 2em; 
            font-weight: 900;
            color: var(--bg-dark); 
            margin-bottom: 10px;
        }
        .delivery-promo a {
            display: inline-block;
            padding: 14px 35px;
            background-color: var(--bg-dark); 
            color: var(--secondary-color) !important;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 700;
            transition: background-color 0.3s;
            text-transform: uppercase;
            margin-top: 15px;
        }
        .delivery-promo a:hover {
            background-color: var(--primary-color);
            color: white !important;
        }
        
        /* 10. FOOTER & FAB WA */
        footer {
            background-color: var(--bg-dark); 
            color: var(--text-light); 
            padding: 30px 20px; 
            border-top: 1px solid rgba(255, 255, 255, 0.05);
        }
        footer a {
            color: var(--secondary-color); 
        }
        
        .fab-container {position: fixed; bottom: 25px; right: 25px; z-index: 1000;}
        .fab {display: block; width: 55px; height: 55px; background-color: #25d366; color: white; border-radius: 50%; text-align: center; line-height: 55px; font-size: 2em; box-shadow: 0 6px 15px rgba(37, 211, 102, 0.6); transition: transform 0.3s ease;}
        .fab:hover {transform: scale(1.15); }

        /* ===================================================================
           RESPONSIVE MOBILE DESIGN (Max 768px)
        =================================================================== */
        @media (max-width: 768px) {
            
            /* Global & Header */
            .section-box { padding: 30px 20px; }
            .header-content h1 { font-size: 2.8em; }
            .header-section { padding: 80px 0 40px 0; }
            
            /* Navbar Mobile Fix (Hamburger) */
            .navbar-content { padding: 0 15px; }
            .hamburger-menu { display: block; }
            .nav-links { 
                display: none; 
                position: absolute;
                top: 60px; 
                left: 0;
                right: 0;
                background-color: var(--bg-card);
                flex-direction: column;
                text-align: center;
                box-shadow: 0 8px 15px rgba(0, 0, 0, 0.4);
                padding: 10px 0;
                gap: 0;
                z-index: 999;
            }
            .nav-links.active {
                display: flex; 
            }
            .nav-links a { 
                margin: 5px 0; 
                padding: 12px 0;
                width: 100%;
                border-bottom: 1px solid rgba(255, 255, 255, 0.05);
            }
            
            /* Layout Vertikal */
            .keunggulan-grid, .process-flow, .testimonial-grid {
                flex-direction: column;
                gap: 20px;
                margin-top: 20px; 
            }
            .process-flow::before {
                top: 0;
                left: 30px; 
                right: auto;
                width: 3px; 
                height: 100%;
            }
            .step {
                text-align: left;
                display: flex;
                align-items: flex-start;
                gap: 20px;
                padding: 15px 0;
            }
            .step-icon {
                margin: 0;
                flex-shrink: 0; 
            }
            
            /* Price Table */
            .price-content table { display: block; overflow-x: auto; min-width: 500px; }
            .price-tab-button { flex: 1 1 45%; margin: 5px 0; }
        }
    </style>
</head>
<body>

    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        AOS.init({ duration: 900, once: true, disable: 'phone' });
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
                <a href="#keunggulan">Keunggulan</a>
                <a href="#harga">Harga</a>
                <a href="#proses">Proses</a>
                <a href="#testimoni">Testimoni</a>
                <a href="#kontak">Kontak</a>
            </div>
        </div>
    </div>

    <div class="header-section">
        <div class="header-content" data-aos="fade-down">
            <h1>SERVICE HP PREMIUM. GARANSI. ANTAR JEMPUT GRATIS.</h1>
            <p>Spesialis diagnosa Mainboard & Mikro-soldering di Surabaya.</p>
            <a href="#layanan" class="header-cta-button">
                RESERVASI SEKARANG <i class="fa-solid fa-arrow-right"></i>
            </a>
        </div>
    </div>

    <div class="container">
        
        <section id="keunggulan" class="keunggulan-grid">
            <div class="keunggulan-item" data-aos="fade-up" data-aos-delay="100">
                <i class="fa-solid fa-shield-halved"></i>
                <h3>Garansi 90 Hari</h3>
                <p>Jaminan kualitas dan ketenangan pikiran.</p>
            </div>
            <div class="keunggulan-item" data-aos="fade-up" data-aos-delay="200">
                <i class="fa-solid fa-truck-fast"></i>
                <h3>Antar Jemput Gratis</h3>
                <p>Jemput & antar balik 100% gratis SBY.</p>
            </div>
            <div class="keunggulan-item" data-aos="fade-up" data-aos-delay="300">
                <i class="fa-solid fa-microchip"></i>
                <h3>Spesialis Mainboard</h3>
                <p>Perbaikan kerusakan IC tingkat lanjut.</p>
            </div>
        </section>


        <section id="layanan" class="section">
            <div class="section-box">
                <h2>Layanan Inti Kami</h2>
                <p class="sub-heading">Kami menangani semua jenis kerusakan hardware dan software.</p>
                
                <div class="layanan-grid">
                    
                    <div class="layanan-item" onclick="openWhatsApp('layar')" data-aos="fade-right">
                        <i class="fa-solid fa-mobile-screen-button"></i>
                        <h3>Ganti LCD & Layar Sentuh</h3>
                        <p>Layar pecah, *blank*, atau *ghost touch*.</p>
                    </div>
                    
                    <div class="layanan-item" onclick="openWhatsApp('mainboard')" data-aos="fade-up" data-aos-delay="100">
                        <i class="fa-solid fa-gear"></i>
                        <h3>Perbaikan Mainboard (IC)</h3>
                        <p>HP mati total, *bootloop*, IC Power, & IC Charger.</p>
                    </div>
                    
                    <div class="layanan-item" onclick="openWhatsApp('baterai')" data-aos="fade-left" data-aos-delay="200">
                        <i class="fa-solid fa-battery-full"></i>
                        <h3>Baterai & Pengisian Daya</h3>
                        <p>Penggantian baterai dan perbaikan port USB.</p>
                    </div>
                </div>

            </div>
        </section>

        <section id="proses" class="section">
            <div class="section-box" style="padding: 50px 30px;">
                <h2>Proses Service 4 Langkah</h2>
                <p class="sub-heading">Transparansi dan kecepatan adalah fokus utama kami.</p>
                
                <div class="process-flow">
                    
                    <div class="step" data-aos="zoom-in" data-aos-delay="100">
                        <div class="step-icon"><i class="fa-solid fa-calendar-days"></i></div>
                        <h4>1. Jadwal & Jemput</h4>
                        <p>Atur jadwal penjemputan gratis via WA.</p>
                    </div>
                    
                    <div class="step" data-aos="zoom-in" data-aos-delay="250">
                        <div class="step-icon"><i class="fa-solid fa-magnifying-glass"></i></div>
                        <h4>2. Diagnosa Mendalam</h4>
                        <p>Pengecekan dan konfirmasi biaya perbaikan.</p>
                    </div>
                    
                    <div class="step" data-aos="zoom-in" data-aos-delay="400">
                        <div class="step-icon"><i class="fa-solid fa-screwdriver-wrench"></i></div>
                        <h4>3. Perbaikan Profesional</h4>
                        <p>Eksekusi perbaikan & Quality Check ketat.</p>
                    </div>
                    
                    <div class="step" data-aos="zoom-in" data-aos-delay="550">
                        <div class="step-icon"><i class="fa-solid fa-award"></i></div>
                        <h4>4. Garansi & Antar Balik</h4>
                        <p>HP kembali ke tangan Anda dengan garansi.</p>
                    </div>
                    
                </div>
            </div>
        </section>

        <section id="harga" class="section">
            <div class="section-box">
                 <h2>Perkiraan Harga (Starting Price)</h2>
                <p class="sub-heading">Harga estimasi. Hubungi kami untuk harga final berdasarkan tipe HP.</p>

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
                            <tr><td>Perbaikan Face ID</td><td class="price-highlight">Mulai Rp 800.000</td></tr>
                        </tbody>
                    </table>
                </div>
                <div id="android" class="price-content" data-aos="fade-up">
                    <table><thead><tr><th colspan="2">Android Premium (Samsung, Xiaomi, dll.)</th></tr></thead>
                    <tbody>
                        <tr><td>Ganti LCD Samsung S23 Ultra</td><td class="price-highlight">Mulai Rp 2.000.000</td></tr>
                        <tr><td>Ganti LCD Samsung S21 Ultra</td><td class="price-highlight">Mulai Rp 1.500.000</td></tr>
                        <tr><td>Ganti Baterai Xiaomi 12 Pro</td><td class="price-highlight">Mulai Rp 200.000</td></tr>
                    </tbody>
                    </table>
                </div>
                <div id="ic" class="price-content" data-aos="fade-up">
                    <table><thead><tr><th colspan="2">Mikrosoldering & Servis Fungsional</th></tr></thead>
                    <tbody>
                        <tr><td>Perbaikan IC Power (HP Mati Total)</td><td class="price-highlight">Mulai Rp 600.000</td></tr>
                        <tr><td>Perbaikan Jalur Charging/Port</td><td class="price-highlight">Mulai Rp 350.000</td></tr>
                        <tr><td>Perbaikan Kerusakan Cairan</td><td class="price-highlight">Konsultasi</td></tr>
                    </tbody>
                    </table>
                </div>
            </div>
        </section>


        <section id="testimoni" class="section">
            <div class="section-box">
                <h2>Apa Kata Pelanggan?</h2>
                <p class="sub-heading">Pengalaman service yang nyata dan terpercaya.</p>
                
                <div class="testimonial-grid">
                    <div class="testimonial-card" data-aos="fade-right" data-aos-delay="100">
                        <i class="fa-solid fa-quote-left"></i>
                        <p>"Pelayanan cepat dan ramah, LCD iPhone saya kembali seperti baru. Recommended!"</p>
                        <h4>- Bima S.</h4>
                    </div>
                    <div class="testimonial-card" data-aos="fade-up" data-aos-delay="200">
                        <i class="fa-solid fa-quote-left"></i>
                        <p>"HP mati total karena kecemplung air, berhasil dihidupkan lagi. Salut buat teknisi!"</p>
                        <h4>- Risa M.</h4>
                    </div>
                    <div class="testimonial-card" data-aos="fade-left" data-aos-delay="300">
                        <i class="fa-solid fa-quote-left"></i>
                        <p>"Ganti baterai Samsung S21 cepat, dan yang terpenting, ada garansinya. Mantap!"</p>
                        <h4>- Agus P.</h4>
                    </div>
                </div>
            </div>
        </section>

        <section class="section" style="padding: 0;">
             <div id="delivery" class="delivery-promo" data-aos="zoom-in">
                <h3><i class="fa-solid fa-bolt"></i> JEMPUT & ANTAR BALIK GRATIS!</h3>
                <p>Khusus Area Surabaya. Tinggal duduk manis, kami yang urus.</p>
                <a href="https://wa.me/6285198331549?text=Saya%20ingin%20memanfaatkan%20layanan%20antar%20jemput%20gratis%20untuk%20service%20HP%20di%20Surabaya." 
                   target="_blank">
                   JADWALKAN JEMPUTAN
                </a>
            </div>
        </section>

    </div> 
    
    <footer id="kontak">
        <p>Surya Teknisi &copy; 2025 | Workshop Surabaya | Hubungi: <a href="tel:085198331549">0851 9833 1549</a></p>
    </footer>

    <div class="fab-container">
        <a href="https://wa.me/6285198331549" target="_blank" class="fab"><i class="fa-brands fa-whatsapp"></i></a>
    </div>

    <script>
        // FUNGSI TOGGLE MENU MOBILE
        document.getElementById('hamburger-btn').addEventListener('click', function() {
            document.getElementById('nav-links').classList.toggle('active');
        });

        document.querySelectorAll('.nav-links a').forEach(link => {
            link.addEventListener('click', function() {
                if (window.innerWidth <= 768) {
                    document.getElementById('nav-links').classList.remove('active');
                }
            });
        });
        
        // FUNGSI TAB HARGA
        function showPrice(tabId, element) {
            const contents = document.querySelectorAll('.price-content');
            contents.forEach(content => content.classList.remove('active'));
            const buttons = document.querySelectorAll('.price-tab-button');
            buttons.forEach(button => button.classList.remove('active'));

            document.getElementById(tabId).classList.add('active');
            if (element) element.classList.add('active');
        }

        // FUNGSI OPEN WHATSAPP DENGAN PESAN OTOMATIS
        const serviceMap = {
            layar: "Halo, saya ingin reservasi Ganti Layar/LCD Original. Tolong infokan tipe HP saya: ",
            mainboard: "Halo, saya ingin reservasi Servis Mainboard (Mikrosoldering). Tolong infokan tipe HP saya: ",
            baterai: "Halo, saya ingin reservasi Baterai & Pengisian Daya. Tolong infokan tipe HP saya: "
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
