**Caso de uso:** Modificación de eventos

_Actor_: Usuario (actor primario)

_Precondiciones_:

-   El organizador debe haber iniciado sesión en la aplicación.
-   El rol del usuario debe ser “Organizador”.
-   El usuario debe ser el creador del evento.

_Camino básico_

1. El sistema muestra al organizador los eventos que puede modificar.
2. El organizador selecciona el evento que desea modificar.
3. El sistema muestra el formulario “formularioEventos” con los valores de la configuración actual.
4. El organizador realiza las modificaciones necesarias.
5. El sistema valida la información, actualiza el evento y notifica a los usuarios suscritos.

_Camino alternativo_

5.a El organizador no completa todos los campos obligatorios o ingresa información inválida  
5.a.1 El sistema indica el problema señalando los campos erróneos.  
5.a.2 Vuelve al paso 4.

_Escenario de éxito_

El organizador modifica su evento exitosamente.

_Escenario de fracaso_

El organizador no completa los campos requeridos y cancela la modificación.
