# Especificación de Requerimientos

## 1. Descripción del sistema

## 2. Integrantes

- Nombre: Christian Benitez
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


### RF-02 - Consulta de la monitorias

#### Resumen
Los estudiantes buscaran a la tutoria a la que desean inscribirse, esta será buscada con la fecha y de manera opcional indicar la asignatura o tema de interés. 

#### Entradas

| Entrada  | Tipo de dato | Descripción |
|---|---|---|
| Fecha_Buscada | DateTime | Fecha de la tutoria buscada |
| Asignatura | String | Nombre de la asigntura |
| Tema | String | Nombre del tema |
| Id_Tutoria | int | Identificador unitario |
| Fecha_Tutoria | DateTime | Fecha de la tutoria asignada por el docente |
| Cupos_Disponibles | Int | Muestra cupos restantes |
| Mensaje_Fallido | String | Mensaje de no haber encontrado la tutoria |

#### Reglas o condiciones
- Condición 1: Buscar por fecha la monitoria o si es deseado con el nombre de la asigntura.
- Condición 2: No mostrar las tutorías que se encuentran llenas.
- Condición 3: El sistema debe mostrar el ID unitario de cada tutoria en la búsqueda.
- Condición 4: Mostrar mensaje de error al no encontrar la tutoria.

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|
| asignatura | String | Nombre de la asigantura |
| id_Tutoria | int | Identificador unico de la tutoria|
| mensaje_Fallido | String | mensaje descriptivo de error |

#### Resultado esperado

El estudiante que desee buscar alguna tutoria por su ID o fecha en la que lo necesite
aparecera un listado de todas las tutorias disponibles. En caso de no encontrar ninguna
resivira en la misma pagina un mensaje de error.


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


### RF-04 - [Nombre del requerimiento]

#### Resumen

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|

#### Reglas o condiciones

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|

#### Resultado esperado


## 4. Gestión de Versiones

### Ramas utilizadas

### Proceso de integración

### Conflictos encontrados