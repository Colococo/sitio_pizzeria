# Pizzeria y Quarto

## Pagina de inicio

This pizzeria guarantees you nicely cooked empanadas, pies and pizza. Food delivery is a big plus of Pizza y Quarto.

### Detalles tecnicos

## Responsive Design / Diseño sensible a cambios

Es una tecnica de diseno para hacer que una pagina web ajuste su contenido y estilo visual a todo tipo de pantalla posible (ventana o tamaño del navegador).
En practica esto significa que el diseño hace que los sitios web puedan ser usados en todos los dispositivos posibles, como en el escritorio del ordenaror, tabletas, y telefonos moviles.
Diseño responsive (Diseño sensible a cambios) no es una tecnologia separada, en realidad es un conjunto de buenas practicas que usamos en CSS (Cascade Style Sheet / Hojas de Estilo).

## Hay 4 ingredientes principales en Responsive Design / Diseño sensible a cambios

1.- Fluid Designs - Diseños fluidos

- Permite que la pagina se adapte al tamaño actual del navegador. Usando generalment FlexBox y CSS Grid (veremos luego que son estos dos) que son fluidos por definicion.
- Usamos % porcentajes (o unidades vh/hw) en lugar de pixeles PX para elementos que deberian adaptarse al tamaño del navegador (layout/diseño del contenido).
- Usamos max-width en lugar de with.

  2.- Responsive Units - Unidades de Respuesta

- Significa que debemos usar unidades REM (root em) en lugar de PX pixeles para la mayoria de los tamaños.
- De esta manera va a ajustar el contenido de la pagina arriba y abajo automaticamente.
- Un truco podria seria establecer 1 REM a 10 PX para facilitar los calculos de tamaños.

  3.- Flexible Images - Imagenes Flexibles

  - Imagenes se comportant muy diferente no se ajustan automaticamente cuando cambiamos el tamaño del navegador. Entonces tenemos que corregir eso para asegurarnos que las imagenes se adaptan a cualquier tamaño del navegador donde visualizamos la pagina.
  - Normalmente hacemos imagenes flexibles usando dimensiones en % (porcentajes) y tambien a veces usando la propiedad max-width en lugar de with.

    4.- Media Queries - Consultas de medios

    - Esto es lo que une todo lo anterior y trae a la vida el modo sensible a cambios (Responsive sites to life!)
    - Sin Media Querias el diseño sensible a cambios no funcionaria nunca, porque las media queries nos permite de cambiar los estilos en ciertos tamaños del ancho del navegador al cual llamamos BREAKPOINTS o puntos de interrupcion. Esto permite a los desarrolladores de sitios web de crear diferentes versiones del sitio web para los diferentes tipos de dispositivos ya que los diferentes tipos de dispositivos tienen diferentes anchos de pantalla.
    - Debemos considerar que usar Media Queries solamente es inutil, debemos crear un diseño de pagina web fluido desde el principio, y lo mismo se aplica para Unidades de Respuesta (Responsive Units) e imagenes flexibles.
    - Generalmente escribimos las Media Queries al final de haber escrito una pagina o un componente. Por este motivo para este sitio web vamos a utlizar Fluid Layouts, Responsive Units y Flexible Images. Luego usaremos Media Queries para hacer la pagina sensible a los cambios de tamaño de las pantallas del ordenador.

### Finalmente hay dos estrategias para constuir sitos que son sensibles a los cambios de tamaño del navegador.

Desktop First Approach (enfoque de escritorio primero): donde optimizamos las interfaces para pantallas grandes, por eso iniciamos escribiendo codigo CSS para las pantallas grandes en nuestro archivo principal de estilos CSS (style.css). Luego cuando queremos hacer el sitio web sensible a cambios escribimos Media Queries para comprimir el contenido de modo que pueda entrar el contenido en una pantalla mas pequeña. Este es el modo mas tradicional y el mas facil de entender. Por esta razon vamos a utilizar este approach para el sitio de la pizzeria.

Mobile First (Dispositivo Movil primero): es donde iniciamos a escribir CSS para pantallas pequeñas de modo de optimizar el contenido del sitio para pantallas de dispositivos moviles y de ahi podemos movernos a pantallas mas grandes usando Media Queries. Basicamente lo opuesto a Desktop First.
La idea detras de Mobile First es que nosotros como diseñadores tenemos que pensar primero en la experiencia del sitio en un dispositivo movil para los usuarios. Y hacemos esto reduciendo el sitio web a lo esencial y quitando todo lo que no sean necesario.

Visto que vivimos en un mundo movil este ultimo se convirtio en el modo mas moderno de construir sitios web estos dias.

Pero como haciendo el modo Desktop first es el mejor modo de aprender como funciona el desarrollo, prefiero usar este primero para que se pueda entender como HTML y CSS funcionan y ver los resultados en una pantalla grande.
