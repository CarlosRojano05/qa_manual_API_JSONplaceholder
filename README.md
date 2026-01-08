# JSONPlaceholder API | QA Manual Project

## Descripción del Proyecto
Este proyecto corresponde a un proceso completo de **testing manual de API REST** realizado sobre la API pública **JSONPlaceholder**. 

El objetivo principal fue validar el correcto funcionamiento de los endpoints, verificando respuestas, códigos de estado (Status Codes), manejo de errores y estructura de los datos (JSON), siguiendo el ciclo de vida del testing (**STLC**) en un escenario simulado de entorno real.

**NOTA:** La API utilizada es un *mock* público, por lo que los datos no son persistentes. Esta limitación técnica fue considerada, analizada y documentada durante toda la fase de ejecución.

## Objetivos de las Pruebas
Verificar que los endpoints de la API cumplan con:
* **Manejo de métodos HTTP:** Uso correcto de `GET`, `POST`, `PUT` y `DELETE`.
* **Validación de Respuestas:** Verificación de Status Codes esperados (200 OK, 201 Created, 404 Not Found, etc.).
* **Integridad de Datos:** Estructura correcta del *Response Body* en formato JSON.
* **Flujos Negativos:** Comportamiento adecuado ante datos inválidos o recursos inexistentes.

## Alcance del Testing
### Tipos de prueba ejecutados:
* **Pruebas Funcionales:** Validación de la lógica de negocio del endpoint.
* **Pruebas Negativas:** Ingreso de datos erróneos para validar la robustez.
* **Validación de Contratos:** Verificación del esquema y tipos de datos en el JSON.
* **Pruebas Exploratorias:** Identificación de comportamientos no documentados.

## Endpoints Evaluados:
* `GET /users` (Listado completo de usuarios)
* `GET /users/{id}` (Consulta de usuario específico)
* `POST /users` (Simulación de creación de recurso)
* `PUT /users/{id}` (Simulación de actualización total)
* `DELETE /users/{id}` (Simulación de eliminación)

## Herramientas Utilizadas
* **Postman:** Ejecución, organización de colecciones y validación de *Requests/Responses*.
* **Jira:** Gestión de Historias de Usuario, trazabilidad y registro de hallazgos.
* **Google Sheets / Excel:** Diseño de la matriz de casos de prueba y reporte de ejecución.
* **JSON Viewer:** Inspección técnica de la estructura de datos.

## Artefactos del Proyecto
La documentación técnica está organizada para garantizar la transparencia y trazabilidad del proceso:

* **[01_Test_Plan_API_JSONplaceholder][Ver Test Plan en Google Drive](https://drive.google.com/file/d/1mjTmiTqTp1UNs_ph1mNPhvWqXrhciDza/view?usp=sharing):** Estrategia, alcance, riesgos y criterios de aceptación.
* **[02_Test_Cases_API_JSONplaceholder][Ver Test Cases en Google Drive](https://docs.google.com/spreadsheets/d/1jHemJO0Lc3al2un8T0yBn1js462-SccuU8FSCxls_74/edit?gid=852891993#gid=852891993):** Diseño de casos de prueba detallando la carga de datos (Requests), validación de respuestas del servidor y códigos de estado.
* **[03_Test_Execution_API_JSONplaceholder][Ver Test Execution en Google Drive](https://docs.google.com/spreadsheets/d/1jHemJO0Lc3al2un8T0yBn1js462-SccuU8FSCxls_74/edit?gid=1064100355#gid=1064100355):** Registro detallado con evidencias de la última ejecución.
* **[04_Informe_Final_JSONplaceholder][Ver Reporte_Final en Google Drive](https://drive.google.com/file/d/17qB1gMh8ngSFAgm37mJc2FCufKVp9Uam/view?usp=sharing):** Informe de cierre con conclusiones, métricas de calidad y recomendaciones.

## Resultados Finales
* **Casos de Prueba Ejecutados:** 12
* **Bugs Reportados:** 0 (Se validó que la API responde según la documentación del mock).
* **Estado del Proyecto:** **Cerrado Exitosamente**. 

---

## 👤 Autor
**Carlos Manuel Rojano Camargo**
*QA Manual | API Testing | Testing Funcional*

