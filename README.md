 MichaelAubras_3_08112020

# Projet 3 Openclassrooms 
![2021-11-25_16h54_47](https://user-images.githubusercontent.com/91529322/143471938-a6a801e6-3001-42c0-b39a-a14fdcd4b79f.png)

## Scenario du projet

Vous venez d’être recruté chez Ohmyfood!, en tant que développeur junior. Félicitations !

Ohmyfood! est une jeune startup qui voudrait s'imposer sur le marché de la restauration. L'objectif est de développer un site 100% mobile qui répertorie les menus de restaurants gastronomiques. En plus des systèmes classiques de réservation, les clients pourront composer le menu de leur repas pour que les plats soient prêts à leur arrivée. Finis, les temps d'attente au restaurant !

# Cahier des charges

### Cible

Classes moyennes et supérieures, connectées et souvent pressées, souhaitant déguster des produits de qualité.

### Identité graphique
Polices
Logo et titres: Shrikhand
Texte: Roboto

### Couleurs de la charte graphique

![2021-11-25_17h24_05](https://user-images.githubusercontent.com/91529322/143475797-72aaf341-9de9-418f-b69e-b0bb08f5c245.png)


## Technologies:
* HTML
* CSS
* SASS
* Interdiction d'utiliser JavaScript
* Aucun framework
* Le code CSS ne doit pas être appliqué avec un attribut style dans une balise HTML
* L'intégralité du code doit être versionné sur Github

## Compatibilité

* L’ensemble du site devra être responsive sur mobile, tablette et desktop.
* Les pages devront passer la validation W3C en HTML et CSS sans erreur.
* Le site doit être parfaitement compatible avec les dernières versions desktop de
Chrome et Firefox.

# Livrables attendus

Contenu des pages

## Page d’accueil (x1)

* Affichage de la localisation des restaurants. À terme il sera possible de choisir sa
localisation pour trouver des restaurants proches d’un certain lieu.
* Une courte présentation de l’entreprise.
* Une section contenant les 4 menus sous forme cartes. Au clic sur la carte,
l’utilisateur est redirigé vers la page du menu.

## Pages de menu (x4)

* 4 pages contenant chacune le menu d’un restaurant.

## Footer

* Le footer est identique sur toutes les pages.
* Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

## Header

* Le header est présent sur toutes les pages.
* Sur la page d’accueil, il contient le logo du site.
* Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil.

# Effets graphique et animations 

Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils devront utiliser
les animations ou transitions CSS, pas de JavaScript ni de librairie.

## Boutons 

* Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir.
L’ombre portée devra également être plus visible.
* À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un
bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se
remplir progressivement. Pour cette première version, l’effet peut être apparaître au
survol sur desktop au lieu du clic.

## Pages d'accueil

* Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur
cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à
3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et
utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini,
toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte
graphique du site.

## Pages de menu

* À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger
décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe
“Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.
*  Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus.
Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de
la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol
sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec
des points de suspension. Un exemple de l’effet attendu est fourni.
