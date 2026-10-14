# Universidad Técnica Nacional
## Sede San Carlos
### Carrera: Ingeniería del Software

**Curso:** Administración de Proyectos Informáticos  
**Código de curso:** ISW-912  
**Estudiante:** Stuarth Fabricio Miranda Rojas  
**Profesor:** Deiver Cubero Molina  

---

## Historial de Versiones / Control de Cambios

| Versión | Fecha | Semana o Fase | Descripción del Cambio | Autor |
| :---: | :---: | :---: | :--- | :--- |
| **0.1** | 23/09/2026 | Semana 1 | Definición inicial de la idea del proyecto, problema, propuesta, valor esperado y objetivos. | Stuarth Fabricio Miranda Rojas |
| **0.2** | 23/09/2026 | Semana 2 / Fase 3 | Incorporación del análisis de contexto organizacional (EEF), mapa de interesados y restricciones conocidas. | Stuarth Fabricio Miranda Rojas |
| **0.3** | 04/10/2026 | Semana 3 | Integración de requerimientos del sistema, casos de prueba iniciales y definición de roles. | Stuarth Fabricio Miranda Rojas |
| **0.4** | 14/10/2026 | Semana 4 | Implementación de ciclo de vida ágil, proyección a 10 semanas (5 Sprints), Product Backlog, DoD y cronograma. | Stuarth Fabricio Miranda Rojas |

---

## Tema/Nombre:
Sistema inteligente para gestión y optimización de operaciones logísticas

## Problema:
Las empresas dedicadas al transporte y logística pueden presentar dificultades para planificar rutas eficientes, controlar el consumo de recursos, dar seguimiento al estado de sus vehículos y medir el impacto ambiental de sus operaciones.

En algunos casos, estas decisiones se realizan de forma manual o basándose principalmente en la experiencia de los encargados, lo que puede provocar recorridos innecesarios, mayor consumo de combustible, dificultades para controlar el mantenimiento de los vehículos y poca información para evaluar la eficiencia de las operaciones.

El proyecto busca abordar esta problemática mediante una solución digital que permita centralizar y analizar la información relacionada con rutas, vehículos, consumo y sostenibilidad. Esto mantiene el enfoque original del proyecto hacia la modernización de los procesos logísticos y el ODS 9.

## Proyecto propuesto:
Se propone desarrollar conceptualmente una plataforma web para la gestión y optimización de operaciones logísticas, que permita registrar vehículos, rutas, proveedores, consumo de recursos, mantenimiento y diferentes indicadores de eficiencia y sostenibilidad.

El sistema permitirá registrar el origen y destino de las rutas y calcular las distancias mediante la fórmula de Haversine, utilizando información geográfica de GoogleMaps. Para la búsqueda de rutas se propone utilizar el algoritmo de Dijkstra, con el objetivo de encontrar una ruta eficiente entre un punto de origen y un punto de destino.

También el sistema podrá considerar información como:
* Distancia de la ruta.
* Tiempo estimado.
* Consumo aproximado de combustible.
* Tipo de carretera.
* Estado del vehículo.
* Historial de mantenimiento.
* Consumo de recursos.
* Emisiones estimadas de CO₂.

## Valor esperado:
Se espera proponer una solución digital que permita mejorar la gestión de las operaciones logísticas mediante el control de rutas, vehículos, mantenimiento y consumo de recursos.

La solución permitirá plantear rutas eficientes utilizando el algoritmo de Dijkstra, además de estimar tiempos, consumo de combustible y emisiones de CO₂. También permitirá llevar un control del mantenimiento preventivo y generar indicadores que faciliten el análisis de la eficiencia de las operaciones y su impacto ambiental.

## Objetivos Completos:

### Objetivo General
Proponer una solución tecnológica para la gestión y optimización de operaciones logísticas, mediante el análisis de rutas, vehículos, mantenimiento y consumo de recursos.

### Objetivos específicos
* Analizar las necesidades relacionadas con la gestión de rutas, vehículos, mantenimiento y consumo de recursos en las operaciones logísticas.
* Definir los requerimientos de una plataforma web que permita centralizar la información de las operaciones logísticas, incluyendo el cálculo de distancias, rutas, consumo, mantenimiento e indicadores de eficiencia.
* Establecer métodos para la optimización de rutas mediante Haversine y Dijkstra, así como para el cálculo de consumo, costos y emisiones estimadas de CO₂.

---

## Contexto del Proyecto e Interesados

### 1. Análisis del Entorno Organizacional y Factores Ambientales (EEF)

#### Estructura Organizacional
El desarrollo del proyecto se plantea bajo una estructura matricial orientada a proyectos dentro del ámbito informático. Esta estructura permite contar con la autoridad necesaria para la toma de decisiones técnicas y de gestión sobre la plataforma, coordinando las actividades del equipo de desarrollo con los requerimientos operativos de la empresa logística.

#### Factores Ambientales de la Empresa (EEF)
* **Factores Internos:** Infraestructura tecnológica disponible, capacidad del equipo de desarrollo en algoritmos (Dijkstra/Haversine) y herramientas de gestión.
* **Factores Externos:** API de Google Maps, normativas ambientales de CO₂, condiciones de las vías.

### 2. Identificación de Interesados (Stakeholders)

| Interesado / Stakeholder | Nivel de Poder | Nivel de Interés | Estrategia de Gestión |
| :--- | :--- | :--- | :--- |
| Gerencia General / Sponsor | Alto | Alto | Gestionar de cerca mediante reportes periódicos de avance. |
| Encargados de operaciones logísticas | Alto | Alto | Gestionar de cerca para asegurar respuesta a necesidades operativas. |
| Director de Proyecto (PM) | Alto | Alto | Gestionar de cerca, coordinando al equipo. |
| Equipo de desarrollo de software | Medio | Alto | Mantener informados y empoderados durante la definición técnica. |
| Conductores de la flota | Bajo | Alto | Mantener informados y recopilar retroalimentación de usabilidad. |
| Jefatura de Mantenimiento | Medio | Medio | Mantener satisfechos integrando módulos de control mecánico. |
| Clientes finales de la carga | Bajo | Alto | Mantener informados sobre tiempos estimados de llegada. |
| Entidades de regulación ambiental | Medio | Bajo | Mantener satisfechos mediante la generación de reportes de CO₂. |

### 3. Restricciones Conocidas del Proyecto
* **Tiempo:** Marco temporal definido (10 semanas) para el diseño conceptual y desarrollo.
* **Presupuesto:** Disponibilidad financiera limitada, exigiendo herramientas de desarrollo gratuitas y capas libres de APIs.
* **Tecnología:** Complejidad computacional al adaptar Dijkstra a datos geográficos en tiempo real.
* **Personas:** Capacidad operativa individual asumiendo todos los roles del proyecto.

---

## 4. Requerimientos del Sistema

### Requerimientos Funcionales

1. El sistema debe permitir registrar información relacionada con las rutas logísticas utilizadas por las empresas, incluyendo origen, destino, distancia y tiempo estimado.
2. El sistema debe ofrecer una funcionalidad para optimizar rutas mediante el análisis de distancia, consumo de recursos y eficiencia operativa.
3. El sistema debe permitir gestionar proveedores logísticos y visualizar información relevante para evaluar prácticas responsables.
4. El sistema debe registrar y mostrar indicadores asociados al uso de recursos, como combustible, materiales y tiempos de operación.
5. El sistema debe proporcionar información en tiempo real sobre el estado de las rutas y actividades logísticas registradas.
6. El sistema debe generar reportes sobre eficiencia operativa, trazabilidad y uso de recursos para apoyar la toma de decisiones.
7. El sistema debe permitir visualizar métricas relacionadas con sostenibilidad y el impacto ambiental asociado a las actividades logísticas.
8. El sistema debe incluir un módulo para registrar y actualizar datos de vehículos utilizados en operaciones logísticas.
9. El sistema debe permitir a los usuarios consultar el historial de rutas, operaciones y reportes generados.
10. El sistema debe garantizar que los usuarios puedan acceder a las funcionalidades según su rol asignado.

### Requerimientos No Funcionales

1. El sistema debe mantener tiempos de respuesta adecuados, de manera que las consultas y operaciones principales se ejecuten sin retrasos perceptibles para el usuario.
2. El sistema debe asegurar la disponibilidad continua de la plataforma, permitiendo que los usuarios accedan a sus funcionalidades durante la mayor parte del tiempo operativo.
3. El sistema debe implementar medidas de seguridad que protejan los datos registrados, incluyendo autenticación de usuarios y manejo adecuado de información sensible.
4. La interfaz del sistema debe ser intuitiva, clara y fácil de utilizar, permitiendo que los usuarios realicen sus tareas sin necesidad de capacitaciones extensas.
5. El sistema debe estar diseñado de forma modular para facilitar futuras actualizaciones, mantenimiento y ampliación de funcionalidades sin afectar la operación principal.
6. El sistema debe ser compatible con navegadores web comunes para garantizar su accesibilidad desde diferentes dispositivos.
7. El sistema debe permitir un desempeño estable incluso en condiciones de carga moderada, manteniendo tiempos de respuesta adecuados a las operaciones realizadas.
8. Los datos almacenados deben gestionarse siguiendo buenas prácticas que aseguren integridad, consistencia y disponibilidad.
9. El sistema debe estar estructurado para garantizar escalabilidad en caso de aumentar el número de usuarios o el volumen de información registrada.
10. El diseño visual del sistema debe seguir criterios de claridad y orden, evitando elementos que dificulten la navegación o la composición de la información.

### Requerimientos de Dominio

1. El sistema debe calcular la distancia estimada entre puntos de origen y destino para cada ruta registrada.
2. El sistema debe estimar el tiempo aproximado de recorrido según la distancia y el tipo de vía seleccionada.
3. El sistema debe registrar y procesar datos relacionados con el consumo de recursos, como combustible o materiales utilizados en operaciones logísticas.
4. El sistema debe generar indicadores básicos de eficiencia como distancia recorrida, tiempo utilizado y consumo aproximado de recursos.
5. El sistema debe emplear unidades estandarizadas para todos los cálculos relacionados con distancia, tiempo y consumo.

---

## 5. Casos de Prueba Iniciales

* **CP-RF01-01: Registrar una ruta correctamente**
  * **Criterios de aceptación:** Origen y destino válidos y diferentes; distancia mayor a cero; tiempo estimado correcto.
* **CP-RF02-01: Optimizar una ruta correctamente**
  * **Criterios de aceptación:** Debe existir al menos una ruta registrada; la alternativa optimizada debe mostrar alguna mejora; la comparación entre rutas debe ser clara y entendible.
* **CP-RF03-01: Registrar un proveedor correctamente**
  * **Criterios de aceptación:** El proveedor debe tener un nombre válido y único; debe incluir al menos un medio de contacto; las certificaciones deben registrarse correctamente.
* **CP-RF04-01: Registrar consumo de recursos correctamente**
  * **Criterios de aceptación:** La cantidad registrada debe ser mayor a cero; el recurso debe asociarse a un vehículo u operación válida; las unidades deben coincidir.
* **CP-RF05-01: Generar un reporte correctamente**
  * **Criterios de aceptación:** Debe existir información para las fechas seleccionadas; los gráficos deben cargarse correctamente; la exportación debe funcionar correctamente.

---

## 6. Metodología de Trabajo y Ciclo de Vida

### 6.1 Enfoque del Ciclo de Vida
Se utilizará un **Ciclo de Vida Adaptativo (Ágil)**. Este enfoque permite evolucionar el proyecto mediante iteraciones (Sprints), ajustando el rumbo según los hallazgos técnicos (como la integración con la API de Google Maps) y asegurando la entrega temprana de valor funcional a los interesados.

### 6.2 Definición del Sprint
El trabajo se estructurará en iteraciones llamadas **Sprints**, con una duración fija de **2 semanas** cada uno. Cada Sprint incluirá las siguientes ceremonias para cumplir con los grupos de procesos:
* **Sprint Planning (Planificación):** Selección de requerimientos a trabajar.
* **Daily Scrum (Monitoreo y Control):** Seguimiento diario del progreso.
* **Sprint Review (Cierre de fase):** Demostración del incremento funcional.
* **Sprint Retrospective (Cierre):** Lecciones aprendidas y mejora continua.

### 6.3 Estimación de Desarrolladores y Capacidad
Para desarrollar esta plataforma en un entorno real con un plazo de **10 semanas (5 Sprints)**, dada la integración de algoritmos complejos y geolocalización, se estimaría un equipo ideal de **4 profesionales** (1 Backend Senior, 1 Frontend, 1 QA y 1 Scrum Master/PO). 
Sin embargo, bajo el contexto académico, el proyecto se ejecuta de forma individual, por lo que **Stuarth Fabricio Miranda Rojas asume todos los roles técnicos y de gestión**, priorizando las funciones críticas para cumplir con las 10 semanas de entrega.

### 6.4 Cronograma del Proyecto de Desarrollo de Software (A 10 Semanas)

| Fase / Tarea | Semanas 1-2 | Semanas 3-4 | Semanas 5-6 | Semanas 7-8 | Semanas 9-10 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **1. Planificación (Planning)** | | | | | |
| - Diseño de propuesta del proyecto (Project Charter) | ████ | | | | |
| - Análisis de entorno (EEF) y selección de recursos | ████ | | | | |
| - Elaboración de la proyección y cronograma a 10 semanas | ████ | | | | |
| **2. Análisis de Requerimientos** | | | | | |
| - Levantamiento y revisión de requerimientos funcionales | ████████ | | | | |
| - Creación del Product Backlog priorizado | | ████ | | | |
| - Definición del Sprint Backlog y Definition of Done (DoD) | | ████ | | | |
| **3. Diseño (Arquitectura y UI/UX)** | | | | | |
| - Evaluación de arquitectura técnica del sistema | | ████████ | | | |
| - Diseño del esquema relacional de Base de Datos SQL | | ████████ | | | |
| - Prototipado visual de interfaces web (Mockups) | | | ████ | | |
| **4. Desarrollo (Ejecución de Sprints)** | | | | | |
| - Desarrollo Backend (API FastAPI, Dijkstra, Haversine) | | | ████████ | ████ | |
| - Desarrollo Frontend (Vistas HTML/CSS/JS y formularios) | | | ████ | ████████ | |
| - Integración de API de Google Maps y cálculos | | | | ████████ | |
| **5. Pruebas y Despliegue (QA)** | | | | | |
| - Ejecución de Pruebas Unitarias y de Humo | | | ████ | ████ | |
| - Ejecución de Pruebas de Integración y Regresión | | | | ████ | ████████ |
| - Evaluación UAT, Presentación y Despliegue final | | | | | ████████ |

---

## 7. Product Backlog Priorizado

Los requerimientos funcionales han sido transformados en elementos del Backlog, agregando valor de negocio y priorizados según la dependencia técnica.

| ID | Prioridad | Elemento del Backlog (Historia de Usuario) | Criterios de Aceptación Básicos |
| :--- | :---: | :--- | :--- |
| **PB-01** | Alta | **Gestión de Accesos:** Como administrador, quiero asignar roles a los usuarios (Login) para garantizar la seguridad de la información. | Autenticación requerida. Roles diferenciados. Base de datos operativa. |
| **PB-02** | Alta | **Gestión de Vehículos:** Como gestor, quiero registrar y actualizar vehículos para controlar la flota logística disponible. | Placa única. Capacidad y consumo estimado definidos. |
| **PB-03** | Alta | **Registro de Rutas:** Como gestor, quiero registrar origen y destino para tener un catálogo de rutas operativas. | Origen y destino distintos. Almacenamiento en base de datos. |
| **PB-04** | Alta | **Gestión de Proveedores:** Como administrador, quiero registrar proveedores para evaluar sus prácticas responsables y certificaciones. | Nombre único. Medio de contacto. Campo de certificaciones ambientales. |
| **PB-05** | Media | **Cálculos de Rutas (Haversine/Dijkstra):** Como sistema, quiero optimizar rutas mediante algoritmos matemáticos y mapas para reducir tiempos y distancias. | Distancia > 0. Mejora operativa comprobable en comparación a rutas estándar. |
| **PB-06** | Media | **Indicadores de Consumo:** Como operario, quiero registrar el combustible y recursos usados para medir la eficiencia de la ruta. | Asociado a un vehículo/ruta. Cantidades mayores a cero. |
| **PB-07** | Media | **Métricas Ambientales (CO₂):** Como analista, quiero visualizar métricas de impacto ambiental para verificar el cumplimiento del ODS 9. | Cálculo de emisiones acorde a la distancia y consumo. Gráficos interactivos. |
| **PB-08** | Baja | **Historial General:** Como auditor, quiero consultar el historial de operaciones pasadas para trazabilidad. | Filtros por fecha y ruta. Ordenamiento cronológico. |
| **PB-09** | Baja | **Generación de Reportes:** Como administrador, quiero exportar la eficiencia operativa en PDF/Excel para presentar resultados. | Exportación funcional. Formato claro con tablas/gráficos. |
| **PB-10** | Baja | **Monitoreo en Tiempo Real:** Como gestor, quiero ver el estado actual de las rutas activas para reaccionar a incidencias. | Integración de mapas interactivos. Actualización de estado en pantalla. |

---

## 8. Planificación a 5 Sprints (Proyección de 10 semanas)

El alcance total del proyecto se ha distribuido en **5 Sprints de 2 semanas**, asegurando que cada incremento genere valor sin bloquear otros requerimientos técnicos.

* **Sprint 1 (Semanas 1-2) - "Estructura Base y Seguridad":** Desarrollo de la base de datos SQL, esquema principal, diseño UI básico, Login y control de roles (PB-01).
* **Sprint 2 (Semanas 3-4) - "Flota y Entidades Principales":** Módulo CRUD para registro de Vehículos (PB-02), Proveedores (PB-04) y Rutas básicas (PB-03).
* **Sprint 3 (Semanas 5-6) - "Inteligencia de Rutas":** Integración de Google Maps API, implementación de la fórmula de Haversine y algoritmo de Dijkstra para optimización (PB-05).
* **Sprint 4 (Semanas 7-8) - "Sostenibilidad y Recursos":** Registro de indicadores de consumo de combustible y desarrollo del cálculo de métricas de emisiones de CO₂ (PB-06, PB-07).
* **Sprint 5 (Semanas 9-10) - "Trazabilidad y Cierre":** Desarrollo del historial general, exportación de reportes PDF, y visualización del monitoreo operativo final (PB-08, PB-09, PB-10).

---

## 9. Sprint Backlog Detallado (Sprints Iniciales)

A continuación, se desglosan las tareas técnicas para los primeros dos Sprints del proyecto:

### Sprint Backlog - Sprint 1 (Estructura Base y Seguridad)
* **Tarea 1.1:** Diseñar y construir el script SQL para la base de datos logística (tablas Usuarios, Roles).
* **Tarea 1.2:** Configurar el entorno de desarrollo local y el servidor en Python (FastAPI).
* **Tarea 1.3:** Maquetar la estructura HTML/CSS de la página de Login.
* **Tarea 1.4:** Desarrollar el endpoint de autenticación segura (Backend).
* **Tarea 1.5:** Conectar el formulario de Login con el servidor y validar inicio de sesión.

### Sprint Backlog - Sprint 2 (Flota y Entidades Principales)
* **Tarea 2.1:** Extender la base de datos para incluir las tablas Vehículos, Proveedores y Rutas.
* **Tarea 2.2:** Desarrollar los endpoints (GET, POST) para guardar y leer Vehículos y Proveedores.
* **Tarea 2.3:** Crear las vistas HTML (formularios y tablas) para el registro de la flota.
* **Tarea 2.4:** Integrar alertas y mensajes de confirmación visuales en el Frontend tras cada registro.

---

## 10. Definition of Done (DoD) y Criterios de Calidad

Para asegurar la estabilidad técnica y operativa del sistema logístico, una historia de usuario o tarea técnica solo se considerará **"Terminada" (Done)** cuando cumpla obligatoriamente con la siguiente lista de verificación ejecutada por el rol de Quality Assurance (QA):

1. **El código ha sido revisado y documentado** según los estándares del proyecto.
2. **Pruebas Unitarias aprobadas:** El código lógico (Backend/FastAPI) pasa sus pruebas individuales de cálculo sin errores matemáticos.
3. **Pruebas de Humo (Smoke Testing) ejecutadas:** Tras el despliegue local, la funcionalidad crítica compila y las vistas HTML cargan correctamente sin fallos evidentes.
4. **Pruebas de Integración exitosas:** El Frontend interactúa correctamente con los endpoints del Backend y la base de datos SQL responde guardando la información íntegra.
5. **Pruebas de Regresión pasadas:** Se garantiza que la nueva función implementada (ej. optimizar ruta) no rompe funciones previas (ej. registrar vehículo).
6. Los Criterios de Aceptación especificados en el Product Backlog se cumplen a cabalidad.
7. Los tiempos de respuesta de la funcionalidad no superan los 2 segundos bajo carga normal.

---

## 11. Definición del Scrum Team a 10 Semanas

Nota aclaratoria: Al ser un proyecto de alcance individual, el estudiante **Stuarth Fabricio Miranda Rojas** asume las responsabilidades de todos los roles técnicos y de gestión (PO, SM, Frontend, Backend y QA) para garantizar la ejecución de las fases en las 10 semanas de plazo.

| Rol dentro del Scrum Team | Encargado | Enfoque Principal |
| :--- | :--- | :--- |
| **Product Owner / PM** | Stuarth Miranda | Negocio, priorización del Product Backlog, validación y cumplimiento de objetivos (ODS 9). |
| **Scrum Master** | Stuarth Miranda | Planificación de Sprints, remoción de bloqueos (ej. APIs) y gestión del proceso ágil. |
| **Frontend Developer** | Stuarth Miranda | Desarrollo de interfaces web (HTML/CSS/JS) y experiencia de usuario. |
| **Backend Developer** | Stuarth Miranda | Lógica de servidor (Python/FastAPI), algoritmos matemáticos (Dijkstra) y BD SQL. |
| **Analista de QA** | Stuarth Miranda | Definition of Done, pruebas unitarias, de integración, regresión y control de estabilidad. |

### Planificación Integral por Rol (Semanas 1 a 10)

| Semana | Product Owner & Scrum Master | Backend & Frontend Developer | Analista de Calidad (QA) |
| :---: | :--- | :--- | :--- |
| **1** | Project Charter, EEFs y reglas de trabajo. | Diseño de BD SQL y maquetación de Login. | Definición de estrategia de pruebas y DoD. |
| **2** | Creación del Product Backlog priorizado. | Setup FastAPI, endpoints de Auth y seguridad. | Ejecución de Pruebas Unitarias y Humo (Login). |
| **3** | Refinamiento de requerimientos de flota. | CRUD de Vehículos y Proveedores (BD y API). | Validación de formularios web y reglas de campos. |
| **4** | Sprint Review enfocado en entidades base. | Vistas de listado y registro de rutas simples. | Pruebas de Integración (Front-Back) para registros. |
| **5** | Priorización operativa (Google Maps). | Implementación matemática de Haversine. | Verificación matemática de distancias calculadas. |
| **6** | Revisión de inteligencia de rutas (Dijkstra). | Algoritmo de rutas óptimas y conexión API. | Pruebas de usabilidad en mapa e integración API. |
| **7** | Validación técnica y gestión de capacidad. | Lógica de recolección de consumo de recursos. | Pruebas de Humo en nuevos módulos de consumo. |
| **8** | Definición de paneles de ODS 9 (CO₂). | Gráficos y cálculo matemático de emisiones. | Validación de precisión de indicadores ambientales. |
| **9** | Refinamiento de requerimientos de trazabilidad. | Generación de PDF/Excel e historial general. | Ejecución de Pruebas de Regresión completas. |
| **10** | Presentación, cierre y entrega final. | Despliegue, optimización de velocidad de BD. | Verificación de tiempos de carga (< 2s) y UAT. |