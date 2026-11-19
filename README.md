# learningIA

Material de estudio interactivo para **Unidad 3 — Modelos Ocultos de Markov**, de la materia Bioinformática (Ingeniería Informática, UNAJ), basado en las Clases 9 y 10 (H. Ariel Álvarez).

🔗 **Sitio publicado (GitHub Pages):** `https://<usuario>.github.io/learningia/`

## Contenido

- **`index.html`** — página de inicio con los dos accesos.
- **`laboratorio-hmm.html`** — "Laboratorio HMM": recorrido guiado por los 9 temas y 51 subtemas de la unidad. Cada subtema trae la cita textual exacta de la filmina, una explicación en palabras simples, diagramas de conjuntos anidados donde corresponde (AI⊃ML⊃DL, Multinomial⊂Markov⊂HMM) y una pregunta de opción múltiple. El progreso se marca automáticamente al responder (no por autoevaluación), con quiz general por tema y avance automático al siguiente. Incluye un glosario académico (tooltip al pasar el mouse) y, si te equivocás, un modal mostrando la respuesta correcta.
- **`millonario-hmm.html`** — "¿Quién Sabe HMM?": el mismo contenido en formato de juego de preguntas y respuestas (estilo programa de TV), con 15 niveles de dificultad creciente, comodines (50:50, ayuda del público, pista del profesor), pisos seguros y sonido sintetizado con Web Audio API (sin archivos de audio con copyright).
- **`topics-data.js`** — banco de preguntas y contenido (compartido entre las dos páginas), extraído verbatim de las filminas originales.

## Desarrollo local

Son páginas estáticas sin build step ni dependencias — basta con abrir `index.html` en un navegador, o servir la carpeta con cualquier servidor estático:

```bash
python -m http.server 8080
```

## Publicar con GitHub Pages

Settings → Pages → Source: Deploy from a branch → `main` / `(root)`.
