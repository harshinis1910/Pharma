# Ex.07 Software Product Company Website
## Date:

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
```
PEOPLE.HTML
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jai Pradhiksha</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
    /*background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQWuaguLIFTiHsLYyNqiNpqcNLpzWMXHvbcBQ&s');*/
    margin: 0;
    padding: 0;
  }
  .container {
    max-width: 1200px;
    margin: 20px auto;
    padding: 0 20px;
  }
  .product {
    width: calc(20% - 20px);
    background-color: #fff;
    border-radius: 8px;
    padding: 20px;
    margin: 10px;
    display: inline-block;
    box-sizing: border-box;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
  .product img {
    width: 100%;
    height: 200px; 
    object-fit: cover;
    border-radius: 4px;
  }
  .product h2 {
    margin-top: 0;
  }
  .search-bar {
    width: 100%;
    background-color: #fff;
    padding: 10px 20px;
    border: 1px solid #ddd;
    border-radius: 4px;
    margin-bottom: 20px;
    box-sizing: border-box;
  }
  header {
    padding-top: 10px 20px;
    background-color: red;
    
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  header img {
    width: 1000px;
  }
  .right-end {
    display: flex;
    align-items: center;
  }
  .right-end span {
    margin-left: 20px;
  }
</style>
</head>
<body>
<header>
  <div class="container">
    <h1 style="color: #fff;">People</h1>
    <div class="right-end">
      <span style="margin-left: 1200px; color:#fff">Login</span>
    </div>
  </div>
</header>
<div class="container">
  <input type="text" class="search-bar" placeholder="Search for people...">
  <div class="product">
    <img src="data:image/jpeg;base64,/ alt="Product 1">
    <h2>Bill gates</h2>
    <p>American businessman, investor, philanthropist, and writer best known for co-founding the software giant Microsoft.</p>
  </div>
  <div class="product">
    <img src="https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcSVvdf3mtAr8BQaBqwu2wAFbJD1dH6jtmyAK7hZRRnbFc0yc_pT"/>
        <h2>Jeff Bezos</h2>
        <p>American businessman, media proprietor and investor. He is the founder, executive chairman, and former president and CEO of Amazon.</p>
  </div>
  <div class="product">
    <img src="https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcS0U5a32I81EyodYLVvHBNs7GSlBgmag51JRMz_0RQ2DqthEDKr"/>
    <h2>Warren Buffet</h2>
    <p>American businessman, investor, and philanthropist who currently serves as the co-founder, chairman and CEO of Berkshire Hathaway.</p>
    </div>
  <div class="product">
    <img src="https://t3.gstatic.com/licensed-image?q=tbn:ANd9GcTqfkApl2zCLk_pG2PwOqSQd4dz0BFGndlyQJQg-an2EsqDcfLjvNQMkIv1mxyJCWzL"/>
    <h2>Larry Page</h2>
    <p>American businessman, computer scientist, and internet entrepreneur best known for co-founding Google with Sergey Brin.</p>
  </div> 
</div>
<footer style="position: fixed; left: 0; bottom: 0; width: 100%; padding-top: 20px; padding-bottom: 20px; background-color: red
; color: #fff; text-align: center;">
  Namitha
</footer>
</body>
</html>

 PRODUCT.HTML

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jai Pradhiksha</title>
<style>
  body {
    font-family: Arial, sans-serif;
    /*background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQWuaguLIFTiHsLYyNqiNpqcNLpzWMXHvbcBQ&s');*/
    background-color: #f5f5f5;
    margin: 0;
    padding: 0;
  }
  .container {
    max-width: 1200px;
    margin: 20px auto;
    padding: 0 20px;
  }
  .product {
    width: calc(20% - 20px);
    background-color: #fff;
    border-radius: 8px;
    padding: 20px;
    margin: 10px;
    display: inline-block;
    box-sizing: border-box;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
  .product img {
    width: 100%;
    border-radius: 4px;
  }
  .product h2 {
    margin-top: 0;
  }
  .search-bar {
    width: 100%;
    background-color: #fff;
    padding: 10px 20px;
    border: 1px solid #ddd;
    border-radius: 4px;
    margin-bottom: 20px;
    box-sizing: border-box;
  }
  header {
    padding-top: 10px 20px;
    background-color: red;
    
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  header img {
    width: 1000px;
  }
  .right-end {
    display: flex;
    align-items: center;
  }
  .right-end span {
    margin-left: 20px;
  }
</style>
</head>
<body>
<header>
  <div class="container">
    <div class="right-end">
      <span style="margin-left: 1200px; color:#fff">Login</span>
    </div>
  </div>
</header>
<div class="container">
  <input type="text" class="search-bar" placeholder="Search for products...">
  <div class="product">
    <img src="https://5.imimg.com/data5/SELLER/Default/2021/9/HR/PW/SE/32162519/vivo-mobile-phone.png" alt="Product 1">
    <h2>Mobiles</h2>
  </div>
  <div class="product">
    <img src="data:image/jpeg;base64,alt="Product 1">
    <h2>Lipsticks</h2>
  </div>
  <div class="product">
    <img src="https://images-eu.ssl-images-amazon.com/images/G/31/img23/Softlines_JWL_SH_GW_Assets/2024/May/8th/QC_Watch-PC2low._SY116_CB558385574_.jpg" alt="Product 1">
    <h2>Watches</h2>
  </div>
  <div class="product">
    <img src="https://images-eu.ssl-images-amazon.com/images/G/31/img19/OOC/Gateway/wk_19/PC_CC_379x304-1._SY304_CB558452919_.jpg" alt="Product 1">
    <h2>Accesories</h2>
  </div>

  <div class="product">
    <img src="https://m.media-amazon.com/images/I/51RXzjrUmkL._AC_SY200_.jpg" alt="Product 2">
    <h2>Kitchen Products</h2>
  </div>
  <div class="product">
    <img src="https://images-eu.ssl-images-amazon.com/images/G/31/Symbol/2024/GW_Mar/25th/Combo_low_res_2_1_1_1_1._SY304_CB579829084_.jpg" alt="Product 2">
    <h2>Clothings</h2>
  </div>
  <div class="product">
    <img src="https://m.media-amazon.com/images/I/81S6A4v-waL._AC_SY200_.jpg" alt="Product 2">
    <h2>Electronics</h2>
  </div>
  <div class="product">
    <img src="https://images-eu.ssl-images-amazon.com/images/G/31/img23/Softlines_JWL_SH_GW_Assets/2024/May/8th/QC_Jewl-PCLow._SY116_CB558385574_.jpg" alt="Product 2">
    <h2>Jewellery</h2>
  </div>
  
</div>
<footer style="position: fixed; left: 0; bottom: 0; width: 100%; padding-top: 20px; padding-bottom: 20px; background-color: red; color: #fff; text-align: center;">
  Namitha
</footer>
</body>
</html>

 CONTACT.HTML

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jai Pradhiksha</title>
<style>
  body {
    font-family: Arial, sans-serif;
    /*background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQWuaguLIFTiHsLYyNqiNpqcNLpzWMXHvbcBQ&s');*/
    background-color: #f5f5f5;
    margin: 0;
    padding: 0;
  }
  .container {
    max-width: 1200px;
    margin: 20px auto;
    padding: 0 20px;
  }
  header {
    padding-top: 10px 20px;
    background-color: red;
    
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  header img {
    width: 1000px;
  }
  .right-end {
    display: flex;
    align-items: center;
  }
  .right-end span {
    margin-left: 20px;
  }
</style>
</head>
<body>
<header>
  <div class="container">
    <h1 style="color: #fff;">Contact Us</h1>
    <div class="right-end">
      <span style="margin-left: 1200px; color:#fff">Logout</span>
    </div>
  </div>
</header>
<div class="container">
    <div class="card" style="margin-top: 300px;">
        <h2 style="color: red;">Contact Details</h2>
        <div class="contact-info">
          <p>Email: namitha@gmail.com</p>
          <p>Phone: +1234567890</p>
          <p>Address: 123 Street, Chennai, India</p>
        </div>
      </div>
</div>
<footer style="position: fixed; left: 0; bottom: 0; width: 100%; padding-top: 20px; padding-bottom: 20px; background-color: red; color: #fff; text-align: center;">
  Namitha
</footer>
</body>
</html>
```
## OUTPUT:
![WhatsApp Image 2024-05-13 at 10 55 01](https://github.com/NamithaS2710/softweb/assets/133190822/f441a413-7813-43e8-96c4-cda0a40cc0d9)
![WhatsApp Image 2024-05-13 at 10 57 14](https://github.com/NamithaS2710/softweb/assets/133190822/e2c86f55-c3ea-4b8c-9886-eafb8c3db11a)
![WhatsApp Image 2024-05-13 at 10 59 33](https://github.com/NamithaS2710/softweb/assets/133190822/e087dbfa-6052-4e85-a61f-ee1b2f7c5c11)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
