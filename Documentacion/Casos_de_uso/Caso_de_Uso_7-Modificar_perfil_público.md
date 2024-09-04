**Caso de uso**: Modificar perfil público

_Actor_: Usuario (actor primario)

_Precondición_: El usuario debe haber iniciado sesión en la aplicación.

_Camino básico_

1. El usuario solicita el cambio de su información pública.
2. El sistema muestra al usuario el formulario “formularioModificaciónPerfil” con los valores actuales.
3. El usuario modifica la información necesaria y confirma el cambio.
4. El sistema valida la información ingresada, realiza la modificación y redirige al usuario a la vista de su perfil.

_Caminos alternativos_

4.a La modificación que realizó el usuario no es válida.  
4.a.1 El sistema señala cuál es el campo inválido.  
4.a.2 Vuelve al paso 3.

_Escenario de éxito_  
El sistema guarda los cambios del usuario con éxito.

_Escenario de fracaso_  
El usuario desiste de la modificación.
