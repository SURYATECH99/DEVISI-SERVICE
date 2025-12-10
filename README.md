<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Surya Teknisi // DARK MODE // Service HP Premium</title>
    
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    
    <style>
        /* ======================================= */
        /* 1. VARIABLE DEFINITIONS (COLOR & SHADOW)*/
        /* ======================================= */
        :root {
            /* Palette Futuristik - Dark & Neon */
            --color-primary: #0077c2; 
            --color-electric: #00ccff; /* Electric Cyan/Blue Neon */
            --color-success: #2ecc71;
            
            --bg-dark-deep: #0a0a0a; /* Background Hitam Murni */
            --bg-dark-card: #141414; /* Card lebih terang sedikit */
            --text-light: #f0f0f0;
            --text-muted: #888888;
            
            /* Neon Glow Shadow */
            --shadow-neon: 0 0 10px rgba(0, 204, 255, 0.5), 0 0 20px rgba(0, 204, 255, 0.2); 
            --shadow-soft: 0 4px 15px rgba(0, 0, 0, 0.5);
        }

        /* ======================================= */
        /* 2. GLOBAL STYLES & ANIMATIONS           */
        /* ======================================= */
        
        @keyframes neon-glow {
            0%, 100% { box-shadow: var(--shadow-neon); }
            50% { box-shadow: 0 0 15px rgba(0, 204, 255, 0.8), 0 0 30px rgba(0, 204, 255, 0.4); }
        }

        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--bg-dark-deep);
            color: var(--text-light);
            line-height: 1.7; 
            scroll-behavior: smooth;
            overflow-x: hidden;
        }

        a {
            text-decoration: none;
            color: var(--text-light);
            transition: all 0.3s ease;
        }

        .container {
            max-width: 1280px;
            margin: 0 auto;
            padding: 0 30px;
        }

        /* ======================================= */
        /* 3. LAYOUT & NAVIGATION                  */
        /* ======================================= */
        
        /* Navigation Bar - Dark Glass */
        .navbar {
            background-color: rgba(10, 10, 10, 0.85);
            backdrop-filter: blur(8px); 
            padding: 20px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            border-bottom: 2px solid var(--color-electric); 
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.7);
        }
        .navbar .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo { 
            font-size: 2.2em; 
            font-weight: 900; 
            color: var(--color-electric); 
            text-shadow: var(--shadow-neon); 
        }
        .nav-links a { 
            font-weight: 400; 
            padding: 10px 15px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        .nav-links a:hover { 
            color: var(--color-electric);
            text-shadow: 0 0 5px var(--color-electric);
        }
        .cta-nav { 
            background-color: var(--color-success);
            color: var(--bg-dark-card) !important;
            padding: 10px 22px; 
            border-radius: 5px; 
            font-weight: 700 !important; 
            box-shadow: 0 0 10px rgba(46, 204, 113, 0.5);
            text-transform: uppercase;
        }
        .cta-nav:hover { 
            background-color: #27ae60;
            transform: scale(1.05); 
        }

        /* Floating WhatsApp Button */
        .floating-whatsapp {
            position: fixed;
            bottom: 30px;
            right: 30px;
            z-index: 999;
        }
        .floating-whatsapp a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 60px;
            height: 60px;
            font-size: 2.2em;
            background-color: var(--color-success); 
            border-radius: 50%; 
            animation: neon-glow 3s infinite alternate; 
            border: 3px solid var(--color-electric);
            color: var(--bg-dark-deep); /* Ikon WA berwarna gelap */
        }
        .floating-whatsapp a:hover {
            transform: scale(1.1);
        }

        /* ======================================= */
        /* 4. SECTIONS & COMPONENTS                */
        /* ======================================= */

        /* 4.1. Hero Section - Asymmetric */
        .header-wrap {
            background: linear-gradient(135deg, var(--bg-dark-deep) 0%, #1a1a1a 100%);
            padding: 200px 0 150px 0; 
            position: relative;
            text-align: center;
            clip-path: polygon(0 0, 100% 0, 100% 90%, 0% 100%);
            margin-bottom: -100px;
            border-bottom: 5px solid var(--color-electric);
        }
        header h1 {
            font-size: 6em; 
            font-weight: 900;
            letter-spacing: -4px; 
            line-height: 0.95;
            text-shadow: 0 0 20px rgba(0, 204, 255, 0.6);
            margin-bottom: 20px;
        }
        .h1-accent {
            color: var(--color-electric);
            font-weight: 200;
        }
        header p {
            font-size: 1.8em;
            font-weight: 300;
            margin-bottom: 80px;
            color: var(--text-muted);
            letter-spacing: 1px;
            text-transform: uppercase;
        }
        .cta-button {
            background-color: var(--color-electric);
            color: var(--bg-dark-deep);
            padding: 22px 60px; 
            border-radius: 5px; 
            font-size: 1.5em;
            font-weight: 800;
            text-transform: uppercase;
            letter-spacing: 1px;
            border: 3px solid var(--color-electric);
            animation: neon-glow 2s infinite alternate;
            transition: all 0.3s ease-out;
        }
        .cta-button:hover {
            background-color: transparent;
            color: var(--color-electric);
            transform: scale(1.05);
            animation: none;
            box-shadow: 0 0 25px rgba(0, 204, 255, 0.8);
        }

        /* 4.2. Main Section Styling */
        .section {
            background-color: var(--bg-dark-card);
            padding: 60px;
            margin: 120px 0; 
            border-radius: 10px;
            box-shadow: var(--shadow-soft); 
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: all 0.3s ease;
        }
        .section:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.8);
        }
        .section h2 {
            font-size: 3.2em;
            font-weight: 200; 
            color: var(--text-light);
            margin-bottom: 50px;
            letter-spacing: 2px;
            text-align: center;
        }
        .section h2 strong {
            font-weight: 800;
            color: var(--color-electric);
        }

        /* 4.3. Warranty Box - Inverted Neon */
        .warranty-box {
            background: var(--color-electric);
            color: var(--bg-dark-deep);
            padding: 50px; 
            border-radius: 5px;
            margin: 150px auto 100px auto;
            border: 5px solid var(--bg-dark-deep);
            box-shadow: var(--shadow-neon);
            max-width: 800px;
            text-align: center;
            transform: rotateZ(-0.5deg);
        }
        .warranty-box h3 {
            display: flex; 
            align-items: center; 
            justify-content: center;
            font-size: 2.8em; 
            font-weight: 900;
            letter-spacing: 1px;
            text-transform: uppercase;
            color: var(--bg-dark-deep);
        }
        .warranty-box p {
            color: var(--bg-dark-deep); 
            font-weight: 500;
        }
        .warranty-box .guarantee-icon {
            font-size: 1.2em;
            margin-right: 15px;
        }

        /* 4.4. Layanan Cards */
        .layanan-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 40px;
        }
        .layanan-card {
            padding: 40px;
            border-radius: 15px;
            background: var(--bg-dark-card);
            border: 1px solid var(--color-electric);
            box-shadow: 0 0 5px rgba(0, 204, 255, 0.3);
            transition: all 0.4s ease;
        }
        .layanan-card:hover {
            transform: scale(1.03); 
            background: var(--bg-dark-deep);
            box-shadow: var(--shadow-neon);
            border-color: var(--color-success);
        }
        .layanan-icon {
            font-size: 4em; 
            color: var(--color-electric);
            background-color: transparent; 
            padding: 10px; 
            border-radius: 50%;
            margin-bottom: 25px;
        }
        .layanan-card h3 {
            font-size: 1.6em;
            font-weight: 700;
            color: var(--color-electric);
            text-transform: uppercase;
        }

        /* 4.5. Process Flow */
        .process-flow {
            position: relative;
            display: flex;
            justify-content: space-between;
            text-align: center;
            padding-top: 20px;
        }
        .process-flow::before {
            content: '';
            position: absolute;
            top: 50px; 
            left: 0;
            right: 0;
            margin: 0 15%;
            height: 4px; 
            background: var(--color-electric); 
            z-index: 1;
        }
        .step {
            flex: 1;
            position: relative;
            z-index: 2;
            padding: 0 10px;
        }
        .step-icon {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 80px;
            height: 80px;
            margin: 0 auto 20px auto;
            font-size: 2em;
            background-color: var(--bg-dark-card);
            color: var(--color-electric);
            border: 4px solid var(--color-electric);
            border-radius: 50%;
            box-shadow: 0 0 10px rgba(0, 204, 255, 0.5);
            transition: all 0.3s ease;
        }
        .step:hover .step-icon {
            background-color: var(--color-electric);
            color: var(--bg-dark-deep);
            box-shadow: 0 0 15px var(--color-electric);
        }
        .step h4 {
            font-weight: 700;
            text-transform: uppercase;
            color: var(--text-light);
        }

        /* 4.6. Final CTA Section */
        .final-cta-wrap {
            position: relative;
            background-color: var(--bg-dark-card);
            color: var(--text-light);
            padding: 120px 0;
            margin-top: 100px;
            text-align: center;
            border-top: 5px solid var(--color-success);
        }
        .final-cta-wrap h2 {
            font-size: 3.5em;
            font-weight: 200;
            color: var(--color-electric);
            margin-bottom: 15px;
        }
        .final-cta-wrap h2 strong {
            font-weight: 900;
            color: var(--color-success);
        }
        .final-cta-wrap p {
            color: var(--text-muted);
            font-weight: 300;
            margin-bottom: 50px;
            text-transform: uppercase;
        }
        .final-cta-wrap .cta-button {
            /* Override CTA Main Button Animation */
            background-color: var(--color-success); 
            color: var(--bg-dark-deep); 
            border-color: var(--color-success); 
            animation: none; 
            box-shadow: 0 0 15px rgba(46, 204, 113, 0.7);
        }
        .final-cta-wrap .cta-button:hover {
            color: var(--color-success);
            background-color: transparent;
            box-shadow: 0 0 25px rgba(46, 204, 113, 1);
        }
        
        /* 4.7. Footer */
        footer {
            background-color: var(--bg-dark-deep);
            color: var(--text-muted);
            padding: 80px 0 50px 0; 
            border-top: 2px solid var(--text-muted);
        }
        .footer-content {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            gap: 30px;
        }
        .footer-col {
            width: 20%; 
            min-width: 200px;
        }
        .footer-col h4 {
            color: var(--color-electric);
            text-transform: uppercase;
            font-weight: 700;
            margin-bottom: 25px;
            position: relative;
        }
        .footer-col ul {
            list-style: none;
            padding: 0;
        }
        .footer-col ul li {
            margin-bottom: 10px;
        }
        .footer-col ul li a {
            color: var(--text-muted);
            font-weight: 300;
        }
        .footer-col ul li a:hover {
            color: var(--color-electric);
        }
        .social-links {
            display: flex;
            gap: 15px;
            margin-top: 15px;
        }
        .social-links a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 40px;
            height: 40px;
            font-size: 1.2em;
            background-color: transparent; 
            border: 1px solid var(--color-electric); 
            border-radius: 4px;
            color: var(--color-electric);
        }
        .social-links a:hover {
            background-color: var(--color-electric);
            color: var(--bg-dark-deep);
        }
        .footer-bottom {
            border-top: 1px solid rgba(255, 255, 255, 0.05);
            margin-top: 40px;
            padding-top: 20px;
            text-align: center;
            color: #4b4b4b;
            font-size: 0.9em;
        }
        .footer-note {
            color: #333333;
            margin-top: 5px;
        }

        /* ======================================= */
        /* 5. MEDIA QUERIES (RESPONSIVENESS)       */
        /* ======================================= */
        
        @media (max-width: 1000px) {
            .footer-col {
                width: 45%;
                min-width: 150px;
            }
        }
        
        @media (max-width: 900px) {
            /* Header */
            header h1 { font-size: 4em; letter-spacing: -2px; }
            header p { font-size: 1.2em; }
            .header-wrap { clip-path: polygon(0 0, 100% 0, 100% 95%, 0% 100%); padding: 100px 0 80px 0; }
            
            /* Sections */
            .section { padding: 30px; margin: 80px 0; }
            .section h2 { font-size: 2.5em; }
            .warranty-box { transform: none; margin: 80px auto; padding: 30px; }
            .warranty-box h3 { font-size: 2em; }

            /* Layouts */
            .layanan-grid { gap: 20px; }
            .process-flow { flex-direction: column; }
            .process-flow::before { display: none; }
            .step { margin-bottom: 20px; }

            /* Footer */
            .footer-content { justify-content: center; }
            .footer-col { width: 100%; text-align: center; min-width: unset; }
        }
    </style>
</head>
<body>
    
    <div class="floating-whatsapp">
        <a href="https://wa.me/6285198331549" target="_blank" aria-label="Hubungi via WhatsApp">
            <i class="fab fa-whatsapp"></i>
        </a>
    </div>

    <nav class="navbar">
        <div class="container">
            <a href="#" class="logo">// SURYA TEKNISI</a>
            <div class="nav-links">
                <a href="#layanan">Layanan</a>
                <a href="#proses">Proses</a>
                <a href="#testimoni">Testimoni</a>
                <a href="tel:085198331549" class="cta-nav"><i class="fas fa-phone"></i> KONSULTASI GRATIS</a>
            </div>
        </div>
    </nav>

    <header class="header-wrap">
        <div class="container">
            <h1><span class="h1-accent">SERVICE HP TINGKAT CHIP</span> <br>GARANSI 90 HARI</h1>
            <p>GRATIS ANTAR JEMPUT // AREA SURABAYA</p>
            <a href="https://wa.me/6285198331549" target="_blank" class="cta-button"><i class="fab fa-whatsapp"></i> JADWALKAN PENJEMPUTAN</a>
        </div>
    </header>

    <div class="container">
        
        <section class="warranty-box">
            <h3>
                <span class="guarantee-icon"><i class="fas fa-shield-alt"></i></span> 
                JAMINAN RESMI GARANSI 90 HARI
            </h3>
            <p>Kualitas Premium, Suku Cadang Terjamin. Ketenangan Anda Prioritas Kami.</p>
        </section>

        <section class="section" id="layanan">
            <h2>Layanan <strong>Utama</strong> Kami</h2>
            <div class="layanan-grid">
                
                <div class="layanan-card">
                    <div class="layanan-icon"><i class="fas fa-mobile-alt"></i></div>
                    <h3>GANTI LAYAR/LCD</h3>
                    <p>Penggantian layar dengan part yang menjamin kualitas visual dan sentuhan.</p>
                </div>

                <div class="layanan-card">
                    <div class="layanan-icon"><i class="fas fa-microchip"></i></div>
                    <h3>SERVIS MAINBOARD</h3>
                    <p>Perbaikan kerusakan tingkat lanjut (mati total, short) oleh teknisi bersertifikasi.</p>
                </div>

                <div class="layanan-card">
                    <div class="layanan-icon"><i class="fas fa-battery-full"></i></div>
                    <h3>BATERAI & CHARGING</h3>
                    <p>Solusi daya tahan baterai dan masalah konektor charging yang cepat dan akurat.</p>
                </div>

                <div class="layanan-card">
                    <div class="layanan-icon" style="color: var(--color-success);"><i class="fas fa-shipping-fast"></i></div>
                    <h3>FREE PICKUP & DELIVERY</h3>
                    <p>Layanan eksklusif Surabaya: Kami ambil, perbaiki, dan antar kembali HP Anda, gratis.</p>
                </div>
            </div>
        </section>

        <section class="section" id="proses">
            <h2>Alur Kerja <strong>Terstruktur</strong></h2>
            <p style="text-align: center; color: var(--text-muted); margin-bottom: 40px; font-weight: 400;">Setiap tahap dilakukan secara transparan dan profesional.</p>
            
            <div class="process-flow">
                <div class="step">
                    <div class="step-icon"><i class="fas fa-handshake"></i></div>
                    <h4>1. BOOKING</h4>
                    <p>Jadwalkan penjemputan via WA.</p>
                </div>
                <div class="step">
                    <div class="step-icon"><i class="fas fa-search-plus"></i></div>
                    <h4>2. DIAGNOSA</h4>
                    <p>Pengujian mendalam di workshop.</p>
                </div>
                <div class="step">
                    <div class="step-icon"><i class="fas fa-cogs"></i></div>
                    <h4>3. PERBAIKAN</h4>
                    <p>Proses perbaikan dan kontrol kualitas.</p>
                </div>
                <div class="step">
                    <div class="step-icon"><i class="fas fa-check-circle"></i></div>
                    <h4>4. SELESAI</h4>
                    <p>HP diantar kembali, garansi aktif!</p>
                </div>
            </div>
        </section>

        <section class="section" id="testimoni" style="text-align: center;">
            <h2>Apa Kata <strong>Pelanggan</strong> Kami</h2>
            <div style="color: var(--text-muted);">
                <p>*(Placeholder untuk Testimoni Carousel yang akan diintegrasikan dengan JavaScript)*</p>
                <div style="font-size: 3em; margin-top: 30px; color: var(--color-electric);"><i class="fas fa-quote-left"></i></div>
            </div>
        </section>
    </div>
        
    <section class="final-cta-wrap">
        <div class="container">
            <h2>HP Anda Siap Kembali <strong>Sempurna</strong>?</h2>
            <p style="font-size: 1.2em;">Jadwalkan penjemputan gratis sekarang untuk layanan service premium bergaransi.</p>
            <a href="https://wa.me/6285198331549" target="_blank" class="cta-button final-cta-button"><i class="fab fa-whatsapp"></i> CHAT DAN MULAI SERVICE</a>
        </div>
    </section>

    <footer>
        <div class="container">
            <div class="footer-content">
                
                <div class="footer-col">
                    <h4>KONTAK // LOKASI</h4>
                    <p>Alamat Workshop: <br>Surabaya (Detail alamat via WA)</p>
                    <p>Telepon: <a href="tel:085198331549">0851 9833 1549</a></p>
                    <p>Email: <a href="mailto:info@suryateknisi.com">info@suryateknisi.com</a></p>
                </div>
                
                <div class="footer-col">
                    <h4>TAUTAN // CEPAT</h4>
                    <ul>
                        <li><a href="#layanan">Layanan</a></li>
                        <li><a href="#proses">Proses Kerja</a></li>
                        <li><a href="#testimoni">Testimoni</a></li>
                    </ul>
                </div>

                <div class="footer-col">
                    <h4>IKUTI // KAMI</h4>
                    <div class="social-links">
                        <a href="https://wa.me/6285198331549" target="_blank" aria-label="WhatsApp"><i class="fab fa-whatsapp"></i></a>
                        <a href="#" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
                        <a href="#" aria-label="Facebook"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" aria-label="YouTube"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>

                <div class="footer-col">
                    <h4>JAMINAN // KAMI</h4>
                    <ul>
                        <li><a href="#">Teknisi Bersertifikasi</a></li>
                        <li><a href="#">Suku Cadang Premium</a></li>
                        <li><a href="#">Garansi Ulang Hingga 90 Hari</a></li>
                        <li><a href="#">Harga Transparan</a></li>
                    </ul>
                </div>

            </div>

            <div class="footer-bottom">
                <p>SURYA TEKNISI &copy; 2025 // ALL RIGHTS RESERVED.</p>
                <p class="footer-note">GRATIS ANTAR JEMPUT HANYA BERLAKU UNTUK AREA KOTA SURABAYA.</p>
            </div>
        </div>
    </footer>

</body>
</html>
