# Pepe Tubo Racer 🏎️

Juego arcade de conducción con perspectiva pseudo-3D tipo OutRun. Corre directamente en el navegador.

## Características

- 🛣️ Carretera con perspectiva 3D (chase cam) y curvas dinámicas
- 🌄 Fondos parallax con montañas, cielo estrellado y nubes
- 🚗 Coche detallado con animaciones de inclinación y bounce
- 🔊 Sonido de motor dinámico (Web Audio API) + efectos de sonido
- 🛢️ Obstáculos en la carretera (barriles) que restan vida
- 👤 Avatar coleccionable (PNG) que suma +50 puntos
- 💥 Efectos al salirse de la carretera (screen shake, partículas, viñeta roja)
- 💫 Partículas de colisión y popups de puntuación
- 📱 Controles táctiles y por teclado (flechas / A-D)
- 🏆 Sistema de récords (top 5, localStorage)
- 📊 Dificultad progresiva con niveles (velocidad máxima aumenta)
- 📈 HUD completo: barra de vida, velocímetro con gauge, puntuación, nivel

## Cómo jugar

### Opción 1 — GitHub Pages (recomendada)
Habilita GitHub Pages en `Settings → Pages → Source: Deploy from branch → main, / (root)`.
Una vez activado, el juego estará disponible en:
```
https://jlrmaster-creator.github.io/pepe_turbo_racer/
```

### Opción 2 — Local
Abre `index.html` en cualquier navegador moderno.

- **Teclado**: Flechas izquierda/derecha o A/D
- **Móvil**: Botones táctiles ◀ ▶
- **Pausa**: P / botón ⏸

Mantén el coche dentro de la carretera el mayor tiempo posible. Esquiva los barriles rojos y recolecta el avatar para ganar puntos extra. La velocidad aumenta con cada nivel.

## Tecnología

HTML5, CSS3, JavaScript (Canvas API + Web Audio API). Sin dependencias externas.
