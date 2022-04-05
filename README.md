## Nama     : Denas Aria Pamungkas
## NIM      : 312010089
## Kelas    : TI.20.A.1
## Matkul   : Pemograman WEB

## 1). Membuat Box Element <b>
### Hasil

![img1](https://user-images.githubusercontent.com/101621068/161721834-57ea6497-2406-4fd6-9846-48c341896cab.png)

Disini saya telah membuat box element dengan tag div dan juga dengan CSS FLOAT PROPERTY.

### Contoh Coding
```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Box Element</title>
<style>
    div {
    float:left;
    padding: 10px;
    }
    .div1 {
    background: red;
    }
    .div2 {
    background: yellow;
    }
    .div3 {
    background: green;
    }
    </style>
</head>
<body>
<header>
<h1>Box Element</h1>
</header>
</body>
<section>
    <div class="div1">Div 1</div>
    <div class="div2">Div 2</div>
    <div class="div3">Div 3</div>
    </section>
</html>
```

## 2). Mengatur ClearFix Element
### Hasil


![img2](https://user-images.githubusercontent.com/101621068/161722847-7304e964-055b-4ac9-8818-dce12912d214.png)

Menambahkan Tag Element Div dan juga CSS Clear yang kemudian Floatnya di none.

### Contoh Coding
```css
    .div4 {
background-color: blue;
clear: left;
float: none;
}
```

```html
<div class="div4">Div 4</div>
```

## 3). Membuat Kerangka Layout
### Hasil

![img3](https://user-images.githubusercontent.com/101621068/161726130-01c3bccd-b158-48a4-a5d5-ab5f45f4b18b.png)

Disini saya membuat kerangka layout sederhana

### Contoh Coding
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Layout Sederhana</title>
</head>

<body>
    <div id="container">
        <header>
            <h1>Layout Sederhana</h1>
        </header>
        <nav>
            <a href="home.html" class="active">Home</a>
            <a href="artikel.html">Artikel</a>
            <a href="about.html">About</a>
            <a href="kontak.html">Kontak</a>
        </nav>
        <section id="hero"></section>
        <section id="wrapper">
            <section id="main"></section>
            <aside id="sidebar"></aside>
        </section>
        <footer>
            <p>&copy; 2021 - Universitas Pelita Bangsa</p>
        </footer>
    </div>
</body>

</html>
```

## 4). Menambahkan CSS Layout
### Hasil
![img4](https://user-images.githubusercontent.com/101621068/161736454-675b3ed9-e54b-4a3c-947c-53be9261a3cb.png)

Disini saya menambahkan CSS Layout pada CSS Eksternal

### Contoh Coding
```css
/* import google font */
@import
url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,600;0,700;0,800;1,300;1,400;1,600;1,700;1,800&display=swap');
@import
url('https://fonts.googleapis.com/css2?family=Open+Sans+Condensed:ital,wght@0,300;0,700;1,300&display=swap');
/* Reset CSS */
* {
    margin: 0;
    padding: 0;
    }
    body {
    line-height:1;
    font-size:100%;
    font-family:'Open Sans', sans-serif;
    color:#5a5a5a;
    }
    #container {
    width: 980px;
    margin: 0 auto;
    box-shadow: 0 0 1em #cccccc;
    }
    /* header */
    header {
    padding: 20px;
    }
    header h1 {
    margin: 20px 10px;
    color: #b5b5b5;
    }
```

## 5). Membuat Navigasi
### Hasil


![img5](https://user-images.githubusercontent.com/101621068/161736542-ff463d12-a161-4052-b5d6-7b1882e52ff8.png)

Disini saya menambahkan navigasi pada CSS

### Contoh Coding
```css
/* navigasi */
nav {
    display: block;
    background-color: #1f5faa;
    }
    nav a {
    padding: 15px 30px;
    display: inline-block;
    color: #ffffff;
    font-size: 14px;
    text-decoration: none;
    font-weight: bold;
    }
    nav a.active,
    nav a:hover {
    background-color: #2b83ea;
    }
```

## 6). Membuat Hero Panel
### Hasil


![img6](https://user-images.githubusercontent.com/101621068/161736630-3f7b69a6-ac90-4dd3-a604-8158e96de678.png)

Disini saya membuat Hero Panel

### Contoh Coding
```css
 /* Hero Panel */
#hero {
    background-color: #e4e4e5;
    padding: 50px 20px;
    margin-bottom: 20px;
    }
    #hero h1 {
    margin-bottom: 20px;
    font-size: 35px;
    }
    #hero p {
    margin-bottom: 20px;
    font-size: 18px;
    line-height: 25px;
    }
```

## 7). Mengatur Layout Main dan Sidebar

Disini saya sudah mengatur layout main dan sidebar

### Contoh Coding
```css
 /* main content */
#wrapper {
    margin: 0;
    }
    #main {
        float: left;
        width: 640px;
        padding: 20px;
        }
        /* sidebar area */
        #sidebar {
        float: left;
        width: 260px;
        padding: 20px;
        }
```

## 8). Membuat Sidebar Widget
### Hasil


![img7](https://user-images.githubusercontent.com/101621068/161736860-8b3a9613-980e-4159-a37b-e2d3e73814de.png)

Menambahkan sidebar widget pada html dan css

### Contoh Coding
```html
 <aside id="sidebar">
                <div class="widget-box">
                    <h3 class="title">Widget Header</h3>
                    <ul>
                        <li><a href="#">Widget Link</a></li>
                        <li><a href="#">Widget Link</a></li>
                        <li><a href="#">Widget Link</a></li>
                        <li><a href="#">Widget Link</a></li>
                        <li><a href="#">Widget Link</a></li>
                    </ul>
                </div>
                <div class="widget-box">
                    <h3 class="title">Widget Text</h3>
                    <p>Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt
                        arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer
                        pharetra est nunc, nec pretium nunc pretium ac.</p>
                </div>
            </aside>
```

```css
/* widget */
.widget-box {
    border:1px solid #eee;
    margin-bottom:20px;
    }
    .widget-box .title {
    padding:10px 16px;
    background-color:#428bca;
    color:#fff;
    }
    .widget-box ul {
    list-style-type:none;
    }
    .widget-box li {
    border-bottom:1px solid #eee;
}
.widget-box li a {
padding:10px 16px;
color:#333;
display:block;
text-decoration:none;
}
.widget-box li:hover a {
background-color:#eee;
}
.widget-box p {
padding:15px;
line-height:25px;
}
```

## 9). Mengatur Footer
### Hasil

![img8](https://user-images.githubusercontent.com/101621068/161736951-5b66b70c-7911-45ce-a6c2-7bebf6ecabca.jpg)

Disini saya menambahkan footer pada bagian css

### Contoh Coding
```css
/* footer */
footer {
    clear:both;
    background-color:#1d1d1d;
    padding:20px;
    color:#eee;
    }
```

## 10). Menambahkan Element Pada Main Content
### Hasil

![img9](https://user-images.githubusercontent.com/101621068/161737031-d0e975d9-9df0-4b4e-9cdd-ed6751827afe.png)

Disini saya telah menambahkan element pada main content

### Contoh Coding
```html
<section id="main">
<div class="row">
<div class="box">
<img src="https://dummyimage.com/120/db7d25/fff.png" alt=""
class="image-circle">
<h3>Heading</h3>
<p>Donec sed odio dui. Etiam porta sem malesuada magna mollis
euismod.</p>
<a href="#" class="btn btn-default">View detail</a>
</div>
<div class="box">
<img src="https://dummyimage.com/120/3e73e6/fff.png" alt=""
class="image-circle">
<h3>Heading</h3>
<p>Donec sed odio dui. Etiam porta sem malesuada magna mollis
euismod.</p>
<a href="#" class="btn btn-default">View detail</a>
</div>
<div class="box">
<img src="https://dummyimage.com/120/71e6d4/fff.png" alt=""
class="image-circle">
<h3>Heading</h3>
<p>Donec sed odio dui. Etiam porta sem malesuada magna mollis
euismod.</p>
<a href="#" class="btn btn-default">View detail</a>
</div>
</div>
</section>
```

```css
/* box */
.box {
display:block;
float:left;
width:33.333333%;
box-sizing:border-box;
-moz-box-sizing:border-box;
-webkit-box-sizing:border-box;
padding:0 10px;
text-align:center;
}
.box h3 {
margin: 15px 0;
}
.box p {
line-height: 20px;
font-size: 14px;
margin-bottom: 15px;
}
box img {
border: 0;
vertical-align: middle;
}
.image-circle {
border-radius: 50%;
}
.row {
margin: 0 -10px;
box-sizing: border-box;
-moz-box-sizing: border-box;
-webkit-box-sizing: border-box;
}
.row:after, .row:before,
.entry:after, .entry:before {
content:'';
display:table;
}
.row:after,
.entry:after {
clear:both;
}
```

## 11). Menambahkan Content Article
### Hasil


![img10](https://user-images.githubusercontent.com/101621068/161737102-b2e42b10-631d-4e7a-8f10-cf4e7846fdad.png)

Disini saya menambahkan element dengan section article dan pada css nya

```html
<hr class="divider" />
                <article class="entry">
                    <h2>First featurette heading.</h2>
                    <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="">
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
                        elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
                        vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
                        pretium ac.</p>
                </article>
                <hr class="divider" />
                <article class="entry">
                    <h2>First featurette heading.</h2>
                    <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="" class="right-img">
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
                        elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
                        vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
                        pretium ac.</p>
                </article>
```

```css
.divider {
    border:0;
    border-top:1px solid #eeeeee;
    margin:40px 0;
    }
    /* entry */
    .entry {
    margin: 15px 0;
    }
    .entry h2 {
    margin-bottom: 20px;
}
.entry p {
line-height: 25px;
}
.entry img {
float: left;
border-radius: 5px;
margin-right: 15px;
}
.entry .right-img {
float: right;
}
```

## Pertanyaan dan Tugas

## 1). Tambahkan Layout untuk menu About => buat single layout yang berisi deskripsi, portofolio, dll.
### Jawaban
![no1](https://user-images.githubusercontent.com/101621068/161744968-f9009282-0b6e-48b3-a16c-5aebcbeae099.png)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="container">
        <header>
            <h1>About Me</h1>
        </header>
        <nav>
            <a href="home.html" class="active">Home</a>
            <a href="artikel.html">Article</a>
            <a href="about.html">About</a>
            <a href="kontak.html">Contact</a>
        </nav>
        <section id="about">
            <div class="row">
                <img src="denas.jpg" title="Denas Aria Pamungkas" alt="Denas Aria Pamungkas" width="200px
                " class="image-circle" style="float: left; border: 2px solid black;">
                <h1>Denas Aria Pamungkas</h1>
                <p>Nama saya Denas Aria Pamungkas, Saya adalah seorang mahasiswa Universitas Pelita Bangsa,Jurusan Teknik Informatika kelas TI.20 A.1. Saya lahir di Bekasi, 11 Oktober 2002. dan saya juga sedang mempelajari html css js dan php sebagai jalan menuju front end developer</p>
            </div>
        </section>
        <footer>
            <p style="text-align: center;">Universitas Pelita Bangsa</p>
        </footer>
    </div>
</body>
</html>
```

### 2). Tambahkan layout untuk menu Contact => yang berisiform isian : nama, email, massage, dll.
### Jawaban

![no2](https://user-images.githubusercontent.com/101621068/161746296-5a846eb9-9e39-4b55-bda4-9004e51614e0.png)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="container">
        <header>
            <h1>Contact Me</h1>
        </header>
        <nav>
            <a href="home.html" class="active">Home</a>
            <a href="artikel.html">Artikel</a>
            <a href="about.html">About</a>
            <a href="kontak.html">Kontak</a>
        </nav>
        <section id="kontak">
            <div class="login">
               <input type="text" placeholder="Your Name" class="input">
               <input type="text" placeholder="Your Email" class="input">
            </div>
            <div class="subject">
                <input type="text" placeholder="Subject" class="input"> 
            </div>
            <div class="msg">
                <textarea name="Message" id="Message" cols="35" rows="10" class="area" class="input" placeholder="Your Message"></textarea>
            </div>
            <button type="submit">Send</button>
        </section>
    </div>
</body>
</html>
```

```css
/* Kontak Panel */
#kontak{
    background-color: #e4e4e5;
    padding: 20px 20px;
    margin-bottom: 20px;
}
.input,
.msg, .area{
    width: 100%;
    padding: 10px;
    border: 1px solid white;
    box-sizing: border-box;
    font-size: 15px;
    margin-bottom: 20px;
    
}
button{
    font-size: 15px;
    background-color: #3f3f3f;
    color: white;
    border-radius: 5px;
    padding: 10px 20px;
    margin-top: 8px;
}
button:hover{
    opacity: 0,9;
    background-color: #1f5faa;
}
```
