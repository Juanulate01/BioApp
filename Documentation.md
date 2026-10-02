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
