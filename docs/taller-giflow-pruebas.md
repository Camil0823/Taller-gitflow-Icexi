# Documento de Pruebas

## 1. Descripcion del Sistema

## 2. Requerimientos a Evaluar

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

## 5. Trazabilidad

## 6. Gestion de Versiones (GitFlow)
