---
layout: logoTop
title: Changer de pays
---

<div class="Motto">changer de pays</div>
<p class="intro-text">En collaboration avec l’association le Pont de Macon et son antenne accueillant des réfugiés, Rêver Tout Haut a imaginé un cycle de 7 séances destiné à deux familles Yezidi résidant dans le Clunisois.
</p>
<p class="intro-text">L’idée étant de pouvoir participer par la création à un accompagnement global de ces familles exilées.
</p>
<p class="intro-text">Comment s’inscrire dans le présent&nbsp;? Dans une nouvelle culture&nbsp;? De nouveaux liens sans trahir ou avoir le sentiment d’abandonner les siens&nbsp;? Comment exprimer des émotions dans une langue que l’on ne maîtrise pas&nbsp;? Comment tout réapprendre&nbsp;? Comment vivre avec le trauma&nbsp;?  Comment changer de pays, de mots, et de manière d’envisager sa vie et sa famille&nbsp;?
</p>
<p class="intro-text">Ce cycle s’est tenu de février à juillet 2020 et a proposé aux familles, en présence de professionnelles du Pont des ateliers argile, textiles, chansons, traductions et photographies.
</p>

<!-- Slideshow container -->
<div class="slideshow-container" style="position: relative;">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides">
    <div class="numbertext">1 / 5</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/q_auto,f_auto,w_800/v1601401045/gatsby-cloudinary/at-photo-frame-with-hands.jpg" style="width:100%;">
      <figcaption class="figCap">© Lucie Moraillon</figcaption>
    </figure>
  </div>
  <div class="mySlides">
    <div class="numbertext">2 / 5</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/q_auto,f_auto,w_800/v1601401042/gatsby-cloudinary/at-collage-yazidi.jpg" style="width: 100%">
      <figcaption class="figCap">© Lucie Moraillon</figcaption>
    </figure>
  </div>
  <div class="mySlides">
    <div class="numbertext">3 / 5</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/q_auto,f_auto,w_820/v1601451152/gatsby-cloudinary/yezidi-collage-gold-pen.jpg" style="width:100%">
      <figcaption class="figCap">© Lucie Moraillon</figcaption>
    </figure>
  </div>
  <div class="mySlides">
    <div class="numbertext">4 / 5</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/q_auto,f_auto,w_623/v1601451585/gatsby-cloudinary/les_mains_de_maman_yezidi.png" style="width:110%">
    </figure>
  </div>
  <div class="mySlides">
    <div class="numbertext">5 / 5</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/q_auto,f_auto,w_447/v1601452460/gatsby-cloudinary/argile-yezidi-four-hands.jpg" style="width:65%">
    </figure>
  </div>

  <!-- Next and previous buttons -->
  <div style="display: flex; flex-wrap:nowrap; justify-content:space-around;">
    <div>
      <a class="prev" onclick="plusSlides(-1)" style="cursor:pointer; color: hsl(30.4,31.2%,48.4%); font-size:2rem">&#10094;</a>
    </div>
    <div>
      <a class="next" onclick="plusSlides(1)" style="cursor:pointer; color: hsl(30.4,31.2%,48.4%); font-size:2rem;">&#10095;</a>
    </div>
  </div>

</div>
<br>

<!-- The dots/circles -->

<script>
  var slideIndex = 1;
  showSlides(slideIndex);

  // Next/previous controls
  function plusSlides(n) {
    showSlides(slideIndex += n);
  }

  // Thumbnail image controls
  function currentSlide(n) {
    showSlides(slideIndex = n);
  }

  function showSlides(n) {
    var i;
    var slides = document.getElementsByClassName("mySlides");
    var dots = document.getElementsByClassName("dot");
    if (n > slides.length) {
      slideIndex = 1
    }
    if (n < 1) {
      slideIndex = slides.length
    }
    for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
    }
    for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i]
        .className
        .replace("active", "");
    }
    slides[slideIndex - 1].style.display = "block";
    dots[slideIndex - 1].className += "active";
  }
</script>
