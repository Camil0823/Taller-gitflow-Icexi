# Documento de Pruebas

## 1. Descripcion del Sistema

## 2. Requerimientos a Evaluar

# RF-03 Inscripción a Evento 
En  este requerimiento nos piden que un estudiante se pueda inscribir a un evento, teniendo en cuenta las condiciones como que el evento este registrado, el evento tiene cupos disponibles y que el estudiante no este incrito ya al evento. Para que funcione este metodo necesitamos un evento con cupos disponibles y un estudiante no inscrito al evento.
## tecnica a usar
Vamos a usar la tecnica de caja negra de tablas de decision 
Usaremos esa tecnica debido a que queremos comparar si una valuacion se cumple en unos casos en especificos, entoces debemos tener en cuenta cada uno de los casos

| esta registrado | hay cupos  | estaba inscrito antes| acceso |
| :--- | :---: | :---: | :--- |
| si | si | si | si |
| si | si | no | no |
| si | no | si | no |
| si | no | no | no |
| no | si | si | no |
| no | si | no | no |
| no | no | si | no |
| no | no | no | no |

la logica de la tabla sigue al pie de la letra el enunciado y las necesidades del clinete, solo se debe dar acceso a las personas que cumplan todas los condiciones con todas las combinaciones presentes
## 3. Tecnicas de Prueba Aplicadas

## 4. Casos de Prueba Diseñados

## 5. Trazabilidad

## 6. Gestion de Versiones (GitFlow)




