## Ejercicio 02: Flexbox - Posicionamiento y Layouts

El objetivo principal de este ejercicio es practicar el uso de CSS3 Flexbox para controlar la distribución, alineación y dirección de los elementos dentro de un contenedor, garantizando layouts limpios y un flujo estructurado de cajas.

📋 Requisitos de los Ejercicios

Para esta serie de prácticas, se aplicaron las siguientes reglas de estilo y posicionamiento:

* **Estructura Común**: Configuración de los encabezados de los menús con fondo negro, texto blanco, tipografía Arial y espaciados reseteados (`margin: 0px`) para evitar desajustes del navegador.
* **Ejercicio 1 (Alineado a la izquierda)**: Activación de Flexbox en el contenedor de la lista (`ul`) para alinear los elementos en fila horizontal hacia la izquierda por defecto de forma nativa.
* **Ejercicio 2 (Alineado al centro)**: Uso de la propiedad `justify-content: center` para agrupar y centrar todos los enlaces en el medio del eje principal.
* **Ejercicio 3 (Espacio entre items)**: Aplicación de `justify-content: space-between` para separar los elementos de manera uniforme, pegando el primero y el último a los extremos exteriores del menú.
* **Ejercicio 4 (Alineado vertical)**: Uso de `flex-direction: column` para cambiar el eje principal y apilar los enlaces verticalmente, limitando el contenedor con un `max-width` para controlar su anchura.
* **Ejercicio 5 (Catálogo de imágenes)**: Creación de una galería horizontal con `display: flex` sobre un contenedor con fondo gris, manteniendo las imágenes agrupadas al inicio del flujo.
* **Ejercicio 6 (Catálogo con espaciado)**: Aplicación de la propiedad moderna `gap: 20px` para separar las imágenes de forma exacta sin alterar los márgenes exteriores, añadiendo además bordes punteados a los elementos.
* **Ejercicio 7 (Catálogo de viajes)**: Maquetación semántica de tarjetas de contenido utilizando `flex: 1` para que todas las columnas crezcan de forma idéntica e igualitaria, combinando `max-width: 100%` y `aspect-ratio: 16/9` para asegurar el comportamiento responsivo de las imágenes.

📂 Archivos del proyecto

* `index.html`: Menú principal e índice de acceso a cada una de las prácticas.
* `ejercicio1.html` a `ejercicio7.html`: Estructuras HTML individuales de cada caso práctico.
* `css/estilos.css`: Hoja de estilos centralizada con las reglas de Flexbox organizadas por selectores específicos.
* `img/`: Carpeta de recursos con las imágenes optimizadas para el catálogo de viajes.
