# CuraGuide - PWA · DoncelProject

## Archivos
- `index.html` — Aplicación completa (HTML/CSS/JS en un solo archivo)
- `sw.js` — Service Worker para funcionamiento offline
- `manifest.json` — Manifest PWA (instalación en dispositivo)

## Despliegue en Netlify
1. Sube los 3 archivos al repositorio GitHub
2. Conecta el repo en Netlify → Deploy
3. Añade dos iconos (icon-192.png y icon-512.png) en la raíz para la instalación PWA completa

## Cambiar contraseña
En `index.html`, busca la línea:
```
const PASSWORD = "molinero26";
```
Cámbiala por la nueva contraseña y haz push al repo.

## Funcionalidades
- 🩹 Selector de apósitos por tipo herida + tejido + exudado + infección
- 📊 Escalas Braden, EMINA, PUSH y RESVECH 2.0 interactivas
- 👤 Gestión de pacientes con seguimiento longitudinal
- 📈 Gráfico evolución PUSH y comparativa últimas 2 curas
- 🔒 Acceso por contraseña
- 📡 Offline completo (Service Worker + localStorage)

## Stack
React-free · Vanilla JS · CSS custom · localStorage · PWA
