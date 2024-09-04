# Diccionario de datos

usuario \= nombreUsuario \+ contraseña \+ teléfono \+ email \+ nombre \+ apellido \+ rol \+ esPremium \+ 0 { interés } 3
\+ foto

rol \= nombreRol

interés \= nombreInterés

evento \= título \+ descripción \+ 1 { foto } 3 \+ capacidad_maxima \+ fecha \+ horaInicio \+ horaFinalizado \+
esGratuito \+ esPeriodico \+ 0 { interés } 3 \+ ciudad \+ direcciónEvento \+ clicksPorHora \+ organizador \+ foto

foto \= urlFoto

ciudad \= nombreCiudad \+ codigoPostal \+ provincia

provincia \= nombreProvincia

formularioRegistro \= nombre \+ apellido \+ correo \+ contraseña \+ confirmación de contraseña \+ teléfono

formularioModificaciónCuenta \= correo \+ teléfono \+ nombreUsuario \+ contraseña

formularioModificaciónPerfil \= nombre \+ apellido \+ fotoDePerfil

formularioEventos \= título \+ descripción \+ 1 { foto } 3 \+ capacidad_maxima \+ fecha \+ horaInicio \+ horaFinalizado
\+ esGratuito \+ esPeriodico \+ 0 { interés } 3 \+ ciudad \+ direcciónEvento
