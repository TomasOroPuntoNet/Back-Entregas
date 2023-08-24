#                                                              CURSO BACKEND CODERHOUSE
# DESAFIO-4

## CONSIGNA

- Configurar nuestro proyecto para que trabaje con Handlebars y websocket

### ASPECTOS A INCLUIR


- Configurar el servidor para integrar el motor de plantillas Handlebars e instalar un servidor de socket.io al mismo.
- Crear una vista “home.handlebars” la cual contenga una lista de todos los productos agregados hasta el momento
- Además, crear una vista “realTimeProducts.handlebars”, la cual vivirá en el endpoint “/realtimeproducts” en nuestro views router, ésta contendrá la misma lista de productos, sin embargo, ésta trabajará con websockets:
    * Al trabajar con websockets, cada vez que creemos un producto nuevo, o bien cada vez que eliminemos un producto, se debe actualizar automáticamente en dicha vista la lista.
db.ejercicio.insertMany[{ nombre:"Jhoceliz", apellido:"Gonzalez", curso:"Backend", edad: 20, correo:"jhoceliz@gmail.com", genero:"Femenino" },{ nombre:"Jhon", apellido:"Lopez", curso:"Frontend", edad: 5, correo:"jhon@gmail.com", genero:"Masculino" },{ nombre:"Sandra", apellido:"Garcia", curso:"Backend", edad: 30, correo:"sandra@gmail.com", genero:"Femenino" },{ nombre:"Ivan", apellido:"Ramirez", curso:"Frontend", edad: 25, correo:"ivan@gmail.com", genero:"Masculino" },{ nombre:"Luis", apellido:"Menendez", curso:"Backend" }]