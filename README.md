# BABUI · Visualizer Studio

Herramienta web para crear visualizers musicales 1080p directamente en el navegador
(render por GPU, sin instalar nada). Parte del arsenal de herramientas de BABUI.

## Qué hace
- Carga una canción (WAV/MP3) y genera un visualizer reactivo a la música.
- Estilos: Túnel retro, Caleidoscopio, Synthwave, Partículas, Imagen y **Patronus (2 capas)**.
- Palabras temporizadas difuminadas (formato `min:seg | palabra | posición`).
- Reactividad explícita: los graves/kicks mueven la escena y disparan destellos.
- Graba en 1080p con el audio y descarga el vídeo (.webm).

## Cómo usar
1. Abre `index.html` (o la URL de GitHub Pages).
2. Elige estilo, carga la canción (y las imágenes si usas Imagen/Patronus).
3. Pulsa **Previsualizar** o **Grabar y descargar**.

## Modo Patronus (2 capas)
- Imagen 1 = fondo (p. ej. laberinto nocturno).
- Imagen 2 = sujeto de luz sobre **fondo negro puro** (p. ej. babuino tipo patronus).
- El sujeto recorre el fondo con aura difusa y palpita con la música.

## Tecnología
HTML + WebGL2 + Web Audio API, en un único archivo autocontenido.
