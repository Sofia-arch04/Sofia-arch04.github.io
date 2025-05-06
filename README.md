
<html lang="fr">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

<h1 style="font-size: 36px;">Offre culturelle à Paris</h1>

Plan du projet <br>
1. Introduction  <br> 
2. Analyse de données<br><br>
Problématique :   L’offre culturelle en grande banlieue parisienne : une répartition équitable face à la densité de population ?
<br><br>

<h2> Partie 1 - Introduction</h2>

<br><br>
La culture joue un rôle clé dans la vie sociale et dans le développement des territoires. À Paris, les lieux culturels sont nombreux et très concentrés, mais cette richesse s’estompe peu à peu dès qu’on s’éloigne du centre. En grande banlieue, l’accès à la culture devient souvent plus compliqué : les équipements sont moins nombreux, parfois éloignés, et les habitants n’y ont pas toujours facilement accès.
<br><br>
Cette étude cherche à comprendre comment les lieux culturels — bibliothèques, musées, cinémas, théâtres, centres d’art, etc. — sont répartis sur le territoire parisien, en tenant compte de la densité de population et des conditions d’accessibilité. L’objectif est de voir si, dans les zones périphériques, l’offre culturelle correspond réellement aux besoins et aux réalités des habitants.
<br><br>
Pour ce faire, nous croiserons plusieurs indicateurs : la localisation des équipements culturels (extraits d’OpenStreetMap), les données démographiques communales (issues de l’INSEE), ainsi qu’un indicateur d’accessibilité spatiale. L’analyse sera menée à l’aide d’un système d’information géographique (SIG), afin de produire des cartes thématiques révélant les éventuelles inégalités territoriales.
<br><br>
L’objectif est donc d’identifier les inégalités d’accès à la culture selon les différentes zones de Paris, et d’envisager des pistes pour mieux répartir les ressources culturelles de manière plus juste et équilibrée.
<br><br>
Au-delà du constat, ce travail cherche à souligner que l’accès à la culture, essentiel pour la cohésion sociale, ne doit pas être un privilège réservé aux quartiers centraux. Assurer une meilleure répartition des équipements culturels dans Paris est désormais un enjeu majeur pour garantir à tous un accès égal à la vie culturelle et citoyenne.
<br><br><br>

<u>=> Données sur la densité de population</u>


=> Délimitation de Paris
<br><br>
<head>

    <div style="text-align: center;">
   <img width="660" alt="Densité pop" src="https://github.com/user-attachments/assets/fdf22230-e757-403b-beef-58115de1a97e" />  
        </div>
<br>

<u>=> Données sur la densité de population</u>

hzfeciafn

<u>=> Recensement des lieux culturels (bibliothèques, cinémas, musées, théâtres, etc.)</u>
<br><br>
   <head>
       <div style="text-align: center;">
<img width="646" alt="Recensement des lieux culturels" src="https://github.com/user-attachments/assets/798b8221-abc1-4c7b-9025-f987efde8694" /> 
       </div>
 <br><br>
       <div style="text-align: center;">
<img width="669" alt="Recensement des lieux culturels zoom" src="https://github.com/user-attachments/assets/8047a719-3c05-4684-a854-67109a282a96" />
       </div>
<br><br>
       <div style="text-align: center;">
"<img width="697" alt="Capture d’écran 2025-05-06 à 16 49 43" src="https://github.com/user-attachments/assets/637c2c18-84c7-4721-b0ef-e070a829e272" /> 
       </div>
<br><br><br>
Dans cette étude sur l'accès à l'offre culturelle à Paris, j'ai choisi de faire des zooms spécifiques sur le recensement des lieux culturels pour plusieurs raisons importantes.
<br><br>
Les lieux culturels (bibliothèques, cinémas, musées, théâtres, etc.) jouent un rôle clé dans la cohésion sociale et l’épanouissement personnel. Pourtant, leur répartition géographique n’est pas toujours équitable : certains territoires bénéficient d’un meilleur accès que d’autres, ce qui crée des inégalités dans l’accès à la culture.
<br><br>
En se concentrant sur le recensement des lieux culturels, cette étude répond à la problématique en identifiant précisément où se trouvent ces équipements. En croisant ces données avec des informations sur la densité de population et l'accessibilité (temps de trajet, distances), il devient possible de mieux comprendre la répartition de l'offre culturelle dans les différentes zones de Paris. Ces analyses permettent de repérer les zones sous-desservies, où la population est éloignée de ces équipements, et d’ouvrir la réflexion sur l'égalité d'accès à la culture.
<br><br>
De plus, se concentrer sur ce recensement permet d'affiner l'analyse en tenant compte non seulement du nombre de lieux culturels, mais aussi de leur répartition par rapport aux besoins spécifiques des populations locales. Cette approche aide à évaluer si l’offre culturelle répond vraiment aux dynamiques démographiques et si des ajustements sont nécessaires pour garantir un accès plus équitable à la culture.
<br><br>



<section class="container mt-4">
    <h2> Partie 2 - Analyse des données</h2>
    <br>
 <u> 1. Croisement des données géographiques et démographiques</u>
<br><br>
Cette étape consiste à croiser les données sur la répartition des équipements culturels (bibliothèques, musées, cinémas, etc.) avec celles concernant la densité de population. L’objectif est de vérifier si les zones les plus peuplées de Paris sont aussi les mieux desservies en équipements culturels. À l’aide de Systèmes d’Information Géographique (SIG), nous créons des cartes permettant de visualiser cette répartition et d’identifier les zones sous-desservies, en tenant compte de la population locale.

    fhiuc

    
<br><br>
<u>2. Calcul de l’accessibilité des lieux culturels</u>
<br><br>
Nous analysons l’accessibilité des lieux culturels en prenant en compte deux principaux critères :
<br><br>
La distance physique entre les lieux culturels et les zones résidentielles (en voiture, à pied ou en transport public).
Les transports en commun, en évaluant leur disponibilité et leur efficacité pour desservir ces lieux.
Cela permet de comprendre si les habitants, en particulier dans les zones plus périphériques, peuvent facilement accéder aux équipements culturels ou s’ils font face à des obstacles géographiques ou de transport.
<br><br>
<u>3. Outils utilisés : SIG (Système d'Information Géographique)</u>
<br><br>
Nous utilisons le SIG pour cartographier les équipements culturels et analyser leur relation avec les données démographiques. Le SIG permet de visualiser les zones où les équipements sont concentrés et celles où ils sont rares. Cela permet de proposer des solutions pour améliorer l’accès à la culture dans les zones les moins desservies, en analysant à la fois la densité de population et l’accessibilité géographique.
<br><br>
