# Ex.06 Book Front Cover Page Design
## Date:09.12.2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
COVER.HTML
```

<!DOCTYPE html>
<html>
<head>
<title>Bookcover</title>
<style>
.bookpage{
width: 400px;
height: 600px;
color:rgb(251, 255, 0);
margin-left: auto;
margin-right: auto;
padding: 20px;
font-family: ' Arial, sans-serif';
background-image: url(https://img.freepik.com/premium-photo/green-smoke_44272-5206.jpg);
background-size: cover;
}
.author{
display: inline;
position: relative;
color:rgb(255, 255, 255);
top:190px;
font-family:Georgia;
font-size: medium;
}
.booktitle{
color:rgb(214, 62, 35);
font-family: Roquen;
font-size: larger;
text-align: center;
position: relative;
top: 30px;
}
.id {
width:400px;
position: relative;
top:180px;
}
.ed{
color:rgb(255, 242, 0);
font-size: medium;
font-family: Verdana;
position:relative;
top:85px;
}
.mypic{
position: relative;
top: 135px;
left: 260px;
width: 90px;
height: 80px;
background-size:contain;
}
</style>
<title>Book Cover Page</title>
</head>
<body>
<div class="bookpage">
<div class="booktitle">
<h1> <font color="orange">I love it, I do it : A mans love towards his work.</h1></div></font>
<br>
<div class="subtitle">
<center> <font color="blue"> Do what you love </center></font>
</div>
<br>
<br>
<br>
<br>

<div class="mypic">
<img src="C:\Users\admin\Downloads\khamal image.jpg" width="90" height="90">
</div>
<div class="id">
<hr style="color:rgb(241, 235, 235)">
</div>
<div class="author">
<p><b>khamalraaj S</b></p>
</div>
<div class="ed">
<b>Special edition</b>
</div>
</div>
</body>
</html>
```
## OUTPUT:
![alt text](<Screenshot 2024-12-09 224118.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
