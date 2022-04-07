# freecodecamp.html.css
Repositorio basado en este curso https://www.youtube.com/watch?v=XqFR2lqBYPs

# Doctype es la declaración de tipo de documento #
## Element ##
Componente básico de HTML, definen la estructira de la página web
## Etiquetas ## 
Nos permiten definir los elementos en un archivo HTML 
Especificn el tipo de elemento se usa "TAG"
Ejemplos : <head> </head> con etiqueta de apertura y de cierre 
Las "Self-closing tags" no ocupan etiqueta de cierre. 
opcional se puede incluir el cierre con slash en este modo <img/>
## Atributo ##
Un atributo especifica algo sobre el elemento en el que está contenido 
## Documentación ## 
Es recomendable utilizar la MDN web docs  Red de Desarrolladores de Mozilla 
## MAIN ##
Es un elemento que representa el contenido principal de <body> Este contenido está directamente relacionado sobre el tema central del documento o funcionalidad central de la aplicación. No debe haber más de un elemeto MAIN en un documento ni puede se descendiente ni parte de otro elemento. 
## Niveles de Identación ##
Por lo regular se usan dos niveles por la recomendación de la guía de estilos de google para html y css, no se recomienda usar espacios ni tabs para indentar. 
## img ##
  Llleva el src para saber de donde proviene la imagen y el alt que es la descripción alterna de nuestra imagen cuando no pueda cargarse por falta de conexión 
 ## Ancor ##
  Sirve para crear enlaces externos con <a>
  "href" es la dirección del enlace externo, "target="_blank"" es para abrir el enlace en una nueva pestaña, por motivos de seguridad es recomendable agregar "rel="noopener noreferrer"" nos premite prevenir el ataque Tabnabbing, es un tipo de ataque en el que lapestaña de origen se reemplaza para que el usuario ingrese sus datos, abriendo una brecha de seguridad. 
  ## Enlaces internos a secciones de la página ##
  ### id="" ### 
  Es un atributo que es una identificación única que funciona con un "href" interno
 ## Dead Links ##
  Es un enlace que no lleva a ningun lado, sirve mientras estamos escribiendo el código cuando no sabemos que enlace se pondrá, al cargar la página, el enlace te lleva a la misma página en una pestaña nueva o bien no te lleva a ningún sitio. 
  ## Listas no ordenadas ##
 se utilia la etiqueta "<ul>" "unordered list"y para especificar cada elemento de la lista etiquetar con "li" estas deben estar anidadas dentro de "ul".
  ## Lista Ordenada ##
  Cada uno de los elementos de la lista tiene un número específico. 
  se utiliza la etiqueta "ol" "ordered list" y para especificar cada elemento "li".
  ## Edición en HTML## 
  Negritas: usar etiqueta strong
  Cursiva/ itálica: etiqueta "em"
  Tachado: etiqueta "s" 
  ## Línea horizontal para separar ##
  Se utiliza "hr" "horizontal rule"
  ## Crear Formulario ## 
  Etiqueta "form", después <input> para que el usuario ingrese un texto con type= text, button para agregar
  botón. Un "placeholder" es una tributo para "marcar posición" para darle una pista al usuario para saber que escribir en el formulario, se ubica en el <input> después de type y desaparece visualmente cuando el ususario ingresa un texto. 
  ## Campos obligatorios ## 
  Para evitar que alguien pueda enviar conjuntos vacíos, se agrega el atributo "required"
 ## Botones de Radio ##
  Es un tipo de elemento en <input>, "radio" permite crear botón de radio u opción. Si queremos que se seleccione el botón al dar click en el texto, se anida el input a un "label". Al incluir el atributo "for" en label, y "id" en input, logramos relacionarlo mejor. Para seleccionar SOLO UNA OPCION  por cada grupo de botones de radio, se crea un grupo de botones o categoria, solo se agrega el atributo "name" al <input>. Todos los elementos que tengan el "name" solo uno podrá estar marcado. 
  ## Casillas de Verificación o Checkmarks/box ##
 Se utiliza el input de tipo "input type="checkbox"", se le pueden dar los mismos atributos de label y relacionarlos por un for-id,  en este caso para "checkbox" aunque se aniden con el atributo "name" podrán seleccionarse varios. 
  ## Head ##
  Contiene la metadata y los elementos que no vemos pero son necesarios para que la página funcione conrrectamentem por ejemplo si necestamos añadir archivos CSS o JS a nuestro archivo HTML se agregan en esta zona. Se puede personalizar el título de la página con "title", lo cual es un factor importante para el SEO, posicionamiento y también para la xperiencia de usuario. 
  
