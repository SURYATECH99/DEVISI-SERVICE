<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Surya Teknisi Premium | Spesialis Service HP Surabaya Garansi 90 Hari</title>
    
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700;800;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    
    <style>
        /* ===================================================================
           1. CORE & GLOBAL STYLES (MODERN)
        =================================================================== */
        :root {
            --primary-color: #0056b3; /* Biru Primer yang Kuat */
            --secondary-color: #ffc107; /* Kuning Aksen */
            --dark-color: #1a1a1a; 
            --light-color: #f8f9fa;
            --text-color: #343a40; 
            --shadow-smooth: 0 10px 30px rgba(0, 0, 0, 0.08);
            --shadow-lift: 0 15px 40px rgba(0, 0, 0, 0.15); 
        }

        body {
            font-family: 'Montserrat', Arial, sans-serif; 
            margin: 0; 
            padding: 0; 
            background-color: var(--light-color); 
            color: var(--text-color); 
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
            margin-top: 0;
        }
        .section-box {
            background-color: white; 
            border-radius: 20px; 
            box-shadow: var(--shadow-smooth);
            padding: 50px;
            margin-bottom: 40px;
        }
        .section h2 {
            font-size: 2.5em; 
            font-weight: 800; 
            color: var(--dark-color);
            margin-bottom: 15px;
            text-align: center;
        }
        .section p.sub-heading {
            text-align: center;
            color: #6c757d;
            font-size: 1.1em;
            margin-bottom: 50px;
        }
        
        /* 2. NAVBAR (MODERN CLEAN) */
        .navbar {
            background-color: var(--primary-color); 
            padding: 15px 0;
            position: sticky; top: 0; z-index: 1000;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
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
            gap: 25px; 
        }
        .nav-links a {
            color: white; 
            text-decoration: none; 
            font-weight: 600; 
            padding: 8px 15px; 
            transition: background-color 0.3s, border-radius 0.3s;
            border-radius: 8px;
        }
        .nav-links a:hover {
            background-color: rgba(255, 255, 255, 0.15);
        }
        .navbar-logo {
            font-size: 1.5em;
            font-weight: 900; 
            color: white !important;
            text-decoration: none; 
            display: flex;
            align-items: center;
            gap: 10px; 
        }
        .navbar-logo .logo-brand {
            color: var(--secondary-color); 
            font-weight: 900;
        }
        .navbar-logo i {
            font-size: 1.2em;
            color: var(--secondary-color);
        }
        
        /* Hamburger Menu */
        .hamburger-menu {
            display: none; 
            font-size: 1.8em;
            color: white;
            cursor: pointer;
        }

        /* 3. HEADER (JUMBOTRON BERSIH) */
        .header-section {
            background: linear-gradient(135deg, var(--primary-color) 0%, #007bff 100%); 
            color: #ffffff; 
            padding: 120px 0; 
            text-align: center; 
            margin-bottom: 40px;
        }
        .header-content {
            max-width: 900px; 
            margin: 0 auto; 
        }
        .header-content h1 {
            font-size: 3.5em; 
            font-weight: 900;
            margin-top: 0; 
            line-height: 1.1;
        }
        .header-content p {
            font-size: 1.3em; 
            margin: 20px 0 35px 0;
            opacity: 0.9;
        }
        .header-cta-button {
            display: inline-block;
            padding: 15px 45px;
            background-color: var(--secondary-color); 
            color: var(--dark-color) !important;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 700;
            font-size: 1.1em; 
            transition: all 0.3s;
            box-shadow: 0 8px 20px rgba(255, 193, 7, 0.4);
        }
        .header-cta-button:hover {
            background-color: #ffda6a;
            transform: translateY(-3px);
            box-shadow: 0 12px 25px rgba(255, 193, 7, 0.6);
        }

        /* 4. KEUNGGULAN (FLEXBOX MODERN) */
        .keunggulan-grid {
            display: flex;
            justify-content: space-around;
            gap: 30px;
            margin-top: -100px; /* Overlap dengan header */
            position: relative;
            z-index: 10;
        }
        .keunggulan-item {
            background-color: white;
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            flex-basis: 30%;
            box-shadow: var(--shadow-lift);
            border-top: 5px solid var(--secondary-color);
            transition: transform 0.3s;
        }
        .keunggulan-item:hover {
            transform: translateY(-10px);
        }
        .keunggulan-item i {
            font-size: 2.5em;
            color: var(--primary-color);
            margin-bottom: 15px;
        }
        .keunggulan-item h3 {
            font-size: 1.4em;
            font-weight: 700;
            color: var(--dark-color);
        }

        /* 5. LAYANAN GRID (CARD YANG LEBIH BAIK) */
        .layanan-grid {
             display: grid; 
             grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); 
             gap: 25px; 
             text-align: center;
        }
        .layanan-item {
            background-color: var(--light-color);
            border-radius: 15px;
            padding: 30px 20px; 
            transition: all 0.3s;
            cursor: pointer; 
            box-shadow: var(--shadow-smooth);
            border-left: 5px solid transparent; 
        }
        .layanan-item:hover {
            transform: translateY(-5px); 
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
            border-left: 5px solid var(--primary-color); 
        }
        .layanan-item i {
            font-size: 3em; 
            color: var(--primary-color);
            margin-bottom: 15px;
        }
        .layanan-item h3 {
            font-size: 1.3em;
            font-weight: 700;
            color: var(--dark-color);
        }

        /* 6. PROMO ANTAR JEMPUT (STRIP CTA) */
        .delivery-promo {
            background: var(--dark-color); 
            color: white; 
            padding: 40px 30px; 
            border-radius: 15px;
            text-align: center;
            margin-bottom: 40px;
            border: 1px solid var(--primary-color);
        }
        .delivery-promo h3 {
            font-size: 2em; 
            font-weight: 800;
            color: var(--secondary-color); 
            margin-bottom: 10px;
        }
        .delivery-promo a {
            display: inline-block;
            padding: 14px 35px;
            background-color: var(--primary-color); 
            color: white !important;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 700;
            transition: background-color 0.3s;
            text-transform: uppercase;
            margin-top: 15px;
        }
        .delivery-promo a:hover {
            background-color: #007bff;
        }

        /* 7. FOOTER (DARK MODERN) */
        footer {
            background-color: var(--dark-color); 
            color: white; 
            padding: 40px 20px; 
            font-size: 1em; 
            text-align: center; 
        }
        footer a {
            color: var(--secondary-color); 
            text-decoration: none;
            font-weight: 600; 
        }
        
        /* FAB WA */
        .fab-container {position: fixed; bottom: 25px; right: 25px; z-index: 1000;}
        .fab {display: block; width: 55px; height: 55px; background-color: #25d366; color: white; border-radius: 50%; text-align: center; line-height: 55px; font-size: 2em; box-shadow: 0 6px 15px rgba(37, 211, 102, 0.6); transition: transform 0.3s ease;}
        .fab:hover {transform: scale(1.15); }


        /* ===================================================================
           RESPONSIVE MOBILE DESIGN (Max 768px)
        =================================================================== */
        @media (max-width: 768px) {
            
            /* Global & Header */
            .container { padding: 0 15px; }
            .section { padding: 40px 0; }
            .section-box { padding: 30px 20px; }
            .section h2 { font-size: 2em; }
            .header-content h1 { font-size: 2.5em; }
            .header-section { padding: 80px 0 40px 0; }
            
            /* Navbar Mobile Fix (Hamburger) */
            .navbar-content { padding: 0 15px; }
            .hamburger-menu {
                display: block; /* Tampilkan Hamburger */
            }
            .nav-links { 
                display: none; 
                position: absolute;
                top: 60px; /* Di bawah navbar */
                left: 0;
                right: 0;
                background-color: var(--primary-color);
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
                border-radius: 0;
            }
            
            /* Keunggulan Vertikal */
            .keunggulan-grid {
                flex-direction: column;
                gap: 20px;
                margin-top: 20px; /* Hapus overlap */
            }
            .keunggulan-item {
                flex-basis: 100%;
            }

            /* Price Table Adjustment */
            .price-content table { min-width: 100%; display: block; overflow-x: auto; }
            .price-tab-button { flex: 1 1 45%; margin: 5px 0; }
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
                <a href="#keunggulan">Keunggulan</a>
                <a href="#harga">Harga</a>
                <a href="#delivery">Antar Jemput</a>
                <a href="#kontak">Kontak</a>
            </div>
        </div>
    </div>

    <div class="header-section">
        <div class="header-content" data-aos="fade-down">
            <h1>SPESIALIS SERVICE HP & MAINBOARD PROFESIONAL SURABAYA</h1>
            <p>Diagnosa Cepat, Suku Cadang Original, Garansi Resmi Hingga 90 Hari.</p>
            <a href="#layanan" class="header-cta-button">
                Lihat Semua Layanan <i class="fa-solid fa-arrow-right"></i>
            </a>
        </div>
    </div>

    <div class="container">
        
        <section id="keunggulan" class="keunggulan-grid">
            <div class="keunggulan-item" data-aos="fade-up" data-aos-delay="100">
                <i class="fa-solid fa-shield-halved"></i>
                <h3>Garansi 90 Hari</h3>
                <p>Jaminan kualitas perbaikan dengan garansi purna jual terpanjang.</p>
            </div>
            <div class="keunggulan-item" data-aos="fade-up" data-aos-delay="200">
                <i class="fa-solid fa-truck-fast"></i>
                <h3>Antar Jemput Gratis</h3>
                <p>Layanan *pick-up* dan *delivery* gratis khusus area Surabaya.</p>
            </div>
            <div class="keunggulan-item" data-aos="fade-up" data-aos-delay="300">
                <i class="fa-solid fa-certificate"></i>
                <h3>Suku Cadang Premium</h3>
                <p>Hanya menggunakan komponen berkualitas original/OEM terbaik.</p>
            </div>
        </section>


        <section id="layanan" class="section">
            <div class="section-box">
                <h2>Layanan Utama Surya Teknisi</h2>
                <p class="sub-heading">Pilih layanan di bawah ini dan langsung konsultasi via WhatsApp.</p>
                
                <div class="layanan-grid">
                    
                    <div class="layanan-item" onclick="openWhatsApp('layar')" data-aos="fade-right">
                        <i class="fa-solid fa-mobile-screen-button"></i>
                        <h3>Ganti LCD & Layar Sentuh</h3>
                        <p>Layar pecah, *blank*, *ghost touch*, atau garis-garis.</p>
                    </div>
                    
                    <div class="layanan-item" onclick="openWhatsApp('mainboard')" data-aos="fade-up" data-aos-delay="100">
                        <i class="fa-solid fa-microchip"></i>
                        <h3>Perbaikan Mainboard (IC)</h3>
                        <p>Service HP mati total, *bootloop*, IC Power, & IC Charger.</p>
                    </div>
                    
                    <div class="layanan-item" onclick="openWhatsApp('baterai')" data-aos="fade-left" data-aos-delay="200">
                        <i class="fa-solid fa-battery-full"></i>
                        <h3>Baterai & Pengisian Daya</h3>
                        <p>Penggantian baterai kembung/boros dan perbaikan port USB-C.</p>
                    </div>
                </div>

            </div>
        </section>

        <section id="harga" class="section">
            <div class="section-box">
                 <h2>Cek Perkiraan Harga</h2>
                <p class="sub-heading">Harga transparan untuk perbaikan umum. Hubungi kami untuk harga detail berdasarkan tipe HP.</p>

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
                            <tr><td>Perbaikan Face ID</td><td class="price-highlight">Mulai Rp 800.000</td></tr>
                        </tbody>
                    </table>
                </div>
                <div id="android" class="price-content" data-aos="fade-up">
                    <table><thead><tr><th colspan="2">Android Premium (Samsung, Xiaomi, dll.)</th></tr></thead>
                    <tbody>
                        <tr><td>Ganti LCD Samsung S23 Ultra</td><td class="price-highlight">Mulai Rp 2.000.000</td></tr>
                        <tr><td>Ganti LCD Samsung S21 Ultra</td><td class="price-highlight">Mulai Rp 1.500.000</td></tr>
                        <tr><td>Perbaikan/Ganti Kaca Belakang</td><td class="price-highlight">Mulai Rp 100.000</td></tr>
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
                        <tr><td>Ganti Modul Speaker & Mic</td><td class="price-highlight">Mulai Rp 250.000</td></tr>
                    </tbody>
                    </table>
                </div>
                <p style="text-align: center; font-size: 0.9em; color: #888; margin-top: 30px;">*Harga estimasi. Hubungi kami untuk diagnosa dan harga final.</p>
            </div>
        </section>


        <section class="section" style="padding: 0;">
             <div id="delivery" class="delivery-promo" data-aos="zoom-in">
                <h3><i class="fa-solid fa-map-location-dot"></i> JEMPUT & ANTAR BALIK GRATIS!</h3>
                <p>Khusus Area Surabaya. Nikmati kenyamanan service tanpa perlu keluar rumah. Cepat, Aman, dan Tanpa Biaya Tambahan.</p>
                <a href="https://wa.me/6285198331549?text=Saya%20ingin%20memanfaatkan%20layanan%20antar%20jemput%20gratis%20untuk%20service%20HP%20di%20Surabaya." 
                   target="_blank">
                   Jadwalkan Penjemputan via WhatsApp
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
        
        // FUNGSI TAB HARGA (Sama seperti sebelumnya)
        function showPrice(tabId, element) {
            const contents = document.querySelectorAll('.price-content');
            contents.forEach(content => content.classList.remove('active'));
            const buttons = document.querySelectorAll('.price-tab-button');
            buttons.forEach(button => button.classList.remove('active'));

            document.getElementById(tabId).classList.add('active');
            if (element) element.classList.add('active');
        }

        // FUNGSI OPEN WHATSAPP DENGAN PESAN OTOMATIS (Sama seperti sebelumnya)
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
