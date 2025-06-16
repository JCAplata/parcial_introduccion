# parcial_introduccion
# diagrama conceptual
## explicacion
las entidades que usare seran:
-vendedor
-cliente
-informacion del libro
-metodo de pago
-pedido
-detalles del pedido
El vendedor interactuara con el pedido la cual este tiene asocciado a (cliente, metodo de pago y detalle del pedido).
Detalle del pedido tiene a (informacion del libro)

# diagrama UML
## explicacion
aca ya entramos a detalle de lo que lleva cada entidad.
* vendedor tiene:
-nombre
* cliente tiene:
  - documento
  - nombre
  - telefono
  - direccion
  - correo
* informacion de libro tiene:
  - isbn
  - titulo
  - autor
  - fecha publicado
  - editorial
  - categoria
  - precio
  - stock
* pedido tiene:
  - id cliente
  - id vendedor
  - fecha
  - id metodo
* detalle de pedido tiene:
  - id del pedido
  - isbn
  - cantidad
  - precio unitario
* metodo de pago tiene:
  - efectivo
  - tarjeta
  - paypal

LO SIENTO PROFESOR NO ME ALCANZO EL TIEMPO PARA SEGUIR LA EXPLICACION

