---
layout: logoTop
title: Amours, désirs et absences
---

<h1>amours, désirs et absences</h1>

<!-- Slideshow container -->
<div class="slideshow-container" style="position: relative;">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides">
    <div class="numbertext">1 / 4</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_600/v1601755787/gatsby-cloudinary/novelline-pat-plus-one.jpg" style="width:100%">
      <figcaption class="figCap"></figcaption>
    </figure>
  </div>
  
  <div class="mySlides">
    <div class="numbertext">2 / 4</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_600/v1601754602/gatsby-cloudinary/novelline_collage2.png" style="width:100%">
      <figcaption class="figCap"></figcaption>
    </figure>
    </div>

    <div class="mySlides">
      <div class="numbertext">3 / 4</div>
      <figure>
        <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_600/v1601756154/gatsby-cloudinary/novelline_pat_dessins-sol.jpg" style="width:100%">
        <figcaption class="figCap"></figcaption>
      </figure>
    </div>

    <div class="mySlides">
    <div class="numbertext">4 / 4</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_600/v1601750320/gatsby-cloudinary/novelline_collage1.jpg" style="width:100%">
      <figcaption class="figCap"></figcaption>
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

<p class="intro-text">A la demande de la résidence la Novelline, à Cluny (71), où vivent des personnes cérébro-lésées, <span class="rever-typog">rêver tout haut</span> a conçu et anime deux cycles d’ateliers dans le cadre d’un projet global "Savoir s'aimer pour savoir aimer". Il s’agit de mettre en perspective et en création ce que la cérébro-lésion fait vivre au niveau affectif, sexuel, sensuel, corporel.
</p> 
<p class="intro-text">Après un coma, une «absence» à soi-même et aux autres, il est parfois difficile de retrouver les liens d’avant l’accident ou l’AVC, difficile de se projeter dans une relation amoureuse, dans un désir d’enfant, d’accepter des pertes. Notre premier cycle, débuté en février 2020 se termine en octobre de cette année et propose art-thérapie, collage et argile. Notre deuxième cycle débutera en janvier 2021 pour se terminer en mai et proposera la composition de chansons et l’écriture comme médiations.
</p>
<p class="intro-text">
Les ateliers sont ouverts aux résidents de la Novelline ainsi qu’à des personnes extérieures, vivant avec les séquelles d’une cérébro-lésion.
</p> 
<p class="intro-text">Renseignements: 03 85 21 01 95
</p>

<ul style="text-align:right;list-style-type:none">
    <li>
      <a style="color:hsl(171,93.5%,36.5%); font-size:30px" href="/media/VAS_plaq_2020_01_HDsfp.pdf" download="download">●&nbsp;Cliquer pour télécharger la plaquette</a>
    </li>
</ul>
<div class="center-block">
<img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_500/v1601752923/gatsby-cloudinary/plaquette_p1.png" alt="flyer savoir s'aimer pour savoir aimer, cycle d'animations proposé par la Novelline, à Cluny, renseignements: 03 85 21 01 95">
</div>
