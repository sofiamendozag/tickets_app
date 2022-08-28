# Tickets application
Aplicación que genera el coste desglosado de un ticket.

## Clases
### Product
La clase Product contiene los atributos y métodos de un producto. Los atributos indican el nombre, el precio y qué impuestos se le deben aplicar. Los métodos definidos en la clase son getters y setters de los atributos, los cuales permiten acceder o cambiar el valor de estos.

### Ticket
La clase Ticket contiene los atributos y métodos de un ticket. Los atributos que se determinan son la lista de productos, la suma total de los impuestos aplicados a los productos y el precio total de todos los productos. Los métodos definidos en esta clase son getProducts, que devuelve la lista de productos, toString, que devuelve una cadena con el contenido del ticket, y addProduct, que permite añadir un producto al ticket, habiéndole aplicado los impuestos necesarios a su precio, y actualiza el precio total y los impuestos totales del ticket.

### Main
La clase Main contiene un único método main, el cual ofrece un menú con distintas opciones: añadir productos a un ticket, generar el ticket y mostrar el coste desglosado, mostrar los resultados de la prueba del ejemplo y detener la ejecución.

## Casos de prueba
Pruebas unitarias realizadas de manera automática utilizando JUnit para probar el comportamiento de la mayor parte de los métodos de las clases Product y Ticket de forma aislada. 
En la clase Product, se comprueba que los métodos getters y setters funcionan correctamente. 
En la clase Ticket, se prueba el método getProduct y el método addProduct. Dentro de esta última prueba se comprueba el funcionamiento de distintos aspectos:
- Probar que los productos se añaden al ticket, para lo cual se comprueba que el número de productos que se han añadido es correcto
- Comprobar que se aplican los impuestos cuando es necesario, verificando que el precio final de los productos tras haber aplicado los impuestos es correcto
- Comprobar que se suman correctamente los valores de los impuestos totales y el precio total del ticket
