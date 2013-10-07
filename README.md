imagenAsonido
=============


sonificar esta imagen:

<img src="http://jardincosmico.net/sound/unloquer/IMG_5367.jpg" with=320 height=240>

* cambiar la extensión de la imagen de .jpg a .raw

* usando sox abrimos la imagen inventando atributos de audio y la grabamos en image.ogg:

 >  sox -r 48000 -b 16 -e unsigned-integer IMG_5367.raw   image.ogg
 
 [Explicación de ese comando aquí](http://explainshell.com/explain?cmd=sox+-r+48000+-b+16+-e+unsigned-integer+IMG_5367.raw+image.ogg+)
 
 * Para atenuar un poco la ganancia (volumen) usamos:
 
 >  sox image.ogg image_at.ogg gain -6
 
 
[Escuchar aquí](http://jardincosmico.net/sound/unloquer/image_at.ogg)
