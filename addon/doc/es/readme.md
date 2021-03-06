# placeMarkers #

* Autores: Noelia, Chris.
* descargar [versión estable][1]
* descarga [versión de desarrollo][2]

Este complemento se utiliza para guardar y restaurar cadenas de texto
específicas o marcas. Puede utilizarse en páginas web o en documentos en el
modo exploración de NVDA. También puede utilizarse para guardar o buscar
cadenas de texto en controles multilínea; en este caso, si no es posible
actualizar el cursor, la cadena correspondiente se copiará al portapapeles,
tal que se pueda buscar utilizando otras herramientas.  El plugin guarda las
cadenas especificadas y marcas en ficheros cuyos nombres se basan en el
título y URL del documento actual.  Este complemento se basa en
SpecificSearch y Bookmark&Search, desarrollados por el mismo autor. Deberías
desinstalarlos para utilizar éste, ya que tienen las mismas combinaciones de
teclas y características.

## Órdenes de teclado: ##

*	control+shift+NVDA+f: abre un diálogo con un cuadro de edición que muestra
  la última búsqueda guardada; en este diálogo también puedes seleccionar
  las búsquedas anteriormente guardadas desde un cuadro combinado o eliminar
  la cadena seleccionada desde el historial utilizando una casilla de
  verificación. Puedes elegir si el texto contenido en el cuadro de edición
  se añadirá al histórico de textos guardados. Finalmente, elegir una acción
  del siguiente grupo de botones de opción (entre buscar siguiente, buscar
  anterior o no buscar), y especificar si NVDA hará una búsqueda sensible a
  las mayúsculas. Cuando pulses Aceptar, NVDA buscará esta cadena.
*	control+shift+NVDA+k: guarda la posición actual como una marca. Si quieres
  proporcionar un nombre para esta marca, selecciona algún texto de esta
  posición antes de guardarla.
*	control+shift+NVDA+suprimir: elimina la marca correspondiente a esta
  posición.
*	NVDA+k: mueve a la marca siguiente.
*	shift+NVDA+k: mueve a la marca anterior.
*	control+shift+k: copia el nombre del fichero donde se guardarán los datos
  de marcadores al portapapeles, sin una extensión.
*	alt+NVDA+k: abre un diálogo con las marcas guardadas para este
  documento. Puedes escribir una nota para cada marca; pulsa Guardar Nota
  para guardar cambios. Pulsando Aceptar puedes moverte al a la posición
  seleccionada.


## Submmenú Place markers (NVDA+N) ##

Utilizando el submenú Place markers en el menú Preferencias, puedes acceder
a 

*	Carpeta de búsqueda específica: abre una carpeta de búsquedas específicas
  guardadas previamente.
*	Carpeta de marcas: abre una carpeta con las marcas guardadas.
*	Copiar carpeta de marcadores: puedes guardar una copia de la carpeta de
  marcadores.
*	Restaurar marcadores: Puedes guardar tus marcas desde una carpeta de
  marcadores guardada anteriormente.

Nota: La posición de la marca se basa en el número de caracteres; y por lo
tanto en páginas con contenido dinámico es mejor usar la búsqueda específica
y no las marcas.


## Cambios para 8.0 ##
*	Eliminados fragmentos de identificadores de nombres de ficheros de
  marcador,  los cuales pueden evitar problemas en VitalSource Bookshelf
  ePUB READER.
*	Se añadió un diálogo Notas, para asociar comentarios para marcas guardadas
  y para moverte a la posición seleccionada.

## Cambios para 7.0 ##
*	El diálogo para guardar una cadena de texto para una búsqueda específica
  se ha eliminado. Esta funcionalidad ahora se incluye el diálogo Búsqueda
  Específica, el cual se ha rediseñado para permitir acciones diferentes al
  pulsar el botón Aceptar.
*	Se ha mejorado la presentación visual del diálogo, adhiriéndose a la
  apariencia de los diálogos mostrados en NVDA.
*	Al realizar una orden Buscar siguiente o buscar anterior en Modo
  exploración ahora se hará correctamente una búsqueda sensible a las
  mayúsculas si la búsqueda original era sensible a las mayúsculas.
*	Se requiere de NVDA 2016.4 o posterior.
*	Ahora puedes asignar gestos para abrir los diálogos Copiar y Restaurar
  marcadores.
*	NVDA presentará un mensaje para notificar cuando se haya copiado o
  restaurado los marcadores con los diálogos correspondientes.

## Cambios para 6.0 ##
* Cuando las características del complemento no son usables, los gestos se
  envían a la aplicación correspondiente.

## Cambios para 5.0 ##
* Añadida búsqueda sensible a las mayúsculas.
* Eliminada la opción para abrir documentación desde el menú Place markers.
* Órdenes de teclado más intuitivas.

## Cambios para  4.0 ##
* Eliminados fragmentos de identificadores de nombres de ficheros de
  marcador,  los cuales pueden evitar problemas en el complemento de Firefox
  ePUBREADER.
* La ayuda del complemento está disponible desde el Administrador de
  Complementos.

## Cambios para 3.1 ##
* Actualización de traducciones y nuevos idiomas.
* Ahora no se anuncia la posición del marcador en la lectura superficial.

## Cambios para 3.0 ##
* Añadido el soporte para lectura superficial.

## Cambios para 2.0 ##
* Añadidas opciones para guardar y eliminar diferentes búsquedas para cada
  archivo.
* Solucionado un problema que rompía cuando las rutas contenían caracteres
  no latinos.
* Los atajos de teclado ahora pueden reasignarse utilizando el diálogo de
  Entrada de gestos de NVDA.

## Cambios para 1.0 ##
* Versión inicial.
* Traducido a: Alemán, Coreano, Eslovaco, Esloveno, Español, Farsi,
  Finlandés, Francés, Gallego, Italiano, Japonés, Nepalí, Portugués,
  Portugués del Brasil, Tamil.

[[!tag dev stable]]

[1]: http://addons.nvda-project.org/files/get.php?file=pm

[2]: http://addons.nvda-project.org/files/get.php?file=pm-dev
