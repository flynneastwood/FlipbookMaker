# FlipbookMaker


--ENGLISH--
Python script to make a spritesheet to be used in Unreal with SubUV animation.
It creates a spritesheet of 8 columns and 8 rows for a total of 64 images.
This script is designed to work with 64 PNG images rendered as squares, power of 2.

Core of this code came from this tutorial: https://minzkraut.com/2016/11/23/making-a-simple-spritesheet-generator-in-python/

You have to get Python 3 to make it work https://www.python.org/downloads/
You need Pip installed to get the Pillow library with the command: pip install Pillow

Place your rendered sequence in the SubUV_Render
Open a Powershell in the script directory and launch the command: python .\flipbookMaker.py
The final texture will be created in the same directory.


--FRANCAIS--
Script pour faire des spritesheets/SubUV textures.
Il produit un spritesheet de 8 colonnes par 8 rangées pour un total de 64 images.
Ce code fonctionne optimalement avec 64 images en .png de format carré, puissance 2.

Le core du code vient de ce tutoriel: https://minzkraut.com/2016/11/23/making-a-simple-spritesheet-generator-in-python/

Il est nécessaire d'avoir Python 3 d'installé https://www.python.org/downloads/
Installer pip
Installer Pillow avec cette commande: pip install Pillow

Placer les images dans le dossier SubUV_Render
Ouvrir un terminal PowerShell au même endroit que le script et exécuter la commande: python .\flipbookMaker.py
La texture finale sera créer dans ce même dossier.
