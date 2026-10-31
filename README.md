# Rider Service - Landing Page

Landing page oficial de descarga y presentación de la app **Rider Service**, desarrollada como proyecto en el marco de la cursada de Aplicaciones Móviles en la Universidad Nacional de Pilar (UNPilar).

Repositorio de la aplicación móvil: [lightbblue/driver-service](https://github.com/lightbblue/driver-service)

## Estructura del proyecto

- `index.html`: Estructura principal de la landing page con Tailwind CSS (vía CDN) y JavaScript para diálogos y descarga.
- `styles.css`: Reglas de estilos complementarias (paleta de colores, modales accesibles y tipografía legal).
- `assets/`: Recursos estáticos e imágenes de la app.

## Cómo verla localmente

Solo necesitás abrir `index.html` en cualquier navegador web. Se requiere conexión a internet para cargar Tailwind CSS desde la CDN.

## Cómo configurar

Al final de `index.html`, dentro de la etiqueta `<script>`, podés configurar las siguientes variables:

- `APK_URL`: Enlace directo de descarga del archivo APK (cuando esté disponible). Mientras esté vacío (`""`), los botones mostrarán automáticamente "Próximamente" y quedarán deshabilitados.
- `CONTACT_EMAIL`: Dirección de correo electrónico de contacto del equipo (`jstachioni@gmail.com`).

## Despliegue en Vercel

1. Importar el repositorio en Vercel (*Add New → Project*).
2. Seleccionar el preset **Other**.
3. No requiere comando de build (*Build Command* vacío) ni directorio de salida especial.
4. Desplegar (*Deploy*).

## Licencia

Este proyecto está bajo la Licencia [MIT](LICENSE).
