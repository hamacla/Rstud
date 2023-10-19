Voici les étapes à suivre pour pouvoir compiler votre rapport

1. Installer le logiciel R (si vous l'aviez déjà installé,
   faites une mise à jour).

2. Installer le logiciel RStudio (si vous l'aviez déjà installé,
   faites une mise à jour).

3. Lancer RStudio et installer le paquet R tinytex
   Menu Tools
     -> Install Packages...

4. Dans la console R (en bas à gauche) entrer les commandes :

     library(tinytex)
     tinytex::install_tinytex()
     
5. Quitter RStudio

6. Lancer RStudio, ouvrir le fichier minitex.tex

7. Cliquer sur l'icone "Compile PDF", vous devez obtenir le
   document minitex.pdf (Bonjour Ô Mon∂e) identique
   au document minitexAttendu.pdf
   
   Si problème, ne pas passer à l'étape suivante tant
   qu'il n'est pas résolu.

8. Ouvrez le fichier BIO3164L.Rmd

9. Enregistrez-le sous "NomPrenom.Rmd", sans caractères
   spéciaux dans "NomPrenom", par exemple pour Stéphanie Von
   Haÿ-les-Roses : VonHayLesRosesStephanie.Rmd.
   
   Menu File
     -> Save as...  (rester dans le dossier BIO3164)

10. Indiquez à R que votre dossier de travail est celui
    qui contient votre fichier *.Rmd
    
    Menu Session
      -> Set Working directory 
          -> To source file location

11. Cliquer sur l'icone "Knit", vous devez obtenir le
    document NomPrenom.pdf, quasiment identique à
    BIO3164L.pdf (vous n'avez plus de message d'alerte
    à la fin du résumé comme quoi le document n'a pas
    été renomé).
