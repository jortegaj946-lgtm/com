# Canva-like MVP Starter

Estructura mínima para un editor tipo Canva (MVP) usando **React + Vite + Tailwind + react-konva**.

## Qué incluye
- Editor con canvas básico (agregar texto e imagen, mover, escalar, rotar).
- Export a PNG.
- Heatmap overlay que registra los clics del usuario para mostrar "mapa de calor" local (MVP).
- Archivos listos para subir a GitHub (usa `git init` y sube).

## Cómo usar localmente
1. Descomprime el zip y entra en la carpeta.
2. Ejecuta:
   ```
   npm install
   npm run dev
   ```
3. Abre http://localhost:5173

## Notas
- Este es un MVP inicial. Para producción: añadir backend, S3 para almacenamiento, Auth, payments, y optimizaciones.
- Revisa `src/components/Editor.jsx` para la lógica del canvas.
