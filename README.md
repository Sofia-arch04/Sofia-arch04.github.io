
<html lang="fr">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

<h1 style="font-size: 36px;">Offre culturelle à Paris</h1>

Plan du projet
1. Introduction   
2. Analyse de données


<h2> Partie 1 - Introduction</h2>


  L’offre culturelle en grande banlieue parisienne : une répartition équitable face à la densité de population ?

L’offre culturelle constitue un levier essentiel du développement social et territorial. À Paris, la concentration des équipements culturels est particulièrement élevée, mais cette abondance se heurte à une réalité contrastée dès que l’on s’éloigne du cœur métropolitain. En grande banlieue parisienne, l’accès à la culture reste souvent inégal, tant en quantité qu’en proximité.

Cette étude propose d’interroger la répartition des lieux culturels (bibliothèques, musées, cinémas, théâtres, centres d’art, etc.) dans les grandes couronnes de l’Île-de-France, en lien avec la densité de population et les conditions d’accessibilité. L’objectif est de déterminer si l’offre culturelle dans ces territoires périphériques est adaptée aux besoins des populations locales.

Pour ce faire, nous croiserons plusieurs indicateurs : la localisation des équipements culturels (extraits d’OpenStreetMap), les données démographiques communales (issues de l’INSEE), ainsi qu’un indicateur d’accessibilité spatiale. L’analyse sera menée à l’aide d’un système d’information géographique (SIG), afin de produire des cartes thématiques révélant les éventuelles inégalités territoriales.

Nous chercherons ainsi à identifier les disparités dans l’accès à la culture selon les zones de la grande banlieue parisienne, et à proposer des pistes d’amélioration pour une répartition plus équitable des ressources culturelles.

Au-delà du constat, ce travail vise à rappeler que l’accès à la culture, facteur de cohésion sociale, ne doit pas être un privilège réservé aux centres urbains. Une meilleure répartition des équipements culturels dans les territoires périurbains apparaît aujourd’hui comme un enjeu central pour garantir l’égalité d’accès à la vie culturelle et citoyenne.


2 - Méthodologie

=> Données sur la densité de population
<head>
   <img width="660" alt="Densité pop" src="https://github.com/user-attachments/assets/fdf22230-e757-403b-beef-58115de1a97e" />   background-position: center center; /* Cela centre l'image sur la page */
            background-repeat: no-repeat; /* Cela évite que l'image se répète */
            color: white; /* Texte en blanc
      

=> Recensement des lieux culturels (bibliothèques, cinémas, musées, théâtres, etc.)

   <head>
<img width="646" alt="Recensement des lieux culturels" src="https://github.com/user-attachments/assets/798b8221-abc1-4c7b-9025-f987efde8694" /> 
   background-position: center center; /* Cela centre l'image sur la page */
            background-repeat: no-repeat; /* Cela évite que l'image se répète */
     

<img width="669" alt="Recensement des lieux culturels zoom" src="https://github.com/user-attachments/assets/8047a719-3c05-4684-a854-67109a282a96" />
   background-position: center center; /* Cela centre l'image sur la page */
            background-repeat: no-repeat; /* Cela évite que l'image se répète */
            color: white; /* Texte en blanc

"<img width="697" alt="Capture d’écran 2025-05-06 à 16 49 43" src="https://github.com/user-attachments/assets/637c2c18-84c7-4721-b0ef-e070a829e272" />
   background-position: center center; /* Cela centre l'image sur la page */
            background-repeat: no-repeat; /* Cela évite que l'image se répète */
            color: white; /* Texte en blanc


Dans cette étude sur l'accès à l'offre culturelle en grande banlieue parisienne, j'ai choisi de faire des zooms spécifiques sur le recensement des lieux culturels pour plusieurs raisons importantes.

Tout d'abord, ces lieux culturels (bibliothèques, cinémas, musées, théâtres, etc.) représentent des ressources essentielles pour la cohésion sociale et l'épanouissement des individus. Cependant, leur répartition géographique n'est pas toujours uniforme, et certains territoires peuvent être mieux desservis que d'autres, créant ainsi des inégalités d'accès à la culture.

Le zoom sur le recensement des lieux culturels permet de répondre à cette problématique en identifiant précisément où se trouvent ces équipements. En croisant ces données avec des informations sur la densité de population et l'accessibilité (temps de trajet, distances), il est possible de mieux comprendre comment l'offre culturelle est distribuée dans les différentes zones de la grande banlieue. Ces zooms permettent de repérer les zones sous-desservies, où la population peut être éloignée de ces lieux de culture, et de soulever des questions sur l'égalité d'accès.

En outre, se concentrer sur ce recensement permet d'affiner l'analyse en prenant en compte non seulement la quantité de lieux culturels, mais aussi leur répartition par rapport aux besoins des populations locales. Cette démarche aide à mieux comprendre si l'offre culturelle suit réellement les dynamiques démographiques, et si des ajustements sont nécessaires pour assurer une plus grande équité dans l'accès à la culture.

En résumé, le choix de faire ces zooms sur le recensement des lieux culturels est une étape clé pour évaluer l'impact de la distribution de ces équipements sur les inégalités territoriales d'accès à la culture. Cela permet de cibler les zones où des efforts supplémentaires pourraient être faits pour garantir une meilleure répartition des ressources culturelles.






---



<section class="container mt-4">
    <h2> Partie 2 - Analyse des données</h2>
  1. Croisement des données géographiques et démographiques

Cette étape consiste à croiser les données sur la répartition des équipements culturels (bibliothèques, musées, cinémas, etc.) avec celles concernant la densité de population. L'objectif est de vérifier si les zones les plus peuplées de la grande banlieue sont également les mieux desservies en équipements culturels. À l'aide de Systèmes d'Information Géographique (SIG), nous créons des cartes qui visualisent cette répartition et permettent d'identifier les zones sous-desservies, en fonction de la population locale.

2. Calcul de l’accessibilité des lieux culturels

Nous analysons l’accessibilité des lieux culturels en prenant en compte deux principaux critères :

La distance physique entre les lieux culturels et les zones résidentielles (en voiture, à pied ou en transport public).
Les transports en commun, en évaluant leur disponibilité et leur efficacité pour desservir ces lieux.
Cela permet de comprendre si les habitants, en particulier dans les zones plus périphériques, peuvent facilement accéder aux équipements culturels ou s’ils font face à des obstacles géographiques ou de transport.

3. Outils utilisés : SIG (Système d'Information Géographique)

Nous utilisons le SIG pour cartographier les équipements culturels et analyser leur relation avec les données démographiques. Le SIG permet de visualiser les zones où les équipements sont concentrés et celles où ils sont rares. Cela permet de proposer des solutions pour améliorer l’accès à la culture dans les zones les moins desservies, en analysant à la fois la densité de population et l’accessibilité géographique.

