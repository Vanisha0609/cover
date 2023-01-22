# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
clone the GitHub repository and create a Django admin interface

### Step 2:
write HTML and CSS code for designing book cover and execute them.
## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/back.jpg);
            background-size: cover;
        }
            

        .insight{
            color: gray;

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: red;
            top:190px;
            
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
            top:180px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:whitesmoke;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color:gray ;">
            </div>
            <div class="booktitle">
                <h1>THE NIGHT OF THE MURDER</h1></div>
            <div class="subtitle">
                What a blast.Weird murders,creepy villians,fiendish puzzles
                -what more could you want from a book?
            </div>
            <div class="mypic">
                <img src="/static/images/my.png" width="170" height="180" alt="">
            </div>
            <div class="id">
                <hr style="color: whitesmoke;">
            </div>
            <div class="author">
               <p><b>VANISHA</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>book1</b>
            </div>

        </div>
    </body>
</html>
```

## Output:
![OUTPUT](./out.png)

# HTML Validator 
![HTML Validator](./valid.png)

## Result:
The program for designing book cover page using HTML and CSS is executed sucessfully
