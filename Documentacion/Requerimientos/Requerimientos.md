#

### Requerimientos funcionales

-   El sistema debe permitir a los usuarios registrarse.
-   El sistema debe permitir a los usuarios ingresar a la aplicación con sus credenciales.
-   El sistema debe permitir a los usuarios ingresar a la aplicación con sus redes sociales.
-   El sistema debe permitir a los usuarios recuperar su contraseña y/o nombre de usuario.
-   El sistema debe poder enviar mensajes de whatsapp con un código de un solo uso para recuperar su usuario.
-   El sistema debe permitir a los usuarios modificar sus datos personales.
-   El sistema debe permitir a los usuarios simples seleccionar intereses.
-   El sistema debe permitir a los usuarios organizadores crear y modificar eventos propios.
-   El sistema debe mostrar la cartelera de eventos.
-   El sistema debe poder realizar búsquedas de eventos por categorías/intereses, etc.
-   El sistema debe implementar la funcionalidad de suscripción para organizadores (promoción de eventos).
-   El sistema debe mostrar anuncios promocionados.

### Requerimientos funcionales futuros / posibles

-   El sistema debe facilitar el contacto entre el usuario normal y el organizador.
-   El sistema debe poder notificar al usuario con un recordatorio del evento al cual suscribió.
-   El sistema debe permitir la búsqueda de eventos privados mediante un código.
-   El sistema debe registrar un historial de eventos a los cuales el usuario asistió.
-   El sistema debe permitir la generación de reservas.
-   El sistema debe llevar la cuenta del total de usuarios ingresados en el día.

### Requerimientos no funcionales

-   El sistema implementará una base de datos SQL.
-   El sistema implementará NodeJS para el backend y React JS para el frontend.
-   La aplicación deberá ser compatible con Android e iOS.
-   El sistema debe ser escalable y estar disponible las 24 horas del día.
-   El sistema debe ser resistente a fallos.
-   El sistema debe presentar una UI agradable e intuitiva.
-   En todo momento el sistema preservará la seguridad de los datos sensibles de los usuarios.
-   El sistema implementará la API de MercadoPago para pequeñas transacciones de la aplicación (suscripciones).

### Requerimientos de dominio:

-   Cada usuario debe tener un nombre de usuario, contraseña, email, teléfono, nombre, apellido, rol, intereses e
    indicadores de suscripción.
-   Cada evento debe tener un título, descripción, capacidad, nombre del organizador, fecha y hora de inicio y finalización, localización (dirección y ciudad) e indicadores de gratuidad, periodicidad y si es o no promocionado.
-   Las localidades tendrán nombre, código postal y provincia.
-   Se implementaran los roles siguientes:
    -   Normal
    -   Organizador
-   La ubicación de los eventos debe ser mostrada en un mapa.
