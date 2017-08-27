### Integrantes
* Kevin García 13177
* Pablo Danilo 13203

# Data Engineer

## Determina objetivos y estrategias 
* Objetivos
    * Mantener actualizada la replica local de data del cliente
* Estrategias
    * Validación diaria de carga de data local 
    * Comparación diaria de la data replicada con el sistema original

## Planea programas
* Diariamente se revisará la carga de información
* Se debe revisar la integridad del proceso de migración de data
* Se debe comparar y validar la data cargada con la data del sistema original

## Determina cargas de trabajo
* Conexión con base de datos del cliente
* Generación de reporte con conteo de filas por fecha, suma de campos de venta de replica local
* Generación de reporte con conteo de filas por fecha, suma de campos de venta de sistema original
* Identificación de discrepancias entre replicación y sistema original
* Identificación de causas de discrepancia
* Elaboración de reporte de validación con identificación de problemas y causas
* Corrección de proceso de migración
* Corrección de data de carga actual

## Asignación de recursos
### Recursos de software
* Servicio de data warehouse
* Cliente SQL
* Procesador de texto
* Excel
* Software de control de migración de data

### Recursos de tiempo
Tiempo |Tarea
--- |---
5 min | Conexión con base de datos del cliente
10 min | Generación de reporte con conteo de filas por fecha, suma de campos de venta de replica local
10 min |Generación de reporte con conteo de filas por fecha, suma de campos de venta de sistema original
20 min | Identificación de discrepancias entre replicación y sistema original
30 min | Identificación de causas de discrepancia
15 min | Elaboración de reporte de validación con identificación de problemas y causas
1 h |Corrección de proceso de migración
20 min | Corrección de data de carga actual

## Adquiere/delega aurotirdad para utilizar recursos
### Recurso de software
Recurso |Tarea
---|---
Cliente SQL | Conexión con base de datos del cliente
Servicio de data warehouse | Generación de reporte con conteo de filas por fecha, suma de campos de venta de replica local
Excel | Generación de reporte con conteo de filas por fecha, suma de campos de venta de replica local
Excel | Generación de reporte con conteo de filas por fecha, suma de campos de venta de sistema original
Excel | Identificación de discrepancias entre replicación y sistema original
Software de control de migración de data | Identificación de causas de discrepancia
Excel | Elaboración de reporte de validación con identificación de problemas y causas
Procesador de texto | Elaboración de reporte de validación con identificación de problemas y causas
Software de control de migración de data | Corrección de proceso de migración
Software de control de migración de data | Corrección de data de carga actual
Cliente SQL | Corrección de data de carga actual

### Recursos de tiempo
Recurso |Tarea
--- |---
Data Engineer | Conexión con base de datos del cliente
Auxiliar | Generación de reporte con conteo de filas por fecha, suma de campos de venta de replica local
Auxiliar |Generación de reporte con conteo de filas por fecha, suma de campos de venta de sistema original
Auxiliar | Identificación de discrepancias entre replicación y sistema original
Data Engineer | Identificación de causas de discrepancia
Auxiliar | Elaboración de reporte de validación con identificación de problemas y causas
Data Engineer |Corrección de proceso de migración
Data Engineer | Corrección de data de carga actual

## Desempeña el trabajo
Revisión diaria de la data migrada y generación de repotes de estado actual

## Compara el desempeño con el plan
* Comparación del tiempo tomado para la revisión y corrección (si fuera necesaria) de la data, contra el tiempo planificado.
* Comparación del software utilizado para la revisión y correccion contra el software planificado para su uso.
* Comparación del personal requerido para realizar la revisión contra el personal planificado.

## Compara los objetivos alcanzados con los objetivos deseados
Revisión del producto final.<br>
Llevar control de la cantidad de días de errores y retrados encontrados.<br>
Identificar los días de retraso de la data en comparación con el sistema del cliente.<br>

## Compara el programa alcanzado con el programa planeado
Identificar métodología aplicada y compararla con la metodología planificada.<br>
Comparar tiempos de cada actividad.<br>
Comparar métricas establecidas para el cumplimiento de los objetivos:
* La data se mantiene como máximo con 1 día de atraso
* La cantidad de errores disminuye con cada revisión y actualización
