
# ohmyfood

L'objectif dans ce projet est de dynamiser des pages web en utilisant le préprocesseur SASS.

## Documentation

Vous pouvez retrouver le brief technique [ici](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/DW_P3/Brief%20cre%CC%81atif%20-%20Ohmyfood!.pdf).

## Livrables

Le projet est conçu en mobile-first. Pour cette raison, seules les maquettes mobiles seront réalisées.

### Objectif :

    - Phase 1 : Développer un site proposant le menu de 4 grands restaurants parisiens.
    - Phase 2 : Permettre la réservation en ligne et la composition de menus.

### Maquettes :

    - Une page d'accueil
    - Page de menu (x4)

![capture_ohmyfood](https://user-images.githubusercontent.com/40861838/123613491-c239c700-d803-11eb-8e87-687513acde03.JPG)

![Accueil](https://user-images.githubusercontent.com/40861838/123613643-e5fd0d00-d803-11eb-9e11-3c3a7c78c220.png)

### Animation :

#### Bouton :
- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir.
L’ombre portée devra également être plus visible.
- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un
bouton "J’aime" en forme de coeur est présent sur la maquette. Au clic, il devra se
remplir progressivement. Pour cette première version, l’effet peut être apparaître au
survol sur desktop au lieu du clic.
Page d’accueil
- Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur
cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à
3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et
utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini,
toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte
graphique du site.

#### Pages de menu :

- À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger
décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe
“Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.
- Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus.
Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de
la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol
sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec
des points de suspension. Un exemple de l’effet attendu est fourni.
## Hebergement

Le site est hébergé sur Github Pages vers ce [lien](https://dimitrilory44.github.io/DimitriLory_3_18062021/index.html).