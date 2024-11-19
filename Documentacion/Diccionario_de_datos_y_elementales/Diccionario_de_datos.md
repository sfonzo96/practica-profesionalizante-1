# Diccionario de datos

usuario \= @nombreUsuario \+ contraseña \+ @teléfono \+ @email \+ nombre \+ apellido \+ rol \+ esPremium \+ 0 { interés } 3
\+ foto + esCorreoVerificado

evento \= título \+ descripción \+ foto \+ capacidadMaxima \+ fecha \+ horaInicio \+ horaFinal \+
esGratuito \+ esPeriodico \+ esPromocionado \+ 0 { interés } 3 \+ ciudad \+ direcciónEvento \+ clicksPorHora \+ foto

ciudad \= nombreCiudad \+ @codigoPostal \+ provincia

formularioRegistro \= nombreUsuario \+ nombre \+ apellido \+ email \+ contraseña \+ confirmaciónContraseña \+ teléfono \+ rol

formularioModificaciónCuenta \= email \+ teléfono \+ contraseña

formularioModificaciónPerfil \= nombre \+ apellido \+ foto

formularioEventos \= título \+ descripción \+ foto \+ capacidadMaxima \+ fecha \+ horaInicio \+ horaFinal \+ esGratuito \+ esPeriodico \+ 0 { interés } 3 \+ ciudad \+ direcciónEvento
