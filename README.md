# Backend Ecommerce - Proyecto final Programacion Backend Coderhouse - Moure Gonzalo
## _Una API RESTFULL que nos brinda el backend para un ecommerce_

## Tecnologia
#### Backend
- NodeJS - Version 14.17.6 o superior 
- Express - Version 4.17.3
- Sequelize - Version 6.15.1
- mysql2 - Version 2.3.3
- jsonwebtoken - Version 8.5.1
- Nodemailer - Version 6.7.2
- bcrypt - Version 5.0.1
- Cors - Version 2.8.5
- Dotenv - Version 12.0.3

## Instalacion

Esta app require [Node.js](https://nodejs.org/)

Instalar las dependencias antes de inicar el servidor, tambien puedes sembrar la DB para el test

```sh
npm i
npm start
```

## El archivo .env requiere
- USERPASSMONGO = 'Usuario y password para MongoDB SAAS'  
- NODE_ENV = 'El entorno de desarollo en el que iniciara el servidor, puede ser test, development ó production'  
- SESSION_SECRET = 'Una palabra secreta para las sesiones'  
- NODEMMAILER_USER = 'Un email de gmail'  
- NODEMAILER_PASS = 'La contraseña del mail'
- TWILIO_SID = 'sid de twilio'
- TWILIO_TOKEN = 'token de twilio'

## Documentacion
https://documenter.getpostman.com/view/17626076/UVsJxSwD#854444aa-2164-4a62-8a7a-48f822ecd6cd
- En la documentacion podran ver ejemplos de los endpoints
