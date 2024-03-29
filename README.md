# bootstrap-3

# Bootstrap Tutorial #01 - Introduction to Bootstrap

```
Bootstrap is a framework
- Frameworks are designed to help do a lot of the heavy lifting associated with certain tasks
- The Bootstrap framework is designed to make creating responsive, feature-rich websites mch easier and comes with manya helpful features
- We have to write our code the way the Bootstrap framework wants us to take advantae of the features
```

```
Bootstrap features
- Fluid and Fixed grid system
- Carousels
- Drop down menus
- Modals / Pop-ups
```

```
Mobile First Approach
- Assume you want to create a mobile friendly website
- Websites you make with Bootstrap will be responsive in nature
```

```
What you need to know
- HTML & CSS
- Javascript
- Responsive Development
```

# Bootstrap Tutorial #02 - How to Use Bootstrap in Your Project

```
Using CDN
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>

Bootstrap butuh jQuery, bila menggunakan recompile js
```

# Bootstrap Tutorial #03 - Bootstrap Grid System

```
Grids
- Bootstrap come with a 12-column grid system
- We add our content into the 'rows' and 'columns' of this grid using Bootstrap's CSS classes
- Bootstrap will take care of the responsive work for us

Containers, Row dan Columns
- Containers surround the whole section of row and columns
- Rows represent a horizontal line of elements
- Columns represent the horizontal space that elements take up in a row
```

# Bootstrap Tutorial #04 - Bootstrap Containers

```
Fix-Container - "container"
a. Has a fix width, which changes at certian brakepoints.
b. Has a built-in padding of 15px all the way around.

Fluid-Continer - "container-fluid"
a. Has a fluid width, which strech to 100%, of it's parent elements
b. Has a built-in padding of 15px all the way around.

"container" : Memiliki ukuran yang fix, dan bila screen berubah dia akan berubah tp dgn ukuran tertentu saja tidak dinamais
"container-fluid" : Memiliki ukuran yang dinamis, yang SELALU mengikuti ukuran parentnya.

Bila kita mau menggunakan 12 Grid System, kita harus wrap it dengan container
```

# Bootstrap Tutorial #05 - Rows

```
Boot strap menggunakna 12 Grid System
col-xs-12 => Untuk Extra small screen terapkan 12 column
col-sm-6 => Untuk Small screen terapkan 6 column
col-md-4 => Untuk Medium screen terapkan 4 column
```

Example :
![Rows](https://github.com/elvinotan/bootstrap-3/blob/master/images/rows.png)

# Bootstrap Tutorial #06 - Columns

```
Columns
- We assign elements within a row, a column-width
- We do this by using bootstrap classes
    col-{size}-{number}
    {size} =  the size of the viewport which you are targeting
    {number} = numbre of columns you want element to span
```

```
Column Size
- Sizes :
    xs (<768), sm (>=768), md (>=992), lg (>=1200)
- Number of Columns :
    any interger between 1 and 12
- Example
    "cols-ex-12" or "col-md-6"

- Tips : Selalu mulai dari xs ke lg
```

# Bootstrap Tutorial #07 - Column Offsetting

```
Offset column adalah space grid sisi kiri dan sisi kanan contoh
Nilai offset harus di hitung sebagai grid contoh :
<div class='col-xs-offset-2 col-xs-8'> Data </div>
Artinya pasang offset 2 grid di kiri, data 8 grid dan offset 2 grid di kanan
```

![Offseting](https://github.com/elvinotan/bootstrap-3/blob/master/images/offseting.png)

# Bootstrap Tutorial #08 - Push & Pull

```
Push: Mendorong element ke kanan sejumlah grid yang di define
Pull : Menarik element ke kiri sejumlah grid yang di define

Bla oprasional push pull berada di tengah, dan untuk screen kecil dan besar mau menggunakan original grid, maka kita harus mereset kembali push dan pull
```

![PushPull](https://github.com/elvinotan/bootstrap-3/blob/master/images/pushpull.png)

# Bootstrap Tutorial #09 - Clearfix

```
Meski ukuan colum 6 misalnya, artinya pairing kanan dan kiri dua column,
tampilannya tidak selalu sesuai dgn yang kita inginkan, hal ini di karenakan ukuran height yang berbeda
Untuk memperbaiki ini kita menggunakan command clearfix, untuk element yang bermasalah

<div class='clearfix'></div>
atau pake custom script
thumb:nth-child(odd){clear: both;}
```

# Bootstrap Tutorial #10 - Text Styles

```
Bila kita menggunakan boostrap, bootstrap sendiri memiliki class bawahaan yang dapat kita gunakan contoh :

<span class="h1">boostrap programing</span>
<p class="lean">ini adalah class yang bertipe article</p>
```

# Bootstrap Tutorial #11 - List Styles

```
list-inline : Untuk menjajarkannya ke kanan, tag ul maupun ol
dl-horizontal : Untuk membuat pairing bagus buat form nih, perhatikan tagnya, lihat contoh di bawah

```

![ListStyle](https://github.com/elvinotan/bootstrap-3/blob/master/images/liststyle.png)

# Bootstrap Tutorial #12 - Button Styles

```
Untuk buttton memiliki beberapa stuktur class
Class dasar button : btn
Class tampilan button : btn-default, btn-primary, btn-info, btn-warning, btn-danger, btn-success
Class button di press : active
Class button disable : disabled
```

![Button](https://github.com/elvinotan/bootstrap-3/blob/master/images/button.png)

# Bootstrap Tutorial #13 - Bootstrap Image Styles

```
Image memiliki bebrapa style mungkin di kita perlukan :
img-responsive : Bila dalam row ada image yang saling overlap gunakan class ini
img-rounded : Membuat gambar menjadi kotak dgn pinggil2nya rounded
img-circle : Membuat gambar menjadi bulat
img-thumbnail : Membuat small border yang mengelilingi gambar
center-block : Membuat gambar center align
```

![Image](https://github.com/elvinotan/bootstrap-3/blob/master/images/image.png)

# Bootstrap Tutorial #14 - Visibility

```
Visibility
digunaan untuk show and hide compoennt
hidden-xs : Bila mencapai ukuran extra small maka akan di hide, selain itu show
hidden-lg : Bila mencapai ukuran large maka akan di hide, selain itu show

visible-md : Bila ukuran mencapai medium akan di tampilkan, selain itu hide
visible-md-inline : Menampilkan saat medium dan menjadi horizontal, dengan respect ke size
visible-md-inline-block: Menampilkan saat medium dan menjadi horizontal dgn strach
```

# Bootstrap Tutorial #15 - Drop-down Menu's

```
Untuk dropdown component bootstrap tidak menggunakna component select, tetapi menggunakan component button dan ul>li
untuk menggunakan dropdown button dan ul harus di bungkus dengan div dgn class dropdown selai itu ada juga class:
a. dropdown-togger : togger button class saat di click dan saat release
b. dropdown-menu : style member yang akan muncul saat button di click
c. dropdown-header : Header pada bagian option
```

![DropDown](https://github.com/elvinotan/bootstrap-3/blob/master/images/dropdown.png)

# Bootstrap Tutorial #16 - Tabs and Pills (navigation)

```
Tab dan Pill di gunakan untuk keperluan menu, intinya membuat ul dan li, lalu gunakan class untuk decorasi</br>
nac = Class dasar navigasi
nav-tabs = Class navigasi berbentuk tabs
nav-pills = Class navigasi berbentuk pills
nav-stacked = Class agar menu berbentuk Vertical
nav-justified = Class agar menu berbentuk Horizontal dan memiliki with yang sama
active = Class pada li, untuk menunjukan menu yang active yang mana
```

![TabsPills](https://github.com/elvinotan/bootstrap-3/blob/master/images/tabsnpill.png)

# Bootstrap Tutorial #17 - Navbars

```
Mirip dgn Tabs and Pill tapi ini lebih di peruntukan Navigasi besar
Untuk cara pakai lihat class di bawh ini
```

![Nav](https://github.com/elvinotan/bootstrap-3/blob/master/images/nav.png)

# Bootstrap Tutorial #18 - Navbar Classes

```
Ternyata untuk nav memiliki header yaitu bagian di sebelah kirin dan footer di bagian kanan
Perhatian gambar di bawah untuk mencari lebih tau
```

![NavBarClass](https://github.com/elvinotan/bootstrap-3/blob/master/images/navbrclass.png)

# Bootstrap Tutorial #19 - Mobile Navbars

```
Nav yang sudah kita buat di atas masih blm support untuk mobile, contoh menunya saling rapat atau melah vertical,
untuk mobile kita akan buat sebuah button di sisi kanan atas yang kalo di click menu akan keluar
```

![MobileNav](https://github.com/elvinotan/bootstrap-3/blob/master/images/mobilenav.png)

# Bootstrap Tutorial #20 - Jumbotrons

```
Jumbotron seperti article tapi yang eye catching sehingga menarik perhatian,
cukup di wrap dalam div dan beri class jumbotron
```

![JumboTron](https://github.com/elvinotan/bootstrap-3/blob/master/images/jumbotron.png)

# Bootstrap Tutorial #21 - Styling Forms

```
Style untuk merapihkan form, lihat contoh di bawah
```

![Form](https://github.com/elvinotan/bootstrap-3/blob/master/images/form.png)

# Bootstrap Tutorial #22 - Badges & Labels

```
Cara menggunakan badge
```

![Form](https://github.com/elvinotan/bootstrap-3/blob/master/images/badge.png)

# Bootstrap Tutorial #23 - Panels

```
Cara menggunakan panel dan classnya
```

![Form](https://github.com/elvinotan/bootstrap-3/blob/master/images/badge.png)

# Bootstrap Tutorial #24 - Tooltips

```
Cara menggunakan tooltips
```

![ToolTips](https://github.com/elvinotan/bootstrap-3/blob/master/images/tooltip.png)

# Bootstrap Tutorial #25 - Carousels

```
Cara menggunakan Corusel, aga jelimet tapi lihat saja classnya
```

![Corusel](https://github.com/elvinotan/bootstrap-3/blob/master/images/corusel.png)

# Bootstrap Tutorial #26 - Modal Pop-ups

```
Penting !!! cara menggunakan modal popup
```

![Modal](https://github.com/elvinotan/bootstrap-3/blob/master/images/modal.png)

# Bootstrap Tutorial #27 - Accordions

```
Penting !!! cara menggunakan modal acordion
```

![Acordion](https://github.com/elvinotan/bootstrap-3/blob/master/images/acordion.png)

# Bootstrap Tutorial #28 - Bootstrap Themes

```
Dengan bootstrap kita bisa ganti theme dengan mudah tinggal download themes dari website di bawah ini
download dan include ke html otomatis langsung change
```

![Themes](https://github.com/elvinotan/bootstrap-3/blob/master/images/theme.png)
