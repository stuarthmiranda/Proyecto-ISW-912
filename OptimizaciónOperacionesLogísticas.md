# Universidad Técnica Nacional
## Sede San Carlos
### Carrera: Ingeniería del Software

**Curso:** Administración de Proyectos Informáticos  
**Código de curso:** ISW-912  
**Integrantes:** Stuarth Fabricio Miranda Rojas, Cristopher Quiros Araya y Miguel Cruz Vargas  
**Profesor:** Deiver Cubero Molina  

---

## Historial de Versiones / Control de Cambios

| Versión | Fecha | Semana o Fase | Descripción del Cambio | Autor |
| :---: | :---: | :---: | :--- | :--- |
| **0.1** | 23/09/2026 | Semana 1 | Definición inicial de la idea del proyecto, problema, propuesta, valor esperado y objetivos. | Stuarth Fabricio Miranda Rojas |
| **0.2** | 23/09/2026 | Semana 2 / Fase 3 | Incorporación del análisis de contexto organizacional (EEF), mapa de interesados y restricciones conocidas. | Stuarth Fabricio Miranda Rojas |
| **0.3** | 04/10/2026 | Semana 3 | Integración de requerimientos del sistema, casos de prueba iniciales y definición de roles. | Stuarth Fabricio Miranda Rojas |
| **0.4** | 14/10/2026 | Semana 4 | Implementación de ciclo de vida ágil, proyección a 10 semanas (5 Sprints), Product Backlog, DoD y cronograma. | Stuarth Fabricio Miranda Rojas |
| **0.5** | 21/10/2026 | Semana 5 | Desglose completo de los requerimientos en Historias de Usuario (regla de las 3 C's). | Stuarth Fabricio Miranda Rojas |
| **0.6** | 21/10/2026 | Semana 5 | Optimización y recorte del alcance para enfocar el valor de negocio. | Stuarth Fabricio Miranda Rojas |
| **0.7** | 21/10/2026 | Semana 5 | División de historia de 13 puntos en dos (HU-02 y HU-03) y renumeración del Backlog para calzar con la velocidad de 8 puntos/Sprint. | Stuarth Fabricio Miranda Rojas |
| **0.8** | 04/11/2026 | Actualización de integrantes | Adaptación del proyecto a tres integrantes, sin cambios en el alcance, historias, requerimientos, puntos ni cronograma originales. | Equipo de desarrollo (3 integrantes) |
| **0.9** | 04/11/2026 | Plan de Comunicaciones | Incorporación del Plan de Comunicaciones y su referencia al tablero existente de Notion, sin cambios en el alcance ni en la planificación originales. | Equipo de desarrollo (3 integrantes) |
| **0.10** | 04/11/2026 | Definiciones de organización y comunicación | Asignación de responsabilidades y definición de horarios, WIP, registros, validación y escalamiento por instrucción del solicitante, conservando el alcance, los puntos y el cronograma. | Equipo de desarrollo (3 integrantes) |
| **0.11** | 04/11/2026 | Semana 8 / Fase 3: Trabajo Colaborativo | Incorporación de matriz de riesgos, mapa de calor, plan de mitigación y adquisiciones críticas, sin modificar el alcance, las estimaciones ni la planificación original. | Equipo de desarrollo (3 integrantes) |
| **0.12** | 09/11/2026 | Semana 8 / Integración de mitigaciones al Sprint Backlog | Incorporación de acciones de mitigación al Sprint Backlog de los Sprints 1, 2 y 3, y actividades de seguimiento para R-08 y R-09. | Equipo de desarrollo (3 integrantes) |
| **0.13** | 10/11/2026 | Semana 8 / Actualización del backlog | Registro del avance documental realizado, estado verificable de las 11 historias y tareas técnicas, y pendientes de ejecución, validación y planificación. | Actualización asistida para revisión del equipo |
---

## Tema/Nombre:
Sistema inteligente para gestión y optimización de operaciones logísticas

## Problema:
Las empresas dedicadas al transporte y logística pueden presentar dificultades para planificar rutas eficientes, controlar el consumo de recursos, dar seguimiento al estado de sus vehículos y medir el impacto ambiental de sus operaciones.

En algunos casos, estas decisiones se realizan de forma manual o basándose principalmente en la experiencia de los encargados, lo que puede provocar recorridos innecesarios, mayor consumo de combustible, dificultades para controlar el mantenimiento de los vehículos y poca información para evaluar la eficiencia de las operaciones.

El proyecto busca abordar esta problemática mediante una solución digital que permita centralizar y analizar la información relacionada con rutas, vehículos, consumo y sostenibilidad. Esto mantiene el enfoque original del proyecto hacia la modernización de los procesos logísticos y el ODS 9.

## Proyecto propuesto:
Se propone desarrollar conceptualmente una plataforma web para la gestión y optimización de operaciones logísticas, que permita registrar vehículos, rutas, consumo de recursos, mantenimiento y diferentes indicadores de eficiencia y sostenibilidad.

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
* **Personas:** Equipo de desarrollo (3 integrantes). Distribución de responsabilidades individuales definida en la sección 11.

---

## 4. Requerimientos del Sistema (Versión Optimizada)

### Requerimientos Funcionales
1. El sistema debe permitir registrar información relacionada con las rutas logísticas utilizadas por las empresas, incluyendo origen, destino, distancia y tiempo estimado.
2. El sistema debe ofrecer una funcionalidad visual en mapas y optimizar rutas mediante el análisis de distancia, consumo de recursos y eficiencia operativa.
3. El sistema debe registrar y mostrar indicadores asociados al uso de recursos, como combustible, materiales y tiempos de operación.
4. El sistema debe generar reportes sobre eficiencia operativa, trazabilidad y uso de recursos para apoyar la toma de decisiones.
5. El sistema debe permitir visualizar métricas relacionadas con sostenibilidad y el impacto ambiental asociado a las actividades logísticas.
6. El sistema debe incluir un módulo para registrar y actualizar datos de vehículos utilizados en operaciones logísticas.
7. El sistema debe garantizar que los usuarios puedan acceder a las funcionalidades según su rol asignado.

### Requerimientos No Funcionales
1. El sistema debe mantener tiempos de respuesta adecuados (menores a 2 segundos) en consultas principales.
2. El sistema debe implementar medidas de seguridad y autenticación que protejan los datos registrados.
3. La interfaz del sistema debe ser intuitiva, clara y fácil de utilizar sin necesidad de capacitaciones extensas.
4. El sistema debe ser compatible con navegadores web comunes para garantizar su accesibilidad.
5. Los datos almacenados deben gestionarse siguiendo buenas prácticas que aseguren integridad relacional y consistencia.

### Requerimientos de Dominio
1. El sistema debe calcular la distancia estimada y el tiempo de recorrido entre puntos de origen y destino utilizando la fórmula de Haversine y datos geográficos.
2. El sistema debe procesar matemáticamente el consumo de recursos para generar indicadores de eficiencia y emisiones.
3. El sistema debe emplear unidades estandarizadas (kilómetros, horas, litros) para todos los cálculos.

---

## 5. Casos de Prueba Iniciales

* **CP-RF01-01: Registrar una ruta correctamente**
  * **Criterios de aceptación:** Origen y destino válidos y diferentes; distancia mayor a cero; tiempo estimado correcto.
* **CP-RF02-01: Visualizar y Optimizar una ruta correctamente**
  * **Criterios de aceptación:** Debe existir al menos una ruta registrada; el mapa debe dibujarse sin errores y la alternativa optimizada debe mostrar alguna mejora clara en la comparación.
* **CP-RF03-01: Registrar consumo de recursos correctamente**
  * **Criterios de aceptación:** La cantidad registrada debe ser mayor a cero; el recurso debe asociarse a un vehículo o ruta válida.
* **CP-RF04-01: Generar un reporte correctamente**
  * **Criterios de aceptación:** Debe existir información para las fechas seleccionadas; el archivo debe exportarse con datos reales y legibles.

---

## 6. Metodología de Trabajo y Ciclo de Vida

### 6.1 Enfoque del Ciclo de Vida
Se utilizará un **Ciclo de Vida Adaptativo (Ágil)**. Este enfoque permite evolucionar el proyecto mediante iteraciones (Sprints), ajustando el rumbo según los hallazgos técnicos y asegurando la entrega temprana de valor funcional.

### 6.2 Definición del Sprint
El trabajo se estructurará en iteraciones llamadas **Sprints**, con una duración fija de **2 semanas** cada uno. Cada Sprint incluirá las ceremonias: Sprint Planning, Daily Scrum, Sprint Review y Sprint Retrospective.

### 6.3 Estimación de Desarrolladores y Capacidad
Para desarrollar esta plataforma en un entorno real con un plazo de **10 semanas (5 Sprints)**, se estimaría un equipo ideal de **4 profesionales** (1 Backend Senior, 1 Frontend, 1 QA y 1 Scrum Master/PO). El proyecto se desarrolla por el **Equipo de desarrollo (3 integrantes)**: **Stuarth Fabricio Miranda Rojas, Cristopher Quiros Araya y Miguel Cruz Vargas**. Se conserva la capacidad de planificación original de **8 puntos de historia por Sprint**, sin aumentarla por el número de integrantes. Distribución de responsabilidades individuales definida en la sección 11.

### 6.4 Cronograma del Proyecto de Desarrollo de Software (A 10 Semanas)

| Fase / Tarea | Semanas 1-2 | Semanas 3-4 | Semanas 5-6 | Semanas 7-8 | Semanas 9-10 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **1. Planificación (Planning)** | | | | | |
| - Diseño de propuesta y Project Charter | ████ | | | | |
| - Análisis de entorno y recursos | ████ | | | | |
| **2. Análisis de Requerimientos** | | | | | |
| - Levantamiento y optimización de alcance | ████████ | | | | |
| - Creación de Historias de Usuario | | ████ | | | |
| **3. Diseño (Arquitectura y UI/UX)** | | | | | |
| - Diseño de BD y Arquitectura | | ████████ | | | |
| - Prototipado visual (Mockups) | | | ████ | | |
| **4. Desarrollo (Ejecución Sprints)**| | | | | |
| - Backend y Algoritmos | | | ████████ | ████ | |
| - Frontend y Vistas Web | | | ████ | ████████ | |
| **5. Pruebas y Despliegue (QA)** | | | | | |
| - Pruebas Unitarias y de Integración | | | | ████ | ████████ |
| - Despliegue final y Reportes | | | | | ████████ |

---

## 7. Product Backlog Priorizado (Historias de Usuario Optimizadas)

A continuación, se detallan las 11 Historias de Usuario principales que engloban el núcleo funcional y técnico del proyecto.

### Estado del backlog al corte de Semana 8 — 10/11/2026

El corte corresponde a la Semana 8 indicada por el equipo. Se revisaron este documento, el historial Git y la página de Notion referenciada en la sección 12. La página consultada conserva una última edición del 04/11/2026, hora de Guatemala, y describe HU-01 y HU-02 sin avances confirmados; no acredita el cierre de historias. El repositorio contiene únicamente este Markdown, sin código ni resultados de pruebas. Por ello, **«Por confirmar» significa que no hay evidencia suficiente para determinar si el trabajo se inició o terminó**, y no equivale a declarar que no se ha trabajado.

#### Trabajo documental realizado

Los siguientes entregables están elaborados en el expediente. Su estado acredita documentación existente, no aprobación del profesor ni implementación del software. Este seguimiento no añade historias ni puntos al Product Backlog.

| Actividad | Estado al corte | Evidencia en el documento |
| --- | --- | --- |
| Definir problema, propuesta, valor y objetivos. | Elaborado | Tema, Problema, Proyecto propuesto, Valor esperado y Objetivos completos. |
| Analizar entorno, interesados y restricciones. | Elaborado | Contexto del Proyecto e Interesados. |
| Definir requisitos y casos de prueba iniciales. | Elaborado | Secciones 4 y 5; los casos están definidos, sin ejecución acreditada. |
| Definir metodología, cronograma y capacidad. | Elaborado | Sección 6: 10 semanas, 5 Sprints y 8 puntos por Sprint. |
| Desglosar y estimar las 11 historias de usuario. | Elaborado | Sección 7; versiones 0.5–0.7. |
| Preparar Release Plan, tareas iniciales y DoD. | Elaborado | Secciones 8, 9 y 10. |
| Adaptar el equipo a tres integrantes y asignar responsabilidades. | Elaborado | Sección 11; versiones 0.8 y 0.10. |
| Establecer plan de comunicaciones, WIP y reglas de validación. | Elaborado | Sección 12; versiones 0.9–0.10. |
| Elaborar matriz de diez riesgos, mapa de calor, mitigaciones y adquisiciones críticas. | Elaborado | Sección 13; versión 0.11. |
| Incorporar mitigaciones y seguimiento al Sprint Backlog. | Elaborado | Sección 9; versión 0.12. Su ejecución sigue pendiente de acreditar. |

#### Estado de las historias y trabajo restante

| Historia | Puntos | Sprint original | Estado verificable | Pendiente para acreditar su cierre |
| --- | :---: | :---: | --- | --- |
| HU-01 — Registro de rutas | 3 | 1 | Por confirmar | Aportar esquema SQL, formulario y guardado integrado (1.1–1.3); validar CP-RF01-01 y DoD. |
| HU-02 — Mapas | 5 | 1 | Por confirmar | Acreditar acceso y condiciones de uso de Maps, integración y dibujo de origen/destino (1.4–1.5); validar DoD. |
| HU-03 — Optimización con Dijkstra | 8 | 2 | Por confirmar | Aportar grafo, algoritmo, endpoint y resultados de pruebas (2.1–2.4); validar ruta mínima y DoD. |
| HU-04 — Registro de recursos | 5 | 4 | Por confirmar | Acreditar registro de combustible/materiales asociado al vehículo correcto y DoD. |
| HU-05 — Reportes de eficiencia | 5 | Sin asignar | Sin programación; ejecución por confirmar | Resolver su planificación y acreditar exportación por fechas en PDF o Excel y DoD. |
| HU-06 — Panel de CO₂ | 8 | 5 | Por confirmar | Acreditar gráficos de emisiones a partir de datos de consumo y DoD. |
| HU-07 — Catálogo de vehículos | 3 | 3 | Por confirmar | Acreditar registro y actualización de vehículos, validación de placa y DoD. |
| HU-08 — Accesos por roles | 5 | 3 | Por confirmar | Acreditar permisos y bloqueo de acceso de operario a reportes gerenciales, mitigación R-07 y DoD. |
| HU-09 — Cálculo geoespacial | 5 | Sin asignar | Sin programación; ejecución por confirmar | Resolver su planificación; acreditar Haversine, unidades, base del tiempo estimado, control R-04 y DoD. |
| HU-10 — Procesamiento de eficiencia | 3 | 4 | Por confirmar | Acreditar procesamiento y almacenamiento de indicadores a partir de combustible/tiempo y DoD. |
| HU-11 — Rendimiento, integridad y UX | 5 | Sin asignar | Sin programación; ejecución por confirmar | Resolver su planificación; acreditar respuesta menor a 2 segundos, integridad, usabilidad y compatibilidad, conforme a requisitos y DoD. |

**Balance verificable:** 11 historias y 55 puntos en el Product Backlog; 8 historias y 40 puntos programados; 3 historias y 15 puntos sin Sprint (HU-05, HU-09 y HU-11). **Ninguna historia tiene cierre acreditado en las fuentes consultadas**; esto no permite calcular el avance real ni concluir que el avance sea 0 %. Los responsables y revisores se mantienen en la sección 11. No se asigna «En proceso», «Hecho» ni «Bloqueada» sin un registro que lo sustente.

#### Pendientes de seguimiento

- Cada responsable debe confirmar el estado real de sus historias y tareas, adjuntar evidencia disponible y señalar lo que falte por ejecutar. El revisor verificará el DoD antes de acreditar el cierre.
- Cristopher debe conciliar con el tablero las asignaciones y reglas ya definidas en las secciones 11 y 12: la página de Notion consultada todavía las presenta como pendientes o propuestas. Esta actualización registra la discrepancia, sin modificar Notion.
- Stuarth debe canalizar la decisión sobre los 15 puntos sin Sprint. Se mantiene la programación original de 40 puntos mientras no exista una decisión registrada.
- Los dueños de riesgos deben registrar la ejecución de las mitigaciones y la revisión prevista para el 11/11/2026. Elaborar el plan no demuestra que sus controles se hayan aplicado.

### 7.1 Historias Funcionales Centrales

#### HU-01: Registro de rutas logísticas
* **Como** gestor logístico
* **Quiero** registrar la información detallada de las rutas (origen, destino, distancia y tiempo estimado)
* **Para** centralizar el catálogo de recorridos operativos.
* **Criterios de Aceptación:**
  * **Criterio 1:** Dado que estoy en el formulario, cuando ingreso datos válidos, entonces el sistema guarda la ruta.
* **Prioridad:** Alta. **Estimación:** 3 puntos.
* **Justificación:** Es un desarrollo directo de formulario (CRUD básico) sin integraciones externas.

#### HU-02: Visualización de rutas en mapas (Frontend)
* **Como** gestor logístico
* **Quiero** visualizar las rutas y ubicaciones en un mapa interactivo
* **Para** tener una referencia gráfica clara de los recorridos operativos en la pantalla.
* **Criterios de Aceptación:**
  * **Criterio 1:** Dado que ingreso a una ruta registrada, cuando carga la pantalla, entonces el mapa muestra el origen y el destino.
* **Prioridad:** Alta. **Estimación:** 5 puntos.
* **Justificación:** Implica integrar la API de Google Maps en el frontend (diseño visual), lo que requiere esfuerzo de interfaz pero no incluye la matemática pesada.

#### HU-03: Algoritmo de optimización de rutas (Backend)
* **Como** sistema (Backend)
* **Quiero** ejecutar un algoritmo inteligente para analizar y encontrar la ruta más eficiente
* **Para** ofrecer alternativas que reduzcan los tiempos de transporte y costos operativos.
* **Criterios de Aceptación:**
  * **Criterio 1:** Dado que hay rutas disponibles, cuando solicito la optimización, entonces el sistema analiza usando Dijkstra y devuelve la alternativa más corta.
* **Prioridad:** Alta. **Estimación:** 8 puntos.
* **Justificación:** Requiere programar la lógica matemática desde cero en Python y asegurar que los cálculos de las rutas y grafos no tengan errores de servidor.

#### HU-04: Registro de indicadores de recursos
* **Como** operario logístico
* **Quiero** registrar el consumo de combustible y materiales
* **Para** medir la eficiencia operativa del viaje.
* **Criterios de Aceptación:**
  * **Criterio 1:** Dado que ingreso el combustible usado, cuando guardo, entonces se asocia al vehículo correcto.
* **Prioridad:** Media. **Estimación:** 5 puntos.

#### HU-05: Generación de reportes de eficiencia
* **Como** administrador
* **Quiero** generar reportes exportables de las operaciones
* **Para** apoyar la toma de decisiones gerenciales.
* **Criterios de Aceptación:**
  * **Criterio 1:** Dado que selecciono fechas, cuando exporto, entonces obtengo un archivo PDF o Excel.
* **Prioridad:** Baja. **Estimación:** 5 puntos.

#### HU-06: Panel de métricas de sostenibilidad (CO₂)
* **Como** analista ambiental
* **Quiero** visualizar gráficos de huella de carbono
* **Para** verificar el cumplimiento del ODS 9.
* **Criterios de Aceptación:**
  * **Criterio 1:** Dado que hay datos de consumo, cuando entro al panel, entonces veo gráficos con las emisiones.
* **Prioridad:** Media. **Estimación:** 8 puntos.

#### HU-07: Gestión del catálogo de vehículos
* **Como** gestor logístico
* **Quiero** registrar y actualizar la información de los vehículos
* **Para** controlar la flota disponible.
* **Criterios de Aceptación:**
  * **Criterio 1:** Dado que ingreso una placa válida, cuando guardo, entonces se registra el vehículo.
* **Prioridad:** Alta. **Estimación:** 3 puntos.

#### HU-08: Gestión de accesos por roles (Seguridad)
* **Como** administrador de sistemas
* **Quiero** que el sistema asigne permisos según el rol del usuario (operario, gestor)
* **Para** garantizar la privacidad de los datos.
* **Criterios de Aceptación:**
  * **Criterio 1:** Dado que un operario inicia sesión, cuando intenta ver reportes gerenciales, entonces el sistema lo bloquea.
* **Prioridad:** Alta. **Estimación:** 5 puntos.

---

### 7.2 Historias de Dominio y No Funcionales (Técnicas)

#### HU-09: Cálculo geoespacial y tiempos estimados
* **Como** sistema (Backend)
* **Quiero** calcular automáticamente la distancia y el tiempo estimado de las rutas
* **Para** asegurar que todos los cálculos operativos del sistema sean precisos.
* **Prioridad:** Alta. **Estimación:** 5 puntos.

#### HU-10: Procesamiento de eficiencia y consumo
* **Como** sistema (Backend)
* **Quiero** procesar los datos ingresados de combustible y tiempo
* **Para** generar y almacenar los indicadores básicos de eficiencia de la flota.
* **Prioridad:** Media. **Estimación:** 3 puntos.

#### HU-11: Rendimiento, Integridad y Experiencia de Usuario
* **Como** desarrollador y usuario final
* **Quiero** que el sistema sea rápido, consistente y fácil de usar en cualquier pantalla
* **Para** garantizar una operación fluida y sin corrupción de datos en la base.
* **Prioridad:** Alta. **Estimación:** 5 puntos.

---

## 8. Planificación y Release Plan (Capacidad: 8 pts / Sprint)

Se conserva la capacidad de planificación original de 8 puntos por iteración para el Equipo de desarrollo (3 integrantes), con la siguiente distribución original de historias clave:

* **Sprint 1 (Semanas 1-2):** Desarrollo visual y registro de la plataforma. (Total Sprint: **8 puntos**).
  * **HU-01 (3 pts):** Registro de rutas logísticas.
  * **HU-02 (5 pts):** Visualización de rutas en mapas (Frontend).
* **Sprint 2 (Semanas 3-4):** Integración de inteligencia artificial y matemática. (Total Sprint: **8 puntos**).
  * **HU-03 (8 pts):** Algoritmo de optimización de rutas (Backend).
* **Sprint 3 (Semanas 5-6):** Seguridad y Catálogo.
  * **HU-08 (5 pts)** y **HU-07 (3 pts)**.
* **Sprint 4 (Semanas 7-8):** Sostenibilidad e indicadores ambientales.
  * **HU-04 (5 pts)** y **HU-10 (3 pts)**.
* **Sprint 5 (Semanas 9-10):** Reportes y cierres ambientales.
  * **HU-06 (8 pts)** (Visualización CO₂).

---

## 9. Sprint Backlog Detallado (Sprints Iniciales)

**Estado al corte de Semana 8 (10/11/2026):** las tareas 1.1–1.5 y 2.1–2.4, la validación de HU-08 y la ejecución del seguimiento R-08/R-09 quedan **Por confirmar**, al no existir evidencia de ejecución en las fuentes consultadas. Las mitigaciones están incorporadas documentalmente; sus verificaciones y resultados deben acreditarse por separado. Este estado se aplica a cada tarea y sus subtareas descritas a continuación. La tabla de seguimiento de la sección 7 indica qué falta acreditar por historia; se conservan las tareas y sus Sprints originales.

### Sprint Backlog - Sprint 1 (Registro y Mapas - 8 pts)
* **Tarea 1.1:** Diseñar y construir el script SQL para la tabla de rutas.
  * **Mitigación R-06:** Revisar campos obligatorios y restricciones para impedir datos incompletos o inconsistentes.
  * **Responsable:** Stuarth Fabricio Miranda Rojas.
  * **Evidencia:** Registrar las validaciones del esquema y los resultados de las pruebas en la tarjeta de HU-01.
  * **Si falla:** Corregir el esquema y repetir la validación antes de aceptar la persistencia de datos.

* **Tarea 1.2:** Crear el formulario de ingreso HTML/CSS para HU-01.

* **Tarea 1.3:** Conectar el frontend para que guarde las rutas (HU-01).
  * **Mitigación R-05:** Comprobar que los nombres, tipos y unidades de los datos enviados desde el frontend coinciden con los esperados por el backend.
  * **Responsable:** Stuarth Fabricio Miranda Rojas realiza la validación técnica, con apoyo de Cristopher Quiros Araya, quien coordina el seguimiento como dueño del riesgo R-05.
  * **Evidencia:** Registrar los datos enviados y la respuesta obtenida en la tarjeta de HU-01.
  * **Si falla:** Corregir el intercambio de datos y repetir la prueba de integración.
  * **Mitigación R-06:** Comprobar que la ruta guardada conserva los datos ingresados y cumple los criterios de CP-RF01-01.
  * **Responsable:** Stuarth Fabricio Miranda Rojas.
  * **Evidencia:** Registrar la comparación entre los datos ingresados y los almacenados.
  * **Si falla:** Cor corregir el guardado y repetir la validación antes de aceptar HU-01.

* **Tarea 1.4:** Integrar el script de Google Maps API en el HTML.
  * **Mitigación R-01:** Validar el acceso a la API y comprobar que el mapa carga sin errores.
  * **Responsable:** Cristopher Quiros Araya.
  * **Evidencia:** Registrar el resultado y una captura o mensaje de error en la tarjeta de HU-02.
  * **Si falla:** Registrar HU-02 como bloqueada y comunicar el impedimento.
  * **Mitigación R-02:** Verificar la modalidad de acceso y el consumo disponible antes de realizar llamadas a la API.
  * **Responsable:** Stuarth Fabricio Miranda Rojas, con apoyo técnico de Cristopher Quiros Araya.
  * **Evidencia:** Registrar la verificación de las condiciones de acceso y del consumo disponible, sin exponer credenciales.
  * **Si falla:** Detener las llamadas que impliquen gasto no autorizado y comunicar el bloqueo.

* **Tarea 1.5:** Programar el Frontend en JS para que dibuje el origen y destino en el mapa (HU-02).
  * **Mitigación R-01:** Comprobar que el mapa representa correctamente el origen y el destino de una ruta registrada.
  * **Responsable:** Cristopher Quiros Araya.
  * **Evidencia:** Registrar el resultado y una captura de la visualización en la tarjeta de HU-02.
  * **Si falla:** Registrar el error y mantener HU-02 sin aceptar hasta corregirlo y repetir la validación.

### Sprint Backlog - Sprint 2 (Lógica Matemática - 8 pts)
* **Tarea 2.1:** Programar en Python la estructura de grafos para las ciudades.
* **Tarea 2.2:** Programar el algoritmo de Dijkstra en FastAPI.

* **Tarea 2.3:** Crear el endpoint (API) para que el frontend envíe las coordenadas a calcular.
  * **Mitigación R-05:** Verificar que el endpoint recibe e interpreta las coordenadas con los nombres, tipos y unidades acordados con el frontend.
  * **Responsable:** Stuarth Fabricio Miranda Rojas realiza la validación técnica, con apoyo de Cristopher Quiros Araya, quien coordina el seguimiento como dueño del riesgo R-05.
  * **Evidencia:** Registrar una solicitud válida, los datos recibidos y la respuesta obtenida en la tarjeta de HU-03.
  * **Si falla:** Corregir el intercambio de datos dentro de la tarea existente y repetir la prueba de integración.

* **Tarea 2.4:** Hacer pruebas unitarias sobre los resultados matemáticos devueltos.
  * **Mitigación R-03:** Comparar los resultados de Dijkstra con grafos pequeños cuya ruta mínima se haya calculado manualmente.
  * **Responsable:** Stuarth Fabricio Miranda Rojas.
  * **Evidencia:** Registrar los datos de entrada, el resultado esperado y el obtenido en la tarjeta de HU-03.
  * **Si falla:** Corregir el algoritmo o el grafo y repetir la prueba fallida y la regresión correspondiente.
  * **Mitigación R-10:** Comprobar que los resultados de estas pruebas quedan registrados como evidencia del criterio de pruebas unitarias del DoD.
  * **Responsable:** Miguel Cruz Vargas.
  * **Evidencia:** Registrar el procedimiento ejecutado y los resultados de las pruebas en la tarjeta de HU-03.
  * **Si falla:** Mantener el criterio como no acreditado y no marcar HU-03 como Hecho hasta completar los cinco criterios del DoD

### Sprint Backlog - Sprint 3: Mitigación vinculada a HU-08

* **Validación de permisos de HU-08:**
  * **Mitigación R-07:** Comprobar que un usuario con rol operario no puede acceder a reportes gerenciales, incluso mediante acceso directo.
  * **Responsable:** Stuarth Fabricio Miranda Rojas implementa y Miguel Cruz Vargas revisa.
  * **Evidencia:** Registrar el rol utilizado, la operación intentada y el resultado obtenido en la tarjeta de HU-08.
  * **Si falla:** Corregir los permisos y repetir la validación antes de marcar HU-08 como Hecho.

### Actividades de seguimiento y planificación

* **Mitigación R-08:** Revisar en cada Daily Scrum la disponibilidad de los integrantes, los bloqueos y los límites WIP.
  * **Responsable:** Cristopher Quiros Araya.
  * **Evidencia:** Registrar los impedimentos y acuerdos de apoyo en las tarjetas afectadas.
  * **Si se detecta indisponibilidad:** Coordinar apoyo entre los integrantes, conservando la revisión por otra persona y comunicando cualquier trabajo que no pueda completarse.

* **Respuesta R-09:** Contrastar en cada Sprint Planning y Sprint Review los compromisos con el Release Plan de 40 puntos.
  * **Responsable:** Stuarth Fabricio Miranda Rojas.
  * **Evidencia:** Registrar que HU-05, HU-09 y HU-11 siguen sin Sprint asignado mientras no exista una decisión de planificación.
  * **Si se propone trabajo adicional:** Registrar la discrepancia y consultar su planificación antes de comprometer la entrega.

---

## 10. Definition of Done (DoD) y Criterios de Calidad

Una historia de usuario solo se considerará **"Terminada" (Done)** cuando cumpla con:

1. **Pruebas Unitarias aprobadas:** El código lógico pasa sus pruebas individuales.
2. **Pruebas de Humo (Smoke Testing):** La vista HTML carga correctamente sin fallos.
3. **Pruebas de Integración exitosas:** El Frontend interactúa correctamente con el Backend y la BD.
4. **Pruebas de Regresión pasadas:** Se garantiza que la nueva función no rompe funciones previas.
5. Los Criterios de Aceptación especificados en la Historia de Usuario se cumplen.

---

## 11. Definición del Scrum Team a 10 Semanas

El **Equipo de desarrollo (3 integrantes)** está conformado por **Stuarth Fabricio Miranda Rojas, Cristopher Quiros Araya y Miguel Cruz Vargas**. Las siguientes asignaciones se establecen como planificación en la versión 0.10, por autorización del solicitante para resolver las definiciones pendientes. No describen experiencia profesional acreditada, disponibilidad comprobada, acuerdos de reuniones anteriores ni trabajo ya ejecutado.

| Integrante | Roles previstos que asume | Responsabilidades dentro del alcance actual |
| --- | --- | --- |
| Stuarth Fabricio Miranda Rojas | PO y Backend | Mantener las prioridades originales, coordinar las consultas académicas con el profesor y desarrollar la lógica de servidor y persistencia de sus historias asignadas. |
| Cristopher Quiros Araya | Scrum Master y Frontend | Facilitar las ceremonias existentes, vigilar los límites WIP, mantener el registro de decisiones y desarrollar las interfaces de sus historias asignadas. |
| Miguel Cruz Vargas | QA y apoyo de Backend | Coordinar la verificación del DoD, registrar resultados reales de pruebas y desarrollar el procesamiento de recursos asignado. |

Los roles se acumulan dentro del equipo de tres; no implican incorporar personas ni aumentar la capacidad. Cada responsable implementará su historia, actualizará su tarjeta y aportará evidencia. La revisión corresponderá a otro integrante para evitar que una persona sea el único validador de su propio trabajo.

| Historia original | Responsable de implementación | Responsable de revisión del DoD | Sprint original |
| --- | --- | --- | --- |
| HU-01 (3 puntos) | Stuarth Fabricio Miranda Rojas | Miguel Cruz Vargas | 1 |
| HU-02 (5 puntos) | Cristopher Quiros Araya | Miguel Cruz Vargas | 1 |
| HU-03 (8 puntos) | Stuarth Fabricio Miranda Rojas | Miguel Cruz Vargas | 2 |
| HU-04 (5 puntos) | Miguel Cruz Vargas | Stuarth Fabricio Miranda Rojas | 4 |
| HU-05 (5 puntos) | Cristopher Quiros Araya | Miguel Cruz Vargas | Sin Sprint asignado en el Release Plan original. |
| HU-06 (8 puntos) | Cristopher Quiros Araya | Miguel Cruz Vargas | 5 |
| HU-07 (3 puntos) | Cristopher Quiros Araya | Miguel Cruz Vargas | 3 |
| HU-08 (5 puntos) | Stuarth Fabricio Miranda Rojas | Miguel Cruz Vargas | 3 |
| HU-09 (5 puntos) | Stuarth Fabricio Miranda Rojas | Miguel Cruz Vargas | Sin Sprint asignado en el Release Plan original. |
| HU-10 (3 puntos) | Miguel Cruz Vargas | Stuarth Fabricio Miranda Rojas | 4 |
| HU-11 (5 puntos) | Miguel Cruz Vargas | Cristopher Quiros Araya | Sin Sprint asignado en el Release Plan original. |

En el Sprint 1, Stuarth asume las tareas originales 1.1 a 1.3 de HU-01, Cristopher las tareas 1.4 y 1.5 de HU-02 y Miguel su revisión según el DoD. En el Sprint 2, Stuarth asume las tareas originales 2.1 a 2.4 y Miguel revisa sus resultados. Los demás integrantes podrán colaborar dentro de las mismas historias sin crear tareas ni puntos adicionales.

Se mantienen las 10 semanas, los 5 Sprints y los 8 puntos por Sprint. El backlog conserva sus 11 historias y 55 puntos; el Release Plan original programa 8 historias y 40 puntos. HU-05, HU-09 y HU-11 permanecen en el backlog sin compromiso de entrega dentro de esos 5 Sprints. Asignarles responsables no las incorpora al cronograma ni elimina sus requisitos.

---

## 12. Plan de Comunicaciones del Proyecto

**Proyecto:** Sistema inteligente para gestión y optimización de operaciones logísticas  
**Equipo:** Stuarth Fabricio Miranda Rojas, Cristopher Quiros Araya y Miguel Cruz Vargas  
**Base:** Alcance de la versión 0.8, plan integrado en la 0.9 y definiciones organizativas de la 0.10.  
**Referencia:** [Optimización logística · Centro del Sprint 1](https://app.notion.com/p/40f28b05e206818bae44c111edf7ee18)

### 12.1. Propósito y fuentes

El plan establece cómo comunicar avances, bloqueos, validaciones y decisiones mediante el tablero existente y las ceremonias ya previstas: Sprint Planning, Daily Scrum, Sprint Review y Sprint Retrospective.

La página de Notion fue consultada el 04/11/2026, fecha local de Guatemala. En esa consulta documentaba HU-01 y HU-02, las cuatro columnas, los límites WIP como propuestas, las asignaciones individuales pendientes y ningún avance confirmado. Esa descripción corresponde al momento de la consulta. Las asignaciones y reglas que siguen son definiciones de esta actualización del Markdown; no se ha modificado Notion ni se afirma que ya las refleje.

### 12.2. Participantes y responsabilidades de comunicación

Cada responsable de historia actualizará el estado, los avances y los impedimentos en los comentarios de su tarjeta existente. El revisor de la sección 11 registrará el resultado de la validación. Cristopher facilitará las ceremonias, comprobará la coherencia del tablero y registrará los acuerdos generales en comentarios de la página principal existente de Notion.

Stuarth será el enlace con el profesor **Deiver Cubero Molina**. Al cierre de cada Sprint preparará un resumen de historias terminadas con evidencia, trabajo restante, bloqueos y consultas académicas. El canal documental será el Markdown del proyecto y el resumen quedará registrado en los comentarios de la página principal de Notion. Para la comunicación directa se utilizará el espacio de clase del curso, sin crear cuentas, correos o reuniones adicionales ni suponer que el profesor tiene acceso a Notion. Las respuestas se registrarán solo cuando se reciban; no se comprometen plazos de respuesta del profesor.

Los demás interesados del mapa se mantienen como roles del contexto conceptual. No se atribuyen nombres, contactos ni participación real a empresas, conductores, clientes o entidades reguladoras. Sus necesidades se revisarán con los requisitos originales en la Sprint Review; no se programan envíos externos ni se inventan representantes. Las dudas sobre su interpretación se canalizarán por Stuarth al profesor dentro del seguimiento académico existente.

### 12.3. Uso del tablero y límites WIP

El tablero del Sprint 1 da seguimiento a **HU-01 (3 puntos)** y **HU-02 (5 puntos)**, por un total de **8 puntos**, junto con las tareas originales 1.1 a 1.5.

| Columna existente | Significado y regla de movimiento |
| --- | --- |
| Pendiente | Trabajo no iniciado. El responsable definido en la sección 11 lo mueve a En proceso cuando comience realmente. |
| En proceso | Implementación activa. El responsable lo mueve a En revisión cuando esté listo para validar y haya incorporado la evidencia disponible. |
| En revisión | El revisor comprueba el DoD. Si falla, registra el motivo y devuelve la historia a En proceso. |
| Hecho | El revisor mueve la historia únicamente después de comprobar los cinco criterios del DoD y dejar evidencia. |

Para este plan se adoptan **máximo 2 tarjetas en En proceso** y **máximo 2 en En revisión**; Pendiente y Hecho quedan sin límite. Se trata de una regla de coordinación manual, no de una restricción automática de Notion. Cristopher vigilará los límites. Si se alcanza uno, el equipo ayudará a terminar o revisar el trabajo existente antes de iniciar otra tarjeta. Si un retorno desde revisión pudiera superar el límite de En proceso, se pausará otra implementación, registrando la pausa en su tarjeta, antes de reanudar la historia devuelta; no se ocultará el trabajo iniciado moviéndolo a Pendiente.

Las actualizaciones de tarjetas corresponderán al trabajo real y se harán el mismo día de trabajo en que cambie su estado. Estas definiciones no autorizan añadir historias al Sprint ni aumentar la velocidad.

### 12.4. Matriz de comunicaciones internas

Se fija el siguiente horario de planificación en **hora de Guatemala**, relativo a las semanas originales de cada Sprint. Se aplica al trabajo futuro, sin reconstruir ni dar por realizadas ceremonias pasadas. La modalidad será escrita mediante comentarios en Notion, sin incorporar otra herramienta. Los bloques horarios reservan una ventana de intercambio, no acreditan asistencia ni disponibilidad previamente comprobada.

| Comunicación | Momento y duración | Responsable y participantes | Contenido y registro |
| --- | --- | --- | --- |
| Sprint Planning | Primer lunes del Sprint, 19:00–19:45. | Facilita Cristopher; participan los tres. | Revisar historias del Release Plan y responsabilidades de la sección 11; resumen en comentarios de la página principal. |
| Daily Scrum | Lunes a viernes, 18:45–19:00. | Facilita Cristopher; cada integrante comunica su estado. | Avance real, siguiente paso dentro de la historia y bloqueos; comentarios de las tarjetas. |
| Cambio de estado | El mismo día de trabajo del cambio. | Responsable de historia o revisor, según la columna. | Justificación y evidencia en la tarjeta existente. |
| Bloqueo | Al detectarlo, con respuesta interna a más tardar en el siguiente Daily Scrum. | Lo comunica quien lo detecte; coordina Cristopher. | Registro en la tarjeta y seguimiento mientras persista. |
| Sprint Review | Segundo viernes del Sprint, 19:00–19:30. | Participan los tres; Miguel presenta el resultado de validación. | Contrastar resultados con requisitos y DoD; resumen en comentarios de la página principal. La participación externa no es necesaria para la revisión interna y no se da por confirmada. |
| Sprint Retrospective | Segundo viernes del Sprint, 19:30–19:50. | Facilita Cristopher; participan los tres. | Revisar dificultades de coordinación y registrar acuerdos en comentarios de la página principal. |

Si un integrante no puede intervenir en una ventana, dejará su actualización escrita antes de ella; el facilitador registrará la ausencia sin atribuirle aprobación. No se añaden reuniones para compensarla. El resumen al profesor se preparará después de la Sprint Review para su comunicación en el siguiente espacio de clase disponible.

### 12.5. Avances, bloqueos y escalamiento

El comentario de avance tendrá este formato: **fecha; HU; tareas originales atendidas; resultado comprobable; evidencia; siguiente paso; bloqueo, si existe**. Se informará únicamente lo realizado; una tarea iniciada no equivale a una historia terminada.

El comentario de bloqueo tendrá el formato: **fecha; HU; impedimento; efecto sobre el trabajo; ayuda requerida; responsable de atención; siguiente revisión; resolución cuando ocurra**. Quien lo detecte lo registrará de inmediato y mencionará a Cristopher. El responsable de implementación atenderá los bloqueos técnicos de su historia con apoyo del revisor; Cristopher atenderá los de coordinación y Stuarth las dudas sobre alcance o requisitos.

La primera respuesta interna deberá quedar registrada a más tardar en el siguiente Daily Scrum. Si el bloqueo continúa durante dos Daily Scrum consecutivos, Cristopher lo escalará a Stuarth en el comentario de la tarjeta. Si requiere orientación académica, Stuarth lo incluirá en el resumen al profesor y lo planteará en el siguiente espacio de clase. Este plazo es de comunicación interna, no una promesa de resolución o de respuesta externa.

Los bloqueos se describirán en comentarios, sin añadir columnas. Su existencia no justifica marcar Hecho, cambiar puntos ni mover fechas. La resolución se registrará con su fecha y evidencia antes de comunicar que el impedimento terminó.

### 12.6. Validación y evidencia de cierre

Se mantienen los cinco criterios del DoD original: pruebas unitarias aprobadas, prueba de humo con HTML sin fallos, integración Frontend/Backend/base de datos exitosa, regresión superada y criterios de aceptación satisfechos.

El responsable de implementación reunirá la evidencia en los comentarios de la tarjeta con el formato: **fecha; criterio del DoD; procedimiento ejecutado; resultado observado; enlace o archivo de evidencia**. Se podrán adjuntar salidas de pruebas y capturas obtenidas durante la validación de las funcionalidades existentes. La ausencia de evidencia se registrará como criterio no acreditado; no se presumirá una prueba aprobada.

El revisor asignado en la sección 11 comprobará cada criterio y registrará su resultado antes de mover la historia a Hecho. Miguel coordinará la consistencia de estas revisiones; en sus propias historias revisará la persona indicada en la tabla. Si falla algún criterio, el revisor devolverá la historia a En proceso con el motivo y el responsable corregirá dentro de su alcance original.

### 12.7. Registro de decisiones

Cristopher mantendrá las decisiones generales en los **comentarios de la página principal existente de Notion**; las decisiones específicas se anotarán en los **comentarios de la tarjeta de la historia** y se referenciarán desde el resumen general cuando afecten al equipo. No se creará otra página, base de datos o tablero.

Cada registro contendrá: **fecha; asunto; HU, si corresponde; alternativas consideradas; decisión; personas que la aprobaron; responsable de aplicación; motivo y referencia a la evidencia disponible**. Las decisiones operativas dentro del alcance se tomarán con la conformidad escrita de al menos dos integrantes, incluida la persona responsable de aplicarlas. Si no se alcanza esa conformidad, se conservará la regla vigente y Stuarth canalizará la consulta en el seguimiento académico, sin detener trabajo no afectado. Las ausencias o el silencio no se contabilizarán como aprobación.

Las asignaciones, los horarios y los límites WIP de esta versión se registran como definiciones de planificación autorizadas por el solicitante, no como acuerdos ya votados por los integrantes. Las decisiones posteriores no modificarán automáticamente el alcance, los puntos ni el cronograma. HU-05, HU-09 y HU-11 mantienen la situación indicada en la sección 11 y no se introducirán en los Sprints programados mediante un acuerdo operativo.

### 12.8. Conservación del alcance y estado de aplicación

Se conservan los objetivos, requerimientos, funcionalidades, 11 historias, puntos, tareas técnicas originales, DoD y cronograma de 10 semanas. Las definiciones de esta actualización distribuyen el trabajo y concretan la comunicación sin ampliar el producto ni prometer la entrega de historias no programadas.

El historial 0.1 a 0.9 se conserva intacto y solo se añade la versión 0.10. Esta edición se limita a los Markdown locales: no modifica el tablero de Notion, no envía mensajes ni crea eventos. Por ello, las nuevas asignaciones y reglas quedan documentadas aquí sin afirmar que ya estén aplicadas en el tablero o que se hayan realizado reuniones, pruebas o entregas.

---

## 13. Gestión de Riesgos — Semana 8

### 13.1. Introducción

La gestión de riesgos permite anticipar condiciones que podrían impedir el cumplimiento de los requisitos del **Sistema inteligente para gestión y optimización de operaciones logísticas** dentro de las 10 semanas previstas. En un equipo de tres integrantes, la disponibilidad de una persona afecta tanto la implementación como la revisión. La integración de Google Maps, los cálculos de Dijkstra y Haversine, la comunicación Frontend/Backend y la persistencia de datos introducen dependencias que deben controlarse sin ampliar el producto. El presupuesto limitado exige vigilar el acceso a servicios externos y evitar comprometer gastos no autorizados.

Esta sección incorpora los dos artefactos de la Semana 8, Fase 3: Trabajo Colaborativo: **Matriz de Riesgos** y **Plan de Mitigación**. Toma como base la versión 0.10, conserva las secciones anteriores y no acredita incidentes, pruebas, reuniones, compras ni entregas realizadas. Las puntuaciones y los riesgos residuales son evaluaciones iniciales de planificación, no mediciones empíricas ni resultados de controles ya ejecutados.

### 13.2. Identificación y registro de riesgos — Artefacto 1

#### 13.2.1. Criterios de evaluación

Se utiliza **prioridad = probabilidad (P) × impacto (I)**. La evaluación expresa exposición a incumplir requisitos, calidad o plazo; no modifica los puntos de historia.

| Valor | Probabilidad | Impacto sobre este proyecto |
| :---: | --- | --- |
| 1 | Baja: condición posible, pero localizada y con pocos factores identificados que la favorezcan. | Bajo: corrección localizada en la historia, sin afectar otras historias ni el cierre previsto. |
| 2 | Media: condición plausible por dependencias o integración aún sin evidencia de validación. | Medio: retrabajo que afecta una historia o su revisión dentro del Sprint. |
| 3 | Alta: condición favorecida por una limitación documentada o varias dependencias concurrentes. | Alto: puede impedir un requisito esencial, el DoD, la seguridad de los datos o el compromiso de entrega dentro de las 10 semanas. |

**Prioridad baja: 1–2; media: 3–4; alta: 6–9.** Se atienden primero las altas y después las medias y bajas; a igual puntuación, se prioriza el mayor impacto y la dependencia que bloquee otra historia. Los valores posibles del producto son 1, 2, 3, 4, 6 y 9. La categoría principal será técnico, equipo, alcance, tercero o negocio; el tipo será amenaza u oportunidad. En esta evaluación se registran diez amenazas relevantes, sin añadir oportunidades sin sustento.

#### 13.2.2. Matriz de riesgos

Los nombres abreviados de los dueños corresponden a los integrantes identificados en la sección 11. El dueño coordina la respuesta y su seguimiento; conserva las responsabilidades de implementación y revisión ya asignadas.

| ID | Descripción: Si ocurre X, entonces Y | Categoría | Tipo | P | I | Prioridad | Dueño del riesgo | Fundamento de la evaluación |
| --- | --- | --- | --- | :---: | :---: | --- | --- | --- |
| R-01 | Si Google Maps API no está disponible o rechaza el acceso durante la integración, entonces HU-02 no podrá mostrar origen y destino y se bloqueará su aceptación. | tercero | amenaza | 2 | 3 | 6 — Alta | Cristopher Quiros Araya | HU-02 depende del acceso externo; no hay evidencia de disponibilidad validada. |
| R-02 | Si el uso de Google Maps exige un gasto superior a los recursos autorizados, entonces la restricción presupuestaria impedirá sostener esa integración. | negocio | amenaza | 2 | 3 | 6 — Alta | Stuarth Fabricio Miranda Rojas | La restricción presupuestaria exige herramientas gratuitas y capas libres; no se documenta contratación ni saldo disponible. |
| R-03 | Si el grafo o la implementación de Dijkstra representan incorrectamente las conexiones y sus pesos, entonces HU-03 devolverá una ruta que no cumple el criterio de alternativa más corta. | técnico | amenaza | 2 | 3 | 6 — Alta | Stuarth Fabricio Miranda Rojas | HU-03 requiere lógica matemática propia y depende de la estructura de grafos. |
| R-04 | Si Haversine recibe coordenadas o unidades interpretadas incorrectamente, entonces las distancias de HU-09 y los cálculos que las utilicen serán inconsistentes. | técnico | amenaza | 2 | 3 | 6 — Alta | Stuarth Fabricio Miranda Rojas | El dominio exige cálculos geográficos y unidades estandarizadas; HU-09 permanece sin Sprint asignado. |
| R-05 | Si Frontend y Backend intercambian coordenadas o datos de rutas con formatos incompatibles, entonces fallará el guardado o el cálculo solicitado desde la interfaz. | técnico | amenaza | 2 | 2 | 4 — Media | Cristopher Quiros Araya | Las tareas 1.3 y 2.3 conectan componentes desarrollados por integrantes distintos. |
| R-06 | Si el esquema SQL o el guardado permiten datos incompletos o relaciones inconsistentes, entonces las rutas registradas y los indicadores derivados perderán integridad. | técnico | amenaza | 2 | 3 | 6 — Alta | Stuarth Fabricio Miranda Rojas | La persistencia de HU-01 y el requisito no funcional de integridad dependen de la tabla y la conexión de guardado. |
| R-07 | Si la validación de permisos permite a un operario acceder a información restringida, entonces HU-08 incumplirá el control por roles y expondrá datos. | técnico | amenaza | 2 | 3 | 6 — Alta | Stuarth Fabricio Miranda Rojas | El criterio de HU-08 exige bloquear accesos no autorizados; no hay evidencia de validación. |
| R-08 | Si un integrante no está disponible para implementar o revisar su historia, entonces se acumulará trabajo en proceso o revisión y se pondrá en riesgo el cierre del Sprint. | equipo | amenaza | 2 | 2 | 4 — Media | Cristopher Quiros Araya | Tres integrantes concentran roles técnicos y de coordinación; cada historia requiere revisión de otra persona. |
| R-09 | Si se interpreta que los cinco Sprints comprometen las once historias, entonces se prometerán 55 puntos con una planificación que solo programa 40 y se comprometerá el plazo de 10 semanas. | alcance | amenaza | 3 | 3 | 9 — Alta | Stuarth Fabricio Miranda Rojas | La diferencia documentada es de 15 puntos: HU-05, HU-09 y HU-11 no tienen Sprint asignado. |
| R-10 | Si se acumulan validaciones o se declara una historia terminada sin evidencia de los cinco criterios del DoD, entonces se comunicarán avances no acreditados y defectos podrían llegar al cierre. | equipo | amenaza | 2 | 3 | 6 — Alta | Miguel Cruz Vargas | El DoD exige cinco verificaciones y QA participa en la revisión de varias historias. |

#### 13.2.3. Mapa de calor inicial

Cada ID aparece una sola vez. Las filas representan probabilidad y las columnas impacto. El color se acompaña de texto para que el mapa sea legible sin depender del color.

| Probabilidad ↓ / Impacto → | 1 — Bajo | 2 — Medio | 3 — Alto |
| --- | --- | --- | --- |
| **3 — Alta** | 🟨 3 — Media: sin riesgos | 🟥 6 — Alta: sin riesgos | 🟥 9 — Alta: **R-09** |
| **2 — Media** | 🟩 2 — Baja: sin riesgos | 🟨 4 — Media: **R-05, R-08** | 🟥 6 — Alta: **R-01, R-02, R-03, R-04, R-06, R-07, R-10** |
| **1 — Baja** | 🟩 1 — Baja: sin riesgos | 🟩 2 — Baja: sin riesgos | 🟨 3 — Media: sin riesgos |

El mapa ubica los diez riesgos: ocho de prioridad alta y dos de prioridad media. Su concentración inicial refleja dependencias esenciales aún sin evidencia de control; no significa que los eventos ya hayan ocurrido.

### 13.3. Plan de mitigación — Artefacto 2

#### 13.3.1. Acciones, disparadores y contingencias

Las acciones siguientes concretan controles dentro de historias, tareas y criterios de calidad ya existentes. **Las acciones de mitigación se incorporan en la sección 9 como subtareas de los Sprints 1 y 2, una actividad de validación de HU-08 en el Sprint 3 y actividades de seguimiento para R-08 y R-09**, sin añadir historias ni modificar sus puntos o programación. R-04 permanece vinculado a HU-09 y pendiente de incorporación al Sprint Backlog, porque esa historia aún no tiene Sprint asignado. Las referencias a Sprints anteriores son vínculos con la planificación original, no afirmaciones de ejecución ni órdenes de rehacer trabajo ya validado.

| ID | Estrategia | Acción concreta e ítem correspondiente del backlog existente | Disparador verificable | Contingencia o respaldo |
| --- | --- | --- | --- | --- |
| R-01 | Mitigar; aceptar la indisponibilidad externa que no controla el equipo. | En **HU-02, Sprint 1, tareas 1.4 y 1.5**, comprobar que la integración carga el mapa y representa origen y destino; registrar errores de acceso y su contexto como evidencia de la validación. | El mapa no carga o la solicitud es rechazada durante la ejecución de esas tareas o su revisión. | Registrar HU-02 como bloqueada y continuar únicamente trabajo original que no dependa del servicio. Reintentar tras resolver el acceso; no sustituir proveedor ni declarar aceptada la visualización con una simulación. |
| R-02 | Evitar gasto no autorizado; mitigar exposición presupuestaria. | Como condición de **HU-02, tarea 1.4**, Stuarth revisará con Cristopher la modalidad de acceso y el consumo disponible en la cuenta que se utilice antes de realizar llamadas de integración; mantener las validaciones limitadas a las necesarias para HU-02. | La cuenta exige un pago no autorizado, no permite verificar el consumo o informa que el uso previsto excede lo disponible. | Detener las llamadas que impliquen gasto y comunicar el bloqueo por la vía de la sección 12. Mantener la funcionalidad pendiente hasta resolver la restricción; no contratar automáticamente otro plan o servicio. |
| R-03 | Mitigar. | En **HU-03, Sprint 2, tareas 2.1, 2.2 y 2.4**, contrastar los resultados con grafos pequeños cuyo recorrido mínimo pueda calcularse manualmente; revisar pesos y conexiones antes de aceptar la lógica. | Una prueba de la tarea 2.4 devuelve una ruta distinta de la mínima esperada o no resuelve un recorrido disponible. | Corregir el grafo o Dijkstra dentro de HU-03 y repetir la prueba fallida y la regresión correspondiente. Conservar la historia sin terminar mientras persista la discrepancia. |
| R-04 | Mitigar y aceptar exposición de programación no resuelta. | En **HU-09**, contrastar coordenadas, conversión de unidades y distancia contra ejemplos calculables de forma independiente; aplicar las unidades del requisito de dominio 3. **No existe tarea desglosada ni Sprint asignado para HU-09**; la acción queda vinculada a esa historia, sin incorporarla a un Sprint. | La revisión detecta mezcla de grados y radianes, unidades distintas de kilómetros o una distancia incompatible con los datos de entrada. | No utilizar el resultado discrepante como evidencia de aceptación; registrar la dependencia afectada y corregir dentro de HU-09 cuando se autorice su ejecución. No estimar tiempo únicamente a partir de distancia sin una base definida en los requisitos. |
| R-05 | Mitigar. | En **HU-01, tarea 1.3**, y **HU-03, tarea 2.3**, contrastar los nombres, tipos y unidades de los datos enviados y recibidos; realizar la verificación de integración ya exigida por el DoD. | Una solicitud válida desde la interfaz es rechazada, guarda datos distintos o devuelve coordenadas incompatibles. | Volver la historia afectada a En proceso, corregir el intercambio en las tareas existentes y repetir la integración; no añadir endpoints ajenos a las historias. |
| R-06 | Mitigar. | En **HU-01, tareas 1.1 y 1.3**, revisar campos y relaciones del esquema y contrastar el dato guardado con la entrada válida del **CP-RF01-01**; comprobar el requisito no funcional 5 al validar la persistencia. | La ruta guardada pierde campos, admite origen/destino inválidos o queda asociada a datos inconsistentes. | Detener la validación de la persistencia afectada y corregir esquema o guardado en las mismas tareas. Repetir la verificación con datos de prueba; no borrar registros reales ni afirmar recuperación mediante copias cuya existencia no está acreditada. |
| R-07 | Mitigar. | En **HU-08, Sprint 3**, verificar su criterio de aceptación con un operario que intenta acceder a reportes gerenciales y contrastar el resultado con el rol autorizado. **La validación se incorpora en la sección 9, en el apartado del Sprint 3**, como actividad vinculada a HU-08 y al DoD. Stuarth implementa y Miguel revisa. | Un usuario con rol operario logra acceder a una operación restringida durante la validación. | Impedir que la historia se marque Hecho o se entregue como segura; corregir los permisos dentro de HU-08 y repetir la validación de acceso e integración. |
| R-08 | Mitigar. | En las historias asignadas en la **sección 11**, el responsable mantendrá el avance y las evidencias en sus comentarios; Cristopher vigilará el WIP y coordinará apoyo sobre las mismas tareas. Para Sprint 1 se vincula a **1.1–1.5** y para Sprint 2 a **2.1–2.4**; en Sprints posteriores, a sus HU originales sin inventar desglose. | Un responsable comunica indisponibilidad o falta su actualización en una ventana diaria sin registro previo. | Redistribuir temporalmente el trabajo original entre los otros dos integrantes mediante decisión registrada, preservando revisión por otra persona. Si no hay capacidad, comunicar el trabajo no terminado, sin elevar velocidad, puntos ni extender fechas automáticamente. |
| R-09 | Evitar promesas fuera del Release Plan; aceptar el riesgo residual de cobertura. | Stuarth contrastará los compromisos con la **sección 8 y las HU originales** en Planning y Review; mantener explícito que HU-05, HU-09 y HU-11 no tienen Sprint asignado. Las tareas de **sección 9** conservan su programación; este control de gestión no agrega una tarea técnica. | Se propone añadir cualquiera de esas tres historias a un Sprint ya completo o se comunica que se entregarán 55 puntos en los cinco Sprints. | Mantener la programación de 40 puntos y registrar la discrepancia para consulta académica. No retirar las tres HU del alcance, no prometer su terminación ni aprobar ampliación de fechas o capacidad como contingencia automática. |
| R-10 | Mitigar. | En **tarea 2.4 de HU-03** y en la revisión de **todas las historias conforme al DoD de sección 10**, el revisor comprobará cada criterio con la evidencia de sección 12.6 antes del movimiento a Hecho; vigilar el límite de 2 tarjetas en revisión. No se crean tareas de pruebas nuevas. | Una historia se propone como Hecho sin evidencia de algún criterio, falla una validación o se acumulan más de dos tarjetas en revisión. | Mantener o devolver la historia a En proceso según el fallo, priorizar su corrección y revisión dentro del trabajo original y comunicar lo no validado en la Review. No omitir criterios para cumplir una fecha. |

#### 13.3.2. Fecha de revisión y evaluación residual

**Fecha de evaluación documental inicial: 04/11/2026. Próxima revisión programada de los diez riesgos: 11/11/2026**, utilizando el seguimiento ya previsto; esta fecha se aplica al registro de riesgos y no cambia las semanas ni las fechas de entrega del proyecto. Se revisará antes si aparece un disparador. No se afirma que ninguna de estas revisiones se haya realizado. Después se actualizará el registro en las Planning y Review existentes mientras el proyecto continúe activo, sin crear reuniones adicionales.

Los valores residuales siguientes son **estimaciones objetivo condicionadas a ejecutar y acreditar las acciones**. Se reduce la probabilidad cuando corresponde, sin asumir que desaparece la consecuencia. Mientras no haya evidencia, se conserva como exposición vigente la puntuación inicial de la matriz.

| ID | Próxima revisión programada | P residual | I residual | Prioridad residual objetivo | Condición y exposición que permanece |
| --- | --- | :---: | :---: | --- | --- |
| R-01 | 11/11/2026 | 1 | 3 | 3 — Media | Solo tras validar el acceso y mapa; puede persistir una interrupción del proveedor. |
| R-02 | 11/11/2026 | 1 | 3 | 3 — Media | Solo con modalidad y consumo verificados; no se asegura gratuidad futura ni disponibilidad presupuestaria. |
| R-03 | 11/11/2026 | 1 | 3 | 3 — Media | Solo tras evidencia de la tarea 2.4; permanecen casos no cubiertos por la validación. |
| R-04 | 11/11/2026 | 2 | 3 | 6 — Alta | Se mantiene inicialmente: HU-09 sigue sin Sprint; no se presume implementado el control. |
| R-05 | 11/11/2026 | 1 | 2 | 2 — Baja | Solo tras integración comprobada; cambios posteriores podrían reintroducir incompatibilidades. |
| R-06 | 11/11/2026 | 1 | 3 | 3 — Media | Solo tras evidencia de persistencia íntegra; permanecen errores posibles fuera de los casos revisados. |
| R-07 | 11/11/2026 | 1 | 3 | 3 — Media | Solo tras comprobar roles; una modificación posterior puede introducir un acceso indebido. |
| R-08 | 11/11/2026 | 1 | 2 | 2 — Baja | Solo con avance accesible y apoyo coordinado; una ausencia prolongada sigue afectando la capacidad. |
| R-09 | 11/11/2026 | 2 | 3 | 6 — Alta | La claridad del compromiso reduce la confusión, pero no resuelve los 15 puntos sin programación. |
| R-10 | 11/11/2026 | 1 | 3 | 3 — Media | Solo con revisión y evidencia del DoD; la carga de validación y defectos no detectados permanecen posibles. |

En cada revisión, el dueño registrará fecha efectiva, evidencia, estado (identificado, activo, en tratamiento o cerrado), P e I reevaluadas y justificación de cualquier cambio. Un riesgo solo se cerrará cuando deje de ser aplicable o exista evidencia suficiente de resolución; una fecha programada no demuestra cierre. Miguel comprobará la evidencia de calidad, Cristopher consolidará el seguimiento y Stuarth canalizará las consultas de alcance conforme a sus roles existentes.

### 13.4. Adquisiciones críticas y dependencias de terceros

Esta identificación responde al requisito académico de adquisiciones. **No acredita contratos firmados, proveedores adicionales elegidos ni compras realizadas.** Se distinguen modalidades previstas de hechos contractuales. No se fijan tarifas, cuotas gratuitas, garantías de servicio ni condiciones comerciales actuales que el expediente no documenta; su comprobación será condición del acceso, no un supuesto de este plan.

| Dependencia crítica y vínculo | Proveedor | Tipo de contrato o modalidad prevista | Control y responsable | Plan de salida o respaldo |
| --- | --- | --- | --- | --- |
| Google Maps API para **HU-02, tareas 1.4 y 1.5**; riesgos R-01 y R-02. | Google, proveedor ya identificado en el proyecto. | Adhesión a condiciones del servicio y modalidad de acceso por uso que resulte aplicable; aceptar únicamente uso compatible con la restricción presupuestaria y previamente autorizado. No se acredita cuenta, aceptación contractual, saldo ni contratación. | Stuarth verificará condiciones y exposición a gasto; Cristopher verificará el acceso técnico al integrar. Si requiere gasto no autorizado, se activa R-02. | Suspender llamadas y deshabilitar las credenciales del proyecto en la cuenta cuando proceda, revisando cualquier compromiso que realmente exista. Conservar el trabajo propio y los datos cuya conservación esté permitida, sin presumir derechos sobre contenido del proveedor. No migrar a otro servicio automáticamente; HU-02 continuará bloqueada si no puede cumplirse con la dependencia original. |
| Notion para seguimiento del Sprint y registro de decisiones de **sección 12**; vínculo con R-08 y R-10. | Notion, plataforma del tablero existente. | Adhesión al servicio de colaboración ya utilizado. El expediente no identifica el plan comercial, titular contractual ni pagos; no se autoriza una nueva suscripción. | Cristopher comprobará acceso a la página y tarjetas durante el seguimiento habitual. Si no puede actualizarse el registro, dejará constancia de la interrupción. | Durante una indisponibilidad, registrar temporalmente en este mismo Markdown el estado y los acuerdos verificables para preservar el expediente, sin crear archivos ni tableros. Reconciliar el registro al recuperar acceso. Si debe abandonarse el servicio, conservar únicamente información propia y accesible conforme a permisos; no suponer una exportación o migración ya efectuada. |

Python, FastAPI, SQL, HTML/CSS y JavaScript están citados como tecnologías del trabajo original; el expediente no define proveedor de hosting, motor de base de datos contratado ni otra compra crítica. No se eligen proveedores ni contratos para completar la tabla. Las incompatibilidades de integración se atienden dentro de R-05 y las tareas existentes, sin incorporar herramientas o servicios nuevos.

### 13.5. Integración colaborativa y conservación del expediente

La matriz y el plan quedan en este mismo Markdown. Los dueños comunicarán disparadores y cambios por el mecanismo de avances y bloqueos de la sección 12, citando el ID del riesgo y su historia o tarea original. Si falla Notion, se aplicará el respaldo documental de la sección 13.4. El análisis de riesgos se incorporará a las ceremonias existentes, sin presumir que ya tuvo lugar.

La incorporación de la versión **0.11** conserva íntegros el historial 0.1–0.10 y el contenido de las semanas anteriores. No modifica objetivos, requisitos, funcionalidades, once historias, sus puntos, asignaciones, DoD, tareas, velocidad de 8 puntos por Sprint ni cronograma de 10 semanas. Las respuestas propuestas describen cómo controlar los riesgos de ese trabajo y no constituyen ampliaciones del alcance o compromisos de contratación. No se crean archivos adicionales ni se modifica el tablero de Notion.
