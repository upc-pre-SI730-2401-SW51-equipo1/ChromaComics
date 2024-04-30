# Capítulo V: Product Implementation, Validation & Deployment.

## 5.1. Software Configuration Management.

### 5.1.1. Software Development Environment Configuration.
En esta sección se describirán los productos para el desarrollo de software que han sido implementados para este proyecto. Así mismo, esta sección da su importancia al contar con información relevante para futuros equipos de desarrollo que deseen continuar con el ciclo de vida del producto de software.
### Project Management
- [**Discord**](https://discord.com/): Plataforma que funciona como aplicación web, mobile y desktop. Se empleó esta plataforma como medio para las reuniones virtuales con el equipo de desarrollo y tener un medio para compartir multimedia.
- [**Trello**](https://trello.com/es): La herramienta es una aplicación web empleada para realizar la asignación de tareas en el formato (do, doing & done). De tal forma que todo el equipo tenga conocimiento de las tareas que se están realizando con el fin de tener un buen proyecto.
### Requirements Management
- [**Trello**](https://trello.com/es): La herramienta nos permite realizar un backlog de equipo y colaborar en el mismo. Adicionalmente, proporciona una vista cómoda respecto a este dejando en claro los puntos de interés o prioridad del equipo.
### Product UI/UX Design
- [**Figma**](https://www.figma.com/): La aplicación web de Figma fue utilizada para desarrollar los wireframes, mockups y mobile applications prototyping de manera colaborativa.
- [**Uxpressia**](https://uxpressia.com/): Se empleó esta aplicación web para la realización de los User Personas, el Customer Journey Map, Empathy Map e Impact Map.
- [**Miro**](https://miro.com/): La aplicación web de Miro ha sido utilizada en el desarrollo de los escenarios mapping y customer journey map
### Software Development
- **Landing Page**: Para la realización del landing page se utilizarán las tecnologías de: HTML5, CSS3 y JavaScript. Además, para realizar un óptimo desarrollo para la forma responsiva, se utilizará el framework de BootStrap.
- **Frontend Web Application**: Para la realización del está sección de nuestra aplicación web se usarán las mismas tecnologías que en el Landing Page. Adicionalmente, nos estaremos apoyando del framework Vue para su realización como librería complementaria de JavaScript.
- **Herramientas:** Node, npm, Vite
### Web Services
Para los diversos servicios web que se desarrollaran, se empleará el estilo de arquitectura RESTful API. Se usará el lenguaje C#, ya que estaremos usando ASP .NET.
### IDE's de desarrollo
[**Webstorm**](https://www.jetbrains.com/webstorm/): Este IDE será usado para el desarrollo de la parte del frontend de la aplicación web.

[**Rider**](https://www.jetbrains.com/rider/): Este IDE será usado para el desarrollo de la parte del backend de la aplicación web.
### Software Testing
Para realizar pruebas del landing page y la aplicación web, se utilizaron los principlaes navegadores web como [Google Chrome]([https://www.google.com/chrome/](https://www.google.com/chrome/)), [Microsoft Edge]([https://www.microsoft.com/en-us/edge](https://www.microsoft.com/en-us/edge)) y [Mozilla Firefox]([https://www.mozilla.org/en-US/firefox/new/](https://www.mozilla.org/en-US/firefox/new/)).
Adicionalmente, se usará la extensión [Google Lighthouse]([https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk))para tener un panorama automatizado y actualizado del landing page.
### Project Deployment
[**Netlify**](https://www.netlify.com/): Para llevar a cabo el deployment del landing page, se procedió a vincular el repositorio de Github con Netlify. De este modo, Netlify gestionará de manera automática el deploy del landing page cada vez que exista un nuevo cambio en el repositorio.
### Software Documentation
- [**GitHub**](https://github.com/): Para la realización del informe y diversos entregables, se ha creado un repositorio en el formato markdown para tener un control de versiones de los archivos.
- [**Lucidchart**](https://www.lucidchart.com/): Aplicación web que fue utilizada para el desarrollo de los wireflows, user flows y diagramas UML.
- [**Structurizr**](https://structurizr.com/): Aplicación web que fue utilizada para  crear los diagramas C4 de manera sencilla.
### 5.1.2. Source Code Management.
El manejo y la organización de las diferentes modificaciones se llevaron a cabo mediante la plataforma de gestión de repositorios Github.
#### Organización:
[upc-pre-SI730-2401-SW51-equipo1](https://github.com/upc-pre-SI730-2401-SW51-equipo1)
#### Repository:
[Web Application & Landing Page](https://github.com/upc-pre-SI730-2401-SW51-equipo1/ChromaComics)
#### Control de versiones con GitFlo:w:
Para llevar un control de las ramas, los commits y los cambios realizados en el código fuente, se procedió a utilizar GitFlow.
Se tenían 3 ramas principales:
- main: En esta rama se almacenan las versiones oficiales del repositorio que ya deben pasar a producción.
- develop: Esta rama se utiliza como rama de integración para las "feature branches". Una vez el "head" alcance un estado estable y el equipo lo considere listo para ser lanzado, se unirá a la rama release.
- Informe: En esta rama se subía en todo lo relacionado a la documentación del proyecto
  Ramas auxiliares:

- feature: En estas ramas se trabajan las features que se unirán a la rama develop.
- release: En wsta rama se podrá corregir pequeños bugs.

##### Convenciones de Commits
El formato de nuestros commits sigue la estructura de los "Conventional Commits" en su versión [1.0.0]([https://www.conventionalcommits.org/en/v1.0.0/](https://www.conventionalcommits.org/en/v1.0.0/)) con el siguiente formato:

``<type>[optional scope]: <description>

Donde:
- type: Indica el tipo de cambio realizado en el commit. Los tipos más comunes son:
- feat: Nueva característica
- fix: Corrección de un bug
- chore: Tareas de mantenimiento
- docs: Actualización de la documentación
- scope: (opcional) Indica el área del código que ha sido modificada.
- description: Breve descripción del cambio realizado.

Ejemplo de commit:

`feat: Implementación del componente de 'add new comic'`
### 5.1.3. Source Code Style Guide & Conventions.
**Convenciones de versiones de lanzamiento:**
Para el formato de versiones se aplicará "Semantic Versioning 2.0.0". Donde las versiones siguen el formato de (X.Y.Z). Donde:

- X: Representa una versión mayor. Aquí se encuentran los cambios que no son compatibles con las versiones anteriores.
- Y: Versión menor. Aquí se encuentran los cambios que sí son compatibles con las versiones anteriores.
- Z: Parches y correcciones de errores menores.

**Guía de estilo y convenciones de código fuente:**
- **HTML y CSS**: Se utilizará [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html), ya que contiene los formatos que se deben tener en cuenta al trabajar con dichas tecnología.
- **JavaScript:** Se utilizará la [guia de estilos para js](https://google.github.io/styleguide/jsguide.html).
- **Gherkin:** Se usarán las convenciones mencionadas en [Make your Gherkin Specifications More Readable](https://specflow.org/gherkin/gherkin-conventions-for-readable-specifications/).
- **Vue JS:** Para las convenciones de se utilizarán las ya mencionadas por el equipo de [Vue](https://vuejs.org/guide/introduction.html).
- C#: Con el fin de cumplir los estándares del leguaje, se usará la [guia proporcionada por Microsoft](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions).
- .NET Framework: Para cumplir con la guia de estilos, Microsoft también nos proporciona una guia en su propio [repositorio github](https://github.com/dotnet/aspnetcore/wiki/Engineering-guidelines#coding-guidelines).
### 5.1.4. Software Deployment Configuration.
Para el despliege en la plataforma, lo realizaremos de la siguiente manera:
1.  Accedemos  a [Netlify](https://www.netlify.com/) y nos creamos una cuenta (si ya contamos con una cuenta, ingresamos). Luego, realizamos la busqueda de la sección de ''add new site'' e importaremos un proyecto existente con la opción ''Import an existing project''.
2. Seleccionamos cuál será la plataforma con el repositorio donde tenemos el código de nuestra aplicación. En nuestro caso será GitHub.
3. Seleccionamos la organización en donde se instalará el deploy de nuestra página web
4. Finalmente, indicamos el repositorio y la ruta o branch de la cuál se realizará el despliegue.
## 5.2. Landing Page, Services & Applications Implementation.

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1.
En este sprint nos enfocaremos en establecer los cimientos para la creación de la landing page de AgroGes utilizando HTML, CSS y JavaScript. Las tareas principales incluyen:

- Usar la estructura general de la landing page incluido en el figma.
- Usar la paleta de colores y estilos visuales definidos en el style guide.
- Configurar el repositorio en GitHub para el proyecto.

| Sprint # | Sprint 1 |
|----------|---------|
| | Sprint Planning Background |
| Date | 2024-04-09 |
| Location | Virtual meeting via Google Meet |
| Prepared By | Sergio |
| Attendees | Alvaro, Sergio Joel, André, Miguel, Fabrizzio |
| Sprint n - 1 Review Summary | As this was our first meeting, we distributed tasks and provided constant feedback on the sections. All team members demonstrated their knowledge and experience during the feedback sessions before committing the work to the repository. |
| Sprint n - 1 Retrospective Summary | Our team members found that continuous review of progress before commits was necessary for the landing page development. While this approach focused us on the final product, it also limited creative freedom. For future deliveries, we plan to work closely in face-to-face meetings to avoid such situations. |
| | Sprint Goal & User Stories |
| Sprint 1 Goal | Our sprint goal is to complete the landing page. Our metric for success will be achieving the following: |
| Sprint 1 Velocity | We aim to complete 9 story points, which we consider an acceptable workload for steady progress. |


#### 5.2.1.2. Sprint Backlog 1.
sprint backlog with the tasks:
-Create Wireframes for Each Landing Page Section: Design wireframes for each section of the landing page.
-Select and Apply a Color Palette Using CSS: Choose and implement a color scheme using CSS.
-Set Up the Basic Structure of the Landing Page Using HTML: Create the foundational structure of the landing page using HTML.
Apply Basic Styles Using CSS for Formatting and Design: Add basic styles to enhance the formatting and visual design of the page.


| **User Story Id** | **Title** | **Work-Item/Task Id** | **Title** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status** |
|-------------------|------------|-----------------------|------------|-----------------|-----------------------|----------------|------------|
| T01               | Explore the Homepage | W01 | Styling for the landing page | In this task, we will design the landing page to attract users to our product. | 1 | Alvaro, Sergio Joel | Done |
| T02               | View Product/Service Information | W02 | Add details about our product | Provide additional information about our product and its benefits. | 1 | André | Done |
| T03               | Contact the Sales Team | W03 | Add a form for email communication with the sales group | Create a contact section where users can provide their information. | 1 | Miguel | Done |
| T04               | Explore Testimonials or Success Stories | W04 | Design a section to showcase testimonials or success stories | Create a section where users can read positive experiences from other clients. | 1 | Fabrizzio | done |

During the sprint, the following elements were developed:

- Detailed wireframes for each section of the landing page.
- A defined color palette applied using CSS.
- The basic structure of the landing page created in HTML.

| Repository | Branch | Commit Id | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|---------------------|--------------------|
| SergioPecan| main   | 8c856     | style: update landing language | 12/04/2024 |

#### 5.2.1.4. Testing Suite Evidence for Sprint Review

Preliminary tests were conducted to verify the correct display and functionality of the landing page across different devices and browsers.

#### 5.2.1.5. Execution Evidence for Sprint Review

During the sprint, active work was done on developing the landing page using HTML and CSS to structure and style the page based on wireframes and the defined color palette.

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

Documentation was prepared regarding the landing page structure, including wireframes and a description of the color palette used.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

No software deployment occurred during this sprint, as the focus was on the initial development of the landing page.

#### 5.2.1.8. Team Collaboration Insights during Sprint

Throughout the sprint, the team collaborated closely on defining the structure and styles of the landing page, actively discussing design and development best practices. GitHub repositories were used to coordinate work and conduct code reviews among team members.

### 5.2.2. Sprint 2

#### 5.2.2.1.Sprint Planning 2.

#### 5.2.2.2.Sprint Backlog 2.

#### 5.2.2.3.Development Evidence for Sprint Review.

#### 5.2.2.4.Testing Suite Evidence for Sprint Review.

#### 5.2.2.5.Execution Evidence for Sprint Review.

#### 5.2.2.6.Services Documentation Evidence for Sprint Review.

#### 5.2.2.7.Software Deployment Evidence for Sprint Review.

#### 5.2.2.8.Team Collaboration Insights during Sprint.


