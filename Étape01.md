# :one: Étape 01 

L’étape 01 du workshop correspond à la collecte des contenus:

> ### Cette archive en ligne s’articulera autour du thème suivant: exploration visuelle des gestes, des habitudes et des outils de l’interaction homme-machine.

Du passé au présent, du présent au futur. Cette archive aura pour objectif de rendre hommage aux anciens outils d’interactions, aux créations visionnaires et à la diversité des interactions imaginées dans l'histoire. Dans un environnement numérique centré sur le développement du tactile et du « mobile first », cette recherche adoptera un caractère anthropologique. Cette archive devra se constituer d’images, vidéos et documents iconographiques divers qui sont preuves claires et directes de l’interaction entre l’homme et l’ordinateur à travers le temps. Chaque groupe devra trouver une thématique comme angle de recherche et élaborer une petite collection de 5 à 20 items pour mettre en évidence des chemins d’évolutions, des modèles communs et une perception historique.

--------------

#### Table des matières 
1. [Programme](https://github.com/domitille-f451/workshop-penser-classer/blob/main/%C3%89tape01.md#date--programme)  
2. [Instructions](https://github.com/domitille-f451/workshop-penser-classer/blob/main/%C3%89tape01.md#memo--instructions)  
3. [Guideline technique](https://github.com/domitille-f451/workshop-penser-classer/blob/main/%C3%89tape01.md#computer--guideline-technique)
4. [Utilisation de GitHub](https://github.com/domitille-f451/workshop-penser-classer/blob/main/%C3%89tape01.md#wrench--utilisation-de-github)

--------------

### :date:  Programme

* #### Lundi 14
  * 09:00 - 10:30 — Présentation (Amphitéâtre)
  * 10:30 - 10:45 — Pause :coffee:
  * 10:45 - 12:30 — Introduction du Workshop (Amphitéâtre)
  * 12:30 - 13:30 — Pause :fork_and_knife:
  * 13:30 - 17:00 — Formation des groupes et recherches thématiques 

* #### Mardi 15
  * 09:00 - 12:30 — Collecte et rédaction des thématiques
  * 12:30 - 13:30 — Pause :fork_and_knife:
  * 12:30 - 16:30 — Collecte et rédaction des thématiques 
  * 16:30 - 17:00 — Déposez vos fichiers finaux dans votre repo

-----------------

### :memo:  Instructions

1. Former des groupes de 1 à 5 personne(s) 
2. Choisir une thématique qui représente un caractère historique, expérimental, étrange, prospectif… Il ne s’agit pas de collecter au maximum mais de trouver du contenu qui est pertinent dans la constitution d’une archive. (exemples de thèmes: L’âge d’or d’IBM, les tutoriels d’utilisation, les périphériques d’entrée à l’usage des personnes en situation de handicap…)
3. Le type de contenu est iconographique mais peut-être divers en termes de supports proposés: illustrations, publicités, didacticiels, extraits de films, photographies, œuvres… 
4. Chaque thème devra constitué une collection de 5 à 20 items soigneusement choisis pour leur pertinence, ainsi qu’un texte descriptif d’environ 600 caractères
5. L’utilisateur et l’outil doivent être présents dans l’objet iconographique. 

Site de départ des recherches:  
+ [https://en.wikipedia.org/wiki/Input_device](https://en.wikipedia.org/wiki/Input_device)  
+ [https://www.vintagecomputing.com/](https://www.vintagecomputing.com/)  
+ [https://www.dougengelbart.org/content/view/162/000/](https://www.dougengelbart.org/content/view/162/000/)  
+ [https://scifiinterfaces.com/](https://scifiinterfaces.com/)  
+ [http://oldcomputers.net/indexwp.html](http://oldcomputers.net/indexwp.html)  

--------------

### :computer:  Guideline technique 

La collecte s’effectuera de manière collective dans ce [tableur](https://docs.google.com/spreadsheets/d/1w9vFQPzr-pXHelSkZ2MjnzVrU2LndFCdSlxtCBIexNY/edit?usp=sharing) et ici sur Github. 
> cf. 2 premières lignes du tableur pour exemple 

1. Chaque groupe/étudiant devra créer une nouvelle feuille avec le nom de son thème et reprendre exactement la même structure que la feuille 1.
2. Chaque groupe/étudiant se verra donner un dossier dans le repo Github avec le nom de son thème et y déposera les images en suivant la nomclature imposée.
3. Les images devront être renommées et suivre une nomenclature précise qui devra correspondre à celle indiquée dans le tableau.
```
Ex: img0301.jpg  
       03: Numéro du groupe  
         01:  Numéro de l’image
```                  
4. Les vidéos doivent provenir de sources en ligne et le lien devra comporter le temps de début de l’information d’intérêts (par exemple, sur YouTube: bouton partager, puis cocher démarrer à:--:-- / sur Vimeo: bouton partages, sélectionner le lien, puis cocher: Commencer la vidéo à --:--). Les items vidéo devront être accompagnés d’une capture d’écran qui suit la même nomenclature que les images.
5. Mardi soir, votre feuille de tableur devra être exporté au format .csv et déposée dans votre dossier sur le repo Github. Depuis Google Sheets, `Fichier > Télécharger > valeurs séparées par des virgules [.csv, feuille active]`

--------------

### :wrench: Utilisation de Github

Comme expliqué plus haut, nous allons nous servir de Github pour récolter l’ensemble des images de tous les groupes. Voilà la démarche à suivre:

1. Un membre de chaque groupe se crée un compte sur Github (si possible un membre qui possède un Mac, pardon aux amateurs de Windows)
2. Une fois que votre compte est créé, ouvrir le Terminal de votre ordinateur! Vous voilà réellement développeur désormais!
3. Écrire cette première commande pour vérifier que Git est bien installé sur votre ordinateur :
```
git --version
```
4. Si vous obtenez quelque chose de ce type `git version 2.24.3 (Apple Git-128)`, tout est bon! Sinon, on va vous aidez pour la suite.
5. À partir de là, il vous faut copier en local le repo en ligne. Entrez la commande qui suit :
```
cd Desktop
git clone https://github.com/f451-faith/workshop-penser-classer.git
cd workshop-penser-classer
```
6. Vous devriez désormais avoir un dossier sur votre bureau nommé `workshop-penser-classer`. Il s'agit du même dossier que celui sur lequel vous êtes actuellement sur GitHub.
7. Vous pouvez maintenant ajouter vos images dans le dossier de votre groupe du dossier `01-collecte`.
8. Vous devez maintenant faire cette manipulation sur votre Terminal en n’oubliant pas de changer le numéro de votre groupe ligne 3 :
```
git pull origin main
git add *
git commit -m "Update des images du groupe ##"
git push origin main 
```
Pour expliquer rapidement ce que vous faites grâce à ces quatre lignes:
+ `git pull origin main` vous permet de mettre à jour votre dossier en local avec les données en ligne et donc récupérer les données des autres. C'est important afin de ne pas créer de conflit entre les fichiers
+ `git add *` vous permet d’indiquer les fichiers que vous souhaitez ajouter au repo en ligne. Ici, `*` indique que vous ajouter l’ensemble des fichiers du dossier.
+ `git commit -m "Update des images du groupe ##"` vous permet d’ajouter un message qui décrit la manipulation en cours.
+ `git push origin main` uploade l’ensemble des données sur le repo en ligne.
9. Vous pouvez répéter cette manipulation à chaque fois que vous souhaitez uploader de nouvelles images en ligne!

--------------
