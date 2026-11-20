# Bona Pilcha · Stock y caja

App web de una sola página (HTML, CSS y JS, sin build) para manejar stock, ventas, caja por turnos, gastos y empleados.

- Los datos se guardan en el navegador (localStorage).
- Opcional: sincronización en la nube con Firebase Realtime Database, que se configura desde **Ajustes** dentro de la app.
- Descargá respaldos con regularidad desde **Ajustes → Descargar respaldo**.

## Estructura

```
index.html   → toda la app
vercel.json  → configuración de Vercel
```

## Publicar en Vercel

1. Subí esta carpeta a un repositorio de GitHub.
2. En vercel.com → **Add New… → Project** → importá el repositorio.
3. Framework Preset: **Other**. Dejá vacíos Build Command y Output Directory.
4. **Deploy**. Cada `git push` a `main` publica una nueva versión.
