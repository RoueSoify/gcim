# gcim
C'est mon projet de poster
Le but était simplement de "créer" un format d'image.
Bien qu'il ne soit lisible que par ces deux exes, le format est simple en soi et ne devrait pas être si dur à dévelloper en extension GIMP (exemple).
Cela dépasserai toute fois mes connaissances, je ne saurais pas le faire.

Le fichier est composé d'un header d'un ligne donnat les dimensions d'une image (largeur puis hauteur) et le nombre de channels de couleur (normalement vous resterez sur 2, 3 ou 4)
Le reste du fichier est simplement une liste de lignes de pixels et le Decompress.exe se chargera automatiquement de les attribuer à leur ligne.

Pour faire fonctionner, lancez simplement le fichier Compress.exe puis sélectionnez une image.
Pour la décrompresser, lancez simplement Decrompress.exe et sélectionnez un .gcim. Mais attention, le fichier qui vous sera retourné sera toujours un .png.
