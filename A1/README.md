# TA-PFC-E1: Primer Avance - Proyecto de Fin de Curso
**Asignatura:** Ingeniería de Requisitos (ISR-401 UTEQ)  
**Tema del Proyecto:** Aplicación web para la gestión de tutorías, seguimiento de estudiantes y provisión de modelos de clases para su evaluación y desempeño.  
**Equipo:** Jordy Rivas, Luis Yepez, Yerai Chalacán y Angelo Espinoza  

---

## Estructura de Reparto y Asignación de Tareas

Para garantizar una distribución equitativa, lógica y coherente del **Primer Avance (TA-PFC-E1)**, el trabajo se ha dividido en cuatro módulos principales gestionados de forma individual e integrada en el repositorio `pro-req`.

---

### 1. Angelo Espinoza — Módulo: Problema, Situación Actual y Alcance
*Responsable de diagnosticar el dolor del proceso actual y delimitar exactamente qué resolverá (y qué no) la plataforma web de tutorías.*

*   **Tarea 1.1: Diagnóstico de la Situación Actual y Problemática**
    *   *Subtarea 1.1.1:* Describir el proceso actual de gestión de tutorías y seguimiento estudiantil (identificando el uso de métodos manuales, hojas de cálculo dispersas o registros en papel).
    *   *Subtarea 1.1.2:* Detallar los cuellos de botella y dificultades observadas (ej. falta de sincronización de horarios entre docentes y alumnos, ausencia de un repositorio centralizado de modelos de clases, y dificultad para medir el impacto de las tutorías en el rendimiento).
    *   *Subtarea 1.1.3:* Identificar claramente a los afectados directos (estudiantes con riesgo académico, docentes tutores con sobrecarga administrativa y coordinadores sin métricas de desempeño).
*   **Tarea 1.2: Definición de la Visión General del Problema**
    *   *Subtarea 1.2.1:* Redactar el planteamiento de mejora que se espera lograr con la implementación del sistema web.
*   **Tarea 1.3: Delimitación del Alcance (In / Out Scope)**
    *   *Subtarea 1.3.1:* Definir los procesos cubiertos dentro del sistema (registro y autenticación de roles, agendamiento de tutorías, subida de modelos de clases por parte del docente, registro de asistencia y seguimiento al desempeño del estudiante).
    *   *Subtarea 1.3.2:* Especificar explícitamente lo que queda fuera del proyecto actual (ej. pasarelas de pago de matrículas, integración con sistemas contables o gestión de nómina institucional).

---

### 2. Luis Yepez — Módulo: Visión del Sistema y Partes Interesadas (Stakeholders)
*Responsable de formalizar el propósito macro de la aplicación web y estructurar la matriz de actores que interactuarán con el sistema.*

*   **Tarea 2.1: Redacción de la Visión del Sistema**
    *   *Subtarea 2.1.1:* Sintetizar el propósito de la aplicación web de tutorías como una solución integral para optimizar el acompañamiento académico y la evaluación del desempeño.
    *   *Subtarea 2.1.2:* Establecer los objetivos de negocio y académicos de alto nivel que la plataforma debe cumplir.
*   **Tarea 2.2: Identificación de Perfiles de Actores**
    *   *Subtarea 2.2.1:* Identificar y definir formalmente a los usuarios del sistema: *Estudiante*, *Docente Tutor*, *Administrador del Sistema* y *Coordinador Académico*.
*   **Tarea 2.3: Elaboración de la Tabla de Partes Interesadas**
    *   *Subtarea 2.3.1:* Construir la matriz detallada con las columnas requeridas por la guía: **Actor**, **Necesidad principal**, **Nivel de influencia** (Alto/Medio/Bajo) y **Forma de participación** en el ciclo de vida del software (ej. entrevistas iniciales, pruebas de aceptación UAT, validación de modelos de clases).

---

### 3. Jordy Rivas — Módulo: Contexto del Sistema e Intercambio de Información
*Responsable de modelar los límites técnicos y funcionales de la aplicación web frente a su entorno operativo y sus flujos de datos.*

*   **Tarea 3.1: Análisis de las Fronteras de la Solución**
    *   *Subtarea 3.1.1:* Definir formalmente dónde terminan las responsabilidades de la aplicación web y dónde empiezan los sistemas externos o procesos manuales.
*   **Tarea 3.2: Diseño del Diagrama de Contexto**
    *   *Subtarea 3.2.1:* Crear el diagrama de contexto editable (en herramientas compatibles con exportación para LaTeX como Draw.io o PlantUML) ubicando la aplicación web de tutorías en el núcleo.
    *   *Subtarea 3.2.2:* Conectar el núcleo con los actores externos identificados (*Estudiante*, *Docente*, *Administrador*) y los servicios externos (ej. base de datos Supabase/PostgreSQL, servicio de notificaciones SMTP para alertas de tutorías o recordatorios de desempeño).
*   **Tarea 3.3: Documentación de los Flujos de Información**
    *   *Subtarea 3.3.1:* Listar y describir textualmente los datos de entrada al sistema (solicitudes de tutoría, credenciales, calificaciones de desempeño, materiales de clases).
    *   *Subtarea 3.3.2:* Listar y describir textualmente los datos de salida del sistema (confirmaciones de citas, reportes analíticos de rendimiento estudiantil, notificaciones de seguimiento).

---

### 4. Yerai Chalacán — Módulo: Plan de Elicitación e Instrumentos de Captura
*Responsable de planificar cómo el equipo recopilará la información técnica y funcional directamente de los usuarios clave del proceso de tutorías.*

*   **Tarea 4.1: Selección de Técnicas de Elicitación**
    *   *Subtarea 4.1.1:* Definir el uso combinado de entrevistas semiestructuradas a docentes experimentados, cuestionarios a estudiantes y análisis documental de formatos de tutoría vigentes.
*   **Tarea 4.2: Elaboración del Cronograma de Sesiones**
    *   *Subtarea 4.2.1:* Diseñar un plan estructurado indicando: a quién se consultará, qué información específica se necesita extraer, qué técnica se aplicará, quién del equipo será el responsable de ejecutarla y la fecha estimada de realización.
*   **Tarea 4.3: Construcción de la Guía de Entrevista e Instrumentos**
    *   *Subtarea 4.3.1:* Redactar el cuestionario base para las entrevistas (enfocado en indagar cómo el docente estructura sus modelos de clase y cómo el estudiante evalúa su propio progreso tras la tutoría).
    *   *Subtarea 4.3.2:* Preparar las plantillas de actas o registros para documentar las evidencias de las sesiones de elicitación que se acoplarán al repositorio.

---