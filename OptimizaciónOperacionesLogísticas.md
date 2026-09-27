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