# Challenge Meetups by nacho almiron
La app se basa en la gestión de historias de usuarios. La web permite la creación, eliminación, subscripción y registro de asistencia a reuniones (meetups). La creación de una meetup te permite ver el clima del lugar en la fecha que se planifique, así como también la cantidad de cerveza que deberían comprar para sus invitados. 

### Como ejecutar la app
Descargar el proyecto. 
Ejecutar los comandos npm: 
    1) npm install
    2) npm run start

### Autenticación
A continuación, se adjuntan los nombres de usuarios habilitados a usar el sistema, con sus respectivos roles

nacho - admin
rodrigo - user
mauro - admin
carolina - user

### Consideraciones
1) Si el usuario esta suscripto (es un invitado) no se podra suscribir de nuevo, el boton estará disabled.
Lo mismo pasa con los checkin

### Stack tecnologico
Se desarrolló únicamente la parte de frontend, usando React, Redux y Material UI. Por tal motivo al momento de hacer post se perderan todos las historias guardadas. 

### Arquitectura 
La arquitectura implementa el patrón flu, a traves de Redux. La estructura se basa en actions, reducers, selectors, middleware y store. El middleware se encarga de interceptar las peticiones REST y gestionarlas según se requiera. 

### Features
WebApp de reuniones
React/Redux
Login/Logout
Roles
Multiidioma - i18n
Test - jtest
Responsive (mobile firts) - Material UI
Darkmode

### Ejecutar los test
Los test de la app se encuentran en el archivo /App.test.js
Ejecutar el comando npm:
    1) npm test
