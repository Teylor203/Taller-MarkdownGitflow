### RF-01 - [Registrar turoria]

#### Resumen
Se busca que el profesor registre una tutoría con toda la información, con el objetivo de que los estudiantes la encuentren después. Se pedirá código, tema, fecha, hora de inicio y cantidad de estudiantes. Se verifica que la fecha sea después de la fecha actual. Cuando el registro sea exitoso, se asigna un identificador y se informa que fue creada correctamente.




#### Entradas
Código profesor: String
Hora inicio: DateTime
Fecha: Date
Cantidad estudiantes maximos: int
Tema: String


#### Reglas o condiciones
Fecha:  debe ser posterior a la actual.
Estudiantes máximos:  máximo 10 minimo 1



#### Salidas
Mensaje confirmación: String
Identificador: String


#### Resultado esperado
Registro de turoria exitoso.
