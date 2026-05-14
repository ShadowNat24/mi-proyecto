Flexbox

Propiedades recuperadas de los desafíos de Flexbox Froggy para organizar los elementos de forma prolija:

justify-content: Alinea los elementos horizontalmente (eje principal). Valores: flex-start, flex-end, center, space-between, space-around.
align-items: Alinea los elementos verticalmente (eje secundario). Valores: flex-start, flex-end, center, baseline, stretch
flex-direction: Define la dirección de los elementos. Valores: row, row-reverse (útil para los testimonios), column, column-reverse
order: Permite cambiar el orden de un elemento específico sin tocar el HTML.
align-self: Permite alinear un solo elemento de forma independiente al resto.
flex-wrap: Define si los elementos deben pasar a una nueva línea si no hay espacio. Valores: nowrap, wrap, wrap-reverse.
flex-flow: Atajo para usar flex-direction y flex-wrap al mismo tiempo.
align-content: Alinea las líneas de un contenedor cuando hay espacio extra (similar a justify-content pero para filas).

Box Model

Propiedades esenciales para manipular el espacio y tamaño de los bloques de información:

padding: Controla el espacio interno entre el contenido y el borde del elemento.
Border: Define el borde o marco que rodea al padding y al contenido.
Margen: Establece el espacio externo que separa a un elemento de los demás.
box-sizing: Determina cómo se calcula el tamaño total del elemento. El valor border-box es el más conveniente para evitar que el padding y el borde aumenten el tamaño real de la caja, manteniendo el diseño ordenado.

Unidades Absolutas y Relativas

Uso recomendado para asegurar que la página no se vea "monstruosa" en diferentes pantallas:

Unidades Absolutas :
Cuándo convienen: Para elementos que deben tener un tamaño fijo y exacto, como el grosor de un borde, sombras o elementos que no deben estirarse bajo ninguna circunstancia.

Unidades Relativas:
Los porcentajes (%) y las unidades de ventana (vh, vw) sirven para que las secciones (como el login centrado) se adapten al tamaño de la pantalla.

La unidad rem es ideal para la tipografía, ya que permite que el texto escale de forma prolija según la configuración del navegador, cumpliendo con el pedido de Elvis de una fuente legible que no canse la vista.
