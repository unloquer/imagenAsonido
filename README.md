imagenAsonido
=============

sonorizar imágen

sonificar esta imágen:

<img src="http://jardincosmico.net/sound/unloquer/IMG_5367.jpg" with=320 height=240>

* cambiar la extensión de la imágen a .raw

usando sox 

 >  sox -r 48000 -b 16 -e unsigned-integer IMG_5367.raw   image.ogg
 
 [Explicación de ese comando aquí](http://explainshell.com/explain?cmd=sox+-r+48000+-b+16+-e+unsigned-integer+IMG_5367.raw+image.ogg+)
 
 atenuando para no reventar los parlantes
 
 >  sox image.ogg image_at.ogg gain -6

