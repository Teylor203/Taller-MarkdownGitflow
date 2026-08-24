# Especificación de Requerimientos

## 1. Descripción del sistema

## 2. Integrantes

- Nombre: Cristian Benitez
- Nombre: Franco Marulanda
- Nombre: Juan Sebastian Benitez
- Nombre: Teylor Tamayo

## 3. Requerimientos Funcionales

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


### RF-02 - [Nombre del requerimiento]

#### Resumen

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|

#### Reglas o condiciones

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|

#### Resultado esperado


### RF-03 - [Nombre del requerimiento]

#### Resumen

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|

#### Reglas o condiciones

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|

#### Resultado esperado


### RF-04 - Cancelación Inscripción

#### Resumen

Un estudiante podrá cancelar su participación de la tutoría.

#### Entradas

| Entrada | Tipo de dato | Descripción |
|codigoEstudiante|String|Codigo que identifica el estudiante|
|idTutoria|String|Código que identifica la tutoría|


#### Reglas o condiciones
- Existe una inscripción previa
- La tutoría aún no comienza

#### Salidas

| Salida | Tipo de dato | Descripción |
|mensajeInscripcionEliminada|String| Mensaje que avisa que la inscripción quedó eliminada|
|mensajeCupoLiberado|String| Mensaje que indica que el cupo se liberó|
|mensajeExito|String| Mensaje que indica que la operación fue exitosa|
|mensajeFallido|String| Mensaje que indica que la operación falló indicando motivo|
|cuposDisponibles|int| Cantidad de cupos disponibles de la tutoría después de liberar el cupo|



#### Resultado esperado
La inscripción será eliminada, el cupo volverá a estar disponible y se mostrará un mensaje que confirme
la operación como exitosa.

## 4. Gestión de Versiones

### Ramas utilizadas

### Proceso de integración

### Conflictos encontrados