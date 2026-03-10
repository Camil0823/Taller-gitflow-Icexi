# Documento de Pruebas

## 1. Descripcion del Sistema



## 2. Requerimientos a Evaluar

**RF02-Student-code.**
-El codigo tiene que tener exactamente 8 caracteres.
-Iniciar con la letra "E".
-Los 7 caracteres restantes deben ser números.

## 3. Tecnicas de Prueba Aplicadas

**Partición de equivalencia**
Por que?
Porque lo que hace la tabla es dividir entre clases validas e invalidas para demostrar de manera clara como ingresar el codigo.
#### RF-01 Registro de Estudiante (Edad)
  El sistema debe permitir el registro de estudiantes cuya edad esté entre 16 y 65 años inclusive.


## 3. Tecnicas de Prueba Aplicadas

- RF-01 Registro de Estudiante (Edad)

    Análisis de Valor Límite

  - Caso 1: Ls16  -> 17 
  - Caso 2: Li16 -> 15
  - Caso 3: Ls65 -> 66
  - Caso 4: Li65 -> 64
  - Caso 5: L16 -> 16
  - Caso 6: L65 -> 65


| Casos | Entrada | Resultado Esperado |
|-------|--------|--------------------|
| C1    | 17     | Válido             |
| C2    | 15     | Inválido           |
| C3    | 66     | Inválido           |
| C4    | 64     | Válido             |
| C5    | 16     | Válido             |
| C6    | 65     | Válido             |

Escogí la técnica de valor límite, porque cómo se esta hablando de rangos con límites, por ende es la más adecuada para demostrar que casos son válidos y cuales no.

- RF-02 Código de Estudiante
- RF-03 Inscripción a Evento

## 4. Casos de Prueba Diseñados
| **Criterio** |  **Clases válidas (V)**  | **Clases inválidas (I)**  | 
| :----- | ----------------: | :-----------------: |
|  Longitud del codigo  | V1: Tiene 8 caracteres | I1: Menos de 8 caracteres<br>I2: Mas de 8 caracteres |
|  Que inicie con la letra "E" |  V2: Empieza con la letra "E"  |   I3: No empieza con la letra "E"    |
| Los 7 caracteres restantes sean numéricos | V3: Los caracteres despues de la "E" son todos numericos | I4: Hay una letra despues de la "E" |

## 5. Trazabilidad



## 6. Gestion de Versiones (GitFlow)
