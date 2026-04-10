<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Biodata Irfan</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', sans-serif;
}

body {
    background: linear-gradient(135deg, #4facfe, #00f2fe);
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

.container {
    width: 90%;
    max-width: 400px;
}

.profile-card {
    background: rgba(255, 255, 255, 0.2);
    backdrop-filter: blur(15px);
    border-radius: 20px;
    text-align: center;
    padding: 30px 20px;
    color: white;
    box-shadow: 0 8px 30px rgba(0,0,0,0.2);
    margin-bottom: 20px;
    transition: 0.3s;
}

.profile-card:hover {
    transform: scale(1.03);
}

.profile-img {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    border: 4px solid white;
    margin-bottom: 15px;
}

.subtitle {
    opacity: 0.8;
    margin-bottom: 10px;
}

.deskripsi {
    font-size: 14px;
    margin-bottom: 15px;
    line-height: 1.5;
}

.info p {
    font-size: 14px;
    margin: 5px 0;
}

.card {
    background: white;
    border-radius: 15px;
    padding: 20px;
    margin-top: 15px;
    box-shadow: 0 5px 20px rgba(0,0,0,0.1);
}

.card h2 {
    margin-bottom: 10px;
}

ul {
    padding-left: 20px;
}

.skills {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
}

.skills span {
    background: #4facfe;
    color: white;
    padding: 6px 12px;
    border-radius: 20px;
    font-size: 13px;
    transition: 0.3s;
}

.skills span:hover {
    background: #00c6ff;
    transform: scale(1.1);
}
</style>

</head>
<body>

<div class="container">

    <div class="profile-card">
        <img src="poto.jpg" class="profile-img">

        <h1>Irfan Dwi Ariyanto</h1>
        <p class="subtitle">Student | RPL Developer</p>

        <p class="deskripsi">
            Saya adalah seorang siswa kelas 11 RPL 2 dari sekolah SMK N 1 Sanden.
            Saya memiliki minat di bidang pengembangan web dan terus belajar meningkatkan kemampuan di bidang teknologi.
        </p>

        <div class="info">
            <p>Tempat: Bantul</p>
            <p>Tanggal Lahir: 20 Januari 2009</p>
            <p>Email: pppp@mbohhhh.com</p>
            <p>No HP: +62 812-2872-9455</p>
        </div>
    </div>

    <div class="card">
        <h2>Pendidikan</h2>
        <ul>
            <li>SD Kalidadap 1 (2015 - 2021)</li>
            <li>SMP N 2 Pundong (2021 - 2024)</li>
            <li>SMK N 1 Sanden - RPL (2024 - 2027)</li>
        </ul>
    </div>

    <div class="card">
        <h2>Keahlian</h2>
        <div class="skills">
            <span>HTML</span>
            <span>CSS</span>
            <span>JavaScript</span>
            <span>PHP</span>
            <span>Laravel</span>
            <span>NodeJS</span>
        </div>
    </div>

</div>

</body>
</html>
