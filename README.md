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
Por razones de seguridad, se ha eliminado la clave de acceso de AppSheet del código fuente. Para que el catálogo funcione correctamente, debes:
1. Abrir `index.html`.
2. Buscar la línea `const APPSHEET_ACCESS_KEY = 'TU_CLAVE_AQUI';`.
3. Reemplazar `'TU_CLAVE_AQUI'` por tu clave real de AppSheet.

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
