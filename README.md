# sistersbentolandpage
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>SistersBento - Bento Lucu & Lezat</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: #fff6e7;
      color: #4B4B4B;
    }
    header {
      background: #ffc3d2;
      padding: 40px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 2.5em;
      margin: 0;
    }
    header p {
      font-size: 1.2em;
    }
    .btn {
      background: #ffacb6;
      color: white;
      padding: 12px 24px;
      border: none;
      border-radius: 8px;
      font-size: 1em;
      cursor: pointer;
      margin-top: 20px;
      text-decoration: none;
      display: inline-block;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    .btn:hover {
      transform: scale(1.05);
      box-shadow: 0 6px 14px rgba(0,0,0,0.15);
    }
    .btn:active {
       transform: scale(0.95);
      box-shadow: 0 3px 8px rgba(0,0,0,0.2); 
    }
    
    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }
    .menu-item {
      background: #FFC3A0;
      border: 1px solid #eee;
      padding: 20px;
      margin: 10px 0;
      border-radius: 12px;
    }
    .faq-item {
      margin-bottom: 16px;
    }
    footer {
      background: #ffc3d2;
      color: white;
      padding: 10px 20px;
      text-align: center;
    }
    .gallery {
      display: flex;
      gap: 20px;
      justify-content: center;
      flex-wrap: wrap;
      margin-top: 20px;
    }
    .gallery-item {
      background: #FFC3A0;
      border: 1px solid #eee;
      border-radius: 12px;
      padding: 10px;
      width: 180px;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }
    .gallery-item img {
      width: 100%;
      border-radius: 8px;
    }
    .gallery-item:hover {
      transform: scale(1.03);
    }
    header {
  background: #FFDDE1;
  padding: 40px 20px;
  text-align: center;
  position: relative; 
}

.logo-kiri {
  position: absolute;
  top: 16px;
  left: 20px;
  width: 60px;
  height: 60px;
  border-radius: 12px;
  object-fit: cover;
}

.judul-header h1 {
  font-size: 2.5em;
  margin: 0;
}

.judul-header p {
  font-size: 1.2em;
  margin-bottom: 20px;
}

  </style>
</head>
<body> 

  <header>
    <img class="logo-kiri" src="logosistersBento.png.png" alt="Logo SistersBento">
    <div class="judul-header">
    <h1>🍱 SistersBento 🍱</h1>
    <p>💕 Cocok buat bekal, hadiah, atau makan bareng bestie!!</p>
    <a class="btn" href="#order" onclick="document.getElementById('fairySound').play()">Pesan Sekarang</a>
  </header>

  <section>
    <h2>🎀 Dibuat dengan Cinta</h2>
    <p>SistersBento adalah usaha bento lucu dan lezat dari dua sahabat yang hobi masak dan suka hal-hal lucu! Kami menyajikan bento homemade yang nggak cuma enak, tapi juga bikin senyum tiap kali dibuka. SistersBento hadir dari dapur kecil kami untuk bawain senyum lewat makanan rumahan yang imut dan enak 🍓✨</p>
  </section>

  <section>
    <h2>📦 Menu PO Minggu Ini</h2>
    <div class="menu-item"><strong>Bento Cinta Ayam</strong> – Rp.15.000</div>
    <div class="menu-item"><strong>Bento Curry Ceria</strong> – Rp.15.000</div>
    <div class="menu-item"><strong>Bento Ebi Fry</strong> – Rp.18.000</div>
    <a class="btn" href="#order">🛒 Lihat Detail & Pesan</a>
  </section>

  <section>
    <h2>📸 Galeri Menu</h2>
    <div class="gallery">
      <div class="gallery-item"><img src="gambar_1_bento_cinta_ayam.png" alt="Bento Cinta Ayam"></div>
      <div class="gallery-item"><img src="gambar_2_bento_curry_ceria.png" alt="Bento Curry Ceria"></div>
      <div class="gallery-item"><img src="gambar_3_ebi_fry_bento.png" alt="Ebi Fry Bento"></div>
    </div>
    <p>Yuk jadi bagian dari #SistersBentoFans!</p>
    </section>

  <section id="order">
    <h2>📆 Cara Pre-Order</h2>
    <ol>
      <li>Pilih menu favorit kamu</li>
      <li>Isi form pemesanan</li>
      <li>Transfer & konfirmasi</li>
      <li>Bento dikirim atau bisa ambil di tempat kami</li>
    </ol>
    <a class="btn" href="https://wa.me/6285752045792" target="_blank">✅ via WhatsApp</a>
    <a class="btn" href="https://www.instagram.com/sistersbento" target="_blank">🎀 Follow Instagram Kami</a>
    <h3>⏰ Waktu PO tersisa:</h3>
    <p id="countdown" style="font-weight: bold; font-size: 1.5em; color: #FF6F91;"></p>
  </section>

  <section>
    <h2>💬 Testimoni Pelanggan</h2>
    <div class="menu-item"><em>"Lucu banget bento-nya, anakku sukaa! 😍"</em><br>— Mama Intan</div>
    <div class="menu-item"><em>"Rasa enak, tampilan gemoy! worth it banget 🐻"</em><br>— Rizka, mahasiswa</div>
  </section>

  <section>
    <h2>❓ FAQ</h2>
    <div class="faq-item"><strong>Q:</strong> Bisa COD?<br><strong>A:</strong> Saat ini hanya transfer terlebih dahulu.</div>
    <div class="faq-item"><strong>Q:</strong> Bisa request karakter lucu?<br><strong>A:</strong> Bisa dong! Tulis request kamu di form.</div>
    <div class="faq-item"><strong>Q:</strong> Bisa pesan buat ulang tahun?<br><strong>A:</strong> Boleh banget! Ada bento spesial ultah juga 🎂</div>
  </section>

  <footer>
  <p>📱 Hubungi Kami:</p>
  <p>WhatsApp: 0857-5204-5792</p>
  <p>
    <a href="https://instagram.com/SistersBento" target="_blank" style="display: inline-flex; align-items: center; color: white; text-decoration: none;">
      <svg xmlns="http://www.w3.org/2000/svg" height="20" viewBox="0 0 448 512" style="margin-right: 6px; fill: white;">
        <path d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9S160.5 370.9 224.1 370.9 339 319.6 339 255.9 287.7 141 224.1 141zm0 186.6c-39.6 0-71.7-32.1-71.7-71.7s32.1-71.7 71.7-71.7 71.7 32.1 71.7 71.7-32.1 71.7-71.7 71.7zm146.4-194.3c0 14.9-12.1 27-27 27-14.9 0-27-12.1-27-27s12.1-27 27-27 27 12.1 27 27zm76.1 27.2c-.7-15.2-4.1-28.6-12-41.1-7.9-12.5-18.2-22.8-30.7-30.7-12.5-7.9-25.9-11.3-41.1-12C328.1 32 191.9 32 126.7 32c-15.2.7-28.6 4.1-41.1 12-12.5 7.9-22.8 18.2-30.7 30.7-7.9 12.5-11.3 25.9-12 41.1C32 191.9 32 328.1 32 393.3c.7 15.2 4.1 28.6 12 41.1 7.9 12.5 18.2 22.8 30.7 30.7 12.5 7.9 25.9 11.3 41.1 12 65.2.7 201.4.7 266.6 0 15.2-.7 28.6-4.1 41.1-12 12.5-7.9 22.8-18.2 30.7-30.7 7.9-12.5 11.3-25.9 12-41.1.7-65.2.7-201.4 0-266.6zM398.8 388c-1.4 11.6-6.1 21.3-13.7 28.8-7.5 7.5-17.2 12.3-28.8 13.7-20 1.5-81.1 1.5-132.3 1.5s-112.3 0-132.3-1.5c-11.6-1.4-21.3-6.1-28.8-13.7-7.5-7.5-12.3-17.2-13.7-28.8-1.5-20-1.5-81.1-1.5-132.3s0-112.3 1.5-132.3c1.4-11.6 6.1-21.3 13.7-28.8 7.5-7.5 17.2-12.3 28.8-13.7 20-1.5 81.1-1.5 132.3-1.5s112.3 0 132.3 1.5c11.6 1.4 21.3 6.1 28.8 13.7 7.5 7.5 12.3 17.2 13.7 28.8 1.5 20 1.5 81.1 1.5 132.3s0 112.3-1.5 132.3z"/>
      </svg>
      @sistersbento
    </a>
  </p>
  <p>© 2025 SistersBento</p>
</footer>

  <audio id="fairySound" src="mixkit-fairy-glitter-867.wav" preload="auto"></audio>

  <script>
    const endTime = new Date("2025-06-14T23:59:59").getTime();
    const countdownEl = document.getElementById("countdown");

    const x = setInterval(() => {
      const now = new Date().getTime();
      const distance = endTime - now;

      if (distance < 0) {
        clearInterval(x);
        countdownEl.innerHTML = "PO sudah ditutup!";
        return;
      }

      const days = Math.floor(distance / (1000 * 60 * 60 * 24));
      const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
      const seconds = Math.floor((distance % (1000 * 60)) / 1000);

      countdownEl.innerHTML = `${days}h ${hours}j ${minutes}m ${seconds}d`;
    }, 1000);
  </script>

</body>
</html>

