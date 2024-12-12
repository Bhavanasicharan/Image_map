# Ex04 Places Around Me
# Date:20-11-2024
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
```
map.html
<html>
    <head>
        <title>MY CITY</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>CHITTOOR</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>B.CHARAN(24009456)</b></font>
        </h3>
        <center>
            <img src="c:\Users\admin\Desktop\image.png" usemap="#image-map" >

            <map name="image-map">
                <area target="" alt="AXIS BANK ATM" title="AXIS BANK ATM" href="atm.html" coords="686,13,860,98" shape="rect">
                <area target="" alt="CHETTIAR SWEET STALL" title="CHETTIAR SWEET STALL" href="sweetstall.html" coords="689,230,901,335" shape="rect">
                <area target="" alt="HOTEL SINDHU TOWERS" title="HOTEL SINDHU TOWERS" href="hotel.html" coords="1032,304,1254,379" shape="rect">
                <area target="" alt="JOYALUKKAS JEWELLERY" title="JOYALUKKAS JEWELLERY" href="jewellery.html" coords="783,492,1026,567" shape="rect">
                <area target="" alt="VISHAL MEGA MART" title="VISHAL MEGA MART" href="mart.html" coords="925,822,1141,892" shape="rect">
            </map>
    </body>
</html>

atm.html
<html>
<body bgcolor="blue">
    <h1 align="center">
        <font  size="10" color="red">
            CHITTOOR
        </font>
    </h1>
    <h2 align="center">
        
        AXIS BANK ATM
    
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="atm.png" height="388" width="822" >
        </center>
        <br>
        <hr>
        <li>
            <font size="4">
                Axis Bank Limited, formerly known as UTI Bank (1993–2007), is an Indian multinational banking and financial services company headquartered in Mumbai, Maharashtra.
                 It is India's third largest private sector bank by assets and fourth largest by market capitalisation.
            </font>
        </li>
        <br>
        <li>
            <font size="4">
                The bank was founded on 3 December 1993 as UTI Bank, opening its registered office in Ahmedabad and a corporate office in Mumbai.
            </font>
        </li>
        <br>
        <li>
            <font size="4">
              The bank has its head officein Mumbai and Registered office inAhmedabad.It has 3304 branches,14,003 ATMs, and nine internationaloffices.
              The bank employs over 55,000people and had a market capitalization
            </font>
        </li>
    </h3>
</body>

</html>
 hotel.html

 <html>
<body bgcolor="pink">
    <h1 align="center">
        <font  size="10" color="red">
            CHITTOOR
        </font>
    </h1>
    <h2 align="center">
        
        HOTEL SINDHU TOWERS
    
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="hotel.png" height="388" width="822" >
        </center>
        <br>
        <hr>
        <li>
            <font size="4">
                Hotel Sindhu Towers, established in 2005 is a star hotel located at the heart of Chittoor. 
                It has introduced the concept of fine dining and top of the line lodging & boarding for the first time in Chittoor.
            </font>
        </li>
        <br>
        <li>
            <font size="4">
                It has also become a popular choice for tourists and visitors to Chittoor. With a wide range of menu options Hotel Sindhu Towers has remained at the forefront of culinary innovations. 
                In November, 2015, we have opened our newest property 'Honey Bee' to the public.  
            </font>
        </li>
        <br>
        <li>
            <font size="4">
                Honey Bee offers the freshest baked items, delicious Indian sweets, desserts, chaats and more. There is a gaming zone and spacious seating for you to spend some quality time with friends and family.
                 With the best of class lodging & boarding facilities
            </font>
        </li>
        <br>
        <li>
            <font size="4">
                it has become the No. 1 choice of stay for travelers on business and/or tourism.
                 Located at the heart of a city which serves as a hub for several major cities like Tirupathi, Vellore, Bangalore and Chennai, it is the perfect anchor for visitors of every variety.  
            </font>
        </li>
    </h3>
</body>

</html><html>
<body bgcolor="pink">
    <h1 align="center">
        <font  size="10" color="red">
            CHITTOOR
        </font>
    </h1>
    <h2 align="center">
        
        HOTEL SINDHU TOWERS
    
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="hotel.png" height="388" width="822" >
        </center>
        <br>
        <hr>
        <li>
            <font size="4">
                Hotel Sindhu Towers, established in 2005 is a star hotel located at the heart of Chittoor. 
                It has introduced the concept of fine dining and top of the line lodging & boarding for the first time in Chittoor.
            </font>
        </li>
        <br>
        <li>
            <font size="4">
                It has also become a popular choice for tourists and visitors to Chittoor. With a wide range of menu options Hotel Sindhu Towers has remained at the forefront of culinary innovations. 
                In November, 2015, we have opened our newest property 'Honey Bee' to the public.  
            </font>
        </li>
        <br>
        <li>
            <font size="4">
                Honey Bee offers the freshest baked items, delicious Indian sweets, desserts, chaats and more. There is a gaming zone and spacious seating for you to spend some quality time with friends and family.
                 With the best of class lodging & boarding facilities
            </font>
        </li>
        <br>
        <li>
            <font size="4">
                it has become the No. 1 choice of stay for travelers on business and/or tourism.
                 Located at the heart of a city which serves as a hub for several major cities like Tirupathi, Vellore, Bangalore and Chennai, it is the perfect anchor for visitors of every variety.  
            </font>
        </li>
    </h3>
</body>

</html>
jewellery.html

<html>
<body bgcolor="orange">
    <h1 align="center">
        <font  size="10" color="red">
            CHITTOOR
        </font>
    </h1>
    <h2 align="center">
        
        JOYALUKKAS JEWELLERY
    
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="jewellary.png" height="388" width="822" >
        </center>
        <br>
        <hr>
        <li>
            <font size="4">
                Joy Alukkas is an Indian businessman from Kerala. He is the chairman and managing director of Joyalukkas Group.
                 According to a 2023 Forbes report, he has a net worth of $4.4 billion.
        </li>
        <br>
        <li>
            <font size="4">
                Joy Alukkas is concentrated in overseas business and started trading in gulf countries. 
                Joy Alukkas' original name according to Malayali naming conventions was A. V. Joy.
            </font>
        </li>
        <br>
        <li>
            <font size="4">
                The Joyalukkas Group has also always believed that the people and the community within which it operates are the cornerstones.
                Its success and as such is actively involved in CSR (Corporate Social Responsibility) activities across the world.
            </font>
        </li>
    </h3>
</body>

</html>

mart.html

<html>
<body bgcolor="yellow">
    <h1 align="center">
        <font  size="10" color="red">
            CHITTOOR
        </font>
    </h1>
    <h2 align="center">
        
        VISHAL MEGA MART
    
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="mart.png" height="388" width="822" >
        </center>
        <br>
        <hr>
        <li>
            <font size="4">
                India’s largest fashion-led hypermarket chain, has risen to prominence with over 400 stores scattered across the country. 
                Founded in 2001 by Ram Chandra Agrawal,  the company started as a modest venture, primarily focused on offering ready-made apparel. 
            </font>  
        </li>
        <br>
        <li>
            <font size="4">
                Vishal Mega Mart has been a successful store enterprise founded by the highly inspirational person in Indian business world  
            </font>
        </li>
        <br>
        <li>
            <font size="4">
                Vishal Mega Mart has a history of ownership change, but the name of the founder-Ram Chandra Agarwal-is still alive in that organization.
            </font>
        </li>
    </h3>
</body>

</html>

sweetstall.html

<html>
<body bgcolor="purple">
    <h1 align="center">
        <font  size="10" color="red">
            CHITTOOR
        </font>
    </h1>
    <h2 align="center">
        
        SRI KARTHIKEYAN SWEET STALL

    </h2>
    <hr>
    <h3>
        <center> 
        <img src="sweet stall.png" height="388" width="822" >
        </center>
        <br>
        <hr>
        <li>
            <font size="4">

                Chettinad cuisine offers a variety of vegetarian and non-vegetarian dishes. Some of the popular vegetarian dishes LIKE;
                 include idiyappam, paniyaram, vellai paniyaram, karuppatti paniyaram, paal paniyaram, kuzhi paniyaram, kozhukatta, masala paniyaram, maavurundai, and athirasam.

            </font>
        <br>
        <li>
            <font size="4">

                One is lucky to eat like a Chettiar, they say in South India. Chettiars say it themselves. They say it because a Chettiar table is a groaning board but also because 
                the cuisine is uncommonly subtle and aromatic,  a heritage of Chettiar participation in the centuries-old spice trade
                
            </font>
        </li>
        <br>
        <li>
            <font size="4">

                Further non-vegetarian influences became entrenched in Chettiar food habits from the late 18th Century after they established businesses in Ceylon, Burma, the Dutch East Indies, French Indo-China and what is now Malaysia and Singapore. 
                So did non-vegetarian fare from other parts of India through which they traveled en route to their overseas businesses.

            </font>
        </li>
    </h3>
</body>

</html>
```
# OUTPUT
![alt text](image1.png)
![alt text](<Screenshot 2024-12-12 214316.png>)
![alt text](<Screenshot 2024-12-12 214351.png>)
![alt text](<Screenshot 2024-12-12 214431.png>)
![alt text](<Screenshot 2024-12-12 214459.png>)
![alt text](<Screenshot 2024-12-12 214525.png>)
# RESULT
The program for implementing image maps using HTML is executed successfully.
