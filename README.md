<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Surya Teknisi | High-End Performance Repair (Cyber Neon Centered)</title>
    
    <link href="https://fonts.googleapis.com/css2?family=Teko:wght@400;600;700&family=Inter:wght@400;600;700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    
    <style>
        /* ===================================================================
           1. VARIABLE & ANIMATIONS
           =================================================================== */
        :root {
            --neon-blue: #00ffff; 
            --neon-purple: #9d00ff; 
            --bg-dark: #0d0d1e; 
            --bg-medium: #1a1a2e;
            --text-light: #e0f7fa; 
            --text-secondary: #a0a0c0;
            --border-opacity: 0.2;
        }
        
        @keyframes neon-pulse {
            0% { text-shadow: 0 0 5px var(--neon-blue), 0 0 10px var(--neon-purple); }
            50% { text-shadow: 0 0 8px var(--neon-blue), 0 0 15px var(--neon-blue); }
            100% { text-shadow: 0 0 5px var(--neon-blue), 0 0 10px var(--neon-purple); }
        }

        @keyframes border-flicker {
            0%, 100% { border-color: rgba(0, 255, 255, 0.4); }
            50% { border-color: rgba(157, 0, 255, 0.6); }
        }
        
        /* ===================================================================
           2. GLOBAL STYLES & LAYOUT (CENTERING)
           =================================================================== */
        body {
            font-family: 'Inter', sans-serif; 
            margin: 0; padding: 0; 
            background-color: var(--bg-dark); 
            color: var(--text-light); 
            line-height: 1.6; 
            scroll-behavior: smooth;
            background-image: radial-gradient(circle at center, #1b1b36 1px, transparent 0);
            background-size: 40px 40px;
            background-attachment: fixed;
        }
        
        /* Kontainer Utama - Memastikan konten di tengah */
        .container { 
            max-width: 1200px; 
            margin: 0 auto; 
            padding: 0 25px; 
        }
        
        .section { 
            padding: 100px 0; 
            position: relative; 
            text-align: center; 
        }
        
        /* Glass Box Style */
        .glass-box {
            background: rgba(26, 26, 46, 0.6);
            backdrop-filter: blur(10px); 
            -webkit-backdrop-filter: blur(10px);
            border-radius: 12px;
            padding: 50px;
            margin-bottom: 40px;
            border: 1px solid rgba(0, 255, 255, var(--border-opacity));
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1), 0 0 20px rgba(0, 255, 255, 0.3);
            transition: all 0.5s;
            text-align: left; 
            margin: 0 auto 40px auto; 
        }
        .glass-box:hover {
            box-shadow: 0 4px 40px rgba(0, 0, 0, 0.2), 0 0 30px rgba(157, 0, 255, 0.5);
            border: 1px solid rgba(157, 0, 255, 0.4);
        }

        /* Headings */
        .section h2 {
            font-family: 'Teko', sans-serif;
            font-size: 4.5em; 
            font-weight: 700; 
            color: var(--text-light);
            text-align: center;
            letter-spacing: 5px; 
            text-transform: uppercase;
            animation: neon-pulse 3s ease-in-out infinite alternate;
            margin-bottom: 10px;
        }
        .section p.sub-heading {
            text-align: center;
            color: var(--neon-blue);
            font-size: 1.1em;
            margin-bottom: 50px;
            font-weight: 400; 
            text-shadow: 0 0 5px rgba(0, 255, 255, 0.4);
        }

        /* ===================================================================
           3. NAVBAR (Diupdate: Menghapus menu burger)
           =================================================================== */
        .navbar {
            background: rgba(13, 13, 30, 0.9);
            backdrop-filter: blur(15px);
            padding: 18px 0;
            position: sticky; top: 0; z-index: 1000;
            border-bottom: 2px solid rgba(0, 255, 255, 0.2);
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.5);
        }
        .navbar-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px; 
            margin: 0 auto; 
            padding: 0 25px;
        }
        .navbar-logo {
            font-family: 'Teko', sans-serif; font-size: 2.2em; font-weight: 700; 
            color: var(--text-light) !important; letter-spacing: 3px; 
            text-shadow: 0 0 5px var(--neon-blue);
        }
        .navbar-logo .logo-brand { color: var(--neon-blue); }
        .nav-links a {
            padding: 8px 15px; 
            color: var(--text-secondary);
            font-weight: 500; 
            transition: all 0.3s ease;
            text-transform: uppercase;
            border-bottom: 2px solid transparent;
            text-decoration: none;
        }
        .nav-links a:hover {
            color: var(--neon-blue);
            border-bottom: 2px solid var(--neon-blue);
            text-shadow: 0 0 8px var(--neon-blue);
        }
        
        /* ===================================================================
           4. HEADER & CTA
           =================================================================== */
        .header-section {
            padding: 180px 0 150px 0; 
            text-align: center; 
            position: relative;
            background: var(--bg-dark); 
        }
        .header-content {
             position: relative; z-index: 1; 
        }
        .header-content h1 {
            font-family: 'Teko', sans-serif; font-size: 6em; 
            text-shadow: 0 0 20px rgba(0, 255, 255, 0.9), 0 0 5px rgba(255, 255, 255, 0.8);
            color: var(--text-light);
            animation: neon-pulse 3s ease-in-out infinite;
        }
        .header-content p {
            font-size: 1.4em; 
            margin: 15px 0 50px 0;
            color: var(--neon-purple); 
            font-weight: 600;
        }
        .header-cta-button {
            padding: 18px 60px; background-color: var(--neon-blue); 
            color: var(--bg-dark) !important; 
            box-shadow: 0 0 15px var(--neon-blue), 0 0 30px var(--neon-blue);
            border: 2px solid var(--neon-blue); border-radius: 4px; 
            font-size: 1.3em; font-weight: 900; letter-spacing: 1px; 
            transition: all 0.3s; display: inline-block; text-decoration: none;
        }
        .header-cta-button:hover {
            transform: scale(1.05); background-color: var(--neon-purple);
            box-shadow: 0 0 15px var(--neon-purple), 0 0 40px var(--neon-purple);
            border-color: var(--neon-purple);
        }

        /* ===================================================================
           5. GRIDS & CARDS
           =================================================================== */
        
        /* KEUNGGULAN (Grid 3 Kolom) */
        .keunggulan-grid {
            display: flex; justify-content: space-between; gap: 30px;
            max-width: 1000px; 
            margin: 0 auto; 
        }
        .keunggulan-item {
            flex: 1; text-align: center; padding: 30px; 
            background: rgba(13, 13, 30, 0.5); backdrop-filter: blur(8px);
            border: 1px solid rgba(0, 255, 255, 0.1); border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 255, 255, 0.1); transition: all 0.4s;
            position: relative; overflow: hidden;
        }
        .keunggulan-item i { font-size: 3.5em; color: var(--neon-blue); text-shadow: 0 0 10px var(--neon-blue); }
        .keunggulan-item h3 { color: var(--text-light); font-family: 'Teko', sans-serif; font-size: 1.8em; margin: 15px 0 10px 0; }
        .keunggulan-item:hover { transform: translateY(-5px); box-shadow: 0 10px 20px rgba(0, 0, 0, 0.5), 0 0 20px rgba(157, 0, 255, 0.4); }
        
        /* LAYANAN (Grid 3 Kolom) */
        .layanan-grid {
            display: flex; justify-content: space-between; gap: 20px;
            margin-top: 40px;
        }
        .layanan-item {
            flex: 1; text-align: center; padding: 30px 20px;
            background: rgba(13, 13, 30, 0.4); border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 6px; transition: all 0.3s;
            cursor: pointer;
        }
        .layanan-item:hover { border: 1px solid var(--neon-purple); box-shadow: 0 0 15px rgba(157, 0, 255, 0.5); }
        .layanan-item i { font-size: 2.5em; color: var(--neon-purple); text-shadow: 0 0 8px var(--neon-purple); margin-bottom: 10px; }
        
        /* PROSES (Flow Diagram) */
        .process-flow { 
            position: relative; display: flex; justify-content: space-between; 
            padding-top: 50px; 
            max-width: 1000px; 
            margin: 0 auto; 
        }
        .process-flow::before { 
            content: ''; position: absolute; top: 75px; left: 15%; right: 15%; height: 2px; 
            background: var(--neon-purple); z-index: 1;
        }
        .step { position: relative; width: 22%; text-align: center; z-index: 2; }
        .step-icon { 
            width: 70px; height: 70px; border-radius: 50%;
            background-color: var(--bg-dark); border: 4px solid var(--neon-blue);
            display: flex; justify-content: center; align-items: center;
            margin: 0 auto 15px auto; transition: all 0.3s;
            box-shadow: 0 0 10px var(--neon-blue);
            animation: border-flicker 4s linear infinite alternate;
        }
        .step h4 { color: var(--neon-blue); font-family: 'Teko', sans-serif; font-weight: 700; letter-spacing: 1px; text-shadow: 0 0 5px var(--neon-blue); }

        /* TESTIMONIALS (Grid 3 Kolom) */
        .testimonial-grid {
            display: flex; justify-content: space-between; gap: 20px;
            margin-top: 40px;
        }
        .testimonial-card {
            flex: 1; padding: 25px; border-radius: 6px; 
            background: rgba(13, 13, 30, 0.7); 
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: transform 0.3s;
            text-align: center;
        }
        
        /* ===================================================================
           6. PRICING TABLE & TABS
           =================================================================== */
        .price-tabs-container {
            display: flex; justify-content: center; margin-bottom: 30px;
        }
        .price-tab-button {
            padding: 10px 20px; margin: 0 5px; cursor: pointer;
            border: 1px solid var(--neon-blue); 
            background: rgba(13, 13, 30, 0.7);
            color: var(--neon-blue);
            transition: all 0.3s; border-radius: 4px;
            font-weight: 600; text-transform: uppercase;
        }
        .price-tab-button:hover, .price-tab-button.active {
            background-color: var(--neon-blue);
            color: var(--bg-dark);
            box-shadow: 0 0 10px var(--neon-blue);
        }
        .price-content { display: none; margin-top: 20px; }
        .price-content.active { display: block; }

        table { width: 100%; border-collapse: collapse; margin: 0 auto; max-width: 800px; }
        th, td { padding: 15px; text-align: left; border-bottom: 1px solid rgba(255, 255, 255, 0.1); }
        th { background-color: var(--neon-purple); color: var(--text-light); text-align: center; font-size: 1.2em; font-family: 'Teko', sans-serif; }
        td:nth-child(2) { text-align: right; }
        .price-highlight { color: var(--neon-blue); text-shadow: 0 0 5px rgba(0, 255, 255, 0.3); font-weight: 700; }

        /* ===================================================================
           7. DELIVERY PROMO
           =================================================================== */
        .delivery-promo {
            padding: 40px; border-radius: 8px; text-align: center;
            background: var(--neon-purple); color: var(--text-light); 
            box-shadow: 0 8px 25px rgba(157, 0, 255, 0.5);
            border: 3px solid var(--neon-purple);
            margin: 0 auto 50px auto; 
            max-width: 1000px;
        }
        .delivery-promo h3 { font-size: 2em; margin-bottom: 10px; text-shadow: 0 0 5px var(--bg-dark); }
        .delivery-promo a {
            padding: 15px 40px; background-color: var(--neon-blue); 
            color: var(--bg-dark) !important; font-weight: 900;
            transition: all 0.3s; display: inline-block; text-decoration: none; border-radius: 4px;
        }

        /* ===================================================================
           8. FOOTER & FAB
           =================================================================== */
        footer {
            background-color: var(--bg-dark); padding: 40px 0; 
            border-top: 5px solid; 
            border-image: linear-gradient(to right, var(--neon-blue), var(--neon-purple)) 1;
            border-image-slice: 1;
        }
        .footer-content { display: flex; justify-content: space-between; flex-wrap: wrap; text-align: left; }
        .footer-left { max-width: 40%; }
        .footer-right { max-width: 40%; text-align: right; }
        .footer-left h4 { color: var(--neon-blue); text-shadow: 0 0 5px var(--neon-blue); }
        .contact-info a { color: var(--text-light); text-decoration: none; display: flex; align-items: center; justify-content: flex-end; margin-bottom: 8px; }
        .contact-info a i { color: var(--neon-blue); text-shadow: 0 0 5px var(--neon-blue); margin-right: 10px; }

        .fab-container { position: fixed; bottom: 30px; right: 30px; z-index: 1001; }
        .fab { 
            display: flex; justify-content: center; align-items: center;
            width: 60px; height: 60px; border-radius: 50%; 
            background-color: #25D366; color: white; font-size: 2em;
            box-shadow: 0 0 15px #25D366; transition: all 0.3s;
            text-decoration: none;
        }
        .fab:hover { box-shadow: 0 0 25px #25D366, 0 0 5px white; }

        /* ===================================================================
           9. MOBILE RESPONSIVE (Menyembunyikan Tautan Navigasi di Mobile)
           =================================================================== */
        @media (max-width: 768px) {
            .navbar-content { padding: 0 15px; }
            .header-content h1 { font-size: 3.5em; }
            
            /* Sembunyikan Nav Links di Mobile agar hanya logo yang tampil */
            .nav-links { display: none; }
            
            .keunggulan-grid, .layanan-grid, .testimonial-grid { flex-direction: column; gap: 15px; }
            .process-flow { flex-wrap: wrap; padding-top: 20px; }
            .process-flow::before { display: none; } 
            .step { width: 45%; margin-bottom: 30px; }
            .footer-content { flex-direction: column; align-items: center; text-align: center; }
            .footer-left, .footer-right { max-width: 100%; text-align: center; }
            .contact-info a { justify-content: center; }
            .contact-info a i { margin-right: 5px; }
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
                <i class="fa-solid fa-bolt logo-brand"></i> SURYA TEKNISI
            </a>

            <div class="nav-links" id="nav-links">
                <a href="#layanan">PERBAIKAN</a>
                <a href="#keunggulan">KEUNGGULAN</a>
                <a href="#harga">HARGA</a>
                <a href="#proses">PROSES</a>
                <a href="#testimoni">TESTIMONI</a>
                <a href="#kontak">KONTAK</a>
            </div>
        </div>
    </div>

    <div class="header-section">
        <div class="header-content" data-aos="fade-down">
            <h1>PRECISE REPAIR. PERFORMANCE REBORN.</h1>
            <p>Spesialis Mikrosoldering dan Optimalisasi Performa HP Bergaransi 1 Tahun.</p>
            <a href="https://wa.me/6285198331549?text=Saya%20ingin%20reservasi%20service%20performance%20cyber%20neon.%20Mohon%20infokan%20tipe%20HP%20saya%20dan%20kerusakan." class="header-cta-button" target="_blank">
                <i class="fa-solid fa-screwdriver-wrench"></i> RESERVASI SERVICE
            </a>
        </div>
    </div>

    <div class="container">
        
        <section id="keunggulan" class="section">
            <h2>KEUNGGULAN UTAMA</h2>
            <p class="sub-heading">Apa yang membuat kami berbeda.</p>
            <div class="keunggulan-grid">
                <div class="keunggulan-item" data-aos="fade-up" data-aos-delay="100">
                    <i class="fa-solid fa-trophy"></i>
                    <h3>GARANSI TERBAIK</h3>
                    <p>Jaminan Performa 1 TAHUN untuk Semua Perbaikan Mainboard.</p>
                </div>
                <div class="keunggulan-item" data-aos="fade-up" data-aos-delay="200">
                    <i class="fa-solid fa-rocket"></i>
                    <h3>KECEPATAN MAXIMUM</h3>
                    <p>Diagnosa Kilat dan Eksekusi Pengerjaan yang Efisien.</p>
                </div>
                <div class="keunggulan-item" data-aos="fade-up" data-aos-delay="300">
                    <i class="fa-solid fa-microchip"></i>
                    <h3>TEKNISI ELITE</h3>
                    <p>Ditangani Ahli Mikrosoldering dengan Peralatan Canggih.</p>
                </div>
            </div>
        </section>


        <section id="layanan" class="section">
            <div class="glass-box">
                <h2>CORE SERVICES. HIGH PRECISION REPAIR.</h2>
                <p class="sub-heading">Keahlian kami untuk mempertahankan keunggulan perangkat Anda.</p>
                
                <div class="layanan-grid">
                    <div class="layanan-item" onclick="openWhatsApp('layar')" data-aos="fade-right"><i class="fa-solid fa-mobile-screen"></i><h3>LCD & Display Gaming</h3><p>Mengatasi *Touch Lag*, Layar Rusak, dan Masalah *Refresh Rate*.</p></div>
                    <div class="layanan-item" onclick="openWhatsApp('mainboard')" data-aos="fade-up" data-aos-delay="100"><i class="fa-solid fa-power-off"></i><h3>Mainboard & Power IC</h3><p>Solusi HP Mati Total, *Restart*, dan *Overheating* karena IC Power.</p></div>
                    <div class="layanan-item" onclick="openWhatsApp('baterai')" data-aos="fade-left" data-aos-delay="200"><i class="fa-solid fa-battery-full"></i><h3>Optimasi Baterai & Daya</h3><p>Penggantian Baterai Kualitas Terbaik dan Perbaikan Jalur Fast Charging.</p></div>
                </div>

            </div>
        </section>

    </div> 

    <section id="proses" class="section" style="background-color: var(--bg-medium);">
        <div class="container">
            <h2>4-STEP PROTOCOL</h2>
            <p class="sub-heading">Proses Kerja Cepat, Akurat, dan Transparan.</p>
            
            <div class="process-flow">
                <div class="step" data-aos="zoom-in" data-aos-delay="100"><div class="step-icon"><i class="fa-solid fa-clock-rotate-left"></i></div><h4>1. RESERVASI SLOT</h4><p>Penjadwalan *service* (Cepat, bahkan *On-The-Spot*).</p></div>
                <div class="step" data-aos="zoom-in" data-aos-delay="250"><div class="step-icon"><i class="fa-solid fa-magnifying-glass-chart"></i></div><h4>2. DIAGNOSA TEKNIS</h4><p>Pengecekan mendalam dan laporan biaya ke Anda.</p></div>
                <div class="step" data-aos="zoom-in" data-aos-delay="400"><div class="step-icon"><i class="fa-solid fa-gears"></i></div><h4>3. EKSEKUSI REPAIR</h4><p>Perbaikan presisi dan pengujian performa intensif (QC).</p></div>
                <div class="step" data-aos="zoom-in" data-aos-delay="550"><div class="step-icon"><i class="fa-solid fa-handshake"></i></div><h4>4. REDEPLOYMENT</h4><p>Pengembalian unit siap tempur ke tangan Anda.</p></div>
            </div>
        </div>
    </section>

    <div class="container">

        <section id="harga" class="section">
            <div class="glass-box">
                 <h2>PRICING MATRIX. TRANSPARENT VALUE.</h2>
                <p class="sub-heading">Daftar harga untuk service kualitas terbaik.</p>

                <div class="price-tabs-container" data-aos="fade-in">
                    <button class="price-tab-button active" onclick="showPrice('iphone', this)">IPHONE</button>
                    <button class="price-tab-button" onclick="showPrice('android', this)">ANDROID GAMING</button>
                    <button class="price-tab-button" onclick="showPrice('ic', this)">MICRO-SOLDERING</button>
                </div>

                <div id="iphone" class="price-content active" data-aos="fade-up">
                    <table><thead><tr><th colspan="2">APPLE IPHONE (Display & Power)</th></tr></thead>
                        <tbody>
                            <tr><td>Ganti LCD iPhone 15 Pro Max</td><td class="price-highlight">Mulai Rp 1.100.000</td></tr>
                            <tr><td>Ganti LCD iPhone 13 Pro</td><td class="price-highlight">Mulai Rp 550.000</td></tr>
                            <tr><td>Perbaikan Face ID</td><td class="price-highlight">Mulai Rp 800.000</td></tr>
                        </tbody>
                    </table>
                </div>
                <div id="android" class="price-content" data-aos="fade-up">
                    <table><thead><tr><th colspan="2">ANDROID PREMIUM (Samsung, ROG, Black Shark)</th></tr></thead>
                    <tbody>
                        <tr><td>Ganti LCD Samsung S23 Ultra</td><td class="price-highlight">Mulai Rp 2.000.000</td></tr>
                        <tr><td>Ganti LCD Samsung S21 Ultra</td><td class="price-highlight">Mulai Rp 1.500.000</td></tr>
                        <tr><td>Ganti Baterai Xiaomi 12 Pro</td><td class="price-highlight">Mulai Rp 200.000</td></tr>
                    </tbody>
                    </table>
                </div>
                <div id="ic" class="price-content" data-aos="fade-up">
                    <table><thead><tr><th colspan="2">PERBAIKAN MAINBOARD & FUNGSI (IC)</th></tr></thead>
                    <tbody>
                        <tr><td>Perbaikan IC Power (HP Mati Total)</td><td class="price-highlight">Mulai Rp 600.000</td></tr>
                        <tr><td>Perbaikan Jalur Charging/Port</td><td class="price-highlight">Mulai Rp 350.000</td></tr>
                        <tr><td>Perbaikan Kerusakan Cairan</td><td class="price-highlight">KONSULTASI</td></tr>
                    </tbody>
                    </table>
                </div>
            </div>
        </section>


        <section id="testimoni" class="section">
            <div class="glass-box">
                <h2>CLIENT FEEDBACK. TRUSTED BY PROS.</h2>
                <p class="sub-heading">Kami membuat *gamer* dan *power user* puas dengan performa.</p>
                
                <div class="testimonial-grid">
                    <div class="testimonial-card" data-aos="fade-right" data-aos-delay="100"><i class="fa-solid fa-thumbs-up"></i><p>"Perbaikan IC Power di sini cepat dan hasilnya HP saya tidak lagi *restart* saat bermain game berat. Garansi 1 tahunnya mantap!"</p><h4>- Zaki (Competitive Gamer)</h4></div>
                    <div class="testimonial-card" data-aos="fade-up" data-aos-delay="200"><i class="fa-solid fa-thumbs-up"></i><p>"Layanan jemputnya sesuai janji. Kualitas LCD yang dipasang Ori, *refresh rate* tetap smooth. Recommended!"</p><h4>- Mega (Streamer Mobile)</h4></div>
                    <div class="testimonial-card" data-aos="fade-left" data-aos-delay="300"><i class="fa-solid fa-thumbs-up"></i><p>"Profesional dan sangat mengerti HP high-end. Masalah baterai boros teratasi total. *Full bar*!"</p><h4>- Raga (Tech Enthusiast)</h4></div>
                </div>
            </div>
        </section>

        <section class="section" style="padding: 0;">
             <div id="delivery" class="delivery-promo" data-aos="zoom-in">
                <h3><i class="fa-solid fa-car-side"></i> SERVICE ANTAR JEMPUT INSTAN GRATIS!</h3>
                <p>Kami jemput HP Anda di Surabaya. Fokus pada performa, biarkan kami urus logistiknya.</p>
                <a href="https://wa.me/6285198331549?text=Saya%20ingin%20memanfaatkan%20layanan%20antar%20jemput%20gratis%20untuk%20service%20HP%20di%20Surabaya." 
                   target="_blank">
                   JADWALKAN PICKUP SEKARANG
                </a>
            </div>
        </section>

    </div> 
    
    <footer id="kontak">
        <div class="container footer-content">
            <div class="footer-left">
                <h4><i class="fa-solid fa-bolt"></i> SURYA TEKNISI REPAIR</h4>
                <p>Spesialis Mikrosoldering dan Perbaikan Performa HP Gaming di Surabaya. Dapatkan garansi 1 tahun untuk setiap service IC.</p>
                <p style="margin-top: 10px;">© 2025 Surya Teknisi</p>
            </div>
            <div class="footer-right">
                <h5>HUBUNGI KAMI SEKARANG</h5>
                <div class="contact-info">
                    <a href="https://wa.me/6285198331549" target="_blank">
                        <i class="fa-brands fa-whatsapp"></i> WhatsApp (Fast Response)
                    </a>
                    <a href="tel:085198331549">
                        <i class="fa-solid fa-phone"></i> Telepon: 0851 9833 1549
                    </a>
                    <a href="https://maps.app.goo.gl/YourLocation" target="_blank">
                        <i class="fa-solid fa-location-dot"></i> Lokasi Toko (Surabaya)
                    </a>
                </div>
            </div>
        </div>
    </footer>

    <div class="fab-container">
        <a href="https://wa.me/6285198331549" target="_blank" class="fab"><i class="fa-brands fa-whatsapp"></i></a>
    </div>

    <script>
        // FUNGSI TOGGLE MENU MOBILE (Dihapus karena tombol burger dihapus)
        // Namun, menjaga fungsi untuk tab harga dan WhatsApp
        
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
            layar: "Halo, saya ingin reservasi Service Layar/Display Gaming. Tolong infokan tipe HP saya: ",
            mainboard: "Halo, saya ingin reservasi Perbaikan Mainboard/IC Power. Tolong infokan tipe HP saya: ",
            baterai: "Halo, saya ingin reservasi Optimasi Baterai & Daya. Tolong infokan tipe HP saya: "
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
