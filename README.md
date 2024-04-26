# Praktikum Pemrograman Web 1
## <h1> 1.) HTML
HTML (*Hyper Markup Language*) adalah bahasa markup standar yang digunakan untuk membuat halaman web. HTML menggunakan serangkaian tag atau kode khusus yang disisipkan ke dalam teks untuk memberi petunjuk kepada browser web tentang cara menampilkan konten. Dengan menggunakan tag seperti < p > untuk paragraf < img > untuk gambar dan sebagainya. pengembang dapat membuat halaman web dengan tata letak yang terstruktur dan konten yang bervariasi.
HTML berfungsi sebagai dasar mengintegritaskan elemen-elemen seperti teks, gambar, video, formulir, dan banyak lagi ke dalam halaman web, sehingga pengguna dapat mengakses dan berinteraksi dengan konten tersebut melalui browser web.

### ***a. Heading***
Heading HTML ditentukan dengan tag h1-h6. h1 menandakan judul yang paling penting h6 menandakan judul yang paling tidak penting. Penggunaan tag h1 hingga h6 membantu pembaca memahami struktur dan pentingnya konten dalam web. Semakin besar nomor heading, maka semakin kecil juga ukuran hurufnya. Misalnya h1 biasanya digunakan untuk judul halaman utama, sedangkan h2, h3, dan seterusnya digunakan untuk judul sub-bagian yang semakin spesifik. dengan menggunakan heading HTML, pengembang dapat membuat halaman web yang lebih terstruktur dan mudah dibaca.
![Screenshot 2024-04-26 065700](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/115a3c41-17f0-4f58-b5fe-c53ec5041f37)

### ***b. Paragraphs***
Elemen HTML p digunakan untuk mendefinisikan paragraf dalam sebuah halaman web. Setiap paragraf yang ditandai dengan p akan dimulai pada baris baru, dan browser akan menambahkan spasi (margin) sebelum dan sesudah paragraf secara otomatis. ini memastikan tata letak yang jelas dan teratur dalam tampilan halaman web.
![Screenshot 2024-04-26 073522](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/f711ce07-542a-44ee-87bd-68a3fa7aded3)

### ***c. Style Font***
Style HTML digunakan untuk menambahkan gaya ke suatu elemen, seperti warna, font, ukuran dan lainnya.
![Screenshot 2024-04-26 075257](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/ccc95272-32d1-4d9a-858a-3db79c2234f2)

### ***d. Text Formatting***
Text Formatting dirancang untuk menampilkan jenis teks khusus:

* < b >- Teks tebal
* < strong >- Teks penting
* < i >- Teks miring
* < em >- Teks yang ditekankan
* < mark >- Teks yang ditandai
* < small >- Teks lebih kecil
* < del >- Teks yang dihapus
* < ins >- Teks yang disisipkan
* < sub >- Teks subskrip
* < sup >- Teks superskrip
![Screenshot 2024-04-26 083852](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/856db854-192d-4ee9-9a9a-11ebdc470991)

### ***e. Quitation***
pada Quitation banyak pembahasan elemen HTML < blockquate >, < q >, < abbr >, < address >, < cite > dan < bdo >
* Elemen HTML < blockquote > mendefinisikan bagian yang dikutip dari sumber lain.
* tag HTML < q > mendefinisikan kutipan singkat.
* Tag HTML < abbr >mendefinisikan singkatan atau akronim, seperti "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM".
* Tag HTML < address > mendefinisikan informasi kontak penulis/pemilik dokumen atau artikel.
Informasi kontak dapat berupa alamat email, URL, alamat fisik, nomor telepon, alamat media sosial, dll.
Teks dalam < address > elemen biasanya ditampilkan dalam huruf miring, dan browser akan selalu menambahkan jeda baris sebelum dan sesudah <address>elemen.
* Tag HTML <cite>mendefinisikan judul suatu karya kreatif (misalnya buku, puisi, lagu, film, lukisan, patung, dll.).
* Tag HTML <bdo>digunakan untuk mengganti arah teks saat ini
  ![Screenshot 2024-04-26 085337](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/88ec7ac9-24bf-474d-8820-565931e5f132)
  
### ***f. Links***
Tautan HTML adalah hyperlink. dengan menggunakan hyperlink dapat mengeklik tautan dan melompat ke dokumen lain dan saat menggerakkan mouse ke atas link, panah mouse akan berubah menjadi tangan kecil. Tautan (link) tidak harus berupa teks. Tautan dapat berupa gambar atau elemen HTML lainnya.
![Screenshot 2024-04-26 091102](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/f8c10972-0fd9-4b8a-958e-dfa366c42845)

### ***g. Tabel***
dengan tabel HTML, web developers dapat dengan mudah mengatur data ke dalam baris dan kolom yang terstruktur serta memungkinkan penyajian informasi yang jelas.

![Screenshot 2024-04-26 093209](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/73656c7d-1f40-4268-9beb-bafae1cab842)

### ***h. Lists***
Lists HTML memungkinkan web developers mengelompokkan sekumpulan item terkait dalam daftar.
![Screenshot 2024-04-26 093935](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/2d0a5c13-2c56-4724-b601-ddc861d7345f)

### ***i. Block and Inline***
Setiap elemen HTML memiliki nilai tampilan default, bergantung pada jenis elemennya. Dua nilai tampilan yang paling umum adalah Block and Inline.
![Screenshot 2024-04-26 095042](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/69f96b40-de2a-4e94-940c-2fbd52732296)



## 2.) CSS
CSS (*Cascanding Style Sheets*) adalah bahasa yang biasa gunakan untuk menata gaya dokumen HTML(aturan gaya pada elemen-elemen HTML). aturan CSS dapat ditulis di dalam file terpisah atau langsung di dalam dokumen HTML dan akan diterapkan secara tersusun sesuai dengan struktur dokumen, yang memungkinkan pengembang untuk membuat aturan gaya yang konsisten dan mudah dikelola untuk seluruh situs web.

### ***a. Borders***
Properti border-stylemenentukan jenis batas yang akan ditampilkan.
Nilai-nilai berikut diperbolehkan:

* dotted- Mendefinisikan batas titik-titik
* dashed- Mendefinisikan batas putus-putus
* solid- Mendefinisikan batas yang solid
* double- Mendefinisikan perbatasan ganda
* groove- Mendefinisikan batas beralur 3D. Efeknya bergantung pada nilai warna batas
* ridge- Mendefinisikan batas bergerigi 3D. Efeknya bergantung pada nilai warna batas
* inset- Mendefinisikan batas sisipan 3D. Efeknya bergantung pada nilai warna batas
* outset- Mendefinisikan batas awal 3D. Efeknya bergantung pada nilai warna batas
* none- Tidak mendefinisikan batas
* hidden- Mendefinisikan perbatasan tersembunyi
![Screenshot 2024-04-26 100345](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/82d244bd-b33e-49ab-be18-335237b44789)

### ***b. Box Model***
Dalam CSS, istilah *"Box Model"* digunakan ketika berbicara tentang desain dan tata letak. Box Model CSS pada dasarnya adalah sebuah kotak yang membungkus setiap elemen HTML. Terdiri dari: content, padding, border dan margin.
![Screenshot 2024-04-26 101614](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/8040bd9b-57ba-402d-af7c-ce0125cddab2)

### ***c. Text Shadow***
Properti text-shadowmenambahkan bayangan ke teks.
![Screenshot 2024-04-26 103012](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/4809b068-f55f-4226-b37b-139f35eb6654)

### ***d. Font Web***
Font web adalah font yang dipasang secara universal di semua browser dan perangkat. Namun, tidak ada font yang 100% aman untuk web. Selalu ada kemungkinan font tidak ditemukan atau tidak terpasang dengan benar. Oleh karena itu, sangat penting untuk selalu menggunakan font fallback. Ini berarti Anda harus menambahkan daftar "font cadangan" serupa di properti font-family . Jika font pertama tidak berfungsi, browser akan mencoba font berikutnya, font berikutnya, dan seterusnya
![Screenshot 2024-04-26 103847](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/c045061d-4f35-4f2a-8447-81c37cae6c5f)

### ***c. Hoverable Table***
Gunakan :hoverpemilih pada <tr> untuk menyorot baris tabel dengan mengarahkan mouse.
![Screenshot 2024-04-26 105042](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/9350aab4-fcd9-451f-a282-3e641f22097b)

### ***d. Overflow***
Properti CSS overflowmengontrol apa yang terjadi pada konten yang terlalu besar untuk dimasukkan ke dalam suatu area.
![Screenshot 2024-04-26 105558](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/8654c189-b105-4fd0-a65b-1370d69b4401)
![Screenshot 2024-04-26 105614](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/53d17851-6ca1-46cc-a178-1f9a2e59a7cb)
![Screenshot 2024-04-26 105641](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/052976d9-b950-494a-832f-c9192ed40eb2)
![Screenshot 2024-04-26 105700](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/c6384331-ac7b-42fd-a670-97d06dc358bf)
![Screenshot 2024-04-26 105641](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/946803d7-6969-42b8-8e40-b6f839bbe4f1)
![Screenshot 2024-04-26 105801](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/8354b87f-8d33-43c4-b199-5a7ee518636f)

## 3. JavaScript
JavaScript adalah bahasa pemrograman yang digunakan untuk membuat halaman web interaktif dan dinamis. Berbeda dengan HTML yang digunakan untuk menentukan struktur dan konten halaman web serta CSS yang digunakan untuk mengatur tampilan atau gayanya. JavaScript memberikan kemampuan tambahan bagi pengembang web untuk menambahkan fungsionalitas yang kompleks ke dalam halaman web.

### ***a. Function***
* Function JavaScript adalah blok kode yang dirancang untuk melakukan tugas tertentu.
* Function JavaScript dijalankan ketika "sesuatu" memanggilnya (memanggilnya).
![Screenshot 2024-04-26 110910](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/4d0ca77d-d700-4a62-aaa7-045aa2835da6)

### ***b. Alert***
Metode 'alert()' digunakan untuk menampilkan sebuah pesan dalam kotak peringatan yang memiliki tombol OK. ini sangatlah berguna ketika kita perlu menyampaikan informasi penting kepada pengguna. Namun, perlu diingat bahwa pengguna akan dialihkan dari apa yang sedang mereka lakukan saat ini dan dipaksa untuk membaca pesan tersebut. Oleh karena itu, sebaiknya penggunaan metode ini dibatasi, agar tidak mengganggu pengalaman pengguna dengan menghalangi akses ke bagian lain dari halaman hingga kotak peringatan ditutup kembali.
![Screenshot 2024-04-26 112352](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/3a7b8d0d-5f05-463d-ac4d-731504651910)

### ***c. Arithmetic***
Arithmetic dalam JavaScript merujuk pada penggunaan operasi matematika untuk melakukan perhitungan pada nilai-nilai numerik. Operasi arithmetic yang paling umum digunakan meliputi pertambahan (+), Pengurangan (-), perkalian (*), dan pembagian (/). Selain itu, JavaScript juga mendukung operasi arithmetic lainnya seperti modulus (%) untuk mendapatkan sisa dari pembagian, serta operator penambahan (++) dan pengurangan (--) untuk menambahkan atau mengurangkan satu dari nilai yang ada.
![Screenshot 2024-04-26 113332](https://github.com/GalihFitria/praktikum-PWEB1/assets/165490209/67b6d22b-74c1-4de1-9619-208e14fd4280)



