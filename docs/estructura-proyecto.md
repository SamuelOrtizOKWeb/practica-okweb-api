# Estructura del proyecto practica-okweb

- `docs/` - Documentación general del proyecto y archivos de referencia.
- `practica-okweb-api/` - Backend Django que contiene la lógica del servidor y las apps.
  - `config/` - Configuración principal de Django: `settings.py`, `urls.py`, `wsgi.py`, `asgi.py`.
  - `docs/` - Documentación específica del backend API.
  - `manage.py` - Script de administración de Django.
  - `db.sqlite3` - Base de datos SQLite local del proyecto.
  - `sesiones/` - App de Django para gestionar sesiones, planes y bitácoras.
    - `bitacoras/` - Documentos y registros de bitácora de sesiones.
    - `planes/` - Planes asociados a las sesiones.
  - `usuarios/` - App de Django para el manejo de usuarios.
  - `venv/` - Entorno virtual de Python del proyecto (no parte del código fuente principal).
- `practica-okweb-app/` - Proyecto frontend o aplicación cliente.
  - `docs/` - Documentación específica de la app frontend.
  - `sesiones/` - Material relacionado con sesiones dentro de la app.
- `README.md` - Información general del proyecto y guía inicial.
