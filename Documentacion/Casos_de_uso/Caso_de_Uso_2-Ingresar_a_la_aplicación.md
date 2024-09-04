**Caso de uso**: Ingresar a la aplicación

_Actor_: Usuario (actor primario)

_Precondiciones_: El usuario está registrado

_Camino básico_

1. El usuario accede a la página de ingreso.
2. El sistema pide al usuario que ingrese usuario y contraseña.
3. El usuario ingresa su usuario y contraseña, y confirma el ingreso.
4. El sistema valida los datos ingresados.
5. El usuario accede a la aplicación.
6. El sistema muestra la página de inicio.

_Caminos alternativos_  
4.a El usuario ingresa datos no válidos.  
4.a.1 El sistema señala el dato no válido en el formulario.  
4.a.2 Vuelve al paso 3.

3.b El usuario ingresa por primera vez.  
3.b.1 El sistema le da a elegir, opcionalmente, categorías / intereses (selección máxima de 3).  
3.b.2.a El usuario las selecciona e ingresa a la aplicación.  
3.b.2.b El usuario saltea la selección e ingresa a la aplicación.

_Escenario de éxito_  
El usuario accede a la aplicación.

_Escenario de fracaso_  
El usuario no recuerda su usuario o contraseña y no puede ingresar.  
El usuario no está registrado.
