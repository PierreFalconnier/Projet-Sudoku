README.txt


main_sudoku_rasp_bouton :
Pour lancer le système sur la Raspberry.

detection_grille_rasp :
Script de traitement d'image utilisé sur la raspberry
Il utilise tflite. Utilisable sur PC si tflite installé

detection_grille :
Script de traitement d'image utilisé sur PC
Il utilise keras (tensorflow).

Reconnaissance_chiffres et Reconnaissance_orientation
Scripts d'entrainement des modèles

test_bouton et test_camera :
Scripts pour réaliser des test sur rapsberry

resolution_sudoku :
Script de résolution à partir de la matrice de la grille

TracerChiffres :
Communication avec la carte Arduino 

ObtenirCourbesChiffres :
Définition des courbes des chiffres


Versions sur Raspberry :

Python - 3.9.2
tflite-runtime==2.5.0.post1
numpy==1.22.3
RPi.GPIO==0.7.0
open-cv - 4.5.5


