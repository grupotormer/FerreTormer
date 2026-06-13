# Catálogo - Ferre Tormer

Este es el proyecto del catálogo web para la ferretería **Ferre Tormer**. 

## Características
- **Catálogo de productos:** Visualización de productos con stock y precios.
- **Buscador:** Filtrado de productos por nombre o categoría.
- **Carrito de compras:** Gestión de pedidos locales.
- **Integración con AppSheet:** Envío de pedidos directamente a una base de datos gestionada.
- **Secciones adicionales:** Información sobre la empresa, postulación de empleo y políticas de servicio.

## Tecnologías utilizadas
- HTML5
- CSS3 (Tailwind CSS vía CDN)
- JavaScript (Vanilla JS)
- Font Awesome para iconos

## Configuración de Seguridad
Por razones de seguridad, las claves de AppSheet se han movido a un archivo externo que no se sube al repositorio.

Para configurar las claves:
1. Localiza la carpeta `config/`.
2. Verás un archivo llamado `config.example.js`.
3. Crea una copia de ese archivo y renómbralo a `config.js`.
4. Abre `config/config.js` y reemplaza los valores de `APPSHEET_APP_ID` y `APPSHEET_ACCESS_KEY` con tus credenciales reales.

El archivo `config/config.js` ya está incluido en el `.gitignore` para evitar que tus claves se publiquen accidentalmente en GitHub.

## Cómo visualizar el proyecto
Para ver el catálogo localmente, simplemente abre el archivo `index.html` en cualquier navegador web moderno.

## Cómo subir este proyecto a GitHub
Si deseas subir cambios adicionales a tu propio repositorio, sigue estos pasos desde tu terminal:

1. **Inicializar Git** (si no lo has hecho):
   ```bash
   git init
   ```
2. **Añadir archivos:**
   ```bash
   git add .
   ```
3. **Crear un commit:**
   ```bash
   git commit -m "Mi primer commit"
   ```
4. **Conectar con GitHub:**
   ```bash
   git remote add origin https://github.com/TU_USUARIO/TU_REPOSITORIO.git
   ```
5. **Subir cambios:**
   ```bash
   git push -u origin main
   ```

> **Nota:** El logo de la empresa (`Logoferre.png`) debe estar presente en la misma carpeta que el archivo HTML para visualizarse correctamente.
