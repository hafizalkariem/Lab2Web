<h1 align="center">Lab2Web</h1>
<h2>Langkah Langkah praktikum</h2> <h2>Pertanyaan dan tugas</h2>
<h1 align="center">Langkah Langkah praktikum</h1>

## 1. Membuat dokumen HTML
Buatlah dokumen HTML seperti berikut:

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

<b>Hasilnya : </b>

![2](https://github.com/hafizalkariem/Lab1web/assets/115614957/639cd054-d917-4ddd-9e42-d8ef6ae3bee0)


## 3. Menambahkan Inline CSS
Kemudian tambahkan deklarasi inline CSS pada tag `<p>` seperti berikut.

```html
<p style="text-align: center; color: #ccd8e4;">
```
<b>Hasil : </b>

![3](https://github.com/hafizalkariem/Lab1web/assets/115614957/988bcbdc-3898-4886-b541-718b3cca627f)

## 4. Membuat CSS Eksternal
Buatlah file baru dengan nama <b>style_eksternal.css</b> kemudian buatlah deklarasi CSS seperti berikut.
```css
nav {
background: #20A759;
color:#fff;
padding: 10px;
}
nav a {
color: #fff;
text-decoration: none;
padding:10px 20px;
}
nav .active, 
nav a:hover {
background: #0B6B3A;
}
```
Kemudian tambahkan tag `<link>` untuk merujuk file css yang sudah dibuat pada bagian `<head>`
```html
<head>
 <!-- menyisipkan css eksternal -->
 <link rel="stylesheet" href="style_eksternal.css" type="text/css">
</head>

```
<b>Hasilnya : </b>

![4](https://github.com/hafizalkariem/Lab1web/assets/115614957/af78a7e9-e5cb-4cdf-82b7-821c5c3e4007)

## 5. Menambahkan CSS Selector
Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file 
style_eksternal.css, tambahkan kode berikut.
```css
/* ID Selector */
#intro {
background: #418fb1;
border: 1px solid #099249;
min-height: 100px;
padding: 10px;
}
#intro h1 {
text-align: left;
border: 0;
color: #fff;
}
/* Class Selector */
.button {
 padding: 15px 20px;
background: #bebcbd;
color: #fff;
display: inline-block;
margin: 10px;
text-decoration: none;
}
.btn-primary {
background: #E42A42;
}

```
<b>Hasilnya : </b>

![5](https://github.com/hafizalkariem/Lab1web/assets/115614957/4a941a63-b295-4ec0-8b57-a33fb29f3161)







