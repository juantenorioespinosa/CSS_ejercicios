# Efectos de Sombras y Menú Desplegable

El objetivo principal de este ejercicio es practicar la aplicación de efectos visuales en CSS3, el uso de propiedades de comportamiento de página ( `scroll-behavior` ) y la construcción lógica de un menú de navegación interactivo y anclado.

## 📋 Requisitos del Ejercicio

Para este ejercicio, se aplicaron las siguientes reglas de estilo:

1. **Comportamiento General:** Configuración del html con scroll-behavior: smooth para garantizar una navegación fluida entre las distintas secciones, combinado con un reseteo universal desde el selector * utilizando padding: 0 , margin: 0 y box-sizing: border-box para mantener un control absoluto sobre el modelo de caja en todo el documento..
2. **Título Principal:** El encabezado h1 destaca visualmente gracias a una sombra aplicada con la propiedad text-shadow.
3. **Menú de Navegación:** Contenedor principal con `position: sticky` y `z-index: 1000` para mantenerse siempre visible al hacer scroll. Enlaces con transiciones de color de fondo al hacer hover.
4. **Submenú Desplegable:**
* Oculto por defecto mediante `display: none` y posicionado con `position: absolute` .
* Despliegue al hacer `:hover` sobre su contenedor padre `li` cambiando a `display: block` .


5. **Sección Sombras en Textos:** Los párrafos utilizan la propiedad `text-shadow` para crear diferentes efectos visuales, combinando múltiples sombras, distintos niveles de desenfoque y colores.
6. **Sección Sombras en Cajas:** Los párrafos aplican la propiedad `box-shadow` para generar profundidad, incluyendo sombras exteriores básicas, sombreado interior ( `inset` ) y desplazamientos en diferentes ejes.

## 📁 Archivos del ejercicio

* `index.html` : Estructura de la página con las secciones y el menú debidamente enlazados mediante IDs.
* `nav.css` : Hoja de estilos dedicada a las reglas del menú de navegación y su comportamiento desplegable.
* `style.css` : Hoja de estilos principal con el reseteo, tipografía y las reglas aplicadas a los ejercicios de sombras.