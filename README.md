# Proyecto de Ingenieria de Software: Digitalizacion de pedidos en restaurantes  
 ___
#### Descripción de la problematica
Debido a la coyuntura de la pandemia de Coronavirus y la reciente apertura económica los establecimientos de comida, tipo restaurante, tienen la necesidad de adaptarse a la nueva normativa que prima el distanciamiento entre las personas y el menor contacto físico que sea posible en todas las situaciones. 
Entonces, buscando apoyar dicho proceso desarrollaremos una aplicación web que le permita a los restaurantes recibir los pedidos de sus clientes que asistan de forma presencial al restaurante sin necesidad de que exista contacto alguno entre el personal del restaurante y los comensales.
___
### Equipo

- Erick J. Ruiz Acosta | T00054462  
_Desarrollador Backend._  
Responsabilidad: implementar interacción entre la base de datos y el fronted.

- Héctor F. Diaz Hernández | T00054643  
_Desarrollador Fronted._  
Responsabilidad: diseño y desarrollo de la interfaz de usuario.

- Isaac D. Castellar Usta | T00055440  
_Diseñador de Base de Datos._  
Responsabilidad: diseño e implementación de la base de datos.
___
### Requerimientos
**Funcionales:** 
- Gestionar la reserva.
- Gestionar pedidos.
- Gestionar base de datos.
- Verificación de entrada.
- Verificación de pedidos.

**Requerimientos no funcionales:**
- El sistema debe funcionar entre 11:00 AM a 10:30PM.
- Gestionar perfiles de usuarios (Clientes y empleados).

**Requerimientos de sistema**
- Gestionar base de datos del usuario.
- Gestión de método de pago.
- Administrar rutas de pedidos.
- Implementación de sistema GPS.
- Administrar tiempo estimado de la orden.

**Requerimientos de usuario:**
- Listado de trabajadores.
- Método de pago (Cliente).
___
### Diagrama BPN de alto nivel
![Diagrama BPN de alto nivel](https://raw.githubusercontent.com/Tr3you/Digitalizacion-de-pedidos-en-restaurantes/main/PS%20BPN%20Alto%20nivel.png)
___
### Diagramas de casos de uso
![Diagrama de casos de uso](https://raw.githubusercontent.com/Tr3you/Digitalizacion-de-pedidos-en-restaurantes/main/PS%20Casos%20de%20uso.png)
___
### Descripción de un caso de uso de prioridad alta.
Código: CCP-00001  
Nombre: IU  
Actores: Cliente  
Descripción: cuando el cliente ingrese a la página tendrá la opción de consumir en restaurante o hacer pedido a domicilio.  
Precondición: entrar a la página.  
Postcondición: selección de acción a realizar.  

Código: CCP-00010  
Nombre: Restaurante  
Actores: Trabajadores  
Descripción: Los trabajadores como Mesero, Repartidor y recepcionista podrán planificar y organizar el listado de todo tipo sea en el restaurante y la ubicación de la mesa o por domicilio y dirección a donde llegara el pedido  
Precondición: Entrar a  la página como trabajadores y su cargo  
Postcondición: gestión de pedidos   

Código: CCP-000100  
Nombre: Platos  
Actores: Chef y clientes  
Descripción: los clientes podrán escoger los platos deseados con las condiciones que ellos deseen al confirmar esto el personal de la cocina conocerá los deseos del comensal e iniciaran a preparar dicho pedido.  
Precondición: confirmar pedido.  
Postcondición: entrega de orden

Código: CPP-010000.  
Nombre: Envió  
Actores: Repartidor  
Descripción: el apartado par domicilios esta condiciona a que los clientes escojan la opción “hacer pedido a domicilio” una ves esto podrán escoger sus platillos y confirmar el pedido el repartidor enviara dos mensajes uno al momento de salir del restaurante y otro al llegar a la dirección dando a si un tiempo estimado de entrega.  
Precondición: Pedido a domicilio  
Postcondición: pedido entregado 

Código: CCP-100000.  
Nombre: Pago  
Actores: clientes  
Descripción: al terminar con el consumo de sus alimentos el cliente podrá proceder con el pago de lo consumido en el restaurante o si este pidió un domisilio pagara al momento de este llegar a su residencia con el método de pago más conveniente para dicho cliente.  
Precondición: haber hecho algún pedido.  
Postcondición: pago total de lo consumido. 
___
### Diagrama de componentes
![Diagrama de componentes](https://github.com/Tr3you/Digitalizacion-de-pedidos-en-restaurantes/blob/main/Diagrama%20de%20componentes.jpg)
___
### Diagrama de clases

![Diagrama de casos de uso](https://raw.githubusercontent.com/Tr3you/Digitalizacion-de-pedidos-en-restaurantes/main/Diagrama%20de%20clases%20(Entrega%20preliminar%20software).jpeg)

### Diagrama de secuencia

![Diagrama de casos de uso](https://github.com/Tr3you/Digitalizacion-de-pedidos-en-restaurantes/blob/main/Diagrama%20de%20secuencia.png)
