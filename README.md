# bankist.me
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Design Agency</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="./media-queries.css">
    <script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"></script>
<script nomodule src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js"></script>
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
</head>
<body>
    <header>
<div class="container">
    <nav>
            <!-- Logo -->
            <!-- <img src="" alt="LOGO" class="logo">  -->
            <h1>Shades</h1>

        <!-- Hamburger -->
        <div class="hamburger">
            <ion-icon name="menu-outline" class="menu"></ion-icon>
        </div>
        <!-- Navigation -->

        <ul class="nav-ul">
            <ion-icon name="close-outline" class="close"></ion-icon>
<li><a href="#" class="nav-link">Home</a></li>
<li><a href="#" class="nav-link">Services</a></li>
<li><a href="#" class="nav-link">About</a></li>
<li><a href="#" class="nav-link">Contact</a></li>
<li><a href="#" class="nav-link">Blogs</a></li>

        </ul>
        
        <ion-icon <slot name="search-outline" class="search"><!-- optional fallback --></slot>></ion-icon>
            
            
            
            
              
    </nav>
</div>



    </header>

<main>
<!-- Intro Section -->
<section id="intro">
<div class="container">
    <div class="text-intro line">
        <h1>We're a digital agency.</h1>
        <a href="#" class="btn btn-dark">Getting Started</a>
    </div>
    <!-- Intro cards1 -->
<div class="card-intro">
    <div class="cards" data-aos="fade-right">
        <ion-icon name="bar-chart-outline"></ion-icon>
        <h3 class=" line heading-3">Future Vision</h3>
        <p>it is a long established fact that a reader will be distracted by the readable content of the page.</p>
    </div>

    <!-- CARD 2 -->
    <div class="cards">
        <ion-icon name="rocket-outline"></ion-icon>
        <h3 class=" line heading-3">Product Design</h3>
        <p>There are many variation of passages of available , but the majority alternation in some form</p>
    </div>
    <!-- CARD 3 -->

    <div class="cards" data-aos="fade-left">
        <ion-icon name="pie-chart-outline"></ion-icon>
        <h3 class="line heading-3">Great Solution</h3>
        <p>The generated lorem ipsum is therefore always free from repitition, injected humor.</p>
    </div>
</div>

</div>

</section>
<!-- SERVICES SECTION -->
<section id="services">
    <div class="container">
        <div class="heading line">
            <h2>Services</h2>
            <p>WE WORK WITH YOU, NOT FOR YOU</p>
        </div>
        <!-- SERVICES -->
<div class="services" data-aos="fade-up">
    <div class="service">
        <ion-icon name="bookmark-outline"></ion-icon>
        <h3>Digital Strategy</h3>
        <ion-icon name="arrow-forward-outline"></ion-icon>

    </div>
    <div class="service">
        <ion-icon name="document-text-outline"></ion-icon>
        <h3>UX Design</h3>
        <ion-icon name="arrow-forward-outline"></ion-icon>

    </div>
    <div class="service">
        <ion-icon name="create-outline"></ion-icon>
        <h3>Product Design</h3>
        <ion-icon name="arrow-forward-outline"></ion-icon>

    </div>
    <div class="service">
        <ion-icon name="bookmark-outline"></ion-icon>
        <h3>Content Strategy</h3>
        <ion-icon name="arrow-forward-outline"></ion-icon>

    </div>
    <div class="service">
        <ion-icon name="document-text-outline"></ion-icon>
        <h3>Brand Identity</h3>
        <ion-icon name="arrow-forward-outline"></ion-icon>

    </div>
    <div class="service">
        <ion-icon name="create-outline"></ion-icon>
        <h3>Media Planing</h3>
        <ion-icon name="arrow-forward-outline"></ion-icon>

    </div>
</div>

    </div>
</section>




    </div>
</section>
<!-- VERTICAL LINE -->
<div class="h-line"></div>

<!-- ABOUT SECTION -->
<section id="about" >
<div class="container">
    <div class="heading line">
        <h2>About</h2>
        <p>WE'RE MORE THAN A DIGITAL AGENCY</p>
    </div>

    <!-- ABOUT IMAGES -->
    <div class="about" data-aos="fade-up">
        <div class="image image1">
            <img src="./IMAGES/img.jpeg" alt="">
            <div class="image-text">
                <h3 class="heading-3">Teamwork</h3>
                <p>Commited and creative</p>
            </div>
        </div>
<!-- Image-2 -->
<div class="image image2">
    <img src="./IMAGES/img1.jpeg" alt="">
    <div class="image-text">
        <h3 class="heading-3">Philosphy</h3>
        <p>Trust pays off</p>
    </div>
</div>
<!-- image-3 -->
<div class="image image3">
    <img src="./IMAGES/img3.jpeg" alt="">
    <div class="image-text">
        <h3 class="heading-3">Office</h3>
        <p>Ikeja, Lagos</p>
    </div>
</div> 


</div>
<!-- About-text -->
<div class="about-text">
    <div class="text1">
        <h3 class="heading-3">What we are</h3>
        <p>
             Bring to the table win-win survival strategies to ensure proactive domination. At the end of the day, going forward will have multiple touchpoints for offshoring. 
        </p>
    </div>
    <!-- About- text-2 -->
    <div class="text2">
        <h3 class="heading-3">Our Philosphy</h3>
        <p>
             A new normal that has evolved from generation X is on the runway heading towards a streamlined cloud solution. User generated content in real-time.
        </p>
    </div>
    <!-- About-text-3 -->
    <div class="text3">
        <h3 class="heading-3">How We work</h3>
        <p>
             Capitalize on low hanging fruit to identify a ballpark value added activity to beta test. Override the digital divide with additional clickthrough fromDevOps
        </p>
    </div>
</div>
</div>



</section>
<!-- VERTICAL LINE -->
<div class="h-line"></div>

<!-- BLOGS SECTION -->
<section id="blog">
    <div class="container">
        <div class="heading">
            <h2>Latest News</h2>
            <p>CHECK OUT SOME OF OUR THINKING</p>
        </div>

        <!-- Blog article -->
        <div class="blog" data-aos="fade-up">
<div class="blog-items image">
    <img src="./IMAGES/hhh1.jpeg" alt="">

<div class="blog-text">
    <p>Design/UX</p>
    <h3 class="heading-3">How to drive your customer experience</h3>
    <ion-icon name="arrow-forward-outline"></ion-icon>

</div>
        </div>
<!-- Blog 2 -->
<div class="blog-items image">
    <img src="./IMAGES/hhh2.5.jpeg" alt="">

<div class="blog-text">
    <p>Design/UX</p>
    <h3 class="heading-3">How to drive your customer experience</h3>
    <ion-icon name="arrow-forward-outline"></ion-icon>

</div>
        </div>
<!-- Blog 3 -->
<div class="blog-items image">
    <img src="./IMAGES/hhh3.jpeg" alt="">

<div class="blog-text">
    <p>Design/UX</p>
    <h3 class="heading-3">How to drive your customer experience</h3>
    <ion-icon name="arrow-forward-outline"></ion-icon>

</div>
        </div>


    </div>
    </div>
</section>


<!-- Contact section -->

<section id="contact">
    <div class="container">
        <div class="contact">

<!-- ICONS -->

<div class="contact-icon">

    <ion-icon name="logo-facebook"></ion-icon>
<ion-icon name="logo-instagram"></ion-icon>
<ion-icon name="logo-github"></ion-icon>
<ion-icon name="logo-twitter"></ion-icon>

</div>
<!-- Text -->
<h2>Let's Talk</h2>

<!-- Button -->
<a href="" class="btn">Make an enquiry</a>

        </div>
    </div>
</section>


</main>

<!-- Footer -->
<footer>
    <div class="container">
        <p>2023 &copy; HadeedTrust. All right reserved.</p>
    </div>
</footer>

<div class="modal">
 <span class="close-modal">&times;</span>
<div class="modal-content">
    <form action="">
        <input type="text" placeholder="search">
<ion-icon  name="search-outline" class="search"><!-- optional fallback --></ion-icon>
    </form>
</div>

</div>




<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="./script.js"></script>
</body>
</html>
