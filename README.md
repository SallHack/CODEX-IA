# Ultron Dashboard (Demo)

Dashboard estático de préstamos hecho con **HTML/CSS/JS** y **Chart.js por CDN**, sin build y sin npm.

## Cómo abrirlo (Windows, sin instalar nada)
1. Entra a esta carpeta del repo.
2. Haz doble click sobre `index.html`.
3. Se abrirá en tu navegador por defecto.

> No requiere servidor local ni instalaciones adicionales.

## Contenido del dashboard
- KPI cards: Outstanding, PAR30, Cobrado hoy, Cobrado semana, Clientes en riesgo.
- Gráfico de PAR30 de las últimas 12 semanas.
- Tabla “At-risk customers” (top 15).
- Sección “Collections” con lista priorizada por `amount_due * recover_probability`.
- Datos demo realistas generados dentro del JavaScript.
