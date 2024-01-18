# Presentación de GitHub Copilot

## Introducción
### Breve descripción de GitHub Copilot

### Beneficios y características

- Varias formas de interactuar con ello: Chat in line, predicciones mientras escribes, chat general.

- Aumento de productividad

- Buena herramienta de aprendizaje

- Es multilingüe

- Comprensión contextual

- Funciona en varios IDEs y en CLI.

- Trabajar con lenguajes de código abierto populares como Javascript, Java, .NET y Python produce mejores sugerencias que, por ejemplo, Cobol

### Challenges

- Aunque GitHub Copilot sugiere código de igual o mejor calidad que el desarrollador medio, no podemos garantizar que el código esté libre de errores. Como cualquier programador, Copilot puede sugerir a veces código inseguro. Le recomendamos que tome las mismas precauciones que toma con el código escrito por sus ingenieros (linting, controles de calidad y de seguridad en CI/CD etc.)

- Dependencia excesiva: Existe el riesgo de que los desarrolladores se vuelvan demasiado dependientes de Copilot.

- Tienes que ser muy preciso en lo que le pides que haga: Por ejemplo, código que se aplica para una versión de un Framework o un Lenguaje, pero no para otras más antiguas.

### Consejos
- Establezca un contexto completo, aliméntalo con todas las entradas relevantes, incluyendo bloques de código, archivos abiertos o todo el workspace. **Sólo sabe lo que tú le dices.**
- A todos nos encanta odiar las expresiones regulares. Es una gran herramienta para ayudarte con esto.
- Tiene una paciencia infinita para explicarte las cosas, algo que un humano no siempre sería capaz de hacer.
- Suponga que es solo un asistente desde el principio. Tienes que leer sus sugerencias y probarlas. Es como cuando vas a stackoverflow donde una respuesta puede ser adecuada para ellos pero no para ti.
- Puede ayudarle a escribir pruebas, incluidos archivos .http para probar endpoints.
- Es importante detenerse cuando algo anda mal. En algún momento la herramienta podría ser correcta, pero también podría estar equivocada. Ayúdale a ayudarte empezando desde el principio.
- No es muy determinista. El mismo prompt producirá un resultado diferente.
- Iterar, iterar, iterar. No acepte la primera sugerencia si está seguro de que se puede mejorar.


## Instalación de GitHub Copilot y GitHub Copilot Chat
- Guía de instalación paso a paso.

## Uso de las herramientas en VS Code

Introducción a VS Code y su integración con GitHub Copilot.

### Ejemplos Prácticos
#### Creación de un proyecto de API y web desde cero

**Crear una API de Spring Boot**

```
¿Cómo puedo crear una API REST en Java Spring Boot?
```

Ahora lo mismo, pero utilizando el agente @workspace:
```
@workspace /new crea un proyecto de un REST API en Java Spring Boot que contiene un endpoint de HealthCheck, que devuelve 200 OK
```

```
¿Cómo puedo ejecutar esta aplicación?
```

```
@workspace ¿Cómo puedo ejecutar esta aplicación?
```

**Crear modelos y endpoints HTTP**

```
Créa para mi un modelo para gestionar libros
```

```
 ¿Puedes crearme una API para este modelo?
```
```
¿Cómo puedo llamar a esta API desde Postman?
```

#### Escribir pruebas
**Cómo escribir pruebas unitarias con la asistencia de GitHub Copilot**
```
¿Puedes ayudarme a hacer tests unitarios?
```
o bien, haga clic en el método y
```
/tests
```

#### Crear pipelines de CI/CD
- Guía para crear pipelines de CI/CD utilizando GitHub Copilot

```
@workspace crea las pipelines CI/CD para Azure DevOps en formato YAML para compilar y desplegar esta aplicación en Azure App Service.
```

```
Separa el CI del CD, para que cada uno este en su propio fichero.
```

#### Definir infraestructura para desplegar en Azure
```
¿Puedes generarme el Terraform para desplegar esta web en Azure?
```

## Preguntas y Respuestas/Conversación
- Abierto para preguntas y comentarios adicionales

## Enlaces de interés
- Documentación: https://docs.github.com/es/copilot
- Usando CoPilot en la CLI: https://docs.github.com/es/copilot/github-copilot-in-the-cli
- Sobre seguridad, seguridad y flujo de datos: https://resources.github.com/copilot-trust-center/

