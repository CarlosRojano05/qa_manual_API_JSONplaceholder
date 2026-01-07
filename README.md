JSONPlaceholder API | QA Manual Project
Descripción del proyecto

Este proyecto corresponde a un proceso completo de testing manual de API REST realizado sobre la API pública JSONPlaceholder.

El objetivo fue validar el correcto funcionamiento de los endpoints, verificando respuestas, códigos de estado, manejo de errores y estructura de los datos, siguiendo el ciclo de vida del testing (STLC) en un escenario similar a un entorno real de trabajo.

NOTA: La API utilizada es un mock público, por lo que los datos no son persistentes. Esta limitación fue considerada y documentada durante las pruebas.

Objetivo

Verificar que los endpoints de la API cumplan con:

Correcto manejo de métodos HTTP (GET, POST, PUT, DELETE)

Respuestas y códigos de estado esperados

Comportamiento ante datos inválidos o inexistentes

Estructura correcta del response en formato JSON

Manejo adecuado de operaciones CRUD

Alcance de las pruebas

Tipos de prueba ejecutados:

Pruebas funcionales

Pruebas negativas

Validación de status codes

Validación de response body

Pruebas exploratorias

Regresión básica

Endpoints evaluados:

GET /users

GET /users/{id}

POST /users

PUT /users/{id}

DELETE /users/{id}

🛠️ Herramientas

Postman: Ejecución de requests HTTP

Jira:

Historias de usuario

Seguimiento de ejecución

Registro y trazabilidad de defectos

Microsoft Excel / Google Sheets:

Casos de prueba

Reporte de ejecución

Evidencias: Capturas de pantalla de respuestas y status codes

Resultados Finales

Casos ejecutados: 12

Bugs reportados: 0

Estado: Proyecto cerrado exitosamente con informe final de QA

Todas las validaciones definidas en el Test Plan fueron ejecutadas conforme a lo esperado, considerando las limitaciones propias de una API mock.

Artefactos del Proyecto

Dentro de este repositorio encontrarás la documentación técnica organizada según el ciclo de vida del testing:

[01_Test_Plan_API] – Estrategia, alcance y criterios de aceptación

[02_Test_Cases_API] – Casos de prueba documentados para cada endpoint

[03_Test_Execution_Report] – Registro detallado de resultados de ejecución

[04_Final_QA_Report] – Informe final con conclusiones y métricas de calidad

👤 Autor

Carlos Manuel Rojano Camargo
QA Manual | API Testing | Testing Funcional
