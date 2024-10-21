
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laporan Magang Setyo</title>
    <link rel="stylesheet" href="yusc.css">
</head>
<body>
    <header>
        <h1>Laporan Magang Setyo</h1>
        <p>Pengalaman Berharga di <strong>Rowellin Persada Utama</strong></p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#tentang">Tentang Magang</a></li>
            <li><a href="#proyek">Proyek yang Dikerjakan</a></li>
            <li><a href="#kesimpulan">Kesimpulan</a></li>
            <li><a href="#kontak">Kontak</a></li>
        </ul>
    </nav>

    <section id="tentang">
        <h2>Tentang Magang</h2>
        <p>Saya melakukan magang di <strong>Rowellin Persada Utama</strong> dari <strong>15/07/2024</strong> hingga <strong>15/12/2024</strong>. Selama magang, saya mendapatkan banyak pengalaman berharga di bidang <strong>[Bidang Pekerjaan]</strong>.</p>
        <img src="gambar.jpg" alt="Gambar terkait magang" class="responsive">  
        </section>
    
    <section id="proyek">
        <h2>Proyek yang Dikerjakan</h2>
        <ul>
            <li><strong>Proyek 1:</strong> Deskripsi singkat tentang proyek 1.</li>
            <li><strong>Proyek 2:</strong> Deskripsi singkat tentang proyek 2.</li>
            <li><strong>Proyek 3:</strong> Deskripsi singkat tentang proyek 3.</li>
        </ul>
    </section>

    <section id="kesimpulan">
        <h2>Kesimpulan</h2>
        <p>Magang ini sangat bermanfaat bagi saya dan membantu saya memahami lebih dalam tentang industri <strong>[Industri Terkait]</strong>. Saya berharap pengalaman ini akan menjadi modal berharga untuk karir saya di masa depan.</p>
    </section>
    
    <section id="kontak">
        <h2>Kontak</h2>
        <p>Jika ada pertanyaan, silakan hubungi saya di:</p>
        <p>Email: <a href="mailto:setyo@example.com">setyo@example.com</a></p>
        <p>Telepon: <strong>[Nomor Telepon]</strong></p>
    </section>

    <footer>
        <p>&copy; 2024 Setyo. Semua hak dilindungi.</p>
    </footer>
</body>
</html>
/* Mengatur box model untuk semua elemen */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #f0f8ff; /* Warna latar belakang yang lembut */
    color: #333;
}

/* Header */
header {
    background-color: #007BFF; /* Warna biru */
    color: #fff;
    text-align: center;
    padding: 2rem 0;
}

header h1 {
    font-size: 2.5rem; /* Ukuran font untuk judul */
}

header p {
    font-size: 1.2rem; /* Ukuran font untuk deskripsi */
}

/* Navigasi */
nav {
    background-color: #333; /* Warna latar belakang navigasi */
    padding: 1rem;
}

nav ul {
    list-style: none;
    text-align: center; /* Pusatkan teks */
}

nav ul li {
    display: inline;
    margin: 0 15px; /* Jarak antar item navigasi */
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold; /* Tebalkan teks */
}

nav ul li a:hover {
    text-decoration: underline; /* Garis bawah saat hover */
}

/* Section */
section {
    padding: 20px;
    margin: 20px auto;
    max-width: 800px; /* Maksimal lebar section */
    background-color: #fff; /* Warna latar belakang section */
    border-radius: 8px; /* Sudut membulat */
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1); /* Bayangan */
}

/* Judul Section */
h2 {
    color: #007BFF; /* Warna judul */
    margin-bottom: 10px; /* Jarak bawah judul */
}

/* Gambar */
.gambar-kecil {
    width: 150px; /* Lebar untuk gambar kecil */
    height: auto; /* Tinggi otomatis */
    border-radius: 8px; /* Sudut membulat pada gambar */
}

.responsive {
    max-width: 100%; /* Gambar responsif */
    height: auto; /* Tinggi otomatis */
}

/* Footer */
footer {
    text-align: center;
    padding: 20px 0;
    background-color: #333; /* Warna latar belakang footer */
    color: #fff;
    position: relative;
    width: 100%;
    bottom: 0;
}
