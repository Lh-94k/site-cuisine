<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Les merveilles du Monde en Bouche</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <nav>
    <div class="titre">Les Merveilles du Monde en Bouche</div>
    <div class="onglets-container">
      <div class="onglet entree"><a href="#">Entrées</a></div>
      <div class="onglet plat"><a href="#">Plats</a></div>
      <div class="onglet dessert"><a href="#">Desserts</a></div>
    </div>
  </nav>

  <div class="section-centrale">
    <p>Bonsoir, bienvenue dans</p>
    <p><strong>"Les merveilles du Monde en Bouche"</strong></p>
    <p>Vous y trouverez tous vos désirs de la cuisine !</p>
    <p>D’après les mousquetaires de la cuisine.</p>
  </div>

  <div class="boutons">
    <button>S'inscrire</button>
    <button>Se connecter</button>
  </div>

</body>
</html>




body {
background-color: #fdf1d0; /* beige clair exact comme sur la photo */
font-family: Arial, sans-serif;
margin: 0;
padding: 0;
box-sizing: border-box;
}

nav {
text-align: center;
padding: 20px;
}

.titre {
background-color: #90ee90; /* vert clair */
padding: 10px;
font-weight: bold;
font-size: 18px;
}

.onglets-container {
display: flex;
justify-content: center;
margin: 10px auto;
width: fit-content;
border: 2px solid #000080; /* bleu foncé comme sur le croquis */
}

.onglet {
width: 200px;
padding: 10px;
border-left: 1px solid #000080;
border-right: 1px solid #000080;
text-align: center;
font-weight: bold;
}

.onglet:first-child {
border-left: none;
}

.onglet:last-child {
border-right: none;
}

.onglet a {
text-decoration: none;
color: black;
display: block;
}

.entree {
background-color: #f49cbb; /* rose clair */
}

.plat {
background-color: #f08080; /* rouge saumon */
}

.dessert {
background-color: #f4a460; /* orange sable */
}

.section-centrale {
text-align: center;
margin: 50px auto;
width: 80%;
color: #000080;
font-size: 18px;
line-height: 1.6;
font-weight: bold;
}

.boutons {
display: flex;
justify-content: center;
margin-top: 30px;
gap: 20px;
}

.boutons button {
padding: 10px 20px;
border: 2px solid #000080;
background-color: white;
color: #000080;
font-weight: bold;
cursor: pointer;
}

.boutons button:hover {
background-color: #d3d3d3;
}
