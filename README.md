<h1 align="center">Lab2Web</h1>
<h2>Langkah Langkah praktikum</h2> <h2>Pertanyaan dan tugas</h2>
<h1 align="center">Langkah Langkah praktikum</h1>

## 1. Membuat dokumen HTML
Buatlah dokumen HTML seperti berikut:

![ss1](https://github.com/hafizalkariem/Lab1web/assets/115614957/ced60e46-09bd-4b92-9d80-d261ec1a3575)

<b>source code : </b>
```html
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>CSS Dasar</title>
</head>
<body>
 <header>
 <h1>CSS Internal dan <i>Inline CSS</i></h1>
 </header>
 <nav>
 <a href="lab2_css_dasar.html">CSS Dasar</a>
 <a href="lab2_css_eksternal.html">CSS Eksternal</a>
 <a href="lab1_tag_dasar.html">HTML Dasar</a>
 </nav>
 <!-- CSS ID Selector -->
 <div id="intro">
 <h1>Hello World</h1>
 <p>Kami sedang belajar HTML dan CSS dasar, pada mata kuliah <b>Pemrograman 
Web</b> di <i>Universitas Pelita Bangsa</i>. Pelajaran pertama yang kami dapat 
adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML 
dan CSS.</p>
 <!-- CSS Class Selector -->
 <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
 </div>
</body>
</html>


```
<b>Hasil </b>

![Screenshot 2023-10-02 221952](https://github.com/hafizalkariem/Lab1web/assets/115614957/947ae7d3-a811-4607-95a5-f0c830fcf6c8)

## 2. Mendeklarasikan CSS Internal
Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen.
```html
<head>
 <title>CSS Dasar</title>
 <style>
 body {
 font-family:'Open Sans', sans-serif;
 }
 header {
 min-height: 80px;
 border-bottom:1px solid #77CCEF;
 }
 h1 {
 font-size: 24px;
 color: #0F189F;
 text-align: center;
 padding: 20px 10px;
 }
 h1 i {
 color:#6d6a6b;
 }
 </style>
</head>

```



