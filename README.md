# Ex.06 Book Front Cover Page Design
## Date:5/10/25

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
```

shoba.html

<head>
    <title>Book Cover</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body> 
    <div class="background">
      <div class="inner">
        <div class="title">
        <p>SEC Insights</p>
        <hr>
        <br><br>
        <h1 align="center">Full of Computer world</h1>
        <br>
        <p class="sub">Communicate with computer</p>
      </div>
      <div class="footer">
        <div class="edition-section">
          <h3 class="edition">MY EDITION</h3>
          <img src="shobana/coverapp/static/my pic.png" class="image" alt="Author Photo">
        </div>
        <hr class="line">
        <div class="footer-text">
          <p class="left-text">AANCY AKSHARESHA A</p>
          <p class="right-text">SAVEETHA ENGINEERING COLLEGE</p>
        </div>
      </div>
    </div>
  </div>
  </body>
</html>

style.css

body{
    display: flex;
    justify-content: center;
    color:purple
}
.background{
    height: 600px;
    width: 400;
    margin-top: 25px;
    background-image:url("back g.jpg");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    position: relative;
    padding:9px;
}
.inner{
    width: 400px;
    height:600px;
    border: 3px solid rgb(200,170,230)

}
.title{
    margin: 4px
}
.sub{
    font-size: large;
}
.footer{
    margin: 4px;
    position: absolute;
    bottom: 25px;
    left: 18px;
    right: 18px;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;

}
.edition-section{
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
}
.image{
    width: 100px;
    height: auto;

}
.footer-text{
    display: flex;
    justify-content: space-between;
    font-weight: bold;
    font-size: 13px;
}
```
## OUTPUT:
![alt text](<Screenshot (21).png>)




## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
