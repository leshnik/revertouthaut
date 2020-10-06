---
layout: logoTop
title: séances à domicile
---

<div class="Motto">séances à domicile</div>

<p class="intro-text">Dans l’idée d’accompagner et de rendre possible le maintien à domicile, de stimuler des capacités cognitives, d’apporter une aide ou de compléter un suivi médical ou psychologique, Rêver Tout Haut propose des séances d’art-thérapie et de sophrologie sur vos lieux de résidence.</p>

<p class="intro-text">Si vous avez des difficultés à vous déplacer, si vous voulez rompre votre isolement, si vous avez envie de redonner du sens à l’investissement de votre lieu de vie, ou si vous désirez diversifier votre programme de soins, nous pouvons élaborer avec vous le rythme et le contenu des séances.</p>

<p class="intro-text">Nous nous déplaçons à domicile dans un rayon de 30 kilomètres autour de Cluny (71).</p>

<!-- Slideshow container -->
<div class="slideshow-container" style="position: relative;">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides">
    <div class="numbertext">1 / 8</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1601972836/gatsby-cloudinary/still-life-teapot-stones.svg">
      <figcaption class="figCap"></figcaption>
    </figure>
  </div>

  <div class="mySlides">
    <div class="numbertext">2 / 8</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1601972834/gatsby-cloudinary/ladder-white-door-2nd-drawing.svg">
      <figcaption class="figCap"></figcaption>
    </figure>
  </div>

  <div class="mySlides">
    <div class="numbertext">3 / 8</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1601972832/gatsby-cloudinary/black-woman-grey-room.svg">
      <figcaption class="figCap"></figcaption>
    </figure>
  </div>

  <div class="mySlides">
    <div class="numbertext">4 / 8</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1601972831/gatsby-cloudinary/portraits-sur-mur.svg">
      <figcaption class="figCap"></figcaption>
    </figure>
  </div>

  <div class="mySlides">
    <div class="numbertext">5 / 8</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1601972830/gatsby-cloudinary/pursed-lips-portrait.svg">
      <figcaption class="figCap"></figcaption>
    </figure>
  </div>

  <div class="mySlides">
    <div class="numbertext">6 / 8</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1601972818/gatsby-cloudinary/acquamarine-bird.svg">
      <figcaption class="figCap"></figcaption>
    </figure>
  </div>

  <div class="mySlides">
    <div class="numbertext">7 / 8</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1601961293/gatsby-cloudinary/five-pink-red.svg">
      <figcaption class="figCap"></figcaption>
    </figure>
  </div>

  <div class="mySlides">
    <div class="numbertext">8 / 8</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1601972830/gatsby-cloudinary/montagne.svg">
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
