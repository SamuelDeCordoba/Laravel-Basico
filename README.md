Ejercicio 1 - Laravel Básico: Gestión de Productos
Descripción
Este ejercicio consiste en crear una estructura básica en Laravel para gestionar productos. Incluye la creación de una migración para la tabla de productos, un modelo Eloquent, una ruta API y un controlador que devuelve los productos en formato JSON.

Qué se va a hacer
Migración: Crear una tabla 'productos' con los campos: id, nombre, precio y stock

Modelo: Crear un modelo Eloquent 'Producto' para interactuar con la tabla

Ruta: Definir una ruta que responda a las solicitudes HTTP

Controlador: Crear un controlador con método index() que devuelva todos los productos en formato JSON

Estructura de la tabla productos
Campo	Tipo	Descripción
id	bigIncrements	Identificador único
nombre	string	Nombre del producto
precio	decimal	Precio del producto
stock	integer	Cantidad en inventario
Endpoint resultante
Método: GET

URL: /api/productos (o similar según configuración)

Respuesta: JSON con listado de todos los productos
