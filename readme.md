# Práctica Portfolio

## La práctica se encuentra desplegada en:
[Practica-Port-Folio](https://rpfumanchu.github.io/Portfolio-Practica/) 

### Composición de la página.
- Navbar.
    - Para la versión movil hice un menú burguer para el que me documente en el uso de "before y after", en páginas como esta:
    [Before-After](https://www.arsys.es/blog/desarrolloweb-tbd)
    - Para hacer el botón del menú encontre conceptos en esta otra página:
    [menu-burguer](https://dev.to/tognola/menu-hamburguesa-solo-con-css-facil-1doc)
    -Tanto el botón del menú como la barra de búsqueda completa "pantalla pc" están fijas al hacer scroll. Además la barra en versión pc tiene en los links una transicion de color.
- Título con dos iconos
- Un header principal con tres imágenes que cambian  
  según el tamaño de la pantalla.
    - [img-movil](imagenes/cabecera-pequeña3.png)
    - [img-tablet](imagenes/cabecera_467.jpg)
    - [img-pc](imagenes/cabecera1.jpg)

- La página tiene cuatro secciones "Biografía, Palmares, Top-2, Contacto.
    - Biografía.
        - [#Biografia](https://rpfumanchu.github.io/Portfolio-Practica/#biografia)
    - Palmares.
        - Esta sección cuenta con un pequeño artículo y 8 barras de progreso animadas, la animación se repite 3 veces, hasta que se detiene en su posición final, además tienen una transición en el color.
        - [#Palmares](https://rpfumanchu.github.io/Portfolio-Practica/#palmares)
    - Top-3.
        - Esta sección cuenta con tres videos optimizados a distintos anchos, para su mejor visualización.
        - [#Top-3](https://rpfumanchu.github.io/Portfolio-Practica/#top-3)
    - Contacto.
        - Uso "method-post y action-registro.html" para que se quede guardada esa informacion de los campos, esto no termina de funcionar al no haber un backend detras.
        - Esta sección tiene un formulario con algunos campos requeridos "usando required" y  un fielset con 4 input-radio también requerido seleccionar uno, un área de texto para dejar tu opinión limitada a 180 caracteres y un campo Fan-club donde usando "pattern" y una expresión regular para obligar que ese campo sea"@username".
        - [#Contacto](https://rpfumanchu.github.io/Portfolio-Practica/#contacto)
- La sección details cuenta con un vídeo y 10 imágenes, utilice "grid" para hacer las columnas, además pasa de 2 columnas en versión movil a 5 en versión pc, "usando media query"
    - Algunos ejemplos:
    - [salvada](videos/salvada.mp4)
    - [img-salvada](imagenes-details/img6.jpg)
    - [img-salvada](imagenes-details/img1.jpg)
    - [img-salvada](imagenes-details/img9.jpg)

- Y finalmente un footer con links a las principales redes sociales, estos links tienen un "target _blank" para no abandonar mi página y uso "noopener noreferrer" para no dejar rastro en estas páginas.

- Uso la extensión "responsive viewer" para ver como se despliega en distintos dispositivos moviles, tablets y pc de distintos tamaños de pantalla.





