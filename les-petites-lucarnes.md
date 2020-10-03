---
layout: logoTop
title: Les petites lucarnes - ateliers destinés aux personnes en insertion à Mâcon et Châlon sur Saône.
summary: Destiné à des personnes en insertion, un cycle d'ateliers réunissant art thérapie, musique, photographie, vidéo, et ayant comme but la revalorisation, l'estime de soi et le retour vers l'emploi. Soutenu par l'association Le Pont.
---

<div class="Motto">Les petites lucarnes</div>
<p class="intro-text"><cite>La lucarne est une ouverture, et c’est aussi de par sa forme et sa matière, une vitre dans laquelle voir son reflet, et c’est aussi un écran sur lequel peuvent se projeter des images. Se refléter (et « se » réfléchir ») et se projeter, voilà donc les buts recherchés dans notre dispositif d’ateliers. </cite></p>

<!-- Slideshow container -->
<div class="slideshow-container" style="position: relative;">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides" style="margin: auto; width:400px">
    <div class="numbertext">1 / 10</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/q_auto,f_auto,w_400/v1601539622/gatsby-cloudinary/photo-comme-miroir.jpg" style="height:50vh; width:auto">
      <figcaption class="figCap">© Lucie Moraillon</figcaption>
    </figure>
  </div>
  <div class="mySlides" style="margin: auto; width:400px">
    <div class="numbertext">2 / 10</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_400/v1601542725/gatsby-cloudinary/hand-reach-tatoo.jpg" style="height:50vh;">
      <figcaption class="figCap">© Lucie Moraillon</figcaption>
    </figure>
  </div>
  
  <div class="mySlides" style="margin: auto; width:400px">
    <div class="numbertext">3 / 10</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_400/v1601543186/gatsby-cloudinary/photo_1_lucarne.jpg" style="height:50vh; width:auto">
      <figcaption class="figCap">© Lucie Moraillon</figcaption>
    </figure>
  </div>
  <div class="mySlides" style="margin: auto; width:400px">
    <div class="numbertext">4 / 10</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_400/v1601543803/gatsby-cloudinary/le-walk.jpg" style="height:50vh; width:auto">
      <figcaption class="figCap">© Lucie Moraillon</figcaption>
    </figure>
  </div>
  <div class="mySlides" style="margin: auto; width:400px">
    <div class="numbertext">5 / 10</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_400/v1601544829/gatsby-cloudinary/cadres-blouse-grise.jpg" style="height:50vh; width:auto">
      <figcaption class="figCap">© Lucie Moraillon</figcaption>
    </figure>
  </div>
  <div class="mySlides" style="margin: auto; width:400px">
    <div class="numbertext">6 / 10</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_400/v1601546026/gatsby-cloudinary/two-hands-text600.png" style="height:50vh; width:auto">
      <figcaption class="figCap">© Lucie Moraillon</figcaption>
    </figure>
  </div>
  <div class="mySlides" style="margin: auto; width:400px">
    <div class="numbertext">7 / 10</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_400/v1601546487/gatsby-cloudinary/clay-catlike.jpg" style="height:50vh; width:auto">
      <figcaption class="figCap">© Lucie Moraillon</figcaption>
    </figure>
  </div>
  <div class="mySlides" style="margin: auto; width:400px">
    <div class="numbertext">8 / 10</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_400/v1601547085/gatsby-cloudinary/dresseuse-dragons.jpg" style="height:50vh; width:auto">
      <figcaption class="figCap">© Lucie Moraillon</figcaption>
    </figure>
  </div>
<div class="mySlides" style="margin: auto; width:400px">
    <div class="numbertext">9 / 10</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_400/v1601547826/gatsby-cloudinary/blue-earing-portrait.jpg" style="height:50vh; width:auto">
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

<p class="intro-text">
À la demande de l’Association le Pont, Rêver Tout Haut a participé au dispositif «Revitalisation», proposé d’octobre 2019 à juillet 2020 à une dizaine de participants sur Chalon sur Saône et Mâcon. L’objectif était de permettre à des personnes loin de l’emploi et dans un certain isolement social, accompagnés par une équipe éducative, de mettre en mouvement créativité et image de soi souvent bien mise à mal. </p>

<p class="intro-text">La temporalité des ateliers, étendue sur plusieurs mois permettant aux personnes de cheminer au travers de leur histoire, leurs résistances. Ouvrir des petites fenêtres, dégager un horizon, éclairer la vie sociale, tels étaient les buts de nos ateliers complémentaires. </p>

<p class="intro-text">Nous avons donc proposé de multiples supports afin de permettre les expériences les plus diverses : écriture, photographies, collage, photo-montage, argile, chansons, dessins, journaux de bord... L’idée était aussi de pouvoir relier entre elles toutes ces médiations : ainsi, un texte pouvait devenir une photo, un dessin pouvait amener une chanson, ou inversement. </p>

<p class="intro-text">Créer des liens sociaux, des liens d’expressions, des liens entre son passé et son avenir des passerelles entre toutes les facettes de sa personne.</p>

<div class="MottoSmaller">Quelques unes des<br> chansons composées</div>
<figure>
    <figcaption>dans le miroir:</figcaption>
    <audio
        controls
        src="/media/dans-le-miroir-compo-chant-florian.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
    <figcaption class="figCapCenter">© Florian Girard</figcaption>
</figure>
<figure>
    <figcaption>mes mains mon gagne-pain:</figcaption>
    <audio
        controls
        src="/media/mes-mains-mon-gagne-pain.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
    <figcaption class="figCapCenter">© Morton Potash, chant: Sidonie Dubosc</figcaption>
</figure>
<figure>
    <figcaption>retourne chez toi :</figcaption>
    <audio
        controls
        src="/media/retourne-chez-toi-compo-chant-morton.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
    <figcaption class="figCapCenter">© Morton Potash</figcaption>
</figure>
<figure>
    <figcaption>douceur:</figcaption>
    <audio
        controls
        src="/media/douceur.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
    <figcaption class="figCapCenter">© Morton Potash, chant: Sidonie Dubosc</figcaption>
</figure>
<figure>
    <figcaption>j'avance:</figcaption>
    <audio
        controls
        src="/media/j-avance-chant-valerie.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
        <figcaption class="figCapCenter">© Morton Potash, chant: Valérie Gaudissart</figcaption>

</figure>

<p class="intro-text">Ateliers animés par Valérie Gaudissart, Lucie Moraillon, Patricia Rigo, Florian Girard, et Morton Potash</p>
