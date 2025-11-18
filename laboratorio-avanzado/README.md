## Ejecutar

- Usar libre preview de microsoft o similar

## Estructura del Proyecto

- Contiene el archivo **index.css**, generado automáticamente a partir del código Sass.

- Incluye la estructura completa de archivos y carpetas sass organizada por **componentes**, **media queries**

- El archivo principal **index.scss** se encarga de importar todos los demás archivos SCSS del proyecto.

- **index.html**  
  Importa el archivo compilado **/css/index.css**.

## Compilación de Sass

El proyecto utiliza un script ya configurado en el archivo `package.json` para compilar Sass a CSS:

"dev": "sass src/scss/index.scss src/css/index.css --watch" (npm run dev personalizado)
