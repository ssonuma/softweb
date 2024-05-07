# Ex.07 Software Product Company Website
## Date: 07.05.24

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:

### soft.html
```
<!DOCTYPE html>
<html>
<head>
<title>SDev Company</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #fff;
        }
        header {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            color: #007bff;
            padding: 10px;
            text-align: center;
        }
        nav {
            background-color: #222;
            padding: 10px;
            text-align: center;
        }
        nav a {
            margin: 0 40px;
            text-decoration: none;
            color: #fff;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #007bff;
        }
        footer {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .content {
            padding: 20px;
            text-align: center;
        }
        h2 {
            color: #fff;
            text-decoration: underline;
            transition: color 0.3s;
        }
        h2:hover {
            color: #007bff;
        }
        p {
            color: #ffffff;
            margin-bottom: 20px; 
            font-size: 20px;
          }
        .image-container {
            display: fill;
            justify-content: space-around;
            margin-bottom: 20px; 
                         }
        .image-container img {
            max-width: 80%; 
            border-radius: 8px; 
        }
        p1 {
            color: #fff  ;
            margin-bottom: 20px; 
            font-size: 15px;
          }
    </style>
</head>
<body>
    <header>
        <h1>SDev Company</h1>
    </header>
    <nav>
        <a href="soft.html">Home</a>
        <a href="products.html">Products</a>
        <a href="council.html">Council</a>
        <a href="contact_us.html">Contact Us</a>
    </nav>
    <div class="content">
        <h2>About Our Company</h2>
        <p>
            Our SDev company specializes in creating tailored software solutions for diverse clients,<br>
            spanning industries like healthcare, finance, and e-commerce. Utilizing a range of technologies<br>
            and methodologies such as Agile and Scrum, these companies employ multidisciplinary teams of<br>
            software engineers, designers, and project managers to deliver high-quality products. Offering<br>
            services including <strong>custom software development, web and mobile app development, and quality assurance,</strong><br>
            they prioritize customer satisfaction through close collaboration, iterative development cycles, and<br>
            rigorous testing processes. Continuously adapting to emerging technologies and industry trends, software<br>
            development companies strive for innovation, efficiency, and excellence in delivering robust and reliable<br>
            software solutions to meet the evolving needs of their clients.
        </p>
        <div class="image-container">
            <img src="image.jpg" alt="Image 1">
            <img src="image2.jpg" alt="Image 2">
        </div>
    </div>
    <footer>
        <p1>&#169SONU S [212223220107]~SEC</p1>
    </footer>
</body>
</html>
```

### products.html
```
<!DOCTYPE html>
<html>
<head>
    <title>SDev Company - Products</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #fff;
        }
        header {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            color: #007bff;
            padding: 10px;
            text-align: center;
        }
        nav {
            background-color: #222;
            padding: 10px;
            text-align: center;
        }
        nav a {
            margin: 0 40px;
            text-decoration: none;
            color: #fff;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #007bff;
        }
        footer {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .content {
            padding: 20px;
            text-align: center;
        }
        h2 {
            color: #fff;
            text-decoration: underline;
            transition: color 0.3s;
        }
        h2:hover {
            color: #007bff;
        }
        p {
            color: #ffffff;
            margin-bottom: 20px; 
            font-size: 20px;
        }
        .image-container {
            display: fill;
            justify-content: space-around;
            margin-bottom: 20px; 
        }
        .image-container img {
            max-width: 80%; 
            border-radius: 8px; 
        }
        .product {
            display: inline-block;
            width: 45%;
            margin: 10px;
            text-align: center;
        }
        .product img{
           max-width: 100%;
           height: auto;
           border-radius: 50%;
        }
        .product h3 {
            color: #fff;
        }
        .product p {
            color: #007bff;
            font-size: 18px;
        }
        p1 {
            color: #fff;
            margin-bottom: 20px; 
            font-size: 15px;
        }
    </style>
</head>
<body>
    <header>
        <h1>SDev Company - Products</h1>
    </header>
    <nav>
        <a href="soft.html">Home</a>
        <a href="products.html">Products</a>
        <a href="council.html">Council</a>
        <a href="contact_us.html">Contact Us</a>
    </nav>
    <div class="content">
    
        <h2>Our Products</h2>

        <div class="product">
            <img src="prod1.jpeg" alt="Python Programming" width="200" height="200">
            <h3>1. Accounting Software</h3>
            <p>Price: $9999</p>
        </div>
        
        <div class="product">
            <img src="prod2.jpeg" alt="Python Programming" width="200" height="200">
            <h3>2. Tax Software</h3>
            <p>Price: $4999</p>
        </div>
        
        <div class="product">
            <img src="prod3.jpeg" alt="Python Programming" width="200" height="200">
            <h3>3. Bookkeeping Software</h3>
            <p>Price: $5999</p>
        </div>
        
        <div class="product">
            <img src="prod4.jpeg" alt="Python Programming" width="200" height="200">
            <h3>4. Time Tracking Software</h3>
            <p>Price: $3499</p>
        </div>
        
        <div class="product">
            <img src="prod5.jpeg" alt="Python Programming" width="200" height="200">
            <h3>5. Project Management Software</h3>
            <p>Price: $8999</p>
        </div>
        
        <div class="product">
            <img src="prod6.jpeg" alt="Python Programming" width="200" height="200">
            <h3>6. Customer Relationship Management Software</h3>
            <p>Price: $7999</p>
        </div>
        
        <div class="product">
            <img src="prod7.jpeg" alt="Python Programming" width="200" height="200">
            <h3>7. Communication Software</h3>
            <p>Price: $4499</p>
        </div>
        
        <div class="product">
            <img src="prod8.jpeg" alt="Python Programming" width="200" height="200">
            <h3>8. Website Building Software</h3>
            <p>Price: $6999</p>
        </div>
        
        <div class="product">
            <img src="prod9.jpeg" alt="Python Programming" width="200" height="200">
            <h3>9. Payment Transaction Software</h3>
            <p>Price: $7999</p>
        </div>
        
        <div class="product">
            <img src="prod10.jpeg" alt="Python Programming" width="200" height="200">
            <h3>10. Sales, Marketing, and PR Software</h3>
            <p>Price: $8999</p>
        </div>
        
        <div class="product">
            <img src="prod11.jpeg" alt="Python Programming" width="200" height="200">
            <h3>11. Medical software</h3>
            <p>Price: $9999</p>
        </div>
        
        <div class="product">
            <img src="prod12.png" alt="Python Programming" width="200" height="200">
            <h3>12. ERP Software</h3>
            <p>Price: $10999</p>
        </div>
        

    </div>
    <footer>
        <p1>&#169SONU S [212223220107]~SEC</p1>
    </footer>
</body>
</html>
```

### council.html
```
<!DOCTYPE html>
<html>
<head>
    <title>SDev Company - Council</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #fff;
        }
        header {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            color: #007bff;
            padding: 10px;
            text-align: center;
        }
        nav {
            background-color: #222;
            padding: 10px;
            text-align: center;
        }
        nav a {
            margin: 0 40px;
            text-decoration: none;
            color: #fff;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #007bff;
        }
        footer {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .content {
            padding: 20px;
            text-align: center;
        }
        h2 {
            color: #fff;
            text-decoration: underline;
            transition: color 0.3s;
        }
        h2:hover {
            color: #007bff;
        }
        p {
            color: #ffffff;
            margin-bottom: 20px; 
            font-size: 20px;
        }
        .image-container {
            display: fill;
            justify-content: space-around;
            margin-bottom: 20px; 
        }
        .image-container img {
            max-width: 80%; 
            border-radius: 8px; 
        }
        .product {
            display: inline-block;
            width: 45%;
            margin: 10px;
            text-align: center;
        }
        .product img{
           max-width: 100%;
           height: auto;
           border-radius: 50%;
        }
        .product h3 {
            color: #007bff;
        }
        p1 {
            color: #fff;
            margin-bottom: 20px; 
            font-size: 15px;
        }
    </style>
</head>
<body>
    <header>
        <h1>SDev Company - Council Members</h1>
    </header>
    <nav>
        <a href="soft.html">Home</a>
        <a href="products.html">Products</a>
        <a href="council.html">Council</a>
        <a href="contact_us.html">Contact Us</a>
    </nav>
    <div class="content">
    
        <h2>Our Members</h2>

        <div class="product">
            <img src="p1.jpeg" alt="Python Programming" width="200" height="200">
            <h3>person 1</h3>
        </div>
        
        <div class="product">
            <img src="p2.jpeg" alt="Python Programming" width="200" height="200">
            <h3>person 2</h3>
        </div>
        
        <div class="product">
            <img src="p3.jpeg" alt="Python Programming" width="200" height="200">
            <h3>person 3</h3>
        </div>
        
        <div class="product">
            <img src="p4.jpeg" alt="Python Programming" width="200" height="200">
            <h3>person 4</h3>
        </div>
        
        <div class="product">
            <img src="p5.jpeg" alt="Python Programming" width="200" height="200">
            <h3>person 5</h3>
        </div>
        
        <div class="product">
            <img src="p6.avif" alt="Python Programming" width="200" height="200">
            <h3>person 6</h3>
        </div>
           

    </div>
    <footer>
        <p1>&#169SONU S [212223220107]~SEC</p1>
    </footer>
</body>
</html>
```


### contact_us.html
```
<!DOCTYPE html>
<html>
<head>
    <title>SDev Company - Contact Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #fff;
        }
        header {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            color: #007bff;
            padding: 10px;
            text-align: center;
        }
        nav {
            background-color: #222;
            padding: 10px;
            text-align: center;
        }
        nav a {
            margin: 0 40px;
            text-decoration: none;
            color: #fff;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #007bff;
        }
        footer {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .content {
            padding: 20px;
            text-align: center;
        }
        h2 {
            color: #fff;
            text-decoration: underline;
            transition: color 0.3s;
        }
        h2:hover {
            color: #007bff;
        }
        p {
            color: #ffffff;
            margin-bottom: 20px; 
            font-size: 20px;
          }
        .image-container {
            display: flex;
            justify-content: space-around;
            margin-bottom: 20px; 
        }
        .image-container img {
            max-width: 80%; 
            border-radius: 8px; 
        }
        .contact-info {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;
        }
        .contact-item {
            margin: 20px;
            text-align: left;
        }
        .contact-item img {
            width: 40px;
            height: 40px;
            margin-right: 10px;
        }
        .contact-item p {
            margin: 0;
        }
        .contact-item p span {
            color: #007bff;
        }
        .contact-item p a {
            color: #007bff;
            text-decoration: none;
            display: block;
        }
        .contact-item p a:hover {
            text-decoration: underline;
        }
        p1 {
            color: #fff;
            margin-bottom: 20px; 
            font-size: 15px;
          }
    </style>
</head>
<body>
    <header>
        <h1>SDev Company - Connect with us through...</h1>
    </header>
    <nav>
        <a href="soft.html">Home</a>
        <a href="products.html">Products</a>
        <a href="council.html">Council</a>
        <a href="contact_us.html">Contact Us</a>
    </nav>
    <div class="content">
        <h2>Links</h2>
        <div class="contact-info">
            <div class="contact-item">
                <img src="phone.png" alt="Phone Logo">
                <p>Phone Number: <span>+91 9344103428</span></p>
            </div>
            <div class="contact-item">
                <img src="address.png" alt="Address Logo">
                <p>Address: <span>NO;60/A, Devasi st,Ganananmurthy Nagar,Ambattur,CH-53</span></p>
            </div>
            <div class="contact-item">
                <img src="linkedin.png" alt="LinkedIn Logo">
                <p>LinkedIn:</p>
                <ul>
                    <li><a href="https://www.linkedin.com/in/sonu06/" target="_blank">SONU S</a></li>
                </ul>
            </div>
            <div class="contact-item">
                <img src="instagram.jpeg" alt="Instagram Logo">
                <p>Instagram:</p>
                <ul>
                    <li><a href="https://www.instagram.com/___.sonu___.06/" target="_blank">___.sonu___.06</a></li>
                </ul>
            </div>
            <div class="contact-item">
                <img src="gmail.png" alt="Gmail Logo">
                <p>Gmail: <a href="mailto:ssonuma2006@gmail.com">ssonuma2006@gmail.com</a></p>
            </div>
        </div>
    </div>
    <footer>
        <p1>&#169 SONU S [212223220107] ~SEC</p1>
    </footer>
</body>
</html>
```

## OUTPUT:

![SONU S  212223220107](https://github.com/ssonuma/softweb/assets/150653312/0221b4b1-6d70-4968-a645-322039222d9b)


![SONU S  212223220107  (1)](https://github.com/ssonuma/softweb/assets/150653312/df2f4f31-2e6f-4c45-8144-553b66d07f2b)



![SONU S  212223220107  (2)](https://github.com/ssonuma/softweb/assets/150653312/8e53f462-4cdc-4a95-8c4b-1f471506a0b0)


![SONU S  212223220107  (3)](https://github.com/ssonuma/softweb/assets/150653312/a490e43b-de3b-498f-8076-01edd7c0f792)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
