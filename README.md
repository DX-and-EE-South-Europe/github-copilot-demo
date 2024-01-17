# Presentación de GitHub Copilot

## Introducción
### Breve descripción de GitHub Copilot

### Beneficios y características

- Puedes interactuar con ello de varias formas: Chat in line, predicciones mientras escribes, chat general.

- Aumentará tu productividad: Copilot ofrece sugerencias de código en tiempo real, lo que puede acelerar el proceso de codificación. Puede ser especialmente útil para tareas repetitivas o cosas aburridas como el código repetitivo.

- Es una buena herramienta de aprendizaje: Para los principiantes, Copilot puede servir como herramienta de aprendizaje al sugerir las mejores prácticas y ofrecer fragmentos de código con los que podrían no estar familiarizados.

- Es multilingüe: Copilot es compatible con una amplia gama de lenguajes de programación, lo que lo hace versátil para diferentes proyectos.

- Comprensión contextual: A diferencia de los completadores de código tradicionales, Copilot entiende el contexto del código y ofrece sugerencias relevantes.

- Reducción de errores: Con sugerencias basadas en IA, hay una reducción potencial de errores sintácticos y lógicos.

- Funciona en varios IDEs y en CLI.

- Si trabajas con lenguajes que tienen mucho volumen en el mundo del Open Source, como Javascript, Java, .NET, Python, obtendrás mejores sugerencias que el equivalente en Cobol.

### Challenges

- Aunque GitHub Copilot sugiere código de igual o mejor calidad que el desarrollador medio, no podemos garantizar que el código esté libre de errores. Como cualquier programador, Copilot puede sugerir a veces código inseguro. Le recomendamos que tome las mismas precauciones que toma con el código escrito por sus ingenieros (linting, controles de calidad y de seguridad en CI/CD etc.)

- Dependencia excesiva: Existe el riesgo de que los desarrolladores se vuelvan demasiado dependientes de Copilot.

- A veces, está mal: Aunque Copilot es impresionante, no es infalible. A veces puede sugerir código incorrecto o ineficiente, como por ejemplo, código que se aplica para una versión de un Framework o un Lenguaje, pero no para otras más antiguas.

### Consejos
- Establezca un contexto completo, aliméntelo con todas las entradas relevantes, incluyendo bloques de código, archivos abiertos o todo el workspace. **Sólo sabe lo que tú le dices.**
- A todos nos encanta odiar las expresiones regulares. Es una gran herramienta para ayudarte con esto.
- Tiene una paciencia infinita para explicarte las cosas, algo que un humano no siempre sería capaz de hacer.
- Suponga que es solo un asistente desde el principio. Tienes que leer sus sugerencias y probarlas. Es como cuando vas a stackoverflow donde una respuesta puede ser adecuada para ellos pero no para ti.
- Puede ayudarle a escribir pruebas, incluidos archivos .http para probar endpoints.
- Es importante detenerse cuando algo anda mal. En algún momento la herramienta podría ser correcta, pero también podría estar equivocada. Ayúdalo a ayudarte empezando desde el principio.
- No es muy determinista. El mismo prompt producirá un resultado diferente.
- Iterar, iterar, iterar. No acepte la primera sugerencia si está seguro de que se puede mejorar.


## Instalación de GitHub Copilot y GitHub Copilot Chat
- Guía de instalación paso a paso

## Uso de las herramientas en VS Code

Introducción a VS Code y su integración con GitHub Copilot.

### Ejemplos Prácticos
#### Creación de un proyecto de API y web desde cero

**Crear una API de Spring Boot**

`@workspace /new crea un proyecto de un REST API en Java Spring que gestiona libros`


**Crear endpoints HTTP**

`@workspace crea los modelos y endpoints necesarios para gestionar autores de esos libros`

**Crear una SPA Angular**

`@workspace Añade una SPA en Angular`

**Intercomunicación entre la API y la SPA**

`@workspace Cambia la SPA para que interactue con el API`

#### Escribir pruebas
- Cómo escribir pruebas unitarias con la asistencia de GitHub Copilot

#### Crear pipelines de CI/CD
- Guía para crear pipelines de CI/CD utilizando GitHub Copilot

#### Definir infraestructura para desplegar en Azure
- Pasos para definir la infraestructura para el despliegue en Azure con GitHub Copilot

## Preguntas y Respuestas/Conversación
- Abierto para preguntas y discusiones adicionales

## Enlaces de interés
- Documentación: https://docs.github.com/es/copilot
- Usando CoPilot en la CLI: https://docs.github.com/es/copilot/github-copilot-in-the-cli
- Sobre seguridad, seguridad y flujo de datos: https://resources.github.com/copilot-trust-center/

