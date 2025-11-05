<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Laman Sally</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <!-- Navbar -->
    <nav class="navbar">
      <a href="index.html">Beranda</a>
      <a href="artikel.html">Artikel</a>
      <a href="tentang saya.html">Tentang saya</a>
    </nav>

    <!-- Hero Section -->
    <section class="hero">
      <h1>Selamat datang di laman Sally!</h1>
      <p>
        Di artikel ini kalian bisa mengetahui apa saja keberagaman yang ada di
        Indonesia
      </p>

      <!-- ✅ Container khusus gambar & tombol -->
      <div class="content-box">
        <img
          src="indonesia kids.png"
          alt="anak-anak Indonesia"
          class="center-img"
        />
        <a class="btn" href="artikel.html">Baca artikel</a>
      </div>
    </section>

    <!-- Flowers -->
    <img src="blue flower left.png" alt="bunga kiri" class="flower left" />
    <img src="blue flowers.png" alt="bunga kanan" class="flower right" />
  </body>
</html>

body {
  margin: 0;
  font-family: "Poppins", sans-serif;
  background: #e3f5ff;
}

/* NAVBAR */
.navbar {
  display: flex;
  justify-content: center;
  gap: 120px;
  background: linear-gradient(to right, #00fff2, #f047ff);
  padding: 15px;
  font-weight: bold;
}

.navbar a {
  text-decoration: none;
  color: #4c38ff;
  font-size: 18px;
}

/* HERO */
.hero {
  text-align: center;
  padding: 40px 20px;
  color: #a60cff;
}

.hero h1 {
  font-size: 28px;
  font-weight: 800;
  margin-bottom: 10px;
}

.hero p {
  font-size: 16px;
  color: #d883ff;
  margin-bottom: 20px;
}

/* ✅ Pusatkan gambar & tombol benar2 */
.content-box {
  display: flex;
  flex-direction: column;
  align-items: center;
}

/* IMAGE */
.center-img {
  width: 200px;
  border-radius: 10px;
  border: 2px solid #ffc1e3;
  margin-bottom: 15px;
}

/* BUTTON */
.btn {
  background: #ffb6e5;
  color: white;
  padding: 12px 35px;
  border-radius: 30px;
  font-size: 18px;
  text-decoration: none;
  font-weight: bold;
  transition: 0.3s;
}

.btn:hover {
  background: #ff8dcc;
}

/* ✅ Flowers bottom left & right */
.flower {
  position: fixed;
  bottom: 0;
  width: 200px;
  z-index: -1;
}

.flower.left {
  left: 0;
}

.flower.right {
  right: 0;
}
