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
| **0.13** | 10/11/2026 | Semana 8 / Actualización del backlog | Actualización del estado de las tareas del backlog. | Equipo de desarrollo (3 integrantes) |
| **0.14** | 10/11/2026 | Incorporación de IA al Product Backlog | Adición de HU-12 para recomendación de rutas mediante IA, con 8 puntos, pendiente y sin Sprint asignado. Product Backlog: 12 historias y 63 puntos. | Equipo de desarrollo (3 integrantes) |
| **0.15** | 11/11/2026 | Replanificación por capacidad de tres integrantes | Proyección de 24 puntos por Sprint (8 × 3), jornada de 40 horas semanales por integrante y distribución de las 12 historias (63 puntos) en cinco Sprints de dos semanas; actualización de responsabilidades, calidad y riesgos. | Equipo de desarrollo (3 integrantes) |
| **0.16** | 11/11/2026 | Presupuesto de trabajo | Estimación del costo por Sprint y por proyecto con tarifa base de CRC 17.202/h y alternativa de USD 41–45/h, proporcionadas por el solicitante; supuestos y exclusiones en la sección 6.3.1. | Equipo de desarrollo (3 integrantes) |
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
1. **RF-01 — Listo.** El sistema debe permitir registrar información relacionada con las rutas logísticas utilizadas por las empresas, incluyendo origen, destino, distancia y tiempo estimado.
2. **RF-02 — Listo.** El sistema debe ofrecer una funcionalidad visual en mapas y optimizar rutas mediante el análisis de distancia, consumo de recursos y eficiencia operativa.
3. **RF-03 — En proceso.** El sistema debe registrar y mostrar indicadores asociados al uso de recursos, como combustible, materiales y tiempos de operación.
4. **RF-04 — Pendiente.** El sistema debe generar reportes sobre eficiencia operativa, trazabilidad y uso de recursos para apoyar la toma de decisiones.
5. **RF-05 — Pendiente.** El sistema debe permitir visualizar métricas relacionadas con sostenibilidad y el impacto ambiental asociado a las actividades logísticas.
6. **RF-06 — Listo.** El sistema debe incluir un módulo para registrar y actualizar datos de vehículos utilizados en operaciones logísticas.
7. **RF-07 — Listo.** El sistema debe garantizar que los usuarios puedan acceder a las funcionalidades según su rol asignado.

### Requerimientos No Funcionales
1. **RNF-01 — Pendiente.** El sistema debe mantener tiempos de respuesta adecuados (menores a 2 segundos) en consultas principales.
2. **RNF-02 — Listo.** El sistema debe implementar medidas de seguridad y autenticación que protejan los datos registrados.
3. **RNF-03 — Pendiente.** La interfaz del sistema debe ser intuitiva, clara y fácil de utilizar sin necesidad de capacitaciones extensas.
4. **RNF-04 — Pendiente.** El sistema debe ser compatible con navegadores web comunes para garantizar su accesibilidad.
5. **RNF-05 — Pendiente.** Los datos almacenados deben gestionarse siguiendo buenas prácticas que aseguren integridad relacional y consistencia.

### Requerimientos de Dominio
1. **RD-01 — Pendiente.** El sistema debe calcular la distancia estimada y el tiempo de recorrido entre puntos de origen y destino utilizando la fórmula de Haversine y datos geográficos.
2. **RD-02 — En proceso.** El sistema debe procesar matemáticamente el consumo de recursos para generar indicadores de eficiencia y emisiones.
3. **RD-03 — Pendiente.** El sistema debe emplear unidades estandarizadas (kilómetros, horas, litros) para todos los cálculos.

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
El equipo está integrado por **Stuarth Fabricio Miranda Rojas, Cristopher Quiros Araya y Miguel Cruz Vargas**. La planificación individual original declaraba **8 puntos por Sprint**. Por decisión del solicitante, se supone que los tres integrantes trabajan al mismo ritmo y con igual dedicación: **8 × 3 = 24 puntos por Sprint de dos semanas**. Esta es una capacidad proyectada, no una velocidad demostrada mediante entregas. Se conserva la escala de puntos de las historias y se revisará la previsión según los puntos que cumplan el DoD al cerrar cada Sprint.

La jornada prevista es de **lunes a viernes, 8 horas diarias por integrante**. Se asumen diez días laborables por Sprint, sin feriados ni ausencias; cualquier indisponibilidad se descontará en Planning.

| Concepto | Por Sprint (2 semanas) | Proyecto (10 semanas / 5 Sprints) |
| --- | ---: | ---: |
| Horas por integrante | 80 h | 400 h |
| Horas del equipo de tres | 240 h | 1.200 h |
| Reserva de planificación propuesta: 20 % para ceremonias, coordinación e imprevistos | 48 h | 240 h |
| Horas para tareas de historias, incluyendo desarrollo, pruebas y revisión | 192 h | 960 h |
| Capacidad proyectada de puntos | 24 | 120 |

Los puntos expresan esfuerzo relativo; **no se establece una conversión fija de puntos a horas**. En cada Planning se desglosarán las historias en tareas y se estimarán sus horas para comprobar que caben en las 192 horas previstas y en la disponibilidad individual. La reserva del 20 % es un supuesto de esta planificación, no una medición histórica.

**Base de costos:** se presupuestan las 240 horas del equipo por Sprint, incluidas coordinación y reuniones. Si todos tienen tarifa horaria T, el costo laboral es **240 × T por Sprint** y **1.200 × T por proyecto**. Si las tarifas difieren, se calcula **80 × (T_Stuarth + T_Cristopher + T_Miguel)** por Sprint y cinco veces ese importe para el proyecto. El margen de puntos no constituye un ahorro automático de horas o costos mientras se mantenga la dedicación durante diez semanas.

#### 6.3.1 Presupuesto de trabajo del equipo

Se adopta como **escenario base de estimación académica una tarifa de ₡17.202 por hora por integrante**, proporcionada por el solicitante. Como escenario alternativo se calcula una tarifa de **USD 41–45 por hora por integrante**. Estas referencias no cuentan todavía con fuente documental o modalidad contractual verificadas en el expediente; se utilizan como supuestos de presupuesto, sin afirmar que sean un salario promedio comprobado. Se interpreta 17.202 como diecisiete mil doscientos dos colones. No se convierten monedas ni se suman ambos escenarios.

**Cálculo base:**

* Por integrante y Sprint: 80 h × ₡17.202 = **₡1.376.160**.
* Por equipo y Sprint: 3 × 80 h × ₡17.202 = **₡4.128.480**.
* Por integrante en diez semanas: 400 h × ₡17.202 = **₡6.880.800**.
* Por equipo en todo el proyecto: 3 × 400 h × ₡17.202 = **₡20.642.400**.

| Sprint | Semanas | Puntos de historias planificados | Horas del equipo | Costo base (CRC) | Alternativa a USD 41/h | Alternativa a USD 45/h |
| --- | --- | ---: | ---: | ---: | ---: | ---: |
| 1 | 1–2 | 16 | 240 | ₡4.128.480 | USD 9.840 | USD 10.800 |
| 2 | 3–4 | 13 | 240 | ₡4.128.480 | USD 9.840 | USD 10.800 |
| 3 | 5–6 | 8 | 240 | ₡4.128.480 | USD 9.840 | USD 10.800 |
| 4 | 7–8 | 13 | 240 | ₡4.128.480 | USD 9.840 | USD 10.800 |
| 5 | 9–10 | 13 | 240 | ₡4.128.480 | USD 9.840 | USD 10.800 |
| **Total** | **10 semanas** | **63** | **1.200** | **₡20.642.400** | **USD 49.200** | **USD 54.000** |

Todos los Sprints tienen el mismo costo porque se presupuesta la misma dedicación de tres integrantes durante dos semanas, aunque cambien los puntos de las historias seleccionadas. La reserva del 20 % ya está incluida en las 240 horas: no se agrega un 20 % adicional al costo. Los roles de PO, Scrum Master y QA se distribuyen entre estos tres integrantes y no se cobran como personas adicionales.

El **presupuesto base de trabajo del equipo para el proyecto es ₡20.642.400**. El escenario alternativo es **USD 49.200–54.000** por el mismo período. Estos importes cubren únicamente el trabajo a las tarifas asumidas; no constituyen un costo integral de contratación laboral o de operación. El expediente no cuantifica cargas patronales, prestaciones, impuestos, equipos, hosting ni consumo de APIs; no se presume que sean gratuitos o que estén incluidos. El costo integral será el presupuesto de trabajo más los gastos adicionales aplicables una vez definidos, evitando duplicar conceptos que ya incluya una tarifa contratada. Si se trata de una valoración académica sin remuneración efectiva, estos montos representan el valor estimado del esfuerzo, no pagos realizados.

### 6.4 Cronograma del Proyecto de Desarrollo de Software (10 semanas)

El análisis, diseño, desarrollo y pruebas se realizan incrementalmente dentro de cada Sprint. Este cronograma sustituye la separación anterior que situaba todo el desarrollo después del diseño inicial.

| Actividad | S1: semanas 1–2 | S2: semanas 3–4 | S3: semanas 5–6 | S4: semanas 7–8 | S5: semanas 9–10 |
| --- | --- | --- | --- | --- | --- |
| Planificación y refinamiento | Propuesta, arquitectura y Planning | Refinamiento y Planning | Refinamiento y Planning | Refinamiento y Planning | Planning y preparación del cierre |
| Diseño y desarrollo | Rutas, mapa, vehículos y roles | Geocálculo y Dijkstra | Consumo e indicadores | Reportes y CO₂ | IA y ajustes de calidad integral |
| Historias | HU-01, HU-02, HU-07, HU-08 | HU-09, HU-03 | HU-04, HU-10 | HU-05, HU-06 | HU-12, HU-11 |
| Pruebas y revisión | DoD y controles de datos/acceso | DoD y exactitud matemática | DoD y consistencia de indicadores | DoD y contraste de reportes/gráficos | DoD, evaluación de IA y regresión integral |
| Entrega incremental | Base operativa protegida | Rutas calculadas y optimizadas | Indicadores de consumo | Reportes y sostenibilidad | Integración, despliegue y cierre documentado |

---
## 7. Product Backlog Priorizado (Historias de Usuario Optimizadas)

A continuación, se detallan las 12 Historias de Usuario principales que engloban el núcleo funcional y técnico del proyecto.

**Estados propuestos al 10/11/2026 según el cronograma, a criterio del solicitante; no representan implementación ni pruebas verificadas.**

### 7.1 Historias Funcionales Centrales

#### HU-01: Registro de rutas logísticas
* **Estado:** Lista.
* **Como** gestor logístico
* **Quiero** registrar la información detallada de las rutas (origen, destino, distancia y tiempo estimado)
* **Para** centralizar el catálogo de recorridos operativos.
* **Criterios de Aceptación:**
  * **Criterio 1:** Dado que estoy en el formulario, cuando ingreso datos válidos, entonces el sistema guarda la ruta.
* **Prioridad:** Alta. **Estimación:** 3 puntos.
* **Justificación:** Es un desarrollo directo de formulario (CRUD básico) sin integraciones externas.

#### HU-02: Visualización de rutas en mapas (Frontend)
* **Estado:** Lista.
* **Como** gestor logístico
* **Quiero** visualizar las rutas y ubicaciones en un mapa interactivo
* **Para** tener una referencia gráfica clara de los recorridos operativos en la pantalla.
* **Criterios de Aceptación:**
  * **Criterio 1:** Dado que ingreso a una ruta registrada, cuando carga la pantalla, entonces el mapa muestra el origen y el destino.
* **Prioridad:** Alta. **Estimación:** 5 puntos.
* **Justificación:** Implica integrar la API de Google Maps en el frontend (diseño visual), lo que requiere esfuerzo de interfaz pero no incluye la matemática pesada.

#### HU-03: Algoritmo de optimización de rutas (Backend)
* **Estado:** Lista.
* **Como** sistema (Backend)
* **Quiero** ejecutar un algoritmo inteligente para analizar y encontrar la ruta más eficiente
* **Para** ofrecer alternativas que reduzcan los tiempos de transporte y costos operativos.
* **Criterios de Aceptación:**
  * **Criterio 1:** Dado que hay rutas disponibles, cuando solicito la optimización, entonces el sistema analiza usando Dijkstra y devuelve la alternativa más corta.
* **Prioridad:** Alta. **Estimación:** 8 puntos.
* **Justificación:** Requiere programar la lógica matemática desde cero en Python y asegurar que los cálculos de las rutas y grafos no tengan errores de servidor.

#### HU-04: Registro de indicadores de recursos
* **Estado:** En proceso.
* **Como** operario logístico
* **Quiero** registrar el consumo de combustible y materiales
* **Para** medir la eficiencia operativa del viaje.
* **Criterios de Aceptación:**
  * **Criterio 1:** Dado que ingreso el combustible usado, cuando guardo, entonces se asocia al vehículo correcto.
* **Prioridad:** Media. **Estimación:** 5 puntos.

#### HU-05: Generación de reportes de eficiencia
* **Estado:** Pendiente.
* **Como** administrador
* **Quiero** generar reportes exportables de las operaciones
* **Para** apoyar la toma de decisiones gerenciales.
* **Criterios de Aceptación:**
  * **Criterio 1:** Dado que selecciono fechas, cuando exporto, entonces obtengo un archivo PDF o Excel.
* **Prioridad:** Baja. **Estimación:** 5 puntos.

#### HU-06: Panel de métricas de sostenibilidad (CO₂)
* **Estado:** Pendiente.
* **Como** analista ambiental
* **Quiero** visualizar gráficos de huella de carbono
* **Para** verificar el cumplimiento del ODS 9.
* **Criterios de Aceptación:**
  * **Criterio 1:** Dado que hay datos de consumo, cuando entro al panel, entonces veo gráficos con las emisiones.
* **Prioridad:** Media. **Estimación:** 8 puntos.

#### HU-07: Gestión del catálogo de vehículos
* **Estado:** Lista.
* **Como** gestor logístico
* **Quiero** registrar y actualizar la información de los vehículos
* **Para** controlar la flota disponible.
* **Criterios de Aceptación:**
  * **Criterio 1:** Dado que ingreso una placa válida, cuando guardo, entonces se registra el vehículo.
* **Prioridad:** Alta. **Estimación:** 3 puntos.

#### HU-08: Gestión de accesos por roles (Seguridad)
* **Estado:** Lista.
* **Como** administrador de sistemas
* **Quiero** que el sistema asigne permisos según el rol del usuario (operario, gestor)
* **Para** garantizar la privacidad de los datos.
* **Criterios de Aceptación:**
  * **Criterio 1:** Dado que un operario inicia sesión, cuando intenta ver reportes gerenciales, entonces el sistema lo bloquea.
* **Prioridad:** Alta. **Estimación:** 5 puntos.

---

### 7.2 Historias de Dominio y No Funcionales (Técnicas)

#### HU-09: Cálculo geoespacial y tiempos estimados
* **Estado:** Pendiente.
* **Como** sistema (Backend)
* **Quiero** calcular automáticamente la distancia y el tiempo estimado de las rutas
* **Para** asegurar que todos los cálculos operativos del sistema sean precisos.
* **Prioridad:** Alta. **Estimación:** 5 puntos.

#### HU-10: Procesamiento de eficiencia y consumo
* **Estado:** En proceso.
* **Como** sistema (Backend)
* **Quiero** procesar los datos ingresados de combustible y tiempo
* **Para** generar y almacenar los indicadores básicos de eficiencia de la flota.
* **Prioridad:** Media. **Estimación:** 3 puntos.

#### HU-11: Rendimiento, Integridad y Experiencia de Usuario
* **Estado:** Pendiente.
* **Como** desarrollador y usuario final
* **Quiero** que el sistema sea rápido, consistente y fácil de usar en cualquier pantalla
* **Para** garantizar una operación fluida y sin corrupción de datos en la base.
* **Prioridad:** Alta. **Estimación:** 5 puntos.

---

### 7.3 Historia de Inteligencia Artificial

#### HU-12: Recomendación de rutas mediante inteligencia artificial
* **Estado:** Pendiente.
* **Como** gestor logístico
* **Quiero** recibir recomendaciones de rutas mediante un modelo de inteligencia artificial que analice los datos históricos de los recorridos
* **Para** seleccionar rutas con menor tiempo estimado y consumo de combustible.
* **Criterios de Aceptación:**
  * **Criterio 1:** Dado que existen datos históricos suficientes de rutas, tiempos y consumo, cuando solicito una recomendación, entonces el sistema utiliza el modelo de IA para comparar las rutas disponibles y recomendar una alternativa.
  * **Criterio 2:** Dado que recibo una recomendación, cuando consulto su detalle, entonces el sistema muestra el tiempo y consumo estimados de la ruta sugerida.
  * **Criterio 3:** Dado que no existen datos suficientes para generar una recomendación, cuando la solicito, entonces el sistema informa esta limitación y permite utilizar la optimización mediante Dijkstra.
* **Prioridad:** Media. **Estimación:** 8 puntos.
* **Justificación:** Requiere preparar datos históricos, entrenar y evaluar un modelo predictivo e integrar sus recomendaciones con las rutas del sistema.

---

## 8. Planificación y Release Plan (Capacidad: 24 pts / Sprint)

Se mantienen **10 semanas y cinco Sprints de dos semanas**, con capacidad proyectada de **24 puntos por Sprint**. Se programan las **12 historias, que suman 63 puntos**, conservando sus estimaciones: el aumento del equipo permite cubrir todo el backlog y reforzar su calidad, sin aumentar artificialmente el valor de las historias para llenar la capacidad.

| Sprint | Semanas | Historias y puntos | Puntos planificados | Capacidad proyectada | Margen de puntos |
| --- | --- | --- | ---: | ---: | ---: |
| 1 | 1–2 | HU-01 (3), HU-02 (5), HU-07 (3), HU-08 (5) | 16 | 24 | 8 |
| 2 | 3–4 | HU-09 (5), HU-03 (8) | 13 | 24 | 11 |
| 3 | 5–6 | HU-04 (5), HU-10 (3) | 8 | 24 | 16 |
| 4 | 7–8 | HU-05 (5), HU-06 (8) | 13 | 24 | 11 |
| 5 | 9–10 | HU-12 (8), HU-11 (5) | 13 | 24 | 11 |
| **Total** | **10 semanas** | **12 historias** | **63** | **120** | **57** |

**Orden y mejora del trabajo con tres integrantes:**

* **Sprint 1 — Base operativa y seguridad:** registrar rutas y vehículos, visualizar origen y destino y habilitar permisos. La colaboración permite integrar desde el inicio validaciones de datos y accesos, con revisión por otra persona.
* **Sprint 2 — Cálculo y optimización:** completar HU-09 antes de integrar los pesos geográficos en HU-03. Se contrastarán distancias y recorridos con casos de referencia para mejorar la precisión. El tiempo estimado requiere una base explícita de velocidad o tiempos por tramo; Haversine por sí sola calcula distancia, no duración.
* **Sprint 3 — Consumo e indicadores:** completar HU-04 antes de HU-10 y validar datos, unidades y resultados. Se preparará un conjunto de datos de prueba para reportes, sostenibilidad e IA, distinguiéndolo de datos operativos reales.
* **Sprint 4 — Reportes y sostenibilidad:** implementar HU-05 y HU-06 sobre los indicadores del Sprint 3. Se contrastarán los datos exportados y los gráficos con los cálculos de origen y se documentarán los factores de emisión utilizados.
* **Sprint 5 — IA, calidad integral y cierre:** completar HU-12 con los datos disponibles y evaluar sus recomendaciones frente a una referencia; si son insuficientes, se aplicará su criterio de limitación y alternativa Dijkstra, sin declarar validado un modelo sin evidencia. HU-11 verificará rendimiento, integridad y experiencia de usuario sobre el sistema integrado. Las verificaciones de calidad también se ejecutan en cada Sprint mediante el DoD.

El margen de **57 puntos** es capacidad proyectada no comprometida con historias adicionales; no es trabajo terminado ni una bolsa de puntos para volver a contar pruebas. Permite absorber variaciones de estimación, corregir defectos, mejorar validaciones y documentación dentro de las historias y completar su DoD. Estas actividades se desglosarán en horas, sin asignar puntos adicionales salvo una reestimación explícita de alcance. No se promete una mejora fuera de los requisitos existentes ni se acorta el plazo.

Esta tabla es una **replanificación autorizada el 11/11/2026**, no una reconstrucción de ejecución pasada. Los estados documentales de las historias se conservan como antecedentes propuestos al 10/11/2026; no acreditan implementación, pruebas ni cierre de los Sprints reorganizados. La selección se confirmará en cada Planning según dependencias, horas por tarea y disponibilidad de cada integrante.

---

## 9. Sprint Backlog Detallado (Plan actualizado a cinco Sprints)

### Sprint Backlog - Sprint 1 (Base operativa y seguridad - 16 pts)
* **Tarea 1.1:** Diseñar y construir el script SQL para la tabla de rutas. **Estado:** Lista.
  * **Mitigación R-06:** Revisar campos obligatorios y restricciones para impedir datos incompletos o inconsistentes.
  * **Responsable:** Stuarth Fabricio Miranda Rojas.
  * **Evidencia:** Registrar las validaciones del esquema y los resultados de las pruebas en la tarjeta de HU-01.
  * **Si falla:** Corregir el esquema y repetir la validación antes de aceptar la persistencia de datos.

* **Tarea 1.2:** Crear el formulario de ingreso HTML/CSS para HU-01. **Estado:** Lista.

* **Tarea 1.3:** Conectar el frontend para que guarde las rutas (HU-01). **Estado:** Lista.
  * **Mitigación R-05:** Comprobar que los nombres, tipos y unidades de los datos enviados desde el frontend coinciden con los esperados por el backend.
  * **Responsable:** Stuarth Fabricio Miranda Rojas realiza la validación técnica, con apoyo de Cristopher Quiros Araya, quien coordina el seguimiento como dueño del riesgo R-05.
  * **Evidencia:** Registrar los datos enviados y la respuesta obtenida en la tarjeta de HU-01.
  * **Si falla:** Corregir el intercambio de datos y repetir la prueba de integración.
  * **Mitigación R-06:** Comprobar que la ruta guardada conserva los datos ingresados y cumple los criterios de CP-RF01-01.
  * **Responsable:** Stuarth Fabricio Miranda Rojas.
  * **Evidencia:** Registrar la comparación entre los datos ingresados y los almacenados.
  * **Si falla:** Corregir el guardado y repetir la validación antes de aceptar HU-01.

* **Tarea 1.4:** Integrar el script de Google Maps API en el HTML. **Estado:** Lista.
  * **Mitigación R-01:** Validar el acceso a la API y comprobar que el mapa carga sin errores.
  * **Responsable:** Cristopher Quiros Araya.
  * **Evidencia:** Registrar el resultado y una captura o mensaje de error en la tarjeta de HU-02.
  * **Si falla:** Registrar HU-02 como bloqueada y comunicar el impedimento.
  * **Mitigación R-02:** Verificar la modalidad de acceso y el consumo disponible antes de realizar llamadas a la API.
  * **Responsable:** Stuarth Fabricio Miranda Rojas, con apoyo técnico de Cristopher Quiros Araya.
  * **Evidencia:** Registrar la verificación de las condiciones de acceso y del consumo disponible, sin exponer credenciales.
  * **Si falla:** Detener las llamadas que impliquen gasto no autorizado y comunicar el bloqueo.

* **Tarea 1.5:** Programar el Frontend en JS para que dibuje el origen y destino en el mapa (HU-02). **Estado:** Lista.
  * **Mitigación R-01:** Comprobar que el mapa representa correctamente el origen y el destino de una ruta registrada.
  * **Responsable:** Cristopher Quiros Araya.
  * **Evidencia:** Registrar el resultado y una captura de la visualización en la tarjeta de HU-02.
  * **Si falla:** Registrar el error y mantener HU-02 sin aceptar hasta corregirlo y repetir la validación.

### Sprint Backlog - Sprint 2 (Cálculo y optimización - 13 pts)
* **Tarea 2.1:** Programar en Python la estructura de grafos para las ciudades. **Estado:** Lista.
* **Tarea 2.2:** Programar el algoritmo de Dijkstra en FastAPI. **Estado:** Lista.

* **Tarea 2.3:** Crear el endpoint (API) para que el frontend envíe las coordenadas a calcular. **Estado:** Lista.
  * **Mitigación R-05:** Verificar que el endpoint recibe e interpreta las coordenadas con los nombres, tipos y unidades acordados con el frontend.
  * **Responsable:** Stuarth Fabricio Miranda Rojas realiza la validación técnica, con apoyo de Cristopher Quiros Araya, quien coordina el seguimiento como dueño del riesgo R-05.
  * **Evidencia:** Registrar una solicitud válida, los datos recibidos y la respuesta obtenida en la tarjeta de HU-03.
  * **Si falla:** Corregir el intercambio de datos dentro de la tarea existente y repetir la prueba de integración.

* **Tarea 2.4:** Hacer pruebas unitarias sobre los resultados matemáticos devueltos. **Estado:** Lista.
  * **Mitigación R-03:** Comparar los resultados de Dijkstra con grafos pequeños cuya ruta mínima se haya calculado manualmente.
  * **Responsable:** Stuarth Fabricio Miranda Rojas.
  * **Evidencia:** Registrar los datos de entrada, el resultado esperado y el obtenido en la tarjeta de HU-03.
  * **Si falla:** Corregir el algoritmo o el grafo y repetir la prueba fallida y la regresión correspondiente.
  * **Mitigación R-10:** Comprobar que los resultados de estas pruebas quedan registrados como evidencia del criterio de pruebas unitarias del DoD.
  * **Responsable:** Miguel Cruz Vargas.
  * **Evidencia:** Registrar el procedimiento ejecutado y los resultados de las pruebas en la tarjeta de HU-03.
  * **Si falla:** Mantener el criterio como no acreditado y no marcar HU-03 como Hecho hasta completar los cinco criterios del DoD

### Sprint Backlog - Sprint 1: Mitigación vinculada a HU-08

* **Validación de permisos de HU-08:** **Estado:** Lista.
  * **Mitigación R-07:** Comprobar que un usuario con rol operario no puede acceder a reportes gerenciales, incluso mediante acceso directo.
  * **Responsable:** Stuarth Fabricio Miranda Rojas implementa y Miguel Cruz Vargas revisa.
  * **Evidencia:** Registrar el rol utilizado, la operación intentada y el resultado obtenido en la tarjeta de HU-08.
  * **Si falla:** Corregir los permisos y repetir la validación antes de marcar HU-08 como Hecho.

### Trabajo complementario y Sprints 3, 4 y 5

Las tareas 1.1–1.5 y 2.1–2.4 conservan sus identificadores y sus registros previos. El trabajo siguiente completa el nuevo Release Plan. Se trata de actividades planificadas, sin afirmar su ejecución; sus horas se estimarán en Planning conforme a la sección 6.3.

| Sprint | Historia | Trabajo previsto y verificación |
| --- | --- | --- |
| 1 | HU-07 | Implementar registro y actualización de vehículos; validar placa y datos persistidos. |
| 1 | HU-08 | Implementar permisos por rol y ejecutar la validación R-07 descrita arriba. |
| 2 | HU-09 | Implementar Haversine y la base del tiempo estimado; validar coordenadas, unidades y casos conocidos (R-04) antes de integrar HU-03. |
| 3 | HU-04 | Registrar consumo asociado a vehículo o ruta; validar cantidades positivas y relaciones. |
| 3 | HU-10 | Calcular indicadores sobre HU-04; contrastar fórmulas y unidades con ejemplos independientes. |
| 4 | HU-05 | Generar la exportación prevista; contrastar filtros y contenido con datos de origen. |
| 4 | HU-06 | Construir el panel de CO₂; documentar factores y verificar cálculos y gráficos. |
| 5 | HU-12 | Preparar datos, entrenar y evaluar el modelo e integrar recomendaciones; verificar los tres criterios de aceptación, incluida la falta de datos. |
| 5 | HU-11 | Verificar consultas principales menores a 2 segundos, integridad de datos, compatibilidad y usabilidad; corregir hallazgos y repetir las verificaciones afectadas. |

La integración, pruebas, revisión y documentación de cada historia forman parte de su esfuerzo original. Los criterios de calidad se aplican desde el primer Sprint; HU-11 consolida la validación del sistema completo.

### Actividades de seguimiento y planificación

* **Mitigación R-08:** Revisar en cada Daily Scrum la disponibilidad de los integrantes, los bloqueos y los límites WIP. **Estado:** En proceso.
  * **Responsable:** Cristopher Quiros Araya.
  * **Evidencia:** Registrar los impedimentos y acuerdos de apoyo en las tarjetas afectadas.
  * **Si se detecta indisponibilidad:** Coordinar apoyo entre los integrantes, conservando la revisión por otra persona y comunicando cualquier trabajo que no pueda completarse.

* **Respuesta R-09:** Contrastar en cada Sprint Planning y Sprint Review los compromisos con el Release Plan de 63 puntos y el límite proyectado de 24 puntos por Sprint. **Estado:** En proceso.
  * **Responsable:** Stuarth Fabricio Miranda Rojas.
  * **Evidencia:** Registrar la cobertura de las 12 historias, sus dependencias y el cumplimiento de la capacidad en horas y puntos de cada Sprint.
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

Los roles se acumulan dentro del equipo de tres; la capacidad proyectada conjunta es de 24 puntos por Sprint según la sección 6.3, sin sumar capacidad adicional por cada rol. Cada responsable implementará su historia, actualizará su tarjeta y aportará evidencia. La revisión corresponderá a otro integrante para evitar que una persona sea el único validador de su propio trabajo.

| Historia | Responsable de implementación | Responsable de revisión del DoD | Sprint actualizado |
| --- | --- | --- | --- |
| HU-01 (3 puntos) | Stuarth Fabricio Miranda Rojas | Miguel Cruz Vargas | 1 |
| HU-02 (5 puntos) | Cristopher Quiros Araya | Miguel Cruz Vargas | 1 |
| HU-03 (8 puntos) | Stuarth Fabricio Miranda Rojas | Miguel Cruz Vargas | 2 |
| HU-04 (5 puntos) | Miguel Cruz Vargas | Stuarth Fabricio Miranda Rojas | 3 |
| HU-05 (5 puntos) | Miguel Cruz Vargas | Stuarth Fabricio Miranda Rojas | 4 |
| HU-06 (8 puntos) | Cristopher Quiros Araya | Miguel Cruz Vargas | 4 |
| HU-07 (3 puntos) | Cristopher Quiros Araya | Miguel Cruz Vargas | 1 |
| HU-08 (5 puntos) | Stuarth Fabricio Miranda Rojas | Miguel Cruz Vargas | 1 |
| HU-09 (5 puntos) | Miguel Cruz Vargas | Stuarth Fabricio Miranda Rojas | 2 |
| HU-10 (3 puntos) | Miguel Cruz Vargas | Stuarth Fabricio Miranda Rojas | 3 |
| HU-11 (5 puntos) | Miguel Cruz Vargas | Cristopher Quiros Araya | 5 |
| HU-12 (8 puntos) | Stuarth Fabricio Miranda Rojas | Miguel Cruz Vargas | 5 |

En el Sprint 1, Stuarth asume las tareas originales 1.1 a 1.3 de HU-01 y HU-08; Cristopher, las tareas 1.4 y 1.5 de HU-02 y HU-07; Miguel coordina su revisión. En el Sprint 2, Stuarth implementa HU-03 y Miguel HU-09, con revisión cruzada. En el Sprint 3, Miguel implementa HU-04 y HU-10, con apoyo de interfaz de Cristopher; en el Sprint 4, Miguel implementa HU-05 y Cristopher HU-06; en el Sprint 5, Stuarth implementa HU-12 y Miguel coordina HU-11, con verificación de Cristopher. Nadie concentra más de 8 puntos de responsabilidad principal en un Sprint. La asignación de puntos no sustituye la estimación de horas: implementación, apoyo y revisión deben caber en la disponibilidad de cada persona.

Se mantienen las **10 semanas y cinco Sprints**, ahora con **24 puntos proyectados por Sprint**. Las **12 historias y sus 63 puntos** tienen Sprint y responsables asignados. Las estimaciones individuales no cambian. La capacidad de 120 puntos supera el backlog en 57 puntos y se utiliza como margen de planificación, no como obligación de ampliar el alcance. Las tareas complementarias se detallan en la sección 9; cada responsable contará con colaboración del equipo sin duplicar puntos y con revisión independiente.

---

## 12. Plan de Comunicaciones del Proyecto

**Proyecto:** Sistema inteligente para gestión y optimización de operaciones logísticas  
**Equipo:** Stuarth Fabricio Miranda Rojas, Cristopher Quiros Araya y Miguel Cruz Vargas  
**Base:** Antecedentes de las versiones 0.8–0.14 y replanificación de capacidad, asignaciones y horarios de la versión 0.15.
**Referencia:** [Optimización logística · Centro del Sprint 1](https://app.notion.com/p/40f28b05e206818bae44c111edf7ee18)

### 12.1. Propósito y fuentes

El plan establece cómo comunicar avances, bloqueos, validaciones y decisiones mediante el tablero existente y las ceremonias ya previstas: Sprint Planning, Daily Scrum, Sprint Review y Sprint Retrospective.

La página de Notion fue consultada el 04/11/2026, fecha local de Guatemala. En esa consulta documentaba HU-01 y HU-02, las cuatro columnas, los límites WIP como propuestas, las asignaciones individuales pendientes y ningún avance confirmado. Esa descripción corresponde al momento de la consulta. Las asignaciones y reglas que siguen son definiciones de esta actualización del Markdown; no se ha modificado Notion ni se afirma que ya las refleje.

### 12.2. Participantes y responsabilidades de comunicación

Cada responsable de historia actualizará el estado, los avances y los impedimentos en los comentarios de su tarjeta existente. El revisor de la sección 11 registrará el resultado de la validación. Cristopher facilitará las ceremonias, comprobará la coherencia del tablero y registrará los acuerdos generales en comentarios de la página principal existente de Notion.

Stuarth será el enlace con los profesores **Deiver Cubero Molina y Yesenia Calvo Araya**. Al cierre de cada Sprint preparará un resumen de historias terminadas con evidencia, trabajo restante, bloqueos y consultas académicas. El canal documental será el Markdown del proyecto y el resumen quedará registrado en los comentarios de la página principal de Notion. Para la comunicación directa se utilizará el espacio de clase del curso, sin crear cuentas, correos o reuniones adicionales ni suponer que el profesor tiene acceso a Notion. Las respuestas se registrarán solo cuando se reciban; no se comprometen plazos de respuesta del profesor.

Los demás interesados del mapa se mantienen como roles del contexto conceptual. No se atribuyen nombres, contactos ni participación real a empresas, conductores, clientes o entidades reguladoras. Sus necesidades se revisarán con los requisitos originales en la Sprint Review; no se programan envíos externos ni se inventan representantes. Las dudas sobre su interpretación se canalizarán por Stuarth al profesor dentro del seguimiento académico existente.

### 12.3. Uso del tablero y límites WIP

El tablero existente del Sprint 1 fue definido para HU-01 y HU-02 (8 puntos). La planificación local actualizada contempla **HU-01, HU-02, HU-07 y HU-08 (16 puntos)**, junto con las tareas originales 1.1 a 1.5 y el trabajo complementario de la sección 9. Esta edición no modifica Notion; su contenido deberá reconciliarse con el Release Plan antes de usarlo como referencia vigente.

| Columna existente | Significado y regla de movimiento |
| --- | --- |
| Pendiente | Trabajo no iniciado. El responsable definido en la sección 11 lo mueve a En proceso cuando comience realmente. |
| En proceso | Implementación activa. El responsable lo mueve a En revisión cuando esté listo para validar y haya incorporado la evidencia disponible. |
| En revisión | El revisor comprueba el DoD. Si falla, registra el motivo y devuelve la historia a En proceso. |
| Hecho | El revisor mueve la historia únicamente después de comprobar los cinco criterios del DoD y dejar evidencia. |

Para este plan se adoptan **máximo 2 tarjetas en En proceso** y **máximo 2 en En revisión**; Pendiente y Hecho quedan sin límite. Se trata de una regla de coordinación manual, no de una restricción automática de Notion. Cristopher vigilará los límites. Si se alcanza uno, el equipo ayudará a terminar o revisar el trabajo existente antes de iniciar otra tarjeta. Si un retorno desde revisión pudiera superar el límite de En proceso, se pausará otra implementación, registrando la pausa en su tarjeta, antes de reanudar la historia devuelta; no se ocultará el trabajo iniciado moviéndolo a Pendiente.

Las actualizaciones de tarjetas corresponderán al trabajo real y se harán el mismo día de trabajo en que cambie su estado. Estas definiciones no autorizan añadir historias al Sprint ni aumentar la velocidad.

### 12.4. Matriz de comunicaciones internas

Se fija el siguiente horario de planificación en **hora de Costa Rica**, relativo a las semanas de cada Sprint del Release Plan actualizado. Como distribución operativa propuesta, se utiliza 08:00–17:00 con una hora de almuerzo no contabilizada, para completar ocho horas diarias; las ceremonias se incluyen dentro de esa jornada. Se aplica al trabajo futuro, sin reconstruir ni dar por realizadas ceremonias pasadas. La modalidad será escrita mediante comentarios en Notion, sin incorporar otra herramienta. Los bloques horarios reservan una ventana de intercambio, no acreditan asistencia ni disponibilidad previamente comprobada.

| Comunicación | Momento y duración | Responsable y participantes | Contenido y registro |
| --- | --- | --- | --- |
| Sprint Planning | Primer lunes del Sprint, 09:00–09:45. | Facilita Cristopher; participan los tres. | Revisar historias del Release Plan y responsabilidades de la sección 11; resumen en comentarios de la página principal. |
| Daily Scrum | Lunes a viernes, 08:00–08:15. | Facilita Cristopher; cada integrante comunica su estado. | Avance real, siguiente paso dentro de la historia y bloqueos; comentarios de las tarjetas. |
| Cambio de estado | El mismo día de trabajo del cambio. | Responsable de historia o revisor, según la columna. | Justificación y evidencia en la tarjeta existente. |
| Bloqueo | Al detectarlo, con respuesta interna a más tardar en el siguiente Daily Scrum. | Lo comunica quien lo detecte; coordina Cristopher. | Registro en la tarjeta y seguimiento mientras persista. |
| Sprint Review | Segundo viernes del Sprint, 15:00–15:30. | Participan los tres; Miguel presenta el resultado de validación. | Contrastar resultados con requisitos y DoD; resumen en comentarios de la página principal. La participación externa no es necesaria para la revisión interna y no se da por confirmada. |
| Sprint Retrospective | Segundo viernes del Sprint, 15:30–15:50. | Facilita Cristopher; participan los tres. | Revisar dificultades de coordinación y registrar acuerdos en comentarios de la página principal. |

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

Las asignaciones, los horarios y los límites WIP de esta versión se registran como definiciones de planificación autorizadas por el solicitante, no como acuerdos ya votados por los integrantes. Las decisiones posteriores no modificarán automáticamente el alcance, los puntos ni el cronograma. Las 12 historias se programan según las secciones 8 y 11; cualquier cambio posterior debe registrar su efecto sobre dependencias, capacidad y fecha de entrega.

### 12.8. Conservación del alcance y estado de aplicación

Se conservan los objetivos, requerimientos, funcionalidades, 12 historias, sus 63 puntos, tareas técnicas originales, DoD y plazo de 10 semanas. La versión 0.15 sustituye la capacidad y las asignaciones anteriores por la planificación de las secciones 6.3, 8, 9 y 11; todas las historias quedan programadas.

Se conserva el historial anterior y se añade la versión 0.15. Esta edición se limita a los Markdown locales: no modifica el tablero de Notion, no envía mensajes ni crea eventos. Por ello, las nuevas asignaciones y reglas quedan documentadas aquí sin afirmar que ya estén aplicadas en el tablero o que se hayan realizado reuniones, pruebas o entregas.

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
| R-04 | Si Haversine recibe coordenadas o unidades interpretadas incorrectamente, entonces las distancias de HU-09 y los cálculos que las utilicen serán inconsistentes. | técnico | amenaza | 2 | 3 | 6 — Alta | Stuarth Fabricio Miranda Rojas | El dominio exige cálculos geográficos y unidades estandarizadas; HU-09 está programada en el Sprint 2 y requiere validar coordenadas y unidades antes de integrar los cálculos. |
| R-05 | Si Frontend y Backend intercambian coordenadas o datos de rutas con formatos incompatibles, entonces fallará el guardado o el cálculo solicitado desde la interfaz. | técnico | amenaza | 2 | 2 | 4 — Media | Cristopher Quiros Araya | Las tareas 1.3 y 2.3 conectan componentes desarrollados por integrantes distintos. |
| R-06 | Si el esquema SQL o el guardado permiten datos incompletos o relaciones inconsistentes, entonces las rutas registradas y los indicadores derivados perderán integridad. | técnico | amenaza | 2 | 3 | 6 — Alta | Stuarth Fabricio Miranda Rojas | La persistencia de HU-01 y el requisito no funcional de integridad dependen de la tabla y la conexión de guardado. |
| R-07 | Si la validación de permisos permite a un operario acceder a información restringida, entonces HU-08 incumplirá el control por roles y expondrá datos. | técnico | amenaza | 2 | 3 | 6 — Alta | Stuarth Fabricio Miranda Rojas | El criterio de HU-08 exige bloquear accesos no autorizados; no hay evidencia de validación. |
| R-08 | Si un integrante no está disponible para implementar o revisar su historia, entonces se acumulará trabajo en proceso o revisión y se pondrá en riesgo el cierre del Sprint. | equipo | amenaza | 2 | 2 | 4 — Media | Cristopher Quiros Araya | Tres integrantes concentran roles técnicos y de coordinación; cada historia requiere revisión de otra persona. |
| R-09 | Si se utiliza el antiguo Release Plan de 40 puntos o se interpreta la proyección de 24 puntos como velocidad demostrada, entonces se comunicarán compromisos incompatibles con la planificación actual y se pondrá en riesgo el plazo de 10 semanas. | alcance | amenaza | 3 | 3 | 9 — Alta | Stuarth Fabricio Miranda Rojas | La versión 0.15 programa 63 puntos en cinco Sprints; la capacidad de 24 puntos se basa en igual ritmo de trabajo, pendiente de validación con entregas. |
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

Las acciones siguientes concretan controles dentro de historias, tareas y criterios de calidad ya existentes. **Las acciones de mitigación se incorporan en la sección 9 como subtareas de los Sprints 1 y 2, una actividad de validación de HU-08 en el Sprint 1 y actividades de seguimiento para R-08 y R-09**, sin añadir historias ni modificar sus puntos. La programación vigente es la de la sección 8; R-04 se incorpora al trabajo de HU-09 en el Sprint 2. Los estados y evidencias anteriores no se reinterpretan como ejecución de esta replanificación.

| ID | Estrategia | Acción concreta e ítem correspondiente del backlog existente | Disparador verificable | Contingencia o respaldo |
| --- | --- | --- | --- | --- |
| R-01 | Mitigar; aceptar la indisponibilidad externa que no controla el equipo. | En **HU-02, Sprint 1, tareas 1.4 y 1.5**, comprobar que la integración carga el mapa y representa origen y destino; registrar errores de acceso y su contexto como evidencia de la validación. | El mapa no carga o la solicitud es rechazada durante la ejecución de esas tareas o su revisión. | Registrar HU-02 como bloqueada y continuar únicamente trabajo original que no dependa del servicio. Reintentar tras resolver el acceso; no sustituir proveedor ni declarar aceptada la visualización con una simulación. |
| R-02 | Evitar gasto no autorizado; mitigar exposición presupuestaria. | Como condición de **HU-02, tarea 1.4**, Stuarth revisará con Cristopher la modalidad de acceso y el consumo disponible en la cuenta que se utilice antes de realizar llamadas de integración; mantener las validaciones limitadas a las necesarias para HU-02. | La cuenta exige un pago no autorizado, no permite verificar el consumo o informa que el uso previsto excede lo disponible. | Detener las llamadas que impliquen gasto y comunicar el bloqueo por la vía de la sección 12. Mantener la funcionalidad pendiente hasta resolver la restricción; no contratar automáticamente otro plan o servicio. |
| R-03 | Mitigar. | En **HU-03, Sprint 2, tareas 2.1, 2.2 y 2.4**, contrastar los resultados con grafos pequeños cuyo recorrido mínimo pueda calcularse manualmente; revisar pesos y conexiones antes de aceptar la lógica. | Una prueba de la tarea 2.4 devuelve una ruta distinta de la mínima esperada o no resuelve un recorrido disponible. | Corregir el grafo o Dijkstra dentro de HU-03 y repetir la prueba fallida y la regresión correspondiente. Conservar la historia sin terminar mientras persista la discrepancia. |
| R-04 | Mitigar la precisión del cálculo y su dependencia de integración. | En **HU-09**, contrastar coordenadas, conversión de unidades y distancia contra ejemplos calculables de forma independiente; aplicar las unidades del requisito de dominio 3. **HU-09 se programa en el Sprint 2**, con trabajo complementario en la sección 9, previo a la integración de HU-03. | La revisión detecta mezcla de grados y radianes, unidades distintas de kilómetros o una distancia incompatible con los datos de entrada. | No utilizar el resultado discrepante como evidencia de aceptación; registrar la dependencia afectada y corregir dentro de HU-09 durante el Sprint 2. No estimar tiempo únicamente a partir de distancia sin una base definida en los requisitos. |
| R-05 | Mitigar. | En **HU-01, tarea 1.3**, y **HU-03, tarea 2.3**, contrastar los nombres, tipos y unidades de los datos enviados y recibidos; realizar la verificación de integración ya exigida por el DoD. | Una solicitud válida desde la interfaz es rechazada, guarda datos distintos o devuelve coordenadas incompatibles. | Volver la historia afectada a En proceso, corregir el intercambio en las tareas existentes y repetir la integración; no añadir endpoints ajenos a las historias. |
| R-06 | Mitigar. | En **HU-01, tareas 1.1 y 1.3**, revisar campos y relaciones del esquema y contrastar el dato guardado con la entrada válida del **CP-RF01-01**; comprobar el requisito no funcional 5 al validar la persistencia. | La ruta guardada pierde campos, admite origen/destino inválidos o queda asociada a datos inconsistentes. | Detener la validación de la persistencia afectada y corregir esquema o guardado en las mismas tareas. Repetir la verificación con datos de prueba; no borrar registros reales ni afirmar recuperación mediante copias cuya existencia no está acreditada. |
| R-07 | Mitigar. | En **HU-08, Sprint 1**, verificar su criterio de aceptación con un operario que intenta acceder a reportes gerenciales y contrastar el resultado con el rol autorizado. **La validación se incorpora en la sección 9, en el apartado del Sprint 1**, como actividad vinculada a HU-08 y al DoD. Stuarth implementa y Miguel revisa. | Un usuario con rol operario logra acceder a una operación restringida durante la validación. | Impedir que la historia se marque Hecho o se entregue como segura; corregir los permisos dentro de HU-08 y repetir la validación de acceso e integración. |
| R-08 | Mitigar. | En las historias asignadas en la **sección 11**, el responsable mantendrá el avance y las evidencias en sus comentarios; Cristopher vigilará el WIP y coordinará apoyo sobre las mismas tareas. Para Sprint 1 se vincula a **1.1–1.5** y para Sprint 2 a **2.1–2.4**; en el resto del plan, al trabajo complementario de las 12 historias descrito en la sección 9. | Un responsable comunica indisponibilidad o falta su actualización en una ventana diaria sin registro previo. | Redistribuir temporalmente el trabajo original entre los otros dos integrantes mediante decisión registrada, preservando revisión por otra persona. Si no hay capacidad, comunicar el trabajo no terminado, sin elevar velocidad, puntos ni extender fechas automáticamente. |
| R-09 | Evitar promesas fuera del Release Plan; aceptar el riesgo residual de cobertura. | Stuarth contrastará los compromisos con la **sección 8 y las HU originales** en Planning y Review; verificar la asignación de las 12 historias y sus 63 puntos, la disponibilidad en horas y el límite proyectado de 24 puntos por Sprint. Este control de gestión no agrega puntos técnicos. | Se usa una asignación anterior, se supera la capacidad de un Sprint o la carga de tareas excede las horas de un integrante. | Revisar la carga con el equipo y registrar una decisión que preserve dependencias y DoD; utilizar el margen disponible dentro de los cinco Sprints sin aumentar automáticamente la velocidad ni extender las diez semanas. Si no cabe el trabajo, comunicar la desviación y resolver la prioridad antes de comprometer una nueva entrega. |
| R-10 | Mitigar. | En **tarea 2.4 de HU-03** y en la revisión de **todas las historias conforme al DoD de sección 10**, el revisor comprobará cada criterio con la evidencia de sección 12.6 antes del movimiento a Hecho; vigilar el límite de 2 tarjetas en revisión. No se crean tareas de pruebas nuevas. | Una historia se propone como Hecho sin evidencia de algún criterio, falla una validación o se acumulan más de dos tarjetas en revisión. | Mantener o devolver la historia a En proceso según el fallo, priorizar su corrección y revisión dentro del trabajo original y comunicar lo no validado en la Review. No omitir criterios para cumplir una fecha. |

#### 13.3.2. Fecha de revisión y evaluación residual

**Fecha de evaluación documental inicial: 04/11/2026. Próxima revisión programada de los diez riesgos: 11/11/2026**, utilizando el seguimiento ya previsto; esta fecha se aplica al registro de riesgos y no cambia las semanas ni las fechas de entrega del proyecto. Se revisará antes si aparece un disparador. No se afirma que ninguna de estas revisiones se haya realizado. Después se actualizará el registro en las Planning y Review existentes mientras el proyecto continúe activo, sin crear reuniones adicionales.

Los valores residuales siguientes son **estimaciones objetivo condicionadas a ejecutar y acreditar las acciones**. Se reduce la probabilidad cuando corresponde, sin asumir que desaparece la consecuencia. Mientras no haya evidencia, se conserva como exposición vigente la puntuación inicial de la matriz.

| ID | Próxima revisión programada | P residual | I residual | Prioridad residual objetivo | Condición y exposición que permanece |
| --- | --- | :---: | :---: | --- | --- |
| R-01 | 11/11/2026 | 1 | 3 | 3 — Media | Solo tras validar el acceso y mapa; puede persistir una interrupción del proveedor. |
| R-02 | 11/11/2026 | 1 | 3 | 3 — Media | Solo con modalidad y consumo verificados; no se asegura gratuidad futura ni disponibilidad presupuestaria. |
| R-03 | 11/11/2026 | 1 | 3 | 3 — Media | Solo tras evidencia de la tarea 2.4; permanecen casos no cubiertos por la validación. |
| R-04 | 11/11/2026 | 2 | 3 | 6 — Alta | La asignación al Sprint 2 no demuestra precisión: se conserva la exposición hasta acreditar los controles de HU-09. |
| R-05 | 11/11/2026 | 1 | 2 | 2 — Baja | Solo tras integración comprobada; cambios posteriores podrían reintroducir incompatibilidades. |
| R-06 | 11/11/2026 | 1 | 3 | 3 — Media | Solo tras evidencia de persistencia íntegra; permanecen errores posibles fuera de los casos revisados. |
| R-07 | 11/11/2026 | 1 | 3 | 3 — Media | Solo tras comprobar roles; una modificación posterior puede introducir un acceso indebido. |
| R-08 | 11/11/2026 | 1 | 2 | 2 — Baja | Solo con avance accesible y apoyo coordinado; una ausencia prolongada sigue afectando la capacidad. |
| R-09 | 11/11/2026 | 2 | 3 | 6 — Alta | La replanificación cubre las 12 historias, pero permanecen la incertidumbre de velocidad y el riesgo de utilizar asignaciones antiguas; se requiere comprobar capacidad real y comunicar la versión vigente. |
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

**Antecedente histórico de la versión 0.11 (sustituido en capacidad y programación por la versión 0.15):** La incorporación de la versión **0.11** conserva íntegros el historial 0.1–0.10 y el contenido de las semanas anteriores. No modifica objetivos, requisitos, funcionalidades, once historias, sus puntos, asignaciones, DoD, tareas, velocidad de 8 puntos por Sprint ni cronograma de 10 semanas. Las respuestas propuestas describen cómo controlar los riesgos de ese trabajo y no constituyen ampliaciones del alcance o compromisos de contratación. No se crean archivos adicionales ni se modifica el tablero de Notion.
