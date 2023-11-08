Lilly (Philippine) Burtin

Les Sélecteurs complexes :




all.css :
Ligne 22 : J'ai sélectionné l'ensemble des stickers Gollum à l'aide une class afin d'indiquer la taille, le positionnement (absolute afin qu'il ne bouge pas de sa position par rapport aux autres éléments) ainsi que le bottom pour le placer sur l'axe vertical.

Ligne 27 : J'ai utilisé l'id d'un sticker spécifique et ai modifié son placement horizontal afin qu'il soit à droite.

Ligne 30 : La class "haut" a été appliquée à toutes mes images d'en-tête. Cette selection me permet d'agir sur sa taille, son placement dans la page et par rapport aux autres éléments de ce bloc.

Ligne 60 : Ce sélecteur me permets d'agir sur les éléments qui constituent ma nav. J'ai ainsi pu les espacer, choisir la couleur du texte, la taille et retirer les paramètres par défaut d'un lien.

Ligne 68 : Au survol des éléments de ma nav (voir ligne 60), le fond change de couleur pour indiquer à l'utilisateur qu'il s'agit d'un lien cliquable.

Ligne 78 : Ici, j'ai simplement appliqué une bordure à toutes les images qui constituent mon bloc "main".

Ligne 94 : J'ai retiré les paramètres par défaut d'un lien et stylisé la couleur et la taille.

Ligne 100 : Au survol de mon lien (voir ligne 94) j'ai ajouté un soulignage pour indiquer à l'utilisateur qu'il s'agit d'un lien actif.

Ligne 113 : Ici, j'ai retiré les puces de ma liste.

Ligne 117 : J'ai appliqué aux composants de ma liste une couleur tout en retirant les paramètres par défaut qui constituent un lien.

Ligne 122 : J'ai rajouté une action de soulignage pour indiquer à l'utilisateur qu'il s'agit d'un lien cliquable.




index.css :
Ligne 12 : J'ai appliqué à mon sticker un ID afin de pouvoir lui appliquer une animation (voir rubrique Transitions). L'ID me permet de ne l'appliquer qu'à lui seul.

Ligne 22 : Ici, la balise "tete" m'a permis de décomposer la partie supérieure de celle inférieure de mon body. Ainsi, je n'agis que sur l'image de l'auteur. J'aurais également pu utiliser la fonction "nth:first-child".

Ligne 33 : J'ai voulu centré les titres qui correspondent aux affiches de films/séries présentés.

Ligne 44 : En spécifiant une class "corps" j'ai pu me détacher des paramètres concernant la présentation de l'auteur pour n'appliquer les effets que sur les affiches de films/séries. J'ai donc paramétré la taille et l'arrondis du bord.

Ligne 49 : Au survol des images (voir ligne 44) j'ai créé un effet d'agrandissement pour ajouter un aspect dynamique à mon site.




pages.css :
Lignes 16, 32, 44 : J'ai appliqué un ID à mes stickers pour pouvoir lui appliquer l'animation de mon choix (voir rubrique Transitions). J'ai également utilisé le système d'ID pour chacune de mes pages mais cela n'était pas nécessaire (je préférais m'assurer que cela s'applique bien à la page désirée).

Ligne 61 : Cette balise me permet d'agir uniquement sur les images paysages. J'ai ajouté un bord légèrement arrondis, un filtre sépia et indiqué une taille en pourcentage afin qu'elle s'adapte à la taille du bloc parent, qui lui s'adapte à la taille de ma page navigateur. J'ai également rajouté une marge en bas de chaque image afin que ce soit plus esthétique et agréable à regarder.

Ligne 68 : Au survol des images (voir ligne 61), ces dernières s'agrandissent et le filtre sépia disparaît pour laisser apparaître la couleur. Cela rend le site plus dynamique et fait intervenir l'utilisateur.

Ligne 86 : Pour les images qui présentent un personnage, j'ai appliqué une bordurde d'une autre couleur que celles utilisées sur mes précédentes images.

Ligne 90 : J'ai centré mon texte dans un but de lisibilité pour l'utilisateur.

Ligne 106 : Ici, j'agis uniquement sur les cellules qui composent mon tableau. J'ai agrandis les bordures, appliqué une couleur de bordure, modifié la marge intérieure (le padding) par soucis de lisibilité, ajouté une couleur de fond et appliqué une couleur de texte, que j'ai centré afin que le contenu soit bien espacé et donc lisible.

Ligne 116 : Ayant une cellule vide, j'ai simplement précisé que celle-ci devait être sans bordure et sans couleur de fond.




Les Médias Queries :




all.css :
Ligne 126 : Cette média querie est faite pour le format tablette. J'ai juste retravaillé les longueurs de mon corps et de mes paragraphes pour que la visibilité reste la même. J'ai centré le tout dans ma balise main afin qu'il n'y ai pas de débordement hors page.

Ligne 141 : Ici, j'ai appliqué la même stratégie que pour le format tablette (voir ligne 126) mais pour le format mobile.




index.css :
Ligne 62 : Format tablette. j'ai retiré ma map car moins ergonomique pour un écran qui n'utilise quasiment jamais de curseur. J'ai également retiré mon sticker Gollum pour éviter qu'il n'entre en conflit avec mes autres élements.

Ligne 71 : Même chose que pour la tablette mais version mobile.




pages.css :
Ligne 121 : Pour le format tablette, j'ai retiré mes stickers pour qu'ils n'entrent pas en conflit avec les autres éléments. J'ai également retiré les filtres de mes images car la tablette n'utilisant quasiment jamais de curseur, l'utilisateur dispose directement de l'image colorée sans avoir à intervenir.

Ligne 136 : Même chose que pour la tablette mais version mobile.




Les Transitions :



all.css :
Aucune transition n'a été utilisée dans cette feuille de style




index.css :
Ligne 1 : J'ai utilisé la fonction "keyframe" pour créer une animation de balancier. Je l'ai ensuite appliquée à mon sticker (voir rubrique Sélecteurs Complexes, ligne 12).

Ligne 49 : J'ai appliqué un délai de transition pour le grossissement de mon image, afin que l'effet soit fluide.




pages.css:
Ligne 7 : J'ai créé une animation de déplacement de gauche à droite que j'ai ensuite appliqué sur mon sticker (voir rubrique Sélecteurs Complexes, lignes 16,32, 44). J'ai également appliqué la fonction "ease-in-out" ainsi qu'un timer de 7 secondes pour qu'il y ai un effet d'accélération et de décélération, ce qui rend le rendu plus "naturel" et fluide.

Ligne 20 : Ici, j'ai créé une animation de grossissement progressif pour l'appliquer à mon sticker (voir rubrique Sélecteurs Complexes, lignes 16,32, 44). J'ai ensuite utilisé les mêmes fonctions que pour l'animation de déplacement de gauche à droite.

Ligne 36 : Initialement, je voulais créer une animation de déplacement de droite à gauche mais j'ai dû faire une erreur car mon sticker (voir rubrique Sélecteurs Complexes, lignes 16,32, 44) ne se déplace pas sur toute la longueur de la page. Toutefois, je trouvais amusant de le voir disparaître et réapparaître alors je l'ai laissé tel quel. Du reste, j'ai appliqué les mêmes fonctions que pour les deux autres animations ci-dessus.

Ligne 68 : Ici, j'ai créé une transition de grossissement qui retire le filtre sépia. J'ai également appliqué un délai de transition par soucis de fluidité.

