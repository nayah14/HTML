# Struktur Dasar Html
## Contoh penulisan HTML
```HTML
<!DOCTYPE html>
<html>
    <head>
        <title>Nayah comel</title>
    </head>
    <body>
        <p>Tidak ada yang tidak mungkin untuk orang yang mau berusaha</p>
        chuakss....
    </body>
</html>
```
- Tag <!DOCTYPE html> memberitahukan web browser bahwa dokumen HTML adalah versi 5.
- Tag pembuka `<html>` menandai awal sebuah dokumen HTML sampai dengan tag penutup `</html>`
- Tag pembuka `<head>` berisi informasi tentang halaman  HTML sampai dengan tag penutup `</head>`,biasanya dalam tag head terdapat tag `<title>` untuk memberikan informasi judul dihalaman HTML 
- Apapun tag yang berada diantara tag pembuka `<body>` sampai dengan tag penutup `</body>` akan tampil diweb browser.
## Contoh tampilan di browser

![](img/head%20contoh.png)
Gambar diatas adalah contoh *title* yang di tampilkan di browser

![](img/Screenshot(25).png)

Gambar diatas adalah contoh kode *body paragraf* yang ditampilkan di browser
# Anatomi Elemen HTML 
Elemen Adalah suatu kesatuan dari sebuah tag yang dimulai dari tag pembuka hingga ke tag penutup. Elemen HTML secara garis besar terdiri dari tiga bagian yaitu tag pembuka, komen/isi tag, dan tag penutup

```html
<a href="https://www.instagram.com/p/CzldX7jRYpuo6_xCMpU5-Eumlnp5L432zexXQo0/?igsh=MWZpZ3I4M2g5azFy">Klik Instagram Saya</a>
```
- Tag `<a>` adalah elemen dasar untuk membuat link di HTML dan termasuk tag pembuka. 
- `href` adalah nama atribut digunakan untuk menghubungkan antara halaman web dan termasuk tag pembuka.
- "https://www.instagram.com/p/CzldX7jRYpuo6_xCMpU5-Eumlnp5L432zexXQo0/?igsh=MWZpZ3I4M2g5azFy" adalah nilai atribut yang digunakan untuk mengakses sebuah link dan termasuk tag pembuka. 
- `Klik Instagram saya` adalah konten/isi tag yg digunakan untuk kata kunci atau judul untuk memudahkan seseorang mengakses link yang di tampilkan .
- `</a>` adalah tag penutupnya.

##  Contoh tampilan di browser

![](img/Screenshot(26).png)

# Tag Dasar 
## Heading
Heading Merupakan **Tag HTML yang digunakan untuk menunjukkan bagian penting pada halaman website dan memiliki enam tingkatan yang berurutan yaitu H1 hingga H6**.Semakin besar tingkat headingnya semakin kecil juga tulisannya.
### Contoh Penulisannya
```HTML
<h1>Qoute Hari ini</h1>
<h2>Qoute Hari ini</h2>
<h3>Qoute Hari ini</h3>
<h4>Qoute Hari ini</h4>
<h5>Qoute Hari ini</h5>
<h6>Qoute Hari ini</h6>
```
### Contoh Tampilan di Browser
 ![[Screenshot (27).png]]

## Paragraf
Paragraf adalah kumpulan dari beberapa kalimat. Pada web, Paragraf biasanya digunakan untuk menampilkan teks atau artikel.Didalam paragraf terdapat kode `<p>`,`<b>`,`<u>`,`<i>`,`<br>`
### Penjelasan Tag Paragraf
- `<p>`digunakan untuk pengaturan antara halaman diweb 
- `<b>`digunakan agar teks pada halaman tebal
- `<u>`digunakan untuk memberikan garis bawa pada halaman
- `<i>`digunakan agar teks miring pada halaman
- `<br>`digunakan untuk membuat baris baru
### Contoh Penulisannya Paragraf
```html
		<p>Nayah paling comel</p>

        <b>Nayah paling comel</b>

        <u>Nayah paling comel</u>

        <i>Nayah paling comel</i>

        <br>Nayah paling comel
```

### Contoh Tampilan Paragraf Di browser 
![](img/Screenshot%20(28).png)

- Baris pertama adalah contoh pemakaian `<p>`
-  Baris kedua adalah contoh pemakaian `<b>`
-  Baris ketiga adalah contoh pemakaian `<u>`
-  Baris keempat adalah contoh pemakaian `<i>`
-  Baris keenam adalah contoh pemakaian `<br>`

#### Align
Atribut `align` digunakan untuk mengatur perataan teks padaa halaman HTML. Elemen `<p>` dapat menggunakan atribut `align="left"`,akan menghasilkan paragraf dengan perataan teks disebelah kiri.Nilai atribut `<align="right"` akan menghasilkan paragraf dengan perataan teks disebelah kanan.Nilai atribut `<align="center"` akan menghasilkan paragraf dengan perataan teks tengah.Nilai atribut `<align="justify"`akan menghasikan paragraf dengan perataan teks sisi kiri dan kanan.
##### Contoh Programnya
```html
 <h3> Belajar Menggunakan elemen Tag HTML P</h3>

     <P align="left">

        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Doloribus, saepe sapiente? Aperiam quidem ipsum nisi numquam sapiente iusto sint porro labore voluptatem, harum, consequuntur assumenda asperiores laudantium itaque? Repellendus, reiciendis?

     </P>

     <p align="right">

        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fuga nisi nemo totam, quod rerum a quisquam officiis amet natus dolore veritatis illo, recusandae libero quidem itaque ducimus quos deserunt molestiae.

     </p>

     <p align="center">

        Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis quaerat, non, mollitia voluptas, temporibus dignissimos cupiditate iure libero assumenda adipisci similique delectus sint consectetur placeat eos eius aut! Expedita, doloribus!

     </p>

     <p align="justify">

        Lorem ipsum dolor sit amet consectetur adipisicing elit. Suscipit blanditiis amet laborum dolor odio, quas ex illo maiores omnis, veritatis voluptas, nihil molestiae corporis. Eos fuga hic ab vitae explicabo.

    </p>
```
##### Contoh Tampilan dibrowser
![](img/Screenshot%20(29).png)

## Komentar
HTML juga mempunyai tag khusus untuk komentar.Untuk membuat komentar diHTML kita menggunakan awalan "`<!--`" dan penutup "`-->`".
>[!faq]- Komentar?
>Komentar tidak akan ditampilkan pada halaman website namun programer biasanya menggunakan komentar untuk memperjelas kode program.

### Contoh Program Komentar
```html
<!-- Ini komentar, tidak akan tampil di browser -->
<p>ini bukan komentar dan akan tampil di browser</p>

```
### Contoh Tampilan di Browser
![](img/Screenshot(30).png)

## List
List adalah fungsi dalam HTML yang digunakan untuk menampilakn daftar dari sesuatu.Dalam HTML,Tag list terdiri dari 2 jenis,`<ol>` **ordered list** (berurutan) dan `<ul>` **unordered list**  (tidak berurutan).Ordered list akan ditampilkan dengan angka atau huruf,sedangkan unordered list dengan bulatan atau kotak ataupun simbol lainnya.
>[!faq]- List? 
> Untuk menampilkan list dalam HTML  dapat menggunakan tag `<li>`...`</li>` namun perlu menyisipkan elemen `<ol>`...`</ol>` atau `<ul>`...`</ul>` kedalam elemen `<li>`tersebut untk membuat daftar list.
### Contoh Program
```html
<h1>Cara membuat kopi</h1>
   <p>Bahan Bahan</p>
   <ul>
    <li>2sdt kopi bubuk</li>
    <li>2sdt gula pasir</li>
    <li>Air panas secukupnya</li>
   </ul>
   <p>Langkah Langkah</p>
   <ol>
    <li>Masukkan bubuk kopi dan gula kedalam cangkir</li>
    <li>Seduh dengan air mendidih</li>
    <li>aduk dan siap dihidangkan</li>
   </ol>
``` 
### Contoh Tampilan di Browser
![](img/Screenshot(31).png)

## Link  
Link dapat ditemukan dihampir semua halaman web. Link/tautan memungkinkan sebuah teks yang ketika diklik akan pindah kehalaman lainnya.HTML menggunakan tag `<a>`untuk keperluan ini.Link ditulis dengan `<a>`yang merupakan singkatan cari anchor (jangkar)
>[!faq]- Href?
>setiap tag `<a>`setidaknya memiliki sebuah atribut `href` dimana `href` berisi alamat yang dituju.`href` adalah singkatan hypertext reference

Atribut penting lainnya dari tag `<a> `adalah `target`.Atribut target menentukan tempat untuk membuka dokumen yang ditautkan.Atribut `target`memiliki beberapa nilai salah satunya `_blank`yang berfungsi untuk membuka tautan ditab baru.
### Contoh Program Link
```html
<h3>Menggunakan Tag Anchor</h3>
<a href="https://www.google.com" target="_blank">Klik disini untuk kegoogle</a><br>
<a href="halaman_lain.html">Klik disini untuk kehalaman lain yang saya buat!</a>
```
### Contoh Tampilan Di Browser
![](img/Screenshot(32).png)
## Multimedia
### **1. Gambar** 
Dalam HTML,gambar didefinisikan dengan tag `<img>`.Tag `<img>` adalah tag kosong,hanya berisi atribut saja,dan tidak memiliki tag penutup.

Atribut `alt`menyediakan teks alternatif untuk gambar,jika pengguna karena beberapa alasan tidak dapat melihatnya (karena kondisi lambat,kesalahan pada  atribut`src`,atau jika web browser telah disetting untuk tidak menampilkan gambar).jika browser tidak dapat menemukan gambar,maka akan muncul nilai pada atribut `alt`

Dalam tag `<img>`terdapat juga atribut `width`dan `height`untuk mengatur ukuran gambar,pada versi HTML5 standar satuan ukuran gambar adalah pixel.
- misalnya dalam folder root terdapat file gambar bernama logo.png. Untuk menampilkan gambar tersebut kita hanya perlu mengisi nama gambar beserta jenis ekstensi file gambar kedalam atribut `src`,contohnya `src="logo.png"`
- untuk menampilkan gambar dari internet carilah link gambar yang akan ditampilkan lalu masukkan dalam nilai atribut `src`,contohnya **https://namasitus.com/gambar.png**

```html
<img src="gmbrhtml.jpg" alt="./img/Gambar HTML" width="150" height="150">
```

 #### **Contoh Tampilan di Browser:**
![](img/Screenshot(33).png)
Gambar diatas adalah contoh tampilan di web browser

![](img/Screenshot(34).png)
Gambar diatas adaalah contoh  dimana file  gambar `gmbrhtml`terletak di dalam file `visual studio code` agar programnya bisa terjalankan  

### **2. Video**
Fitur HTML 5 mencakup dukungan audio dan video asli tanpa memerlukan Flash. Tag `<audio>` dan `<video>` pada HTML 5 mempermudah penambahan media ke dalam halaman web. Yang penting untuk diatur pada tag ini adalah atribut src yang berfungsi untuk mengidentifikasi sumber media. Selain itu, terdapat pula atribut controls agar pengguna dapat memutar dan menjeda media.

```html
<video src="nayah comel.mp4"  width="300" height="200" controls>Browser anda tidak mendukung elemen <video>.   
</video>
```

Contoh Tampilan Dibrowser:
![](img/Screenshot(35).png)
Gambar diatas adalah contoh tempat file video tersebut disimpan.Tempat penyimpanan nya berada di file teks editor tersebut

![](img/Screenshot(36).png)
Gambar diatas adalah contoh tampilan di Browser.

### 3. Audio
Setiap yang telah dibahas sebelumnya bahwasanya tag `<audio>` merupakan bagian fitur HTML 5 untuk menampilkan audio asli dihalaman web tanpa memerlukan flash sebagaimana pada HTML versi 4.Yang penting untuk diatur pada tag ini adalah atribut `src` yang berfungsi untuk mengidentifikasi sumber media.Selain itu,terdapat pula atribut `controls` agar pengguna dapat memutar atau menjeda media

```html
<audio src="./img/nayah comel.mp4" controls>``
```

Contoh tampilan di browser:

![](img/Screenshot(37).png)

### 4. Halaman Web Lain
Elemen `<iframe>` dapat digunakan untuk menampilkan halaman website lain dalam suatu website. Atau menampilkan dokumen HTML lain dalam sebuah website. Mudahnya, bisa dibilang website dalam website.

 >[!faq]-  Halaman web?
 >Contoh penggunaannya seperti ini. Jika kita mempunyai website sekolah, lalu di website tersebut ingin menampilkan alamat dalam google maps sekolah. Agar memudahkan pengunjung website, kita bisa langsung tampilkan saja halaman sekolah yang ada di google maps.

Dalam tag `iframe` ada beberapa atribut yang penting seperti:

- `src`, untuk mencari sumber halaman html atau web yang akan ditampilkan di dalam frame
- `width` dan `height`, untuk mengatur ukuran panjang dan lebar dari frame.

```html
<iframe src="http://smkn7makassar.sch.id/" width="1250" height="550"></iframe>
```

Contoh Tampilan di Browser:
![](img/Screenshot(38).png)


## Tabel
Tabel dalam HTML didefinisikan dengan tag `<table>`
- Setiap baris tabel didefinisikan dengan tag `<tr>`
- Header (judul) tabel didefinisikan dengan tag `<th>`. Secara default, header tabel memiliki teks tebal dan berada di tengah.
- Data tabel/sel didefinisikan dengan tag `<td>`. Karena sel merupakan bagian terkecil dari tabel maka dari itu tag ini selalu berada di dalam tag `<tr>`.

**Contoh:**
```html
<!DOCTYPE html>

<html>

    <head>

     <title>JUDUL HALAMAN </title>

    </head>

    <body>

        <table border="1">

            <tr>

                <th>Nama</th>

                <th>Asal Institusi</th>

            </tr>

            <tr>

                <td>Nayah Comel</td>

                <td>Universitas Gajah Madah</td>

            </tr>

            <tr>

                <td>Rezky Awalya RUSTAM</td>

                <td>SMKN 7 Makassar</td>

            </tr>

            <td>Andi Ashadelah Maharani ANIL</td>

            <td>SMKN 7 Makassar</td>

        </tr>

            </table>

    </body>

</html>
```

>[!faq]-  Table?
>Perhatikan bahwa pada tag `<table>` terdapat sebuah atribut border. Atribut border digunakan untuk memberikan nilai garis tepi dari tabel. Nilai ini dalam ukuran pixel. border=”1”, berarti kita mengistruksikan kepada web browser bahwa tabel tersebut akan memiliki garis tepi sebesar 1 pixel. Jika tidak ditambahkan, secara default tabel tidak memiliki garis tepi

**Contoh Tampilan di Browser:**
![](img/Screenshot(39).png)

Selain itu, terdapat pula beberapa atribut tabel yang penting untuk diketahui yaitu:
- `rowspan` merupakan atribut HTML yang berfungsi untuk menggabungkan beberapa **baris (ke bawah)**.
- `colspan` atau `column span` merupakan atribut HTML yang berfungsi untuk menggabungkan beberapa *kolom (ke samping).*
- `width` berfungsi untuk mengatur *lebar* tabel yang nilainya didefinisikan dalam satuan pixel secara default.
- `height`  berfungsi untuk mengatur *tinggi* tabel yang nilainya didefinisikan dalam satuan pixel secara default.
- `align` berfungsi untuk mengatur *perataan teks* pada tabel. Nilai atribut yang dapat diberikan yaitu `left` untuk perataan teks ke kiri, `right` untuk perataan teks ke kanan, dan `center` untuk perataan teks ke tengah.
- `border`berfungsi sebagai pembatas antar tabel

**Contoh:**
```html
<table border="1">

    <tr>

         <th rowspan="2">Nama</th>

       <th colspan="2">Asal Institusi</th>

    </tr>

    <tr>

       <th width="100">Sekolah</th>

       <th width="100">Kampus</th>

    </tr>

    <tr>

       <td>Nur Inayah Athaillah</td>

       <td>SMAN 17 Makassar</td>

       <td>Universitas Gajah Madah</td>

    </tr>

    <tr>

        <td>Andi Ashadelah Maharani ANIL</td>

        <td rowspan="2">SMKN 7 Makassar</td>

        <td align="center" rowspan="2">-</td>

    </tr>

    <tr>

         <td>St Nurhazisa</td>

    </tr>

    <tr>

         <td>Rezky Awalya RUSTAM</td>

         <td>SMK 7 MAKASSAR</td>

         <td>Universitas Negeri Makassar</td>

    </tr>

</table>
```

Contoh Tampilan Di Browser:
![](img/Screenshot(40).png)

>[!faq]- Rowspan?
>Perhatikan pada konten elemen `<td>` yang berisi **Rezky Awalya RUSTAM**, hanya terdapat satu elemen `<td>` disana. Hal ini dikarenakan konten elemen `<td>` sebelumnya yaitu SMKN 7 Makassar
>
>Pada data Andi Ashadelah Maharani ANIL mengandung atribut rowspan dengan nilai 2 yang secara otomatis mengisi data di bawahnya yakni data **Rezky Awalya RUSTAM**. Nilai 2 menunjukkan bahwa ada dua baris yang digabungkan menjadi satu

>[!faq]- Colspan?
>Konsep ini juga sama dengan apa yang terjadi pada `<th rowspan`="2">Nama`</th>`dan `<th colspan`="2">Asal Institusi`</th>`

## Form
Elemen `<form>` HTML digunakan untuk mendefinisikan *form* yang digunakan untuk mengumpulkan inputan dari pengguna *website*. Tag ini digunakan untuk mengkoleksi inputan dari user, konsep ini sama seperti konsep formulir di dunia nyata. 

>[!faq]- Form
> Dengan kata lain tag `<form>` merepresentasikan sebuah **“formulir”** di mana satu formulir bisa memiliki banyak kolom isian.

Form HTML berisikan elemen-elemen `form` lainnya. Elemen `<form>` digunakan untuk menampung macam-macam elemen yang berkaitan dengan sebuah `form`, seperti `text fields`, `checkbox`, `radio button`, tombol `submit`, dan banyak lagi yang dapat diedit kemudian ditulis untuk dikirim pada sebuah *server* untuk selanjutnya diproses guna mendapatkan informasi tertentu dari atau untuk *user*.

Umumnya, sebuah *website* selalu memiliki fitur *form*, contoh paling umum yang sering kita temui adalah seperti *form login*, *form sign up*, *form* komentar di suatu *blog*/media.

### Input
 Elemen `<input>` adalah elemen `form` yang paling penting. Elemen `<input>` dapat ditampilkan dalam beberapa cara, tergantung pada nilai atribut `type` yang digunakan. Berikut adalah beberapa contoh nilai dari atribut `type` :
    - `text` digunakan untuk mengambil isian berupa **teks**. Contohnya seperti nama.
    - `password` digunakan untuk mengambil isian berupa **kata sandi** atau sesuatu yang bersifat rahasia. Tipe ini akan mengubah semua karakter yang diketikkan ke dalam karakter bulat.
    - `radio` digunakan sebagai kolom isian bertipe **pilihan** yang menawarkan beberapa opsi kepada *user* namun tetapi **hanya satu opsi saja** yang boleh dipilih. Contohnya seperti jenis kelamin atau agama.
        
>[!faq]- Radio? 
>Perlu diperhatikan bahwa untuk penggunaan tipe `radio` yang berkategori set pilihan yang sama mengharuskan nilai `name` -nya juga sama.
        
Opsi *default* dapat dilakukan dengan menambahkan atribut `checked` pada elemen opsi yang dijadikan sebagai opsi *default*.
- `checkbox` digunakan untuk memberikan **daftar pilihan dalam satu set opsi**. *User* dapat memilih satu atau bahkan **lebih dari satu pilihan** pada tipe ini. Hal ini berbeda dengan tipe sebelumnya yaitu `radio` yang hanya memungkinkan *user* untuk memilih satu pilhan saja. Contoh penggunaan `checkbox` seperti daftar makanan kesukaan, daftar olahraga yang tidak disukai, dan yang semisalnya.
        
>[!faq]- Checkbox? 
>Perlu diperhatikan bahwa untuk penggunaan tipe `checkbox` yang berkategori set pilihan yang sama mengharuskan nilai `name` -nya juga sama.
        
- `number` digunakan untuk membatasi isian *user* hanya pada karakter **numerik** saja. Browser akan menambahkan dua buah tombol atas dan bawah untuk mengubah angka isian.
Beberapa atribut untuk tipe `number`:
    - `min` - menentukan angka minimal
    - `max` - menentukan angka maksimal
    - `step` - menentukan kelipatan (nilai yang tidak sesuai kelipatan tidak bisa di-*input*, dan *default* dari atribut ini adalah `1`)

- `date` digunakan untuk memberikan isian berupa **tanggal**. Atribut `min` dan `max` dapat pula difungsikan pada tipe ini untuk mengatur tanggal minimal dan tanggal maksimal yang diinginkan. Nilai `min` dan `max` tersebut ditulis dengan format: `YYYY-MM-dd`.
- `file` digunakan untuk memungkinkan pengguna memuat ***file**.* Atribut `accept` juga dapat disisipkan pada tipe ini dengan maksud untuk mengatur *file* apa saja yang boleh di-*upload*. Beberapa contoh *value* dari atribut `accept` yaitu:
    - `accept**=**"image/png,image/jpg,image/jpeg"` untuk file gambar seperti `png`, `jpg`, atau `jpeg`    
    - `accept=".pdf"` untuk file pdf
    - `accept=".doc, .docx"`  untuk file `doc` atau `docx`
    - `accept=".ppt, .pptx"`  untuk file `ppt` atau `pptx`
        
- `submit` ditampilkan dalam bentuk **tombol untuk mengirim data** pada `<form>` yang menjadi pembungkusnya. Atribut `value` digunakan untuk mengisi teks yang ingin ditampilkan pada tombol.
- `reset` berguna untuk **mengembalikan *state* (keadaan) atau data dari suatu *form* ke nilai awalnya**. Jika nilai awal sebuah input adalah kosong, maka ketika direset ia akan kembali kosong. Tapi jika nilai awalnya sudah terisi sesuatu, maka ketika direset datanya akan kembali seperti yang sudah diset sebelumnya.
- `button` berguna untuk membuat **inputan berupa sebuah tombol**. Tombol ini nantinya bisa difungsikan sesuai dengan keinginan dari pengembang web.


### Label
Elemen `<label>` memiliki fungsi khusus untuk **melabeli sebuah kolom inputan**. Ketika *screen reader* membaca konten halaman HTML, lalu menemukan sebuah inputan, ia akan membaca label yang bersangkutan.
Fungsi lain dari tag `<label>` adalah ketika kita mengklik  label, maka browser akan meletakkan fokus pada kolom isian yang terhubung dengannya. Syarat yang perlu diperhatikan yaitu dengan menghubungkan sebuah `<label>` dan `<input>` dengan atribut `for` untuk `label`, dan atribut `id` pada `<input>` dengan nilai untuk kedua atribut tersebut mesti sama persis.
    
### Select
Elemen `<select>` berguna dalam mendefinisikan sebuah tombol ***dropdown*** yang dimana *user* dapat memilih salah satu dari banyak pilihan. 
    
   >[!faq]- Select?
   >Elemen `<select>` nantinya berperan sebagai kontainer atau pembungkus dari elemen `<option>` yang berperan sebagai daftar pilihan atau opsi.
    
Elemen `<select>` hampir mirip fungsinya dengan `<input type=”radio">` akan tetapi baiknya elemen `<select>` digunakan untuk memilih satu pilihan yang terdapat banyak opsi di dalamnya, sedangkan `<input type=”radio">` lebih baiknya untuk digunakan jika  *user* diarahkan memilih hanya satu pilihan yang opsi pilihannya tidak terlalu banyak. Contoh penggunaan elemen ini seperti memasukkan pilihan berupa asal daerah atau yang semisalnya.
    
Penting untuk diketahui  bahwasanya opsi yang aktif secara *default* adalah adalah opsi yang pertama. Akan tetapi, kita bisa mengatur opsi mana yang aktif secara *default* dengan menambahkan atribut `selected` pada suatu `<option>` yang ingin dijadikan sebagai opsi *default*. 
    
### Text Area
Elemen `<textarea>` berguna untuk mengambil inputan *user* berupa teks yang dapat memuat **lebih dari satu baris**. Jika dibandingkan dengan elemen `<input>` teks biasa, elemen `<textarea>` memiliki ukuran tinggi yang lebih besar. Element `textarea` bisa diisi lebih dari satu baris dengan menekan enter.
    
Atribut yang dapat digunakan untuk mengatur kuran dari `textarea` yaitu `rows` untuk jumlah baris, sedangkan atribut `cols` untuk lebarnya.
    
### Button
Elemen `<button>` yang berada di dalam sebuah `form` akan otomatis dianggap sama fungsinya seperti `<input type="submit">`. Jika ingin membuat tombol biasa yang tidak men-*submit* `<form>` dapat dilakukan dengan menambahkan atribut `type="button"`.

  **Beberapa atribut yang digunakan pada contoh di atas yang perlu untuk diperjelas yaitu sebagai berikut:**
- name - digunakan sebagai nama variabel yang akan diproses oleh web server (contoh menggunakan PHP)
- required - digunakan untuk memastikan bahwa pengguna harus memasukkan nilai pada input tersebut sebelum dapat melakukan proses submit formulir
- placeholder - menuliskan teks pada elemen input. Placeholder sangat bermanfaat untuk memberikan teks bantuan kepada user untuk inputan form yang kompleks
- value - menentukan nilai awal dari sebuah elemen input
- disabled - digunakan untuk menonaktifkan inputan pada elemen yang diberi atribut ini
- ID untuk mengantar kek kotak form

**CONTOH PROGRAM:**
```HTML
<h1>Formulir Pendaftaran</h1>
<form action="">
    <div>
      <label for="nama-lengkap"><b>Nama Lengkap:</b></label><br>
      <input type="text" id="nama-lengkap" name="nama_lengkap" placeholder="Masukkan nama lengkap" required>
     </div>

     <div>
       <label for="password"><b>Password:</b></label><br>
       <input type="password" id="password" name="password" placeholder="Masukkan password" required>
      </div>

      <div>
        <b>Jenis Kelamin:</b><br>
        <input id="lk" type="radio" name="jenis_kelamin" checked>
        <label for="lk">Laki-Laki</label>

        <input id="pr" type="radio" name="jenis_kelamin">
        <label for="pr">Perempuan</label>
      </div>

      <div>
        <label for="isian-usia"><b>Usia:</b></label><br>
        <input type="number" id="isian-usia" name="usia" min="17" max="25" value="19" required> Tahun
      </div>

      <div>
         <label for="tgl-ijazah"><b>Tanggal Ijazah:</b></label> <br>
         <input type="date" id="tgl-ijazah" name="tgl_ijazah" min="2021-01-01" value="2023-06-20" required>
      </div>

      <div>
         <label for="opsi-agama"><b>Agama:</b></label><br>
         <select id="opsi-agama" name="agama" required>
           <option disabled>---Pilih Agama----</option>
           <option value="islam">Islam</option>
           <option value="kristen">Kristen</option>
           <option value="katolik">Katolik</option>
           <option value="hindu">Hindu</option>
           <option value="buddha">Buddha</option>
           <option value="atheis" disabled>Atheis</option>
          </select>
       </div>

       <div>
          <label for="alamat"><b>Alamat:</b></label> <br>
          <textarea id="alamat" name="alamat" cols="25" rows="5" placeholder="Harap masukkan alamat secara lengkap" required></textarea>
       </div>

       <div>
          <b>Kemampuan Berbahasa Asing:*</b><br>
	        <input type="checkbox" id="inggris" name="bahasa_asing">
	        <label for="inggris">Inggris</label>

          <input type="checkbox" id="arab" name="bahasa_asing">
          <label for="arab">Arab</label>
                
          <input type="checkbox" id="jepang" name="bahasa_asing">
          <label for="jepang">Jepang</label>
       </div>

       <div>
          <label for="isian-foto"><b>Foto 4x6:*</b></label><br>
          <input type="file" id="isian-foto" name="foto" accept="image/png,image/jpg,image/jpeg">
       </div>

       <br>
       <input type="submit" value="Kirim">
       <input type="reset" value="Batal">
       <i>*opsional (tidak wajib diisi)</i>
</form>
```

**HASIL BROWSER:**
![](img/Screenshot(41).png)

### *Bagaimana Cara Memproses Form?*
Ketika sebuah `<form>` disubmit, baik menggunakan elemen `<button>` mau pun `<input type="submit">,` browser akan mengirimkan data tersebut kepada URL yang didefinisikan pada atribut action di dalam tag form.

Ada pun jika atribut action tidak didefinisikan, maka browser akan menggunakan URL sekarang sebagai tujuan pengiriman data.

Contoh:
```html
<form action="/proses-pendaftaran">
  ...
</form>
```
Pada contoh di atas, ketika form di-submit, browser akan mengirimkan data yang ada  menuju URL /proses-pendaftaran.


**Apa yang terjadi pada URL /proses-pendaftaran?**
Pada URL tersebut terdapat sebuah aplikasi/program yang berjalan di server (bukan di browser). Tugas dari program tersebut adalah mengelola data yang dikirim seperti misalnya menyimpan data tersebut ke dalam sebuah database.

Bahasa yang umum digunakan di dalam server adalah python, nodejs, PHP, dan lain sebagainya.

Untuk mendapatkan gambaran lebih jelas, sebenarnya akan dijelaskan pada modul selanjutnya yang berkaitan dengan materi PHP atau juga bisa dengan membaca tutorial berikut:



# Tugas Latihan Membuat tabel Hari dan Bulan
```html
<table border="2">

    <tr>

        <td colspan="2" bgcolor="green" width="200">Nama Hari</td>

        <td colspan="2"bgcolor="green" widht="200">Nama Bulan</td>

    </tr>

    <tr>

        <td>senin</td>

        <td>selasa</td>

        <td>april</td>

        <td rowspan="2" align="center">juni</td>

    </tr>

    <tr>

        <td>rabu</td>

        <td>kamis</td>

        <td>mei</td>

    </tr>

</table>
```

**HASIL:**
![](img/Screenshot(42).png)

## Analisis
- `<table border="2"> </table>`table digunakan untuk membuat tabel pada halaman html dan harus menggunakan penutup yaitu `</table`,border yaitu atribut yg digunakan untuk mengatur ketebalan garis pinggir dari tabel,`2`adalah ketebalan tabelnya.
- `<tr>` `</tr>`digunakan untuk membuat baris baru dalam tabel
- `<td colspan="2" bgcolor="green" width="200">Nama Hari</td>`colspan adalah sebuah atribut html yg menyatukan 2 baris tabel menjadi 1 baris,`bgcolor` digunakan untuk mewarnai kolomnyaa,`width` digunakan untuk mengatur lebar pada tabel
- `<td colspan="2"bgcolor="green" widht="200">Nama Bulan</td>`colspan adalah sebuah atribut html yg menyatukan 2 baris tabel menjadi 1 baris,`bgcolor` digunakan untuk mewarnai kolomnyaa,`width` digunakan untuk mengatur lebar pada tabel
- ` <td>senin</td>` `td` digunakan untuk membuat kolom disetiap baris pada tabel
- `<td>selasa</td>` `td`digunakan untuk membuat kolom disetiap baris pada tabel
- `<td>april</td>` `td`digunakan untuk membuat kolom disetiap baris pada tabel
- `<td rowspan="2" align="center">juni</td>` `rowspan` digunakan untk menyatukan 2 kolom menjadi 1 kolom
- `<td>rabu</td>`  `td`digunakan untuk membuat kolom disetiap baris pada tabel
- `<td>kamis</td>` `td`digunakan untuk membuat kolom disetiap baris pada tabel
- `<td>mei</td>` `td` digunakan untuk membuat kolom disetiap baris pada tabel

# Tugas Latihan Membuat Form
```html
<form>

    <label for="nama">

        Nama:

    </label>

    <input type="text" required id="nama"><br>

  

    <label for="password">

        Password:

    </label>

    <input type="password" required id="password"><br>

  

    <label>

        Jenis Kelamin:

    </label>

    <input type="radio"name="Lk"

    <label>laki-laki</label>

    <input type="radio"name="Lk"

    <label>perempuan</label><br>

  

    <label>

        coding pemograman yang dikuasai:

    </label>

    <input type="checkbox"

    name="coding">web

    <input type="checkbox"

    name="coding">mobile

    <input type="checkbox"

    name="coding">desktop <br>

  

    <br/>

    pesan anda:

    <textarea></textarea>

    <br/>

  

    <input type="submit"value="kirim">

    <input type="reset"value="ulang">

</form>

```

**Hasil:**
![](img/Screenshot(44).png)

**Analisis:**
- `<form>` `</form>` adalah atribut untuk membuat form
- `for` untuk mengarahkan teks kekolom dan harus sama dengan id.
- `name` adalah sebuah atribut yg hanya biisa memilih 1
- `input type`adalah atribut yg digunakan untuk menampilkannya teks nya seperti nama,passwoard dan sebagainya
- `value` adalah isi dari sebuah button


# Analisis Ujian Html
## Index
```html
<!DOCTYPE html>

<html>

<head>

    <title>ujian</title>

</head>

<body>

    <table border="0" height="100%" width="100%">

        <tr>

            <td width="100%" align="=left" bgcolor=" yellow" height="50px">Flower shop</td>

        </tr>

    </table><br>

  

    <table align="center">

        <tr>

            <th colspan="2" align="center">Selamat datang di Flower shop <br><br>

            <img src="3.jpg" width="410" height="410" align="center"><br><br>

            <a href="file:///C:/Users/ASUS/Documents/Visual%20Studio%20Code/Ujian%20HTML/order%20bunga.html" target="_blank"><input type="submit" value="Order now!"</a>    

            </th>

        </tr>

    </table><br>

    <table border="0" height="100%" width="100%">

        <tr bgcolor="aqua" >

            <td align="center"><a href="file:///C:/Users/ASUS/Documents/Visual%20Studio%20Code/Ujian%20HTML/list%20bunga.html" target="_blank">Lihat Daftar Bunga</a></td>

            <td align="center"><a href="file:///C:/Users/ASUS/Documents/Visual%20Studio%20Code/Ujian%20HTML/order%20bunga.html" target="_blank">Pesan Bunga </a></td>

        </tr>

    </table>

</body>

</html>
```

### Analisis 
- `<table border="0" height="100%" width="100%">` adalah atribut yang digunakan untuk menentukan apkah tabel tersebut memiliki garis pembatas disekitar sel dan kolomnya.`Height` dan `width `adalah besar lebar dan tingginya.
- `<td width="100%" align="=left" bgcolor=" yellow" height="50px">Flower shop</td>`  `align` adalah perataan teks dalam program, `bgcolor` adalah warna baground pada teksnya
- `<table>` adalah atribut pembuka untuk membuat table
- `<th colspan="2"` adalah atrbut untuk menggabungkkan 2kolom/lebih 
- `<img src` digunakan untuk menambahkan gambar pada program
- `<br>` digunakan untuk membuat baris baru
- `<a` digunakan untuk menambahkan link halaman web
- `<target=_blank` digunakan untuk judul pada link halaman web tersebutt
## List Bunga
```html
<!DOCTYPE html>

<html>

<head>

    <title>List Bunga</title>

</head>

<body>

    <h1>List Bunga</h1>

    <table border="1">

        <div>

            <tr>

                <td>Bunga 1 <br>

                 <img src="1.jpg" height="70" width="70"></td>

                 <td>

                    <ul>

                        <li>Asal: <b>Gunung Latimojong</b></li>

                        <li>Keharuman: <b>Tahan Lama</b></li>

                        <li>Harga: <b>Rp.75.000</b></li>

                    </ul>

                 </td>

  

                 <td>Bunga 4 <br>

                    <img src="4.jpg" height="70" width="70"></td>

                    <td>

                       <ul>

                           <li>Asal: <b>Danau Tanralili</b></li>

                           <li>Keharuman: <b>Sedang</b></li>

                           <li>Harga: <b>Rp.50.000</b></li>

                       </ul>

                    </td>

            </tr>

        </div>

  

                <div>

                    <tr>

                    <td>Bunga 2 <br>

                        <img src="2.jpg" height="70" width="70"></td>

                        <td>

                           <ul>

                               <li>Asal: <b>Taman Macan</b></li>

                               <li>Keharuman: <b>Biasa</b></li>

                               <li>Harga: <b>Rp.15.000</b></li>

                           </ul>

                        </td>

  

                        <td>Bunga 5 <br>

                            <img src="5.jpg" height="70" width="70"></td>

                            <td>

                               <ul>

                                   <li>Asal: <b>Gunung Bawakaraeng</b></li>

                                   <li>Keharuman: <b>Tahan Lama</b></li>

                                   <li>Harga: <b>Rp.100.000</b></li>

                               </ul>

                            </td>

                    </tr>

                </div>

  

                <div>

                    <tr>

                        <td>Bunga 3 <br>

                            <img src="3.jpg" height="70" width="70"></td>

                            <td>

                               <ul>

                                   <li>Asal: <b>Taman Pakui</b></li>

                                   <li>Keharuman: <b>Sedang</b></li>

                                   <li>Harga: <b>Rp.25.0000</b></li>

                               </ul>

                            </td>

  

                            <td colspan="2" align="center" bgcolor="grey">Kosong</td>

                    </tr>

                </div>

  

                <tr bgcolor="red">

                <td colspan="4" align="center"><a href="file:///C:/Users/ASUS/Documents/Visual%20Studio%20Code/Ujian%20HTML/order%20bunga.html" target="_blank">Pesan Sekarang</a></td><br>

                </tr>

             </table><br>

             <td align="center"><a href="file:///C:/Users/ASUS/Documents/Visual%20Studio%20Code/Ujian%20HTML/latihan%20ujian.html" target="_blank">Kembali Ke Home</a></td>

    </body>

</html>
```
### Analisis
- `<h1>` adalah heading untuk  membuat  judul
-   `<table border="1">` adalah atribut yang digunakan untuk menentukan apkah tabel tersebut memiliki garis pembatas disekitar sel dan kolomnya.
- `<div>` digunakan dalam tabel untuk membagi konteks menjadi beberapa bagian
- `img src` dgunakan untuk menambahkan gambar
- `ul` digunakan untuk mendefinisikan sebuah daftar tak berurutan
- `li` digunakan untuk membuat setiap item dalam daftar informasi
- `height dan width` digunakan untuk mengatur lebar dan tingginya
- `br` digunakan untuk membuat baris baru
- `colspan` dgunakan untuk menggabungkan 2 kolom/lebih
- `bgcolor` digunakan untuk warna baground pada paragraf
- `<a href` digunakan untuk menambakan link halaman link
- `target=_blank` digunakan untuk menambahkan judul linknya

## Order Bunga

```html
<!DOCTYPE html>

<html>

<head>

    <title>Order Bunga</title>

</head>

<body>

    <h1>Pesan bunga</h1>

    <label for="nama">

       <b>Nama:</b>

    </label><br>

    <input type="text" required id="nama"><br>

    <div><br>

        <b>Jenis Bunga:</b> <br>

        <select>

            <option>Bunga 1</option>

            <option>Bunga 2</option>

            <option>Bunga 3</option>

            <option>Bunga 4</option>

            <option>Bunga 5</option>

        </select>

    </div><br>

  

    <div>

        <label for="pembayaran"><b>Jenis Pembayaran:</b></label><br>

        <input type="radio" name="jp" id="pembayaran">

        <label>Tunai</label>

        <input type="radio" name="jp" id="pembayaran">

        <labe>Transfer</label>

    </div> <br>

  

   <b>Alamat Pengiriman:</b> <br>

    <textarea name="Alamat"></textarea><br>

  

    <label><br>

       <b>Waktu Pengiriman:</b>

    </label> <br>

    <input type="checkbox"

    name="Waktu">Pagi

    <input type="checkbox"

    name="Waktu">Siang

    <input type="checkbox"

    name="Waktu">Sore

    <input type="checkbox"

    name="Waktu">Malam <br>

  

   <br> <input type="submit"value="pesan">

      <input type="reset"value="hapus">

  

    <br><br><hr>

    <br> <td align="center"><a href="file:///C:/Users/ASUS/Documents/Visual%20Studio%20Code/Ujian%20HTML/list%20bunga.html" target="_blank">Lihat Daftar Bunga</a></td>

    <br> <td align="center"><a href="file:///C:/Users/ASUS/Documents/Visual%20Studio%20Code/latihan%20ujian.html" target="_blank">Kembali ke home </a></td>

  

</body>

</html>
```

### Analisis 
- `h1` digunakan untuk membuat judul 
- `<label for` digunakan untuk memberi id elemen yg sesuai sebagai nilainya,yg kemudian akan dihubungkan dengan elemen input tersebut
- `<input type="text" required id="nama">` `input type text ` digunakan untuk menentukan bahwa inpu tersebut akan menerima text, `required id` menandakan bahwa input ini harus diisi sebelum formulr dapat disubmit
- `<div` digunakan untuk mengelompokkan elemen2 html tertentu dalam sebuah wadah
- `<select` digunakan untu membuat menu atau kotak pilhan 
- `<option` digunakan untuk menampilkan plihan kpada pengguna
- `value` digunakan untuk menentukan nlaii yang akan dikirimkan saat formulr disubmit
-   `<input type="radio" name="jp" id="pembayaran">` , `input type radio ` digunakan untuk menentukan bahwa input tersebut akan menerima beberapa pilihan,`id` digunakan untuk memberkan identifikasi unik pada suatu elemen
- ` <textarea name="Alamat"></textarea>` digunakan untuk membuat formulr alamat
- `<input type="checkbox"` digunakan untuk membuat pilihan dan pilihannya hanya boleh 1
- `<input type="submit"value="pesan">` digunakan untuk membua tombol submit atau tombol selesai mengisi formulir
- `<input type="reset"value="hapus">` digunakan untuk membuat tombol hapus atau meriset semua jawaban
- `<a href` dgunakan untuk menambakan link halaman web lain



