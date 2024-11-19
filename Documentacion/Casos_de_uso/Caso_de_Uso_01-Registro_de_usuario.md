**Caso de uso:** Registro de nuevo usuario.

_Actor_: Usuario (actor primario)

_Precondición_: El usuario no debe estar autenticado en el sistema.

_Camino básico_

1. El usuario accede a la página de registro.
2. El sistema muestra opciones para seleccionar el rol (usuario u organizador).
3. El usuario selecciona su rol.
4. El sistema muestra el formulario “formularioRegistro”.
5. El usuario completa los campos del formulario y confirma el registro.
6. El sistema valida los campos completados, envía un correo electrónico de confirmación y redirige al usuario a la
   página de login.

_Caminos alternativos_

6.a El usuario ingresó datos no válidos.  
6.a.1 El sistema señala el dato no válido en el formulario.  
6.a.2 Vuelve al paso 5.  
6.b El usuario ingresó un dato único ya existente.  
6.b.1 El sistema indica que tal dato ya está en uso.  
6.b.2 Vuelve al paso 5.

_Escenario de éxito_

El usuario logra registrarse correctamente.

_Escenario de fracaso_

El usuario decide no registrarse.
