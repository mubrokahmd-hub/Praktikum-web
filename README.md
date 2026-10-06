<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login Mahasiswa | Boash University</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <a class="brand" href="#home" aria-label="Boash University, beranda">
      <span class="brand-mark" aria-hidden="true">BU</span>
      <span>Boash University</span>
    </a>
    <span class="header-label">Area Mahasiswa</span>
  </header>

  <main class="login-layout" id="home">
    <section class="welcome-panel" aria-labelledby="welcome-title">
      <p class="eyebrow">Boash University</p>
      <h1 id="welcome-title">Selamat datang kembali.</h1>
      <p>Masuk untuk mengakses informasi perkuliahan dan layanan akademik Anda.</p>
      <div class="welcome-decoration" aria-hidden="true">
        <span></span><span></span><span></span>
      </div>
    </section>

    <section class="login-card" aria-labelledby="login-title">
      <div class="card-heading">
        <p class="eyebrow">Akun mahasiswa</p>
        <h2 id="login-title">Login</h2>
        <p>Masukkan email dan kata sandi akun Anda.</p>
      </div>

      <form action="/login" method="POST">
        <div class="form-group">
          <label for="email">Email mahasiswa</label>
          <input
            type="email"
            id="email"
            name="email"
            placeholder="nama@kampus.ac.id"
            autocomplete="username"
            required
          >
        </div>

        <div class="form-group">
          <label for="password">Kata sandi</label>
          <input
            type="password"
            id="password"
            name="password"
            placeholder="Masukkan kata sandi"
            autocomplete="current-password"
            required
          >
        </div>

        <div class="form-actions">
          <button class="login-button" type="submit">Login</button>
          <button class="reset-button" type="reset">Reset</button>
        </div>
      </form>

      <p class="security-note"><span aria-hidden="true">●</span> Pastikan Anda menggunakan akun mahasiswa yang terdaftar.</p>
      <nav class="form-navigation" aria-label="Halaman formulir mahasiswa">
        <a href="biodata.html">Form Biodata</a>
        <a href="minat-teknologi.html">Form Minat Teknologi</a>
      </nav>
    </section>
  </main>

  <footer class="site-footer">
    <p>&copy; 2026 Boash University. Hak cipta dilindungi.</p>
  </footer>
</body>
</html>
