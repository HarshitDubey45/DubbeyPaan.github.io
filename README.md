# DubbeyPaan.github.io
DubeyPaanVesu/imagesss/1-removebg-preview (1).png
DubeyPaanVesu/imagesss/1-removebg-preview (1).png
DubeyPaanVesu/imagesss/DubeyPaanImage.png
DubeyPaanVesu/imagesss/Super chocolate pan.jpeg
DubeyPaanVesu/imagesss/download (1).jpeg
DubeyPaanVesu/imagesss/MAGHAI MEETHA PAN.jpeg
DubeyPaanVesu/imagesss/images.jpeg
DubeyPaanVesu/imagesss/Shahi  pan.jpeg
DubeyPaanVesu/imagesss/Gundi pan3.jpeg
DubeyPaanVesu/imagesss/333994347_732875088496620_8971074184401928432_n.jpg
DubeyPaanVesu/imagesss/1-removebg-preview (1).png
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css?family=Poppins:100,100italic,200,200italic,300,300italic,regular,italic,500,500italic,600,600italic,700,700italic,800,800italic,900,900italic" rel="stylesheet" />
    <title>Dubey Paan</title>
    <script src="script.js" defer></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
<!--     <link rel="stylesheet" href="style.css"> -->
  <style>
  *{
    box-sizing: border-box;
}
html{
    scroll-behavior: smooth;
}
body{
       background-color:#F6F0EB;
       font-family: 'poppins',sans-serif;
       margin: 0%;
       /* max-width: 1440px; */
       /* overflow-x: hidden; */
       /*overflow hidden ka  matlab nav bar ke ander animation lagege to jo nav bar rightside me ja raha hai wo hide ho */

}   
.main-contant{
    overflow-x: hidden;
    height: 100vh;
    scroll-behavior: smooth;
}

header{
    /* display: flex;
    align-items: center;
    justify-content: space-between;
    padding:24px 32px; */
    background-color: #FFFFFF;
    /* padding:24px 32px; */
    padding: 24px;
    
    /* display: flex; */
}
 .header-content{
    max-width: 1290px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    /* padding:24px 32px;
    margin: 0 auto; isse hearder center me aa jayega */
    margin: 0 auto;
    /* display: flex; */
    height: 70px;

 }
.logo{
    width: 200px;
}
.logo img{
    width: 100%;
}
a{
    text-decoration: none;
    color: inherit;
    /* color: #492118; */
    
}
nav{
    display: flex;

}
 /* or */
 nav a + a{
    margin-left: 60px;
 
 }
nav a{
    font-weight: 700;
    font-size: 16px;
    color: #492118; 
}
/*  images ke ander ja rahe hai */
/* .hero-section{
 
} */
 main{
    padding: 0 32px;
 }
 .hero-section{
    margin-top: 40px;
 }
img{
    width:100%
}
.img-container{
   max-width: 1200px;
   
   margin: 0 auto;
}

.hero-section p{
    color: #492118;
    text-align: center;
    font-size: 24px;
}
.section h2{
    color:#492118 ;
    text-align: center;
    font-size: 24px;
}
.section .img-containerfirst{
    max-width: 1040.87px;
    
}
/* .section{
    margin-top: 100px;
} */

/* .section .img-container */
.img-containerfirst{
    margin: 0 auto;
}

.section h2{
    color:#492118 ;
    text-align: center;
    font-size: 24px;
}
.section .img-containerfirst{
    max-width: 960px;
}
.section{
    margin-top: 100px;
}

/* .section .img-container */
.img-containerfirst{
    margin: 0 auto;
}
.go-to-top{
    text-align:right ;
    max-width:960px;
    margin: 0 auto;
    font-size: 32px;
    margin-top: 88px;
}

.go-to-top a{
    text-decoration: underline;
}
/* footer p{
    text-align: center;
    color: #492118;
} */
 .footer-text{
    text-align: center;
    color: #492118;
    margin-top: 40px;
 }
 .close-icons{
    position: absolute;
    top: 8px;
    right:14px;
    cursor: pointer;
    display: none;

 }

 .hamburger-menu{
    background-color: #FFFFFF;
    padding: 3px;
    height:200px ;
    width: 200px;
    position: absolute;
    border-radius: 50%;
    /* left: 0; */
    top: -131px;
    right: -128px;
    /* top: -64px;
    right: -58px; */
    cursor: pointer;
    /* display: flex;
    justify-content: center;
    /* align-items: center; */
    /* align-items: flex-end; */ 
    /* border-radius: ; */
     
 }

 .hamburger-icon{
    font-size: 32px;
    position: absolute;
    bottom: 22px;
    left: 36px;
    /* font-size: 16px;
    position: absolute;
    bottom: 10px;
    left: 20px; */
 }
 .hamburger-menu-container{
    overflow: hidden;
    position: relative;/* position relative , partent ke upper lagta hai
     tab child me position: absolute laga hi ais liye */
     /* height:48px ;
     width: 48px; */
     height: 65px;
    width: 67px;
     display: none;
 }
 /* ---------------------------------------------------------------------------------------------
 -----------------------------------------------------------------------------------------------------------
 -------------------------------------------------------------------------------------------------------- */
 /* code of sliding image  */
 /* styles.css*/
.slideFirst {
    margin: 0;
    font-family: Arial, sans-serif;
}

.carousel {
    position: relative;
    /* max-width: 200px; Adjust as needed */
    max-width: 900px;
    margin: auto;
    overflow: hidden;
}

.carousel-images {
    display: flex;
    transition: transform 0.5s ease;
}

.carousel-images img {
    width: 100%; /* Adjust to your desired size */
    flex-shrink: 0;
}

button {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    background-color: rgba(255, 255, 255, 0.7);
    border: none;
    cursor: pointer;
    font-size: 18px;
    padding: 10px;
}

.prev {
    left: 10px;
}

.next {
    right: 10px;
}
 


 

/* ------------------------------------------- */
@media(max-width:1200px){
    nav a{
        font-weight: 700;
        font-size: 16px;
         /* color: #492118;  */
    }
    nav a + a{
        margin-left: 40px;
}
header{
    padding: 16px 24px;
}
}

@media(max-width:960px){
    nav a{
        font-weight: 700;
        font-size: 12px;
         /* color: #492118;  */
    }
    nav a + a{
        margin-left: 22px;
}
.hero-section{
    margin-top: 48px;
    border-style: groove;
}
.section{
    margin-top: 42px;
}
}
@media(max-width:768px){
   header{
    background-color: transparent;
    /* background-color: ; */
    position: sticky;
    top: 0;
    /* backdrop-filter: blur(8px) ; */
    /* overflow: hidden; */
   }
   .header-content{
    min-height: 100px;
    /* overflow: hidden; */
   }

   nav{
    position: absolute;
    background-color: #ffffffa0;
    flex-direction: column;
    backdrop-filter: blur(4px) ;
    padding: 24px;
    right: -200px;/*right side me ander chala jayega animation hai */
    top: 16px;
    /* display: none; jab animate karte hai to display none nahi karte hai phale se */
    /* idhar sab kuch hone ke badd display none karwaya hai */
    transition: right 0.25s ease-in-out;
   }
   /* .menu-open nav{
    display: flex;
   } */

   nav a+a{
    margin: 0;
    margin-top: 16px;
    
   }
   .close-icons,
   .hamburger-menu-container{
    
    display: block;

 }
 /* .hamburger-menu-container{
    display: block;
 } */
 .menu-open nav{
    /* display: flex; - jab ham
    animation dete hai to dislpay:flex, and display:block,& none property kuch nahi lagti*/
    right: 24px;
   }

.menu-open .hamburger-menu-container{
    display: none;

}
.go-to-top{
    font-size: 12px ;
    margin-top: 32px;
}
/* --------------------------------------------------------------------- */
/* ----------------------------------------------------------------------- */
   
}
.contact-info{
    
        background-color: #333;
        color: white;
        padding: 20px;
        text-align: center;
        margin-top: 20px;
}
.contact-info a{
    padding: 10px;
    
}
.contact-left{
    position: relative;
    /* left: 10px;
    bottom: 10px; */
    left: -159px;
    bottom: -76px;
}
.social-links{
    position: relative;
    /* left: 10px;
    bottom: 10px; */
    /* left: 137px;
    bottom: -11px; */
    left: -14px;
    bottom: -10px;
}

/* .allinfo p{
    font-size: 0.875em;
    position: relative;
    left: 5px; */
/* } */
.allinfo .paragraph1{
    display: flex;
    /* ----- */
    /* flex-direction: column;
    align-items: flex-start; */

    /* -------- */
    justify-content: space-around;
    flex-wrap: wrap;

}

.paragraph1 p {
    flex: 1;
    /* -----------
    text-align: center;
    display: flex; */
    /* ----------- */ 
    margin: 10 px;
    /* margin: 10 0 px; */
    /* ---------------- */
    line-height: 1.6;
    color: #eee6e6;
    
    min-width: 200px; /* Ensures paragraphs don't get too small */
    /* text-align:justify; */
}
.owner-image {
    width: 70px; /* Set image width */
    height: 70px; /* Set image height */
    /* border-radius: 50%; Make images circular */
    border-style: outset;
    margin-right: 10px; /* Space between image and text */
    /* margin: 0 auto; */
}
/* --------------------- */
ul {
    list-style-type: disc;
    /* margin: 10px 0;
    padding-left: 20px;
     Indent the list */
     margin: -7px 0;
    padding-left: 29px;
    min-width: 200px;
}

li {
    margin: 5px 0; /* Space between list items */
    text-align: left;
    margin: 10 px;
    min-width: 200px;
}
/* sliding show in front of website */








/* styles.css*/
/* .slideFirst {
    margin: 0;
    font-family: Arial, sans-serif;
}

.carousel {
    position: relative;
    /* max-width: 200px; Adjust as needed 
    max-width: 900px;
    margin: auto;
    overflow: hidden;
}

.carousel-images {
    display: flex;
    transition: transform 0.5s ease;
}

.carousel-images img {
    width: 100%; /* Adjust to your desired size 
    flex-shrink: 0;
}

button {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    background-color: rgba(255, 255, 255, 0.7);
    border: none;
    cursor: pointer;
    font-size: 18px;
    padding: 10px;
}

.prev {
    left: 10px;
}

.next {
    right: 10px;
}
  */

    
  </style>
</head>
<body>
   <div class="main-contant">
      <!-- agar ham parent ke upper -> overflow hidden laga dete hai to  
        chlid ha 
        position:sticky
        ya 
        position:absolute kaam nnhai karta
        . is liya hamko 
        height:100vh lagana padega -->


   <header>
      <!-- <img src="" alt=""> -->
   <!-- <div class="header-content menu-open" > -->
      <div class="header-content " >
   <!-- </header> -->
    <div class="logo" id="logo">
        <img src="/DubeyPaanVesu/imagesss/1-removebg-preview (1).png" alt="LOGO">
    </div>
    
     <!--  RAKHNE Ko to ham div me bhi rakh sakte hai navigational bar
        par ham sematic tag ka use kar ke responsive website banaye ge -->
        <!-- is liye we use nav bar -->
        <div class="hamburger-menu-container">
         <div class="hamburger-menu">
            <span class="hamburger-icon">
               &#9776; <!-- three dought wala image ka code hai-->
             </span>
         </div>
         </div>
         <nav>
            <span class="close-icons"> <strong >&times;close icon</strong></span><!--&times;cross ka icon hai-->
            <!-- <img src="" alt="">jab phone device me convert ho ga tab x cross wala icon tick hoga -->
            <!-- <nav class="nav"></nav> -->
            <!-- using ul & li -->
             <!-- par a ancher tag ka hi use kar sakte hai -->
            <a href="#Top-Picks">MAGHAI MEETHA PAN</a>
            <a href="#Whopper">Chocolate pan</a>
            <a href="#Stunner-Menu">Super chocolate pan</a>
            <a href="#New-Foodie-Collection">Shahi  pan</a>
            <a href="#Deal-of-the-Day">Gundi pan</a>
            <a href="#About Us">About Us</a>
         </nav>
         <!-- <div class="hamburger-menu-container">
         <div class="hamburger-menu">
            <span class="hamburger-icon">
                &#9776; three dought wala image ka code hai
             </span>
         </div>
         </div> --> 
         </div>
   </header> 
   <main>
      
      <section class="hero-section">
         <!-- <div class="img-container">
            <img src="/DubeyPaanVesu/imagesss/DubeyPaanImage.png" alt="hero-image">
         </div> -->
         <!-- add sliding imagess -->
          <div class="slideFirst">
         <div class="carousel">
            <div class="carousel-images">
                <img src="DubeyPaanVesu/imagesss/DubeyPaanImage.png" alt="Image 1">
                <img src="DubeyPaanVesu/imagesss/Super chocolate pan.jpeg" alt="Image 2">
                <img src="DubeyPaanVesu/imagesss/download (1).jpeg" alt="Image 3">
            </div>
            <button class="prev" onclick="moveSlide(-1)">&#10094;</button>
            <button class="next" onclick="moveSlide(1)">&#10095;</button>
        </div>
        </div>
        <!-- <p>Well, You can,t resist anymore!</p>  -->
         <p>""Wellcome to <STROng> Dubey Paan</STROng>""</p>
      </section>
      
      <section id="Top-Picks" class="section">
         <h2>MAGHAI MEETHA PAN   ₹ = 55         </h2>
         <div class="img-containerfirst">
            <img src="DubeyPaanVesu/imagesss/MAGHAI MEETHA PAN.jpeg" alt="hero-image">
         </div>
         
      </section>
      <section id="Whopper" class="section">
         <h2>Chocolate pan ₹ = 50</h2>
         <div class= "img-containerfirst">
            <img src="DubeyPaanVesu/imagesss/download (1).jpeg" alt="hero-image">
         </div>
         
      </section>
      <section id="Stunner-Menu" class="section">
         <h2>Super chocolate pan ₹ = 50 </h2>
         <div class="img-containerfirst">
            <img src="DubeyPaanVesu/imagesss/images.jpeg" alt="hero-image">
         </div>
         
      </section>
      <section id="New-Foodie-Collection" class="section">
         <h2>Shahi  pan ₹ = 40 </h2>
         <div class="img-containerfirst">
            <img src="DubeyPaanVesu/imagesss/Shahi  pan.jpeg" alt="hero-image">
         </div>
         
      </section>
      <section id="Deal-of-the-Day " class="section">
         <h2>Gundi pan ₹ = 35    </h2>
         <div class="img-containerfirst">
            <img src="DubeyPaanVesu/imagesss/Gundi pan3.jpeg" alt="hero-image">
         </div>
         
      </section>
      <footer id="About Us">
      <h3 class="go-to-top"><a href="#logo">Go to top</a></h3>
      <!-- ----------------------------------------------------------------- -->
      <!-- added extra about us feature in dubey Paan website -->
       <!-- ---------------------------------------------------------------- -->
      <div class="contact-info">
          <div class="allinfo">
            <h2>
               About Us
            </h2>
            
            <div class="paragraph1">
               <!-- <ul>
                  <li>Passion for Paan: Our young entrepreneur is passionate about crafting unique flavors that reflect both tradition and innovation.</li>
                  <li>Fresh Ingredients: We source only the freshest ingredients to ensure each bite is a burst of flavor.</li>
                  <li>Community Focused: We believe in supporting our local community and contributing to its vibrancy through our small business.</li>
                  <li>Customer-Centric: Your satisfaction is our priority! We welcome feedback and are always looking to improve.</li>
                  <li>Thank You for Your Support: Every purchase helps fuel young entrepreneurship and inspires creativity.</li>
               </ul> -->
               <p>Welcome to <strong>Dubey Paan</strong>, a paan shop run by a creative 13-year-old! We offer a variety of delicious paan flavors made with love and fresh ingredients. Thank you for supporting young entrepreneurship!<br></br>
                  <!-- <ul>
                     <li>Passion for Paan: Our young entrepreneur is passionate about crafting unique flavors that reflect both tradition and innovation.</li>
                     <li>Fresh Ingredients: We source only the freshest ingredients to ensure each bite is a burst of flavor.</li>
                     <li>Community Focused: We believe in supporting our local community and contributing to its vibrancy through our small business.</li>
                     <li>Customer-Centric: Your satisfaction is our priority! We welcome feedback and are always looking to improve.</li>
                     <li>Thank You for Your Support: Every purchase helps fuel young entrepreneurship and inspires creativity.</li>
                  </ul> -->
                  
                  <img src="DubeyPaanVesu/imagesss/333994347_732875088496620_8971074184401928432_n.jpg" class="owner-image">
                  <img src="DubeyPaanVesu/imagesss/1-removebg-preview (1).png" alt="Owner's Picture" class="owner-image">
                  <img src="DubeyPaanVesu/imagesss/271928188_385773370067252_7774573447020605327_n.jpg" alt="Owner's Picture" class="owner-image">
               </p>
               <section>
               <ul style="color: darkolivegreen;">
                  <h3 style="color: rgb(241, 243, 237) ;">Delicious paan flavors</h3>
                   <!-- <li>Classic Mint Pan</li>
                   <li>Sweet Coconut Pan</li>
                   <li>Spicy Masala Pan</li>
                   <li>Fruity Surprise Pan</li> -->
                   <li>Chocolate bomb ₹ 35 </li>
                  <li>Super sada ₹ 40</li>
                  <li>Chocolate pan ₹ 50
                  </li>
                  <li>MAGHAI MEETHA PAN ₹ 55
                  </li>
                  <li>MAGHAI chocolate pan ₹ 60
                  </li>
                  <li>Kalkatta Sada pan ₹ 35
                  </li>
                  <li>Meetha pan ₹ 45
                  </li>
                  <li>Shahi  pan ₹ 45
                  </li>
                  <li>Gundi pan ₹ 35

                  </li>
                  <li>Banarasi meetha pan ₹ 35
                  </li>
                  <li>Banarasi sada pan ₹ 30
                  </li>
                  <li>Tulsi 00 pan ₹ 30</li>
                  <li>Navratna chatni sada pan ₹ 40
                  </li>
                  <li>Navratna quiwam 90 no pan ₹ 65 </li>
                  <li>Super chocolate pan ₹ 55
                  </li>
                  <li>Baba 120 pan ₹ 30
                  </li>
                  <li>Chocolaty 120 pan ₹ 35
                  </li>
                  <li>Super sada ₹ 40</li>
               </ul>
               </section>
               <!-- <p></p>
               <p></p> -->
                <!--
                    <h3>Delicious Paan Flavors </h3>
                  <li>Chocolate bomb ₹ 35 </li>
                  <li>Super sada ₹ 40</li>
                  <li>Chocolate pan ₹ 50
                  </li>
                  <li>MAGHAI MEETHA PAN ₹ 55
                  </li>
                  <li>MAGHAI chocolate pan ₹ 60
                  </li>
                  <li>Kalkatta Sada pan ₹ 35
                  </li>
                  <li>Meetha pan ₹ 45
                  </li>
                  <li>Shahi  pan ₹ 45
                  </li>
                  <li>Gundi pan ₹ 35

                  </li>
                  <li>Banarasi meetha pan ₹ 35
                  </li>
                  <li>Banarasi sada pan ₹ 30
                  </li>
                  <li>Tulsi 00 pan ₹ 30</li>
                  <li>Navratna chatni sada pan ₹ 40
                  </li>
                  <li>Navratna quiwam 90 no pan ₹ 65 </li>
                  <li>Super chocolate pan ₹ 55
                  </li>
                  <li>Baba 120 pan ₹ 30
                  </li>
                  <li>Chocolaty 120 pan ₹ 35
                  </li>
                  <li>Super sada ₹ 40</li>
              
                </p> 
            </p>
         </li> -->
               
               
           
            </div>
            <!-- <p>Welcome to <strong>Dubey Paan</strong>, a paan shop run by a creative 13-year-old! We offer a variety of delicious pan flavors made with love and fresh ingredients. Thank you for supporting young entrepreneurship!</p> -->
            <!-- <p class="contact-left">Contact Number: <a href="tel:+1234567890">+91 8511333600</a></p> -->
          </div>

         <!-- <p class="contact-left">Contact Number: <a href="tel:+1234567890">+91 8511333600</a></p> -->
         <div class="social-links">
            <h2>Contact Us</h2>
            <!-- <p class="contact-left">Contact Number: <a href="tel:+1234567890">+91 8511333600</a></p> -->
             <a href="tel:+8511333600">+91 8511333600
               <i class="fa fa-phone" style="font-size:30px;color:rgb(21, 130, 58)"></i>
             </a>
             <a href="https://www.facebook.com/p/Dubey-pan-Vesu-100063941534085/" target="_blank">
                 <i class="fab fa-facebook-f" style="font-size:30px;color:rgb(59, 99, 234)"></i> Facebook
             </a>
             <a href="https://www.instagram.com/dubey_paan/" target="_blank">
                 <i class="fab fa-instagram" style="font-size:30px;color:red"></i> Instagram
             </a>
         </div>
     </div>
     <!-- ---------------------------------------------------------------------- -->
      <p class="footer-text">  Made with ❤️ by Harshit dubey   ""The website is currently in the development phase.""</p>
      </footer>
      <!-- by defualt # lagane se top pe hi chala jata hai  -->
   </main>
</div>
<!-- <h2>HARSHIT DUBEY</h2> -->
<script>
    const hamburgerIcon= document.querySelector(".hamburger-menu-container")
const headerContent= document.querySelector(".header-content")
const closeIcon= document.querySelector(".close-icons")
// sab kuch karne ke baad vedio timining->1-hour-59-minit nav  wala
const nav=document.querySelector('nav')
hamburgerIcon.addEventListener('click',(e)=>{
    e.stopPropagation()// idhar jo bulbing ho rahi hai parent or child wala wo stop ho jayega
    headerContent.classList.add('menu-open')
    
})
// header ke upper bhi bullbling wala effect na jae
headerContent.addEventListener('click',(e)=>{
    e.stopPropagation()//stoppropagation jo child se parent tak bubling hoti hai wo stop o jati hai
})
// nav ke upper bhi stop bulbulnig vedio timing-> 2hour
nav.addEventListener('click',(e)=>{
    e.stopPropagation()
})
closeIcon.addEventListener('click',()=>{
    headerContent.classList.remove('menu-open')
})
// CLASS Bubbling ka use hua hai uske baad isko hidden kiya haai
// bubbling wale ek vedio hai > jisme tum kidhar bhi click karte hi
 //                             > wo pure event pe click mana jata hai
 //                             > parent se child tak jata hai element to html body tak any click event

window.addEventListener('click',()=>{
    headerContent.classList.remove('menu-open')
})
// add sliding imagess in front of website
// script.js
let currentIndex = 0;

function showSlide(index) {
    const slides = document.querySelectorAll('.carousel-images img');
    if (index >= slides.length) {
        currentIndex = 0;
    } else if (index < 0) {
        currentIndex = slides.length - 1;
    } else {
        currentIndex = index;
    }
    const offset = -currentIndex * 100; // Shift based on the image width
    document.querySelector('.carousel-images').style.transform = `translateX(${offset}%)`;
}

function moveSlide(direction) {
    showSlide(currentIndex + direction);
}

// Optional: Auto slide every 3 seconds
setInterval(() => {
    moveSlide(1);
}, 3000);

// Initial display
showSlide(currentIndex);
</script>
</body>
</html>
