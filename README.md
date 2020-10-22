# ARBattle

## Jeudi 24 septembre
Présents : Iris, Clémence, Nathan, Léo.

Pendant la séance :
- Choix du projet
- Ciblage de technologies potentiellement intéressantes pour l’AR : AR.js et ARcore

test de AR.js :
Tutorial : https://github.com/AR-js-org/AR.js
Fonctionne moyennement avec la démo fournie par AR.js sur leur github. De mauvaise augure. 
Pour la méthode de détection, il semble avoir peu de liberté, c’est NFt Market creator qui semble préconisé. 
Pour les animations Blender ou A-frame semblent être ceux qui sont recommandé par AR.js 
D’ici la semaine prochaine tester non pas avec un serveur en ligne mais avec un serveur local afin de voir si on gagne en rapidité / fluidité.

test de ARCore.js : 
Installation pas facile.

Objectifs de la séance 2 :
- Être fixé sur les technologies.
- Si on ne trouve pas de librairies de reconnaissance d’image intégrées facilement applicable aux cartes, creuser ce modèle de machine learning codé en python. 


## Jeudi 1er octobre
Présents : Iris, Clémence, Nathan, Léo.

Pendant la séance :
- Création repo Github
- Diapo de présentation sur le drive
- Prise en main de AR.js 
- Prise en main de ARcore
- Choix de modèles 3D
- Tests sur Android d'exemples existants

Bilan :
- les deux outils d'AR sont intéressants et ont des avantages/inconvénients. L'objectif est de bien comprendre leur fonctionnement pour coder notre application sur le plus adapté.
- il existe beaucoup de modèles 3D en ligne et gratuits. Pour notre jeu, on pourrait faire deux sets de modèles, un pour les cartes rouges, un autre pour les noires.
- Pour AR.js version repertoire glitch https://glitch.com/edit/#!/join/2cd0009d-a790-4cbe-9b85-4c1b30a3bbd0
- Si AR.js ou ARCore.js trop galère, il existe Vuforia un plug-in Unity pour faire de l’AR

A venir :
- Essais sur les cartes
- Codage des différents marqueurs de AR (en AR.js)
- Codage de différents modèles 3D(en AR.js)
- Création de scène avec modèle 3D (en ARcore)

## Jeudi 8 octobre
Présents : Iris, Clémence, Nathan, Léo.

Pendant la séance :
  - AR.js : on arrive à importer un modèle 3D custom, et à utiliser un marker custom : https://learn.framevr.io/project1/part3
  - problème : les markers sont assez limités et ne permettent pas de reconnaître une grande variété d'images
  - Reconnaissance des cartes : Etat de l'art + Test d'un classifieur déjà entrainé https://github.com/EdjeElectronics/TensorFlow-Object-Detection-API-Tutorial-Train-Multiple-Objects-Windows-10
  - Glitch : brouillon sur https://glitch.com/edit/#!/ar-battle-nancy?path=index.html%3A4%3A8
             version d'Iris fonctionelle : 
  - ARcore: introduction de personnages 3D personnalisés             
             
Bilan :
  - on continue sur AR.js
  
  
A venir :
  - on essaie de remplacer les markers de AR.js par des NFT marker (https://www.kalwaltart.com/blog/2020/02/25/tutorial-create-marker-nft/)
  - Finir le tuto d'installation pour la reconnaissance de cartes puis l'essayer

## Jeudi 22 octobre
Présents : Iris, Clémence, Nathan, Léo.

Pendant la séance :
  - Pseudo code règles du jeu (Iris)
  - NFT markers (Léo)
  - Détection de cartes (Nat)
  - Intégration perso 3D au jeu (Clem)
             
Bilan :
  - NFT markers ne fonctionnent pas, problème de Cross Origin Content
  - L'application AR core commence à fonctionner ! Hourra. Bon maintenant je commence à construire une base de données d'images qui seront reconnnues par l'application et qui permettent l'affichage d'objets 3d au choix ensuite. Voilà comment construire la BDD : https://developers.google.com/ar/develop/c/augmented-images/arcoreimg . 
  
  
A venir :
  - On met toutes les forces vives sur AR core car c'est ce qui est le plus prometteur 
  - Faire le Augmented Images a partir de ce site https://developers.google.com/ar/develop/java/augmented-images/guide
