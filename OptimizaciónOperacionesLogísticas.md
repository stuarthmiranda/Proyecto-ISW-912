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
| **0.2** | 23/09/2026 | Semana 2 / Fase 3 | Incorporación del análisis de contexto organizacional (EEF), mapa de 8 interesados (poder e interés) y restricciones conocidas. | Stuarth Fabricio Miranda Rojas |
| **0.3** | 04/10/2026 | Semana 3 | Integración de requerimientos del sistema, casos de prueba iniciales y definición de roles del Scrum Team a 14 semanas. | Stuarth Fabricio Miranda Rojas |

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
---
## Contexto del Proyecto e Interesados

### 1. Análisis del Entorno Organizacional y Factores Ambientales (EEF)

#### Estructura Organizacional
El desarrollo del proyecto se plantea bajo una estructura matricial orientada a proyectos dentro del ámbito informático. Esta estructura permite contar con la autoridad necesaria para la toma de decisiones técnicas y de gestión sobre la plataforma, coordinando las actividades del equipo de desarrollo con los requerimientos operativos de la empresa logística.

#### Factores Ambientales de la Empresa (EEF)
* **Factores Internos:**
  * Infraestructura tecnológica disponible para el alojamiento y despliegue de la plataforma web.
  * Capacidad y experiencia del equipo de desarrollo en la implementación de algoritmos como Dijkstra y Haversine.
  * Canales de comunicación interna y herramientas para el seguimiento de la gestión del proyecto.

* **Factores Externos:**
  * Servicios de información geográfica de Google Maps y sus condiciones de uso o límites de consulta de la API.
  * Normativas ambientales vigentes relacionadas con el control y reporte de emisiones de CO₂.
  * Condiciones de las vías y tipos de carretera en las zonas donde operan los vehículos de transporte.

---

### 2. Identificación de Interesados (Stakeholders) y Mapa de Poder e Interés

| Interesado / Stakeholder | Rol en el Proyecto | Nivel de Poder | Nivel de Interés | Estrategia de Gestión |
| :--- | :--- | :--- | :--- | :--- |
| Gerencia General / Sponsor del Proyecto | Aprobación de recursos y alineación estratégica del negocio | Alto | Alto | Gestionar de cerca mediante reportes periódicos de avance y valor entregado. |
| Encargados de operaciones logísticas | Planificación de rutas, asignación de cargas y gestión diaria | Alto | Alto | Gestionar de cerca para asegurar que el sistema responda a las necesidades operativas reales. |
| Director de Proyecto (PM) | Liderazgo, integración y control del cumplimiento de objetivos | Alto | Alto | Gestionar de cerca, coordinando al equipo y facilitando la toma de decisiones. |
| Equipo de desarrollo de software | Diseño, arquitectura, desarrollo e implementación del sistema | Medio | Alto | Mantener informados y empoderados durante la definición de requerimientos y algoritmos. |
| Conductores / Transportistas de la flota | Usuarios finales que ejecutan las rutas asignadas | Bajo | Alto | Mantener informados y recopilar retroalimentación sobre la usabilidad y precisión de las rutas. |
| Jefatura de Mantenimiento Vehicular | Registro y control del estado mecánico y mantenimientos preventivos | Medio | Medio | Mantener satisfechos integrando los módulos de control mecánico y alertas preventivas. |
| Clientes / Destinatarios finales de la carga | Receptores del servicio de transporte y seguimiento de entrega | Bajo | Alto | Mantener informados sobre los tiempos estimados de llegada y estado del paquete. |
| Entidades de regulación ambiental y ODS | Auditoría y evaluación del impacto ambiental e indicadores de CO₂ | Medio | Bajo | Mantener satisfechos mediante la generación de reportes precisos de huella de carbono. |

---

### 3. Restricciones Conocidas del Proyecto

* **Tiempo:** El marco temporal definido dentro del periodo académico para completar el análisis, definición de requerimientos y diseño conceptual de la plataforma.
* **Presupuesto:** La disponibilidad de recursos financieros limitados, lo que exige el uso de herramientas de desarrollo gratuitas, librerías de código abierto y capas de uso libre de APIs geográficas.
* **Tecnología:** La necesidad de adaptar el cálculo de algoritmos como Dijkstra a datos geográficos en tiempo real, considerando la complejidad computacional y las limitaciones de cuota en las consultas a Google Maps.
* **Personas:** La capacidad operativa del equipo de estudiantes asignado para asumir los roles del proyecto, requiriendo una distribución eficiente del trabajo.

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

Para garantizar la calidad del sistema, se definen los siguientes casos de prueba principales basados en los requerimientos funcionales críticos:

* **CP-RF01-01: Registrar una ruta correctamente**
  * **Descripción:** El usuario con permisos ingresa al módulo de Rutas, completa los datos de la ruta. Al guardar, el sistema valida la información y registra la ruta, mostrándola inmediatamente en el listado de rutas disponibles.
  * **Criterios de aceptación:** Origen y destino válidos y diferentes; distancia mayor a cero; tiempo estimado correcto.

* **CP-RF02-01: Optimizar una ruta correctamente**
  * **Descripción:** El usuario ingresa al módulo de Optimización de Rutas, selecciona una ruta previamente registrada y solicita la optimización. El sistema analiza información y genera una alternativa optimizada mostrando las mejoras detectadas.
  * **Criterios de aceptación:** Debe existir al menos una ruta registrada; la alternativa optimizada debe mostrar alguna mejora; la comparación entre rutas debe ser clara y entendible.

* **CP-RF03-01: Registrar un proveedor correctamente**
  * **Descripción:** El usuario autorizado accede al módulo de Proveedores y completa los datos solicitados de un nuevo proveedor, incluyendo sus certificaciones ambientales. Al guardar, el sistema valida la información y registra el proveedor.
  * **Criterios de aceptación:** El proveedor debe tener un nombre válido y único; debe incluir al menos un medio de contacto; las certificaciones deben registrarse correctamente.

* **CP-RF04-01: Registrar consumo de recursos correctamente**
  * **Descripción:** El usuario autorizado ingresa al módulo de Indicadores, selecciona registrar consumo y completa los datos. El sistema valida la información y registra el consumo, asociándolo a la ruta, vehículo o actividad.
  * **Criterios de aceptación:** La cantidad registrada debe ser mayor a cero; el recurso debe asociarse a un vehículo u operación válida; las unidades deben coincidir.

* **CP-RF05-01: Generar un reporte correctamente**
  * **Descripción:** El usuario ingresa al módulo de Reportes, selecciona el tipo de reporte y define filtros. El sistema recopila los datos, procesa la información y genera un reporte visual con gráficos que puede ser exportado a PDF.
  * **Criterios de aceptación:** Debe existir información para las fechas seleccionadas; los gráficos deben cargarse correctamente; la exportación debe funcionar correctamente.

---

## 6. Definición del Scrum Team (Roles, Responsabilidades y Plan a 14 Semanas)

Para alinear el desarrollo del sistema con la metodología ágil y las tecnologías seleccionadas, el trabajo se distribuye de manera semanal entre 5 roles específicos dentro del Scrum Team.

| Rol dentro del Scrum Team | Enfoque Principal |
| :--- | :--- |
| **Product Owner (PO) / PM** | Negocio, priorización del Product Backlog y cumplimiento de objetivos (ODS 9). |
| **Scrum Master** | Facilitación, remoción de bloqueos y gestión del proceso ágil. |
| **Frontend Developer** | Desarrollo de interfaces web (HTML/CSS/JS) y experiencia de usuario. |
| **Backend Developer** | Lógica de servidor (Python/FastAPI), algoritmos matemáticos y base de datos SQL. |
| **Analista de Calidad (QA)** | Pruebas, validación de requerimientos y control de estabilidad del sistema. |

### 1. Product Owner (PO) / Project Manager (PM)
**Responsabilidad:** Maximizar el valor del producto, gestionar el Product Backlog y asegurar que la plataforma cumpla con los objetivos de negocio y el ODS 9 (sostenibilidad).

| Semana | Tareas y Responsabilidades del Rol |
| :---: | :--- |
| **1** | Definición del Project Charter y visión general del producto. |
| **2** | Análisis del entorno organizacional (EEF) e identificación de interesados. |
| **3** | Creación inicial del Product Backlog (Rutas, Proveedores, Vehículos). |
| **4** | Refinamiento de historias de usuario con el equipo técnico. |
| **5** | Validación de los primeros prototipos visuales (Login y Dashboard). |
| **6** | Priorización de tareas operativas para el cálculo de distancias y tiempos. |
| **7** | Aceptación del módulo de registro de vehículos y proveedores. |
| **8** | Revisión de la lógica de optimización (Dijkstra/Haversine) desde la perspectiva de negocio. |
| **9** | Validación de la integración y los datos geográficos de Google Maps. |
| **10** | Refinamiento de los requerimientos para el módulo de métricas ambientales (CO₂). |
| **11** | Aceptación del módulo de reportes y validación de la trazabilidad. |
| **12** | Pruebas de aceptación de usuario (UAT) sobre la plataforma completa. |
| **13** | Gestión de últimos cambios en el alcance y preparación del entregable final. |
| **14** | Presentación final del producto ante interesados y cierre formal. |

### 2. Scrum Master
**Responsabilidad:** Facilitar el proceso ágil, remover bloqueos operativos y técnicos, y asegurar que el equipo trabaje en un entorno colaborativo.

| Semana | Tareas y Responsabilidades del Rol |
| :---: | :--- |
| **1** | Definición del Scrum Team y establecimiento de reglas de trabajo interno. |
| **2** | Configuración del entorno de gestión (ej. GitHub Projects/Trello). |
| **3** | Facilitación de la primera planificación de Sprint (Sprint Planning). |
| **4** | Resolución de impedimentos iniciales (gestión de llaves de API de Google Maps). |
| **5** | Facilitación de Daily Stand-ups y monitoreo de avances. |
| **6** | Facilitación de retrospectiva temprana para ajustar procesos del equipo. |
| **7** | Remoción de bloqueos técnicos de integración entre Frontend y Backend. |
| **8** | Facilitación de Sprint Review enfocado en el algoritmo de rutas. |
| **9** | Gestión de la capacidad del equipo para evitar sobrecargas operativas. |
| **10** | Asegurar comunicación fluida entre Developers y Analista de Calidad (QA). |
| **11** | Seguimiento exhaustivo a la corrección de errores (bugs) detectados. |
| **12** | Facilitación de la penúltima planificación enfocada en pulir detalles. |
| **13** | Preparación para el cierre administrativo del proyecto logístico. |
| **14** | Retrospectiva final y documentación técnica de lecciones aprendidas. |

### 3. Frontend Developer
**Responsabilidad:** Construir la interfaz de usuario web utilizando HTML, CSS y JavaScript, garantizando una navegación responsiva, fluida y orientada a la experiencia del operario logístico.

| Semana | Tareas y Responsabilidades del Rol |
| :---: | :--- |
| **1** | Planificación de la estructura de vistas web y diseño UI básico. |
| **2** | Definición de la paleta de colores y estilos CSS base. |
| **3** | Maquetación responsiva del Login y Panel Principal (Dashboard). |
| **4** | Creación de formularios HTML para el registro de rutas y vehículos. |
| **5** | Desarrollo de las vistas de listado y gestión de proveedores. |
| **6** | Integración inicial de JavaScript para validaciones en el cliente (formularios). |
| **7** | Incorporación de la vista del mapa para el monitoreo de rutas. |
| **8** | Conexión de la interfaz web con los primeros endpoints de la API (Backend). |
| **9** | Renderizado visual de la ruta óptima sugerida en el mapa interactivo. |
| **10** | Desarrollo de paneles gráficos interactivos para métricas de sostenibilidad. |
| **11** | Creación de la interfaz para la generación, filtrado y descarga de reportes. |
| **12** | Manejo de estados de error y mensajes de éxito al usuario (UI polish). |
| **13** | Optimización de carga de archivos estáticos y rendimiento de renderizado web. |
| **14** | Despliegue de la aplicación cliente y resolución de errores visuales finales. |

### 4. Backend Developer
**Responsabilidad:** Diseñar la arquitectura de la base de datos SQL, programar la lógica de negocio y desarrollar la API REST utilizando Python (FastAPI).

| Semana | Tareas y Responsabilidades del Rol |
| :---: | :--- |
| **1** | Diseño del modelo relacional y diagramas de base de datos SQL. |
| **2** | Configuración del entorno de desarrollo local en FastAPI (Python). |
| **3** | Creación del esquema SQL y conexión inicial a la base de datos. |
| **4** | Desarrollo del CRUD básico para vehículos y proveedores (API REST). |
| **5** | Desarrollo de endpoints para el registro y consulta de historial de rutas. |
| **6** | Implementación inicial de la fórmula de Haversine para cálculo de distancias. |
| **7** | Configuración de consultas seguras a la API de Google Maps (datos geográficos). |
| **8** | Programación e integración del algoritmo de Dijkstra para rutas eficientes. |
| **9** | Ajuste, parseo y optimización de las respuestas JSON de la API. |
| **10** | Implementación de la lógica matemática de cálculo de emisiones (CO₂). |
| **11** | Generación de la estructura de datos para la exportación de reportes (PDF/Excel). |
| **12** | Integración de filtros de búsqueda complejos para el historial general del sistema. |
| **13** | Refactorización de código Python y optimización de consultas SQL (latencia). |
| **14** | Preparación del servidor, despliegue del Backend y monitoreo de estabilidad. |

### 5. Analista de Calidad (QA)
**Responsabilidad:** Validar que los incrementos de software cumplan con los requerimientos, manteniendo tiempos de respuesta óptimos y garantizando la fiabilidad de las métricas.

| Semana | Tareas y Responsabilidades del Rol |
| :---: | :--- |
| **1** | Definición de la estrategia general de pruebas del proyecto. |
| **2** | Estructuración de los casos de prueba formales basados en los requerimientos. |
| **3** | Revisión de usabilidad sobre los flujos de navegación planificados. |
| **4** | Validación de campos obligatorios y restricciones en formularios (Frontend). |
| **5** | Ejecución de pruebas unitarias sobre los primeros endpoints de FastAPI. |
| **6** | Ejecución del caso de prueba CP-RF01-01 (Registro de rutas). |
| **7** | Validación técnica de precisión en los cálculos de distancia (Haversine). |
| **8** | Ejecución del caso de prueba CP-RF02-01 (Optimización de rutas con Dijkstra). |
| **9** | Reporte de defectos (bugs) encontrados en la integración del mapa interactivo. |
| **10** | Ejecución de pruebas funcionales para métricas ambientales y de recursos (CP-RF04-01). |
| **11** | Ejecución del caso CP-RF05-01 (Generación y exportación de reportes). |
| **12** | Pruebas de compatibilidad en múltiples navegadores (Chrome, Edge, Safari). |
| **13** | Ejecución de pruebas de regresión y verificación de tiempos de respuesta (< 2s). |
| **14** | Validación final de estabilidad y emisión del reporte de calidad para el cierre. |