# Asiste · Lista de asistencia

Aplicación de asistencia creada con Astro. Permite marcar estudiantes como presentes, ausentes o atrasados, filtrar la lista, buscar por nombre y guardar el registro por fecha en el navegador.

## Requisitos
- Node.js 20.3.0 o superior (recomendado)
- Git

## Ejecutar en local
```bash
npm install
npm run dev
```
Abre la URL que muestre la terminal, normalmente `http://localhost:4321`.

## Generar versión de producción
```bash
npm run build
npm run preview
```

## Estructura
- `src/pages/index.astro`: página principal y controles de asistencia.
- `src/components/Header.astro`: encabezado y navegación.
- `src/components/Footer.astro`: pie de página.
- `src/layouts/Layout.astro`: estructura HTML y carga del CSS global.
- `src/styles/global.css`: estilos globales y diseño adaptable.
- `src/data.js`: lista de estudiantes y marca JUNAEB.

## Compartir por GitHub
1. Crea un repositorio en GitHub llamado `asistencia-curso-astro`.
2. En la terminal, dentro de esta carpeta, ejecuta:
   ```bash
   git init
   git add .
   git commit -m "Crear aplicación de asistencia con Astro"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/asistencia-curso-astro.git
   git push -u origin main
   ```
3. En GitHub, entra a **Settings → Collaborators** (o **Collaborators and teams**) y agrega a Miley Casanova, Adriana Morillo y a tu profesor usando sus nombres de usuario de GitHub.
4. Comparte el enlace del repositorio con el grupo. Reemplaza `TU-USUARIO` por tu usuario real de GitHub.

## Nota sobre los datos
La lista se guarda en el navegador de cada persona. Para que todas vean y editen una misma asistencia en tiempo real, se necesitaría agregar una base de datos compartida y autenticación. No se debe subir información sensible a un repositorio público.
