<h1 align="center"> DAFTAR GAME GRATIS </h1>

<p align="justify"> Aplikasi Android ini menyediakan pengguna dengan akses mudah ke daftar game-game menarik yang dapat dimainkan secara gratis. Memanfaatkan layanan API FreeToGame, pengguna dapat dengan cepat menemukan berbagai judul game berkualitas tanpa biaya. Dengan antarmuka yang intuitif dan user-friendly, pengguna dapat menjelajahi daftar game, membaca deskripsi singkat, dan menemukan tautan langsung untuk mengunduh atau memainkan game secara online. Dengan aplikasi ini, pengguna dapat menikmati pengalaman bermain game yang menyenangkan tanpa harus khawatir tentang biaya. </p>


<h2 align="center">Anggota Proyek</h2>
<ul style="list-style-type:none; text-align:center; padding:0;">
  <li>
    <h4>Attar Akram Abdillah - 121140013 (pengembang proyek)</h4>
  </li>
  <li>
    <h4>Winnerson Laila - 121140121 (pengembang proyek)</h4>
  </li>
  <li>
    <h4>Solafide Zamili - 121140201 (pengembang proyek)</h4>
  </li>
  <li>
    <h4>Nasrul Alfin Prassetyo - 121140001 (pengujian dan dokumentasi)</h4>
  </li>
  <li>
    <h4>Muhammad Faried Halim - 121140197 (pengujian dan dokumentasi)</h4>
  </li>
</ul>

<h1 align="center">  BAB I : System Strukture </h1>
<p align="justify"> Tech Stack yang akan digunakan dalam aplikasi ini termasuk arsitektur MVVM untuk memisahkan antara model, tampilan, dan logika pemrosesan data. Aplikasi akan ditargetkan untuk SDK 34 dari Android. Basis data lokal akan dikelola menggunakan Room DB, sementara Retrofit akan digunakan untuk berkomunikasi dengan layanan API FreeToGame. Interceptor HTTP akan dipasang dengan Chucker untuk memantau dan mencatat panggilan API. Navigasi antar-fragmen akan dikelola menggunakan komponen Navigation, dan komponen Paging2 atau Paging3 akan digunakan untuk mengimplementasikan paginasi dalam daftar game.</p>		
<h2 align="center"> 1.1 Entity Relationship Diagram (ERD) </h2>
<p align="center">
  <img src="https://github.com/attarakram121140013/Tugas-Besar-PAM-Aplikasi-Rekomendasi-Game-Gratis/assets/96344530/27e36a83-ba64-46dc-b575-e8731b3c2373" alt="ERD" width="600">
</p>

<h2 align="center"> 1.2 Sequence Diagram </h2>
<p align="center">
  <img src="https://github.com/attarakram121140013/Tugas-Besar-PAM-Aplikasi-Rekomendasi-Game-Gratis/assets/96344530/74a9d9fc-992b-4138-99d8-c3d8bef2f9b3" alt="Sequence Diagram" width="600">
</p>

<h2 align="center"> 1.3 Class Diagram </h2>
<p align="center">
  <img src="https://github.com/attarakram121140013/Tugas-Besar-PAM-Aplikasi-Rekomendasi-Game-Gratis/assets/96344530/57f861e7-1465-40f4-95bd-d7eba59bbf8b" alt="Class Diagram" width="600">
</p>

<h2 align="center"> 1.4 Desain </h2>
<p align="center">
  <a href="https://www.figma.com/file/YjxT3uiYV3rpXhAW8vc8Yn/Tugas-Besar-Pengembangan-Aplikasi-Mobile-R---03?type=design&mode=design&t=mwpzdenIHItqEs5O-0">Link ke Desain Figma</a>
</p>
<p align="center">Di dalam desain kami, kami memiliki beberapa layer:</p>
<div align="center">
  <ol style="text-align: left;">
    <li>splashscreen</li>
    <li>sign in</li>
    <li>home</li>
    <li>profil</li>
    <li>favorit</li>
    <li>search</li>
    <li>detail game</li>
  </ol>
</div>





