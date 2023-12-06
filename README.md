## Descripcion del proyecto

Creacion de una plataforma e-commerce utilizando React + NodeJS + MongoDB y ExpressJS

## Indice
- Objetivos
- Requerimientos Minimos
- Librerias utilizadas
- Instalacion
- Autor

## Objetivos

- Manejo de rutas del lado del cliente (Frontend)
- Manejo de estados locales y globales (Frontend)
- Manejo de rutas en un servidor (Backend)
- Gestión y flujo de datos en MongoDB
- Seguridad (Autenticación y autorización)


## Requerimientos Minimos

- Un catálogo de productos
- Un carrito de compras
- Una pasarela de pago (puntualmente PayPal o MercadoPago, con la versión de pruebas)
- Autenticación (registro de usuario e inicio de sesión, a través de JWT)
- Autorización (zona privada donde el usuario pueda ver su perfil)

## Despliegue

- Frontend: ghpages
- Backend : render


## Librerias Opcionales

- MDBoostrap para la creacion de componentes

## Instalacion

`backend`

```shell

$ npm install
$ npm start

```

Luego crear las variables de entorno.

`.env`

```
MONGODB_URI=mongodb+srv://mongo:mongo@cluster0.jultqxv.mongodb.net/?retryWrites=true&w=majority
SECRET=MySecret
PORT=3005

```

## Autor

Felipe Quezada