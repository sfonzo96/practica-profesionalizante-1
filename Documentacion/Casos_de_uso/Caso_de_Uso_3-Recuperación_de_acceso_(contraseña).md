**Caso de uso**: Recuperación de acceso.

_Actor_: Usuario (actor primario)

_Precondición_: El usuario debe estar registrado en la aplicación.

_Camino básico_

1. El usuario solicita el cambio de contraseña.
2. El sistema redirige al usuario a una vista con un formulario que solicita el email de recuperación.
3. El usuario ingresa su correo electrónico y confirma el formulario.
4. El sistema envía un correo con un enlace de recuperación.
5. El usuario ingresa al enlace recibido por correo.
6. El sistema muestra un formulario con dos campos para ingresar la nueva contraseña (duplicado).
7. El usuario ingresa su nueva contraseña y confirma el formulario.
8. El sistema valida la contraseña ingresada y modifica la contraseña del usuario.

_Caminos alternativos_  
4.a El correo ingresado no es válido.  
4.a.1 El sistema indica la invalidez del correo ingresado.  
4.a.2 Vuelve al paso 3.

4.b El usuario ingresa un correo electrónico que no está registrado en el sistema.  
4.b.1 El sistema indica que el correo no está asociado a ninguna cuenta.  
4.b.2 Vuelve al paso 3.

8.a La contraseña ingresada no es segura (se requieren al menos ocho caracteres alfanuméricos y al menos una
mayúscula).  
8.a.1 El sistema señala la necesidad de una contraseña más segura.  
8.a.2 Vuelve al paso 7.

8.b Las contraseña y el duplicado no coinciden.  
8.b.1 El sistema señala la diferencia entre las contraseñas ingresadas.  
9.b.2 Vuelve al paso 7.

_Escenario de éxito_  
El usuario modifica su contraseña con éxito y recupera el acceso a su cuenta.

_Escenario de fracaso_  
El usuario no recuerda el correo electrónico que utilizó para crear su cuenta.  
El usuario recuerda su contraseña y decide no continuar la recuperación.
