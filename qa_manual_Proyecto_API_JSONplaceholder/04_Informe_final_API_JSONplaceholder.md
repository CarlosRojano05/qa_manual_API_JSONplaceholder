# INFORME FINAL DE QA – API TESTING

### 1. Información General
**Proyecto:** JSONPlaceholder – API Testing  
**Tipo de aplicación:** API REST (Mock pública)  
**URL Base:** https://jsonplaceholder.typicode.com  
**Responsable QA:** Carlos Manuel Rojano Camargo  
**Fecha de inicio:** 05/01/2026  
**Fecha de cierre:** 07/01/2026  
**Tipo de pruebas:** Pruebas manuales de API  
**Herramientas utilizadas:** **Postman, Excel, Jira**

### 2. Objetivo del Testing
Validar el correcto funcionamiento de los endpoints expuestos por la API JSONPlaceholder, asegurando:

* **Correcto uso de métodos HTTP**
* **Respuestas acordes a lo esperado**
* **Manejo adecuado de errores**
* **Validación de códigos de estado (status codes)**
* **Estructura y formato correcto de los responses en JSON**

### 3. Alcance del Proyecto
**Endpoints probados**

| Endpoint | Método | Descripción |
| :--- | :--- | :--- |
| /users | **GET** | Obtener lista de usuarios |
| /users/{id} | **GET** | Obtener usuario por ID |
| /users | **POST** | Crear usuario |
| /users/{id} | **PUT** | Actualizar usuario |
| /users/{id} | **DELETE** | Eliminar usuario |

**Tipos de prueba ejecutados**
* **Pruebas funcionales**
* **Pruebas negativas**
* **Validación de status codes**
* **Validación de estructura del response**
* **Validación de comportamiento esperado en API mock**

**Fuera de alcance**
* **Autenticación (/login)**
* **Pruebas de performance**
* **Pruebas de seguridad**
* **Automatización**

### 4. Estrategia de Pruebas
Las pruebas se ejecutaron de forma manual utilizando **Postman**.  
Para cada caso de prueba se validó:

* **Endpoint correcto**
* **Método HTTP correcto**
* **Status code esperado**
* **Body de la respuesta**
* **Campos obligatorios**
* **Comportamiento ante datos inválidos**

Los resultados fueron documentados en **Excel** y gestionados en **Jira**.

### 5. Entorno de Pruebas
| Elemento | Detalle |
| :--- | :--- |
| **Ambiente** | Producción pública (Demo) |
| **Autenticación** | No requerida |
| **Formato de datos** | **JSON** |
| **Persistencia de datos** | No (API mock) |

### 6. Resumen de Ejecución
| Métrica | Resultado |
| :--- | :--- |
| **Total de casos de prueba** | **10** |
| **Casos ejecutados** | **10** |
| **Casos PASS** | **10** |
| **Casos FAIL** | **0** |
| **Casos bloqueados** | **0** |
| **Defectos encontrados** | **0** |

### 7. Resultados del Testing
* **Todos los casos de prueba fueron ejecutados exitosamente.**
* **La API respondió conforme a lo esperado en todos los escenarios.**
* **No se encontraron defectos funcionales.**
* **Los comportamientos observados coinciden con las limitaciones documentadas de una API mock (datos no persistentes).**

### 8. Defectos
**No se identificaron defectos durante la ejecución de las pruebas.** Por esta razón, **no se generaron tickets de tipo BUG en Jira** para este proyecto.

### 9. Riesgos y Limitaciones
| Riesgo / Limitación | Observación |
| :--- | :--- |
| **API mock** | Los cambios no se persisten |
| **Respuestas simuladas** | Algunas validaciones no reflejan un entorno real |
| **API pública** | Dependencia de disponibilidad externa |

### 10. Conclusión
El proyecto **JSONPlaceholder – API Testing** fue ejecutado exitosamente.  
La API cumple con los criterios funcionales definidos dentro del alcance del proyecto.  
Los resultados obtenidos permiten concluir que los endpoints probados se comportan de manera correcta bajo los escenarios evaluados.  
Este proyecto demuestra la aplicación práctica del ciclo de vida del testing (**STLC**): planificación, diseño de casos de prueba, ejecución, documentación y cierre.
