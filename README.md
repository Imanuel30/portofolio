<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Portofolio [imanuel yudho kristiyadi]</title>
  <style>
    /* Reset & base */
    * {
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
      line-height: 1.6;
    }
    /* Navbar sticky */
    header {
      position: sticky;
      top: 0;
      background-color: #3f51b5;
      color: white;
      padding: 20px;
      text-align: center;
      z-index: 1000;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
      transition: background-color 0.3s ease;
    }
    header:hover {
      background-color: #2c3a9a;
    }
    /* Main content */
    main {
      padding: 20px;
      max-width: 900px;
      margin: auto;
    }
    .section {
      margin-bottom: 30px;
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }
    /* Animasi saat hover section */
    .section:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 15px rgba(0,0,0,0.15);
    }
    h1, h2, h3 {
      margin-top: 0;
    }
    ul {
      padding-left: 20px;
    }
    .project {
      margin-bottom: 15px;
      padding: 15px;
      background-color: #fafafa;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      transition: box-shadow 0.3s ease, background-color 0.3s ease;
    }
    .project:hover {
      background-color: #e3e7ff;
      box-shadow: 0 6px 10px rgba(0,0,0,0.2);
    }
    a {
      color: #3f51b5;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s ease;
    }
    a:hover {
      color: #2c3a9a;
      text-decoration: underline;
    }
    /* Responsive Design */
    @media (max-width: 600px) {
      main {
        padding: 10px;
      }
      header {
        padding: 15px 10px;
      }
      .section {
        padding: 15px;
      }
      .project {
        padding: 10px;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>[imanuel yudho kristiyadi]</h1>
    <p>Calon Web Developer | Pelajar SMK</p>
  </header>
  <main>
    <section class="section" id="tentang-saya">
      <h2>Tentang Saya</h2>
      <p>Saya adalah siswa SMK jurusan RPL yang sedang belajar web development dan ingin menjadi developer profesional. Saya tertarik pada teknologi, desain, dan membuat aplikasi yang bermanfaat.</p>
    </section>
    <section class="section" id="skill">
      <h2>Skill</h2>
      <ul>
        <li>HTML, CSS, JavaScript</li>
        <li>Python Dasar</li>
        <li>Git & GitHub</li>
        <li>Desain UI dasar (Canva, Figma)</li>
      </ul>
    </section>
    <section class="section" id="proyek">
      <h2>Proyek</h2>
      <div class="project">
        <h3>Website Pribadi</h3>
        <p>Web sederhana yang saya buat untuk belajar HTML dan CSS.</p>
        <a href="#">Lihat Proyek</a>
      </div>
      <div class="project">
        <h3>To-Do List App</h3>
        <p>Aplikasi daftar tugas menggunakan JavaScript dasar.</p>
        <a href="#">Lihat Proyek</a>
      </div>
    </section>
    <section class="section" id="kontak">
      <h2>Kontak</h2>
      <p>Email: kamu@email.com</p>
      <p>GitHub: <a href="https://github.com/yudho" target="_blank" rel="noopener noreferrer">github.com/yudho</a></p>
    </section>
  </main>
</body>
</html>
