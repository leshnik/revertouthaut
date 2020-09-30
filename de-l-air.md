---
layout: logoTop
title: De l'air !
---

<div class="Motto">
de l'air&nbsp;!
</div>
<p class="intro-text">
Sur une proposition du Foyer de Vie et du Foyer d’Accueil Médicalisé les Avouards, à Bonnay (71), Rêver Tout Haut est intervenu sur un cycle d’ateliers à la suite du déconfinement. De juillet à septembre 2020, nous avons animé des ateliers que nous voulions les plus ouverts possibles, permettant une itinérance, un mouvement, une forme de liberté, restreints jusque là du fait du confinement.
</p>
<p class="intro-text">Nos ateliers ont donc accueilli les résidents et les soignants une matinée par semaine pendant l’été. Nos trois ateliers avaient lieu en simultané et pouvaient permettre aux participants de passer de l’un à l’autre, de revenir, de choisir. Nous avons proposé art-thérapie, sophrologie et travail corporel, et musique et composition de chansons.
</p>
<p class="intro-text">L’idée de cette proposition créative plurielle était de remettre de la vie dans un lieu confiné, et par nos médiations complémentaires, de permettre aux résidents de s’exprimer sur différents supports et d’arriver à faire des liens entre ces différents modes d’expression.
</p>
<p class="intro-text">Chansons, dessins, peinture ont donc été créées à foison&nbsp;!
</p>

<!-- Slideshow container -->
<div class="slideshow-container" style="position: relative;">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides">
    <div class="numbertext">1 / 6</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/q_auto,f_auto,w_800/v1601402167/gatsby-cloudinary/m-----ir.jpg" style="width:100%;">
    </figure>
  </div>
  <div class="mySlides">
    <div class="numbertext">2 / 6</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/q_auto,f_auto,w_800/v1601402171/gatsby-cloudinary/trois-sur-fil.jpg" style="width: 100%">
    </figure>
  </div>

  <div class="mySlides">
    <div class="numbertext">3 / 6</div>
    <figure><img src="https://res.cloudinary.com/dnxcesebo/image/upload/q_auto,f_auto,w_327/v1601448256/gatsby-cloudinary/st---2-2-short.jpg" style="width:40%;">
    </figure>
  </div>

  <div class="mySlides">
    <div class="numbertext">4 / 6</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/q_auto,f_auto,w_800/v1601385516/gatsby-cloudinary/avouards-clothesline-inside.jpg" style="width:100%">
    </figure>
  </div>
  <div class="mySlides">
    <div class="numbertext">5 / 6</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/q_auto,f_auto,w_647/v1601449225/gatsby-cloudinary/redface.jpg" style="width:80%">
    </figure>
  </div>
  <div class="mySlides">
    <div class="numbertext">6 / 6</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/q_auto,f_auto,w_820/v1601449524/gatsby-cloudinary/avouards-fil-dehors.jpg" style="width:100%">
    </figure>
  </div>

  <!-- Next and previous buttons -->
  <div style="display: flex; flex-wrap:nowrap; justify-content:space-around;">
    <div>
      <a class="prev" onclick="plusSlides(-1)" style="cursor:pointer; color: green; font-size:2rem">&#10094;</a>
    </div>
    <div>
      <a class="next" onclick="plusSlides(1)" style="cursor:pointer; color: green; font-size:2rem;">&#10095;</a>
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
