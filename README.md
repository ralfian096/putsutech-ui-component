<h1>Putsutech UI Components Documentation</h1>

<h3>Navigasi</h3>
<ul>
  <li>
    <b><a href="#installation">Instalasi</a></b>: Panduan instalasi project pada komputer
  </li>
</ul>

<br> <br> <br>
<h2 id="installation">Instalasi</h2>

<h3>Kebutuhan sebelum instalasi</h3>
<ol>
  <li>NPM & Node.js</li>
  <li>VS Code</li>
</ol>

<h3>Cara instalasi</h3>
<ol>
  <li>
    Clone repositori ini ke komputer anda
  </li>
  <li>
    Arahkan terminal ke direktori yang sudah di clone
  </li>
  <li>
    Pilih branch <b>"basic_component"</b> dengan menjalankan perintah berikut:
    <blockquote>
      $ git checkout basic_component
    </blockquote>
  </li>
  <li>
    Pastikan token di git lokal sama dengan token di github.
    <br>Untuk memeriksannya jalankan perintah berikut:
    <blockquote>
      $ git branch -v
    </blockquote>
    Git akan memberikan respon seperti berikut:
    <blockquote>
      <b>basic_component</b> [6 digit pertama token] [Judul update terakhir]<br>
      master [6 digit pertama token] [Judul update terakhir]
    </blockquote>
  </li>
  <li>
    Hapus branch yang tidak diperlukan. Hapus branch <b>"master"</b>
    <blockquote>
      $ git branch -D master
    </blockquote>
  </li>
  <li>
    Jalankan perintah dibawah ini untuk meng-install dependency:
    <blockquote>
      npm update
    </blockquote>
    NPM akan meng-install node_modules yang dibutuhkan proyek.<br>
    Tunggu hingga proses selesai
  </li>
  <li>
    Jalankan perintah ini untuk menjalankan proyek di komputer anda
    <blockquote>
      npm run dev
    </blockquote>
    Buka project di browser menggunakan port yang sudah ditentukan.
  </li>
</ol>