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
| **0.5** | 21/10/2026 | Semana 5 | Desglose completo de los requerimientos en Historias de Usuario (regla de las 3 C's). | Stuarth Fabricio Miranda Rojas |
| **0.6** | 21/10/2026 | Semana 5 | Optimización y recorte del alcance para enfocar el valor de negocio. | Stuarth Fabricio Miranda Rojas |
| **0.7** | 21/10/2026 | Semana 5 | División de historia de 13 puntos en dos (HU-02 y HU-03) y renumeración del Backlog para calzar con la velocidad de 8 puntos/Sprint. | Stuarth Fabricio Miranda Rojas |

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
* **Personas:** Capacidad operativa individual asumiendo todos los roles del proyecto.

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
Para desarrollar esta plataforma en un entorno real con un plazo de **10 semanas (5 Sprints)**, se estimaría un equipo ideal de **4 profesionales** (1 Backend Senior, 1 Frontend, 1 QA y 1 Scrum Master/PO). Sin embargo, el proyecto se ejecuta de forma individual por **Stuarth Fabricio Miranda Rojas**, limitando la capacidad (velocidad) a un promedio de **8 puntos de historia por Sprint**.

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

Dado que la capacidad individual (Velocidad) es de 8 puntos por iteración, las historias clave se distribuyen de la siguiente forma para asegurar entregas funcionales exactas a la capacidad:

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

### Sprint Backlog - Sprint 1 (Registro y Mapas - 8 pts)
* **Tarea 1.1:** Diseñar y construir el script SQL para la tabla de rutas.
* **Tarea 1.2:** Crear el formulario de ingreso HTML/CSS para HU-01.
* **Tarea 1.3:** Conectar el frontend para que guarde las rutas (HU-01).
* **Tarea 1.4:** Integrar el script de Google Maps API en el HTML.
* **Tarea 1.5:** Programar el Frontend en JS para que dibuje el origen y destino en el mapa (HU-02).

### Sprint Backlog - Sprint 2 (Lógica Matemática - 8 pts)
* **Tarea 2.1:** Programar en Python la estructura de grafos para las ciudades.
* **Tarea 2.2:** Programar el algoritmo de Dijkstra en FastAPI.
* **Tarea 2.3:** Crear el endpoint (API) para que el frontend envíe las coordenadas a calcular.
* **Tarea 2.4:** Hacer pruebas unitarias sobre los resultados matemáticos devueltos.

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

Nota aclaratoria: Al ser un proyecto individual, **Stuarth Fabricio Miranda Rojas** asume las responsabilidades de todos los roles (PO, SM, Frontend, Backend y QA) para garantizar la ejecución de las fases en las 10 semanas de plazo.