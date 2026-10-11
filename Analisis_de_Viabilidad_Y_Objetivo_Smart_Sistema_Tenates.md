# DOCUMENTO DETALLADO: OBJETIVO SMART Y ANÁLISIS DE VIABILIDAD MULTIDIMENSIONAL

**Asignatura:** Gestión de Proyectos de Software (SCG-1009)

**Tema:** Objetivo SMART y Análisis de Viabilidad Multidimensional

**Unidad:** 3. Planificación del Proyecto

**Proyecto:** Sistema de apoyo para vendedores de tenates artesanales de palma

**Lugar:** Heroica Ciudad de Tlaxiaco, Oaxaca

**Metodología de trabajo:** eduScrum

**Equipo de desarrollo:** Maritza Sanchez Garcia, Paola Rosario Ayala, Ariadna Belen Bernabe Juarez, Mayra Gonzalez Lita

## 1. Formulación del objetivo SMART

### Objetivo del proyecto

Desarrollar y validar un sistema de software para apoyar a vendedores y artesanas productoras de tenates artesanales de palma de la Heroica Ciudad de Tlaxiaco, Oaxaca, mediante el registro del tiempo de elaboración y costo de los materiales, el control de existencias y ventas, el registro de las características de los productos y la publicación de un catálogo digital. El sistema buscará facilitar la determinación de precios mínimos, mejorar el control de los productos y ampliar su visibilidad comercial, considerando el uso desde teléfonos móviles y las condiciones de conectividad limitada de la región Mixteca. El desarrollo se realizará mediante eduScrum durante el periodo académico de agosto a diciembre de 2026, verificando las cuatro historias de usuario definidas en el backlog mediante criterios de aceptación, pruebas funcionales y evidencias de calidad.

### Desglose de las dimensiones SMART

**S — Específico:** desarrollar una solución informática que permita registrar los costos y tiempos de elaboración, controlar las existencias y ventas, administrar las características de los tenates y publicar productos en un catálogo digital compartido.

**M — Medible:** evaluar el cumplimiento mediante las cuatro historias de usuario del proyecto, sus criterios de aceptación y los resultados de las pruebas. Se buscará alcanzar el 100 % de cumplimiento de los criterios de aceptación seleccionados, validar los datos obligatorios y evitar errores críticos conocidos al finalizar las pruebas.

**A — Alcanzable:** organizar el trabajo en actividades incrementales mediante eduScrum, priorizando las funcionalidades del backlog y distribuyendo las tareas de análisis, diseño, desarrollo, pruebas y documentación entre los integrantes del equipo, de acuerdo con sus responsabilidades y disponibilidad.

**R — Relevante:** contribuir a que las personas dedicadas a la elaboración y venta de tenates conozcan mejor sus costos, mantengan un registro de sus existencias, consulten sus ventas y presenten sus productos a posibles compradores, sin depender exclusivamente de la comercialización presencial.

**T — Temporalizado:** realizar las actividades de planificación, desarrollo, pruebas y documentación entre agosto y diciembre de 2026, de acuerdo con el calendario del proyecto. Las fechas específicas de entrega deberán establecerse en el tablero eduScrum.

## 2. Trazabilidad con el backlog y el costo de la calidad

La trazabilidad permitirá relacionar las necesidades de las artesanas y vendedores con las historias de usuario, los criterios de aceptación, las pruebas y las evidencias obtenidas durante el desarrollo.

### A. Relación con las historias de usuario

**HU01. Registro de tiempo y costo de elaboración**

El sistema deberá registrar el tiempo de tejido y el costo de la palma utilizada en cada pieza. Con los datos necesarios y la fórmula previamente definida por el equipo, deberá calcular el precio mínimo. Si falta información, deberá indicar qué dato se necesita, sin presentar resultados inventados.

**HU02. Control de productos para el tianguis**

El sistema deberá registrar las existencias y las ventas realizadas durante los días de mercado. Las cantidades disponibles deberán actualizarse correctamente y permitir consultar los registros históricos, evitando inventarios negativos y duplicados conocidos en las pruebas.

**HU03. Catálogo digital de tenates**

El sistema deberá permitir publicar fotografías, medidas y precios de los productos en un catálogo compartido. También deberá reflejar correctamente la disponibilidad de los tenates y facilitar la publicación desde un teléfono móvil en un máximo de tres pasos, conforme al criterio establecido en la historia.

**HU04. Registro de características de los tenates terminados**

El sistema deberá guardar y consultar las características de los productos, como tipo, medida, material y precio. Deberá validar la información obligatoria y rechazar datos inválidos antes de guardar el registro.

### B. Costo de la calidad (CoQ)

El costo de la calidad permite identificar el esfuerzo y los recursos destinados a prevenir errores, evaluar el funcionamiento del sistema y corregir defectos.

**Costos de prevención**

- Revisar las historias de usuario y sus criterios de aceptación.
- Definir las reglas para calcular el precio mínimo.
- Establecer validaciones para cantidades, medidas, precios y datos obligatorios.
- Diseñar pruebas antes de implementar cada funcionalidad.
- Revisar la facilidad de uso desde teléfonos móviles.
- Analizar los riesgos relacionados con la conectividad limitada.

**Costos de evaluación**

- Probar el registro del tiempo y costo de elaboración.
- Verificar el cálculo del precio mínimo con datos conocidos.
- Comprobar la actualización de las existencias después de registrar ventas.
- Revisar la publicación y disponibilidad de los productos.
- Validar el registro y consulta de las características de los tenates.
- Realizar pruebas de usabilidad y disponibilidad de información guardada.

**Costos de fallas internas**

- Corregir errores detectados antes de entregar una funcionalidad.
- Reparar cálculos incorrectos y validaciones defectuosas.
- Corregir duplicados e inconsistencias en el inventario.
- Repetir pruebas después de aplicar una corrección.

**Costos de fallas externas**

- Atender problemas detectados durante el uso por las personas beneficiarias.
- Corregir información comercial incorrecta.
- Recuperar registros perdidos, si ocurre una falla de almacenamiento.
- Corregir productos vendidos que todavía aparezcan disponibles.

La estimación de estos costos deberá actualizarse con las horas reales de trabajo, las pruebas realizadas y los defectos registrados por el equipo.

## 3. Análisis de viabilidad técnica y operativa

### A. Viabilidad técnica

La viabilidad técnica consiste en determinar si las herramientas, los conocimientos y los recursos disponibles permiten desarrollar el sistema con las funcionalidades previstas.

**Gestión de la información:** el sistema deberá registrar, almacenar y consultar los datos correspondientes a los productos, los tiempos de elaboración, los costos, las existencias y las ventas.

**Integridad de los datos:** deberán implementarse validaciones para impedir que se guarden campos obligatorios vacíos, precios o medidas inválidos y cantidades de inventario inconsistentes.

**Cálculo del precio mínimo:** el equipo deberá definir y documentar la fórmula antes de implementarla. Las pruebas deberán utilizar valores conocidos para verificar que el resultado sea correcto.

**Catálogo digital:** la solución deberá mostrar correctamente las fotografías, medidas, precios y disponibilidad de los productos publicados.

**Conectividad:** debido a las condiciones de la región Mixteca, será necesario evaluar cómo se conservarán los registros cuando se interrumpa Internet. La disponibilidad local y la sincronización posterior dependerán de la arquitectura que finalmente seleccione el equipo.

**Usabilidad móvil:** los formularios y las funciones principales deberán ser comprensibles y utilizables desde teléfonos móviles, evitando pasos innecesarios.

**Mantenimiento:** el código, la estructura de datos y la documentación deberán permitir revisar y corregir las funcionalidades sin introducir cambios innecesarios en el resto del sistema.

**Evaluación técnica preliminar:** el proyecto presenta requisitos funcionales definidos y criterios de prueba para las cuatro historias de usuario. Sin embargo, la viabilidad técnica definitiva dependerá de confirmar las tecnologías seleccionadas, los recursos disponibles y la posibilidad de implementar las condiciones de conectividad previstas.

### B. Viabilidad operativa mediante eduScrum

La viabilidad operativa determina si el equipo puede organizar y completar las actividades dentro del periodo académico.

**Organización del trabajo:** las tareas deberán distribuirse entre análisis, diseño, programación, pruebas y documentación, asignando responsables y fechas de entrega.

**Gestión del backlog:** las historias HU01, HU02, HU03 y HU04 deberán priorizarse según su importancia, las dependencias existentes y el tiempo disponible.

**Seguimiento del avance:** el tablero eduScrum deberá mostrar las tareas pendientes, en proceso y terminadas, además de los responsables, las prioridades y las evidencias correspondientes.

**Revisión de entregas:** antes de marcar una historia como terminada, se deberán verificar sus criterios de aceptación y documentar los resultados de las pruebas.

**Gestión de impedimentos:** las dificultades técnicas, los errores de programación y los problemas relacionados con la conectividad deberán registrarse para acordar acciones correctivas.

**Retroalimentación:** las revisiones del Sprint permitirán analizar los resultados, identificar mejoras y ajustar las actividades posteriores.

**Evaluación operativa preliminar:** la viabilidad operativa dependerá de que el equipo establezca una distribución clara de responsabilidades, mantenga actualizado el backlog y disponga de tiempo suficiente para desarrollar y probar las funcionalidades.

## 4. Análisis de viabilidad financiera y dictamen GO/NO-GO

### A. Estructura de costos del proyecto

Para evaluar la viabilidad financiera se deben identificar los recursos necesarios para desarrollar, probar, documentar e implementar el sistema.

| Concepto | Descripción | Costo |
|---|---|---:|
| Análisis y diseño | Revisión de requisitos, historias y diseño de la solución | Por estimar |
| Desarrollo de software | Programación de las cuatro historias de usuario | Por estimar |
| Prevención y evaluación | Revisión de requisitos y ejecución de pruebas | Por estimar |
| Corrección de errores | Reparación de defectos y repetición de pruebas | Por estimar |
| Infraestructura | Alojamiento, almacenamiento y servicios necesarios, si aplican | Por estimar |
| Documentación y capacitación | Manuales y orientación a las personas usuarias, si aplican | Por estimar |
| Implementación | Preparación y puesta en funcionamiento del sistema, si aplica | Por estimar |
| **Costo total del proyecto** | **Suma de los costos aplicables** | **Pendiente de cálculo** |

Los costos del proyecto completo no pueden determinarse únicamente con las horas de calidad. Para calcularlos será necesario estimar el esfuerzo de desarrollo y los recursos que realmente se utilizarán.

### B. Estimación económica del costo de la calidad

El Plan de Calidad del proyecto contempla una estimación inicial de 20 horas: 12 horas de prevención y 8 horas de corrección. También propone un costo académico de referencia de $100 MXN por hora.

Con ese supuesto, el costo estimado de prevención y corrección es de $2,000 MXN. El documento de calidad presenta, además, una estimación total de $3,250 MXN al incluir evaluación y fallas externas. Estas cantidades son estimaciones académicas y no gastos reales.

| Concepto | Horas estimadas | Costo de referencia |
|---|---:|---:|
| Prevención | 12 h | $1,200 MXN |
| Corrección | 8 h | $800 MXN |
| **Prevención y corrección** | **20 h** | **$2,000 MXN** |
| Evaluación y fallas externas | Por validar | Incluidas en la estimación CoQ original |
| **Costo de calidad de referencia** | **Pendiente de conciliación** | **$3,250 MXN, estimación académica** |

Antes de utilizar el total de $3,250 MXN como presupuesto definitivo, el equipo deberá revisar que las horas, las tarifas y los conceptos no estén duplicados. El costo de calidad tampoco debe confundirse con el costo total de desarrollar el sistema.

### C. Posibles mecanismos de financiación

Las siguientes opciones podrán evaluarse según las condiciones del proyecto:

- **Recursos propios:** aportaciones que las personas participantes u organizaciones colaboradoras decidan proporcionar, si corresponde.
- **Apoyo institucional:** disponibilidad de equipos, asesoría, laboratorios o infraestructura proporcionados por la institución educativa.
- **Herramientas gratuitas o de código abierto:** utilización de tecnologías que satisfagan los requisitos sin generar costos de licencia.
- **Programas de apoyo:** revisión de convocatorias relacionadas con la digitalización, la comercialización artesanal y el desarrollo de actividades productivas.

Estas alternativas son posibilidades de análisis y no representan financiamiento confirmado.

### D. Dictamen de viabilidad

| Dimensión | Evaluación preliminar | Justificación |
|---|---|---|
| Técnica | Pendiente de validación | Se deben confirmar las tecnologías, el almacenamiento de datos y el manejo de la conectividad limitada. |
| Operativa | Pendiente de validación | Es necesario confirmar las responsabilidades, el calendario y la capacidad de trabajo del equipo. |
| Financiera | Pendiente de validación | Falta estimar el costo total del desarrollo y confirmar los recursos disponibles. |

**Dictamen preliminar: pendiente de validación.**

El proyecto cuenta con cuatro historias de usuario definidas y un Plan de Calidad que establece criterios, pruebas y métricas. Sin embargo, no es suficiente para emitir una decisión definitiva de viabilidad. El dictamen **GO** deberá establecerse cuando el equipo confirme que puede desarrollar el alcance acordado, completar las pruebas y disponer de los recursos necesarios. Si se identifican impedimentos que no puedan resolverse dentro del periodo o del presupuesto disponible, deberá evaluarse un **NO-GO** o una reducción justificada del alcance.

## 5. Gestión del equipo y gobernanza eduScrum

### A. Organización del equipo

La gestión del proyecto deberá coordinarse mediante eduScrum, manteniendo las responsabilidades y los acuerdos visibles para todos los integrantes.

Las funciones de trabajo deberán incluir:

- **Product Owner:** José Alfredo Román Cruz, de acuerdo con la información registrada en el proyecto. La validación de prioridades y requisitos deberá realizarse conforme a los acuerdos del equipo.
- **Análisis de requisitos:** revisión de las historias de usuario y sus criterios de aceptación.
- **Desarrollo:** implementación de las funcionalidades priorizadas.
- **Pruebas de calidad:** diseño y ejecución de casos de prueba, registro de defectos y comprobación de correcciones.
- **Documentación:** actualización de evidencias, decisiones, resultados y avances.

La asignación nominal de las tareas deberá registrarse en el tablero, de acuerdo con la integración real del equipo.

### B. Seguimiento y control

El equipo deberá:

1. Mantener actualizadas las cuatro historias de usuario y sus criterios de aceptación.
2. Registrar las tareas, sus responsables, prioridades y estados.
3. Documentar las horas de prevención, evaluación y corrección.
4. Registrar los errores detectados y las acciones realizadas para resolverlos.
5. Guardar capturas, resultados de pruebas y demás evidencias.
6. Utilizar GitHub para conservar el historial de cambios y coordinar la documentación, conforme al flujo de trabajo acordado.
7. Revisar periódicamente el avance y los impedimentos.

### C. Criterios de finalización

Una historia de usuario podrá considerarse terminada cuando:

- Cumpla sus criterios de aceptación.
- Haya superado las pruebas previstas para su alcance.
- No presente defectos críticos conocidos que impidan su uso previsto.
- Cuente con evidencias verificables de las pruebas.
- Disponga de la documentación necesaria.
- Haya sido revisada conforme a la Definición de Hecho (DoD) acordada por el equipo.

## 6. Conclusión

El Sistema de apoyo para vendedores de tenates artesanales de palma busca contribuir a mejorar el control de los costos de elaboración, las existencias, las ventas y las características de los productos, además de facilitar la difusión comercial mediante un catálogo digital.

La formulación del objetivo SMART permite establecer resultados específicos y verificables, mientras que la trazabilidad con las historias de usuario relaciona las necesidades de las artesanas y vendedores con las pruebas necesarias para comprobar el funcionamiento del sistema.

El análisis de viabilidad técnica permite identificar los requisitos relacionados con la integridad de la información, el uso desde teléfonos móviles y la conectividad limitada. La viabilidad operativa permite organizar el trabajo mediante eduScrum, y la evaluación financiera establece los elementos necesarios para estimar los recursos y costos del desarrollo.

En conclusión, el proyecto cuenta con una base funcional y un Plan de Calidad que pueden orientar su desarrollo. No obstante, la decisión definitiva de viabilidad deberá sustentarse en la validación de las tecnologías, la planificación del equipo, las pruebas realizadas y el cálculo de los costos reales. De esta manera, será posible determinar si el sistema puede completarse durante el periodo académico y responder a las necesidades de quienes producen y comercializan tenates artesanales en Tlaxiaco, Oaxaca.
