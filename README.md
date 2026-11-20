# Mi Glucosa — Control de diabetes

App web instalable (PWA) para registrar la glucosa con foto del glucómetro.

- Plan de 7 días: ayunas, antes de la comida principal, 2 h después de comer (+ antes de dormir opcional)
- Foto del glucómetro y del plato en cada medición
- Recomendaciones de alimentación (qué conviene y qué evitar) según el valor, el momento y lo que comiste
- Análisis opcional con IA (Google Gemini gratis, o Claude) que lee la foto del glucómetro y reconoce el plato
- Temporizador de 2 h para la medición posprandial y recordatorios
- Tabla semanal, gráficos, patrones e informe para el médico (PDF), exportar a Excel (CSV)

Los datos se guardan solo en el teléfono (IndexedDB). No sustituye la indicación médica.

## Publicar
Settings → Pages → Deploy from a branch → `main` / `(root)`.
