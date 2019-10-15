# Practica01-Mi-Blog
Desarrollado en HTML y CSS
Creacion de un Blog Barcelonista con Referencias de Wikipedia
## 1.Creacion de la Estructura Basica de Html5
Doctype: Se especifica el tipo de Documento que vamos a realizar como es el caso de HTML
La Estructura HTML
* HTML
Con el atributo lang que especifica el idioma que esta desarrollo nuestra pagina en este caso es ES por español
  * HEAD
La Head o Cabecera con la etiqueta META que son de utilidad para los navegadores se utiliza el atributo charset que   especifica la codificacion utilizada en esta pagina. Se utiliza UTF-8 que es un estandar de HTML5. Con la etiqueta TITLE que va a especificar el titulo de nuestra pagina. Con la etiqueta LINK especifica la relacion entre el documento actual y un recurso externo puede ser otro HTML o en este caso llama a los efectos realizados en CSS con el atributo REL=”STYLESHEET” que especifica que el documento relacionado es una hoja de estilos y HREF que especifica el path donde se encuentra el otro documento.
  * BODY
Aqui se van a desarrollar todos los aspectos relavantes de la pagina y todo lo que los usuarios van a ver
## 2.Creacion de la Pagina Index.html
La Pagina Index.html va a ser la pagina principal donde se va a realizar un menu y unira a las demas paginas con la elaboracion de un menu definidos con un documento de estilos llamado estilos.css
* HEADER
Es el elemento que tiene contiene el encabezado de una seccion o documento, tambien se coloca habitualmente los vinculos de navegacion, logos, introducciones y tablas de contenidos con el atributo ID que representa un identificador unico para dicho elemento.
  * A
Es una etiqueta que representa un vinculo con el atributo HREF que representa el path de ubicacion de dicho  documento. SPAN es un contenedor de texto y sirve para agrupar elemento en linea.
  * NAV
Define un menu de navegacion esta etiqueta solo contiene referencias a otras secciones de la web. Con UL que representa una lista desordenada. Dentro de esta etiqueta se desarrolla la elaboracion de un Menu

Con elaboracion de un Documento de Estilos CSS uno que afecta de manera general a toda el BODY de la pagina otra que llama a ciertas etiquetas en comunes.

## 3.Desarrollo de una hoja de Estilos CSS General.CSS y Estilos.CSS
Para la interaccion con el usuario se desarrolla un hoja de Estilos para integrar de mejor manera los elementos antes mencionados.
**GENERAL.CSS** afecta principalmente al BODY de la pagina
- Margin: Se establece el valor de los Margenes de los elementos
- Padding:Se establece el valor de las zonas de rellenos
- Font-Family: Se especifica el tipo de Letra utilizada
- Color:el color del tipo de letra
- Background-image: especifica que se va poner una imagen de fondo
**ESTILOS.CSS** afecta a ciertos elementos en comun.
Afecta a los ID de cabecera,cabecera-1 con sus span respectivos, imagenes y menu de navegaciones.
- Font-size:Es el tamaño de la letra 
- Line-Height: Espacio entre lineas
- La propiedad :Hover: Es como un evento cuando el usuario pasa con el click
## 4.Creacion del Footer
Creacion del Pie de Pagina establecido en la Practica
**FOOTER**
Es el elemento de pie de pagina para representar el contenido
- &nbsp entidad que representa un espacio en blanco
- &copy entidad que representa la leyenda de Derechos Reservados
## 5.Creacion de un Tabla 
Creacion de una tabla especificada como en la Practica

* **TABLE**
Elemento que representa una tabla con el atributo **BORDER** que representa tamaño del border y el atributo CLASS que representa la clase establecida.
* **TR**
Representa las filas de una tabla con los atributos **ROWSPAN** que representa el numero de filas que representa la celda ALIGN que representa la alineacion del texto dentro de la fila **COLSPAN** que representa el numero de columnas que representa la celda
* **TD**
Representa una celda de Datos se encuentra dentro de un TR.
## 6.Enlace a un Video de Youtube
Para enlazar un video de Youtube se puede utilizar la Herramienta **IFRAME**
* IFRAME
Permite insertar un documento HTML dentro de otro documento HTML
- Src Origen o URL del Video de Youtube 
## 7.Creacion de 2 Section, 3 Article y Navegacion entre ellos
Elaboracion del Documento Historia.html que permite la Navegacion entre ellos
El Atributo **HREF** hace referencia a las ID de los ARTICLE
Para la Creacion de las Section con Article se Utilizo
- Con la etiqueta **DFN** que representa un termino que esta definido dentro del parrafo **ABBR** que representa una abreviacion **P** que representa el parrafo **CITE** que representa una cita **EM** que es apropiado para marcar con enfasis las partes importantes del texto **MARK** que va a subrayar de amarillo lo que se encuentro de la etiqueta
