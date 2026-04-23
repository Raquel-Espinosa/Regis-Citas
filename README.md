# CEDIS/DOCK — Sistema de Citas de Proveedores

App web para gestión de citas de proveedores en centro de distribución.

## Stack
- Frontend: HTML + CSS + JS (sin frameworks)
- Base de datos: Google Sheets vía Apps Script
- Correos: EmailJS
- Hosting: GitHub Pages

## Configuración
1. Clonar este repositorio
2. Crear Apps Script en Google Sheets (ver `/docs/setup-sheets.md`)
3. Configurar APPS_SCRIPT_URL en index.html línea 1 del bloque `<script>`
4. Configurar EmailJS Public Key en la sección de Correos del panel admin
5. Push a main → deploy automático en GitHub Pages

## Accesos de demo
- Admin: admin@cedis.mx / admin123
- Proveedor: sigma@proveedor.mx / sigma123
