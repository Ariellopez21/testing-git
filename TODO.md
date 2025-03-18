Inicializa un repositorio, creando un archivo .gitignore que excluya el archivo TODO.md. Luego copia el archivo con las instrucciones dentro del repositorio con el nombre TODO.md.
Crea un primer commit con una página básica en HTML (index.html):

<!DOCTYPE html>
<html>
  <head>
    <title>MyStore - Inicio</title>
  </head>
  <body>
    <h1>Bienvenido a TechStore</h1>
  </body>
</html>

Crea la rama feature/products y añade un commit añadiendo el archivo products.html, que presenta una lista de productos:

<!DOCTYPE html>
<html>
  <head>
    <title>MyStore - Productos</title>
  </head>
  <body>
    <h1>Nuestros productos</h1>
    <ul>
      <li>Laptop</li>
      <li>Teclado mecánico</li>
      <li>Mouse gamer</li>
    </ul>
  </body>
</html>

Cambia a la rama main y luego crea la rama feature/footer. Añade un commit añadiendo un pie al archivo index.html:

<footer>
  <p>&copy; 2025 My Store</p>
</footer>

Cambia a la rama main y fusiona las ramas feature/products y feature/footer en ella.
En la rama main, añade un nuevo commit con un nuevo encabezado a la lista de productos:

<h2>Nuestros productos en oferta</h1>

Cambia a la rama feature/products y añade un nuevo commit con un nuevo producto a la lista:

<li>Monitor curvo</li>

Luego añade otro commit con un nuevo encabezado al final de la lista:

<h2>Descubre nuestros nuevos productos</h2>

Cambia a la rama main y fusiona la rama feature/products en ella. Resuelve los conflictos si es necesario.
Crea un tag llamado v1.0 cuando hayas fusionado todas las ramas y hayas verificado que todo funcionó correctamente.
