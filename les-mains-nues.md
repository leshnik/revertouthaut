---
layout: logoTop
title: les mains nues
---

<h1>les mains nues</h1>

<!-- Slideshow container -->
<div class="slideshow-container" style="position: relative;">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides">
    <div class="numbertext">1 / 10</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1602006221/gatsby-cloudinary/mains-nues74.svg">
      <figcaption class="figCap"></figcaption>
    </figure>
  </div>
  
  <div class="mySlides">
    <div class="numbertext">2 / 10</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1602006613/gatsby-cloudinary/mains-nues20.svg">
      <figcaption class="figCap"></figcaption>
    </figure>
  </div>
  
  <div class="mySlides">
    <div class="numbertext">3 / 10</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1602006688/gatsby-cloudinary/mains-nues31.svg">
      <figcaption class="figCap"></figcaption>
    </figure>
  </div>

  <div class="mySlides">
    <div class="numbertext">4 / 10</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1602006776/gatsby-cloudinary/mains-nues33.svg">
      <figcaption class="figCap"></figcaption>
    </figure>
  </div>

  <div class="mySlides">
    <div class="numbertext">5 / 10</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1602006850/gatsby-cloudinary/mains-nues50.svg">
      <figcaption class="figCap"></figcaption>
    </figure>
  </div>

  <div class="mySlides">
    <div class="numbertext">6 / 10</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1602006925/gatsby-cloudinary/mains-nues51.svg">
      <figcaption class="figCap"></figcaption>
    </figure>
  </div>

  <div class="mySlides">
    <div class="numbertext">7 / 10</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1602007036/gatsby-cloudinary/mains-nues54.svg">
      <figcaption class="figCap"></figcaption>
    </figure>
  </div>

<div class="mySlides">
    <div class="numbertext">8 / 10</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1602007168/gatsby-cloudinary/mains-nues58.svg">
      <figcaption class="figCap"></figcaption>
    </figure>
  </div>

<div class="mySlides">
    <div class="numbertext">9 / 10</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1602007231/gatsby-cloudinary/mains-nues62.svg">
      <figcaption class="figCap"></figcaption>
    </figure>
  </div>

<div class="mySlides">
    <div class="numbertext">10 / 10</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_800/v1602007370/gatsby-cloudinary/mains-nues63.svg">
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

<p class="intro-text">Avant <span class="rever-typog">rêver tout haut</span>, Valérie Gaudissart a animé à la Maison d’Arrêt de Dijon un atelier vidéo et écriture avec et pour des femmes prévenues. Voici donc «Les mains nues», film qui retrace un atelier mené l’été 2009 et pour lequel il a fallu inventer un dispositif créatif compatible avec les contraintes de la prison : pas d’images reconnaissables des femmes, ni de leurs effets personnels. C’est pourquoi, après un atelier d’une semaine consacrée à l’écriture, l’échange de paroles, pendant lequel l’objectif était de revaloriser l’image de soi, et de se projeter dans l’avenir et vers un chemin nouveau, un deuxième temps d’atelier a suivi, pendant lequel deux comédiennes sont venues interpréter les textes écrits devant et avec les prévenues.
</p>

<p class="intro-text">Nous tenions à rendre compte ici de ce travail sur le site de Rêver Tout Haut car il a alimenté nos réflexions futures sur la conception de certains de nos ateliers.
</p>

<h2>les mains nues</h2>
<div class="space-below"></div>

<script src="https://fast.wistia.com/embed/medias/659jhbpr5j.jsonp" async></script><script src="https://fast.wistia.com/assets/external/E-v1.js" async></script><div class="wistia_responsive_padding" style="padding:75.0% 0 0 0;position:relative;"><div class="wistia_responsive_wrapper" style="height:100%;left:0;position:absolute;top:0;width:100%;"><div class="wistia_embed wistia_async_659jhbpr5j videoFoam=true" style="height:100%;position:relative;width:100%"><div class="wistia_swatch" style="height:100%;left:0;opacity:0;overflow:hidden;position:absolute;top:0;transition:opacity 200ms;width:100%;"><img src="https://fast.wistia.com/embed/medias/659jhbpr5j/swatch" style="filter:blur(5px);height:100%;object-fit:contain;width:100%;" alt="" aria-hidden="true" onload="this.parentNode.style.opacity=1;" /></div></div></div></div>

<p class="intro-text">Résumé: <em>une caméra, des femmes qui écrivent et qui racontent, des femmes qui jouent...</em>
</p>
<p class="cite">31 minutes<br>Réalisation et atelier : Valérie Gaudissart<br>
Avec Sylvia Etcheto et Blandine Pélissier<br>
Musique : Morton Potash
</p>
