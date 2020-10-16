---
layout: logoTop
title: Histoire de mes ressemblances, atelier d'écriture gratuit destiné aux seniors du Val de Joux
summary: Atelier d'écriture gratuit destiné aux seniors du val de Joux
Phrase: Cycle d'ateliers destiné aux résidents de la résidence du val de Joux et aux seniors extérieurs, ayant pour but la création d'un livret sur le thème de la transmission et de l'histoire familiale.
---

<h1>Histoire de mes ressemblances</h1>

<!-- Slideshow container -->
<div class="slideshow-container" style="position: relative;">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides">
    <div class="numbertext">1 / 6</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1601915140/gatsby-cloudinary/bobine-fil-H.jpg" style="width:100%">
      <figcaption class="figCap">© Lucie Moraillon</figcaption>
    </figure>
  </div>
  
  <div class="mySlides">
    <div class="numbertext">2 / 6</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1601915144/gatsby-cloudinary/four-laughing-H.jpg" style="width:100%">
      <figcaption class="figCap">© Lucie Moraillon</figcaption>
    </figure>
  </div>

  <div class="mySlides">
    <div class="numbertext">3 / 6</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1601915143/gatsby-cloudinary/music-box-H.jpg" style="width:100%">
      <figcaption class="figCap">© Lucie Moraillon</figcaption>
    </figure>
  </div>

  <div class="mySlides">
    <div class="numbertext">4 / 6</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1601916568/gatsby-cloudinary/framed-picture-H.jpg" style="width:100%">
      <figcaption class="figCap">© Lucie Moraillon</figcaption>
    </figure>
  </div>

  <div class="mySlides" style="max-width: 400px; margin: auto">
    <div class="numbertext">5 / 6</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_400/v1601916444/gatsby-cloudinary/fagot-V.jpg" style="width:100%">
      <figcaption class="figCap">© Lucie Moraillon</figcaption>
    </figure>
  </div>

  <div class="mySlides" style="max-width: 400px; margin: auto">
    <div class="numbertext">6 / 6</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_400/v1601916444/gatsby-cloudinary/unframed-marriage-V.jpg" style="width:100%">
      <figcaption class="figCap">© Lucie Moraillon</figcaption>
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

<p class="intro-text">«Histoire de mes ressemblances» est un cycle d’ateliers destinés aux seniors, qui se déroule en partenariat avec la résidence du Val de Joux de Saint Bonnet de Joux (71), ouvert aux résidents et aux personnes extérieures vivant dans le Clunisois et le Charolais.
</p>
<p class="intro-text">Ce projet a pour vocation de réfléchir, de partager et de créer autour de la notion de transmission.
</p>
<p class="intro-text">De qui tient-on ce sourire, ce trait de caractère, ce goût pour les arts ou le travail des mains ?
</p>
<p class="intro-text">Il y a dans ces ressemblances que nous portons malgré nous ou que nous revendiquons, l’histoire que l’on se raconte, celle que l’on transmet, celle qui nous est racontée, celle que l’on arrange ou celle que l’on rêve.
</p>
<p class="intro-text">Différents supports sont proposés (évocations d’objets, écriture, parole, photographie.), et seront réunis dans un livret destiné aux participants, à leurs familles et à la jeune génération.
</p>
<p class="intro-text">Les ateliers ont débuté en novembre 2019 et se terminent en octobre 2020.
</p>

<div class="center-block">
    <img src="https://res.cloudinary.com/dnxcesebo/image/upload/v1567428674/2019-08-_Pass_age_v1_xgygqk.jpg">
</div>

<div class="center-block">
    <img src="https://res.cloudinary.com/dnxcesebo/image/upload/v1567428869/pass_age_p2_atsyim.jpg">
</div>
