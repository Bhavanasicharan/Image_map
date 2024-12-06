# Ex04 Places Around Me
# Date:
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
'''
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="viewport"
        content="width=device-width,initial-scale=1.0">
        <style>
        
        .bookpage{
            width: 400px;
            height: 600px;
            color: rgb(229, 14, 14);
            margin-left: auto;
            margin-right: auto;
            padding:20px;
            font-family: 'Times New Roman', Times, serif;
            background-image: linear-gradient(rgb(0, 255, 229), rgb(255, 192, 247)), url('../images/back.png');
            background-size: cover;
        }

        .insight{
            color: rgba(10, 1, 18, 0.29);

        }

        .hrstyle{
            width: 100px;
        }

        .author{
            color: rgb(37, 4, 51);
            display: inline;
            position: relative;
            color: rgb(0, 17, 255);
            top: 190px;

            font-family: Georgia, 'Comic Sans MS', Times, serif;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        }

        .id{
            width: 400px;
            position: relative;
            top: 180px;

        }

        .pub{
            font-size: medium;
            position: relative;
            top: 155px;
            left: 330px;
        }
        .ed{
            color: rgb(182, 61, 13);
            font-size: medium;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            position: relative;
            top: 85px;

        }
        .subtile{
            font-family: Tahoma;
            font-size: large;
            text-align: center;  
            position: relative;
            top: 40px;
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
                SEC INSIGHTS
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(0, 255, 166);">
            </div>
            <div class="booktitle">
                <h1>CSS and HTML</h1>
            </div>
            <div class="subtitle">
            and <br> javascript demystified
            </div>
            <div class="mypic">
                <img src="swan.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: rgb(0, 17, 255);">
            </div>
            <div class="author">
                <p><b> B.Charan reddy</b></p>
            </div>
            <div class="pub">
                Saveetha<br> Engineering<br> College 
            </div>
            <div class="ed">
                <b>Extended Edition</b><br>
            </div>
        </div>
    </body>
</html>
'''
# OUTPUT
![Screenshot 2024-12-06 233533](https://github.com/user-attachments/assets/974ccec7-4fbe-4a84-b530-1516cdabc713)


# RESULT
The program for implementing image maps using HTML is executed successfully.
