# Lab4_Membuat_weblayout
Nama: Doni Alvero <p>
Nim: 312410663 <P>
Kelas: TI.24.A.5 <P>
Jurusan: Teknik Informatika <p>
Mata Kuliah: Pemograman Web 1 <p>

### Membuat Box Element
***Deskripsi:**
Ada tiga kotak kecil yang berjejer secara horizontal (ke samping) di bagian kiri atas halaman. Masing-masing kotak diberi label "Div 1", "Div 2", dan "Div 3" dan memiliki warna latar belakang yang berbeda-beda (merah, kuning, dan hijau). Ini adalah contoh dasar bagaimana kita bisa membuat dan mengatur elemen kotak (biasanya menggunakan tag `<div>`) dan memberikan gaya (seperti warna dan tata letak) pada halaman web. Dalam konteks web, semua elemen dianggap sebagai "kotak".
<img width="1918" height="1013" alt="Box Element" src="https://github.com/user-attachments/assets/c372bf10-4629-4a79-91d6-cd2c64470fc8" />

### Mengatur Clearfix Element
***Deskripsi:**
Kotak-Kotak Kecil (Di atas): Ada lima kotak kecil berwana-warni ("Div 1" sampai "Div 5") yang berbaris horizontal. Kotak-kotak ini kemungkinan diatur menggunakan properti CSS seperti float. Kotak Biru Besar (Di bawah): Ada satu kotak besar berwarna biru gelap ("Div 4"). Fungsi "Clearfix": Kotak biru ("Div 4") berada tepat di bawah barisan kotak kecil, dan memiliki lebar penuh halaman. Ini menunjukkan bahwa "Clearfix" telah berhasil diterapkan. Clearfix digunakan untuk "membersihkan" efek float tersebut, memastikan elemen berikutnya (kotak biru) dimulai di baris baru dan tidak "terganggu" oleh elemen yang di-float di atasnya.
Singkatnya, gambar ini menunjukkan tata letak elemen kotak yang rapi setelah menggunakan teknik Clearfix untuk mengelola elemen yang di-float.
<img width="1918" height="1002" alt="Mengatur Clearfix Element" src="https://github.com/user-attachments/assets/92691a8e-ed32-48e2-a23a-318116b0e56a" />

### Membuat Layout Sederhana
***Deskripsi:**
Secara keseluruhan, gambar ini menunjukkan kerangka dasar (wireframe) dari sebuah halaman web yang terdiri dari elemen-elemen paling penting: judul, menu navigasi, dan informasi hak cipta. Semua elemen "kotak" (teks, tautan) tampil dalam bentuk aslinya tanpa diberi styling (warna, batas, latar belakang) CSS yang rumit.
<img width="1918" height="1017" alt="Layout Sederhana polos" src="https://github.com/user-attachments/assets/77c3db7e-19a9-4b0f-9407-ac8e54f19a66" />

### Membuat Navigasi
***Deskripsi:**
Secara keseluruhan, gambar ini menunjukkan pembuatan elemen kotak (div) yang ditata dan diberi gaya (warna, padding, margin) untuk membentuk struktur layout web yang lebih baik dan menu navigasi yang jelas.
<img width="1918" height="1020" alt="Membuat Navigasi" src="https://github.com/user-attachments/assets/25c99267-f22f-432f-a3e4-229a081ec77f" />

### Membuat Hero Panel
***Deskripsi:**
Secara keseluruhan, gambar ini menunjukkan penggunaan elemen kotak (div) untuk membangun bagian konten utama (Hero Panel) dari sebuah halaman web, melengkapi struktur layout menjadi lebih fungsional dan siap diisi.
<img width="1917" height="1007" alt="Membuat Hero Panel" src="https://github.com/user-attachments/assets/bb13aaf7-a7cc-4715-b26b-a034f4290a88" />

### Mengatur layout main dan Sidebar & Membuat Sidebar Widget
***Deskripsi:**
Secara keseluruhan, gambar ini menunjukkan penggunaan elemen kotak (div) untuk membuat layout multi-kolom yang standar, di mana konten utama diletakkan di samping kiri, dan konten pelengkap (widget) diletakkan di sisi kanan & struktur ini sangat umum digunakan pada blog.
<img width="1918" height="1018" alt="widget header   text" src="https://github.com/user-attachments/assets/a73a9d98-9e68-4cb5-b337-744012328401" />

### Menambahkan Elemen lainnya pada Main Content
***Deskripsi:**
Secara keseluruhan, gambar ini menunjukkan tata letak yang terstruktur dan berlapis, di mana elemen-elemen kotak (div) digunakan untuk menciptakan desain dua kolom (Main dan Sidebar) yang dinamis, serta mengatur konten utama dengan elemen-elemen berbentuk kolom (fitur grid).
<img width="1918" height="1018" alt="Mengatur layout main dan Sidebar   Membuat Sidebar Widget" src="https://github.com/user-attachments/assets/38e02cd5-2fb8-42d6-8ae7-950179aec43b" />

### Menambahkan Content Artikel
***Deskripsi:**
Secara keseluruhan, gambar ini menunjukkan pengaturan tata letak konten artikel yang dinamis dan berulang (zigzag), di mana elemen teks dan gambar ditukar posisinya (satu di kiri, satu di kanan) untuk menciptakan tampilan yang lebih menarik dalam area konten utama.
<img width="1918" height="1017" alt="Elemen Main Content" src="https://github.com/user-attachments/assets/b77c7abc-be2c-4813-85fe-7673cb48fc91" />
<img width="1917" height="1018" alt="Content Artikel" src="https://github.com/user-attachments/assets/2ee02ef2-5ac5-40b0-8441-8ea79b37ba6f" />


### codingannya
```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Layout Sederhana - Satu Halaman</title>
    
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }

        .wrapper {
            width: 80%;
            max-width: 1000px;
            margin: 20px auto;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
            box-sizing: border-box;
            padding-bottom: 0;
        }

        header h1 {
            color: #aaa;
            margin: 0;
            font-size: 2em;
            font-weight: normal;
            padding: 20px 0 0;
        }

        /* Navigasi */
        nav {
            background-color: #2159a4; 
            overflow: hidden; 
            margin: 10px 0;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        nav ul li {
            float: left;
        }

        nav ul li a {
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
            transition: background-color 0.3s;
        }

        nav ul li a.active {
            background-color: #4b89d8; 
        }
        
        nav ul li a:hover:not(.active) {
            background-color: #3d79c6; 
        }

        /* Konten Utama & Sidebar */
        .hero-content {
            padding: 0 0 20px;
            border-bottom: 1px solid #eee; 
            margin-bottom: 20px;
        }

        .hero-content h2 {
            color: #555;
            font-size: 2.2em;
            margin-top: 0;
            font-weight: 500;
        }

        .hero-content p {
            line-height: 1.6;
            color: #666;
            margin-bottom: 15px;
            text-align: justify;
        }

        .btn-learn {
            display: inline-block;
            background-color: #4b89d8;
            color: white;
            padding: 8px 15px;
            text-decoration: none;
            border-radius: 4px;
            font-weight: bold;
            transition: background-color 0.3s;
        }

        .btn-learn:hover {
            background-color: #2159a4;
        }

        .main-container {
            overflow: hidden; 
            padding-bottom: 20px;
        }

        .main-content {
            width: 68%; 
            float: left;
            padding-right: 30px; 
            box-sizing: border-box;
        }
        
        .content-section {
            padding-top: 20px; 
            margin-bottom: 40px; 
        }
        
        #beranda { 
            padding-top: 0;
        }

        .sidebar {
            /* PENTING: tempat widget berada */
            width: 32%; 
            float: right;
        }
        
        /* Gaya Featurettes (3 lingkaran & 2 blok gambar) */
        .featurette-circles {
            display: flex;
            justify-content: space-between;
            margin-bottom: 40px;
            padding-bottom: 20px;
            border-bottom: 1px solid #eee;
        }

        .featurette-item {
            flex-basis: 30%; 
            text-align: center;
        }

        .featurette-item h3 {
            font-size: 1.2em;
            color: #555;
            margin-top: 15px;
        }

        .featurette-item p {
            font-size: 0.9em;
            color: #666;
            line-height: 1.4;
            text-align: center;
        }

        .circle-placeholder {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            margin: 0 auto 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 0.9em;
        }

        .circle-1 { background-color: #e5944d;} 
        .circle-2 { background-color: #4d7fe5;} 
        .circle-3 { background-color: #4de5c2;} 

        .btn-detail {
            display: inline-block;
            background-color: #ccc;
            color: #333;
            padding: 6px 12px;
            text-decoration: none;
            border-radius: 4px;
            font-size: 0.85em;
        }

        .featurette-block {
            overflow: hidden;
            margin-bottom: 40px;
            padding-top: 40px;
            border-top: 1px solid #eee;
        }

        .featurette-block:first-of-type {
            border-top: none;
            padding-top: 0;
        }
        
        .featurette-block h3 {
            font-size: 1.8em;
            font-weight: normal;
            color: #555;
            margin-top: 0;
        }

        .featurette-block p {
            line-height: 1.6;
            color: #666;
            text-align: justify;
        }

        .featurette-img-left, .featurette-img-right {
            width: 150px;
            height: 150px;
            background-color: #7ba27a;
            margin-bottom: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 0.8em;
            border-radius: 5px;
        }

        .featurette-img-left {
            float: left;
            margin-right: 20px;
        }

        .featurette-img-right {
            float: right;
            margin-left: 20px;
        }

        .widget {
            margin-bottom: 20px;
            border: 1px solid #ccc;
        }

        .widget-header {
            background-color: #4b89d8;
            color: white;
            padding: 10px 15px;
            font-weight: bold;
            font-size: 1.1em;
        }

        .widget-link-list {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        .widget-link-list li {
            border-bottom: 1px solid #eee;
        }

        .widget-link-list li:last-child {
            border-bottom: none;
        }

        .widget-link-list a {
            display: block;
            padding: 10px 15px;
            text-decoration: none;
            color: #333;
            transition: background-color 0.2s;
        }

        .widget-link-list a:hover {
            background-color: #f7f7f7;
        }

        .widget-text-body {
            padding: 15px;
            background-color: #f9f9f9;
            font-size: 0.9em;
            color: #666;
            line-height: 1.5;
            text-align: justify;
        }

        /* Footer */
        footer {
            clear: both;
            padding: 10px 20px;
            text-align: left;
            color: white; 
            font-size: 0.85em;
            background-color: #333;
            margin: 0 -20px -20px -20px; 
            box-sizing: border-box;
        }
    </style>
</head>
<body>
    <div class="wrapper">
        
        <header>
            <h1>Tata Letak Sederhana</h1>
        </header>
        
        <nav>
            <ul>
                <li><a href="#beranda" class="active">Beranda</a></li>
                <li><a href="#artikel">Artikel</a></li>
                <li><a href="#tentang">Tentang</a></li>
                <li><a href="#kontak">Kontak</a></li>
            </ul>
        </nav>
        
        <div class="hero-content">
            <h2>Hello Word!</h2>
            <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat, malesuada 
                tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium 
                nunc pretium ac.
            </p>
            <a href="#artikel" class="btn-learn">Learn More »</a>
        </div>
        
        <div class="main-container">
            
            <div class="main-content">
                
                <section id="beranda" class="content-section">
                    
                    <div class="featurette-circles">
                        <div class="featurette-item">
                            <div class="circle-placeholder circle-1">120 x 120</div>
                            <h3>Judul</h3>
                            <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                            <a href="#" class="btn-detail">Lihat detail</a>
                        </div>
                        <div class="featurette-item">
                            <div class="circle-placeholder circle-2">120 x 120</div>
                            <h3>Judul</h3>
                            <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                            <a href="#" class="btn-detail">Lihat detail</a>
                        </div>
                        <div class="featurette-item">
                            <div class="circle-placeholder circle-3">120 x 120</div>
                            <h3>Judul</h3>
                            <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                            <a href="#" class="btn-detail">Lihat detail</a>
                        </div>
                    </div>
                    
                    <div class="featurette-block">
                        <div class="featurette-img-left">150 x 150</div>
                        <h3>First Featurette Heading.</h3>
                        <p>Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
                    </div>

                    <div class="featurette-block">
                        <div class="featurette-img-right">150 x 150</div>
                        <h3>First Featurette Heading.</h3>
                        <p>Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
                    </div>
                </section>
                
            </div> <div class="sidebar">
                
                <div class="widget">
                    <div class="widget-header">Widget Header</div>
                    <ul class="widget-link-list">
                        <li><a href="#">Widget Link</a></li>
                        <li><a href="#">Widget Link</a></li>
                        <li><a href="#">Widget Link</a></li>
                        <li><a href="#">Widget Link</a></li>
                        <li><a href="#">Widget Link</a></li>
                    </ul>
                </div>
                
                <div class="widget">
                    <div class="widget-header">Widget Text</div>
                    <div class="widget-text-body">
                        Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.
                    </div>
                </div>
                
            </div> </div> <footer>
            &copy; 2021 - Universitas Pelita Bangsa
        </footer>
        
    </div>
</body>
</html>
```






































