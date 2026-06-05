# 7 a 0 · Edición Fútbol Argentino (BETA)
Un juego de **Juniloyd** 🇦🇷

Tirá el dado, armá tu equipo con cracks históricos del fútbol argentino y ganá la Copa de la Liga Chiqui Tapia.

## CÓMO PUBLICARLO EN VERCEL (gratis, ~5 min)

### Opción A — Arrastrar la carpeta (la más fácil)
1. Entrá a https://vercel.com e iniciá sesión (con GitHub, GitLab o tu email).
2. Click en **"Add New..."** (arriba a la derecha) → **"Project"**.
3. Buscá la opción de subir archivos / **"Deploy"** manual y **arrastrá la carpeta `deploy-vercel`** (la que contiene index.html).
4. Vercel detecta que es un sitio estático y lo publica solo.
5. En segundos te da una URL tipo **`https://7a0-argentino.vercel.app`** — esa es tu página, lista para compartir por WhatsApp.

### Opción B — Con Vercel CLI (desde la terminal)
```bash
npm i -g vercel
cd deploy-vercel
vercel
```
Seguí los pasos (login + Enter en todo), y al final te da la URL.
Para publicar la versión definitiva: `vercel --prod`

## CÓMO ACTUALIZARLO MÁS ADELANTE
Cuando cambiemos algo del juego, reemplazás el `index.html` por el nuevo y:
- Opción A: volvés a arrastrar la carpeta en vercel.com
- Opción B: corrés `vercel --prod` de nuevo

La URL queda igual, solo se actualiza el contenido.

## QUÉ INCLUYE ESTE BETA
- 46 equipos históricos del fútbol argentino (781 jugadores)
- Ratings por tiers (los grandes pegan más fuerte)
- 30 DTs con estilos (ofensivo, defensivo, equilibrado, ganador)
- Copa de la Liga Chiqui Tapia: fase de grupos + eliminación
- Apodos de cracks, frases derroteras y premios
