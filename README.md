# Ex.06 Book Front Cover Page Design
## Date:25.11.2023

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

cover.html

<style>
    .bookpage{
        width: 400px;
        height: 600px;
        color:rgb(247, 248, 248);
        margin-left: auto;
        margin-right: auto;
        padding: 20px;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        background-image: url(/static/cse.jpg);
        background-size: cover;
    }
        
    
    .insight{
        color: rgb(248, 10, 10);
    
    }
    
    
    .hrstyle{
        width:220px;
    }
    .author{
    
        display: inline;
        position: relative;
        color: rgb(0, 255, 200);
        top:200px;
        font-family:Georgia;
        font-size: medium;
    }
    .booktitle{
        font-family: 'Courier New', Courier, monospace;
        font-size: larger;
        text-align: center;
        position: relative;
        top: 30px;
    
    }
    .id {
        width:400px;
        position: relative;
        top:210px;
        
    }
    .pub{
        font-size: medium;
        position: relative;
        top:165px;
        left:330px;
    }
    .ed{
        color: rgb(229, 255, 0);
        font-size: medium;
        font-family: Verdana;
        position:relative;
        top:120px;
    
    }
    .subtitle{
        font-family:Tahoma;
        font-size: large;
        position: relative;
        top:60px;
    }
    .mypic{
        position: relative;
        top: 160px;
        left: 270px;
        width: 100px;
        height: 90px;
        background-size: cover;
    }
    </style>
    <title>Book Cover Page</title>
    </head>
    <body>
    <div class="bookpage">
        <div class="insight">
            DREAM DESIGN COMPETE WIN
        </div>
        <div class="hrstyle">
            <hr style="color: yellow;">
        </div>
        <div class="booktitle">
            <h1>HAND'S ON MOBILE WEB DEVELOPMENT USING HTML</h1></div>
        <div class="subtitle">
            HTML5 apps are designed to function on the smaller screens of handheld devices. They can be used with any standard web browser. 
        </div>
        <div class="mypic">
            <img src="/static/image.png" width="130" height="145" alt="">
        </div>
        <div class="id">
            <hr style="color: goldenrod;">
        </div>
        <div class="author">
           <p><b>BASKAR . J</b></p>
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            <b>Experience With :</b>
        </div>
    </div>
    </body>

```

## OUTPUT:

![Alt text](<baskar/Book Design.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
