En este repositorio se encuentra la base de datos de:
Catálogo de comercio electrónico (e-commerce)

Catálogo de comercio electrónico orientado a la administración de productos, pedidos y clientes dentro de una plataforma digital. La base de datos tiene como propósito almacenar información relacionada con los artículos disponibles, las compras realizadas y los usuarios registrados, facilitando la gestión de inventario y el registro de transacciones. Entre las operaciones principales se incluyen la búsqueda de productos por SKU, nombre o categoría, el filtrado por rango de precios, la consulta de existencias y la generación de resúmenes de ventas que permitan analizar el comportamiento del catálogo.
El desarrollo del caso se centra en la creación y manipulación de una base de datos implementada en MongoDB, utilizando datos de prueba representativos. Se contemplan procesos de inserción, actualización, consulta y eliminación de documentos, así como operaciones de agregación orientadas al cálculo de estadísticas básicas. Este modelo de base de datos desea representar de manera sencilla la estructura funcional de un sistema de comercio electrónico, priorizando la claridad, la organización y la eficiencia en el manejo de la información.
Diseño de la base de datos
La base de datos e-commerce_db se compone de tres colecciones principales: productos, que almacena la información del catálogo de artículos disponibles; clientes, que registra los datos de los usuarios del sistema; y pedidos, que gestiona las órdenes de compra estableciendo referencias tanto a los productos adquiridos como al cliente correspondiente, donde cada colección contiene documentos individuales con campos y tipos de datos coherentes según su función dentro del modelo.
<br></br>
Tabla 1
Colección: productos
<br></br>
<img width="640" height="247" alt="1" src="https://github.com/user-attachments/assets/2025db3f-42c8-4f7a-8bc5-57c1aaf627c1" />
<br></br>
Tabla 2
<br></br>
Colección: clientes
<br></br>
<img width="641" height="199" alt="2" src="https://github.com/user-attachments/assets/14fe186c-832a-4618-8a3b-0aaac76d5e73" />
<br></br>
Tabla 3
<br></br>
Colección: pedidos
<br></br>
<img width="639" height="288" alt="3" src="https://github.com/user-attachments/assets/0a9c0224-da72-46ba-81b7-a5f912bafff2" />
<br></br>
Para esta base de datos se uso:<br></br>
MongoDB Server 8.2<br></br>
para la gestión se uso:<br></br>
MongoDB Compass 1.48.2
<br></br>
Se exporto el contenido de los archivos que se encuentran en /Datos/
