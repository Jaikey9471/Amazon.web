# Amazon.web
Make a Amazon web page using the language of HTML and CSS....
------------------- HTML Code ------------------------------
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon.in</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="Amazon.css">
</head>
<body>
     <header> 
    <div class="navbar">
        <div class="nav-logo border" title="Amazon"> 
            <div class="logo"></div>
        </div>
        <div class="location border">
            <p class="add-first">Deliver.in</p>
            <div class="add-location">
                <i class="fa-solid fa-location-dot"></i>
                <p class="add-sec">India</p>
            </div>
        </div>
        <div class="search-bar border">
            <select class="selection">
                <option>All</option>
            </select>
            <input type="text" placeholder="Search Amazon" class="field">
            <div class="magnify">
                <i class="fa-solid fa-magnifying-glass"></i>
            </div>
        </div>
        <div class="sign border">
           <div class="sign-in">
            <p><span>Hello,Sign.in</span></p>
            <p>Accont & list</p>
           </div>
        </div>
        <div class="return border">
            <div class="order">
                <span>Return</span>
                <p>& Order</p>
            </div>
        </div>
        <div class="cart border">
            <i class="fa-solid fa-cart-plus"></i>
           Cart
        </div>
    </div>
    <div class="panel">
        <div class="panel-all">
        <i class="fa-solid fa-bars"></i>
        All
    </div>
    <div class="panel-ops">
        <p>Today's Deals</p>
        <p>Customer Care</p>
        <p>Registry</p>
        <p>Gift card</p>
        <p>Sells</p>
    </div>
        <div class="last-panel"><p>Shop Deals in Electronics</p></div>
</div>
  </header>
  <div class="hero-section">
    <div class="hero-mess">
        <p>This web page developed by Jaikey Yadav..<a href="##">Click here to make website</a></p>
    </div>
  </div>
  <div class="shop-sec">
   <div class="box1 box">
    <div class="box-content">
        <p1>Iphones</p>
        <div class="image-tag1 photo">  </div> 
        <p>Shop Now</p>
    </div>
   </div>
   <div class="box2 box">
    <div class="box-content">
        <p1>Refridgerator</p1>
        <div class="image-tag2 photo"></div>
        <p>Shop Now</p>
    </div>
   </div>
   <div class="box3 box">
    <div class="box-content">
        <p1>Study Smart Watch</p1>
        <div class="image-tag3 photo"></div>
        <p>Shop Now</p>
    </div>
   </div>
  </div>
  
  <div class="shop-sec2">
    <div class="box1 box">
     <div class="box-content">
         <p1>Home-Style</p1>
         <div class="image-tag4 photo">  </div> 
         <p>Shop Now</p>
     </div>
    </div>
    <div class="box2 box">
     <div class="box-content">
         <p1>Washing Machine</p1>
         <div class="image-tag5 photo"></div>
         <p>Shop Now</p>
     </div>
    </div>
    <div class="box3 box">
     <div class="box-content">
         <p1>microwave</p1>
         <div class="image-tag6 photo"></div>
         <p>Shop Now</p>
     </div>
    </div>
   </div>
   <div class="shop-sec3">
    <div class="box1 box">
     <div class="box-content">
         <p1>Decoration</p1>
         <div class="image-tag7 photo">  </div> 
         <p>Shop Now</p>
     </div>
    </div>
    <div class="box2 box">
     <div class="box-content">
         <p1>Clothes</p1>
         <div class="image-tag8 photo"></div>
         <p>Shop Now</p>
     </div>
    </div>
    <div class="box3 box">
     <div class="box-content">
         <p1>Sofa</p1>
         <div class="image-tag9 photo"></div>
         <p>Shop Now</p>
     </div>
    </div>
   </div>
   <footer>
    <div class="footer-class1">
        Back To Top
    </div>
    <div class="footer-class2">
    <ul>
        <p class="man">Get to Know Us</p>
            <a href="##">About Us</a>
            <a href="##">Carrear</a>
            <a href="##">Press realse</a>
            <a href="##">Amazon Science</a>
    </ul>
        <ul>
            <p class="man">Connect with us</p>
        <a href="##">Facebook</a>
        <a href="##">Twitter</a>
        <a href="##">Instagram</a>
        <a href="##">Whatsapp</a>
    </ul>
    <ul>
        <p class="man">Make Money With Us</p>
    <a href="##">Sell on Amazon</a>
    <a href="##">Sell on Amazon Accelletor</a>
    <a href="##">Amazon Global</a>
    <a href="##">Become on Affalated</a>
    <a href="##">Advitise Your Product</a>
    </ul>
    <ul>
        <p class="man">Let Us to help you</p>
    <a href="##">COVID 19</a>
    <a href="##">YOUR ACCONT</a>
    <a href="##">RETURN & ORDER</a>
    <a href="##">HELP</a>
    </ul>
    </div>
    <div class="last-footer">
        <div class="last-logo"></div>
    </div>
    <div class="copyright">© 1996-2024, Amazon.com, Inc. or its affiliates</div>
   </footer>
</body>
</html>

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

-----------------------------   CSS Code --------------------------------------

*{
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
}
.navbar{
    height: 70px;
    width: 100%;
    background-color: black;
    color: white;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}
.nav-logo{
    height: 60px;
    width: 150px;
}
.logo{
    background-image: url(amazon\ logo.jpeg);
   background-size: cover;
   height: 60px;
   width: 150px;
}
.border{
    border: 2px solid transparent;
}
.border:hover{
    border: 2px solid white;
}
.add-first{
    font-size: 0.95rem;
    color: wheat;
    margin-left: 15px;
}
.add-sec{
    font-size: 1.5rem;
    color: white;
    margin: 5px;
}
.add-location{
    display: flex;
    align-items: center;
}
.search-bar{
    display: flex;
    width: 500px;
    height: 30px;
    border-radius: 4px;
}
.selection{
    background-color: #fff;
    width: 50px;
    text-align: center;
    border-top-left-radius: 4px;
    border-bottom-left-radius: 4px;
}
.field{
    width: 400px;
}
.magnify{
    background-color: #e59006;
    width: 40px;
    border-top-right-radius: 4px;
    border-bottom-right-radius: 4px;
}
span{
    font-size: 15px;
}
p{
    font-size: 20px;
    font-weight: 400;
}
.search-bar:hover{
    border: 2px solid orange;
}
.cart i{
    font-size: 35px;
}
.panel{
    height: 40px;
    width: 100%;
    background-color: rgb(61, 78, 81);
    display: flex;
    color: white;
    justify-content: space-evenly;
    align-items: center;
}
.panel-ops p{
    display: inline;
    margin-left: 15px;
}
.panel-ops {
   width: 70%;
}
.hero-section{
    background-image: url(first\ pic.jpg);
    background-size: cover;
    height: 400px;
    display: flex;
    justify-content: center;
    align-items: flex-end;
}
.hero-mess{
    background-color: #fff;
    color: black;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 90%;
    margin-bottom: 20px;
}
.shop-sec{
    display: flex;
    justify-content: space-evenly;
    margin: 10px;
    background-color: rgb(221, 219, 215);
}
.box{
    height: 400px;
    width: 30%;
    background-color: white;
}
.image-tag1{
    background-image: url(iphone.jpg);
    height: 280px;
    width: 80%;
    padding: 20px 0px 15px;
    background-size: contain;
    display: flex;
    margin-left: 30px;
    margin-top: 5px;
}
p1{
    font-size: 30px;
    font-weight: 400;
    font-style: italic;
}
.image-tag2{
    background-image: url(appliance2.jpg);
    height: 290px;
    width: 80%;
    padding: 20px 0px 15px;
    background-size: cover;
    display: flex;
    margin-top: 5px;
    margin-left: 30px;
}
.image-tag3{
    background-image: url(Digitalwatch.jpg);
    height: 290px;
    width: 90%;
    padding: 20px 0px 15px;
    background-size: contain;
    display: flex;
    margin-top: 5px;
    margin-left: 30px;
}
.image-tag4{
    background-image: url(appliance1.jpg);
    height: 290px;
    width: 90%;
    padding: 20px 0px 15px;
    background-size: contain;
    background-repeat: no-repeat;
    display: flex;
    margin-top: 5px;
    margin-left: 30px;
}
.image-tag5{
    background-image: url(appliance4.jpg);
    height: 290px;
    width: 90%;
    padding: 20px 0px 15px;
    background-size: cover;
    display: flex;
    margin-top: 5px;
    margin-left: 30px;
}
.image-tag6{
    background-image: url(appliance3.jpg);
    height: 290px;
    width: 90%;
    padding: 20px 0px 15px;
    background-size: cover;
    display: flex;
    margin-top: 5px;
    margin-left: 30px;
}
.photo:hover{
    border: 3px solid orange;
}
.shop-sec2{
    display: flex;
    justify-content: space-evenly;
    margin: 10px;
    background-color: rgb(221, 219, 215);
    margin-top: 20px;
}
.box-content p{
color: rgb(73, 73, 228);
}
.shop-sec3{
    display: flex;
    justify-content: space-evenly;
    margin: 10px;
    background-color: rgb(221, 219, 215);
    margin-top: 20px;
}
.image-tag7{
    background-image: url(homestyle4.jpg);
    height: 290px;
    width: 90%;
    padding: 20px 0px 15px;
    background-size: cover;
    display: flex;
    margin-top: 5px;
    margin-left: 30px;
}
.image-tag8{
    background-image: url(homestyle3.jpg);
    height: 290px;
    width: 90%;
    padding: 20px 0px 15px;
    background-size: cover;
    display: flex;
    margin-top: 5px;
    margin-left: 30px;
}
.image-tag9{
    background-image: url(homestyle1.jpg);
    height: 290px;
    width: 90%;
    padding: 20px 0px 15px;
    background-size: contain;
    display: flex;
    margin-top: 5px;
    margin-left: 30px;
}
footer{
    margin-top: 20px;
}
.footer-class1{
    height: 50px;
    background-color: rgb(46, 46, 98);
    color: #fff;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1rem;
    border-radius: 10px;
}
.footer-class2 {
   height: 300px;
   background-color: #222f3d;
   border-radius: 10px;
   display: flex;
  justify-content: space-evenly;
   
}
 ul a{
    display: block;
    color: #dddddd;
    font-size: 0.90rem;
    margin-top: 15px;
 }
 ul{
    margin-top: 25px;
 }
 .man{
    color: white;
 }
 .last-footer{
    background-color: #222f3d;
    color: #fff;
    border: 0.5px solid white;
    height: 70px;display: flex;
    justify-content: center;
    align-items: center;
 }
 .last-logo{
    background-image: url(amazon\ logo.jpeg);
    background-size: cover;
    height: 60px;
    width: 150px;
 }
 .copyright{
    background-color: #090909;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    color: #fff;
 }

 ----------------------------------------------------------------------------------  THANKS FOR WATCHING MY CODE ------------------------------------------------------------------------------------------------
