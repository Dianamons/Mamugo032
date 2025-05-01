<!DOCTYPE html><html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Admin SD Negeri 032 Mamugo</title>
  <style>
    body {
      background-color: #1e1e2f;
      color: #fff;
      font-family: Arial, sans-serif;
      padding: 10px;
    }
    h1 {
      text-align: center;
      color: #3399ff;
    }
    .section {
      background-color: #2a2a40;
      padding: 15px;
      margin: 15px 0;
      border-radius: 10px;
    }
    label, select, input, textarea, button {
      display: block;
      margin: 10px 0;
      width: 100%;
      max-width: 400px;
    }
    button {
      background-color: #3399ff;
      color: white;
      border: none;
      padding: 10px;
      border-radius: 8px;
      cursor: pointer;
    }
    button:hover {
      background-color: #2277cc;
    }
  </style>
</head>
<body>
  <h1>Panel Admin - SD Negeri 032 Mamugo</h1>  <div class="section">
    <h2>Login Admin</h2>
    <input type="password" id="adminPass" placeholder="Masukkan Password Admin">
    <button onclick="loginAdmin()">Login</button>
  </div>  <div class="section">
    <h2>Tambah Siswa</h2>
    <select id="kelasSiswa">
      <option value="">-- Pilih Kelas --</option>
      <option>Kelas 1</option><option>Kelas 2</option><option>Kelas 3</option>
      <option>Kelas 4</option><option>Kelas 5</option><option>Kelas 6</option>
    </select>
    <input type="text" id="namaSiswa" placeholder="Nama Siswa">
    <input type="text" id="alamatSiswa" placeholder="Alamat Siswa">
    <button onclick="tambahSiswa()">Tambah Siswa</button>
  </div>  <div class="section">
    <h2>Tambah Jadwal</h2>
    <select id="kelasJadwal">
      <option value="">-- Pilih Kelas --</option>
      <option>Kelas 1</option><option>Kelas 2</option><option>Kelas 3</option>
      <option>Kelas 4</option><option>Kelas 5</option><option>Kelas 6</option>
    </select>
    <textarea id="isiJadwal" placeholder="Masukkan Jadwal"></textarea>
    <button onclick="simpanJadwal()">Simpan Jadwal</button>
  </div>  <div class="section">
    <h2>Upload Latar Belakang Beranda</h2>
    <input type="text" id="urlLatarBeranda" placeholder="Masukkan URL Gambar">
    <button onclick="gantiLatarBeranda()">Simpan Latar</button>
  </div>  <div class="section">
    <h2>Upload Latar Kelas</h2>
    <select id="kelasLatar">
      <option value="">-- Pilih Kelas --</option>
      <option>Kelas 1</option><option>Kelas 2</option><option>Kelas 3</option>
      <option>Kelas 4</option><option>Kelas 5</option><option>Kelas 6</option>
    </select>
    <input type="text" id="urlLatarKelas" placeholder="Masukkan URL Gambar">
    <button onclick="gantiLatarKelas()">Simpan Latar Kelas</button>
  </div>  <div class="section">
    <h2>Upload Galeri Foto</h2>
    <input type="text" id="urlGaleri" placeholder="URL Gambar dari Imgur">
    <input type="text" id="ketGaleri" placeholder="Keterangan Gambar">
    <button onclick="tambahGaleri()">Tambah Foto Galeri</button>
  </div>  <div class="section">
    <h2>Pengumuman & Agenda</h2>
    <textarea id="pengumuman" placeholder="Tulis pengumuman atau agenda..."></textarea>
    <button onclick="simpanPengumuman()">Simpan Info</button>
  </div>  <div class="section">
    <h2>Sambutan Kepala Sekolah</h2>
    <textarea id="sambutan" placeholder="Tulis sambutan..."></textarea>
    <button onclick="simpanSambutan()">Simpan Sambutan</button>
  </div>  <div class="section">
    <h2>Jam & Kontak Sekolah</h2>
    <input type="text" id="jam" placeholder="Jam Operasional">
    <input type="text" id="kontak" placeholder="Nomor Kontak">
    <button onclick="simpanKontak()">Simpan</button>
  </div>  <script>
    function loginAdmin() {
      const pass = document.getElementById("adminPass").value;
      if (pass === "admin032") alert("Login berhasil");
      else alert("Password salah");
    }
    function tambahSiswa() {
      alert("Siswa ditambahkan (simulasi)");
    }
    function simpanJadwal() {
      alert("Jadwal disimpan (simulasi)");
    }
    function gantiLatarBeranda() {
      alert("Latar belakang beranda diubah (simulasi)");
    }
    function gantiLatarKelas() {
      alert("Latar belakang kelas diubah (simulasi)");
    }
    function tambahGaleri() {
      alert("Foto galeri ditambahkan (simulasi)");
    }
    function simpanPengumuman() {
      alert("Pengumuman disimpan (simulasi)");
    }
    function simpanSambutan() {
      alert("Sambutan disimpan (simulasi)");
    }
    function simpanKontak() {
      alert("Kontak disimpan (simulasi)");
    }
  </script></body>
</html>
