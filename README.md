[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10657558.svg)](https://doi.org/10.5281/zenodo.10657558)
# Simulación en arqueología

Presentación para seminario en la asignatura ["Tendencias Actuales en Arqueología"](https://grad.ub.edu/grad3/plae/AccesInformePDInfes?curs=2023&assig=573569&ens=M270D&recurs=pladocent&n2=1&idioma=ESP) en el [Máster en Estudios Avanzados](https://web.ub.edu/es/web/estudis/w/masteruniversitari-M270D?presentation) en Arqueología de la Universidad de Barcelona (14/12/2023).

Preparado con *reveal.js* (https://revealjs.com/).

Diapositivas: https://andros-spica.github.io/UB-Angourakis-2023/


## Ejercicio: diseño o modelización conceptual  

El objetivo de este ejercicio es introducir la primera y más importante etapa en la aplicación de la simulación, definición del sistema y diseño del modelo, a temas de arqueología.

Dado un tópico general de interés asociado a un cierto tipo de evidencia arqueológica, hemos de producir un modelo conceptual que contiene una definición de los rasgos mínimos de un fenómeno o sistema (representación), con miras a la formalización matemática del mismo (mecanismo), de modo que contribuya a la respuesta a una o más preguntas de investigación o a falsear o reformular una hipótesis de trabajo (validación).

Este ejercicio refleja la naturaleza exploratoria de la modelización explicativa, dónde es clave cubrir el máximo de explicaciones potenciales desde nuestro conocimiento previo, pero también hemos de avanzar parsimoniosamente hacia la definición de un modelo computacional (implementación) que sea inteligible y computable en un plazo razonable.  

Un modelo conceptual puede expresarse aquí de maneras diversas, por ejemplo como listas de elementos y relaciones, esquemas, diagramas, etc. Es decir, no forzaremos el uso de convenciones como [UML](https://es.wikipedia.org/wiki/Lenguaje_unificado_de_modelado), pese a que podría facilitar la siguiente etapa (implementación). Ejemplos de diagramas UML también pueden ofrecer inspiraciones, aunque no se aprendan sus reglas. Otras convenciones más específicas pueden ser también muy útiles y relativamente fáciles de aprender: 

- [Diagramas causales, "stocks" y flujos, o de Forrester](https://en.wikipedia.org/wiki/System_dynamics): útiles para relacionar el cambio de variables agregadas (stocks) a parámetros y otras variables (flujos).
- [Diagramas de flujo](https://es.wikipedia.org/wiki/Diagrama_de_flujo): útiles para representar flujos de lógica, sobre todo procedimentos simples de toma de decisiones.

Ver algunos ejemplos de modelización conceptual en este tutorial en inglés: https://github.com/Andros-Spica/ABM-tutorial-koeln-2022?tab=readme-ov-file#conceptual-model

Se anima a que se escoja el ámbito de arqueología y se proponga el proceso en el pasado según los intereses y experiencia previa del estudiante/investigador. Alternativamente, se pueden usar una de las siguientes propuestas a modo de punto de partida:

| evidencia arqueológica | fenómenos en el pasado (candidatos a mecanismos) |
| ---------------------- | --------------------- |
| distribución y tamaño de asentamientos | subsistencia, crecimiento demográfico dependiente de factores ambientales, mobilidad y sedentariedad |
| contexto funerario (número y estilo de artefactos, determinación de edad y sexo, proximidad morfológica y genética entre individuos, etc) | enterramiento ritual de ciertos individuos (creencias, composición de la población, asimetrias y desigualdades, etc), mortalidad (frecuencia, contextos), toma de decisión y logistica sobre la práctica funeraria |
| detección de residuos orgánicos en la superfície de vasijas cerámicas | producción (tratamiento de superfície) y uso de vasijas (almacenamiento, cocción, consumo de alimentos), toma de decisiones en la producción, selección de recetas y componentes de la dieta |
| distribución y diversidad de variedades de un tipo de artefacto muy frecuente (instrumentos líticos, cerámicas, etc.) | movimientos de personas y artefactos, transmisión cultural de maneras de producir y/o usar dichos artefactos |
| frecuencia de especies en carbones vegetales entre los estratos de un yacimiento | cambios climáticos que limiten o potencien el crecimiento por especie, talla selectiva, incendios, deforestación |
| datación por C14 más antigua de la presencia de plantas y animales domesticados en yacimientos distribuidos a lo largo de una región | crecimiento demográfico y migración, interacción entre grupos con y sin domesticados (intercambio, asimilación, conflicto, etc) |
| volumen de un mineral extraído en un yacimiento con mineración, duración de ocupación y actividad | subsistencia y liberación de mano de obra, toma de decisiones sobre intensidad mineradora, uso y intercambio de minerales |
