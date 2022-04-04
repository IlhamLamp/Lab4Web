# LAB4 WEB

<table border="2" cellpading="10">
  <tr>
    <td><b>Nama</b></td>
    <td>Ilham Nur Utomo</td>
  </tr>
  <tr>
    <td><b>NIM</b></td>
    <td>312010129</td>
  </tr>
  <tr>
    <td><b>Kelas</b></td>
    <td>TI.20.A1</td>
  </tr>
  <tr>
    <td><b>MataKuliah</b></td>
    <td>Pemrograman Web</td>
  </tr>
</table>

# <b>Praktikum</b>

## <b>1. Box Element </b>
- Dengan internal css, <i>float property</i>
![image1](image/0-1_box-element.PNG)

## <b>2. Clearfix Element </b>
- Properti ``clear: left;`` pada ``div4``
![image2](image/0-2_cfix-element.PNG)<br>

- Box Merah berada di kiri
- Properti ``clear: right;`` Box Hijau berada di kanan
- Properti ``clear: both;`` Box Kuning berada di antara Box Merah dan Box Hijau
- Properti ``clear: left;`` Box biru berada di kiri.
![image3](image/0-2-1_clear-option.PNG)

## <b>3. Kerangka Layout </b>
- File baru, ``lab4_layout.html`` dengan css eksternal ``css/style.css``.
![image4](image/0-3_kerangka-layout.PNG)

## <b>4. Menu Navigasi </b>
![image5](image/0-4_nav.PNG)

## <b>5. Hero Panel </b>
![image6](image/0-5_hero-panel.PNG)

## <b>6. Layout Main dan Sidebar </b>
- Sidebar widget, dengan zoom in microsoft edge 67%
![image7](image/0-6_sidebar-widget.PNG)

## <b>7. Footer </b>
![image8](image/0-7_footer.PNG)

## <b>8. Main Content </b>
![image9](image/0-8_main-content.PNG)

## <b>9. Konten Artikel </b>
![image10](image/0-9_article.PNG)

# Tugas

- <b>1. Tambahkan Layout untuk menu About => buat single layout yang berisi deskripsi, portfolio, dll<b>
  - Jawaban:
  
  - Berikut isi dari ``<div> id="about">``.
  ![image11](image/1-about-me.PNG)<br>

  - ``display: flex;`` berfungsi membuat elemen-elemen yang ada di dalamnya menjadi menjajar ke samping dengan rapih (sesuai keinginan).
  - ``align-items: center`` agar semua item di dalam flex berada di tengah.
  - ``justify-content: space-between;``untuk memberi jarak antar kontennya. 

- <b>2. Tambahkan layout untuk menu Contact => yang berisi form isian: nama, email, message, dll</b>
  - Jawaban:

  - Sebelum,
  ![image11](image/2-contact.PNG)<br>
  - Sesudah, proses klik <i>Send Message</i>
  ![image12](image/3-contact.png)<br>

  - Pada ``input[type=text], textarea``, ``resize: vertical;`` berfungsi mengatur kolom <b>Masukan</b> agar hanya dapat naik-turun.
  - ``input[type=submit]:hover`` adalah ketika kursor diarahkan ke elemen tersebut, maka akan berubah sesuai pengkondisiannya.
