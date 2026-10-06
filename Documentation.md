# Proyecto BioApp

**Universidad:** Universidad Técnica Nacional, Sede San Carlos  
**Curso:** ISW-912 — Administración de Proyectos Informáticos  
**Docente:** Deiber Cubero Molina  
**Periodo académico:** III cuatrimestre de 2026  
**Integrantes:** Kristel Ramírez, Juan Daniel Ulate y Krisley Castro  
**Duración del trabajo:** 14 semanas

  ## Índice

1. [Project Charter](#1-acta-de-inicio-del-proyecto-project-charter)
   - [1.1. Nombre y descripción del proyecto](#11-nombre-y-descripción-del-proyecto)
   - [1.2. Problemática](#12-problemática)
   - [1.3. Justificación y valor esperado](#13-justificación-y-valor-esperado)
   - [1.4. Objetivo general](#14-objetivo-general)
   - [1.5. Objetivos específicos](#15-objetivos-específicos)
   - [1.6. Alcance y límites generales](#16-alcance-y-límites-generales)
     - [Funcionalidades incluidas](#funcionalidades-incluidas)
     - [Límites del proyecto](#límites-del-proyecto)
   - [1.7. Entregables previstos](#17-entregables-previstos)
   - [1.8. Condiciones generales de aceptación](#18-condiciones-generales-de-aceptación)  
   
2. [Definición del Scrum Team](#2-definición-del-scrum-team)
   - [2.1. Product Owner: Juan Daniel Ulate](#21-product-owner-juan-daniel-ulate)
   - [2.2. Scrum Master y Developer: Kristel Ramírez](#22-scrum-master-y-developer-kristel-ramírez)
     - [Responsabilidades como Scrum Master](#responsabilidades-como-scrum-master)
     - [Responsabilidades como Developer](#responsabilidades-como-developer)
   - [2.3. Developer: Krisley Castro](#23-developer-krisley-castro)
   - [2.4. Acuerdos de trabajo para las 14 semanas](#24-acuerdos-de-trabajo-para-las-14-semanas)
     - [Sprint Planning](#sprint-planning)
     - [Daily Scrum](#daily-scrum)
     - [Sprint Review](#sprint-review)
     - [Sprint Retrospective](#sprint-retrospective)
   - [2.5. Definición de Terminado](#25-definición-de-terminado)
   - [2.6. Comunicación y seguimiento del trabajo](#26-comunicación-y-seguimiento-del-trabajo)

3. [Análisis de Entorno](#3-análisis-de-entorno)
   - [3.1. Factores ambientales (EEFs)](#31-factores-ambientales-eefs)
   - [3.2. Stakeholder del proyecto](#32-interesados-del-proyecto)
   - [3.3. Conclusión del análisis](#33-conclusión-del-análisis)


## 1. Project Charter

### 1.1. Nombre y descripción del proyecto

**BioApp** es una aplicación para consultar recetas paso a paso de bioinsumos agrícolas, como insecticidas orgánicos y bioles y calcular las cantidades necesarias para su aplicación mediante atomización.

El cálculo considerará el área del terreno, el tipo de cultivo, su etapa de desarrollo y las características del equipo utilizado.

### 1.2. Problemática

Las personas productoras que desean utilizar bioinsumos pueden encontrar recetas con instrucciones incompletas o dispersas. Además, calcular cuánto producto y cuánta mezcla preparar para atomizar un terreno requiere considerar diferentes variables del cultivo, del terreno y del equipo de aplicación.

Realizar estos cálculos manualmente puede provocar desperdicio de insumos, mezclas insuficientes o aplicaciones inadecuadas, por ello, se necesita una herramienta que reúna las instrucciones de elaboración y facilite la planificación de cada aplicación.

### 1.3. Justificación 

BioApp busca facilitar el acceso a instrucciones claras de elaboración y apoyar el cálculo de las cantidades necesarias para aplicar bioinsumos.

Su desarrollo permitirá integrar en una misma herramienta la consulta de recetas, el registro de cultivos y terrenos, los datos del equipo de atomización y el historial de preparaciones y aplicaciones.

##### ¿Cúal es el valor esperado?

Se espera mejorar la planificación de recursos, reducir errores de cálculo y facilitar la consulta de aplicaciones anteriores.

Para que los resultados sean confiables, las recetas, dosis y reglas de cálculo deberán revisarse con profesionales en agronomía y personas con experiencia en elaboración de bioinsumos antes de incorporarse a la aplicación.

### 1.4. Objetivo general

Desarrollar una aplicación para consultar la elaboración de bioinsumos y calcular las cantidades necesarias para su aplicación mediante atomización, considerando el área del terreno, el tipo y la etapa de desarrollo del cultivo, y las características del equipo utilizado.

### 1.5. Objetivos específicos

1. Organizar un catálogo de bioinsumos que incluya ingredientes, cantidades, pasos de elaboración, forma de uso y recomendaciones de almacenamiento.
2. Permitir el registro de cultivos y terrenos, incluyendo el tipo de cultivo, el área y la etapa de desarrollo.
3. Registrar los datos del equipo de atomización, como la capacidad del tanque y el volumen que aplica por unidad de área.
4. Calcular el volumen total de mezcla, la cantidad de bioinsumo y el número de tanques necesarios para cubrir el terreno indicado.
5. Mostrar los resultados de forma comprensible, detallando los datos utilizados y las cantidades que deben medirse para cada tanque.
6. Guardar un historial de preparaciones y aplicaciones para facilitar la consulta y la planificación posterior.

### 1.6. Alcance y límites generales

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
- El alcance corresponde al desarrollo académico durante 14 semanas. Una eventual publicación para uso real o comercial requerirá una revisión adicional de los requisitos aplicables.
- La plataforma, las tecnologías y el presupuesto deberán acordarse durante la planificación, pues no están definidos en el material base.

### 1.7. Entregables previstos

1. Catálogo inicial de recetas revisadas y documentadas.
2. Funcionalidades para registrar cultivos, terrenos y equipos de atomización.
3. Calculadora con resultados totales y cantidades por tanque.
4. Historial de preparaciones y aplicaciones.
5. Documentación del proyecto y evidencia de las pruebas realizadas.

### 1.8. Condiciones generales de aceptación

- Las recetas presentan ingredientes, cantidades y pasos comprensibles, junto con su fuente y versión.
- Los cálculos utilizan reglas revisadas y producen resultados consistentes con casos de referencia validados.
- La aplicación identifica datos obligatorios faltantes o valores inválidos antes de calcular.
- Los resultados muestran las unidades, los datos utilizados y las cantidades necesarias para cada tanque.
- Las funcionalidades implementadas se revisan con el Product Owner y se presentan al docente según los criterios de las entregas académicas.

## 2. Definición del Scrum Team

El Scrum Team de BioApp estará conformado por tres integrantes y trabajará durante las 14 semanas del proyecto.

| Integrante | Rol | Responsabilidad principal |
| --- | --- | --- |
| Juan Daniel Ulate | Product Owner | Definir el objetivo del producto, ordenar el Product Backlog y aclarar los requisitos para maximizar el valor de BioApp. |
| Kristel Ramírez | Scrum Master y Developer | Facilitar la aplicación de Scrum, ayudar a resolver impedimentos y participar en el desarrollo, las pruebas y la documentación. |
| Krisley Castro | Developer | Participar en el diseño, desarrollo, pruebas y documentación de los incrementos de la aplicación. |

### 2.1. Product Owner: Juan Daniel Ulate

Juan Daniel Ulate será responsable de orientar el producto hacia las necesidades de las personas usuarias y mantener claras las prioridades del proyecto.

#### Responsabilidades

- Definir y comunicar el objetivo del producto.
- Crear, mantener y ordenar el Product Backlog.
- Aclarar los requisitos y establecer criterios de aceptación para las funcionalidades.
- Priorizar el catálogo de recetas, los registros de cultivos, terrenos y equipos, la calculadora y el historial de aplicaciones.
- Recoger las necesidades de las personas agricultoras y las observaciones del docente.
- Coordinar la revisión del contenido con profesionales en agronomía y personas con experiencia en elaboración de bioinsumos.
- Revisar los incrementos y ajustar las prioridades según la retroalimentación recibida.
- Gestionar las decisiones sobre alcance para mantener el proyecto viable dentro de las 14 semanas.

### 2.2. Scrum Master y Developer: Kristel Ramírez

Kristel Ramírez combinará las responsabilidades de Scrum Master con la participación técnica cuando sea requerida durante el desarrollo de BioApp.

#### Responsabilidades como Scrum Master

- Orientar a los integrantes sobre los roles, eventos y artefactos de Scrum.
- Ayudar al equipo a comprender y aplicar Scrum durante el proyecto.
- Facilitar que los eventos se realicen, respeten su duración y cumplan su propósito.
- Promover la autogestión, la colaboración y una comunicación respetuosa.
- Ayudar a identificar y eliminar impedimentos, como requisitos poco claros, dificultades de coordinación o falta de información técnica.
- Apoyar al Product Owner en la gestión clara y efectiva del Product Backlog.
- Facilitar las retrospectivas y dar seguimiento a las acciones de mejora acordadas.

#### Responsabilidades como Developer

- Participar junto con Krisley Castro en la planificación del trabajo de cada Sprint.
- Diseñar e implementar las funcionalidades priorizadas.
- Realizar pruebas, corregir errores y verificar los resultados de los cálculos.
- Mantener actualizado el Sprint Backlog y adaptar el plan de trabajo.
- Documentar las funcionalidades y las decisiones técnicas.


### 2.3. Developer: Krisley Castro

Krisley Castro participará en la construcción de BioApp y colaborará con Kristel Ramírez para entregar incrementos funcionales en cada Sprint.

#### Responsabilidades

- Participar en la planificación de cada Sprint y definir el trabajo necesario para alcanzar su objetivo.
- Diseñar e implementar las funcionalidades del catálogo, los registros, la calculadora y el historial.
- Colaborar con Kristel en la integración de las funcionalidades.
- Realizar pruebas, corregir errores y verificar la calidad de los incrementos.
- Verificar que los cálculos implementados correspondan con las reglas técnicas revisadas.
- Mantener actualizado el Sprint Backlog y adaptar el plan de trabajo.
- Documentar el funcionamiento y las decisiones técnicas necesarias para mantener la aplicación.
- Comunicar oportunamente las dificultades que puedan afectar el objetivo del Sprint.
- Entregar incrementos utilizables que cumplan la Definición de Terminado.

### 2.4. Acuerdos de trabajo para las 14 semanas

Como propuesta de organización, el equipo trabajará en **siete Sprints de dos semanas**, ajustando las entregas al calendario del curso.

#### Sprint Planning

Los tres integrantes participarán en la planificación.

Juan Daniel presentará las prioridades del Product Backlog y aclarará los requisitos, el equipo acordará el objetivo del Sprint,  Kristel y Krisley seleccionarán el trabajo que puedan completar según su capacidad disponible.


#### Daily Scrum

Kristel y Krisley realizarán una reunión diaria de hasta 15 minutos para revisar el avance hacia el objetivo del Sprint y adaptar su plan de trabajo.

Identificarán dificultades, coordinarán el trabajo técnico y acordarán las siguientes acciones, cuando necesiten aclaraciones sobre requisitos o prioridades, las consultarán con Juan Daniel.

#### Sprint Review

El equipo presentará el incremento desarrollado y recogerá observaciones para orientar las siguientes decisiones del producto.

Se buscará retroalimentación de personas agricultoras y profesionales en agronomía. Juan Daniel utilizará esta información para actualizar el Product Backlog.

#### Sprint Retrospective

Los tres integrantes revisarán la colaboración, las dificultades encontradas y las prácticas que funcionaron.

Kristel facilitará la identificación de mejoras concretas en la comunicación, la organización y la calidad del trabajo, el equipo acordará acciones para aplicar durante el siguiente Sprint.


### 2.5. Definición de Terminado

Una funcionalidad se considerará terminada cuando:

- Cumpla los criterios de aceptación establecidos.
- Esté integrada en la aplicación y pueda utilizarse.
- Haya sido probada y tenga sus errores relevantes corregidos.
- Presente información comprensible y unidades claras cuando corresponda.
- Cuente con la documentación necesaria.
- En el caso de recetas y cálculos, tenga respaldo técnico para el contenido y las reglas utilizadas.

Kristel y Krisley serán responsables de verificar que los incrementos cumplan esta definición antes de considerarlos terminados.

### 2.6. Comunicación y seguimiento del trabajo

- El equipo mantendrá un tablero de trabajo con las tareas pendientes, en proceso y terminadas.
- Las decisiones relevantes sobre requisitos, cálculos y alcance quedarán documentadas.
- Los impedimentos se comunicarán oportunamente para facilitar su resolución.
- El trabajo se distribuirá según los conocimientos, la disponibilidad y la capacidad de las Developers.
- Las consultas sobre prioridades y requisitos se dirigirán al Product Owner.
- Las mejoras en la forma de trabajo se revisarán durante las retrospectivas.


## 3. Análisis de Entorno

BioApp se desarrolla dentro de un entorno en el que existen factores tecnológicos, organizacionales y externos que pueden influir en el proyecto. Estos factores no dependen completamente del equipo de desarrollo, pero pueden afectar la construcción, las pruebas y el funcionamiento de la aplicación. Por esta razón, es importante identificarlos desde la planificación y considerar también a los principales interesados que pueden influir en la solución o aportar información necesaria para su desarrollo.

### 3.1. Factores ambientales (EEFs)

| Factor | Impacto en BioApp |
|---|---|
| **Infraestructura tecnológica disponible** | El desarrollo depende de computadoras, herramientas de programación, bases de datos y servicios necesarios para construir y probar la aplicación. |
| **Conectividad a Internet** | Puede afectar el acceso a herramientas en línea, servicios en la nube y pruebas de funcionamiento de la aplicación. |
| **Compatibilidad con dispositivos** | La aplicación debe considerar que las personas usuarias pueden acceder desde diferentes dispositivos, principalmente teléfonos y computadoras. |
| **Seguridad y protección de datos** | BioApp puede manejar información de usuarios, cultivos, terrenos e historial de aplicaciones, por lo que se deben proteger estos datos. |
| **Normativas aplicables** | Si la aplicación llega a utilizarse fuera del entorno académico, deberá considerar requisitos relacionados con privacidad, manejo de datos y uso de información agrícola. |
| **Disponibilidad de información confiable** | Las recetas, dosis y reglas de cálculo deben provenir de información previamente validada para evitar resultados incorrectos. |
| **Disponibilidad de usuarios para pruebas** | Se necesita la participación de agricultores y personas relacionadas con bioinsumos para comprobar que la aplicación sea clara y útil. |
| **Tiempo y recursos disponibles** | El proyecto se desarrolla dentro de un periodo académico de 14 semanas y con recursos limitados, por lo que el alcance debe mantenerse realista. |

### 3.2. Stakeholders del proyecto

| Interesado | Impacto en BioApp |
|---|---|
| **Personas agricultoras** | Permiten validar si la aplicación responde a necesidades reales y si resulta práctica para sus cultivos y terrenos. |
| **Profesionales en agronomía** | Apoyan en la validación de recetas, dosis y reglas de cálculo antes de incorporarlas a la aplicación. |
| **Personas encargadas de atomizar** | Ayudan a verificar si los cálculos de mezcla y cantidad por tanque son claros y útiles. |
| **Personas con experiencia en bioinsumos** | Pueden revisar ingredientes, pasos de elaboración y recomendaciones de uso. |
| **Equipo de desarrollo** | Se encarga de diseñar, programar, probar y mejorar la aplicación. |
| **Docente o persona evaluadora** | Influye en los criterios académicos, los entregables y el alcance del proyecto. |
| **Cooperativas o asociaciones agrícolas** | Pueden facilitar el contacto con personas agricultoras y apoyar posibles pruebas de la aplicación. |
| **Autoridades relacionadas con el área agrícola** | Pueden influir si la aplicación llega a utilizarse de manera pública o comercial. |

### 3.3. Conclusión del análisis

La identificación de estos factores ambientales y de los principales interesados permite comprender mejor el entorno en el que se desarrollará BioApp y las condiciones que pueden influir en el proyecto.

Tener estos elementos claros desde el inicio ayuda a anticipar posibles limitaciones relacionadas con la infraestructura tecnológica, la conectividad, la disponibilidad de recursos, la validación de la información y la participación de las personas usuarias durante las pruebas.

Además, reconocer a los interesados permite identificar quiénes pueden aportar información importante, validar funcionalidades o influir en determinadas decisiones del proyecto. De esta manera, el equipo puede organizar mejor el desarrollo, reducir posibles inconvenientes y mantener la solución enfocada en las necesidades reales de las personas usuarias y en los objetivos definidos para BioApp.