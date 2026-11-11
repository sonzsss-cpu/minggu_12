[index.html](https://github.com/user-attachments/files/34685128/index.html)
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="theme-color" content="#090b2b" />
  <title>JUMANJI — Jelajah Universitas MAN 1 Jember</title>
    <link rel="stylesheet" href="style.css" />

</head>
<body>
  <nav class="nav">
    <div class="container nav-inner">
      <a class="brand" href="#home">✦ JUMANJI</a>
      <button class="menu-toggle" id="menuToggle" aria-label="Buka menu">☰</button>
      <div class="nav-links" id="navLinks">
        <a href="#tentang">Tentang</a>
        <a href="#keseruan">Keseruan</a>
        <a href="#hitung-mundur">Hitung Mundur</a>
        <a href="#lokasi">Lokasi</a>
      </div>
    </div>
  </nav>

  <header class="hero" id="home">
    <div class="container hero-grid">
      <div>
        <div class="eyebrow">A journey beyond the stars • MAN 1 Jember</div>
        <h1>JU<span>MANJI</span></h1>
        <h2>Jelajah Universitas MAN 1 Jember</h2>
        <p>Satu hari, banyak pilihan masa depan. Mari jelajahi dunia perkuliahan, temukan kampus impian, dan mulai petualanganmu menuju masa depan!</p>
        <div class="hero-actions">
          <a class="btn btn-primary" href="#tentang">Jelajahi Acara ✦</a>
          <a class="btn btn-outline" href="#lokasi">Lihat Lokasi</a>
        </div>
      </div>
      <div class="mascot-wrap" aria-label="Maskot rusa JUMANJI">
        <div class="planet"></div>
        <span class="floating-star star-one">✦</span>
        <span class="floating-star star-two">✧</span>
        <span class="floating-star star-three">✦</span>
        <img class="mascot" src="maskot-rusa.png" alt="Maskot rusa JUMANJI mengenakan pakaian astronaut" />
      </div>
    </div>
  </header>

  <div class="container event-strip">
    <div class="event-info">
      <div class="info-item"><small>Tanggal</small><strong>16 Januari 2027</strong></div>
      <div class="info-item"><small>Tempat</small><strong>MAN 1 Jember</strong></div>
      <div class="info-item"><small>Acara</small><strong>Campus Expo</strong></div>
    </div>
  </div>

  <main>
    <section class="content-section" id="tentang">
      <div class="container">
        <div class="section-heading">
          <div class="eyebrow">Welcome, explorers</div>
          <h2 class="section-title">Apa itu JUMANJI?</h2>
          <p>Gerbang awal untuk mengenal lebih dekat dunia universitas dan kehidupan kampus.</p>
        </div>
        <div class="about-card">
          <p><strong>JUMANJI (Jelajah Universitas MAN 1 Jember)</strong> merupakan kegiatan expo kampus yang mempertemukan siswa dengan informasi seputar perguruan tinggi. Temukan wawasan tentang pilihan program studi, lingkungan perkuliahan, jalur masuk, serta pengalaman mahasiswa secara langsung.</p>
          <p>Siapkan rasa ingin tahumu, karena petualangan menentukan masa depan dimulai dari sini!</p>
        </div>
      </div>
    </section>

    <section class="content-section" id="keseruan">
      <div class="container">
        <div class="section-heading">
          <div class="eyebrow">Explore the universe</div>
          <h2 class="section-title">Jelajahi Kemungkinan</h2>
          <p>Buka wawasanmu dan temukan inspirasi dari berbagai pilihan pendidikan tinggi.</p>
        </div>
        <div class="feature-grid">
          <article class="feature">
            <div class="emoji">🪐</div>
            <h3>Kenali Kampus</h3>
            <p>Dapatkan informasi dan gambaran tentang berbagai perguruan tinggi.</p>
          </article>
          <article class="feature">
            <div class="emoji">🚀</div>
            <h3>Temukan Jurusan</h3>
            <p>Jelajahi bidang studi dan peluang yang sesuai dengan minatmu.</p>
          </article>
          <article class="feature">
            <div class="emoji">🌟</div>
            <h3>Rancang Masa Depan</h3>
            <p>Bangun motivasi dan persiapkan langkah menuju kampus impian.</p>
          </article>
        </div>
      </div>
    </section>

    <section class="content-section" id="hitung-mundur">
      <div class="container">
        <div class="section-heading">
          <div class="eyebrow">The countdown begins</div>
          <h2 class="section-title">Menuju JUMANJI</h2>
          <p>Tandai kalender dan bersiaplah untuk memulai petualanganmu.</p>
        </div>
        <div class="countdown" aria-label="Hitung mundur menuju acara">
          <div class="count-box"><strong id="days">--</strong><span>Hari</span></div>
          <div class="count-box"><strong id="hours">--</strong><span>Jam</span></div>
          <div class="count-box"><strong id="minutes">--</strong><span>Menit</span></div>
          <div class="count-box"><strong id="seconds">--</strong><span>Detik</span></div>
        </div>
      </div>
    </section>

    <section class="content-section" id="lokasi">
      <div class="container">
        <div class="section-heading">
          <div class="eyebrow">Your destination</div>
          <h2 class="section-title">Temui Kami di Sini</h2>
        </div>
        <div class="location-card">
          <div class="emoji">📍</div>
          <h3>MAN 1 Jember</h3>
          <p>16 Januari 2027<br>Datang dan jadi bagian dari perjalanan JUMANJI!</p>
          <!-- Tambahkan tautan Google Maps resmi sekolah di sini jika sudah tersedia. -->
          <a class="btn btn-outline" href="https://www.google.com/maps/search/?api=1&query=MAN+1+Jember" target="_blank" rel="noopener">Buka Peta</a>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">
      <strong>JUMANJI 2027</strong>
      <p>Jelajah Universitas MAN 1 Jember · Explore your future among the stars.</p>
    </div>
  </footer>

  <script>
    // Tanggal acara: 16 Januari 2027. Jam default 08.00 WIB; ubah jika jadwal resmi berbeda.
    const eventDate = new Date('2027-01-16T08:00:00+07:00').getTime();

    function updateCountdown() {
      const remaining = eventDate - Date.now();
      const ids = ['days', 'hours', 'minutes', 'seconds'];
      if (remaining <= 0) {
        ids.forEach(id => document.getElementById(id).textContent = '0');
        return;
      }
      const values = [
        Math.floor(remaining / 86400000),
        Math.floor((remaining % 86400000) / 3600000),
        Math.floor((remaining % 3600000) / 60000),
        Math.floor((remaining % 60000) / 1000)
      ];
      ids.forEach((id, index) => {
        document.getElementById(id).textContent = String(values[index]).padStart(2, '0');
      });
    }
    updateCountdown();
    setInterval(updateCountdown, 1000);

    document.getElementById('menuToggle').addEventListener('click', () => {
      document.getElementById('navLinks').classList.toggle('open');
    });
    document.querySelectorAll('.nav-links a').forEach(link => {
      link.addEventListener('click', () => document.getElementById('navLinks').classList.remove('open'));
    });
  </script>
</body>
</html>
