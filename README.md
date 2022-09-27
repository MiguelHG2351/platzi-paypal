# platzi-store
Curso de pagos en linea - Platzi 💚

## Setup de proyecto

`$ npm install`
`$ npm run setup`

## Correr el proyecto

`$ DEBUG=platzi-store:* npm start`

El proyecto corre localmente en [localhost:3000](http://localhost:3000/)


## Qué son los pagos online?

Son los que se realizan vía internet usando un servicio de procesamiento de pago

No se limitan a usar tarjetas de credito, también pueden ser físico tradicional como los boletos o oxxo en México.

Los pagos tradicional es el que llevas dinero a la tienda y te entrega el producto y el vendedor lo lleva al banco

En línea requiere de un 3er intermediario que es el procesador de pagos.

## Qué opciones existen para aceptar pagos en línea?

Existen varias opciones para aceptar pagos en línea, pero las más populares son:

- Stripe
- PayPal
- MercadoPago
- PayU

- Paypal cobra 2.9% + 0.3USD

- PayU: Que te obliga a darte de alta como empresa antes de comenzar a trabajar.

- Stripe: Que solo está disponible en Mexico y Brasil en modo de prueba.

- Mercado pago: que limita las herramientas dependiendo del país.

Otra forma de vender es mediante marketplaces (Amazon o mercado libre) pero estos tienen limitantes (una es que no te dan acceso a la lista de clientes).

## Librerias del curso

- SQLite3: Nuestro driver generativo de DB

- HttpError: Herramienta generativa de errores HTTP para express

- Debug: Pequeña herramienta para observar el tracking generado por Nodejs

- ejs: Motor de plantillas para generar HTML

- cookie-parser: Herramienta para parsear cookies de los headers

- Express: Framework para Nodejs

- Sequelize: ORM para NodeJS

- Sequelize CLI: Herramienta para generar modelos y migraciones
