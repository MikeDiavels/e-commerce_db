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
<br></br>
Origen de los datos: N/A
<br></br>
Descripción de consultas basicas.
<br></br>
Creacion de Base de datos<br></br>
<img width="953" height="501" alt="Db" src="https://github.com/user-attachments/assets/9e6349a5-72ca-46b2-b34e-6697417c503e" />
<br></br>
Inserción de productos.
<br></br>
<img width="955" height="502" alt="Insercion" src="https://github.com/user-attachments/assets/d84bee69-3373-4d6f-a9c8-21bc456871e2" />
<br></br>
Selección (Consultar todos los productos de una categoría):
<br></br>
<img width="959" height="502" alt="Seleccion" src="https://github.com/user-attachments/assets/9cfb31ee-7514-4e67-9150-b3b9d602261f" />
<br></br>
Actualización (Actualizar el precio de un producto):
<br></br>
<img width="959" height="505" alt="Actualizacion" src="https://github.com/user-attachments/assets/e0497d3e-be03-401d-b280-32f6f18cddef" />
<br></br>
Eliminación (Eliminar un producto por SKU):
<br></br>
<img width="959" height="502" alt="Eliminacion" src="https://github.com/user-attachments/assets/1cd90ddc-43e5-418a-9b78-ed32933e340a" />
BIG DATA - (202016911A_2034)
<br></br>
Tarea 4 - Almacenamiento y Consultas de Datos en Big Data
<br></br>
Grupo: 2
