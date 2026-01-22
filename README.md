# RPM Frontend

Frontend del sistema RPM (Repositorio de Productos del Mercado).

## Estructura del Proyecto

- `Administrador/` - Interfaz de administración
- `Comerciante/` - Interfaz para comerciantes
- `Natural/` - Interfaz para usuarios naturales
- `PrestadorServicios/` - Interfaz para prestadores de servicios
- `Publicaciones/` - Gestión de publicaciones
- `General/` - Componentes generales compartidos
- `JS/` - Scripts JavaScript
- `Imagen/`, `image/`, `imagen/` - Recursos de imágenes

## Configuración para Backend

Este frontend está preparado para conectarse a un backend separado. Para configurar la conexión:

1. Copia `.env.example` a `.env`
2. Configura la URL del backend en tu archivo `.env`:
   ```
   BACKEND_URL=https://tu-backend-url.com
   ```
3. Asegúrate de que el backend tenga configurado CORS para aceptar peticiones desde este frontend

## Archivos Importantes

- `package.json` - Contiene las dependencias del proyecto original (backend incluido)
- `.env.example` - Plantilla de configuración de variables de entorno
- `.gitignore` - Archivos a ignorar en el control de versiones

## Nota

Este repositorio contiene solo el frontend. El backend debe estar en un repositorio separado para mantener una arquitectura desacoplada.
