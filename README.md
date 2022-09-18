# Userlogs Middleware

App creada para practicar el uso de middlewares

## Objetivo

Registrar el ingreso a cualquier ruta del sistema. Cada registro deberá quedar:
**El usuario ingresó a la ruta: **<nombre_de_la_ruta>

Para ello será necesario que tengamos una carpeta denominada **/middlewares** y, dentro de ella, el middleware llamado: _userLogs.js_. Este middleware se usará en toda la aplicación, por lo tanto deberemos implementarlo según corresponda. Asimismo, podremos crear las rutas que estimemos necesarias para probar el middleware.
Importante: el archivo _userLogs.txt_ deberá ir almacenando TODAS las rutas a las que accede el usuario. El mismo deberá verse así:
**
El usuario ingresó a la ruta: /services
El usuario ingresó a la ruta: /services/design
El usuario ingresó a la ruta: /
**

Y así sucesivamente con el resto de las rutas.
