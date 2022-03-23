# FlipbookMaker


--ENGLISH--
Python script to make a spritesheet to be used in Unreal with SubUV animation.
It creates a spritesheet of 8 columns and 8 rows for a total of 64 images.
This script is designed to work with 64 PNG images rendered as squares, power of 2.
Final image is 512 by 512.

Core of this code came from this tutorial: https://minzkraut.com/2016/11/23/making-a-simple-spritesheet-generator-in-python/

You have to get Python 3 to make it work https://www.python.org/downloads/ or available through the Microsoft Store.

To install the following requirements, use the terminal. 
You need Pip installed with the command: py -m ensurepip --upgrade 
You also need the Pillow library. install it with the command: pip install Pillow

Place your rendered sequence in a folder called SubUV_Render
Open a terminal in the script directory and launch the command: python .\flipbookMaker.py
The final texture will be created in the same directory.


--FRANCAIS--
Script pour faire des spritesheets/SubUV textures.
Il produit un spritesheet de 8 colonnes par 8 rangées pour un total de 64 images.
Ce code fonctionne optimalement avec 64 images en .png de format carré, puissance 2.
L'image finale sera de 512 par 512.

Le noyau du code vient de ce tutoriel: https://minzkraut.com/2016/11/23/making-a-simple-spritesheet-generator-in-python/

Il est nécessaire d'avoir Python 3 d'installé https://www.python.org/downloads/ ou disponible depuis le Microsoft Store.

Pour installer les modules suivants, utilisez le terminal.
Installer pip avec la commande: py -m ensurepip --upgrade
Installer Pillow avec la commande: pip install Pillow

Placer les images dans le dossier SubUV_Render
Ouvrir un terminal au même endroit que le script et exécuter la commande: python .\flipbookMaker.py
La texture finale sera créer dans ce même dossier.
