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
- [05. Product Backlog, Sprint Backlog y mecanismo de seguimiento](#05-product-backlog-sprint-backlog-y-mecanismo-de-seguimiento)
  - [05.1. Product Backlog inicial](#051-product-backlog-inicial)
  - [05.2. Historias de usuario y criterios de aceptación](#052-historias-de-usuario-y-criterios-de-aceptación)


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

## 05. Product Backlog, Sprint Backlog y mecanismo de seguimiento

### 05.1. Product Backlog inicial

El Product Backlog es una lista ordenada: la columna **Orden** indica la prioridad de cada elemento, mientras que el **ID** solo lo identifica, la prioridad se expresa con el método MoSCoW: *Must* (imprescindible), *Should* (importante), *Could* (deseable) y *Won't* (fuera de esta versión).

Los elementos se clasifican en tres tipos:

- **Historia de usuario:** funcionalidad que aporta valor directo a las personas usuarias.
- **Habilitador:** trabajo del equipo necesario para construir, validar o entregar el producto.
- **Contenido:** incorporación de información validada técnicamente, como recetas y dosis.

| Orden | ID | Tipo | Elemento | Prioridad | Estimación (días-persona) | Dependencias | Sprint |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | PB-01 | Habilitador | Definir requisitos y organizar el proyecto | Must | 3 | - | 1 |
| 2 | PB-02 | Habilitador | Diseñar y validar el prototipo | Must | 5 | PB-01 | 1 |
| 3 | PB-11 | Historia de usuario | Registrar una cuenta e iniciar sesión | Must | 4 | PB-02 | 2 |
| 4 | PB-12 | Historia de usuario | Almacenar información vinculada a la cuenta | Must | 5 | PB-11 | 2 |
| 5 | PB-13 | Contenido | Cargar las recetas validadas | Must | 2 | PB-12 | 2 |
| 6 | PB-03 | Historia de usuario | Consultar el catálogo de bioinsumos | Must | 4 | PB-13 | 2 |
| 7 | PB-04 | Historia de usuario | Registrar terrenos y cultivos | Must | 5 | PB-12 | 3 |
| 8 | PB-05 | Historia de usuario | Registrar equipos de atomización | Must | 4 | PB-12 | 3 |
| 9 | PB-15 | Contenido | Cargar las dosis validadas | Must | 1 | PB-13 | 3 |
| 10 | PB-06 | Historia de usuario | Calcular la mezcla y la cantidad de bioinsumo | Must | 5 | PB-04, PB-05, PB-15 | 3 |
| 11 | PB-07 | Historia de usuario | Mostrar cantidades por tanque | Must | 3 | PB-06 | 4 |
| 12 | PB-14 | Historia de usuario | Validar los datos antes de calcular | Must | 2 | PB-06 | 4 |
| 13 | PB-08 | Historia de usuario | Guardar y consultar el historial | Should | 5 | PB-07 | 4 |
| 14 | PB-16 | Habilitador | Publicar la aplicación en producción | Must | 2 | PB-12 | 5 |
| 15 | PB-09 | Habilitador | Validar el funcionamiento completo | Must | 5 | PB-08, PB-16 | 5 |
| 16 | PB-10 | Habilitador | Preparar la versión final y la documentación | Must | 4 | PB-09 | 5 |
| 17 | PB-17 | Historia de usuario | Recuperar la contraseña | Could | 2 | PB-11 | Si hay capacidad |
| 18 | PB-18 | Historia de usuario | Administrar recetas y dosis desde la aplicación | Won't | 4 | PB-13, PB-15 | Fuera de esta versión |
| | | | **Total planificado (PB-01 a PB-16)** | | **59** | | |



### 05.2. Historias de usuario y criterios de aceptación

En esta sección se detallan las historias de usuario y los demás elementos del Product Backlog de BioApp. Cada elemento incluye su descripción, criterios de aceptación, prioridad, estimación, Sprint previsto, dependencias y notas adicionales.

Las estimaciones de esta sección se expresan en puntos de historia, mientras que el Product Backlog inicial utiliza días-persona. Ambas medidas son diferentes.

---

#### PB-01. Definir requisitos y organizar el proyecto

**Título:** Definición de requisitos y organización de BioApp

**Historia de usuario**

Como equipo de BioApp, queremos definir los requisitos, el alcance y los acuerdos de trabajo, para organizar el desarrollo y mantener una planificación viable dentro del tiempo disponible.

**Criterios de aceptación**

1. Dado que se inicia la planificación del proyecto, cuando el equipo define la orientación de BioApp, entonces quedan documentados el objetivo del producto, el Product Goal, el alcance y los límites de esta versión.
2. Dado que se identificaron las necesidades de las personas usuarias, cuando se documentan los requisitos iniciales, entonces se incluyen las cuentas de usuario, el catálogo, los terrenos y cultivos, los equipos, la calculadora y el historial.
3. Dado que existen elementos identificados para desarrollar, cuando el Product Owner organiza el Product Backlog, entonces cada elemento cuenta con un identificador, orden, prioridad, estimación inicial, dependencias y Sprint previsto.
4. Dado que el equipo acuerda cómo construirá y verificará BioApp, cuando finaliza la organización inicial, entonces quedan documentadas las tecnologías seleccionadas y la Definición de Terminado.

**Tipo:** Habilitador  
**Prioridad:** Alta (Must)  
**Estimación propuesta:** 3 puntos  
**Sprint previsto:** 1  
**Dependencias:** Ninguna

**Notas adicionales:** Este elemento es un habilitador. El Product Owner ordena el backlog y los Developers realizan las estimaciones del trabajo de desarrollo. No tiene dependencias previas.

---

#### PB-02. Diseñar y validar el prototipo

**Título:** Prototipo de navegación de BioApp

**Historia de usuario**

Como persona agricultora, quiero contar con una navegación clara entre las pantallas de BioApp, para comprender cómo consultar recetas, registrar mi información y acceder a los cálculos.

**Criterios de aceptación**

1. Dado que los requisitos iniciales están definidos, cuando se elabora el prototipo, entonces se incluyen las pantallas de registro, inicio de sesión, catálogo, terrenos y cultivos, equipos, calculadora e historial.
2. Dado que una persona recorre el prototipo, cuando selecciona las opciones principales, entonces puede identificar cómo avanzar entre las pantallas y regresar a las secciones anteriores.
3. Dado que el prototipo incluye formularios y resultados de cálculo, cuando se revisan sus pantallas, entonces los campos, las unidades de medida y los resultados se presentan de manera comprensible.
4. Dado que el prototipo está disponible para revisión, cuando el Product Owner evalúa los recorridos, entonces se documentan sus observaciones y los ajustes acordados.
5. Dado que se identificaron cambios durante la revisión, cuando se prepara la versión revisada del prototipo, entonces los ajustes acordados quedan incorporados o registrados como pendientes en el backlog.

**Tipo:** Habilitador  
**Prioridad:** Alta (Must)  
**Estimación propuesta:** 5 puntos  
**Sprint previsto:** 1  
**Dependencias:** PB-01

**Notas adicionales:** Depende de PB-01. El prototipo permite revisar la navegación y la presentación de información antes de implementar las funcionalidades.

---

#### PB-11. Registrar una cuenta e iniciar sesión

**Título:** Registro y acceso de usuarios

**Historia de usuario**

Como persona agricultora, quiero crear una cuenta e iniciar sesión en BioApp, para acceder a mi información personal y utilizarla desde distintos dispositivos.

**Criterios de aceptación**

1. Dado que una persona no tiene una cuenta registrada, cuando ingresa un correo válido y una contraseña que cumple los requisitos definidos, entonces el sistema crea la cuenta y permite utilizar esas credenciales para iniciar sesión.
2. Dado que el correo ingresado ya pertenece a una cuenta, cuando se intenta realizar otro registro con ese correo, entonces el sistema impide crear una cuenta duplicada e informa la situación.
3. Dado que existen campos obligatorios vacíos o datos con formato inválido, cuando la persona intenta registrarse, entonces el sistema indica qué información debe corregir y no completa el registro.
4. Dado que la persona tiene una cuenta, cuando ingresa sus credenciales, entonces el sistema permite el acceso si son correctas y lo rechaza si son incorrectas.
5. Dado que el usuario tiene una sesión activa, cuando selecciona cerrar sesión, entonces el sistema finaliza el acceso y solicita autenticación para volver a consultar las secciones privadas.
6. Dado que se registra una contraseña, cuando el sistema la almacena, entonces guarda su hash mediante un mecanismo seguro y no conserva la contraseña en texto plano.

**Tipo:** Historia de usuario  
**Prioridad:** Alta (Must)  
**Estimación propuesta:** 5 puntos  
**Sprint previsto:** 2  
**Dependencias:** PB-02

**Notas adicionales:** Depende de PB-02. La recuperación de contraseña corresponde a PB-17 y se mantiene como funcionalidad opcional si existe capacidad.

---

#### PB-12. Almacenar información vinculada a la cuenta

**Título:** Almacenamiento y acceso a información por usuario

**Historia de usuario**

Como persona agricultora, quiero que mi información permanezca guardada y vinculada a mi cuenta, para consultarla desde distintos dispositivos sin perder mis registros.

**Criterios de aceptación**

1. Dado que el usuario ha iniciado sesión, cuando se guarda un registro personal, entonces la información se almacena en la base de datos centralizada y queda asociada a su cuenta.
2. Dado que existe información guardada en una cuenta, cuando el usuario cierra sesión y vuelve a ingresar con esa misma cuenta, entonces los registros continúan disponibles.
3. Dado que el usuario tiene registros almacenados, cuando inicia sesión con la misma cuenta desde otro dispositivo con conexión a Internet, entonces puede consultar la misma información.
4. Dado que un registro pertenece a una cuenta, cuando otra cuenta intenta consultarlo o modificarlo, entonces el sistema rechaza el acceso y conserva la información sin cambios.
5. Dado que una persona no tiene una sesión activa, cuando intenta acceder a información privada, entonces el sistema impide la consulta y solicita iniciar sesión.

**Tipo:** Historia de usuario  
**Prioridad:** Alta (Must)  
**Estimación propuesta:** 8 puntos  
**Sprint previsto:** 2  
**Dependencias:** PB-11

**Notas adicionales:** Depende de PB-11. Durante el Sprint 2, la persistencia y los controles de acceso pueden comprobarse con registros de prueba en el entorno de pruebas. Posteriormente, esta estructura se utilizará para los terrenos y cultivos de PB-04, los equipos de PB-05 y el historial de PB-08. Así, este elemento puede verificarse sin adelantar el registro de terrenos previsto para el Sprint 3.

---

#### PB-13. Cargar las recetas validadas

**Título:** Incorporación de recetas con revisión técnica

**Historia de usuario**

Como Product Owner, quiero que las recetas revisadas técnicamente queden incorporadas en BioApp, para ofrecer un catálogo con información documentada y respaldada.

**Criterios de aceptación**

1. Dado que las recetas requieren revisión técnica, cuando se coordina su entrega con la persona especialista en agronomía, entonces se establece el 21 de octubre como fecha límite y se registra la recepción del material revisado.
2. Dado que se recibe una receta revisada, cuando se verifica su información, entonces contiene ingredientes, cantidades, pasos de elaboración, forma de uso, recomendaciones de almacenamiento, fuente, versión, fecha de revisión y responsable de la revisión.
3. Dado que una receta cuenta con toda la información y la revisión requeridas, cuando se realiza la carga, entonces queda almacenada en la base de datos y disponible para su consulta mediante PB-03.
4. Dado que una receta tiene información incompleta o no cuenta con revisión técnica documentada, cuando se evalúa su incorporación, entonces queda pendiente de corrección y no se incluye como receta validada.
5. Dado que finaliza la carga de las recetas, cuando se compara la información almacenada con el material recibido, entonces los ingredientes, cantidades e instrucciones coinciden con la versión revisada.

**Tipo:** Contenido  
**Prioridad:** Alta (Must)  
**Estimación propuesta:** 3 puntos  
**Sprint previsto:** 2  
**Dependencias:** PB-12

**Notas adicionales:** Este elemento corresponde a contenido y depende de PB-12, según la planificación inicial. El Product Owner coordina la recepción y comprueba la integridad del material; los Developers realizan la carga técnica. No requiere un panel de administración, ya que esa funcionalidad pertenece a PB-18 y está fuera de esta versión.

---

#### PB-03. Consultar el catálogo de bioinsumos

**Título:** Consulta de recetas de bioinsumos

**Historia de usuario**

Como persona agricultora, quiero consultar un catálogo de recetas de bioinsumos, para conocer los ingredientes, las cantidades y los pasos necesarios para elaborarlos correctamente.

**Criterios de aceptación**

1. Dado que el usuario ingresa al catálogo de bioinsumos, cuando consulta las recetas disponibles, entonces el sistema muestra un listado y permite seleccionar una receta para ver su información.
2. Dado que el usuario selecciona una receta, cuando abre su información, entonces el sistema muestra los ingredientes, cantidades, pasos de elaboración, forma de uso y recomendaciones de almacenamiento.
3. Dado que el usuario consulta una receta, cuando revisa su información, entonces puede visualizar la fuente y versión del contenido, el cual debe contar con una revisión técnica documentada.

**Tipo:** Historia de usuario  
**Prioridad:** Alta (Must)  
**Estimación propuesta:** 5 puntos  
**Sprint previsto:** 2  
**Dependencias:** PB-13

**Notas adicionales:** Las recetas deben haber sido revisadas técnicamente antes de incorporarse al catálogo. Esta historia depende de PB-13, que corresponde a la carga de recetas validadas.

---

#### PB-04. Registrar terrenos y cultivos

**Título:** Registro de terrenos y cultivos

**Historia de usuario**

Como persona agricultora, quiero registrar la información de mis terrenos y cultivos, para tener sus características guardadas y utilizarlas al calcular la cantidad de mezcla necesaria para atomizar.

**Criterios de aceptación**

1. Dado que el usuario ha iniciado sesión, cuando registra un terreno y su cultivo, entonces el sistema guarda la información y permite consultarla, modificarla o eliminarla, solicitando confirmación antes de eliminar.
2. Dado que el usuario está registrando un terreno, cuando ingresa sus características, entonces el sistema permite indicar el área, la unidad de medida, el tipo de cultivo y su etapa de desarrollo, según las etapas validadas para ese cultivo.
3. Dado que el usuario ingresa el área del terreno, cuando selecciona la unidad de medida, entonces el sistema permite utilizar metros cuadrados, hectáreas o manzanas y realiza las conversiones correspondientes, considerando que una manzana equivale a 6 987 m².
4. Dado que el usuario deja campos obligatorios vacíos o ingresa un área igual o menor que cero, cuando intenta guardar el registro, entonces el sistema muestra un mensaje indicando qué información debe corregir.

**Tipo:** Historia de usuario  
**Prioridad:** Alta (Must)  
**Estimación propuesta:** 8 puntos  
**Sprint previsto:** 3  
**Dependencias:** PB-12

**Notas adicionales:** Las conversiones de unidades deben comprobarse con casos de referencia. Los registros deben permanecer asociados a la cuenta del usuario.

---

#### PB-05. Registrar equipos de atomización

**Título:** Registro de equipos de atomización

**Historia de usuario**

Como persona encargada de atomizar, quiero registrar las características de los equipos de atomización, para utilizar esa información al calcular la mezcla necesaria para aplicar en un terreno.

**Criterios de aceptación**

1. Dado que el usuario ha iniciado sesión, cuando registra un equipo de atomización, entonces el sistema guarda la información y permite consultarla, modificarla o eliminarla, solicitando confirmación antes de eliminar.
2. Dado que el usuario está registrando un equipo, cuando ingresa sus características, entonces el sistema permite indicar la capacidad del tanque y el volumen que aplica por unidad de área, junto con sus respectivas unidades de medida.
3. Dado que el usuario ingresa una capacidad o un volumen igual o menor que cero, cuando intenta guardar el equipo, entonces el sistema le indica que debe corregir el valor.
4. Dado que el usuario tiene equipos registrados, cuando inicia sesión desde otro dispositivo, entonces puede consultar la información de sus equipos guardados.

**Tipo:** Historia de usuario  
**Prioridad:** Alta (Must)  
**Estimación propuesta:** 5 puntos  
**Sprint previsto:** 3  
**Dependencias:** PB-12

**Notas adicionales:** Los datos registrados deben utilizarse posteriormente en la calculadora de BioApp. Los equipos deben quedar vinculados a la cuenta del usuario.

---

#### PB-15. Cargar las dosis validadas

**Título:** Registro de dosis validadas

**Historia de usuario**

Como Product Owner, quiero incorporar las dosis validadas de los bioinsumos según el cultivo y su etapa de desarrollo, para que la calculadora utilice únicamente recomendaciones que cuenten con respaldo técnico.

**Criterios de aceptación**

1. Dado que la persona especialista en agronomía debe revisar las dosis de los bioinsumos, cuando finaliza la validación, entonces entrega la tabla de dosis revisadas a más tardar el 28 de octubre.
2. Dado que se reciben las dosis validadas, cuando se incorporan a la base de datos, entonces cada dosis queda asociada al bioinsumo, cultivo y etapa correspondiente, junto con su fuente, versión y responsable de la revisión.
3. Dado que las dosis están disponibles, cuando se preparan las pruebas de la calculadora, entonces se cuenta con casos de referencia que incluyen los datos de entrada y los resultados esperados para comprobar los cálculos.

**Tipo:** Contenido  
**Prioridad:** Alta (Must)  
**Estimación propuesta:** 3 puntos  
**Sprint previsto:** 3  
**Dependencias:** PB-13

**Notas adicionales:** Esta actividad depende de contar con las recetas y la información técnica revisadas. No se deben incorporar dosis que no hayan sido validadas por una persona especialista en agronomía.

---

#### PB-06. Calcular la mezcla y la cantidad de bioinsumo

**Título:** Cálculo bioinsumo

**Historia de usuario**

Como persona agricultora, quiero calcular la cantidad de bioinsumos necesarios según el terreno, el equipo de aplicación, el cultivo y su etapa, para preparar la dosis adecuada para cubrir el terreno seleccionado.

**Criterios de aceptación**

1. Dado que el usuario selecciona un terreno, un equipo, un bioinsumo, un cultivo y una etapa con una dosis validada, cuando solicita el cálculo, entonces el sistema muestra el volumen total de mezcla y la cantidad de bioinsumo necesaria para cubrir el terreno.
2. Dado que la combinación seleccionada no cuenta con una dosis validada, cuando el usuario intenta realizar el cálculo, entonces el sistema muestra un aviso indicando que no es posible calcular la cantidad para esa combinación.
3. Dado que el usuario no completa la información necesaria, cuando intenta calcular, entonces el sistema indica qué dato debe ingresar para continuar.

**Tipo:** Historia de usuario  
**Prioridad:** Alta (Must)  
**Estimación propuesta:** 5 puntos  
**Sprint previsto:** 3  
**Dependencias:** PB-04, PB-05, PB-15

**Notas adicionales:** Los casos de referencia para validar los cálculos deben quedar definidos y automatizados como pruebas durante el Sprint.

---

#### PB-07. Mostrar cantidades por tanque

**Título:** Cantidades de preparación por tanque

**Historia de usuario**

Como persona encargada de atomizar, quiero conocer cuántos tanques debo preparar y qué cantidades de bioinsumo y agua necesito en cada uno, para realizar la preparación sin confusiones y utilizar las cantidades correctas.

**Criterios de aceptación**

1. Dado que el usuario realiza un cálculo de mezcla, cuando obtiene el resultado, entonces el sistema muestra la cantidad de tanques completos que necesita preparar y si debe preparar un tanque parcial.
2. Dado que el usuario consulta el resultado por tanque, cuando revisa las cantidades, entonces el sistema muestra cuánto bioinsumo y agua debe utilizar en cada tanque.
3. Dado que el sistema presenta las cantidades necesarias, cuando muestra los resultados, entonces expresa el bioinsumo en mililitros o gramos enteros y el agua en litros con un decimal, indicando también los datos utilizados para el cálculo.
4. Dado que el cálculo requiere varios tanques, cuando se suman las cantidades de mezcla de los tanques completos y del tanque parcial, entonces el resultado coincide con el volumen total calculado, considerando únicamente la diferencia permitida por el redondeo.

**Tipo:** Historia de usuario  
**Prioridad:** Alta (Must)  
**Estimación propuesta:** 5 puntos  
**Sprint previsto:** 4  
**Dependencias:** PB-06

**Notas adicionales:** Esta historia depende de PB-06, porque primero debe funcionar el cálculo de la mezcla total. También deben verificarse los resultados cuando se necesita preparar un tanque parcial.

---

#### PB-14. Validar los datos antes de calcular

**Título:** Validación de datos para el cálculo

**Historia de usuario**

Como persona agricultora, quiero recibir mensajes claros cuando falten datos, haya información incorrecta o no exista una dosis validada, para saber qué debo corregir o cuándo consultar a un profesional en agronomía.

**Criterios de aceptación**

1. Dado que el usuario dejó sin completar un dato necesario, cuando intenta realizar el cálculo, entonces el sistema le indica qué dato le hace falta por ingresar.
2. Dado que el usuario ingresa un valor inválido, fuera de rango o con unidades incompatibles, cuando intenta realizar el cálculo, entonces el sistema le indica qué dato debe corregir y no realiza el cálculo.
3. Dado que no existe una dosis validada para la combinación seleccionada, cuando el usuario intenta calcular, entonces el sistema le explica que no puede realizar el cálculo porque falta una dosis validada y le recomienda consultar a un profesional en agronomía.

**Tipo:** Historia de usuario  
**Prioridad:** Alta (Must)  
**Estimación propuesta:** 5 puntos  
**Sprint previsto:** 4  
**Dependencias:** PB-06

**Notas adicionales:** Cada criterio de validación debe contar con pruebas que comprueben que el sistema responde correctamente.

---

#### PB-08. Guardar y consultar el historial

**Título:** Historial de preparaciones y aplicaciones

**Historia de usuario**

Como persona agricultora, quiero guardar y consultar mis preparaciones y aplicaciones anteriores, para llevar un registro y usarlo como apoyo al planificar futuras labores.

**Criterios de aceptación**

1. Dado que el usuario realiza un cálculo, cuando obtiene el resultado, entonces el sistema guarda la preparación con la fecha, el terreno, el cultivo, el bioinsumo, el equipo y las cantidades utilizadas.
2. Dado que una preparación está guardada, cuando el usuario la marca como una aplicación realizada e indica la fecha, entonces el sistema la registra como aplicación y muestra claramente ese estado en el historial.
3. Dado que el usuario consulta su historial desde un dispositivo, cuando inicia sesión con su cuenta desde otro dispositivo, entonces puede consultar los mismos registros.
4. Dado que existen registros guardados, cuando el usuario consulta el historial, entonces puede distinguir cuáles son preparaciones y cuáles son aplicaciones realizadas.

**Tipo:** Historia de usuario  
**Prioridad:** Media (Should)  
**Estimación propuesta:** 8 puntos  
**Sprint previsto:** 4  
**Dependencias:** PB-07

**Notas adicionales:** La estimación considera que el historial debe guardarse en la cuenta del usuario y estar disponible desde distintos dispositivos.

---

#### PB-16. Publicar la aplicación en producción

**Título:** Publicación de BioApp para su uso

**Historia de usuario**

Como persona agricultora, quiero acceder a BioApp por Internet desde mi teléfono o computadora, para consultar y utilizar la aplicación desde mis dispositivos.

**Criterios de aceptación**

1. Dado que BioApp está publicada, cuando una persona usuaria ingresa desde Internet, entonces puede acceder de forma segura mediante HTTPS.
2. Dado que la aplicación se encuentra en producción, cuando se comprueba la configuración del entorno, entonces se verifica que la base de datos de producción está separada de la base de pruebas y cuenta con un respaldo.
3. Dado que BioApp está publicada, cuando la persona usuaria consulta el contenido, entonces encuentra cargadas las recetas y las dosis validadas.
4. Dado que la persona usuaria accede desde un teléfono o una computadora, entonces puede ingresar y utilizar BioApp correctamente desde ambos dispositivos.

**Tipo:** Habilitador  
**Prioridad:** Alta (Must)  
**Estimación propuesta:** 8 puntos  
**Sprint previsto:** 5  
**Dependencias:** PB-12

**Notas adicionales:** La estimación es alta porque la historia incluye preparar la publicación, cargar el contenido y comprobar el acceso desde distintos dispositivos.

---

#### PB-09. Validar el funcionamiento completo

**Título:** Validación del funcionamiento de BioApp

**Historia de usuario**

Como equipo de desarrollo, queremos comprobar que BioApp sea fácil de entender y que sus funciones, cálculos y controles de acceso funcionen correctamente, para ofrecer una aplicación confiable a las personas usuarias.

**Criterios de aceptación**

1. Dado que BioApp está disponible en producción, cuando las personas usuarias realizan el recorrido completo, entonces se comprueba que pueden entender y utilizar la aplicación.
2. Dado que se ingresan los datos de los casos de referencia, cuando se repiten los cálculos, entonces los resultados coinciden con los valores esperados.
3. Dado que se realizan pruebas con distintas cuentas, cuando cada persona consulta sus datos, entonces solo puede ver la información correspondiente a su cuenta.
4. Dado que una funcionalidad se completa durante un Sprint, cuando se verifica según la Definición de Terminado, entonces cumple las pruebas establecidas para ese Sprint.
5. Dado que durante las pruebas se encuentra un problema, cuando se registra, entonces queda documentado y los errores relevantes se corrigen y se vuelven a probar.

**Tipo:** Habilitador  
**Prioridad:** Alta (Must)  
**Estimación propuesta:** 8 puntos  
**Sprint previsto:** 5  
**Dependencias:** PB-08, PB-16

**Notas adicionales:** Como esta historia incluye pruebas de cada Sprint y una validación completa en producción, el equipo podría dividirla en historias más pequeñas si resulta demasiado amplia para estimarla o completarla en un Sprint.

---

#### PB-10. Preparar la versión final y la documentación

**Título:** Versión final y documentación de BioApp

**Historia de usuario**

Como equipo de BioApp, queremos integrar y documentar la versión final de la aplicación, para entregar un producto completo, revisado y listo para presentar.

**Criterios de aceptación**

1. Dado que se prepara la versión final, cuando se revisan las funcionalidades comprometidas, entonces todas cumplen la Definición de Terminado.
2. Dado que se prepara la entrega, cuando se revisa la documentación, entonces están completas la guía de uso, la documentación técnica, las evidencias de las pruebas y la presentación.
3. Dado que la aplicación está lista para entregarse, cuando el Product Owner revisa la versión final antes del 7 de diciembre, entonces puede confirmar si está preparada para la entrega.

**Tipo:** Habilitador  
**Prioridad:** Alta (Must)  
**Estimación propuesta:** 8 puntos  
**Sprint previsto:** 5  
**Dependencias:** PB-09

---

#### PB-17. Recuperar la contraseña

**Título:** Recuperación de contraseña

**Historia de usuario**

Como persona agricultora, quiero restablecer mi contraseña si la olvido, para recuperar el acceso a mi cuenta y a mi información.

**Criterios de aceptación**

1. Dado que el usuario tiene una cuenta registrada, cuando solicita restablecer su contraseña, entonces el sistema envía un enlace al correo asociado con esa cuenta.
2. Dado que el usuario recibe el enlace, cuando intenta usarlo después de que venció, entonces el sistema no permite cambiar la contraseña con ese enlace.
3. Dado que el enlace aún está vigente, cuando el usuario ingresa una nueva contraseña, entonces el sistema la actualiza y le permite utilizarla para iniciar sesión.

**Tipo:** Historia de usuario  
**Prioridad:** Could (Opcional)  
**Estimación propuesta:** 5 puntos  
**Sprint previsto:** Si hay capacidad  
**Dependencias:** PB-11

**Notas adicionales:** La nueva contraseña debe guardarse de forma segura mediante un hash en la base de datos. También conviene definir cuánto tiempo estará vigente el enlace.

---

#### PB-18. Administrar recetas y dosis desde la aplicación

**Título:** Administración de recetas y dosis validadas

**Historia de usuario**

Como Product Owner, quiero crear y actualizar recetas y dosis validadas desde BioApp, para mantener la información al día sin modificar directamente la base de datos.

**Criterios de aceptación**

1. Dado que el Product Owner tiene acceso autorizado, cuando crea o actualiza una receta o una dosis, entonces puede registrar la fuente de la información, su versión y quién realizó la revisión técnica.
2. Dado que una cuenta no está autorizada para administrar recetas y dosis, cuando intenta acceder a esa función, entonces el sistema le impide hacerlo.
3. Dado que una receta o dosis fue actualizada, cuando se guarda el cambio, entonces la información queda registrada en BioApp.

**Tipo:** Historia de usuario  
**Prioridad (MoSCoW):** Won't (Fuera de esta versión)  
**Estimación propuesta:** 5 puntos  
**Sprint previsto:** Fuera de esta versión  
**Dependencias:** PB-13, PB-15

**Notas adicionales:** Conviene definir cuáles cuentas estarán autorizadas para administrar esta información.
