**Caso de uso**: Modificar configuración de cuenta

_Actor_: Usuario (actor primario)

_Precondición_: El usuario debe haber iniciado sesión en la aplicación.

_Camino básico_

1. El usuario solicita el cambio de alguna de sus credenciales.
2. El sistema muestra al usuario el formulario “formularioModificaciónCuenta” con los valores actuales.
3. El usuario modifica la información necesaria y confirma el cambio.
4. El sistema valida la información ingresada y pide al usuario ingresar la contraseña actual para efectivizar la
   modificación.
5. El usuario ingresa la contraseña y confirma.
6. El sistema verifica que es la correcta, realiza la modificación y envía un mail notificando del cambio.

_Caminos alternativos_

4.a La modificación que realizó el usuario no es válida.  
4.a.1 El sistema señala cuál es el campo inválido.  
4.a.2 Vuelve al paso 3.

6.a La contraseña ingresada por el usuario no es correcta.  
6.a.1 El sistema señala el problema e indica que se debe reintentar.  
6.a.2 Vuelve al paso 5.

_Escenario de éxito_  
El sistema guarda los cambios del usuario con éxito.

_Escenario de fracaso_  
El usuario desiste de la modificación.  
El usuario no recuerda su contraseña.
