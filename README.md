# Mi Rincón de Paz — primera versión

Aplicación personal y bilingüe (español/eslovaco), diseñada para móvil y ordenador.

## Contenido
- Inicio con mensaje de calma.
- Pensamientos positivos en español y eslovaco.
- Ejercicio guiado de respiración de un minuto.
- Panel de naturaleza con paisajes ilustrados por colores (no necesita imágenes externas).
- Diario privado guardado en el almacenamiento local del navegador.
- Diseño adaptable a pantallas de móvil y ordenador.
- Archivos PWA para instalación en navegadores compatibles y caché básica offline.

## Probar en el ordenador
Abre `index.html` en un navegador moderno. Las funciones principales funcionan localmente. Para instalar la PWA y probar el modo offline, sírvela desde un sitio HTTPS (o desde localhost); algunos navegadores no permiten service workers al abrir un archivo directamente.

## Publicación gratuita mediante GitHub Pages
1. Crea o inicia sesión en GitHub.
2. Crea un repositorio nuevo, por ejemplo `mi-rincon-de-paz`.
3. Sube `index.html`, `manifest.webmanifest`, `sw.js` e `icon.svg` a la raíz del repositorio.
4. En Settings → Pages, activa la publicación desde la rama principal (`main`) y la carpeta raíz (`/root`).
5. GitHub Pages te mostrará la dirección pública. Ábrela en Android con Chrome y usa el menú del navegador → “Instalar aplicación” o “Añadir a pantalla de inicio” si aparece.
6. En ordenador, abre la misma dirección en un navegador compatible.

## Privacidad importante
El diario usa `localStorage` en el navegador del dispositivo. No se envía a un servidor, pero cualquier persona con acceso al mismo perfil del navegador podría verlo. Las notas no se sincronizan entre teléfono y ordenador y podrían borrarse al limpiar los datos del navegador. No introduzcas información muy sensible.

## Limitaciones de esta primera versión
- No hay cuenta, sincronización, notificaciones ni conexión con una IA.
- Las ilustraciones de naturaleza son fondos gráficos, no fotografías.
- La PWA no equivale por sí misma a una aplicación publicada en Google Play.
