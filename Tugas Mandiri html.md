<!DOCTYPE html>
<html lang="id">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sistem Booking Homestay Bali</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<!-- HEADER -->

<header>

<div class="logo">HOMESTAY BALI</div>

<nav>
<a href="#">Home</a>
<a href="#">Promo</a>
<a href="#">Kontak</a>
<button class="login">Masuk</button>
</nav>

</header>



<!-- BREADCRUMB -->

<div class="breadcrumb">

<span>HOMESTAY.co.id</span> >
<span>Homestay</span> >
<span>Homestay Asia</span> >
<span>Homestay Indonesia</span> >
<span class="active">Homestay Bali</span>

<span class="info-star" onclick="openPopup()"> *</span>

</div>



<!-- POPUP INFORMASI -->

<div id="popupInfo" class="popup">

<div class="popup-content">

<span class="close" onclick="closePopup()">×</span>

<h2>Informasi Harga Homestay</h2>

<p>
Harga kamar sudah termasuk pajak dan biaya layanan dalam mata uang Rupiah.
</p>

<p>
Harga dapat berubah sewaktu-waktu tergantung ketersediaan kamar.
</p>

<p>
Website ini membantu pengguna membandingkan berbagai homestay dengan cepat.
</p>

</div>

</div>



<!-- HERO -->

<section class="hero">

<div class="overlay">

<div class="search-box">

<h1>Cari Homestay Terbaik di Bali</h1>

<div class="form-search">

<input type="text" placeholder="Lokasi" id="lokasi">

<input type="date" id="checkin">

<input type="date" id="checkout">

<select id="tamu">
<option>1 Tamu</option>
<option>2 Tamu</option>
<option>3 Tamu</option>
<option>4 Tamu</option>
</select>

<button onclick="cariHomestay()">Telusuri</button>

</div>

</div>

</div>

</section>



<!-- PILIHAN KAMAR -->

<section class="kamar">

<h2>Pilihan Kamar Homestay</h2>

<div class="kamar-container">

<div class="kamar-card">
<img src="https://images.unsplash.com/photo-1560448204-e02f11c3d0e2">
<h3>Standard Room</h3>
<p>Kamar nyaman untuk 2 orang</p>
<h4>Rp 300.000</h4>
<button>Pesan</button>
</div>

<div class="kamar-card">
<img src="https://images.unsplash.com/photo-1590490360182-c33d57733427">
<h3>Deluxe Room</h3>
<p>Kamar luas dengan balkon</p>
<h4>Rp 450.000</h4>
<button>Pesan</button>
</div>

<div class="kamar-card">
<img src="https://images.unsplash.com/photo-1551882547-ff40c63fe5fa">
<h3>Family Room</h3>
<p>Kamar untuk keluarga</p>
<h4>Rp 600.000</h4>
<button>Pesan</button>
</div>

<div class="kamar-card">
<img src="https://images.unsplash.com/photo-1505691938895-1758d7feb511">
<h3>Garden View</h3>
<p>Pemandangan taman</p>
<h4>Rp 500.000</h4>
<button>Pesan</button>
</div>

<div class="kamar-card">
<img src="https://images.unsplash.com/photo-1501117716987-c8e1ecb210b1">
<h3>Pool View</h3>
<p>Pemandangan kolam</p>
<h4>Rp 550.000</h4>
<button>Pesan</button>
</div>

<div class="kamar-card">
<img src="https://images.unsplash.com/photo-1582719478250-c89cae4dc85b">
<h3>Luxury Suite</h3>
<p>Kamar premium</p>
<h4>Rp 750.000</h4>
<button>Pesan</button>
</div>

</div>

</section>



<!-- FASILITAS -->

<section class="fasilitas">

<h2>Fasilitas Homestay</h2>

<div class="fasilitas-container">

<div class="fasilitas-box">
<span>📅</span>
<h3>Tanggal Pemesanan</h3>
<p>Pilih tanggal check-in dan check-out sesuai kebutuhan.</p>
</div>

<div class="fasilitas-box">
<span>💳</span>
<h3>Pembayaran</h3>
<p>Pembayaran dapat dilakukan melalui transfer atau e-wallet.</p>
</div>

<div class="fasilitas-box">
<span>🛏️</span>
<h3>Kamar Nyaman</h3>
<p>Kamar bersih dan nyaman.</p>
</div>

<div class="fasilitas-box">
<span>📶</span>
<h3>Wifi Gratis</h3>
<p>Akses internet gratis selama menginap.</p>
</div>

</div>

</section>



<!-- FOOTER -->

<footer>

<div class="footer-container">

<div>
<h4>Perusahaan</h4>
<p>Tentang Kami</p>
<p>Karir</p>
</div>

<div>
<h4>Kontak</h4>
<p>Email</p>
<p>Bantuan</p>
</div>

<div>
<h4>Lainnya</h4>
<p>Keamanan</p>
<p>Kebijakan</p>
</div>

</div>

<p class="copyright">©2026 Homestay Bali</p>

</footer>


<script src="script.js"></script>

</body>
</html>
