# Bonus_management_app


# INTRODUCTION
Qt est un cadre de développement d'applications multiplateforme pour les ordinateurs de bureau,
embarqués et mobiles. Les plates-formes prises en charge incluent Linux, OS X, Windows, VxWorks,
QNX, Android, iOS, BlackBerry, Sailfish OS et autres. Qt n'est pas un langage de programmation en soi.
C'est un framework écrit en C++. Un préprocesseur, le MOC (Meta-Object Compiler), est utilisé pour
étendre le langage C++ avec des fonctionnalités comme les signaux et les slots. Avant l'étape de
compilation, le MOC analyse les fichiers source écrits en C++ étendu Qt et génère à partir de ceux-ci
des sources C++ conformes aux standards. Ainsi, le framework lui-même et les
applications/bibliothèques qui l'utilisent peuvent être compilés par n'importe quel compilateur C++
conforme à la norme comme Clang, GCC, ICC, MinGW et MSVC.

  
 
● Show : ce boutton est résponsable de vous lancer vers le tableau globale d’un groupe (A,B ou
C ) après avoir choisi un groupe et fuseau horaire
● ShowTOTAL : permit de géner un dossier résultat et vider tout les fichiers du dossier en-cours
:
  
 
qui contient :
Le fichier TOTAL c’est un fichier de nom variable c-â-d que le nom du fichier port la date où le
boutton <<showTOTAL>> est cliqué , dans ce fichier se trouve tout les employées avec leurs
prime final :
  
 
Ce tableau contient 120 lignes
Les dossiers A,B et C ont une structure identique c-â-d tout le traitement effectuer sur A est
le même pour B et C :
le fichier Test contient principalment 2 choses :
1) des feuils s’appellent <Sheet ¨i¨ > il y a 40 sheet chaque sheet represente les details
d’un employé dans une periode d’un mois complé avec son groupe specifier en haut du
tableau aussi la date de dérnière modification et son matricule et nom et prenom ,
le numero represente son numero dans le tableau global :
  
 
2) le tableau global comporte la ligne Total de tout les employés en sommant la prime de
chaque joues il contient au maximum 40 employés :
  
 
Comme on les colones document et réclamation comme des sous tableau , j’ai descidé de
les mettre dans des fichires excels séparé només < document > et <réclamation> aussi
ils contiennent 60 lignes maximum :
  
 
C’est le table de document
  
 
c’est le table de réclamation
● le dossier <en-cours> où le traitement vraiment s’effectue , ce a la même structure du
dossier résultat + 2 fichers auxicillaire ,il contient le fichier <TOTAL> , où se trouve la somme
totale des prime du mois , le fichier <dbprime >, la base données de chaque employés et la
prime qui peut toucher par mois , le <S> , où il y a les matricule avec les nom et prenom de
tout les employés de tout les groupes (c’est pour vérifier les employés ajouter dans le
système ), et les dossiers des groups A,B et C et chaque dossiers contient les fichiers
document , réclamation et Test :
  
 
Deusième page :
Cette page afficher le contenu de la feuil <Global> du fichier Test il contient la somme des
primes d’un mois aussi la somme des cértificat médical , les jours fiéries , les congés ou
autorisation , réclamation ,documents et les heurs sup de 15 min .
● retour : permet de revenir à la page précédente
● show réclamation : affiche le contenu d’une feuil specifique du fichier réclamation après
avoir séléctionner l’employé specifique
● show document : fais le même traitement de < show réclamation >
● add : vous permet d’ajouter un employé dans la liste des primes
● edit : vous permet de modifier la matricule et le nom d’un employé existant dans la liste
● detail : affiche les details d’un employé spécifique après le séléctionner
troisième page :
  
 
Cette page affiche le contenu des feuils Sheet dans le fichier Test :
  
 
● numero : c’est le numero de l’employé dans la liste des primes
● mois : c’est le mois –jour courant
● show : pour revenir à la page précédente vers la liste des employés
● add : pour ajouter un autre jour de travail de l’employé
● edit : pour modifier les données d’un employé existant dans ce tableau
● delete : permet de rendre le linge selectione null
● show réclamation : affiche la liste des réclamation d’un jour selectionne :
  
 
add : permet ajouter une réclamation à l’employé séléctionné
Cancel : pour revenir à la liste des réclamation sans ajout
add : confirme la modification
  
 
edit :effectue la modification sur une réclamation :
Cancel : pour revenir à la liste des réclamation sans modification
Edit : confirme la modification
Delete : suprime la réclamation séléctionnée
  
 
Show document : fais le même traitement que <show réclamaton>
● add : permet d’ajouter un jour de travail :
  
 
● edit : permet de modifier des informatiion d’un jour existant dans la table :
● delete : permet d’annuler un jour :
  
 
● stop : permet d’arrêter l’insertion des nouveau lignes dans le tableau pour recommencer il
faut just la cliqué de nouveau :
● jump : permet de sauter vers un jour spéficier dans la zone du text (dans l’exemple j’ai
specifier 10 ):
  
 
