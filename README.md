Muy buenos días profesora, en este caso, separé los ejercicios en 4 carpetas, en los cuales los ejercicios 4 y 5 están en un solo proyecto debido a que el ejercicio 5 es de pruebas.
Para ejecutar los proyectos basta con descomprimir la carpeta y abrirlos en intellij IDEA o el que gustes.
Luego de abrirlo lo ponemos a correr, obviamente con todo lo necesario instalado.
Debemos tener en cuenta que para mi computadora siempre ejecuta el proyecto en el puerto 8080.

entonces para validar el ejercicio 1, debemos abrir el localhost en el puerto 8080.

Para el ejercicio 2, del CRUD básico me ayudé de Postman, allí depende del tiempo de solicitud, agregamos, actualizamos, eliminamos o vemos un producto, de la siguiente manera:
Listar Productos (GET)
URL en postman: http://localhost:8080/api/productos
Obtener Producto por ID (GET)
URL en postman: http://localhost:8080/api/productos/1  (el 1 es el ID del registro)
Actualizar Producto (PUT)
URL en postman: http://localhost:8080/api/productos/1
Body (JSON):
json
{
    "nombre": "Laptop Gamer",
    "precio": 3000.50
}
Eliminar Producto (por ID) (DELETE)
URLen postman: http://localhost:8080/api/productos/1

para el ejercicio 3 basta con poner la url con la extensión de cada lenguaje como se nos explica en el parcial.

para el ejercicio 4 y 5, utilizaremos postman con un get a la URL para que nos muestre de forma reactiva y para la prueba, desde la terminal lanzaremos un mvn test para testear.
