---
name: review-date-rules
description: Revisar reglas AL de fechas de seguimiento, estados y reprogramación. Usar al comprobar el estado de revisión o la acción Customer Follow-up y sus casos límite.
---
# Revisión de fechas de seguimiento

Leer el contrato vigente y localizar dónde se obtiene la fecha de referencia. En Customer Follow-up la interfaz pasa WorkDate y la función recibe un Date explícito.

Comprobar fecha vacía, anterior, igual y posterior. Consultar boundary-cases.md para los ejemplos docentes. Distinguir días naturales, días laborables y meses según el contrato. Revisar desde qué fecha cuenta la reprogramación y qué ocurre al repetir la acción.

Si cambia un registro, comprobar persistencia y conservación de campos ajenos al cambio. Relacionar cada discrepancia con archivo, caso y evidencia. Proponer correcciones solo cuando la observación o el contrato las justifiquen. Si no hay ejecución, escribir «no ejecutado» en observado.

## Interpretar los casos del taller

En cases.csv, la columna starter_expected describe el resultado esperado
del starter original, antes de resolver los TODOs. No debe actualizarse
al completar un laboratorio. Contrasta el comportamiento actual con el
contrato y los resultados esperados de la etapa; registra los resultados
observados en evidence/. No presentes la diferencia respecto a
starter_expected como un defecto del código ni del archivo de casos.