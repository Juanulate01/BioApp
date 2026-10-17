# Proyecto BioApp

**Universidad:** Universidad Técnica Nacional, Sede San Carlos  
**Curso:** ISW-912 — Administración de Proyectos Informáticos  
**Docente:** Deiber Cubero Molina  
**Periodo académico:** III cuatrimestre de 2026  
**Integrantes:** Kristel Ramírez, Juan Daniel Ulate y Krisley Castro  
**Duración del trabajo:** 10 semanas

## Índice

- [00. Project Charter (borrador) y Product Goal](#00-project-charter-borrador-y-product-goal)
  - [00.1. Nombre y descripción del proyecto](#001-nombre-y-descripción-del-proyecto)
  - [00.2. Problemática](#002-problemática)
  - [00.3. Justificación](#003-justificación)
  - [00.4. Objetivo general](#004-objetivo-general)
  - [00.5. Objetivos específicos](#005-objetivos-específicos)
  - [00.6. Alcance y límites generales](#006-alcance-y-límites-generales)
  - [00.7. Entregables previstos](#007-entregables-previstos)
  - [00.8. Condiciones generales de aceptación](#008-condiciones-generales-de-aceptación)
  - [00.9. Product Goal](#009-product-goal)
- [01. Scrum Team](#01-scrum-team)
  - [01.1. Product Owner: Juan Daniel Ulate](#011-product-owner-juan-daniel-ulate)
  - [01.2. Scrum Master y apoyo al desarrollo: Kristel Ramírez](#012-scrum-master-y-apoyo-al-desarrollo-kristel-ramírez)
  - [01.3. Developers: Krisley Castro, Developer 2 y Developer 3](#013-developers-krisley-castro-developer-2-y-developer-3)
  - [01.4. Equipo de trabajo](#014-equipo-de-trabajo)
  - [01.5. Acuerdos de trabajo para las 10 semanas](#015-acuerdos-de-trabajo-para-las-10-semanas)
  - [01.6. Definición de Terminado](#016-definición-de-terminado)
  - [01.7. Comunicación y seguimiento del trabajo](#017-comunicación-y-seguimiento-del-trabajo)
- [02. Contexto organizacional](#02-contexto-organizacional)
  - [02.1. Factores ambientales (EEFs)](#021-factores-ambientales-eefs)
- [03. Mapa de interesados y restricciones](#03-mapa-de-interesados-y-restricciones)
  - [03.1. Mapa de interesados](#031-mapa-de-interesados)
  - [03.2. Restricciones del proyecto](#032-restricciones-del-proyecto)
  - [03.3. Conclusión del análisis](#033-conclusión-del-análisis)
- [04. Ciclo de vida del proyecto y primer Sprint](#04-ciclo-de-vida-del-proyecto-y-primer-sprint)
  - [04.1. Enfoque del ciclo de vida](#041-enfoque-del-ciclo-de-vida)
  - [04.2. Fases del proyecto](#042-fases-del-proyecto)
  - [04.3. Hitos del proyecto](#043-hitos-del-proyecto)
  - [04.4. Ciclo de cada Sprint](#044-ciclo-de-cada-sprint)
  - [04.5. Primer Sprint](#045-primer-sprint)


## 00. Project Charter (borrador) y Product Goal

### 00.1. Nombre y descripción del proyecto

**BioApp** es una aplicación para consultar recetas paso a paso de bioinsumos agrícolas, como insecticidas orgánicos y bioles, y calcular las cantidades necesarias para su aplicación mediante atomización.

El cálculo considerará el área del terreno, el tipo de cultivo, su etapa de desarrollo y las características del equipo utilizado.

### 00.2. Problemática

Las personas productoras que desean utilizar bioinsumos pueden encontrar recetas con instrucciones incompletas o dispersas. Además, calcular cuánto producto y cuánta mezcla preparar para atomizar un terreno requiere considerar diferentes variables del cultivo, del terreno y del equipo de aplicación.

Realizar estos cálculos manualmente puede provocar desperdicio de insumos, mezclas insuficientes o aplicaciones inadecuadas; por ello, se necesita una herramienta que reúna las instrucciones de elaboración y facilite la planificación de cada aplicación.

### 00.3. Justificación

BioApp busca facilitar el acceso a instrucciones claras de elaboración y apoyar el cálculo de las cantidades necesarias para aplicar bioinsumos.

Su desarrollo permitirá integrar en una misma herramienta la consulta de recetas, el registro de cultivos y terrenos, los datos del equipo de atomización y el historial de preparaciones y aplicaciones.

#### ¿Cuál es el valor esperado?

Se espera mejorar la planificación de recursos, reducir errores de cálculo y facilitar la consulta de aplicaciones anteriores.

Para que los resultados sean confiables, las recetas, dosis y reglas de cálculo deberán revisarse con profesionales en agronomía y personas con experiencia en elaboración de bioinsumos antes de incorporarse a la aplicación.

### 00.4. Objetivo general

Desarrollar una aplicación para consultar la elaboración de bioinsumos y calcular las cantidades necesarias para su aplicación mediante atomización, considerando el área del terreno, el tipo y la etapa de desarrollo del cultivo, y las características del equipo utilizado.

### 00.5. Objetivos específicos

1. Organizar un catálogo de bioinsumos que incluya ingredientes, cantidades, pasos de elaboración, forma de uso y recomendaciones de almacenamiento.
2. Permitir el registro de cultivos y terrenos, incluyendo el tipo de cultivo, el área y la etapa de desarrollo.
3. Registrar los datos del equipo de atomización, como la capacidad del tanque y el volumen que aplica por unidad de área.
4. Calcular el volumen total de mezcla, la cantidad de bioinsumo y el número de tanques necesarios para cubrir el terreno indicado.
5. Mostrar los resultados de forma comprensible, detallando los datos utilizados y las cantidades que deben medirse para cada tanque.
6. Guardar un historial de preparaciones y aplicaciones para facilitar la consulta y la planificación posterior.

### 00.6. Alcance y límites generales

#### Funcionalidades incluidas

- Consulta de un catálogo de recetas de bioinsumos con instrucciones de elaboración y uso.
- Registro de terrenos y cultivos con los datos necesarios para realizar los cálculos.
- Registro de las características del equipo de atomización.
- Cálculo del volumen de mezcla, la cantidad de bioinsumo y los tanques necesarios, incluida la preparación de un tanque parcial cuando corresponda.
- Presentación de resultados y cantidades por tanque.
- Consulta del historial de preparaciones y aplicaciones.

#### Límites del proyecto

- La aplicación calculará a partir de dosis y recomendaciones previamente validadas para cada combinación de bioinsumo y cultivo; no generará dosis sin respaldo técnico.
- La edad del cultivo podrá complementar los datos, pero se considerará también su etapa de desarrollo, ya que cultivos de la misma edad pueden requerir aplicaciones distintas.
- Los resultados dependerán de la exactitud de los datos registrados por la persona usuaria y de la calibración del equipo de atomización.
- La aplicación no sustituirá la valoración profesional en agronomía ni realizará diagnósticos automáticos de plagas o enfermedades.
- El alcance del proyecto llegará a una etapa de producción.
- La plataforma, las tecnologías y el presupuesto deberán acordarse durante la planificación.

### 00.7. Entregables previstos

1. Catálogo inicial de recetas revisadas y documentadas.
2. Funcionalidades para registrar cultivos, terrenos y equipos de atomización.
3. Calculadora con resultados totales y cantidades por tanque.
4. Historial de preparaciones y aplicaciones.
5. Documentación del proyecto y evidencia de las pruebas realizadas.

### 00.8. Condiciones generales de aceptación

- Las recetas presentan ingredientes, cantidades y pasos comprensibles, junto con su fuente y versión.
- Los cálculos utilizan reglas revisadas y producen resultados consistentes con casos de referencia validados.
- La aplicación identifica datos obligatorios faltantes o valores inválidos antes de calcular.
- Los resultados muestran las unidades, los datos utilizados y las cantidades necesarias para cada tanque.
- Las funcionalidades implementadas se revisan con el Product Owner.

### 00.9. Product Goal

Al finalizar las 10 semanas, las personas agricultoras podrán consultar recetas de bioinsumos con revisión técnica y calcular, con su propia cuenta, la mezcla, la cantidad de bioinsumo y los tanques necesarios para atomizar sus terrenos, a partir de dosis validadas, y conservar el historial de sus preparaciones y aplicaciones.

El Product Goal orienta la ordenación del Product Backlog y sirve como referencia para definir el objetivo de cada Sprint.

## 01. Scrum Team

El Scrum Team de BioApp estará conformado por cinco integrantes y trabajará durante las 10 semanas del proyecto: un Product Owner, una Scrum Master con apoyo parcial al desarrollo y tres Developers a tiempo completo.

| Integrante | Rol | Nivel | Dedicación | Responsabilidad principal |
| --- | --- | --- | --- | --- |
| Juan Daniel Ulate | Product Owner | - | Parcial | Definir el objetivo del producto, ordenar el Product Backlog y aclarar los requisitos para maximizar el valor de BioApp. |
| Kristel Ramírez | Scrum Master y apoyo al desarrollo | - | Parcial | Facilitar la aplicación de Scrum, ayudar a resolver impedimentos y apoyar en las pruebas, la documentación y el desarrollo cuando su disponibilidad lo permita. |
| Krisley Castro | Developer | Senior | Tiempo completo | Participar en el diseño, desarrollo, pruebas y documentación de los incrementos de la aplicación, y acompañar al Developer junior. |
| Developer 2 (por definir) | Developer | Senior | Tiempo completo | Participar en el diseño, desarrollo, pruebas y documentación de los incrementos de la aplicación, y acompañar al Developer junior. |
| Developer 3 (por definir) | Developer | Junior | Tiempo completo | Participar en el desarrollo, las pruebas y la documentación de los incrementos de la aplicación, con el acompañamiento de los Developers senior. |

### 01.1. Product Owner: Juan Daniel Ulate

Juan Daniel Ulate será responsable de orientar el producto hacia las necesidades de las personas usuarias y mantener claras las prioridades del proyecto.

#### Responsabilidades

- Definir y comunicar el objetivo del producto.
- Crear, mantener y ordenar el Product Backlog.
- Aclarar los requisitos y establecer criterios de aceptación para las funcionalidades.
- Priorizar el catálogo de recetas, los registros de cultivos, terrenos y equipos, la calculadora y el historial de aplicaciones.
- Recoger las necesidades de las personas agricultoras y las observaciones del docente.
- Coordinar la revisión del contenido con profesionales en agronomía y personas con experiencia en elaboración de bioinsumos.
- Revisar los incrementos y ajustar las prioridades según la retroalimentación recibida.
- Gestionar las decisiones sobre alcance para mantener el proyecto viable dentro de las 10 semanas.

### 01.2. Scrum Master y apoyo al desarrollo: Kristel Ramírez

Kristel Ramírez será la Scrum Master del proyecto y apoyará al equipo de desarrollo a tiempo parcial; no se considera desarrolladora a tiempo completo.

#### Responsabilidades como Scrum Master

- Orientar a los integrantes sobre los roles, eventos y artefactos de Scrum.
- Ayudar al equipo a comprender y aplicar Scrum durante el proyecto.
- Facilitar que los eventos se realicen, respeten su duración y cumplan su propósito.
- Promover la autogestión, la colaboración y una comunicación respetuosa.
- Ayudar a identificar y eliminar impedimentos, como requisitos poco claros, dificultades de coordinación o falta de información técnica.
- Apoyar al Product Owner en la gestión clara y efectiva del Product Backlog.
- Facilitar las retrospectivas y dar seguimiento a las acciones de mejora acordadas.

#### Responsabilidades de apoyo al desarrollo

- Apoyar a los Developers en la verificación de los resultados de los cálculos y en las pruebas de los incrementos.
- Colaborar en la documentación de las funcionalidades y de las decisiones técnicas.
- Apoyar en tareas de desarrollo puntuales cuando su disponibilidad lo permita, sin asumir compromisos que pongan en riesgo su rol de Scrum Master.

### 01.3. Developers: Krisley Castro, Developer 2 y Developer 3

Krisley Castro y dos Developers por definir trabajarán a tiempo completo en la construcción de BioApp y colaborarán con el Product Owner y la Scrum Master para entregar incrementos funcionales en cada Sprint.

El equipo de desarrollo estará conformado por dos Developers senior (Krisley Castro y Developer 2) y un Developer junior (Developer 3). Los niveles indican la experiencia de cada persona; de acuerdo con Scrum, dentro del equipo no existen jerarquías y los Developers se organizan por sí mismos para distribuir el trabajo.

Como referencia, se recomienda que los Developers senior asuman los elementos de mayor complejidad y riesgo, como las cuentas de usuario y la separación de datos (PB-11, PB-12), la calculadora (PB-06) y la publicación (PB-16), y que el Developer junior participe en elementos más predecibles, como el registro de equipos (PB-05), la carga de contenido (PB-13, PB-15), la validación de datos (PB-14) y las pruebas, con la revisión de un Developer senior.

#### Responsabilidades

- Participar en la planificación de cada Sprint y definir el trabajo necesario para alcanzar su objetivo.
- Diseñar e implementar las funcionalidades del catálogo, los registros, la calculadora y el historial.
- Colaborar entre sí en la integración de las funcionalidades y revisar el trabajo de los demás.
- Realizar pruebas, corregir errores y verificar la calidad de los incrementos.
- Verificar que los cálculos implementados correspondan con las reglas técnicas revisadas.
- Mantener actualizado el Sprint Backlog y adaptar el plan de trabajo.
- Documentar el funcionamiento y las decisiones técnicas necesarias para mantener la aplicación.
- Comunicar oportunamente las dificultades que puedan afectar el objetivo del Sprint.
- Entregar incrementos utilizables que cumplan la Definición de Terminado.

### 01.4. Equipo de trabajo

Además del Scrum Team, para desarrollar BioApp en 10 semanas se recomienda contar con los siguientes puestos de apoyo y con la conformación de equipo que se resume al final de esta sección.

#### 1. Otros puestos recomendados

| Puesto | Dedicación | Justificación |
| --- | --- | --- |
| QA / Tester | Medio tiempo desde el Sprint 2 y tiempo completo en el Sprint 5 | Verificaría el acceso por cuenta y la separación de datos (PB-11, PB-12), los casos de referencia de los cálculos (PB-06, PB-07), la validación de datos (PB-14) y la validación completa (PB-09). Un error de cálculo puede provocar desperdicio de insumos o aplicaciones inadecuadas. |
| Especialista en agronomía o bioinsumos | Tiempo parcial (4 a 8 horas por semana) | Debe entregar las recetas revisadas a más tardar el 21 de octubre (PB-13) y la tabla de dosis validadas con sus casos de referencia a más tardar el 28 de octubre (PB-15). Sin esta información, PB-03, PB-06, PB-07 y PB-08 no pueden cumplir la Definición de Terminado. |
| Diseñador/a UX/UI | Tiempo parcial durante el Sprint 1 | Responsable del prototipo (PB-02), considerando que las personas usuarias utilizarán la aplicación en el campo. |
| Curador/a de contenido | Tiempo parcial en los Sprints 2 y 3 | Transcripción y carga de las recetas y dosis validadas con su fuente y versión (PB-13 y PB-15). Puede asumirlo el Product Owner o la persona especialista en agronomía. |

Por el tamaño del proyecto, no se consideran necesarios puestos dedicados de DevOps, arquitectura, administración de bases de datos ni gestión de proyectos, ya que estas funciones pueden cubrirse por los Developers, la Scrum Master y el Product Owner.

#### 2. Equipo recomendado

1. Product Owner: Juan Daniel Ulate.
2. Scrum Master con apoyo parcial al desarrollo: Kristel Ramírez.
3. Tres Developers a tiempo completo: dos senior (Krisley Castro y Developer 2) y un junior (Developer 3).
4. Una persona de QA a medio tiempo desde el Sprint 2 y a tiempo completo en el Sprint 5.
5. Especialista en agronomía a tiempo parcial y diseñador/a UX/UI durante el Sprint 1.

### 01.5. Acuerdos de trabajo para las 10 semanas

Como propuesta de organización, el equipo trabajará en **5 Sprints de dos semanas**, ajustando las entregas al calendario.

#### Sprint Planning

Los cinco integrantes participarán en la planificación.

Juan Daniel presentará las prioridades del Product Backlog y aclarará los requisitos, el equipo acordará el objetivo del Sprint y los Developers seleccionarán el trabajo que puedan completar según su capacidad disponible.

#### Daily Scrum

Krisley Castro, Developer 2 y Developer 3 realizarán una reunión diaria de hasta 15 minutos para revisar el avance hacia el objetivo del Sprint y adaptar su plan de trabajo. Kristel participará para facilitar la reunión y dar seguimiento a los impedimentos.

Identificarán dificultades, coordinarán el trabajo técnico y acordarán las siguientes acciones. Cuando necesiten aclaraciones sobre requisitos o prioridades, las consultarán con Juan Daniel.

#### Sprint Review

El equipo presentará el incremento desarrollado y recogerá observaciones para orientar las siguientes decisiones del producto.

Se buscará retroalimentación de personas agricultoras y profesionales en agronomía. Juan Daniel utilizará esta información para actualizar el Product Backlog.

#### Sprint Retrospective

Los cinco integrantes revisarán la colaboración, las dificultades encontradas y las prácticas que funcionaron.

Kristel facilitará la identificación de mejoras concretas en la comunicación, la organización y la calidad del trabajo, y el equipo acordará acciones para aplicar durante el siguiente Sprint.

### 01.6. Definición de Terminado

Una funcionalidad se considerará terminada cuando:

- Cumpla los criterios de aceptación establecidos.
- Esté integrada en la aplicación y pueda utilizarse.
- Haya sido probada y tenga sus errores relevantes corregidos.
- Presente información comprensible y unidades claras cuando corresponda.
- Cuente con la documentación necesaria.
- En el caso de recetas y cálculos, tenga respaldo técnico para el contenido y las reglas utilizadas.

Los Developers serán responsables de verificar que los incrementos cumplan esta definición antes de considerarlos terminados, con el apoyo de Kristel en la revisión de las pruebas.

### 01.7. Comunicación y seguimiento del trabajo

- El equipo mantendrá un tablero de trabajo con las tareas pendientes, en proceso y terminadas.
- Las decisiones relevantes sobre requisitos, cálculos y alcance quedarán documentadas.
- Los impedimentos se comunicarán oportunamente para facilitar su resolución.
- El trabajo se distribuirá según los conocimientos, la disponibilidad y la capacidad de los Developers.
- Las consultas sobre prioridades y requisitos se dirigirán al Product Owner.
- Las mejoras en la forma de trabajo se revisarán durante las retrospectivas.

## 02. Contexto organizacional

BioApp se desarrolla dentro de un entorno en el que existen factores tecnológicos, organizacionales y externos que pueden influir en el proyecto, estos factores no dependen completamente del equipo de desarrollo, pero pueden afectar la construcción, las pruebas y el funcionamiento de la aplicación. Por esta razón, es importante identificarlos desde la planificación.

### 02.1. Factores ambientales (EEFs)

| Factor | Impacto en BioApp |
|---|---|
| **Infraestructura tecnológica disponible** | El desarrollo depende de computadoras, herramientas de programación, bases de datos y servicios necesarios para construir y probar la aplicación. |
| **Conectividad a Internet** | Puede afectar el acceso a herramientas en línea, servicios en la nube y pruebas de funcionamiento de la aplicación. |
| **Compatibilidad con dispositivos** | La aplicación debe considerar que las personas usuarias pueden acceder desde diferentes dispositivos, principalmente teléfonos y computadoras. |
| **Seguridad y protección de datos** | BioApp puede manejar información de usuarios, cultivos, terrenos e historial de aplicaciones, por lo que se deben proteger estos datos. |
| **Normativas aplicables** | Se deberán considerar requisitos relacionados con privacidad, manejo de datos y uso de información agrícola. |
| **Disponibilidad de información confiable** | Las recetas, dosis y reglas de cálculo deben provenir de información previamente validada para evitar resultados incorrectos. |
| **Disponibilidad de usuarios para pruebas** | Se necesita la participación de agricultores y personas relacionadas con bioinsumos para comprobar que la aplicación sea clara y útil. |
| **Tiempo y recursos disponibles** | El proyecto se desarrolla dentro de un periodo de 10 semanas y con recursos limitados. |

## 03. Mapa de interesados y restricciones

Además del contexto, es necesario considerar a los principales interesados que pueden influir en la solución o aportar información necesaria para su desarrollo, así como las restricciones dentro de las cuales se desarrollará el proyecto.

### 03.1. Mapa de interesados

| Interesado | Impacto en BioApp |
|---|---|
| **Personas agricultoras** | Permiten validar si la aplicación responde a necesidades reales y si resulta práctica para sus cultivos y terrenos. |
| **Profesionales en agronomía** | Apoyan en la validación de recetas, dosis y reglas de cálculo antes de incorporarlas a la aplicación. |
| **Personas encargadas de atomizar** | Ayudan a verificar si los cálculos de mezcla y cantidad por tanque son claros y útiles. |
| **Personas con experiencia en bioinsumos** | Pueden revisar ingredientes, pasos de elaboración y recomendaciones de uso. |
| **Equipo de desarrollo** | Se encarga de diseñar, programar, probar y mejorar la aplicación. |
| **Cooperativas o asociaciones agrícolas** | Pueden facilitar el contacto con personas agricultoras y apoyar posibles pruebas de la aplicación. |
| **Autoridades relacionadas con el área agrícola** | Pueden influir si la aplicación llega a utilizarse de manera pública o comercial. |

### 03.2. Restricciones del proyecto

| Restricción | Descripción |
|---|---|
| **Tiempo** | El proyecto tiene una duración fija de 10 semanas, organizadas en 5 Sprints de dos semanas, con entrega final el 7 de diciembre. |
| **Equipo** | El Scrum Team está conformado por cinco integrantes. El desarrollo está a cargo de tres Developers a tiempo completo, dos senior y un junior; la Scrum Master apoya a tiempo parcial. Dos de los Developers aún deben confirmarse. |
| **Validación técnica** | La aplicación solo podrá calcular a partir de recetas y dosis validadas por profesionales en agronomía; no generará dosis sin respaldo técnico. |
| **Alcance** | La aplicación no sustituirá la valoración profesional en agronomía ni realizará diagnósticos automáticos de plagas o enfermedades. |
| **Plataforma, tecnologías y presupuesto** | Aún no están definidos y deberán acordarse durante la planificación. |
| **Protección de datos** | Cada cuenta solo podrá consultar y modificar su propia información, y las contraseñas deberán almacenarse de forma segura. |
| **Exactitud de los datos** | Los resultados dependerán de los datos registrados por la persona usuaria y de la calibración del equipo de atomización. |

### 03.3. Conclusión del análisis

La identificación de estos factores ambientales y de los principales interesados permite comprender mejor el entorno en el que se desarrollará BioApp y las condiciones que pueden influir en el proyecto.

Tener estos elementos claros desde el inicio ayuda a anticipar posibles limitaciones relacionadas con la infraestructura tecnológica, la conectividad, la disponibilidad de recursos, la validación de la información y la participación de las personas usuarias durante las pruebas.

Además, reconocer a los interesados permite identificar quiénes pueden aportar información importante, validar funcionalidades o influir en determinadas decisiones del proyecto. De esta manera, el equipo puede organizar mejor el desarrollo, reducir posibles inconvenientes y mantener la solución enfocada en las necesidades reales de las personas usuarias y en los objetivos definidos para BioApp.

## 04. Ciclo de vida del proyecto y primer Sprint

### 04.1. Enfoque del ciclo de vida

BioApp se desarrollará con un **ciclo de vida adaptativo**, basado en Scrum, de forma **iterativa e incremental**, el proyecto se divide en cinco Sprints de dos semanas, al finalizar cada uno, se obtiene un incremento que se revisa con el Product Owner y cuando sea posible con profesionales en agronomía.

El proyecto mantiene algunos hitos fijos que no dependen del equipo, como la entrega del contenido validado por la persona especialista en agronomía y la fecha de entrega final.

### 04.2. Fases del proyecto

| Fase | Sprints | Periodo | Propósito | Resultados principales |
| --- | --- | --- | --- | --- |
| **Inicio** | Sprint 1 | 30 de septiembre al 13 de octubre | Definir el producto, organizar al equipo y validar la navegación. | Project Charter (borrador), Product Goal, Scrum Team, análisis del contexto, Product Backlog ordenado, Definición de Terminado y prototipo validado. |
| **Construcción** | Sprints 2, 3 y 4 | 14 de octubre al 24 de noviembre | Desarrollar las funcionalidades en incrementos que cumplan la Definición de Terminado. | Cuentas de usuario, catálogo de recetas, registros de terrenos, cultivos y equipos, calculadora, cantidades por tanque e historial. |
| **Validación y cierre** | Sprint 5 | 25 de noviembre al 7 de diciembre | Publicar la aplicación, validarla con personas usuarias y entregar la versión final. | Aplicación en producción, evidencias de pruebas, documentación técnica, guía de uso y presentación. |

#### Cronograma de Sprints

| Sprint | Periodo | Elementos del backlog | Objetivo del Sprint |
| --- | --- | --- | --- |
| 1 | 30 de septiembre al 13 de octubre | PB-01 y PB-02 | Acordar el alcance, ordenar el backlog y validar el prototipo de navegación. |
| 2 | 14 al 27 de octubre | PB-11, PB-12, PB-13 y PB-03 | Permitir el registro e inicio de sesión, conservar los datos por cuenta y consultar el catálogo de recetas revisadas. |
| 3 | 28 de octubre al 10 de noviembre | PB-04, PB-05, PB-15 y PB-06 | Registrar terrenos, cultivos y equipos por usuario y calcular la mezcla total a partir de dosis validadas. |
| 4 | 11 al 24 de noviembre | PB-07, PB-14 y PB-08 | Mostrar las cantidades por tanque, validar los datos antes de calcular y guardar el historial. |
| 5 | 25 de noviembre al 7 de diciembre | PB-16, PB-09 y PB-10 | Publicar la aplicación, validarla con personas usuarias y entregar la versión final. |

### 04.3. Hitos del proyecto

| Fecha | Hito |
| --- | --- |
| 30 de septiembre | Inicio del proyecto y Sprint Planning del Sprint 1. |
| 13 de octubre | Prototipo validado y Product Backlog ordenado. |
| 21 de octubre | Entrega de las recetas revisadas por la persona especialista en agronomía. |
| 28 de octubre | Entrega de la tabla de dosis validadas y de los casos de referencia. |
| 10 de noviembre | Calculadora funcionando con dosis validadas y comprobada con casos de referencia. |
| 24 de noviembre | Funcionalidades del producto completas. |
| 7 de diciembre | Entrega de la versión final y de la documentación. |

### 04.4. Ciclo de cada Sprint

Cada Sprint dura dos semanas, inicia un miércoles y finaliza el martes de la segunda semana.

| Momento | Evento | Duración máxima | Participantes |
| --- | --- | --- | --- |
| Primer día | Sprint Planning | 4 horas | Todo el Scrum Team |
| Cada día hábil | Daily Scrum | 15 minutos | Developers |
| Cada miércoles | Seguimiento semanal del avance | 1 hora | Todo el Scrum Team |
| Último día | Sprint Review | 2 horas | Scrum Team y personas interesadas invitadas |
| Último día, después de la Review | Sprint Retrospective | 1.5 horas | Todo el Scrum Team |

Durante el Sprint, el Product Owner y los Developers revisan y detallan los elementos del Product Backlog de los siguientes Sprints, para que estén listos al momento de la planificación.

### 04.5. Primer Sprint

#### Datos generales

| Aspecto | Detalle |
| --- | --- |
| **Periodo** | 30 de septiembre al 13 de octubre |
| **Seguimiento semanal** | 7 de octubre |
| **Elementos del backlog** | PB-01 Definir requisitos y organizar el proyecto; PB-02 Diseñar y validar el prototipo |

#### Objetivo del Sprint

Acordar el alcance de BioApp, ordenar el Product Backlog y validar un prototipo de navegación comprensible para las personas agricultoras.

#### Eventos del Sprint 1

| Fecha | Evento |
| --- | --- |
| 30 de septiembre | Sprint Planning |
| 7 de octubre | Seguimiento semanal del avance |
| 13 de octubre | Sprint Review y Sprint Retrospective |

#### Incremento esperado

- Project Charter (borrador) y Product Goal documentados.
- Scrum Team, acuerdos de trabajo y Definición de Terminado definidos.
- Contexto organizacional, mapa de interesados y restricciones identificados.
- Product Backlog ordenado, con criterios de aceptación y estimaciones.
- Prototipo de navegación revisado por el Product Owner, con sus observaciones documentadas.

#### Riesgos del Sprint 1

| Riesgo | Acción prevista |
| --- | --- |
| No se defina a tiempo la plataforma ni las tecnologías. | Tomar la decisión antes del cierre del Sprint, ya que el Sprint 2 inicia con el desarrollo de las cuentas de usuario. |
| No se confirme la participación de la persona especialista en agronomía. | Confirmarla antes del 13 de octubre, ya que las recetas validadas se necesitan el 21 de octubre. |


