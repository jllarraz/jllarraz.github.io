# Media Server

Esta aplicación le permite compartir el contenido multimedia (fotos / música / videos) de su dispositivo Android con cualquier cliente UPnP / DLNA, como por ejemplo una Smart TV o Play Station 3 o Xbox 360.

https://www.youtube.com/watch?v=47rQSMHETz8

Algunas cosas acerca de la aplicación, sólo para evitar quejas:
-La aplicación sólo puede ver los archivos multimedia que la galería Android puede ver (excepto los archivos avi), si se agrega un video y no se muestra en la galería no esperes que el servidor pueda verlo.
Lo he probado con: "mkv", "avi", "mp4"
-Con algunos routers, especialmente aquellos que son baratos o viejo, si sufres una gran cantidad de desconexiones, es debido a que el router está saturado y no puede manejar todos los datos, esto es un problema especialmente con el vídeo.
-Si estás conectado al Wi-Fi y su cliente no puede ver el servidor, el problema está en el router en el 90% de los casos (ver configuración UPNP o actualizarlo).
-Por favor, lea la Ayuda.

La versión Pro no esta limitada en modo alguno, aunque se recomienda que primero pruebe la aplicación gratuita para ver si el teléfono funciona bien con el cliente que desee.

Versión Pro tiene las siguientes funciones:
-Firewall integrado(Seleccione los dispositivos que pueden acceder a su contenido multimedia)
-Selección de archivos individuales (Usted puede elegir lo que va a compartir)
-Soporte de subtítulos (no todos los clientes lo soportan) para Smart TV / BD para las marcas Samsung y LG.
-Soporte de red Ethernet (no probado en un dispositivo físico).

La versión gratuita tiene las siguientes funciones:
-Firewall Integrado (La Seleccion de dispositivos a los que se les permite acceder a su contenido multimedia se limita a un dispositivo en estado prohibido o permitido)
-Selección de archivos individuales (No se puede elegir lo que desea compartir)
-Soporte de subtítulos (no todos los clientes lo soportan) para Smart TV / BD de las marcas Samsung y LG (limitado a una solo subtítulo activo al mismo tiempo).
-Soporte de red Ethernet(no probado en un dispositivo físico).

Modo de empleo:
-Con tu dispositivo Android conectado a una red (WiFi o Ethernet), activar el servidor (se activa automáticamente cuando se inicia la aplicación).
Con un dispositivo compatible con DLNA (yo uso una PlayStation 3 o plugin de Winamp con ml_upnp o UpnpPlay) abrir el servidor y ver su contenido.
Por ejemplo: desde la PS3 ir a la Música-> MediaServer-> Música-> All-> "seleccionar una canción y esperar". si quieres ver las fotos ir a Foto-> MediaServer-> Fotos-> Todos> "seleccionar una imagen y esperar". y lo mismo para el vídeo.

El servidor puede tardar hasta 10 segundos para estar visible en un cliente, si por cualquier razón después de un rato nada sucediera, pulse el botón en el servidor móvil (apagado y encendido).

Nota importante: No utilice programas p2p en la misma red WiFi, ya que introducen demasiadoas retransmisiones en las comunicaciones.

Nota: Aunque el servidor sigue funcionando con la pantalla del móvil apagada, he comprobado que la aplicación funciona mejor con la pantalla encendida, por lo que se recomienda desactivar el apagado de la pantalla automático.

Nota importante:
Si está conectado a una red inalámbrica móvil y sufre conexiones y desconexiones cuando intenta transmitir contenido multimedia, el problema está en el router (saturado), para resolver este problema o bien actualiza el firmware del router a una versión mejorada o compra un router que soporte el estandar 802.11ac.

Nota: Si la aplicación se cuelga y cuando vuelva a arrancarla no funciona (reinicie el teléfono, esto es muy raro).

Bugs conocidos:
Con velocidades de transferencia bajas el vídeo puede tener saltos en la imagen, aunque esto depende de la velocidad de la red y la resolución de vídeo.
