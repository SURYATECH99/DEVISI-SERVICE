<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
  <title>Surya Teknisi Premium — Service HP Surabaya | Garansi 90 Hari</title>
  <meta name="description" content="Surya Teknisi — Jasa service HP profesional Surabaya. Spesialis mikrosoldering, ganti LCD, baterai, dan antar jemput gratis. Garansi hingga 90 hari.">
  <meta name="keywords" content="service hp surabaya, teknisi hp, mikrosoldering, ganti lcd, antar jemput gratis">

  <!-- Open Graph -->
  <meta property="og:title" content="Surya Teknisi Premium — Service HP Surabaya">
  <meta property="og:description" content="Spesialis diagnosa mainboard & perbaikan premium. Garansi hingga 90 hari. Antar jemput gratis Surabaya.">
  <meta property="og:type" content="website">
  <meta property="og:image" content="https://via.placeholder.com/1200x630?text=Surya+Teknisi+Premium">

  <!-- Schema: LocalBusiness -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "LocalBusiness",
    "name": "Surya Teknisi",
    "image": "https://via.placeholder.com/1200x630?text=Surya+Teknisi+Premium",
    "@id": "https://example.com/",
    "url": "https://example.com/",
    "telephone": "+6285198331549",
    "address": {
      "@type": "PostalAddress",
      "addressLocality": "Surabaya",
      "addressRegion": "Jawa Timur",
      "addressCountry": "ID"
    },
    "priceRange": "Rp",
    "openingHours": "Mo,Tu,We,Th,Fr 09:00-18:00"
  }
  </script>

  <!-- Fonts & Icons -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

  <style>
    :root{
      --bg:#f6f8fb; --card:#ffffff; --primary:#0b61b7; --accent:#ffb000; --muted:#667085; --success:#1fa73a; --danger:#c91f3a; --glass: rgba(255,255,255,0.6);
      --maxw:1100px; --radius:14px; --shadow: 0 8px 30px rgba(7,18,38,0.08);
    }
    *{box-sizing:border-box}
    html,body{height:100%; margin:0; font-family:'Poppins',system-ui,Arial; background:var(--bg); color:#0b2a3a; -webkit-font-smoothing:antialiased}
    a{color:inherit}

    .container{max-width:var(--maxw); margin:28px auto; padding:0 18px}

    /* NAVBAR */
    .navbar{position:sticky; top:0; z-index:50; backdrop-filter: blur(6px); background: linear-gradient(90deg, rgba(11,97,183,0.96), rgba(3,64,130,0.96)); color:#fff; box-shadow:var(--shadow)}
    .nav-inner{max-width:var(--maxw); margin:0 auto; display:flex; align-items:center; gap:16px; padding:12px 18px}
    .brand{display:flex; gap:10px; align-items:center; text-decoration:none}
    .brand .logo{width:44px;height:44px;border-radius:10px;background:var(--accent); display:grid; place-items:center; color:#082033; font-weight:800}
    .brand h1{font-size:1.05rem;margin:0;font-weight:700}

    .nav-links{margin-left:auto; display:flex; gap:14px; align-items:center}
    .nav-links a{color:#f1f9ff; text-decoration:none; padding:8px 12px; border-radius:8px; font-weight:600; font-size:0.95rem}
    .nav-links a:hover{background:rgba(255,255,255,0.06)}

    /* Hamburger mobile */
    .hamburger{display:none; background:transparent;border:0;color:white;font-size:1.1rem}
    @media(max-width:880px){ .nav-links{display:none} .hamburger{display:block} }

    /* HERO */
    .hero{display:grid; grid-template-columns:1fr 420px; gap:28px; align-items:center; padding:44px 0}
    .hero-card{background:linear-gradient(180deg, rgba(255,255,255,0.6), rgba(255,255,255,0.38)); border-radius:var(--radius); padding:36px; box-shadow:var(--shadow)}
    .kicker{display:inline-block; background:rgba(255,176,0,0.14); color:#774b00; padding:6px 10px;border-radius:999px; font-weight:700; font-size:0.85rem}
    h2.hero-title{margin:16px 0 8px;font-size:1.6rem;color:#072c4b}
    p.lead{margin:0 0 16px;color:var(--muted)}

    .hero-cta{display:flex; gap:12px; flex-wrap:wrap}
    .btn{display:inline-flex; align-items:center; gap:10px; padding:12px 18px; border-radius:12px; text-decoration:none; font-weight:700}
    .btn-primary{background:var(--accent); color:#072033}
    .btn-ghost{background:transparent; border:2px solid rgba(7,18,38,0.06)}

    /* SERVICES */
    .grid{display:grid; grid-template-columns:repeat(3,1fr); gap:18px}
    .card{background:var(--card); border-radius:12px; padding:20px; box-shadow:var(--shadow); text-align:center}
    .card i{font-size:34px; color:var(--primary); margin-bottom:12px}
    .card h3{margin:6px 0 8px}
    .card p{color:var(--muted); font-size:0.95rem}
    .card:hover{transform:translateY(-6px); transition:transform .25s}
    @media(max-width:1024px){ .grid{grid-template-columns:repeat(2,1fr)} }
    @media(max-width:640px){ .hero{grid-template-columns:1fr; } .grid{grid-template-columns:1fr} }

    /* PRICE & TABS */
    .tabs{display:flex; gap:8px; justify-content:center; margin-bottom:18px; flex-wrap:wrap}
    .tab-btn{padding:8px 14px; border-radius:999px; border:2px solid rgba(7,18,38,0.08); background:white; font-weight:700}
    .tab-btn.active{background:var(--primary); color:white; border-color:var(--primary)}
    .price-table{width:100%; border-collapse:collapse; margin:0 auto}
    .price-table th, .price-table td{padding:12px 14px; border-bottom:1px solid #eef2f6}
    .price-table th{background:linear-gradient(90deg,var(--primary), #07579b); color:white}

    /* PROCESS */
    .process{display:flex; gap:12px; align-items:center; justify-content:space-between}
    .step{flex:1; text-align:center}
    .step .dot{width:64px; height:64px; border-radius:50%; display:grid; place-items:center; margin:0 auto 12px; background:var(--primary); color:white}
    @media(max-width:720px){ .process{flex-direction:column} .step{text-align:left} .step .dot{margin:0} }

    /* TESTIMONIAL */
    .testi{display:flex; gap:12px; flex-wrap:wrap}
    .testi .item{flex:1; min-width:220px; border-radius:12px; padding:18px; background:linear-gradient(180deg,#ffffff,#fbfdff); box-shadow:var(--shadow)}

    /* FOOTER */
    footer{margin-top:24px; padding:20px; text-align:center; color:white; background:linear-gradient(90deg,var(--primary), #07579b); border-radius:12px}

    /* FAB whatsapp */
    .fab{position:fixed; right:18px; bottom:18px; width:64px; height:64px; border-radius:999px; background:var(--success); display:grid; place-items:center; color:white; box-shadow:0 10px 30px rgba(31,167,79,0.28); z-index:999}

    /* tiny responsive tweaks */
    @media(max-width:420px){ .brand h1{font-size:0.92rem} .hero-card{padding:20px} }
  </style>
</head>
<body>

  <nav class="navbar">
    <div class="nav-inner">
      <a class="brand" href="#">
        <div class="logo">S</div>
        <div>
          <h1>Surya Teknisi</h1>
          <div style="font-size:0.78rem;color:rgba(255,255,255,0.88)">Service HP — Garansi 90 hari</div>
        </div>
      </a>

      <div class="nav-links" id="navLinks">
        <a href="#layanan">Layanan</a>
        <a href="#harga">Harga</a>
        <a href="#proses">Proses</a>
        <a href="#testimoni">Testimoni</a>
        <a href="#kontak">Kontak</a>
      </div>

      <button class="hamburger" id="hamburger" aria-label="Toggle menu"><i class="fa-solid fa-bars"></i></button>
    </div>
  </nav>

  <main class="container">
    <!-- HERO -->
    <section class="hero" id="home">
      <div class="hero-card" data-aos="fade-up">
        <span class="kicker">Premium Workshop</span>
        <h2 class="hero-title">Solusi Service HP Profesional di Surabaya</h2>
        <p class="lead">Spesialis diagnosa mainboard & mikrosoldering, ganti layar original, perbaikan jalur charging, dan layanan antar-jemput 100% gratis di area Surabaya.</p>

        <div class="hero-cta">
          <a class="btn btn-primary" href="https://wa.me/6285198331549?text=Halo%2C%20saya%20ingin%20reservasi" target="_blank"><i class="fa-brands fa-whatsapp"></i> Reservasi via WhatsApp</a>
          <a class="btn btn-ghost" href="#harga">Lihat Harga</a>
        </div>

        <ul style="margin-top:18px;display:flex;gap:12px;padding:0;list-style:none">
          <li style="font-weight:700;color:var(--primary)"><i class="fa-solid fa-check"></i> Garansi 90 hari</li>
          <li style="font-weight:700;color:var(--primary)"><i class="fa-solid fa-truck-fast"></i> Antar-jemput Surabaya</li>
        </ul>
      </div>

      <aside data-aos="fade-left">
        <div style="background:linear-gradient(180deg, #ffffff, #f0f6ff); padding:20px; border-radius:12px; box-shadow:var(--shadow)">
          <h3 style="margin:0 0 8px">Booking Cepat</h3>
          <p style="margin:0 0 12px;color:var(--muted)">Isi tipe perangkat dan keluhan. Kurir kami akan menghubungi untuk jemput.</p>
          <form id="bookingForm" onsubmit="submitBooking(event)">
            <label for="name" style="display:block;margin-bottom:6px;font-weight:600">Nama</label>
            <input id="name" name="name" required style="width:100%;padding:10px;border-radius:8px;border:1px solid #e6eef9;margin-bottom:8px">
            <label for="device" style="display:block;margin-bottom:6px;font-weight:600">Tipe HP</label>
            <input id="device" name="device" required style="width:100%;padding:10px;border-radius:8px;border:1px solid #e6eef9;margin-bottom:8px">
            <label for="note" style="display:block;margin-bottom:6px;font-weight:600">Keluhan singkat</label>
            <input id="note" name="note" style="width:100%;padding:10px;border-radius:8px;border:1px solid #e6eef9;margin-bottom:12px">
            <button class="btn btn-primary" type="submit" style="width:100%"><i class="fa-solid fa-paper-plane"></i> Kirim via WhatsApp</button>
          </form>
        </div>

        <div style="margin-top:14px;text-align:center;color:var(--muted,font-size:.95rem)">
          <div style="font-weight:700">Kontak Cepat</div>
          <a href="tel:085198331549" style="display:block;margin-top:6px;text-decoration:none;color:var(--primary);font-weight:700">0851 9833 1549</a>
        </div>
      </aside>
    </section>

    <!-- SERVICES -->
    <section class="section" id="layanan" data-aos="fade-up">
      <h2 style="text-align:center;margin-top:0">Layanan Unggulan</h2>
      <p style="text-align:center;color:var(--muted)">Solusi lengkap — dari software ringan hingga mainboard mikrosoldering.</p>

      <div class="grid" style="margin-top:18px">
        <div class="card" onclick="openWhatsAppPrefill('Ganti Layar - Tipe: ')">
          <i class="fa-solid fa-mobile-screen"></i>
          <h3>Ganti Layar / LCD</h3>
          <p>Original & aftermarket. Garansi fungsi setelah pemasangan.</p>
        </div>
        <div class="card" onclick="openWhatsAppPrefill('Servis Mainboard - Tipe: ')">
          <i class="fa-solid fa-microchip"></i>
          <h3>Servis Mainboard & Mikrosoldering</h3>
          <p>Perbaikan IC power, CPU reballing ringan, dan jalur charging.</p>
        </div>
        <div class="card" onclick="openWhatsAppPrefill('Ganti Baterai - Tipe: ')">
          <i class="fa-solid fa-battery-three-quarters"></i>
          <h3>Baterai & Charging</h3>
          <p>Ganti baterai, perbaikan port pengisian, dan kalibrasi baterai.</p>
        </div>
      </div>

    </section>

    <!-- DELIVERY PROMO -->
    <section class="section" id="delivery" data-aos="flip-left" style="background:linear-gradient(90deg,#0b61b7,#07579b); color:white; text-align:center">
      <h2 style="margin-top:0;color:var(--accent)">Jemput & Antar Gratis — Surabaya</h2>
      <p>Proses aman dengan kurir profesional. Cukup pesan, kami jemput dan antar kembali setelah selesai.</p>
      <a class="btn btn-primary" href="https://wa.me/6285198331549?text=Saya%20ingin%20memanfaatkan%20layanan%20antar%20jemput%20gratis%20Surabaya" target="_blank">Jadwalkan Penjemputan</a>
    </section>

    <!-- PRICE -->
    <section class="section" id="harga" data-aos="fade-up">
      <h2 style="text-align:center;margin-top:0">Daftar Harga — Estimasi</h2>
      <div class="tabs" role="tablist" aria-label="Kategori Harga">
        <button class="tab-btn active" data-tab="iphone" onclick="switchTab(event)">iPhone</button>
        <button class="tab-btn" data-tab="android" onclick="switchTab(event)">Android</button>
        <button class="tab-btn" data-tab="ic" onclick="switchTab(event)">Mikrosoldering</button>
      </div>

      <div id="iphone" class="tab-content">
        <table class="price-table"><thead><tr><th>Layanan</th><th>Estimasi</th></tr></thead><tbody>
          <tr><td>Ganti LCD iPhone 15 Pro Max</td><td>Mulai Rp 1.100.000</td></tr>
          <tr><td>Ganti Baterai iPhone 14</td><td>Rp 550.000</td></tr>
        </tbody></table>
      </div>

      <div id="android" class="tab-content" style="display:none">
        <table class="price-table"><thead><tr><th>Layanan</th><th>Estimasi</th></tr></thead><tbody>
          <tr><td>Ganti LCD Samsung S23 Ultra</td><td>Mulai Rp 2.000.000</td></tr>
          <tr><td>Ganti Baterai Xiaomi</td><td>Mulai Rp 200.000</td></tr>
        </tbody></table>
      </div>

      <div id="ic" class="tab-content" style="display:none">
        <table class="price-table"><thead><tr><th>Layanan</th><th>Estimasi</th></tr></thead><tbody>
          <tr><td>Perbaikan IC Power (HP Mati)</td><td>Mulai Rp 600.000</td></tr>
          <tr><td>Perbaikan Jalur Charging</td><td>Mulai Rp 350.000</td></tr>
        </tbody></table>
      </div>

      <p style="text-align:center;color:var(--muted);margin-top:14px">*Harga estimasi. Hubungi kami untuk diagnosa final & penawaran terbaik.</p>
    </section>

    <!-- PROCESS -->
    <section class="section" id="proses" data-aos="fade-up">
      <h2 style="text-align:center;margin-top:0">Proses Kerja</h2>
      <div class="process" style="margin-top:18px">
        <div class="step"><div class="dot"><i class="fa-solid fa-calendar-check"></i></div><strong>Jemput</strong><div style="color:var(--muted)">Kurir jemput perangkat</div></div>
        <div class="step"><div class="dot"><i class="fa-solid fa-microscope"></i></div><strong>Diagnosa</strong><div style="color:var(--muted)">Analisa hardware & software</div></div>
        <div class="step"><div class="dot"><i class="fa-solid fa-wrench"></i></div><strong>Perbaikan</strong><div style="color:var(--muted)">Eksekusi teknisi berpengalaman</div></div>
        <div class="step"><div class="dot"><i class="fa-solid fa-shield-halved"></i></div><strong>QC & Antar</strong><div style="color:var(--muted)">Testing & pengantaran kembali</div></div>
      </div>
    </section>

    <!-- TESTIMONIAL -->
    <section class="section" id="testimoni" data-aos="fade-up">
      <h2 style="text-align:center;margin-top:0">Testimoni Pelanggan</h2>
      <div class="testi" style="margin-top:16px">
        <div class="item">"Service cepat, hasil rapi, dan garansi jelas." <div style="text-align:right;margin-top:8px;font-weight:700;color:var(--primary)">— Bima S.</div></div>
        <div class="item">"HP kena air, akhirnya nyala lagi. Data aman." <div style="text-align:right;margin-top:8px;font-weight:700;color:var(--primary)">— Risa M.</div></div>
        <div class="item">"Pelayanan ramah dan harga transparan." <div style="text-align:right;margin-top:8px;font-weight:700;color:var(--primary)">— Agus P.</div></div>
      </div>
    </section>

    <!-- KNOWLEDGE -->
    <section class="section" data-aos="fade-up">
      <h2 style="text-align:center;margin-top:0">Pengetahuan Singkat</h2>
      <div style="display:flex;gap:12px;flex-wrap:wrap;justify-content:center;margin-top:18px">
        <div style="flex:1;min-width:260px;background:var(--card);padding:16px;border-radius:10px;box-shadow:var(--shadow)"><h4>Kerusakan Software</h4><p style="color:var(--muted)">Bootloop, virus, dan masalah software biasanya dapat diperbaiki tanpa ganti sparepart.</p></div>
        <div style="flex:1;min-width:260px;background:var(--card);padding:16px;border-radius:10px;box-shadow:var(--shadow)"><h4>Kerusakan Hardware</h4><p style="color:var(--muted)">Melibatkan penggantian komponen atau perbaikan mainboard.</p></div>
      </div>
    </section>

    <!-- CONTACT / FOOTER -->
    <footer id="kontak">
      <div style="padding:18px">
        <div style="font-weight:800;font-size:1.05rem">Surya Teknisi — Service HP Surabaya</div>
        <div style="margin-top:6px">Tel: <a href="tel:085198331549" style="color:rgba(255,255,255,0.95);text-decoration:none">0851 9833 1549</a> • Garansi 90 hari</div>
        <div style="margin-top:10px;color:rgba(255,255,255,0.9)">© Surya Teknisi 2025 • Keahlian & Kejujuran</div>
      </div>
    </footer>

  </main>

  <a class="fab" href="https://wa.me/6285198331549" target="_blank" aria-label="Chat WhatsApp"><i class="fa-brands fa-whatsapp"></i></a>

  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init({duration:700,once:true});

    // Hamburger toggle
    const ham = document.getElementById('hamburger');
    const navLinks = document.getElementById('navLinks');
    ham.addEventListener('click', ()=>{ if(navLinks.style.display==='flex'){navLinks.style.display='none'}else{navLinks.style.display='flex'; navLinks.style.flexDirection='column'; navLinks.style.background='linear-gradient(180deg, rgba(11,97,183,0.96), rgba(3,64,130,0.96))'; navLinks.style.position='absolute'; navLinks.style.right='18px'; navLinks.style.top='64px'; navLinks.style.padding='12px'; navLinks.style.borderRadius='10px'}})

    // Tabs
    function switchTab(e){
      const btns = document.querySelectorAll('.tab-btn'); btns.forEach(b=>b.classList.remove('active'));
      e.currentTarget.classList.add('active');
      const target = e.currentTarget.getAttribute('data-tab');
      document.querySelectorAll('.tab-content').forEach(c=>c.style.display='none');
      document.getElementById(target).style.display='block';
    }

    // Booking form -> WA message
    function submitBooking(e){
      e.preventDefault();
      const name = encodeURIComponent(document.getElementById('name').value || '');
      const device = encodeURIComponent(document.getElementById('device').value || '');
      const note = encodeURIComponent(document.getElementById('note').value || '');
      const wa = `https://wa.me/6285198331549?text=Reservasi%20Booking%20%0AName:%20${name}%0ATipe:%20${device}%0AKeluhan:%20${note}`;
      window.open(wa,'_blank');
    }

    // Card click prefill
    function openWhatsAppPrefill(prefill){
      const msg = encodeURIComponent(prefill);
      window.open(`https://wa.me/6285198331549?text=${msg}`,'_blank');
    }

    // Improve mobile viewport render for GitHub Pages: remove background-attachment usage and make images fluid
  </script>
</body>
</html>
