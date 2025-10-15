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
<img width="1918" height="1017" alt="layout1" src="https://github.com/user-attachments/assets/e309a923-809d-464d-bbe8-82cbf78dc6bc" />
<img width="1918" height="1015" alt="layout2" src="https://github.com/user-attachments/assets/bab42621-4a6f-4810-ac12-c829818d08d9" />
<img width="1918" height="1017" alt="layout3" src="https://github.com/user-attachments/assets/c6a4dff9-4c52-4048-adcb-d64766582b84" />
<img width="1918" height="1018" alt="layout4" src="https://github.com/user-attachments/assets/c84c1400-8b8a-4c1c-943b-890402e38a84" />



### codingan 1
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

### Condingan 2
```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Layout Sederhana - Multi Konten</title>
    
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
            /* Awalnya sembunyikan semua section kecuali "beranda" */
            display: none; 
        }
        
        /* Tampilkan section yang sedang aktif (dipanggil via JS) */
        .content-section.active {
            display: block;
        }
        
        /* Pastikan Hero Content selalu tampil untuk "Beranda" */
        #beranda .hero-content { 
            display: block !important;
        }
        
        #beranda { 
            padding-top: 0;
        }

        .sidebar {
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
        
        /* Tambahkan class untuk tautan sidebar agar bisa diakses oleh JS */
        .widget-link-list a.sidebar-link.active {
             background-color: #eee; /* Beri sedikit penanda visual saat aktif */
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

        /* --- GAYA CSS BARU (Untuk About dan Contact) --- */
        
        /* Gaya untuk Konten Tentang */
        .about-portfolio {
            display: flex;
            gap: 20px;
            margin-top: 20px;
            border-top: 1px solid #eee;
            padding-top: 20px;
        }

        .portfolio-item {
            flex-basis: calc(33.33% - 14px); /* 3 item per baris */
            text-align: center;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        
        .portfolio-item img {
            width: 100%;
            height: auto;
            border-radius: 3px;
            background-color: #d9edf7;
            padding: 10px;
            box-sizing: border-box;
        }

        /* Gaya untuk Formulir Kontak */
        .contact-form label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
            color: #555;
        }

        .contact-form input[type="text"],
        .contact-form input[type="email"],
        .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
            font-family: inherit;
        }
        
        .contact-form textarea {
            resize: vertical;
            min-height: 150px;
        }

        .contact-form button {
            background-color: #2159a4;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 1em;
            transition: background-color 0.3s;
        }

        .contact-form button:hover {
            background-color: #1a437d;
        }

    </style>
</head>
<body>
    <div class="wrapper">
        
        <header>
            <h1>Pembersih Halaman Sekitar Rumah</h1>
        </header>
        
        <nav>
            <ul>
                <li><a href="#beranda" class="nav-link active">Beranda</a></li>
                <li><a href="#artikel" class="nav-link">Artikel</a></li>
                <li><a href="#tentang" class="nav-link">Tentang</a></li>
                <li><a href="#kontak" class="nav-link">Kontak</a></li>
            </ul>
        </nav>
        
        <div class="main-container">
            
            <div class="main-content">
                
                <section id="beranda" class="content-section active">
                    <div class="hero-content">
                        <h2>Selamat Datang!</h2>
                        <p>
                            Kami adalah penyedia layanan kebersihan yang berdedikasi untuk memberikan kebersihan terbaik bagi rumah.
                        </p>
                        <a href="#artikel" class="btn-learn">Lihat Layanan »</a>
                    </div>

                    <div class="featurette-circles">
                        <div class="featurette-item">
                            <div class="circle-placeholder circle-1">Cepat</div>
                            <h3>Layanan Cepat</h3>
                            <p>Kami hadir dengan respons cepat dan pekerjaan tuntas tepat waktu.</p>
                            <a href="#" class="btn-detail">Lihat detail</a>
                        </div>
                        <div class="featurette-item">
                            <div class="circle-placeholder circle-2">Profesional</div>
                            <h3>Tim Handal</h3>
                            <p>kami terlatih dan profesional dalam setiap penanganan kebersihan.</p>
                            <a href="#" class="btn-detail">Lihat detail</a>
                        </div>
                        <div class="featurette-item">
                            <div class="circle-placeholder circle-3">Aman</div>
                            <h3>Peralatan Aman</h3>
                            <p>Kami menggunakan peralatan dan cairan pembersih yang aman lingkungan.</p>
                            <a href="#" class="btn-detail">Lihat detail</a>
                        </div>
                    </div>
                    
                </section>
                
                <section id="artikel" class="content-section">
                    <h2>Artikel & Layanan Kami</h2>
                    <p>Temukan tips, trik, dan informasi mendalam mengenai layanan kebersihan yang kami tawarkan.</p>
                    
                    <div class="featurette-block">
                        <div class="featurette-img-left">Alat Pel Lantai</div>
                        <h3>Teknik Membersihkan Lantai.</h3>
                        <p>1.Hilangkan dulu semua kotoran padat, debu, rambut, dan serpihan kasar dari permukaan lantai.</p>
                        <p>2.Gunakan air bersih (bisa air hangat untuk hasil lebih baik) dan cairan pembersih lantai yang sesuai dengan jenis lantai.</p>
                        <p>3.Pastikan kain pel tidak terlalu basah (peras hingga lembap) & Pel dengan pola teratur (misalnya zig-zag).</p>
                        <p>4.Segera ganti air pel jika sudah terlihat kotor/keruh agar kotoran tidak menempel kembali.</p>
                        <P>5.Keringkan: Biarkan lantai kering sepenuhnya sebelum diinjak untuk mencegah lantai kembali kotor atau lengket.</P>
                    </div>

                    <div class="featurette-block">
                        <div class="featurette-img-right">Vakum Debu</div>
                        <h3>Pentingnya Vakum Rutin untuk Kesehatan.</h3>
                        <p> Vakum rutin merupakan langkah kunci untuk menciptakan lingkungan hidup yang sehat dan aman, melindungi kesehatan keluarga dari penyakit pernapasan yang dipicu oleh polutan dan alergen di rumah.</p>
                    </div>
                </section>

                <section id="tentang" class="content-section">
                    <h2>Tentang Kami & Portofolio</h2>
                    
                    <h3>Deskripsi Peralatan Pembersih </h3>
                    <p>Kami hanya menggunakan peralatan pembersih dan mudah digunakan untuk membersihkan halaman sekitar rumah. alat & bahan yang digunakan seperti:</p>
                    <ul>
                        <li>Vakum Pembersih.</li>
                        <li>Sapu.</li>
                        <li>Alat Pel.</li>
                        <li>Ember.</li>
                        <li>Kain Lap.</li>
                    </ul>
                    
                    <h3>Portofolio Proyek Terakhir</h3>
                    <div class="about-portfolio">
                        <div class="portfolio-item">
                            <div class="circle-placeholder" style="background-color: #7d52a2;">Rumah A</div>
                            <p>Pembersihan Area Sekitar Rumah.</p>
                        </div>
                        <div class="portfolio-item">
                            <div class="circle-placeholder" style="background-color: #a25252;">Rumah B</div>
                            <p>Pembersihan Area Halaman Depan.</p>
                        </div>
                        <div class="portfolio-item">
                            <div class="circle-placeholder" style="background-color: #52a27d;">Rumah C</div>
                            <p>Sanitasi dan kebersihan Area Halaman Belakang.</p>
                        </div>
                    </div>
                </section>
                
                <section id="syarat" class="content-section">
                    <h2>Syarat & Ketentuan Layanan</h2>
                    <h3>1. Kebijakan Pemesanan</h3>
                    <p>Semua pemesanan harus dilakukan minimal 1 hari sebelumnya. Pembatalan dalam waktu 1 jam sebelum jadwal akan batal</p>

                    <h3>2. Jangkauan Area</h3>
                    <p>Layanan kami saat ini mencakup area Sekitar Dangga. Untuk lokasi di luar area tersebut, mungkin akan dikenakan biaya transportasi tambahan.</p>
                    
                    <h3>3. Jam Operasional</h3>
                    <p>Layanan reguler tersedia Senin-Sabtu, pukul 08:00 - 21:00 WIB. Pemesanan di luar jam tersebut tergantung pada ketersediaan tim.</p>
                    
                    <h3>4. Garansi Kebersihan</h3>
                    <p>Kami menjamin hasil kebersihan yang memuaskan. Jika ada keluhan, harap laporkan dalam waktu 3 jam setelah layanan selesai untuk peninjauan ulang.</p>
                </section>

                <section id="kontak" class="content-section">
                    <h2>Hubungi Kami / Booking Layanan</h2>
                    <p>Silakan isi formulir di bawah ini untuk mendapatkan penawaran atau mengajukan pertanyaan.</p>
                    
                    <form action="#" method="POST" class="contact-form">
                        <label for="nama">Nama Lengkap</label>
                        <input type="text" id="nama" name="nama" required>
                        
                        <label for="email">Email</label>
                        <input type="email" id="email" name="email" required>
                        
                        <label for="message">Pesan Anda / Detail Booking (Jenis Layanan, Alamat, Tanggal)</label>
                        <textarea id="message" name="message" required></textarea>
                        
                        <button type="submit">Kirim Pesan / Booking</button>
                    </form>
                </section>
                
            </div> 
            
            <div class="sidebar">
                
                <div class="widget">
                    <div class="widget-header">Link Cepat</div>
                    <ul class="widget-link-list">
                        <li><a href="#tentang" class="sidebar-link">Tentang Kami</a></li>
                        <li><a href="#kontak" class="sidebar-link">Booking Layanan</a></li> 
                        <li><a href="#artikel" class="sidebar-link">Layanan Kami</a></li>
                        <li><a href="#syarat" class="sidebar-link">Syarat & Ketentuan</a></li>
                    </ul>
                </div>
                
                <div class="widget">
                    <div class="widget-header">Informasi Singkat</div>
                    <div class="widget-text-body">
                        Kami melayani area Sekitar dangga. Jam operasional layanan: Senin-Sabtu, 08:00 - 21:00. Hubungi kami untuk jadwal di luar jam tersebut.
                    </div>
                </div>
                
            </div> 
        </div> 

        <footer>
            &copy; 2021 - Universitas Pelita Bangsa
        </footer>
        
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const navLinks = document.querySelectorAll('.nav-link');
            const sidebarLinks = document.querySelectorAll('.sidebar-link'); // Ambil semua tautan sidebar
            const allLinks = document.querySelectorAll('.nav-link, .sidebar-link'); // Gabungkan semua tautan
            const sections = document.querySelectorAll('.content-section');
            const heroContent = document.querySelector('.hero-content');

            // Fungsi untuk mengaktifkan tautan pada navigasi utama
            const setActiveNav = (targetId) => {
                navLinks.forEach(l => l.classList.remove('active'));
                const navTarget = document.querySelector(`.nav-link[href="${targetId}"]`);
                if (navTarget) {
                    navTarget.classList.add('active');
                }
            };
            
            // Fungsi untuk menampilkan/menyembunyikan konten
            const showSection = (targetId) => {
                sections.forEach(section => {
                    // Sembunyikan semua section
                    section.classList.remove('active');
                });
                
                // Tampilkan section yang dituju
                const targetSection = document.querySelector(targetId);
                if (targetSection) {
                    targetSection.classList.add('active');
                    
                    // Khusus untuk #beranda, kita perlu memastikan hero-content terlihat
                    if (targetId !== '#beranda') {
                        // Cek apakah hero-content ada di section lain, jika tidak, sembunyikan secara global
                        heroContent.style.display = 'none';
                    } else {
                        heroContent.style.display = 'block';
                    }
                }
            };
            
            // Atur event listener untuk setiap tautan (Navigasi Utama dan Sidebar)
            allLinks.forEach(link => {
                link.addEventListener('click', (e) => {
                    e.preventDefault();
                    
                    const targetId = link.getAttribute('href');
                    
                    // Hapus kelas 'active' dari semua tautan navigasi utama
                    navLinks.forEach(l => l.classList.remove('active'));
                    
                    // Set kelas 'active' pada Navigasi Utama yang sesuai
                    setActiveNav(targetId);
                    
                    // Tampilkan section yang sesuai
                    showSection(targetId);
                });
            });

            // Pastikan halaman dimulai di #beranda
            showSection('#beranda');
        });
    </script>
</body>
</html>
```






































