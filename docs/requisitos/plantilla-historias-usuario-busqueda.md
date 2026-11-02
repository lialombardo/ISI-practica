# Historias de usuario de búsqueda

| Campo | Valor |
| --- | --- |
| Proyecto | Proyecto Simbiosis |
| Fecha | [dd/mm/aaaa] |
| Versión | [Versión de trabajo] |
| Estado | Borrador |

## Fuentes comunes

- [Acta de UC-21 Buscar recetas](../captura/acta-acuerdos-uc-21-buscar-recetas.md), v1.1, Vigente.
- [Catálogo de requisitos](catalogo-requisitos.md), UR-08 y FR pertinentes.
- [Modelo de casos de uso](../modelos/modelo-casos-de-uso.md), UC-21.

## Épica de búsqueda

Como persona quiero buscar recetas mediante palabras, frases ,ingredientes incluido y excluir ingerdientes, para encontrar recetas especificas.

**Estado:** descompuesta en US-01, US-02 y US-03. Conserva la necesidad conjunta.

## Justificación de la división

[Justificación de los resultados útiles que separa la división.]

## US-01

**Título:** Buscar recetas por palabra o frase

Como persona, quiero buscar recetas mediante una palabra o frase, para localizar rápidamente platos por su nombre o descripción.


**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado que hay recetas publicadas y validadas con una frase en su título o descripción breve, cuando la persona busca esa frase exacta, entonces el sistema muestra esas recetas ordenadas por fecha de publicación, con las más recientes primero.
- **CA-02.** Dado que ninguna receta cumple con la palabra de búsqueda introducida, cuando la persona ejecuta la búsqueda, entonces el sistema indica que no hay resultados, conserva los criterios para poder modificarlos y propone correcciones ortográficas o alternativas relacionadas con los criterios.
- **CA-03.** Dada la interfaz de búsqueda, cuando la persona intenta ejecutar la búsqueda sin indicar ningún criterio, entonces el sistema solicita que introduzca un criterio y conserva la búsqueda sin ejecutarla.

## US-02

**Título:** Buscar recetas por ingredientes incluidos


Como persona usuaria registrada, quiero buscar recetas seleccionando los ingredientes que quiero  que sean incluidos, para localizar recetas que continenen los ingredientes que tengo en casa.

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado que la persona selecciona los ingredientes, a partir de los nombres disponibles, cuando ejecuta la busqueda, entonces los resultados muestran solo recetas que continen los ingredientes seleccionados.
- **CA-02.** Dado que la persona ha seleccionado más de un ingrediente, cuando ejecuta la busqueda, entonces las recetas encontradas contienen todos los ingredientes seleccionados.
- **CA-03.** Dado que la persona ha ejecutado una busqueda seleccionando ingredientes con éxito, cuando el sistema muestra los resultados, entonces cada vista previa muestra título, imagen, calificación y descripcion breve.
  
## US-03

**Título:** [Capacidad]

Como [rol], quiero [capacidad], para [beneficio].

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-02.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## Revisión INVEST

La revisión abarca US-01, US-02 y US-03. «Aplicado» indica si se ha realizado la comprobación. «Cumple» indica si todas las historias cumplen el criterio. Si alguna no lo cumple, indicar «No» e identificar la historia y el motivo en la justificación. Si no se ha realizado la comprobación o faltan datos, indicar «Pendiente» en «Cumple».

| Criterio | Pregunta de revisión | Aplicado | Cumple | Justificación |
| --- | --- | --- | --- | --- |
| Independiente | ¿Puede implementarse cada historia y ofrecer un resultado útil sin implementar antes las otras historias del conjunto? Puede compartir infraestructura con ellas. | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Negociable | ¿Cada historia explica qué necesita la persona y deja margen para discutir los detalles de la solución, respetando los acuerdos confirmados? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Valiosa | ¿La parte «para…» de cada historia explica el beneficio que obtiene la persona al usar esa capacidad? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Estimable | ¿Están claros el alcance y los datos necesarios para estimar el trabajo de cada historia? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Pequeña | ¿Se centra cada historia en una única capacidad de alcance manejable? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Comprobable | ¿Los criterios de aceptación de cada historia describen acciones y resultados observables que permiten distinguir un comportamiento correcto de uno incorrecto? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |

## Dudas pendientes

[Cuestiones pendientes de aclaración. Si no quedan cuestiones, indicar «Ninguna».]
