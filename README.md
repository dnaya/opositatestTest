Al tratarse de una landing page he tratado de evitar la fuga de usuarios hacia otros apartados
dejando que se centren en el contenido/objetivo de la página. Por este motivo es por el que he 
quitado todos los enlaces de la barra de menu hacia otras partes de nuestra página princpial. 
Lo mismo he hecho con los enlaces del pie de página. Quedando únicamente los enlaces a las aplicaciones
de IOS y Android (ya que si que es relevante que el usuario las descargue) y el apartado de CONTACTO, ya que al contactar con nuestro equipo también tendría que proporcionar sus datos.

Para reforzar la imagen de marca y tratar de convencer al usuario de que nuestros servicios le 
podrán ayudar, se ha incorporado un apartado con opiniones de otros usuarios, ya que esto le suele 
proporcionar realismo a los productos.

Se ha primado que el contenido de la página se vea correctamente en todas las resoluciones.
(En el caso de no quitar secciones de la barra de menu habría cambiar su estilo, ya que hay muchas resoluciones en las que el comportamiento no es correcto).
Las imagenes del Logo y de las Apps se han modificado para emplear una única imagen, además sobretodo en el caso del logo no tenía sentido cargar una imagen tan grande y después redimensionarla con css.

Para el empaquetado de la aplicación he tratado de utilizar Parcel.js
pero al no disponer de todos los recursos referenciados en el código, como otras imagenes que en este apartado no se emplean pero si estan sus rutas en archivos .css, da conflictos y no se puede empaquetar correctamente. Sería muy interesante poder emplearlo ya que podría ayudar a reducir considerablemente el proceso de carga. 
Además me ha quedado por revisar todos los archivos css y js que se están referenciando, ya que muy posiblemente no sean todos necesarios en esta landing.

Por otro lado la página da un error al tratar de cargar el fichero uwt.js, se ha comentando el código de Google Tag Manager para que no trate de referenciarlo, ya que en localhost no es necesario, habría que comprobar si en producción se da el mismo problema al tratar de cargar el fichero de Twitter, para intentar solucionarlo en ese caso 

