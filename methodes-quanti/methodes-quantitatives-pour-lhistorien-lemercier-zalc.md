# « Méthodes quantitatives pour l'historien » — LEMERCIER / ZALC

## Introduction

> Alors même que tout étudiant a à sa disposition des capacités de calcul dont rêvaient les chercheurs des années 1970, grâce aux développements de la micro-informatique notamment, les chemins d'apprentissage restent encore ardus. Les historiens continuent à recevoir une formation strictement littéraire et éprouvent parfois des sentiments ambivalents à l'égard du chiffre.

Après avoir été portée aux nues, l'histoire quantitative a fait l'objet de nombreuses critiques (chap I). Signe d'une "méconnaissance relative"? Aridité croissante des techniques employées?
**Chap 2.** construction d'un corpus et d'un échantillon  
**Chap 3.** saisie et codage des sources

Un panorama des principales méthodes quantitatives avec leurs grands principes, leurs domaines d'utilisation et leurs précautions d'emploi.
* visée descriptive -> 
	* nombreuses variables: analyse factorielle
* visée explicative ->
	* variables quanti: régression (linéaire...)
	* variables quali: régression logistique
	* petits effectifs: analyse quali-quantitative comparée


## Face aux sources: corpus et échantillon
### Echantillon et significativité

**Combien de cas prendre en compte?**
D'abord, la qualité des conclusions chiffrées obtenues à partir d'un échantillon aléatoire, c'est à dire la marge d'erreur qu'il faut appliquer dépend de l'effectif de l'échantillon et pas du taux de sondage. étudier 1000 des 60 000 galéries d'A. Zysbert = étudier 1000 des 60M de français.

L'effectif total de 1000 correspond en effet à une marge d'erreur usuellement considérée comme acceptable.
Si on trouve 20% pour telle ou telle caractéristique, il y a des chances raisonnables pour que cette caractéristique dans la population entière soit comprise entre 19 et 21%, de très bonnes chances entre 18 et 22%, et une quasi-certitude entre 15 et 25%.

### Présenter des résultats en pourcentages

**Warning:** les pourcentages, proportions issues de divisions, ne peuvent pas faire l'objet de simples additions ou soustractions. De ce fait, l'expression "points" a été créée pour rendre compte d'écarts entre pourcentages. On dit donc qu'une valeur passe de 10 à 20% a augmenté de 100% ou de 10 *points*.

* On utilise en général 2 types de pourcentages. Ceux qui sont issus de **tris à plat** représentent la distribution de la population étudiée entre les modalités (les différentes valeurs) d'une variable.
IMG

* Les **tris à plat** donnent une première idée des données mais, en général, on s'intéresse plus aux **tris croisés**, qui présentent en même temps la distribution de 2 variables, donc donnent une première idée des liens, ou de l'absence de liens, entre elles. Fournir ces tris croisés en pourcentages plutôt qu'en nombres absolus permet au lecteur de se rendre compte des particularités de certaines parties de la population par rapport à l'ensemble, pour peu que l'on utilise judicieusement les pourcentages en ligne ou en colonne.

* Pour lire de tels tableaux, il faut *d'abord regarder la ligne ou la colonne qui donne le tri à plat pour toute la population*, puis y comparer *le profil* des autres lignes ou colonnes. Exemple:
IMG

C'est le repérage des cases "100%" qui nous permet de dire que le premier tableau est en *pourcentage en ligne*, le second en *pourcentage en colonne*.
* Le premier compare les profils d'activité selon la date d'entrée
* Le second les profils de date d'entrée selon l'activité

### A partir de quel écart en pourcentage peut-on se permettre un commentaire? / quand les chiffres ont-ils un sens?

Indiquer le degré de confiance à accorder aux différents chiffres présentés. Il existe des règles pour intérpréter les pourcentages en fonction des effectifs:
* Grosso modo, pour 2 groupes de 100 personnes chacun, il faut une différence de 12 à 14 points entre les pourcentages caractérisant chacun de ces groupes pour que l'on puisse se permettre de considérer ces pourcentages comme réellement différents avec certitude.
* Pour 2 groupes de 1000 personnes chacun, 4 points de différence suffisent
* Pour des groupes de 300 et 500 personnes, 7 points.

### le chi-2

Le chi-2 est un indicateur de liaison entre deux variables. Celui-ci permet de dire avec une certitude raisonnable si les différences observées dans un tableau croisé peuvent être dues au simple hasard, du fait de faibles effectifs, ou si elles renvoient à une *attraction* ou une *opposition* réelle entre les modalités de variables considérées. Attention, ces liens sont ensuite à interpréter, pas forcément lien de causalité.

Le chi-2/khi-deux/x2 est une mesure des écarts entre la situation observée et une situation imaginaire. Cette situation, appelée en général *théorique*, est celle où il n'y aurait aucun lien entre les variables considérées : elles seraient totalement indépendantes.

Le chiffre important est alors une probabilité, souvent notée *p* ou *prob*. On considère en général que cette probabilité doit être inférieure à 5% pour que l'on en conclues que les variables sont liées. CAD qu'il y a moins de 5% de risques pour que la liaison que nous avons l'impression de voir soit simplement due aux trop faibles effectifs observés.

**Warning:** le chi-deux montre ses limites pour les effectifs vraiment faibles, typiquement, quand certaines cases du tableau croisé renvoient à un effectif théorique, en situation d'indépendance, de moins de 5 cas, il faut se méfier des résultats.




