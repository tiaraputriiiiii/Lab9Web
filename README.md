# Lab9Web

```
Nama    : Tiara Putri
NIM     : 312210064
Kelas   : TI.22.A1
Matkul  : Pemrograman Web 1
```

## **Daftar Isi**
**[Instruksi Praktikum](#instruksi-praktikum)**         
**[Langkah-langkah Praktikum](#langkah-langkah-praktikum)**         
**[Result](#result)**

## **Instruksi Praktikum**
1. Persiapkan text editor misalnya VSCode.
2. Buat folder baru dengan nama **lab9_php_modular** pada docroot webserver 
(htdocs)
3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.

## **Langkah-langkah Praktikum**
1. **Persiapan**
Untuk memulai membuat aplikasi CRUD sederhana, yang perlu disiapkan adalah 
database server menggunakan MySQL. Pastikan MySQL Server sudah dapat dijalankan 
melalui XAMPP. 

2. **Buat file baru dengan nama header.php**
    ```html
        <h1>Modularisasi</h1>
        <nav>
            <a href="home.php">Home</a>
            <a href="about.php">Tentang</a>
            <a href="kontak.php">Kontak</a>
            <a href="index.php">Data Barang</a>
        </nav>
    ```
![Screenshot 2023-12-04 201333](https://github.com/tiaraputriiiiii/Lab9Web/assets/115775237/5bb05998-cd74-42e9-b9d9-dae6ba44cedc)

3. **Buat file baru dengan nama footer.php**
    ```html
        <footer>
            <p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
        </footer>
    ```
![Screenshot 2023-12-04 201542](https://github.com/tiaraputriiiiii/Lab9Web/assets/115775237/2dd7eb82-83b9-40fb-a8b9-d7d2b278ef5b)

4. **Buat file baru dengan nama home.php**
    ```html 
        <?php require('header.php'); ?>

        <div class="content">
        Modul Praktikum Pemrograman Web
        Agung Nugroho (agung@pelitabangsa.ac.id) 78
        Universitas Pelita Bangsa, Bekasi
            <h2>Ini Halaman Home</h2>
            <p>Ini adalah bagian content dari halaman.</p>
        </div>

        <?php require('footer.php'); ?
    ```
![Screenshot 2023-12-04 201223](https://github.com/tiaraputriiiiii/Lab9Web/assets/115775237/77e7ea7c-744b-476f-bade-d451784494da)

5. **Buat file baru dengan nama about.php**
    ```
   <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About</title>
    <style>
</head>

<body>
        <?php require('header.php'); ?>
        <section id="about" class="about">
            <h2>About</h2>
            <div class="row">
                <div class="about-img">
                    <img src="WhatsApp Image 2023-09-06 at 14.54.12_98cddecc.jpg">
                </div>
                <div class="content">
                    <h3>Hello!!</h3>
                    <p>perkenalkan nama saya Tiara Putri saya adalah anak pertama dari dua bersaudara, saudara kandung saya bernama Muhammad Zidan Ramadhan. saat ini usia saya 19 tahun dan saya sedang menempuh s1 di jurusan Teknik Informatika di Universitas Pelita Bnngsa. saya mamiliki 3 teman di kelas yang selalu mensupport perkuliahan saya diantaranya adalah Syifa, Fathia, dan Aas.</p>
                </div>
        </section>
        <?php require('footer.php'); ?>
    </div>
</body>

</html>
    ```
![Screenshot 2023-12-04 201230](https://github.com/tiaraputriiiiii/Lab9Web/assets/115775237/00d723f2-9c13-464f-9c6d-94fc5f6ee560)
