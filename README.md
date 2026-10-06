<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Biodata Mahasiswa | Boash University</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body class="student-form-page">
  <header class="site-header">
    <a class="brand" href="index.html" aria-label="Boash University, halaman login">
      <span class="brand-mark" aria-hidden="true">BU</span>
      <span>Boash University</span>
    </a>
    <span class="header-label">Area Mahasiswa</span>
  </header>

  <main class="student-form-layout">
    <section class="student-form-card" aria-labelledby="form-title">
      <p class="eyebrow">Data mahasiswa</p>
      <h1 id="form-title">Biodata Mahasiswa</h1>
      <p class="form-intro">Lengkapi informasi diri Anda pada formulir berikut.</p>

      <form action="#" method="get">
        <div class="form-group">
          <label for="nim">NIM</label>
          <input type="text" id="nim" name="nim" autocomplete="off">
        </div>

        <div class="form-group">
          <label for="nama">Nama Lengkap</label>
          <input type="text" id="nama" name="nama" autocomplete="name" required>
        </div>

        <div class="form-group">
          <label for="email">Email</label>
          <input type="email" id="email" name="email" autocomplete="email">
        </div>

        <div class="form-group">
          <label for="tanggal-lahir">Tanggal Lahir</label>
          <input type="date" id="tanggal-lahir" name="tanggal_lahir">
        </div>

        <fieldset class="form-group choice-group">
          <legend>Jenis Kelamin</legend>
          <label class="choice-option" for="laki-laki">
            <input type="radio" id="laki-laki" name="jenis_kelamin" value="laki-laki">
            <span>Laki-laki</span>
          </label>
          <label class="choice-option" for="perempuan">
            <input type="radio" id="perempuan" name="jenis_kelamin" value="perempuan">
            <span>Perempuan</span>
          </label>
        </fieldset>

        <button class="login-button save-button" type="submit">Simpan</button>
      </form>

      <nav class="form-navigation" aria-label="Navigasi formulir">
        <a href="index.html">Kembali ke Login</a>
        <a href="minat-teknologi.html">Form Minat Teknologi</a>
      </nav>
    </section>
  </main>

  <footer class="site-footer">
    <p>&copy; 2026 Boash University. Hak cipta dilindungi.</p>
  </footer>
</body>
</html>
