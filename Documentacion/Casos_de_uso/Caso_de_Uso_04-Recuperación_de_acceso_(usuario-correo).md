**Caso de uso**: Recuperación de usuario

_Actor_: Usuario (Actor primario)

_Precondición:_ El usuario debe estar registrado en la aplicación.

_Camino básico_

1. El usuario solicita la recuperación de su usuario.
2. El sistema redirige al usuario a una vista con un formulario que solicita su número de teléfono.
3. El usuario ingresa su número de teléfono.
4. El sistema valida el número ingresado, envía a su WhatsApp un código de 6 dígitos (validez de una hora) al número de
   teléfono asociado y redirige al usuario a una nueva vista con un nuevo formulario en el que ingresará dicho código.
5. El usuario ingresa el código recibido.
6. El sistema verifica la validez del código y redirige al usuario a una nueva vista donde puede ver su usuario / correo
   electrónico asociado.

_Caminos alternativos_  
4.a. El teléfono ingresado por el usuario no está asociado a ninguna cuenta  
4.a.1 El sistema indica que el número de teléfono no está asociado a ninguna cuenta.  
4.a.2 Vuelve al paso 3.

6.a El código que el usuario ingresa ha expirado o no es válido.  
6.a.1 El sistema muestra indica que el código expiró o no es correcto.  
6.a.2 Usuario vuelve a paso 1.

_Escenario de éxito_  
El usuario logra recuperar su usuario / correo electrónico.

_Escenario de fracaso_  
El usuario no tiene acceso al número de teléfono asociado con su cuenta y desiste.
