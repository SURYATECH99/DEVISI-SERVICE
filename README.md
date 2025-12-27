<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>SURYATECH — Premium Service HP (Soft Silver)</title>
  <meta name="description" content="SURYATECH - Service HP premium Surabaya. Mikrosoldering, ganti LCD & battery. Free antar jemput Surabaya.">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    :root{
      --bg:#F5F7FA;
      --panel:#ffffff;
      --nav:#315776;
      --gold:#C4A454;
      --accent:#4B8CBF;
      --muted:#6B7785;
      --text:#122028;
      --radius:12px;
      --shadow: 0 10px 30px rgba(16,24,40,0.06);
      --glass: rgba(255,255,255,0.6);
      --maxw:1120px;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:'Poppins',system-ui,Arial;background:var(--bg);color:var(--text);-webkit-font-smoothing:antialiased}
    a{color:inherit}
    .container{max-width:var(--maxw);margin:26px auto;padding:0 18px}

    /* NAVBAR */
    .navbar{position:sticky;top:0;z-index:120;background:linear-gradient(90deg,var(--nav), #274f66);color:white;padding:12px 0;box-shadow:var(--shadow)}
    .nav-inner{max-width:var(--maxw);margin:0 auto;display:flex;align-items:center;gap:16px;padding:0 18px}
    .brand{display:flex;gap:12px;align-items:center;text-decoration:none}
    .logo-wrap{width:52px;height:52px;border-radius:10px;background:linear-gradient(135deg,var(--gold),#b8860b);display:grid;place-items:center;color:#082033;font-weight:900;font-size:20px}
    .brand h1{margin:0;font-size:1.05rem;color:white}
    .brand small{display:block;color:rgba(255,255,255,0.9);font-size:0.78rem;margin-top:2px}
    nav#mainNav{margin-left:auto;display:flex;gap:10px;align-items:center}
    nav#mainNav a{color:rgba(255,255,255,0.95);text-decoration:none;padding:8px 12px;border-radius:10px;font-weight:600}
    nav#mainNav a:hover{background:rgba(255,255,255,0.04)}
    .hamburger{display:none;background:transparent;border:0;color:white;font-size:1.15rem}
    @media(max-width:900px){ nav#mainNav{display:none} .hamburger{display:block} }

    /* HERO */
    .hero{position:relative;border-radius:16px;overflow:hidden;margin-top:18px;padding:28px;background:linear-gradient(180deg,#ffffff,#fbfdff);box-shadow:var(--shadow)}
    canvas#particles{position:absolute;inset:0;z-index:0;pointer-events:none}
    .hero-inner{position:relative;z-index:2;display:grid;grid-template-columns:1fr 420px;gap:20px;align-items:center}
    @media(max-width:900px){ .hero-inner{grid-template-columns:1fr} }
    .hero-kicker{display:inline-block;background:rgba(196,164,84,0.12);color:var(--gold);padding:6px 12px;border-radius:999px;font-weight:700}
    .hero-title{font-size:1.9rem;margin:12px 0;color:var(--text);line-height:1.05}
    .hero-lead{color:var(--muted);max-width:60ch}
    .cta-group{margin-top:16px;display:flex;gap:10px;flex-wrap:wrap}
    .btn{display:inline-flex;align-items:center;gap:10px;padding:10px 14px;border-radius:10px;text-decoration:none;font-weight:800}
    .btn-gold{background:linear-gradient(90deg,var(--gold),#b8860b);color:#071428}
    .btn-outline{border:1px solid rgba(16,24,40,0.06);color:var(--text);background:transparent}

    /* HERO CARD (booking) */
    .hero-card{background:linear-gradient(180deg,#fff,#fbfdff);border-radius:12px;padding:16px;border:1px solid rgba(16,24,40,0.03);box-shadow:var(--shadow)}
    .hero-card input, .hero-card select, .hero-card textarea{width:100%;padding:10px;border-radius:10px;border:1px solid #eef4fb;margin:8px 0;font-family:inherit}
    .small-muted{font-size:0.92rem;color:var(--muted)}

    /* GRID SERVICES */
    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-top:18px}
    @media(max-width:1024px){ .grid{grid-template-columns:repeat(2,1fr)} }
    @media(max-width:640px){ .grid{grid-template-columns:1fr} }
    .card{background:var(--panel);border-radius:12px;padding:16px;box-shadow:var(--shadow);text-align:center;cursor:pointer;transition:transform .3s,box-shadow .3s}
    .card:hover{transform:translateY(-8px);box-shadow:0 18px 40px rgba(16,24,40,0.08)}
    .card i{font-size:28px;color:var(--accent);margin-bottom:10px}

    /* PROMO */
    .promo{margin-top:18px;padding:18px;border-radius:12px;background:linear-gradient(90deg,var(--gold), #f0c86b);color:#071428;text-align:center;box-shadow:var(--shadow)}

    /* PRICE TABLE */
    .price-section{margin-top:20px}
    .price-title{color:var(--gold);font-size:1.2rem;text-align:center;margin-bottom:10px}
    .table-wrap{overflow:auto;padding:12px;border-radius:12px;background:linear-gradient(180deg, rgba(255,255,255,0.95), rgba(255,255,255,0.98));border:1px solid rgba(16,24,40,0.03)}
    table.price{width:100%;border-collapse:collapse;background:#fff;color:var(--text);border-radius:8px;overflow:hidden}
    table.price thead th{background:linear-gradient(90deg,var(--gold),#b8860b);color:#071428;padding:12px;text-transform:uppercase;font-weight:700}
    table.price td{padding:10px 12px;border-bottom:1px solid rgba(16,24,40,0.04);color:var(--text);font-weight:600}
    table.price tr:hover td{background:rgba(196,155,45,0.03);transition:0.2s}

    /* TRACKING */
    .tracking{margin-top:18px;display:grid;grid-template-columns:1fr 420px;gap:12px}
    @media(max-width:900px){ .tracking{grid-template-columns:1fr} }
    .track-card{background:var(--panel);padding:16px;border-radius:12px;border:1px solid rgba(16,24,40,0.03);box-shadow:var(--shadow)}
    .track-card h3{margin:0;color:var(--gold)}
    .track-input{width:100%;padding:10px;border-radius:10px;border:1px solid #eef4fb;margin-top:10px}
    .track-btn{margin-top:10px;padding:10px 12px;border-radius:10px;background:linear-gradient(90deg,var(--gold),#b8860b);border:none;color:#071428;font-weight:800;cursor:pointer}

    .timeline{margin-top:12px;display:flex;align-items:center;gap:12px}
    .step-bubble{width:56px;height:56px;border-radius:12px;background:rgba(16,24,40,0.04);display:grid;place-items:center;color:var(--muted);font-weight:700;transition:transform .35s,box-shadow .35s}
    .step-bubble.active{background:linear-gradient(180deg,var(--gold),#b8860b);color:#071428;transform:translateY(-8px);box-shadow:0 10px 30px rgba(198,155,45,0.12)}
    .progress-bar{flex:1;height:12px;background:rgba(16,24,40,0.04);border-radius:10px;overflow:hidden}
    .progress-fill{height:100%;background:linear-gradient(90deg,var(--gold),#ffd88a);width:0%;transition:width 900ms cubic-bezier(.2,.8,.2,1)}

    /* PROCESS */
    .process-steps{display:grid;grid-template-columns:repeat(auto-fit,minmax(160px,1fr));gap:12px;margin-top:12px}
    .proc{background:var(--panel);padding:12px;border-radius:12px;border:1px solid rgba(16,24,40,0.03);text-align:center;box-shadow:var(--shadow)}
    .proc h4{color:var(--gold);margin:8px 0 6px}
    .proc p{color:var(--muted);font-size:0.95rem}

    /* ADMIN modal */
    .modal{position:fixed;inset:0;display:none;align-items:center;justify-content:center;background:rgba(6,10,15,0.4);z-index:3000}
    .modal.open{display:flex}
    .modal-card{width:420px;background:var(--panel);padding:16px;border-radius:12px;box-shadow:var(--shadow)}
    .btn-ghost{background:transparent;border:1px solid rgba(16,24,40,0.06);padding:10px 12px;border-radius:10px}

    /* Floating WA */
    .wa-float{position:fixed;width:70px;height:70px;bottom:22px;right:22px;background:#25D366;border-radius:50%;display:grid;place-items:center;box-shadow:0 12px 30px rgba(23,201,100,0.24);z-index:2200;cursor:pointer;transition:transform .25s}
    .wa-float:hover{transform:scale(1.12) rotate(6deg)}
    .wa-icon{width:42px}

    /* subtle 3D hover for important buttons */
    .btn-3d{display:inline-block;padding:12px 18px;border-radius:12px;background:linear-gradient(180deg, #fff, #f6f8fa);box-shadow:0 8px 20px rgba(16,24,40,0.06);transition:transform .25s}
    .btn-3d:hover{transform:translateY(-6px)}

    /* small */
    .muted{color:var(--muted)}
    input,select,textarea,button{font-family:inherit}
  </style>
</head>
<body>
  <div class="container">
    <!-- NAVBAR -->
    <header class="navbar" role="banner">
      <div class="nav-inner">
        <a class="brand" href="#">
          <div class="logo-wrap">S</div>
          <div>
            <h1>SURYATECH</h1>
            <small>Premium Board Repair & Service HP</small>
          </div>
        </a>

        <nav id="mainNav" role="navigation" aria-label="Main navigation">
          <a href="#layanan">Layanan</a>
          <a href="#harga">Harga</a>
          <a href="#tracking">Tracking</a>
          <a href="#proses">Proses</a>
          <a href="#kontak">Kontak</a>
        </nav>

        <button class="hamburger" id="hamburger" aria-label="Toggle menu"><i class="fa-solid fa-bars"></i></button>
      </div>
    </header>

    <!-- HERO -->
    <section class="hero" aria-label="Hero">
      <canvas id="particles" aria-hidden="true"></canvas>

      <div class="hero-inner">
        <div>
          <span class="hero-kicker">Premium Workshop</span>
          <h2 class="hero-title">SURYATECH — Solusi Service HP Profesional di Surabaya</h2>
          <p class="hero-lead">Spesialis diagnosa mainboard & mikrosoldering, ganti layar original & battery, perbaikan jalur charging. Antar-jemput gratis area Surabaya.</p>

          <div class="cta-group">
            <a class="btn btn-gold" href="#booking" id="bookNow"><i class="fa-brands fa-whatsapp"></i> Booking via WhatsApp</a>
            <a class="btn btn-outline" href="#harga">Lihat Price List</a>
          </div>

          <ul style="margin-top:14px;display:flex;gap:12px;padding:0;list-style:none">
            <li style="font-weight:700;color:var(--accent)"><i class="fa-solid fa-check"></i> Garansi 90 hari</li>
            <li style="font-weight:700;color:var(--accent)"><i class="fa-solid fa-truck-fast"></i> Free Antar-Jemput (Surabaya)</li>
          </ul>
        </div>

        <aside>
          <div class="hero-card" id="booking">
            <strong>Booking Cepat</strong>
            <p class="small-muted" style="margin:6px 0 10px">Isi form, kurir jemput. Form akan membuka WhatsApp dengan isi otomatis.</p>

            <form id="bookingForm" onsubmit="submitBooking(event)" aria-label="Form Booking Cepat">
              <input id="name" name="name" placeholder="Nama lengkap" required />
              <input id="phone" name="phone" placeholder="No. HP (WhatsApp)" required />
              <input id="device" name="device" placeholder="Tipe HP (contoh: iPhone 11 Pro)" required />
              <textarea id="note" name="note" placeholder="Keluhan singkat (opsional)" rows="2"></textarea>
              <button class="btn btn-gold" type="submit" style="width:100%;margin-top:8px"><i class="fa-solid fa-paper-plane"></i> Kirim via WhatsApp</button>
            </form>

            <div style="margin-top:12px;display:flex;gap:8px;align-items:center;justify-content:space-between">
              <div><strong>Kontak:</strong> <a href="tel:085233400200" style="color:var(--nav);font-weight:700">0852 3340 0200</a></div>
              <div><button class="btn-ghost btn-3d" onclick="openAdminModal()">Admin Login</button></div>
            </div>
          </div>
        </aside>
      </div>
    </section>

    <!-- SERVICES -->
    <section id="layanan" style="margin-top:18px;">
      <h2 style="text-align:center;margin:0 0 8px">Layanan Unggulan</h2>
      <p class="muted" style="text-align:center;margin-top:6px">Dari software ringan hingga mainboard mikrosoldering tingkat lanjut.</p>

      <div class="grid">
        <div class="card" onclick="prefill('Ganti Layar - Tipe: ')">
          <i class="fa-solid fa-mobile-screen"></i>
          <h3>Ganti Layar / LCD</h3>
          <p class="muted">Original & aftermarket. Garansi pemasangan.</p>
        </div>
        <div class="card" onclick="prefill('Servis Mainboard - Tipe: ')">
          <i class="fa-solid fa-microchip"></i>
          <h3>Servis Mainboard</h3>
          <p class="muted">IC Power, reballing ringan, jalur charging.</p>
        </div>
        <div class="card" onclick="prefill('Ganti Baterai - Tipe: ')">
          <i class="fa-solid fa-battery-half"></i>
          <h3>Baterai & Charging</h3>
          <p class="muted">Ganti baterai, port charging, kalibrasi.</p>
        </div>
      </div>
    </section>

    <!-- DELIVERY PROMO -->
    <section id="delivery" class="promo" data-aos="fade-left">
      <h3 style="margin:0;color:#071428">Jemput & Antar Gratis — Surabaya</h3>
      <p style="margin-top:8px;color:#071428">Kurir profesional, pengemasan aman, tracking service tersedia.</p>
      <a class="btn btn-gold" href="#tracking" style="margin-top:12px;display:inline-block">CEK STATUS PERBAIKAN</a>
    </section>

    <!-- PRICE -->
    <section id="harga" class="price-section" data-aos="fade-up">
      <div class="price-title">Price List iPhone (LCD & Battery) — Gold Premium</div>
      <div class="table-wrap" style="margin-top:12px;">
        <table class="price" role="table" aria-label="Price list iPhone">
          <thead>
            <tr><th>Model</th><th>Harga LCD</th><th>Harga Battery</th></tr>
          </thead>
          <tbody>
            <tr><td>iPhone 6 / 6 Plus</td><td>Rp 250.000</td><td>Rp 150.000</td></tr>
            <tr><td>iPhone 6s / 6s Plus</td><td>Rp 300.000</td><td>Rp 170.000</td></tr>
            <tr><td>iPhone 7 / 7 Plus</td><td>Rp 300.000</td><td>Rp 180.000</td></tr>
            <tr><td>iPhone 8 / 8 Plus</td><td>Rp 300.000</td><td>Rp 200.000</td></tr>
            <tr><td>iPhone X</td><td>Rp 450.000</td><td>Rp 250.000</td></tr>
            <tr><td>iPhone XR</td><td>Rp 400.000</td><td>Rp 300.000</td></tr>
            <tr><td>iPhone XS / XS Max</td><td>Rp 600.000</td><td>Rp 300.000</td></tr>
            <tr><td>iPhone 11</td><td>Rp 400.000</td><td>Rp 350.000</td></tr>
            <tr><td>iPhone 11 Pro / Pro Max</td><td>Rp 650.000</td><td>Rp 400.000</td></tr>
            <tr><td>iPhone 12 / 12 Mini</td><td>Rp 500.000</td><td>Rp 450.000</td></tr>
            <tr><td>iPhone 12 Pro / Pro Max</td><td>Rp 800.000</td><td>Rp 500.000</td></tr>
            <tr><td>iPhone 13 / 13 Mini</td><td>Rp 800.000</td><td>Rp 550.000</td></tr>
            <tr><td>iPhone 13 Pro / Pro Max</td><td>Rp 1.000.000</td><td>Rp 600.000</td></tr>
            <tr><td>iPhone 14 / 14 Plus</td><td>Rp 1.000.000</td><td>Rp 650.000</td></tr>
            <tr><td>iPhone 14 Pro / Pro Max</td><td>Rp 1.400.000</td><td>Rp 750.000</td></tr>
            <tr><td>iPhone 15 / 15 Plus</td><td>Rp 1.500.000</td><td>Rp 800.000</td></tr>
            <tr><td>iPhone 15 Pro / Pro Max</td><td>Rp 2.200.000</td><td>Rp 900.000</td></tr>
            <tr><td>iPhone 16 / 16 Plus</td><td>Rp 4.000.000</td><td>Rp 1.000.000</td></tr>
            <tr><td>iPhone 16 Pro / Pro Max</td><td>Rp 4.500.000</td><td>Rp 1.200.000</td></tr>
          </tbody>
        </table>
      </div>
     dikarena kan banyak kualitas yang tersedia, Estimasi harga — hubungi kami untuk konfirmasi final. Gratis antar jemput area Surabaya
    </section>

    <!-- TRACKING -->
    <section id="tracking" class="tracking" data-aos="fade-up">
      <div class="track-card">
        <h3>Cek Status Perbaikan</h3>
        <p class="muted">Masukkan Kode Servis yang kamu dapat (contoh: ST001)</p>
        <input id="trackInput" class="track-input" placeholder="Contoh: ST001" aria-label="Input kode servis">
        <button class="track-btn" onclick="checkStatus()">Cek Status</button>

        <div class="timeline" aria-hidden="false">
          <div id="bubble1" class="step-bubble">1</div>
          <div class="progress-bar" role="progressbar" aria-valuemin="0" aria-valuemax="100">
            <div id="fill" class="progress-fill" style="width:0%"></div>
          </div>
          <div id="bubble4" class="step-bubble">4</div>
        </div>

        <div id="statusText" style="margin-top:12px;color:var(--muted)">Masukkan kode servis untuk melihat status.</div>
      </div>

      <div class="track-card">
        <h3>Detail Servis</h3>
        <div id="detailBox" style="color:var(--muted);white-space:pre-line">Masukkan kode servis untuk melihat detail pengerjaan, teknisi, dan catatan.</div>

        <hr style="margin:12px 0;border:none;border-top:1px solid rgba(16,24,40,0.04)">

        <div style="font-size:13px;color:var(--muted)">
          <strong>Admin:</strong> Tekan tombol "Admin Login" lalu update tracking. Data disimpan di browser (LocalStorage). Untuk versi produksi, gunakan Firebase (opsional).
        </div>
      </div>
    </section>

    <!-- PROCESS -->
    <section id="proses" class="process-section" data-aos="fade-up">
      <h3 style="text-align:center;color:var(--gold);margin-bottom:12px">Proses Kerja SURYATECH</h3>
      <div class="process-steps">
        <div class="proc">
          <div style="font-size:22px;color:var(--gold)">1</div>
          <h4>Pemesanan & Penjemputan</h4>
          <p>Pelanggan pesan, kurir jemput perangkat (Surabaya — gratis).</p>
        </div>
        <div class="proc">
          <div style="font-size:22px;color:var(--gold)">2</div>
          <h4>Diagnosa Lengkap</h4>
          <p>Analisa board-level & software, dokumentasi, dan estimasi biaya.</p>
        </div>
        <div class="proc">
          <div style="font-size:22px;color:var(--gold)">3</div>
          <h4>Perbaikan & Penggantian</h4>
          <p>Mikrosoldering, reballing, atau penggantian sparepart original.</p>
        </div>
        <div class="proc">
          <div style="font-size:22px;color:var(--gold)">4</div>
          <h4>QC & Pengantaran</h4>
          <p>Quality check, foto before/after, lalu diantar kembali ke pelanggan.</p>
        </div>
      </div>
    </section>

    <!-- FOOTER -->
    <footer id="kontak" style="margin-top:26px;padding:18px;border-radius:12px;background:linear-gradient(90deg,var(--nav), #274f66);color:white;text-align:center">
      <div style="font-weight:800;color:var(--gold)">SURYATECH — Service HP Surabaya</div>
      <div style="margin-top:6px;color:rgba(255,255,255,0.95)">Tel: <a href="tel:085198331549" style="color:rgba(255,255,255,0.95);text-decoration:none">0851 9833 1549</a> • Garansi 90 hari</div>
      <div style="margin-top:8px;color:rgba(255,255,255,0.9)">© SURYATECH 2025 • Keahlian & Kejujuran</div>
    </footer>
  </div>

  <!-- Admin Modal -->
  <div id="adminModal" class="modal" role="dialog" aria-modal="true" aria-labelledby="adminTitle">
    <div class="modal-card">
      <h3 id="adminTitle">Admin Login</h3>
      <div id="adminArea">
        <label style="display:block;margin-top:8px">Password</label>
        <input id="adminPass" type="password" style="width:100%;padding:8px;border-radius:8px;border:1px solid #eef4fb" />
        <div style="margin-top:10px;display:flex;gap:8px">
          <button class="btn btn-gold" onclick="adminLogin()">Login</button>
          <button class="btn btn-outline" onclick="closeAdminModal()">Batal</button>
        </div>
        <hr style="margin:12px 0;border:none;border-top:1px solid rgba(16,24,40,0.04)">
        <div style="font-size:13px;color:var(--muted)">Admin dapat tambah/update kode servis di sini.</div>
      </div>

      <div id="adminPanel" style="display:none;margin-top:12px">
        <h4>Update Tracking</h4>
        <label style="display:block;margin-top:8px">Kode Servis</label>
        <input id="adminCode" placeholder="Contoh: ST001" style="width:100%;padding:8px;border-radius:8px;border:1px solid #eef4fb" />
        <label style="display:block;margin-top:8px">Status (singkat)</label>
        <input id="adminStatus" placeholder="Contoh: Diagnosa" style="width:100%;padding:8px;border-radius:8px;border:1px solid #eef4fb" />
        <label style="display:block;margin-top:8px">Step (1..4)</label>
        <select id="adminStep" style="width:100%;padding:8px;border-radius:8px;border:1px solid #eef4fb">
          <option value="1">1 — Diterima</option>
          <option value="1.5">1.5 — Dijemput</option>
          <option value="2">2 — Diagnosa</option>
          <option value="2.6">2.6 — Menunggu Sparepart</option>
          <option value="3">3 — Perbaikan</option>
          <option value="3.7">3.7 — QC</option>
          <option value="4">4 — Selesai</option>
        </select>
        <label style="display:block;margin-top:8px">Detail (opsional)</label>
        <textarea id="adminDetail" style="width:100%;padding:8px;border-radius:8px;border:1px solid #eef4fb" rows="3"></textarea>
        <div style="margin-top:10px;display:flex;gap:8px">
          <button class="btn btn-gold" onclick="saveTracking()">Simpan</button>
          <button class="btn btn-outline" onclick="closeAdminModal()">Selesai</button>
        </div>
        <div style="margin-top:8px;font-size:13px;color:var(--muted)">Data disimpan lokal (LocalStorage). Untuk multi-admin & realtime gunakan Firebase (opsional).</div>
      </div>
    </div>
  </div>

  <!-- Floating WhatsApp -->
  <a class="wa-float" id="waFloat" href="https://wa.me/62085233400200?text=Halo%20SURYATECH,%20saya%20ingin%20booking%20servis" target="_blank" aria-label="Chat WhatsApp">
    <img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" class="wa-icon" alt="WhatsApp" />
  </a>

  <script>
    // ---------------------
    // Basic UI interactions
    // ---------------------
    AOSinitSafe();
    function AOSinitSafe(){
      try{ if(window.AOS) AOS.init({duration:700,once:true}); }catch(e){}
    }

    // Hamburger toggle for mobile
    document.addEventListener('DOMContentLoaded', ()=> {
      const ham = document.getElementById('hamburger'), nav = document.getElementById('mainNav');
      ham && ham.addEventListener('click', ()=> {
        if(nav.style.display === 'flex'){ nav.style.display = 'none'; }
        else { nav.style.display = 'flex'; nav.style.flexDirection = 'column'; nav.style.position='absolute'; nav.style.right='20px'; nav.style.top='64px'; nav.style.background='linear-gradient(180deg, rgba(16,24,40,0.96), rgba(10,20,36,0.96))'; nav.style.padding='12px'; nav.style.borderRadius='10px'; }
      });

      // seed demo DB if needed
      if(!localStorage.getItem('suryatech_tracking')){
        const seed = {
          'ST001': { status:'Diterima', step:1, detail:'Unit diterima & dicatat.' },
          'ST002': { status:'Dijemput Kurir', step:1.5, detail:'Kurir menjemput.' },
          'ST005': { status:'Perbaikan', step:3, detail:'Sedang diperbaiki.' }
        };
        localStorage.setItem('suryatech_tracking', JSON.stringify(seed));
      }

      // quick book button fills small sample (nudge)
      document.getElementById('bookNow').addEventListener('click', ()=>{ document.getElementById('name').focus(); });
    });

    // ---------------------
    // PARTICLES (light)
    // ---------------------
    (function particles(){
      const canvas = document.getElementById('particles');
      if(!canvas) return;
      const ctx = canvas.getContext('2d');
      let DPR = window.devicePixelRatio || 1;
      function fit(){ canvas.width = canvas.offsetWidth * DPR; canvas.height = canvas.offsetHeight * DPR; ctx.setTransform(DPR,0,0,DPR,0,0); }
      window.addEventListener('resize', ()=>{ DPR = window.devicePixelRatio || 1; fit(); });
      fit();
      const particles = [];
      const N = Math.max(12, Math.floor((canvas.offsetWidth * canvas.offsetHeight) / 20000));
      for(let i=0;i<N;i++){
        particles.push({
          x: Math.random()*canvas.offsetWidth,
          y: Math.random()*canvas.offsetHeight,
          r: Math.random()*2.2 + 0.6,
          vx: (Math.random()-0.5)*0.4,
          vy: (Math.random()-0.5)*0.25,
          a: Math.random()*0.6 + 0.08
        });
      }
      function draw(){
        ctx.clearRect(0,0,canvas.width,canvas.height);
        for(const p of particles){
          p.x += p.vx; p.y += p.vy;
          if(p.x < -10) p.x = canvas.offsetWidth + 10;
          if(p.x > canvas.offsetWidth + 10) p.x = -10;
          if(p.y < -10) p.y = canvas.offsetHeight + 10;
          if(p.y > canvas.offsetHeight + 10) p.y = -10;
          ctx.beginPath();
          ctx.fillStyle = 'rgba(75,140,191,' + p.a + ')';
          ctx.arc(p.x, p.y, p.r, 0, Math.PI*2);
          ctx.fill();
        }
        requestAnimationFrame(draw);
      }
      draw();
    })();

    // ---------------------
    // konsultasi -> WhatsApp
    // ---------------------
    function submitBooking(e){
      e.preventDefault();
      const name = encodeURIComponent(document.getElementById('name').value || '');
      const phone = encodeURIComponent(document.getElementById('phone').value || '');
      const device = encodeURIComponent(document.getElementById('device').value || '');
      const note = encodeURIComponent(document.getElementById('note').value || '');
      // Craft message (Indonesian)
      const text = `Reservasi%20SURYATECH%0AName:%20${name}%0AWhatsApp:%20${phone}%0ATipe:%20${device}%0AKeluhan:%20${note}`;
      const waNumber = '62085233400200'; // your number
      window.open(`https://wa.me/${waNumber}?text=${text}`, '_blank');
    }

    // ---------------------
    // Tracking functions (localStorage)
    // ---------------------
    function readDB(){ try{ return JSON.parse(localStorage.getItem('suryatech_tracking') || '{}'); }catch(e){ return {}; } }
    function writeDB(db){ localStorage.setItem('suryatech_tracking', JSON.stringify(db)); }

    function stepToPercent(step){
      const min=1, max=4;
      const pct = Math.round(((step - min)/(max-min))*100);
      return Math.max(0, Math.min(100, pct));
    }

    function setProgress(percent){
      const el = document.getElementById('fill');
      if(el) el.style.width = percent + '%';
    }

    function checkStatus(){
      const code = (document.getElementById('trackInput').value || '').trim().toUpperCase();
      const statusText = document.getElementById('statusText');
      const detailBox = document.getElementById('detailBox');
      const bubble1 = document.getElementById('bubble1');
      const bubble4 = document.getElementById('bubble4');

      if(!code){
        statusText.innerText = 'Masukkan kode servis.';
        detailBox.innerText = 'Contoh: ST001';
        setProgress(0);
        if(bubble1) bubble1.classList.remove('active');
        if(bubble4) bubble4.classList.remove('active');
        return;
      }

      const db = readDB();
      if(db[code]){
        const e = db[code];
        statusText.innerHTML = 'Status: ' + e.status;
        detailBox.innerText = (e.detail || '') + '\\n\\nKode: ' + code;
        const p = stepToPercent(Number(e.step || 1));
        setProgress(p);
        if(bubble1) bubble1.classList.toggle('active', e.step >= 1.5);
        if(bubble4) bubble4.classList.toggle('active', e.step >= 4);
        return;
      }

      statusText.innerText = 'Kode tidak ditemukan. Hubungi CS jika perlu.';
      detailBox.innerText = 'Hub: 0851 9833 1549';
      setProgress(0);
      if(bubble1) bubble1.classList.remove('active');
      if(bubble4) bubble4.classList.remove('active');
    }

    // ---------------------
    // ADMIN modal & actions
    // ---------------------
    const ADMIN_PASS = 'Violencia12'; // change this after deploy
    function openAdminModal(){ document.getElementById('adminModal').classList.add('open'); document.getElementById('adminPass').value=''; document.getElementById('adminPanel').style.display='none'; }
    function closeAdminModal(){ document.getElementById('adminModal').classList.remove('open'); }

    function adminLogin(){
      const p = (document.getElementById('adminPass').value || '');
      if(p === ADMIN_PASS){
        document.getElementById('adminArea').style.display='none';
        document.getElementById('adminPanel').style.display='block';
      } else { alert('Password salah.'); }
    }

    function saveTracking(){
      const code = (document.getElementById('adminCode').value || '').trim().toUpperCase();
      const status = (document.getElementById('adminStatus').value || '').trim();
      const step = (document.getElementById('adminStep').value || '1');
      const detail = (document.getElementById('adminDetail').value || '').trim();
      if(!code || !status){ alert('Kode & status wajib diisi'); return; }
      const db = readDB();
      db[code] = { status: status, step: Number(step), detail: detail };
      writeDB(db);
      alert('Data tersimpan. Kode: ' + code);
      document.getElementById('trackInput').value = code;
      checkStatus();
    }

    // Export/Import DB (admin convenience)
    function exportDB(){ const data = readDB(); const blob = new Blob([JSON.stringify(data, null, 2)], {type:'application/json'}); const url = URL.createObjectURL(blob); const a = document.createElement('a'); a.href = url; a.download = 'suryatech_tracking.json'; a.click(); URL.revokeObjectURL(url); }
    function importDB(file){
      const reader = new FileReader();
      reader.onload = e => { try{ const obj = JSON.parse(e.target.result); writeDB(obj); alert('Import sukses'); } catch(err){ alert('Format file salah'); } };
      reader.readAsText(file);
    }

    // helper: Enter key submits track check
    document.addEventListener('DOMContentLoaded', ()=>{
      const t = document.getElementById('trackInput');
      if(t) t.addEventListener('keyup', (e)=>{ if(e.key === 'Enter') checkStatus(); });
    });

    // Prefill quick
    function prefill(text){
      const d = document.getElementById('device');
      if(d){ d.value = text; d.scrollIntoView({behavior:'smooth', block:'center'}); d.focus(); }
    }

    // OPTIONAL: prompt to change admin password on first load (developer convenience)
    (function maybeWarnChangePassword(){
      try{
        if(!localStorage.getItem('suryatech_warn_pw')){
          console.info('Reminder: ganti ADMIN_PASS in the script to a secure password before production.');
          localStorage.setItem('suryatech_warn_pw','1');
        }
      }catch(e){}
    })();

  </script>
</body>
</html>
