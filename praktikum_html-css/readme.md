# 📄 CV Digital dengan HTML Semantic dan CSS

Praktikum ini adalah pembuatan Curriculum Vitae (CV) sederhana berbasis web.  
Tujuan utama proyek ini adalah melatih penggunaan **HTML semantic** untuk struktur halaman yang rapi dan **CSS** untuk styling agar tampilan lebih menarik dan mudah dibaca.

---

## 🫧 Identitas Penulis
Nama: Ni Luh Risma Putri Wirdianthi<br>
NIM: 42430001

---

## 📋 Deskripsi Praktikum
Praktikum ini membuat CV sederhana dengan memanfaatkan **HTML semantic** seperti `<header>`, `<section>`, dan `<footer>`.  
CSS digunakan untuk memberikan gaya visual seperti layout, warna, tipografi, dan spasi agar informasi mudah dibaca.

---

## 🧩 Implementasi

Beberapa tag HTML semantic yang digunakan:  
- `<header>` : Menampilkan nama dan posisi (contoh: *Future Data Scientist*).  
- `<section>` : Membagi konten utama seperti pendidikan, pengalaman, dan keahlian.    
- `<footer>` : Bagian penutup CV yang berisi informasi sosial media penulis.  

### Contoh potongan kode: HTML
<img src="./images/tampilan-akhir/header-html-cv.png" alt="Preview Header CV HTML" width="500"><br>
<img src="./images/tampilan-akhir/section-html-cv.png" alt="Preview Main Section CV HTML" width="500"><br>
<img src="./images/tampilan-akhir/footer-html-cv.png" alt="Preview Footer CV HTML" width="500"><br>

### Contoh potongan kode: CSS
<img src="./images/tampilan-akhir/header-cv.png" alt="Preview Header CV CSS" width="500"><br>
<img src="./images/tampilan-akhir/section-cv.png" alt="Preview Main Section CV CSS" width="500"><br>
<img src="./images/tampilan-akhir/footer-cv.png" alt="Preview Footer CV CSS" width="500"><br>

---

## 🦾Pembahasan Baris Kode HTML
### Header
<img src="./images/pembahasan/header-cv-html.png" alt="Header CV" width="500"><br>
- `<header class="header">` : Bagian atas halaman untuk identitas utama.  
- `<h1>` : Menampilkan nama pemilik CV.  
- `<p>` : Menampilkan deskripsi singkat atau posisi, misalnya "Future Data Scientist".  

### Section Biodata
<img src="./images/pembahasan/section-biodata-cv-html.png" alt="Section Biodata CV" width="500"><br>
- `<section id="biodata" class="bagian-biodata">` : Bagian khusus untuk menampilkan biodata diri.  
- `<h2>` : Judul subbagian "Biodata Diri".  
- `<p>` : Menampilkan informasi biodata (alamat, email, status, hobi, dll).  
- `<div class="foto-risma">` : Membungkus elemen foto.  
- `<img>` : Menampilkan foto profil agar CV lebih personal.  

### Section Pendidikan dan Bahasa
<img src="./images/pembahasan/section-pendidikan-cv-html.png" alt="Section Pendidikan dan Bahasa CV" width="500"><br>
- `<section id="pendidikan-bahasa">` : Bagian untuk menampilkan riwayat pendidikan dan bahasa.  
- `<h2>` : Judul subbagian, yaitu "Pendidikan" dan "Bahasa".  
- `<ul><li>` : Daftar riwayat pendidikan serta bahasa yang dikuasai agar lebih mudah dibaca.  

### Section Keahlian
<img src="./images/pembahasan/section-keahlian-cv-html.png" alt="Section Keahlian CV" width="500"><br>
- `<section id="keahlianDasar-nonTeknis">` : Bagian untuk menampilkan keahlian teknis dan non-teknis.  
- `<h2>` : Judul subbagian keahlian.  
- `<ul><li>` : Daftar keahlian teknis (pemrograman, data analysis, machine learning) dan non-teknis (manajemen waktu, tanggung jawab).  

### Footer
<img src="./images/pembahasan/footer-cv-html.png" alt="Footer CV" width="500"><br>
- `<footer class="footer">` : Bagian bawah halaman.  
- `<p>` : Menampilkan ajakan untuk mengikuti sosial media.  
- `<a href="..." target="_blank">` : Link menuju Instagram dan LinkedIn yang terbuka di tab baru.  

---

## 🦾Pembahasan Baris Kode CSS
### Body
<img src="./images/pembahasan/body-css.png" alt="Body CV CSS" width="500"><br>

- `font-family: system-ui, 'Segoe UI';` digunakan untuk membuat teks menggunakan font standar sistem agar lebih enak dibaca.  
- `margin-left` dan `margin-right` digunakan untuk memberi jarak kiri dan kanan, jadi isi CV lebih rapi di tengah.  
- `background-color: #053157;` digunakan untuk memberi warna biru gelap sebagai latar belakang halaman.    

### Header
<img src="./images/pembahasan/header-css.png" alt="Header CV CSS" width="500"><br>
    
- `background: #EEF7FF;` digunakan untuk memberi warna latar yang lembut agar kontras dengan background halaman.  
- `color: #7AB2B2;` digunakan untuk mengatur warna teks menjadi hijau kebiruan.  
- `padding: 10px;` digunakan untuk memberi ruang di dalam header agar teks tidak menempel.  
- `text-align: center;` digunakan untuk membuat teks berada di tengah.  
- `font-weight: bold;` digunakan untuk menebalkan teks agar lebih tegas.   

### Section Umum
<img src="./images/pembahasan/section-css.png" alt="Section Umum CV CSS" width="500"><br>

- Semua `<section>` memakai `background-color: white;` supaya isi terlihat bersih di atas background biru.  
- Setiap section utama (`#biodata`, `#pendidikan-bahasa`, `#keahlianDasar-nonTeknis`) diberi `padding-left` agar teks tidak terlalu menempel di tepi.   

### Biodata
<table>
    <tr>
        <td>
            <img src="./images/pembahasan/biodata-css.png" alt="Biodata Bagian 1 CV CSS" width="500"><br>
        </td>
        <td>
            <img src="./images/pembahasan/biodata2-css.png" alt="Biodata Bagian 2 CV CSS" width="500"><br>
        </td>
    </tr>
</table>

- `.bagian-biodata` menggunakan `display: flex` agar teks dan foto bisa sejajar.  
- `gap: 50px;` digunakan untuk memberi jarak antara biodata dan foto.  
- `align-items: center;` digunakan untuk membuat konten rata tengah secara vertikal.  
- `line-height: 0.7;` digunakan untuk mengecilkan jarak antarbaris biodata.  
- `flex: 1;` digunakan agar bagian biodata bisa menyesuaikan diri agar tidak tumpang tindih dengan bagian foto.  
- `.bagian-biodata p { text-indent: 21.5px; }` digunakan untuk memberi indentasi di awal tiap paragraf biodata.  
- `.biodata-diri { color: #7AB2B2; }` digunakan untuk membuat judul subbagian tampil dengan warna khusus. 
- `position: relative;` digunakan untuk mengatur posisi gambar agar lebih fleksibel di dalam section. 
- `.foto-risma img { width: 200px; }` digunakan untuk menentukan ukuran foto agar konsisten.  

### Pendidikan dan Bahasa
<table>
    <tr>
        <td>
            <img src="./images/pembahasan/pendidikan-css.png" alt="Pendidikan-Bahasa Bagian 1 CV CSS" width="500"><br>
        </td>
        <td>
            <img src="./images/pembahasan/pendidikan2-css.png" alt="Pendidikan-Bahasa Bagian 2 CV CSS" width="500"><br>
        </td>
    </tr>
</table>

- `#pendidikan-bahasa { display: flex; justify-content: space-between; }` membuat bagian pendidikan dan bahasa ditampilkan berdampingan.  
- `padding-right: 200px;` digunakan untuk memberi ruang di sisi kanan agar tampilan tidak terlalu penuh.  
- `.pendidikan-kuliah { color: #7AB2B2; }` digunakan untuk memberi warna khusus pada judul pendidikan. 
- `width: 45%;` digunakan untuk elemen list agar lebarnya hanya setengah dari container. 
- `.pendidikan-kuliah ul li { text-align: right; }` digunakan untuk membuat daftar pendidikan rata kanan.  
- `.bahasa-digunakan { color: #7AB2B2; }` digunakan untuk memberi warna khusus pada judul bahasa.  
- `.bahasa-digunakan ul li { text-align: left; }` digunakan untuk membuat daftar bahasa rata kiri.  

### Keahlian
<table>
    <tr>
        <td>
            <img src="./images/pembahasan/keahlian-css.png" alt="Keahlian Bagian 1 CV CSS" width="500"><br>
        </td>
        <td>
            <img src="./images/pembahasan/keahlian2-css.png" alt="Keahlian Bagian 2 CV CSS" width="500"><br>
        </td>
    </tr>
</table>

- `#keahlianDasar-nonTeknis { display: flex; justify-content: space-between; }` digunakan untuk menempatkan keahlian teknis dan non-teknis berdampingan.  
- `.minat-bakat { color: #7AB2B2; }` digunakan untuk memberi warna judul keahlian teknis.  
- `.minat-bakat ul li { text-align: right; }` digunakan untuk membuat daftar keahlian teknis rata kanan.  
- `.bakat-minat { color: #7AB2B2; text-align: left; }` digunakan untuk memberi warna dan meratakan keahlian non-teknis ke kiri. 

### Footer
<img src="./images/pembahasan/footer-css.png" alt="Footer CV CSS" width="500"><br>
      
- `.footer { text-align: center; padding: 5px; color: #4D869C; background-color: #EEF7FF; }`: Bagian footer dibuat rata tengah, diberi ruang dalam, warna teks hijau kebiruan, dan latar lembut agar kontras dengan halaman.  
- `.footer p a { text-decoration: none; }` digunakan untuk menghilangkan garis bawah pada link, sehingga terlihat lebih bersih.  

---

## 🖼 Hasil Tampilan
Berikut ini adalah hasil akhir tampilan CV dalam mode desktop browser: 
<br><img src="./images/tampilan-akhir/hasil-akhir-cv.png" alt="Preview CV Final" width="500">

---

## ✅ Kesimpulan
Praktikum ini membantu penulis memahami penggunaan HTML semantic dan CSS dasar dalam membuat halaman CV digital.
Struktur yang rapi memudahkan pengembangan lebih lanjut menjadi CV online yang profesional. Sebagai tambahan, penulis juga membuat bagian homepage agar nantinya dimasa depan homepage ini bisa berkembang menjadi portfolio website yang terintegrasi juga dengan CV penulis didalamnya. Sehingga alurnya menjadi: homepage-cv.  
