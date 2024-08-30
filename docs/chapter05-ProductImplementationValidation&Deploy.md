
---

# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
En este apartado, se mencionarán los distintos productos de software empleados por el equipo de desarrollo, para llevar acabo las actividades relacionadas con la elaboración del proyecto.

<br>

**Project Management**

Google Meet (https://meet.google.com/): Google Meet es una plataforma de videoconferencias que permite realizar reuniones a distancia, facilitando la comunicación entre los integrantes del proyecto.  
<br>

**Requirements Managements**

Trello (https://trello.com/): Es un software de gestión de proyectos, que facilita asignar y organizar las tareas a realizar. Fue utilizado para el Product Backlog.  
<br>

**Product UX/UI Design** 

UXPressia (https://uxpressia.com/): Es una herramienta en línea que permite a los equipos de trabajo identificar y comprender los problemas, necesidades y comportamiento del usuario en relación a la solución de software que se está desarrollando, con el uso de plantillas. Se utilizó para la elaboración de los User Personas, Empathy Maps, Journey Maps e Impact Maps.

Figma (https://www.figma.com/): Figma es una herramienta de edición gráfica, en donde se puede diseñar y prototipar páginas web y aplicaciones de manera colaborativa en tiempo real. Se usó para realizar los wireframes, mock-ups y los desktop and mobile application prototype del proyecto.

Miro (https://miro.com/): Es una plataforma colaborativa el cual permite crear y usar pizarras digitales personalizadas en tiempo real. Miro cuenta con distintas herramientas y plantillas para la elaboración de mapeos, diagramas, flujos de trabajo, etc. Se utilizó para la realización de los As-Is y Tob-Be Scenario Maps.  
<br>

**Software Development**  

Landing Page: Para la creación de la landing page, se utilizaron las tecnologías base del desarrollo web: HTML5, CSS3 y JavaScript.  

GitHub (https://github.com/): Esta es una plataforma digital donde se pueden alojar proyectos mediante repositorios, los cuales utilizan un sistema de control de versiones llamado Git. GitHub nos permite trabajar colaborativamente y tener un seguimiento detallado de los avances en el proyecto. 

Git (https://git-scm.com/): Este es un software de control de versiones el cual se instala localmente y nos permite tener un historial de cambios que se realizan en el proyecto mediante commits. También se utiliza para trabajar colaborativamente en repositorios que se encuentran subidos en GitHub. 

WebStorm: Este es un entorno de desarrollo, el cual nos permite trabajar con HTML, CSS, Javascript y con frameworks como Vue y Angular.

Rider: Este es un entorno de desarrollo, el cual nos permite trabajar con el lenguaje C# y la plataforma .NET que nos permite crear diferentes tipos de aplicaciones, ya sean móvil, web o de escritorio. En nuestro caso, usaremos ASP .NET para crear un Web Service para nuestro proyecto.  
<br>

**Software Deployment**  

Netlify (https://www.netlify.com/): Netlify es una plataforma de despliegue de páginas y aplicaciones web, integrandose con repositorios en Git. Se usó para hospedar la landing page del proyecto.  
<br>

**Software Documentation**  

Vertabelo (https://vertabelo.com/): Es una herramienta online que facilita el diseño, creación y gestión de bases de datos de manera colaborativa. Se usó para diseñar la base de datos del proyecto.

LucidChart (https://lucid.app/): LucidChart es una plataforma que cuenta con opciones para la creación de diagramas, mapas mentales, flujos y más, con el uso de plantillas y tableros con edición en tiempo real. Fue utilizado en el desarrollo del diagrama de clases UML, así como los Wireflows y User Flows.

Structurizr (https://www.structurizr.com/): Es una plataforma que permite modelado de diagramas de arquitectura de software por medio de código. Structurizr fue utilizado para crear el modelo C4 de nuestro proyecto.     
<br>

**Software Testing**

Gherkin: Este es un lenguaje DSL (Domain Specific Language), que nos permite abordar problemas específicos. Esto lo utilizamos para los criterios de aceptación de las historias de usuario de nuestro proyecto.

GitHub Pages (https://pages.github.com/): Este es un servicio que ofrece GitHub para publicar un sitio web a partir de un repositorio, cabe destacar que solo permite alojar sitios web estáticos con archivos HTML, CSS y JavaScript. 

Markdown: Este es un lenguaje de marcado ligero, el cual nos permite documentar proyectos. En cuanto a nosotros, utilizamos este lenguaje para redactar el informe de nuestro proyecto y en los archivos README en el repositorio de la organización. 

### 5.1.2. Source Code Management
### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration
## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1
<table>
     <tr> 
        <th>  Sprint #  </th>
        <th> Sprint 1 </th>
     </tr>
     <tr> 
        <td style="font-weight: bold;" colspan="7"> Sprint Planing Background</td>
     </tr>
     <tr>
       <td style="font-weight: bold;"> Date </td>
       <td> 27/08/2024 </td>
     </tr>
     <tr>
       <td style="font-weight: bold;"> Time </td>
       <td> 20:00 pm - 02:00 am </td>
     </tr>
     <tr>
       <td style="font-weight: bold;"> Location </td>
       <td> Modalidad remota a través de WhatsApp y Google Meets </td>
     </tr>
      <tr>
        <td style="font-weight: bold;"> Prepared By </td>
        <td> Bárbara Espinoza Espinoza Delgado </td>
     </tr>
        <tr>
        <td style="font-weight: bold;"> Attendees (to planning meeting) </td>
        <td> 
         Adriana María Diestra Zambrano
           <br>
         Bárbara Espinoza Espinoza Delgado 
          <br>
         Mathias Adriano Hidalgo López 
          <br>
         Néstor Velarde Gonzales 
          <br>
         Quique Vladimir Jara Benites
          <br>
         Roy Linsh Fernandez Remon
     </td>
     </tr>
     <tr>
        <td style="font-weight: bold;"> Sprint 0 Review Summary </td>
        <td> No existe.</td>
     </tr>
     <tr>
        <td style="font-weight: bold;"> Sprint 0 Retrospective Summary </td>
        <td> No existe. </td>
     </tr>
     <tr> 
        <td style="font-weight: bold;" colspan="7"> Sprint Goal & User Stories</td>
     </tr>
       <tr>
          <td style="font-weight: bold;"> Sprint 1 Goal</td>
          <td>  En este sprint se espera la implementación y deployado de la landing page con las secciones funcionales, el footer y el diseño responsivo. En el grupo acordamos usar html y css para hacer la landing page. Al finalizar este sprint la landing page se desplegó en Netlifly para que sea accesible por culaquier usuario desde su navegador de preferencia. </td>
      </tr>
       <tr>
          <td style="font-weight: bold;"> Sprint 1 Velocity </td>
          <td>  9  </td>
      </tr>
      <tr>
          <td style="font-weight: bold;"> Sum of Story Points </td>
          <td> 9 </td>
      </tr>


  </table>
  
#### 5.2.1.2. Sprint Backlog 1

<img src="https://github.com/UPC-AppWeb-CiberMach/Final-Report/blob/bcf2a8744e2aa6d6ffc796f7a9796660338452f7/assets/chapter-05/Trellos/Trello%20Sprint%201.png">

Link de Trello: https://trello.com/invite/b/66ccf1855ff6c24fe148a766/ATTI34b50c784e97d0a7ba15dd3b49b56ca5D82CFA4B/sprint-1 

<table> 
   <tr>
      <th colspan="4"> Sprint # </th>
      <th colspan="7"> Sprint 1 </th>
   </tr>
   <tr >
     <th colspan="4"> User Story </th>
     <th colspan="7"> Work-Item /Task</th>
   </tr>
   <tr>
     <th > Id </th>
     <th colspan="3"> Title </th>
     <th> Id </th>
     <th > Title </th>
     <th> Description </th>
     <th> Estimation (Hours) </th>
     <th> Assigned To </th> 
     <th> Status (To-do / In-Process / To- Review / Done) </th>
    <tr>
      <th> EP01-US01 </th>
     <th colspan="3"> Implementación de la sección Home de la Landing Page</th>
      <th> W01  </th>
     <th> Sección Inicio </th>
     <th> Implementar la seccion Inicio de la Landing Page. </th>
     <th> 2  </th>
     <th> Néstor Velarde </th> 
     <th> Done </th>
   </tr>
    <tr>
      <th> EP01-US02 </th>
     <th colspan="3">Implementación de la sección "About us" de la Landing Page</th>
      <th> W02  </th>
     <th> Sección "Sobre nosotros"</th>
     <th> Implementar la seccion "About Us" de la landing page. </th>
     <th> 1  </th>
     <th> Bárbara Espinoza  </th> 
     <th> Done </th>
   </tr>
     <tr>
      <th> EP01-US03 </th>
     <th colspan="3"> Implementación de la sección "Servicios" de la Landing Page</th>
      <th> W03  </th>
     <th> Sección "Services" </th>
     <th> Implementar la sección "Servicios" de la landing page. </th>
     <th> 2  </th>
     <th> Vladimir Jara </th> 
     <th> Done </th>
   </tr>
     <tr>
      <th> EP01-US04 </th>
     <th colspan="3">Implementación de la sección "Pricing" de la Landing Page</th>
      <th> W04  </th>
     <th> Sección "Membresías" </th>
     <th> Implementar la seccion "Membresías" en la landing page </th>
     <th> 3  </th>
     <th> Mathias Hidalgo </th> 
     <th> Done </th>
   </tr>
     <tr>
      <th> EP01-US05 </th>
     <th colspan="3"> Implementación de la sección "About the Team" de la Landing Page</th>
      <th> W05  </th>
     <th> Sección "About the Team" </th>
     <th> Implementar la sección "About the Team" de la landing page</th>
     <th> 3  </th>
     <th> Adriana Diestra </th> 
     <th> Done </th>
   </tr>
    <tr>
      <th> EP01-US06 </th>
     <th colspan="3">Landing Page Responsiva a Diferentes tamaños de pantalla</th>
      <th> W03  </th>
     <th> Landing Page Responsive </th>
     <th> Implementación de diseño responsivo a la landing page para que se adapte a diferentes tamaños de pantalla </th>
     <th> 5  </th>
     <th> Roy Fernandez </th> 
     <th> Done </th>
   </tr>
</table>
    
#### 5.2.1.3. Development Evidence for Sprint Review
#### 5.2.1.4. Testing Suite Evidence for Sprint Review
#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint.

---

