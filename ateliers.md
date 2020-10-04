---
layout: logoTop
title: ateliers
---

<div class="Motto">ateliers</div>
<p class="intro-text"><span class="rever-typog">rêver tout haut</span>, en réponse à des demandes individuelles, groupales ou institutionnelles conçoit, organise et anime des ateliers divers, souvent complémentaires, et menés par toute une équipe d’intervenant.es qui communiquent entre elles/eux afin de permettre et d’inventer le meilleur accompagnement possible.
</p>
<p class="intro-text">Nous intervenons à domicile, en cabinet et en institution.
</p>
<p class="intro-text">Différentes activités sont proposées : art-thérapie, sophrologie, musique, photographie, vidéo, textiles, argile, vannerie, écriture, composition de chansons, travail du corps et de la voix... toujours dans un objectif thérapeutique et réparateur et dans la perspective de mettre certaines problématiques en travail.
</p>

<p class="intro-text">Voici quelques uns de nos ateliers à venir, en cours, ou effectués depuis 2019.
</p>
<ul class="CenterList">
  <li><a style="color: hsl(40.6,50.5%,42%)" href="/cycles-de-sophrologie">●&nbsp;cycles de sophrologie</a></li>

  <li><a style="color: #29c" href="/aidants-aimants">●&nbsp;aidants, aimants</a></li>

  <li><a style="color: hsl(120,50%,42%)" href="/liens-familiaux-defaits-renoues">●&nbsp;liens familiaux défaits, renoués</a>
  </li>

  <li><a style="color: hsl(200,50%,42%)" href="/deja-parent">●&nbsp;déjà parent</a></li>

  <li><a style="color: hsl(240,50%,42%)" href="/amours-desirs-et-absences">●&nbsp;amours, désirs et absences</a>
  </li>

  <li><a style="color: hsl(300,50%,42%)" href="/de-l-air">●&nbsp;de l'air&nbsp;!</a></li>

  <li><a style="color: hsl(330,50%,42%)" href="/changer-de-pays">●&nbsp;changer de pays</a></li>

  <li><a style="color: hsl(165, 50%, 42%)" href="/les-plus-que-proches">●&nbsp;les plus que proches</a></li>

  <li><a style="color: #29c" href="/les-petites-lucarnes">●&nbsp;les petites lucarnes</a></li>

  <li><a style="color: rgb(181, 136, 136)" href="/histoire-de-mes-ressemblances">●&nbsp;histoire de mes ressemblances</a></li>

</ul>
<div class="Spacer"></div>
<!-- Slideshow container -->
<div class="slideshow-container" style="position: relative;">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides" style="max-width: 400px; margin: auto">
    <div class="numbertext">1 / 3</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_400/v1601828382/gatsby-cloudinary/dessin-colore%CC%81.jpg" style="width:100%">
      <figcaption class="figCap"></figcaption>
    </figure>
  </div>
  
  
  <div class="mySlides" style="max-width: 400px; margin: auto">
    <div class="numbertext">2/ 3</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_400/v1601828381/gatsby-cloudinary/colline-floue.jpg" style="width:100%">
      <figcaption class="figCap"></figcaption>
    </figure>
  </div>

  <div class="mySlides" style="max-width: 400px; margin: auto">
    <div class="numbertext">3/ 3</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_400/v1601845305/gatsby-cloudinary/face-pursed-lips.jpg" style="width:100%">
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
