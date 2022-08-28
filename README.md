# tickets_app
Aplicación que genera el coste desglosado de un ticket

# Clases
## Product
Esta clase contiene los atributos y métodos de un producto. Los atributos indican el nombre, el precio y qué impuestos se le deben aplicar. Los métodos definidos en la clase son getters y setters de los atributos, los cuales permiten acceder o cambiar el valor de estos.

## Ticket
Esta clase contiene los atributos y métodos de un ticket. Los atributos que se determinan son la lista de productos, la suma total de los impuestos aplicados a los productos y el precio total de todos los productos. Los métodos definidos en esta clase son getProducts, que devuelve la lista de productos, toString, que devuelve una cadena con el contenido del ticket, y addProduct, que permite añadir un producto al ticket, habiéndole aplicado los impuestos necesarios a su precio, y actualiza el precio total y los impuestos totales del ticket.

## Main
Esta clase contiene un único método main, el cual ofrece un menú con distintas opciones: añadir productos a un ticket, generar el ticket y mostrar el coste desglosado, mostrar los resultados de la prueba del ejemplo y detener la ejecución.

# Casos de prueba
Pruebas unitarias para probar la mayor parte de los métodos de las clases Product y Ticket.
