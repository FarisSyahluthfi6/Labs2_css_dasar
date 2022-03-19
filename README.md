# Labs2_css_dasar

| Nama= Faris Syahluthfi      | 
|-----------------------------|
| NIM= 312010034              |
|=============================| 
| Kelas= TI.20.A.1            |
|-----------------------------|
| Matkul= Pemrograman Web     |
|=============================|

## 1. Membuat dokumen HTML
![Membuat_dokumen_HTML](screenshot/Membuat_dokumen_HTML.PNG)

Ini adalah sebuah hasil dari texs Kodingan tag membuat dokumen HTML<p>
 Dan Ini Adalah program codingan dari tag membuat dokumen HTML:

## Contoh Kode
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
    <h1><b>TUGAS PRATIKUM 2 MEMBUAT CSS DASAR</b></h1>
</header>
<nav>
<a href="lab2_css_dasar.html">CSS Dasar</a>
<a href="lab2_css_eksternal.html">CSS Eksternal</a>
<a href="lab1_tag_dasar.html">HTML Dasar</a>
</nav>
<!-- CSS ID Selector -->
<div id="intro">
    <h1>FARIS SYAHLUTHFI</h1>
<p>Saya sedang mengerjakan <b>PRATIKUM 2</b> mata kuliah <b><u>PEMROGRAMAN WEB</u></b> 
    disini saya diberikan tugas yaitu untuk membuat <u>CSS DASAR</u></p>
<!-- CSS Class Selector -->
<a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
</div>
</body>
</html>
```

## 2. Mendeklarasikan CSS Internal
![Deklarasi_css_internal](screenshot/Deklarasi_css_internal.PNG)

Ini adalah sebuah hasil dari texs Kodingan tag Mendeklarasikan CSS Internal<p>
 Dan Ini Adalah program codingan dari tag Mendeklarasikan CSS Internal:

 ## Contoh Kode

 ```html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CSS Dasar</title>
</head>
<body>

    <head>


        <title>CSS Dasar</title>
        <style>
        body {
        font-family:'Open Sans', sans-serif;
        }
        header {
        min-height: 100px;
        border-bottom:5px solid #ef777d;
        }
        nav {
            font-size: 20px;
            text-align: center;
            padding: 50px 25px ;
        }
        h1 {
        font-size: 50px;
        color: #0f9f3a;
        text-align: center;
        padding: 150px 200px;
        }
        h1 i {
        color:#6d6d6a;
        }
        
        </style>
        </head>

<header>
    <h1><b>TUGAS PRATIKUM 2 MEMBUAT CSS DASAR</b></h1>
</header>
<nav>
<a href="lab2_css_dasar.html">CSS Dasar</a>
<a href="lab2_css_eksternal.html">CSS Eksternal</a>
<a href="lab1_tag_dasar.html">HTML Dasar</a>
</nav>
<!-- CSS ID Selector -->
<div id="intro">
    <h1>FARIS SYAHLUTHFI</h1>
<p>Saya sedang mengerjakan <b>PRATIKUM 2</b> mata kuliah <b><u>PEMROGRAMAN WEB</u></b> 
    disini saya diberikan tugas yaitu untuk membuat <u>CSS DASAR</u></p>
<!-- CSS Class Selector -->
<a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
</div>
</body>
</html>

 ```


## 3. Menambahkan Inline CSS
![Menambahkan_inline_css](screenshot/Menambahkan_inline_css.PNG)

Ini adalah sebuah hasil dari texs Kodingan tag Menambahkan Inline CSS<p>
 Dan Ini Adalah program codingan dari tag Menambahkan Inline CSS:

## Contoh Kode
```Html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CSS Dasar</title>
</head>
<body>

    <head>


        <title>CSS Dasar</title>
        <style>
        body {
        font-family:'Open Sans', sans-serif;
        }
        header {
        min-height: 100px;
        border-bottom:5px solid #ef777d;
        }
        nav {
            font-size: 20px;
            text-align: center;
            padding: 50px 25px ;
        }
        h1 {
        font-size: 50px;
        color: #0f9f3a;
        text-align: center;
        padding: 150px 200px;
        }
        h1 i {
        color:#6d6d6a;
        }
        
        </style>
        </head>

<header>
    <h1><b>TUGAS PRATIKUM 2 MEMBUAT CSS DASAR</b></h1>
</header>
<nav>
<a href="lab2_css_dasar.html">CSS Dasar</a>
<a href="lab2_css_eksternal.html">CSS Eksternal</a>
<a href="lab1_tag_dasar.html">HTML Dasar</a>
</nav>
<!-- CSS ID Selector -->
<div id="intro">
    <h1>FARIS SYAHLUTHFI</h1>
    <p style="text-align: center; font-size: 25px; color: #3a68be;">Saya sedang mengerjakan <b>PRATIKUM 2</b> mata kuliah <b><u>PEMROGRAMAN WEB</u></b> 
        disini saya diberikan tugas yaitu untuk membuat <u>CSS DASAR</u>
    </p>
    
<!-- CSS Class Selector -->
<a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
</div>
</body>
</html>

```

### 4. Membuat CSS Eksternal

Membuat file baru dengan nama style_eksternal.css. ini adalah kodingan dari file style_eksternal.css:<p>

 ```css

Nav {
    background: #d35013;
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
    background: #ca5c12;
    }

```
Kemudian saya menambahkan tag <link> untuk merujuk file css yang sudah dibuat pada bagian <head> <p>
```html
<head>
<!-- menyisipkan css eksternal -->
<link rel="stylesheet" href="style_eksternal.css" type="text/css">
</head>

```
![Membuat_css_eksternal](screenshot/Membuat_css_eksternal.PNG)

Ini adalah sebuah hasil dari texs Kodingan full tag  Membuat CSS Eksternal<p>
 


## 5. Menambahkan CSS Selector
Selanjutnya saya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file
style_eksternal.css. Berikut kodingan yang sudah saya buat:<p>

## Contoh Kode

 ```css
Nav {
    background: #d35013;
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
    background: #ca5c12;
    }

    /* ID Selector */
#intro {
    background: #41b15d;
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

![Membuat_css_eksternal](screenshot/Menambahkan_css_selector.PNG)

Ini adalah sebuah hasil dari texs Kodingan full tag  Menambahkan CSS Selector<p>

## Full Program
![Full_Program](screenshot/Full_Program.PNG)

Ini adalah sebuah hasil Program yang sudah saya buat<p>
 Dan Ini Adalah program codingannya:

 ```html

 <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CSS Dasar</title>
</head>
<body>
    <head>

        <!-- menyisipkan css eksternal -->
<link rel="stylesheet" href="style_eksternal2.css" type="text/css">

        <title>CSS Dasar</title>
        <style>
        body {
        font-family:'Open Sans', sans-serif;
        }
        header {
        min-height: 100px;
        border-bottom:5px solid #ef777d;
        }
        nav {
            font-size: 20px;
            text-align: center;
            padding: 50px 25px ;
        }
        h1 {
        font-size: 50px;
        color: #0f9f3a;
        text-align: center;
        padding: 150px 200px;
        }
        h1 i {
        color:#6d6d6a;
        }
        
        </style>
        </head>


<header>
<h1><b>TUGAS PRATIKUM 2 MEMBUAT CSS DASAR</b></h1>
</header>

<nav>
<a href="Membuat_dokumen_HTML.html">MEMBUAT DOKUMEN HTML</a>
<a href="deklarasi_CSS_internal.html">MENDEKLARASIKAN CSS INTERNAL</a>
<a href="Menambahkan_Inline_CSS.html">MENAMBAHKAN INLINE CSS</a>
<a href="Membuat_CSS_Eksternal.html">MEMBUAT CSS EKSTERNAL</a>


</nav>

<!-- CSS ID Selector -->
<div id="intro">
<h1>FARIS SYAHLUTHFI</h1>

<p style="text-align: center; font-size: 25px; color: #3a68be;">Saya sedang mengerjakan <b>PRATIKUM 2</b> mata kuliah <b><u>PEMROGRAMAN WEB</u></b> 
    disini saya diberikan tugas yaitu untuk membuat <u>CSS DASAR</u>
</p>

<!-- CSS Class Selector -->
<a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
</div>
</body>
</html>

```