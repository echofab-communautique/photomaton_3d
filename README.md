# Photomaton 3D



## Sommaire
Machine permettant de numériser une personne. Cette machine sera utilisée dans le cadre d'une activité au Centre des Sciences de Montréal, organisé par le Centre Turbine.

![untitled1](https://user-images.githubusercontent.com/65183668/84677824-8bae4880-af2f-11ea-93c0-96e182c263b7.png)



## Concept
Pour numériser un objet en 3D, il faut pouvoir avoir des prise de vue de ce même objet sous tout ses angles. Suivant cette logique, la technique populaire pour numériser, consiste à faire tourner un objet sur son axe et de prendre des photos de façon constante, en plongé et contre-plongé. Comme si l'on plaçait un objet sur un table tournante que l'on photographiait à un rythme constant.

Pour construire un photomaton 3D, nous utiliserons donc un système de table tournante (pas mal plus grosse que celle de votre grand père), une structure vertical pour fixer un ou deux Kinect (qui remplaceront les appareils photos) et un poste informatique pour traiter l'information des Kinects. La surface rotative sera tournée manuellement à l'aide d'un système d'engrenage.

Une fois le modèle généré par le logiciel Skanect, nous imprimerons le modèle avec une imprimante 3D.

La construction et le développement de ce projet est entièrement fait par l'équipe d'échoFab.



## La Kinect
La Kinect, en plus d'être un appareil photo, possède un émetteur de points et une caméra infrarouge. Les deux fonctionnent ensemble. L'émetteur envoie une grille de point infrarouge, la camera capte ces points et envoie à l'ordinateur un image comportant strictement de l'information infrarouge. Le logiciel utilisé analyse la distance entre les points de la grille pour définir //la profondeur de l'image//. Ces informations ajoutent donc une troisième dimension à l'image 2D traditionnelle. 

Il existe d'autres méthodes pour composer des modèles 3D à partir d'image 2D. Ces méthodes peuvent s'avérer plus simple mais prennent en général plus de temps. Puisque nous avons en notre possession une Kinect et le logiciel nécessaire, nous prendrons avantage de cette technologie.

## Fabrication mécanique

![untitled2](https://user-images.githubusercontent.com/65183668/84677846-95d04700-af2f-11ea-87f5-24547d76db37.png)

Système d’engrenage fait à partir d’un vieux vélo et de matériel de quincaillerie.

![untitled3](https://user-images.githubusercontent.com/65183668/84677904-a84a8080-af2f-11ea-8bea-52c421a9d252.png)

Test du système d’engrenage.
## Électronique
À venir

## Logiciel, traitement de l'image et impression
Pour créer nos modèles 3D, nous utiliserons Skanect à l'aide d'une Kinect. Skanect est un logiciel plutôt efficace pour créer des numériser des personnes/lieux/objet en peu de temps.

![untitled5](https://user-images.githubusercontent.com/65183668/84677903-a7b1ea00-af2f-11ea-831d-7d24a42f7374.png)
Reconstruction du modèle dans Skanect.

![untitled6](https://user-images.githubusercontent.com/65183668/84677902-a7195380-af2f-11ea-8380-085dc3f3681e.png)
Exemples de modèles générés par notre photomaton 3D.

## Contact et questions
Pour toutes questions en lien avec le projet, veuillez nous écrire au [[mailto:info@echofab.org|info@echofab.org]]


## Ont contribués à ce projet


  * Antoine et Yves, Centre Turbine
  * Roby Provost - Concept et conception
  * Raphaël Dermers - Électronique et Arduino et conception technique
  * Marc-Olivier Ducharme -  Conception originale et démarage du projet - Soutien technique

Si votre nom n'apparait pas n'hésitez pas à l'ajouter à la liste ou nous contacter!
