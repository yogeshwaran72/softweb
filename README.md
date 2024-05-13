# Ex.07 Software Product Company Website
## Date:10.3.2024

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

home.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Company</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-image: url(https://img.freepik.com/free-vector/realistic-neon-lights-background_23-2148907367.jpg);
            background-size: cover;
        }

        header {
            background-color: rgba(51, 51, 51, 0.7); 
            color: #fff;
            padding: 10px 0;
            display: flex; 
            justify-content: space-between; 
            align-items: center; 
            font-family: 'verdana', 'verdana';
        }

        nav {
            overflow: hidden;
            background-color: #2478a1;
        }

        nav a {
            float: right;
            display: block;
            color: #fff;
            text-align: left;
            padding: 15px 20px;
            text-decoration: none;
        }

        .company-name {
            font-size: 40px;
            margin: 20px;
        }

        nav a:hover {
            background-color: rgba(111, 205, 248, 0.7); 
            color: #333;
        }

        .content {
            padding: 100px 0px 200px; 
            color:#fff;
            text-align: left;
            font-size: 50px; 
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1 class="company-name">Tech Innovations </h1>
</header>

<nav>
    <a href="contact.html">Contact us</a>
    <a href="products.html">Products</a>
    <a href="people.html">People</a>
    <a href="home.html">Home</a>
</nav>

<div class="content">
    <div class="company-description">
        <pre>
            Build skills
            as you learn
            with over
            many people here.
        </pre>
    </div>
</div>

<footer>
    &copy; Created and developed by Jaswanth
</footer>

</body>
</html>
people.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Team</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #0e0442;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }

        .team-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }

        .person {
            width: 250px;
            margin: 20px;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .person img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-bottom: 10px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>OUR TEAM</h1>
</header>

<div class="team-container">
    <div class="person">
        <img src="https://www.fcbarcelona.com/photo-resources/2020/02/19/d8f54b57-05d8-46bc-854e-014d7a9a9e46/2635_01_24.jpg?width=1200&height=750" alt="Person 1">
        <h3>Maridona</h3>
        <p>CEO</p>
    </div>

    <div class="person">
        <img src="https://ktastro.blob.core.windows.net/images/Celebrity/BillGates.png" alt="Person 2">
        <h3>Bill Gates</h3>
        <p>COO</p>
    </div>

    <div class="person">
        <img src="https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcQGeAGP53IJZqX6XC212fwBCpiWuOYVez3ABH7v5UvucwXOHRxM" alt="Person 3">
        <h3>Ratan Tata</h3>
        <p>CTO</p>
    </div>

    <div class="person">
        <img src="https://media.npr.org/assets/img/2023/01/09/scott_edit_toned-2_custom-2bf7c35edc7c77a1766950f8fa8d6ca56a1523c8.jpg?s=1100&c=50&f=jpeg" alt="Person 4">
        <h3>MacKenzie Scott</h3>
        <p>Marketing Manager</p>
    </div>

    <div class="person">
        <img src="https://cdn.britannica.com/09/225009-050-9BA6E880/French-businessman-Bernard-Arnault-2017.jpg" alt="Person 5">
        <h3>bernard arnault</h3>
        <p>Product Manager</p>
    </div>

    <div class="person">
        <img src="https://c.ndtvimg.com/2024-03/339tnn4_sini-shetty_625x300_09_March_24.jpg" alt="Person 6">
        <h3>sini chetty</h3>
        <p>Software Engineer</p>
    </div>
</div>

<footer>
    <p>&copy; Created and developed by jaswanth</p>
</footer>

</body>
</html>
products.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PRODUCT CATALOG</title>
    <style>
        body {
            font-family: 'Verdana';
            margin: 0;
            padding: 0;
            background-image: url(back.jpg);
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }

        .product-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }

        .product {
            color: #d53299;
            width: 200px;
            margin: 20px;
            padding: 10px;
            text-align: center;
        }

        .product img {
            width: 150px;
            height: 150px;
            margin-bottom: 10px;
        }

        .product-details{
            background-color: #1990e5;
            padding: 10px;
            border-radius: 5px;
        }

        footer {
            background-color: #333;
            color: #0db460;
            text-align: center;
            padding: 5px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>PRODUCT CATALOG</h1>
</header>

<div class="product-container">
    <div class="product">
        <img src="https://img-prod-cms-rt-microsoft-com.akamaized.net/cms/api/am/imageFileData/RW16TLT?ver=99ac&q=90&m=6&h=705&w=1253&b=%23FFFFFFFF&f=jpg&o=f&p=140&aim=true" alt="Product 1">
        <h3>Product 1</h3>
        <p>Laptop</p>
    </div>

    <div class="product">
        <img src="https://images.samsung.com/is/image/samsung/p6pim/in/2401/gallery/in-galaxy-s24-sm-s921blbcins-thumb-539572328" alt="Product 1">
        <h3>Product 2</h3>
        <p>Mobile</p>
    </div>

    <div class="product">
        <img src="https://www.livemint.com/lm-img/img/2023/09/23/600x338/rhh_1695470152346_1695470161360.jpg" alt="Product 1">
        <h3>Product 3</h3>
        <p>Watches</p>
    </div>

    <div class="product">
        <img src="https://sony.scene7.com/is/image/sonyglobalsolutions/wh-ch520_Primary_image?$categorypdpnav$&fmt=png-alpha" alt="Product 1">
        <h3>Product 4</h3>
        <p>Earphones</p>
    </div>

    <div class="product">
        <img src="https://i.pinimg.com/originals/e7/5d/db/e75ddbda351d44e24b6b8099fa200aad.jpg" alt="Product 1">
        <h3>Product 5</h3>
        <p>camera</p>
    </div>

    <div class="product">
        <img src="https://p3-ofp.static.pub/ShareResource/na/tablets-splitter/featured-cards/lenovo-tab-p11-android-tablets.png" alt="Product 1">
        <h3>Product 6</h3>
        <p>Tablets</p>
    </div>

</div>

<footer>
    <p>&copy; Created and developed by Jaswanth.</p>
</footer>

</body>
</html>
contact.html 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #112f4d;
        }

        header {
            background-color: #343a40;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }

        .contact-container {
            max-width: 800px;
            margin: 0 auto;
            padding: 50px 20px;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }

        .contact-info {
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
            padding: 40px;
            flex: 1;
            margin-right: 20px;
        }

        .contact-info h2 {
            color: #343a40;
            font-size: 28px;
            margin-bottom: 20px;
        }

        .contact-info p {
            color: #6c757d;
            font-size: 18px;
            margin-bottom: 10px;
        }

        .contact-info p:last-child {
            margin-bottom: 0;
        }

        .contact-info a {
            color: #007bff;
            text-decoration: none;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        #map {
            flex: 1;
            border-radius: 10px;
            overflow: hidden;
        }

        footer {
            background-color: #343a40;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Contact Us</h1>
</header>

<div class="contact-container">
    <div class="contact-info">
        <h2>Company Name</h2>
        <p><strong>Address:</strong> 123 Elm Street, Springfield, IL 62701, United States</p>
        <p><strong>Email:</strong> <a href="mailto:info@example.com">techinnovation@gmail.com</a></p>
        <p><strong>Phone:</strong> <a href="tel:+15551234567">+1 (555) 123-4567</a></p>
        
    </div>
    <div id="map">
        <!-- Google Maps embed code goes here -->
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3022.554458216143!2d-89.64965458458049!3d39.7836443908857!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x88762e1e50fc0adf%3A0x2f7d3bc20b9e6b18!2s123%20Elm%20St%2C%20Springfield%2C%20IL%2062701%2C%20USA!5e0!3m2!1sen!2suk!4v1621469930245!5m2!1sen!2suk" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </div>
</div>

<footer>
    <p>&copy; Created and developed by Jaswanth</p>
</footer>

</body>
</html>


## OUTPUT:

![image](https://github.com/yogeshwaran72/softweb/assets/153492924/8325b9ad-b1e3-4c72-afbf-b39c7c870375)
![image](https://github.com/yogeshwaran72/softweb/assets/153492924/05e72ece-22cf-4c00-8652-8972d0b505f4)
![image](https://github.com/yogeshwaran72/softweb/assets/153492924/18ea7690-fb56-4b15-91ef-ed91a9e29dca)
![image](https://github.com/yogeshwaran72/softweb/assets/153492924/3d94341d-a8e0-4e17-8389-1e5f7ee3aa14)





## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
