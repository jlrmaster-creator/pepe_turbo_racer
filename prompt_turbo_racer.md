**Contexto y Rol**
Actúa como un desarrollador experto en videojuegos web tipo arcade con experiencia en juegos de conducción y optimización para dispositivos móviles. Tu objetivo es crear una experiencia fluida, visualmente atractiva y con sensación de juego profesional directamente en el navegador.

**Consulta / Tarea**
Desarrollar una aplicación web de tipo arcade donde el jugador controla un coche que debe mantenerse dentro de una carretera con curvas dinámicas que se generan continuamente. El objetivo es avanzar el mayor tiempo posible sin salirse de la carretera.

**Especificaciones**

**Mecánica principal:**

* El jugador controla un coche que:

  * Se desplaza horizontalmente (izquierda/derecha).
  * Avanza automáticamente hacia adelante.
* La carretera:

  * Se genera dinámicamente con curvas suaves y continuas.
  * Se mueve hacia el jugador (efecto de desplazamiento infinito).

**Sistema de control:**

* Compatible con:

  * Teclado (flechas izquierda/derecha o A/D)
  * Dispositivos móviles:

    * Botón táctil izquierda
    * Botón táctil derecha
* Botón adicional de **pausa/reanudar**

**Sistema de puntuación y niveles:**

* Puntuación aumenta según la distancia recorrida.
* Sistema de niveles:

  * Aumenta automáticamente con el tiempo o puntuación.
  * Incrementa dificultad progresivamente.

**Dificultad progresiva:**

* Aumento gradual de:

  * Velocidad del juego
  * Intensidad de curvas
* La progresión debe ser suave y no frustrante.

**Sistema de vida:**

* Barra de progreso/vida visible:

  * Disminuye cuando el coche se sale de la carretera.
  * Se recupera ligeramente si el coche vuelve al centro (opcional).
  * Cuando llega a 0 → fin de partida.

**Diseño visual:**

* Estilo profesional arcade
* Fondos con paisajes dinámicos (ejemplo: montañas, desierto, ciudad, bosque)
* Posible efecto parallax para dar profundidad
* Animaciones suaves y consistentes

**Interfaz (UI):**

* Pantalla inicial:

  * Título del juego
  * Botón “Jugar”
* Pantalla de juego:

  * HUD con:

    * Puntuación
    * Nivel
    * Barra de vida
    * Botón de pausa
* Pantalla final:

  * Puntuación final
  * Botón de reinicio

**Audio:**

* Sonido del motor
* Efecto al salirse de la carretera
* Música de fondo opcional (loop suave)

**Tecnología sugerida:**

* HTML5, CSS3, JavaScript
* Canvas API o librería ligera como Phaser.js
* Diseño responsive adaptado a móviles

**Criterios de Calidad**

* Rendimiento fluido (mínimo 60 FPS)
* Código modular y limpio
* Experiencia mobile-first optimizada
* Controles precisos y responsivos
* Sensación de juego pulido y profesional

**Cómo debe ser la respuesta**

* Incluir:

  * Estructura del proyecto
  * Código funcional base
  * Explicación clara de la lógica principal
* Priorizar claridad, jugabilidad y rendimiento
* Mantener el diseño atractivo pero eficiente
