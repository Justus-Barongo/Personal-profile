<head lang="en">
    <meta charset="UTF-8">
    <title>
        HOME
    </title>
    <link type="text/css" href="StyleSheet.css" rel="stylesheet">
    <script type="javascript" src="SiteScripts.js"></script>
</head>
<body>

<h2 style="font-size: 3.0em; color: #fffbf9; text-align: center; margin:0;">UREMBO</h2>
<h3 style="font-size: 2.0em; color: #fffbf9; text-align: center; margin:0;">FLOWER SHOP</h3>
<nav>
    <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="our_products.html">Products</a></li>
        <li><a href="about_us.html">About Us</a></li>
        <li><a href="contact_us.html">Contact Us</a> </li>
    </ul>
</nav>

<hr>

<img name="slide" src="SiteImages/lilies.jpg" height="350" width="900">

<hr>

<article>
    <header>
        <h3 class="center">Who We Are</h3>
    </header>

    <section class="center">
        Urembo Flower Shop is an online floral shop composed of a team of Highly experienced florists who offer the best flowers.
        Order Fresh flowers online with Same Day Delivery. We deliver Fresh flowers all over Nairobi. Every bouquet is hand-made by our
        expert florists. Discover this experience today! <br>
        Our goal is to provide the best online flower ordering service in Nairobi, Kenya backed up with first class customer support.
    </section>
</article>

<hr>

<h3 class="center">Send Flowers Today</h3>

<div class="images">
    <a target="_blank" href="#">
        <img src="SiteImages/display%20_1.jpg" alt="First Image" height="122" width="194">
    </a>
    <div class="description">Spring Sonata</div>
</div>
<div class="images">
    <a target="_blank" href="#">
        <img src="SiteImages/display_2.jpg" alt="Second Image" height="122" width="194">
    </a>
    <div class="description">Teleflora</div>
</div>
<div class="images">
    <a target="_blank" href="#">
        <img src="SiteImages/display_3.jpg" alt="Third Image" height="122" width="194">
    </a>
    <div class="description">Isle Of White</div>
</div>

<div class="images">
    <a target="_blank" href="#">
        <img src="SiteImages/display_4.jpg" alt="Third Image" height="122" width="194">
    </a>
    <div class="description">Victoria Romance</div>
</div>

<article>
    <header>
        <h3 class="center">We Gurantee </h3>
    </header>

    <hr>

    <h3 class="center">Same Day Delivery </h3>
    <section class="center">
        Order before 2pm(Kenyan time) on weekdays and we will deliver your flowers the same day throughout Nairobi.
    </section>

    <h3 class="center">Freshness Guranteed </h3>
    <section class="center">
        You get at least 5 days freshness guarantee on all flowers ordered and delivered by us.
    </section>

    <hr>

</article>

<footer class="center" style="display: inline;">
    <p>Designed by: Me</p>
    <p>Contact information: <a href="mailto:me@me.com">
        me@me.com</a>.</p>
</footer>





<script language="JavaScript">
    var i = 0;
    var path = new Array();

    // LIST OF IMAGES
    path[0] = "SiteImages/lilies.jpg";
    path[1] = "SiteImages/flowers_1.jpg";
    path[2] = "SiteImages/flowers_2.jpg";
    path[3] = "SiteImages/flowers_3.jpg";
    path[4] = "SiteImages/flowers_4.jpg";
    path[5] = "SiteImages/flowers_5.jpg";

    function SwapImage()
    {
        document.slide.src = path[i];
        if(i < path.length - 1) i++; else i = 0;
        setTimeout("SwapImage()",3000);
    }
    window.onload=SwapImage;
</script>

</body>
