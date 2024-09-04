**Caso de uso:** Modificación de eventos

_Actor_: Usuario (actor primario)

_Precondiciones_:

-   El usuario debe haber iniciado sesión en la aplicación.
-   El rol del usuario debe ser “Organizador”.

_Camino básico_:

1. El usuario solicita crear un evento.
2. El sistema muestra al usuario el formulario “formularioEventos”.
3. El usuario completa el formulario y confirma la creación del evento.
4. El sistema valida la información proporcionada por el usuario, crea el evento y le notifica mediante un correo.

_Camino alternativo_:

4.a El organizador no completa todos los campos obligatorios o ingresa información inválida.  
4.a.1 El sistema indica el problema señalando los campos erróneos.  
4.a.2 Vuelve al paso 3.

_Escenario de éxito_:  
El organizador crea su evento exitosamente.

_Escenario de fracaso_:  
El organizador no completa los campos requeridos y desiste en su creación.
