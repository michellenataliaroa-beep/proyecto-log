# Proyecto Login - SENA GA7-220501096

Actividades: AA4-EV03 (front-end) y AA5-EV01 (servicio web de registro e inicio de sesión).

## Cómo ejecutarlo
1. Instala Node.js (LTS) desde https://nodejs.org
2. Abre esta carpeta en Visual Studio Code (Archivo > Abrir carpeta)
3. Abre la terminal (Ctrl + ñ) y ejecuta:
   npm install
   npm start
4. Abre http://localhost:3000 en el navegador

## Servicios
- POST /api/registro  { usuario, contrasena }
- POST /api/login     { usuario, contrasena }

## Versionamiento
git init
git add .
git commit -m "Primer commit"
## Pruebas de la API (AA5-EV02)
Importa en Postman el archivo pruebas-postman/AA5-EV02_proyecto-login.postman_collection.json
y ejecuta las 6 peticiones en orden con el servidor corriendo (npm start).
