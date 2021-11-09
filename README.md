## Front-end challenge

#### Resumen
El objetivo de este challenge es crear un pequeña aplicación en React.
El candidato deberá usar herramientas básicas como javascript y git para conectarse, leer, procesar y mostrar información.

#### Detalle
La aplicación constará de dos vistas las cuales se accederán de una barra de navegación (horizontal o vertical según preferencia del candidato), los items de dicha barra son: "**Cotización**" y "**Historial**"

##### 1. Cotización:
En esta vista se mostrará el valor (en ARS) del preció del Dolar (oficial y blue) y del Euro.
Debajo deberá encontrarse una calculadora, donde el usuario ingrese un monto y esta haga la conversión a cuantos dolares/euros es.

##### 2. Historial
En esta vista se podrá visualizar un gráfico histórico con el precio del dolar en el trascurso del tiempo.

#### API
La fuente de donde se sacará la información es de la API pública de [bluelytics](https://bluelytics.com.ar/).

URL Base 

    https://api.bluelytics.com.ar

Última cotización

    GET /v2/latest

Histórico

    GET /v2/evolution.json


#### Envio
Forkear este repositorio y enviar un pull request con tu código.
Nos pondremos en contacto para hablar sobre la revisión del challenge.

#### Puntos extras

 - Responsive design
 - Utilizar una librería de UI (ant.design, rsuite, etc)
 - Para gráficos utilizar Highcharts/Highstock
 - Basarse en [la guía de javascript de Airbnb](https://github.com/airbnb/javascript) para mantener un código prolijo.
 - Uso de Hooks y programación funcional
 - Modularización de código
 - Utilizar Next.js


Contactarse a hola@waia.ar o npaez@waia.ar si necesita más detalles.
