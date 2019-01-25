# latihan-CSSResponsive-Anandarafimanullah-XRPL4-07
1. Kenapa kita perlu membuat web dengan responsive?
Karena responsive berfungsi untuk tampilan web kita di segala device baik desktop maupun smartphone. Halaman website yang baik harus dapat menyesuaiakan tampilan web kita dari device yang kita gunakan. maka dari itu kita mengatasinya dengan cara menggunakan Responsive.
2. Bagaimana cara membuat web dengan responsive? Jelaskan!
Hal yang pertama kali untuk membuat halaman web yang responsive adalah dengan mengatur viewport pada halaman web tersebut. Pengaturan tersebut dituliskan pada tag <meta> yang terdapat di dalam tag <head>. Berikut ini adalah kode untuk mengatur viewport pada halaman web. <head> <meta name=”viewport” content=”width=device-width, initialscale=1.0” > .. </head>
(Maksudnya adalah kita harus mengatur viewport pada halaman tersebut didalam <head>...</head>. viewport harus diketikkan bersama meta tag. Tag <meta> menyediakan metadata tentang dokumen HTML. Metadata dapat digunakan oleh browser (cara menampilkan konten web kita atau memuat ulang halaman secara otomatis dengan waktu yang kita tentukan), mesin pencari suatu web  (kata kunci). Dengan begitu cara responsive. maksud dari content="width=device-width, initialscale=1.0" adalah contentnya yaitu lebar= ukuran device yang kita gunakan dikurangi width yang kita sesuaikan serta maksud dari initialscale=1.0 yaitu saat ketika kita membuka web tersebut, layout kita akan ditampilkan dengan baik pada skala 1:1. Tidak ada pembesaran pada web tersebut.)
3. Apa maksud dari kode "initial- scale=1.0” ?  
maksudnya yaitu saat ketika kita membuka web tersebut, layoukita akan ditampilkan dengan baik pada skala 1:1. Tidak ada pembesaran pada web tersebut.
4. Bagian mana saja yang perlu kita atur/buat responsive dalam sebuah web!
pada bagian head didalam HTML kita berikan kode <meta name=”viewport” content=”width=device-width, initialscale=1.0” > supaya ketika kita membuka web tersebut, layout kita akan ditampilkan dengan baik pada skala 1:1. Tidak ada pembesaran pada web tersebut. Selain mengatur viewport pada halaman web, kita harus memperhatikan beberapa hal terutama ketika mengatur elemen HTML pada CSS. Agar halaman web menjadi responsive, pengaturan dimensi (width dan height) harus stabil atau teratur. Dengan kata  lain, pengaturan width menggunakan satuan pesen (%) dan height harus auto.  
Dan pada CSS kita dapat menambahkan Fitur media query. Fitur media query adalah fitur yang digunakan sebagai filter terhadap lebar layar device kita. Berikut ini contoh kode penggunaan media query. (@media only screen and (min-width: 780px) {  body {   background:black; } }) Darikode di atas dapat kita artikan bahwa background dari body akan berwarna hitam ketika lebar layar minimal 768 pixel (background berwarna hitam ketika lebar layar berukuran > 780 pixel).


query(desktop
![alttext](https://github.com/Anandarafi/latihan-CSSResponsive-Anandarafimanullah-XRPL4-07/blob/master/query(desktop).PNG)
query(tablet)
![alttext](https://github.com/Anandarafi/latihan-CSSResponsive-Anandarafimanullah-XRPL4-07/blob/master/query(tablet).PNG)
scrip3(tablet)
![alttext](https://github.com/Anandarafi/latihan-CSSResponsive-Anandarafimanullah-XRPL4-07/blob/master/scrip3(tablet).PNG)
scrip3(desktop)
![alttext](https://github.com/Anandarafi/latihan-CSSResponsive-Anandarafimanullah-XRPL4-07/blob/master/scrip3(desktop).PNG)
script(desktop)
![alttext](https://github.com/Anandarafi/latihan-CSSResponsive-Anandarafimanullah-XRPL4-07/blob/master/script(desktop).PNG)
script(tablet
![alttext](https://github.com/Anandarafi/latihan-CSSResponsive-Anandarafimanullah-XRPL4-07/blob/master/script(tablet).PNG)
script1(desktop)
![alttext](https://github.com/Anandarafi/latihan-CSSResponsive-Anandarafimanullah-XRPL4-07/blob/master/script1(desktop).PNG)
script1(tablet)
![alttext](https://github.com/Anandarafi/latihan-CSSResponsive-Anandarafimanullah-XRPL4-07/blob/master/script1(tablet).PNG)
script2(tablet)
![alttext](https://github.com/Anandarafi/latihan-CSSResponsive-Anandarafimanullah-XRPL4-07/blob/master/script2(tablet).PNG)
script2(desktop)
![alttext](https://github.com/Anandarafi/latihan-CSSResponsive-Anandarafimanullah-XRPL4-07/blob/master/script2(desktop).PNG)
script4(desktop)
![alttext](https://github.com/Anandarafi/latihan-CSSResponsive-Anandarafimanullah-XRPL4-07/blob/master/script4(desktop).PNG)
script4(tablet)
![alttext](https://github.com/Anandarafi/latihan-CSSResponsive-Anandarafimanullah-XRPL4-07/blob/master/script4(tablet).PNG)
