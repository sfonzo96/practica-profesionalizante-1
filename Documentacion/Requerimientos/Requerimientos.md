#

### Requerimientos funcionales

-   El sistema debe permitir a los usuarios registrarse.
-   El sistema debe permitir a los usuarios ingresar a la aplicación con sus credenciales.
-   El sistema debe permitir a los usuarios ingresar a la aplicación con sus redes sociales.
-   El sistema debe permitir a los usuarios recuperar su contraseña y/o nombre de usuario en caso de olvidarse.
-   El sistema debe poder enviar mensajes de whatsapp con un código de un solo uso para recuperar su usuario.
-   El sistema debe permitir a los usuarios modificar sus datos personales.
-   El sistema debe permitir a los usuarios simples seleccionar intereses.
-   El sistema debe permitir a los usuarios organizadores registrar y modificar eventos propios.
-   El sistema debe mostrar la cartelera de eventos.
-   El sistema debe mostrar al usuario los eventos a los que se ha registrado.
-   El sistema debe poder realizar búsquedas de eventos por nombre, organizador, fecha, etc.
-   El sistema debe poder filtrar y ordenar los eventos de acuerdo a su costo, relevancia, a su fecha, por defecto se
    ordenarán de acuerdo a los gustos del usuario (gratuito o no), por localidad.
-   El sistema debe implementar la funcionalidad de suscripción para organizadores.
-   El sistema debe mostrar anuncios promocionados.
-   El sistema debe llevar la cuenta del total de usuarios ingresados en el día.

### Requerimientos funcionales futuros / posibles

-   El sistema debe facilitar el contacto entre el usuario común y el anunciante (interno, mail, whatsapp, etc.)
-   El sistema debe poder notificar al usuario con un recordatorio del evento al cual suscribió.
-   El sistema debe permitir la búsqueda de eventos privados mediante un código.
-   El sistema debe registrar un historial de eventos a los cuales el usuario asistió.
-   El sistema debe permitir la generación de reservas.

### Requerimientos no funcionales

-   El sistema implementará una base de datos SQL.
-   El sistema implementará NodeJS para el backend y React JS para el frontend.
-   La aplicación deberá ser compatible con Android e iOS.
-   El sistema debe ser escalable y estar disponible las 24 horas del día.
-   El sistema debe ser resistente a fallos.
-   El sistema debe presentar una UI agradable e intuitiva.
-   En todo momento el sistema preservará la seguridad de los datos sensibles de los usuarios.
-   El sistema implementará la API de MercadoPago para pequeñas transacciones de la aplicación.

### Requerimientos de dominio:

-   Cada usuario debe tener un nombre de usuario, contraseña, email, teléfono, nombre, apellido, rol, intereses e
    indicadores de suscripción.
-   Se implementaran los roles siguientes:
    -   Normal
    -   Organizador
-   Los eventos tendrán título, descripción, capacidad, nombre del organizador, fecha, horas de inicio y finalización,
    localización (dirección y localidad) e indicadores de gratuidad, periodicidad y privacidad.
-   Las localidades tendrán nombre, código postal y provincia.
-   Los eventos deben poder caracterizarse según distintas categorías y de acuerdo a si tienen o no un costo asociado.
-   La ubicación de los eventos debe ser mostrada en un mapa.
