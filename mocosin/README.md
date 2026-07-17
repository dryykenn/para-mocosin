# Flores para Ti 🌷🌹🌻

Este proyecto consiste en una **tarjeta digital interactiva y animada** diseñada como un detalle romántico o conmemorativo especial. El archivo principal es un documento auto-contenido en HTML, CSS y JavaScript que genera un árbol cuyos brotes florecen dinámicamente formando la silueta de un corazón.

## Características Principales

*   **Animación de Florecimiento Dinámico:** Un tronco y ramas vectoriales (SVG) crecen en la pantalla, seguidos por el brote secuencial de flores (girasoles, rosas y tulipanes) que se posicionan de manera matemática utilizando una curva implícita de corazón.
*   **Contador en Tiempo Real:** Incluye un cronómetro interactivo que calcula y muestra de forma exacta los días, horas, minutos y segundos transcurridos desde una fecha significativa (**14 de octubre de 2021**).
*   **Efectos Ambientales Visuales:** Cuenta con una caída sutil y constante de pétalos animados, junto con corazones flotantes de fondo en un degradado de tonos vino y rosa.
*   **Diseño Responsivo y Adaptable:** Completamente optimizado para visualizarse de forma óptima tanto en dispositivos móviles como en pantallas de escritorio.
*   **Accesibilidad de Animación:** Soporta la directiva de CSS `prefers-reduced-motion` para usuarios que prefieren reducir las animaciones del sistema.

## Tecnologías Utilizadas

*   **HTML5:** Estructura semántica de la tarjeta y contenedores de la escena.
*   **CSS3 (Animaciones y Gradientes):** Estilos personalizados, transiciones fluidas, variables nativas (`:root`) y animaciones de fotogramas clave (`@keyframes`) para simular la caída de pétalos y el crecimiento de los elementos.
*   **SVG (Scalable Vector Graphics):** Gráficos vectoriales nativos para las estructuras del árbol y las figuras detalladas de cada tipo de flor.
*   **JavaScript (Vanilla JS):** Algoritmo de dispersión matemática para barajar y posicionar las flores sobre los puntos coordenados del corazón, control de los tiempos de retraso en la animación (`animationDelay`) y lógica del contador en tiempo real con ejecución por intervalos (`setInterval`).

## Instrucciones de Uso

1. Guarda el código proporcionado en un archivo local con extensión `.html` (por ejemplo, `index.html`).
2. Abre el archivo en cualquier navegador web moderno (Chrome, Firefox, Safari, Edge).
3. ¡Disfruta de la animación interactiva y el contador en tiempo real!
