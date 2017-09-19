NIVEAU 1
Crée un script shell nommée “ex01.sh” qui réalise les actions suivantes:

1) Crée un nouveau répertoire appelé “src”
2) Télécharge le document dans le répertoire src sur:
“ https://docs.google.com/uc?export=download&id=0Bx-PGwLU7KF7RFc0S0xYdjNFUEE” et le nomme “library.xml” (il va falloir utiliser les options -L et -o de curl, à vous de voir comment les utiliser)
3) Fait tourner le script shell “ex02.sh”


NIVEAU 2

Crée un script shell nommé “ex02.sh” qui s’exécute comme suit: 

1) Affiche le nombre de chansons présentes dans library.xml
2) Affiche le nombre de chansons de Manu Chao présentes dans library.xml
3) Sauvegarde le nom de chaque chanson (seulement le nom de la chanson qui apparaît dans: <key>Name</key>row) avec .mp3 ajouter à la fin du nom de la piste dans le fichier output.txt


NIVEAU 3 (Facultatif)

Créez un script shell nommée “challenge.sh” pour effectuer soit une soit toutes les tâches ci-dessous:  

1)Trouver le nom de chaque chanson sortie depuis 2010 dans un dossier nommé challenge01.txt
2) Trouver la chanson la plus écouté et sauvegarder le nom et le nombre d’écoute dans un ficher nommé challenge02.txt dans le format [nom] [nombre d’écoute]
3) Trouver le top dix des chansons les plus écoutées et les sauvegarder dans un ficher nommé challenge03.txt
4) Trouver la longueur (temps total) de la plus longue chanson et la sauvegarder dans challenge04.txt dans le format minutes:seconds
5) Générer une playlist avec une chanson de chaque genre unique dans library.xml et le sauvegarder en tant que challenge05.txt
