---
layout: logoTop
title: Les petites lucarnes - ateliers destinés aux personnes en insertion à Mâcon et Châlon sur Saône.
summary: Destiné à des personnes en insertion, un cycle d'ateliers réunissant art thérapie, musique, photographie, vidéo, et ayant comme but la revalorisation, l'estime de soi et le retour vers l'emploi. Soutenu par l'association Le Pont.
---

<h1>Les petites lucarnes</h1>
<p class="intro-text"><cite>La lucarne est une ouverture, et c’est aussi de par sa forme et sa matière, une vitre dans laquelle voir son reflet, et c’est aussi un écran sur lequel peuvent se projeter des images. Se refléter (et « se » réfléchir ») et se projeter, voilà donc les buts recherchés dans notre dispositif d’ateliers. </cite></p>

<!-- Slideshow container -->
<div class="slideshow-container">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides" style="max-width:600px; margin:auto">
    <div class="numbertext">1 / 9</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/q_auto,f_auto,w_400/v1601539622/gatsby-cloudinary/photo-comme-miroir.jpg" style="width:100%">
      <figcaption class="figCapCenter">© Lucie Moraillon</figcaption>
    </figure>
  </div>
  <div class="mySlides" style="max-width:600px; margin:auto">
    <div class="numbertext">2 / 9</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_400/v1601542725/gatsby-cloudinary/hand-reach-tatoo.jpg" style="width:100%">
      <figcaption class="figCapCenter">© Lucie Moraillon</figcaption>
    </figure>
  </div>
  
  <div class="mySlides" style="max-width:600px; margin:auto">
    <div class="numbertext">3 / 9</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_400/v1601543186/gatsby-cloudinary/photo_1_lucarne.jpg" style="width:100%">
      <figcaption class="figCapCenter">© Lucie Moraillon</figcaption>
    </figure>
  </div>
  <div class="mySlides" style="max-width:600px; margin:auto">
    <div class="numbertext">4 / 9</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_400/v1601543803/gatsby-cloudinary/le-walk.jpg" style="width:100%">
      <figcaption class="figCapCenter">© Lucie Moraillon</figcaption>
    </figure>
  </div>
  <div class="mySlides" style="max-width:600px; margin:auto">
    <div class="numbertext">5 / 9</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_400/v1601544829/gatsby-cloudinary/cadres-blouse-grise.jpg" style="width:100%">
      <figcaption class="figCapCenter">© Lucie Moraillon</figcaption>
    </figure>
  </div>
  <div class="mySlides" style="max-width:600px; margin:auto">
    <div class="numbertext">6 / 9</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_400/v1601546026/gatsby-cloudinary/two-hands-text600.png" style="width:100%">
      <figcaption class="figCapCenter">© Lucie Moraillon</figcaption>
    </figure>
  </div>
  <div class="mySlides" style="max-width:600px; margin:auto">
    <div class="numbertext">7 / 9</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_400/v1601775006/gatsby-cloudinary/clay-catlike.jpg" style="width:100%">
      <figcaption class="figCapCenter"></figcaption>
    </figure>
  </div>
  <div class="mySlides" style="max-width:600px; margin:auto">
    <div class="numbertext">8 / 9</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_400/v1601547085/gatsby-cloudinary/dresseuse-dragons.jpg" style="width:100%">
      <figcaption class="figCapCenter">© Lucie Moraillon</figcaption>
    </figure>
  </div>
<div class="mySlides" style="max-width:600px; margin:auto">
    <div class="numbertext">9 / 9</div>
    <figure>
      <img src="https://res.cloudinary.com/dnxcesebo/image/upload/f_auto,q_auto,w_400/v1601774668/gatsby-cloudinary/portrait-blue-earrings4x6.jpg" style="width:100%">
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

<h2>Quelques unes des<br> chansons composées</h2>
<figure>
    <h4 style="color: black">devant le miroir:</h4>
    <audio
        controls
        src="/media/dans-le-miroir-compo-chant-florian.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
    <figcaption class="figCapCenter">© Florian Girard, chant: Florian Girard</figcaption>
</figure>
<p class="quote">
quand je me regarde dans le miroir<br>
je vois cette tête qui est moi sans l’être vraiment<br>
me regarde dans les yeux<br>
en voyant cette âme consumée<br>
ces yeux bleus qu’on dit beaux<br>
ces oreilles qu’on voit grandes<br>
et je revois mes visages d’avant<br>
ceux qui ont été tués par le temps<br>
et en me voyant les yeux déchirés<br>
par tous ces joints fumés<br>
mon empathie joue avec mes souvenirs<br>
<br>
devant le miroir<br>
devant le miroir<br>
je vois alors cet homme plein de rage<br>
pourtant rempli de gentillesse<br>
mais que le temps a rendu méfiant<br>
hésitant, blessant parfois<br>
même envers lui trop méchant<br>
et crois moi c’est chiant<br>
alors je pose un chant devant ce moi même<br>
je clashe contre moi même<br>
je me fâche dans les insultes<br>
et je me lâche<br>
t’es con ou quoi t’aurais du faire ça<br>
t’es con ou quoi t’aurais du faire ça<br>
<br>
devant le miroir<br>
quand je retrouve une certaine raison<br>
je me fais un doigt d’honneur<br>
à moi pas au miroir<br>
me lamentant de mes états dérisoires<br>
de désespoir, dans l’envie de boire<br>
devant le miroir<br>
deuxième doigt d’honneur<br>
sur moi même et mes douleurs<br>
mon pét’ m’attend pour soulager mes erreurs<br>
même pas peur<br>
salut l’enculé dans le miroir<br>
c’est l’heure de me dire bonsoir.
</p>


<figure>
    <h4 style="color: black">mes mains mon gagne-pain:</h4>
    <audio
        controls
        src="/media/mes-mains-mon-gagne-pain.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
    <figcaption class="figCapCenter">© Morton Potash, chant: Sidonie Dubosc</figcaption>
</figure>
<p class="quote">
mes mains mon gagne-pain<br>
manger à ma faim<br>
hiver été les champs et les prés<br>
la faux et la bêche<br>
la hache et la scie<br>
pommiers pêchers mes mains sont transies<br>
la calligraphie tracée par le givre<br>
moments de répit<br>
pensées qui m'enivrent<br>
dans l’avenir elles feraient bien d’écrire des bouquins<br>
pour découvrir l'autre face d'une planète cachée<br>
ou aller dans la cuisine, faire fondre<br>
du chocolat<br>
ajouter des œufs de la farine<br>
et faire des crêpes avec tout ça

</p>
<figure>
    <h4 style="color: black">retourne chez toi :</h4>
    <audio
        controls
        src="/media/retourne-chez-toi-compo-chant-morton.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
    <figcaption class="figCapCenter">© Morton Potash, chant: Morton Potash</figcaption>
</figure>
<p class="quote">
retourne chez toi<br>
et oublie moi<br>
me prends pas la tête sinon,<br>
je vais me vener<br>
je reste calme<br>
m'enflamme pas ça va chauffer<br>
<br>
pourquoi tu m'cherches<br>
tu fais pitié<br>
on n'a rien en commun que dalle<br>
on n'est pas copains<br>
qu'est-ce que tu m'veux ?<br>
dégage que j'te revois plus
</p>
<figure>
  <h4 style="color: black">dans le miroir:</h4>
  <audio controls src="/media/dans-le-miroir-val.mp3">
  Your browser does not support the
            <code>audio</code> element.
  </audio>
  <figcaption class="figCapCenter">© Morton Potash, chant: Valérie Gaudissart</figcaption>
  </figure>

  <p class="quote">
  des fois le matin<br>
quand je me regarde dans le miroir<br>
j'ai pas vu le temps passé<br>
et pourtant<br>
tout est bien loin<br>
j'ai un grand vide comme si un tsunami<br>
avait emporté tous ces années<br>
j'ai le sentiment<br>
d'avoir oublié<br>
et pourtant je me souviens<br>
de tous ces moments<br>
et plus j'y pense plus ils sont nombreux<br>
et puis<br>
finalement<br>
jour après jour année après année<br>
le reflet du miroir<br>
me rappelle que ce temps-là<br>
est bien passé<br>
est bien passé
</p>


<figure>
    <h4 style="color: black">douceur:</h4>
    <audio
        controls
        src="/media/douceur.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
    <figcaption class="figCapCenter">© Morton Potash, chant: Sidonie Dubosc</figcaption>
</figure>
<p class="quote">
douceur<br>
les yeux fermés<br>
trop de crier<br>
je suis fatigué<br>
de toi<br>
mon ange<br>
<br>
douleur<br>
les mains serrées<br>
trop de pleurer<br>
je suis énervée<br>
de moi ma biche<br>
de moi ma biche<br>
de moi<br>
mon ange
</p>
<figure>
    <h4 style="color: black">j'avance:</h4>
    <audio
        controls
        src="/media/j-avance-chant-valerie.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
        <figcaption class="figCapCenter">© Morton Potash, chant: Valérie Gaudissart</figcaption>

</figure>
<p class="quote">
j'avance<br>
je suis une délinquante<br>
j'avance<br>
je ne regrette rien<br>
car le regret n'efface rien<br>
j'avance, j'avance<br>
quand je m'engage<br>
j'obtiens ce que je veux<br>
j'avance<br>
j'ai été punie<br>
pour ce que j'ai commis<br>
j'avance<br>
je ne veux pas changer<br>
j'aime comme je suis<br>
j'avance<br>
faut pas m'emmerder<br>
on ne peut pas me déstabiliser<br>
j'avance<br>
pour ma gueule j'avance<br>
pour mes filles j'avance<br>
j'avance, j'avance, j'avance
</p>

<p class="intro-text">Ateliers animés par Valérie Gaudissart, Lucie Moraillon, Patricia Rigo, Florian Girard, et Morton Potash</p>
