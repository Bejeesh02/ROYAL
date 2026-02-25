<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Royal</title>
    <link rel="stylesheet" href="royal.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <style>
        *{
    margin: 0;
    scroll-behavior: smooth;
    font-family: Arial, Helvetica, sans-serif;
    box-sizing:border-box;
}
 .fist{
    background-color: yellowgreen;
    text-align: center;
    height: 50px;
    align-items: center;
    display: flex;
    justify-content: center;
    position: fixed;
    width: 100%;
    z-index: 10;
}
 nav{
    background-color: black;
    text-align: center;
    align-items: center ;
    justify-content: space-around;
    display: flex;
    width: 100%;
    height: 80px;
    position: sticky;
    top: 50px;
    z-index: 10;
    padding: 10px 20px;
}
.nav1{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    position: absolute;
    gap: 0px;
    top: 78px;
}
.navb{
    position: relative;
    height: 80px;
    align-items: center;
    display: flex;
    justify-content: space-around;
}
nav img{
    margin-left: 17%;
}
.navb:hover  .nav1{
    visibility: visible;
}
.navb .nav1{
    visibility: hidden;
}
.nav1 a button{
    width: 400px;
    margin-left: 40px;
    padding-top: 30px;
    padding-bottom: 30px;
    display: flex;
    justify-content: center;
    text-align: center;
    align-content: center;
    text-decoration: none;
}
.nav1 a{
    text-decoration: none;
    text-align: center;
    align-items: center;
}
.home{
    width: 100%;
    overflow: hidden;
}
.riding{
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    text-align: center;
    justify-content: center;
    padding-top: 40px;
    border-radius: 25px;
}
.riding img{
    width: 340px;
}
.rid{
    background-color: whitesmoke;
    padding-bottom: 3px;
    transition: 0.5s; 
}
.rid:hover{
    transform: scale(1.1);
    cursor: pointer;
}
.new{
    background-image: url(himalayan.jpg);
    background-position: center;
    background-repeat: no-repeat;
    height: 50vh;
    margin-top: 20px;
    padding-top: 250px;
    color: white;
    font-size: 30px;
    padding-left: 50px;
    margin-bottom: 30px;
}
.zoom {
    display: flex;
    width: 100%;
    overflow: hidden;
}
.zoom div img {
    width: 100%;
    height: 400px;
    transition: 0.3s;
}
.zoom div h4 {
    margin-top: -50px;
    color: white;
    padding-left: 50px;
    transition: 0.3s;
}
.zoom:hover div img {
    width: 300px;
    opacity: 0.6;
}
.zoom div:hover img {
    width: 100%;
    opacity: 1;
}
.zoom div:hover h4 {
    font-size: 40px;
    transition: 0.6;
}
.tnow{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 50px;
}
.tnow h4{
    font-size: 30px;
}
.tr{
    display: flex;
    gap: 20px;
    width: 100%;
    padding-left: 100px;
    flex-wrap: wrap;
    border-radius: 25px;
}
.trd{
    width: 250px;
    gap: 20px;
    margin-bottom: 20px;
}
.trd img{
    width: 100%;
    padding-bottom: 10px;
}
.trd p{
    height: 50px;
    align-items: center;
}
.trd button{
    background-color: black;
    color: white;
    border: 2px solid;
    width: 150px;
    height: 50px;
    transition: 0.5s;
}
.trd button:hover{
    background-color: white;
    color: black;
    cursor: pointer;
    border: 2px solid;
    transition: 0.7s;
}
.knowmore{
    background-image: url(bgimg.webp);
    height: 66vh;
    margin-bottom: 20px;
    color: white;
    font-size: 40px;
    padding-top: 60px;
    padding-left: 40px;
}
.knowmore button{
    font-size: 20px;
    background-color: black;
    color: white;
    text-align: center;
    border: 2px solid;
    transition: 0.5s;
}
.knowmore button:hover{
    background-color: white;
    color: black;
    cursor: pointer;
    border: 2px solid;
    transition: 0.7s;
}
.footer {
    background: #000;
    color: #fff;
    padding: 60px 40px;
    font-family: Arial, sans-serif;
}
.footer-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    gap: 40px;
}
.footer-col {
    flex: 1 1 230px;
}
.footer-col h3 {
    margin-bottom: 10px;
    font-size: 17px;
    font-weight: bold;
}
.footer-col ul {
    list-style: none;
    padding: 0;
}
.footer-col ul li {
    margin: 7px 0;
}
.footer-col a {
    color: #fff;
    text-decoration: none;
}
.footer-col a:hover {
    color: #ccc;
}
.footer-btn {
    display: block;
    padding: 18px;
    border: 1px solid #444;
    margin: 10px 0 20px;
    color: #fff;
    text-decoration: none;
    text-align: center;
    transition: 0.3s;
}
.footer-btn:hover {
    background: #222;
}
/* Newsletter Form */
.newsletter-box {
    display: flex;
    margin: 15px 0;
}
.newsletter-box input {
    flex: 1;
    padding: 12px;
    border: 1px solid #444;
    background: #111;
    color: #fff;
}
.newsletter-box button {
    width: 50px;
    border: none;
    background: #444;
    color: #fff;
    font-size: 22px;
    cursor: pointer;
}
.newsletter-box button:hover {
    background: #666;
}
.checkbox {
    display: flex;
    gap: 6px;
    margin: 10px 0 20px;
    font-size: 14px;
}
.footer-bottom {
    text-align: center;
    border-top: 1px solid #333;
    margin-top: 50px;
    padding-top: 25px;
}
.social-icons a {
    color: #fff;
    margin: 0 8px;
    text-decoration: none;
}
.social-icons a:hover {
    color: #aaa;
}
.back-top {
    display: block;
    margin-top: 10px;
    text-decoration: none;
    color: #fff;
}
.back-top:hover {
    color: #888;
}
@media (max-width: 768px) {
    .footer-container {
        flex-direction: column;
    }
}
    </style>

</head>
<body>
     <div class="fist"> UOTO 40% 0FF ON WINTERWEAR | SHOP NOW</div>
     <nav>
        
        <div class="navb">
            <img src="hamburger.png" alt="" height="50px" width="50px">
            <div class="nav1">
                <a href="#ride"><button>RIDING GEAR</button></a>
                <a href="#now"><button>LIFESTYLE APPAREL</button></a>
                <a href="#new"><button>NEW ARRIVALS</button></a>
                <a href=""><button>WOMENS'S WEAR</button></a>
                <a href=""><button>SPECIAL PRICES</button></a>
                <a href=""><button>MAKE IT YOURS</button></a>
                <a href=""><button>WARRANTY CLAIM</button></a>
            </div>
        </div>     
        <img class="img-fluid" src="logo.webp" alt="" >
        <div>
            <form class="d-flex">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form> 
        </div>
     </nav>
     <section>
        <div class="home">
            <img class="img-fluid" src="ban.webp" alt="">
        </div>
     </section>
     <section id="ride">
        <div class="riding">
            <div class="rid">
                <img src="Gloves_5.webp" alt="">
                <p style="font-size: 20px; padding-top: 10px;">
                    Gloves
                </p>
            </div>
             <div class="rid">
                <img src="Helmets_4.webp" alt="">
                <p style="font-size: 20px; padding-top: 10px;">
                    Helmets
                </p>
            </div>
             <div class="rid">
                <img src="L_S_Jacket.webp" alt="">
                <p style="font-size: 20px; padding-top: 10px;">
                    Jacket
                </p>
            </div>
            <div class="rid">
                <img src="Protector_01_Pending.webp" alt="">
                <p style="font-size: 20px; padding-top: 10px;">
                    Protector
                </p>
            </div>
            <div class="rid">
                <img src="riding_boots.webp" alt="">
                <p style="font-size: 20px; padding-top: 10px;">
                    Riding Boots
                </p>
            </div>
            <div class="rid">
                <img src="riding_jacket_1.webp" alt="">
                <p style="font-size: 20px; padding-top: 10px;">
                    Riding Jacket
                </p>
            </div>
            <div class="rid">
                <img src="shoes_6.webp" alt="">
                <p style="font-size: 20px; padding-top: 10px;">
                   shoes
                </p>
            </div>
            <div class="rid">
                <img src="T_shirt.webp" alt="">
                <p style="font-size: 20px; padding-top: 10px;">
                    T-shirt
                </p>
            </div>
        </div>
     </section>
     <section id="HIMALAYAN">
        <div class="new">
            <p class="text" style="font-size: 25px; padding-bottom: -10px;"><strong>Explore our collection</strong></p>
            <p><strong class="text">NEW HIMALAYAN SCALE MODEL</strong></p>
        </div>
     </section>

     <section>
        <div class="zoom">
            <div class="zoom1">
                <img src="adventureride.webp" alt="" width="200px">
                <h4>adventureride</h4>
            </div>
            <div class="zoom2">
                <img src="stouring.webp" alt="" width="200px">
                <h4>Stouring</h4>
            </div>
            <div class="zoom3">
                <img src="Cityride.webp" alt="" width="200px">
                <h4>City Ride</h4>
            </div>
            <div class="zoom4">
                <img src="lifestyle.jpg" alt="" width="400px">
                <h4>Lifestyle</h4>
            </div>
     </section>
     <section>
        <div>
            <img  class="imade-fluied" src="usecode.webp" alt="" width="100%">
        </div>
     </section>
     <section id="now" >
        <div class="tnow">
            <h4>Trending Now</h4>
            <a href="">view all</a>
        </div>
        <div class="tr">
            <div class="trd">
                <img src="tr1.webp" alt="">
                <p><strong>1901 WELCOME KIT - BLACK</strong></p>
                <p><b>₹1,290.00</b></p>
                <p>⚫</p>
                <button class="btn">Add to Cart</button>
            </div>
            <div class="trd">
                <img src="tr2.webp" alt="">
                <p><strong>CLASSIC SLING BAG - DARK GREEN</strong></p>
                <p><b>₹1,250.00</b></p>
                <p>🟢⚫</p>
                <button class="btn">Add to Cart</button>
            </div>
            <div class="trd">
                <img src="tr3.webp" alt="">
                <p><strong>CITY VIBE MID ANKLE BOOTS - OLIVE</strong></p>
                <p><b>₹5,990.00</b></p>
                <p>⚫ 🟢</p>
                <button class="btn">Add to Cart</button>
            </div>
            <div class="trd">
                <img src="tr4.webp" alt="">
                <p><strong>1:12 NEW HIMALAYAN 450 SCALE MODEL - BLACK</strong></p>
                <p><b>₹1,610.00</b></p>
                <p>⚫⚪🟡</p>
                <button class="btn">Add to Cart</button>
            </div>
            <div class="trd">
                <img src="tr5.webp" alt="">
                <p><strong>ROYAL ENFIELD URBAN HUSTLER V2 GLOVES - NEON</strong></p>
                <p><b>₹1,550.00</b></p>
                <p>⚫</p>
                <button class="btn">Add to Cart</button>
            </div>
        </div>
     </section>
     <section>
        <div class="knowmore">
            <p><strong>Discover the Ultimate <br> Guide to Cargo Lowers <br> for Men:  Style, Comfort,<br> and Versatility</strong></p>
            <button>Know More</button>
        </div>
     </section>
     <section id="new" >
        <div class="tnow">
            <h4>New Arrivals</h4>
            <a href="">view all</a>
        </div>
        <div class="tr">
            <div class="trd">
                <img src="nr1.webp" alt="">
                <p><strong>TRU DRY WATERPROOF ROLL TOP DUFFLE BAG - GREEN</strong></p>
                <p><b>₹4,290.00</b></p>
                <p>⚫</p>
                <button>Add to Cart</button>
            </div>
            <div class="trd">
                <img src="ne2.webp" alt="">
                <p><strong>ICONIC DRUM BOTTLE - GREEN</strong></p>
                <p><b>₹999.00</b></p>
                <p>🟢⚫</p>
                <button>Add to Cart</button>
            </div>
            <div class="trd">
                <img src="ne3.webp" alt="">
                <p><strong>TRU DRY WATERPROOF ROLL TOP BACKPACK - BLACK</strong></p>
                <p><b>₹3,950.00</b></p>
                <p>⚫ 🟢</p>
                <button>Add to Cart</button>
            </div>
            <div class="trd">
                <img src="ne4.webp" alt="">
                <p><strong>MOTO FLASK BOTTLE - BLACK</strong></p>
                <p><b>₹450.00</b></p>
                <p>⚫⚪🟡</p>
                <button>Add to Cart</button>
            </div>
            <div class="trd">
                <img src="ne5.webp" alt="">
                <p><strong>TRU DRY WATERPROOF ROLL TOP BACKPACK - GREEN</strong></p>
                <p><b>₹3,950.00</b></p>
                <p>⚫</p>
                <button>Add to Cart</button>
            </div>
        </div>
     </section>
     <section>
        <div>
            <img src="sc1.webp" alt="" width="100%">
        </div>
     </section>
     <footer class="footer">
    <div class="footer-container">

        <div class="footer-col">
            <h3>Royal Enfield</h3>
            <ul>
                <li><a href="#">About us</a></li>
                <li><a href="#">Motorcycle</a></li>
                <li><a href="#">Media & events</a></li>
                <li><a href="#">Career</a></li>
                <li><a href="#">Forum</a></li>
                <li><a href="#">Contact Us</a></li>
                <li><a href="#">Warranty Claim</a></li>
            </ul>
        </div>

        
        <div class="footer-col">
            <h3>Bulk Order</h3>
            <a class="footer-btn" href="#">Place a Bulk Order</a>

            <h3>Store Locator</h3>
            <a class="footer-btn" href="#">Find a store</a>

            <h3>Track Your Order</h3>
            <a class="footer-btn" href="#">Track Status</a>
        </div>

    
        <div class="footer-col">
            <h3>Keep In Touch</h3>
            <p>Sign up for our newsletter and be the first to know<br>
               about coupons and special promotions.</p>

            <div class="newsletter-box">
                <input type="email" placeholder="ENTER YOUR EMAIL ADDRESS">
                <button>→</button>
            </div>

            <label class="checkbox">
                <input type="checkbox">
                I accept the Terms and Conditions &
                Privacy Policy
            </label>

            <h3>Raise Return or Exchange</h3>
            <a class="footer-btn" href="#">Raise a Request</a>
        </div>


        <div class="footer-col">
            <h3>Our Policies</h3>
            <ul>
                <li><a href="#">Shipping & Payment</a></li>
                <li><a href="#">General & Returns and Exchange Policy</a></li>
                <li><a href="#">Terms & Conditions</a></li>
                <li><a href="#">Privacy & Policy</a></li>
            </ul>
        </div>

    </div>

        <p>© 2025 Royal Enfield. All rights reserved. | MRP wherever mentioned is inclusive of all taxes.</p>
    </div>
</footer>

</body>

</html>
