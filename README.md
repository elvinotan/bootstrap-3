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

# Bootstrap Tutorial #08 - Push & Pull

# Bootstrap Tutorial #09 - Clearfix

# Bootstrap Tutorial #10 - Text Styles

# Bootstrap Tutorial #11 - List Styles

# Bootstrap Tutorial #12 - Button Styles

# Bootstrap Tutorial #13 - Bootstrap Image Styles

# Bootstrap Tutorial #14 - Visibility

# Bootstrap Tutorial #15 - Drop-down Menu's

# Bootstrap Tutorial #16 - Tabs and Pills (navigation)

# Bootstrap Tutorial #17 - Navbars

# Bootstrap Tutorial #18 - Navbar Classes

# Bootstrap Tutorial #19 - Mobile Navbars

# Bootstrap Tutorial #20 - Jumbotrons

# Bootstrap Tutorial #21 - Styling Forms

# Bootstrap Tutorial #22 - Badges & Labels

# Bootstrap Tutorial #23 - Panels

# Bootstrap Tutorial #24 - Tooltips

# Bootstrap Tutorial #25 - Carousels

# Bootstrap Tutorial #26 - Modal Pop-ups

# Bootstrap Tutorial #27 - Accordions

# Bootstrap Tutorial #28 - Bootstrap Themes
