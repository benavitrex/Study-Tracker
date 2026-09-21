# 🎯 PAES Tracker

Tracker personal para el proceso de preparación PAES 2026 — construido como una sola página HTML, sin backend ni dependencias externas. 🚀

🔗 **Demo:** _agrega aquí tu link de GitHub Pages una vez publicado_

## ✨ ¿Qué hace?

- ⏳ **Countdown** en vivo hasta la rendición PAES Regular (30 nov – 2 dic 2026).
- 💬 **Frase del día**, rotando automáticamente según la fecha.
- ⚖️ **Ponderación de la carrera objetivo** (Ing. Civil Industrial – PUCV): NEM, ranking, M1, M2, Comprensión Lectora, Historia.
- 📅 **Fechas clave** del proceso de admisión (DEMRE), marcando cuáles ya pasaron.
- 🔥 **Heatmap anual estilo GitHub**: click en un día para marcar si estudiaste (4 niveles de intensidad), con racha actual, racha récord y total de días.
- 🗓️ **Horario semanal**: vista tipo calendario (lunes a domingo) con todos los bloques de clases, estudio autónomo y ensayos.
- 📚 Acceso directo al preuniversitario de apoyo.

## 🕹️ Cómo usarlo

1. Abre `index.html` en el navegador (o entra al link de GitHub Pages).
2. Haz click en los días del heatmap para ir marcando tu avance. ✅
3. Todo se guarda en `localStorage` del navegador — no requiere cuenta ni servidor. 🔒

## 🌐 Publicarlo con GitHub Pages

1. Sube este archivo a un repositorio público.
2. Ve a **Settings → Pages**.
3. En *Branch* selecciona `main` y carpeta `/ (root)`.
4. Guarda. En 1-2 minutos tu sitio queda disponible en `tu-usuario.github.io/nombre-repo/`. 🎉

## 🛠️ Notas técnicas

- Un solo archivo (`index.html`): HTML + CSS + JS inline, cero dependencias.
- Persistencia local por año (`localStorage`, clave `paeslog:AÑO`) — los datos no salen del navegador ni se comparten entre dispositivos.
- Fechas y ponderaciones están hardcodeadas para el proceso de admisión 2027 (rendición PAES 2026); si cambian, se editan directamente en el HTML.

---
