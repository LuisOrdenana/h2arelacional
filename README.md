# Proyecto de Base de Datos Hotelera

Este proyecto se centra en implementar una base de datos relacional utilizando PostgreSQL para gestionar datos de hoteles. A continuación, se describe el proceso paso a paso:

## Configuración de la Base de Datos

- **Configuración del `application.properties`:** En lugar de usar la base de datos H2 en memoria, configuramos nuestra aplicación para conectarse a una base de datos PostgreSQL. Asegúrate de proporcionar las credenciales y la URL de conexión adecuadas.

![image](https://github.com/LuisOrdenana/h2arelacional/assets/170282412/5aff9ada-305f-4a89-b9ba-5a392873f9c8)


- **Eliminación de la tabla anterior (si existe):** Antes de crear la nueva tabla, verificamos si la tabla anterior existe y, si es así, la eliminamos para evitar conflictos.
- **Creación de la tabla `hotel`:** Creamos una nueva tabla llamada `hotel` con las siguientes columnas:
   - `id`: Identificador único del hotel.
   - `name`: Nombre del hotel.
   - `address`: Dirección del hotel.
  
![image](https://github.com/LuisOrdenana/h2arelacional/assets/170282412/3e603946-616c-42a3-b8a9-77b5064f320e)






- **Visualización en pgAdmin:** Utilizamos pgAdmin para verificar que la tabla `hotel` se ha creado correctamente con todas sus características.


![image](https://github.com/LuisOrdenana/h2arelacional/assets/170282412/cc07951c-cdbe-4104-85ce-b421d593bb26)


## Integración con Postman

Para agregar datos a la base de datos, utilizamos Postman para enviar solicitudes HTTP. Esto nos permite insertar registros de hoteles directamente desde la interfaz de usuario de Postman. La integración efectiva entre el cliente de API y la base de datos PostgreSQL garantiza una gestión eficiente y la persistencia de los datos del sistema hotelero.
