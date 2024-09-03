# Capítulo IV: Product Design
## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines

<b>Misión</b>  
Proporcionar a nuestros clientes una plataforma donde puedan alquilar de manera rápida, sencilla y segura scooters eléctricos que se adecúen a sus necesidades.

<b>Visión</b>  
Ser la aplicación web líder en el alquiler de scooters eléctricos, promoción del transporte ecoamigable y reconocidos por grupos y asociaciones de emprendimiento y medio ambiente.

<b>Brand Name</b>  
El nombre del producto es MoviRent, el cual cuenta con un logo representado por el icono de un scooter y un rayo que simboliza que el vehículo funciona electricamente con el color verde como el más predominante simbolizando el medio ambiente.  
![Logo](https://github.com/user-attachments/assets/4117bfeb-a0f2-4a3c-9a45-13fb105fb737)

<b>Colores</b>  
Decidimos elegir los colores verde claro, lila y azul al ser una combinación ligera y agradable a la vista de usuarios de diversad edades.  
![Paleta de colores](https://github.com/user-attachments/assets/4725a7ff-e7ac-4bf4-b1fd-a60d3bc9c98f)

<b>Tipografía</b>
Elegimos la fuente Open Sans porque es legible y popular en el diseño de aplicaciones web, por lo que nos aseguramos de que nuestros clientes con toda clase de necesidades visuales logren leer facilmente el contenido de nuestra web.  
![Fuentes](https://github.com/user-attachments/assets/75992501-cdf2-4a55-bc42-dd726bab6adc)

<b>Espaciado</b>  
Para nuestra aplicación usaremos el espaciado x1.5, el cual es un poco mas amplio que el usual, lo que evitará que el texto se sienta pesado o genere complicaciones de legibilidad

Tamaño de letra: 42px-20px

Interlineado: 1.5px

<b>Tono de comunicación y lenguaje aplicado</b>  
Usaremos un tono  de comunicación entusiasta y amigable en toda la web, puesto que consideramos que sería adecuado para nuestro tipo de aplicación al buscar incentivar el uso concurrido de esta. Además haremos uso de un lenguaje popular para ser inclusivos con todo tipo de nivel de lenguaje entre nuestros usuarios.

### 4.1.2. Web Style Guidelines 

Paleta de colores: Asignamos al color verde y lila como los colores más representativos de la web a demás del color blanco para mostrar una disminución en la recarga de colores para que la atención de los usuarios vaya hacia los servicios y no se desvíe a otra parte menos relevante.

Diseño Responsivo: La aplicación debe ser compatible con diferentes dispositivos y tamaños de pantalla para una experiencia de usuario consistente en todos los dispositivos.

Navegación Intuitiva: Estructura de navegación clara y fácil de usar que permita a los usuarios encontrar rápidamente la información que están buscando, se prioriza la simplicidad.

Carga Rápida: Optimización del rendimiento de la aplicación para tiempos de carga rápidos, lo que incluye la optimización de imágenes y el uso de técnicas de almacenamiento en caché así como los scripts cargados al inicio de la página.

Diseño de Tarjetas: Diseños de tarjetas para mostrar la información de manera visualmente atractiva y organizada, especialmente para la presentación de destinos y detalles de viajes.

Botones de la web: Los botones utilizados para la web serán botones rectangulares con esquinas circulares, ademas de tener botones en forma de texto en la navbar para una mejor navegación en la aplicación.

![Botones](https://github.com/user-attachments/assets/be33d4a1-f502-4f78-84c1-11eae1f82dee)

## 4.2. Information Architecture
### 4.2.1. Organization Systems

- **Jerarquía Visual:**

Con el propósito de mantener la estética de nuestra plataforma interactiva y a la vanguardia de
la competencia actual, hemos decidido priorizar la interfaz según importancia para facilitar la
interacción con el usuario.

- **Jerarquía de Tipografía:**

Nuestra plataforma difunde información que es recibida por nuestros usuarios con un orden
específico según la demanda. Por lo tanto, es importante tener en cuenta las características
con las que se generan nuestros títulos, subtítulos, párrafos, entre otros.

- **Alineación:**

En nuestra plataforma, nuestras imágenes y botones se encuentran alineados siempre de
manera vertical y horizontal. Permitiendo así agrupar varios objetos de diversos tipos con la
misma información.

- **Color y Contraste:**
A la vista de nuestros segmentos objetivos, el color cumple un rol muy importante en nuestra aplicación, promueve
las correctas composiciones del color, para dirigir diversas emociones y del contraste para
enfatizar aquellos objetos de mayor importancia.

- **Organización Secuencial:**

Además, los métodos de almacenamiento sobre los registros que el usuario final emplea
siguen una organización secuencial, esto con el objetivo de mejorar la simplicidad y la
rapidez con la que se almacenan y acceden a ellos. En el caso de nuestro proyecto
organizaremos se visualizarán la lista de Scooter para los User mientras.


- **Esquemas de categorización de contenido de nuestra web:**

Para el caso de organización visual utilizaremos el sistema jerárquico, lo que nos permitirá resaltar los componentes 
a los que deseamos que el usuario preste mayor atención. Esto dirigirá la atención del usuario a componentes de 
suma importancia.
Para el proceso de reservas de scooters haremos uso de la organización secuencial:
- Solicitud de reserva (clientes):
  - Búsqueda de scooter.
  - Elección del scooter.
  - Solicitud de reserva.
  - Entrega del scooter.
  - Devolución del scooter.

- Solicitud de la inscripción de scooters (owner):
  - Inscripción de scooter a la plataforma.
  - Establecer tarifa y disponibilidad del scooter.
  - Publicar disponibilidad del scooter.

Para los esquemas de organización utilizaremos los siguientes tipos:
- Organización por orden cronológico para el historial de reservas de los clientes.
- Organización por orden alfabético para la sección “Mis scooters” del Owner.

### 4.2.2. Labeling Systems
Para el uso de etiquetas de nuestro landing page, se ha elegido un lenguaje sencillo lo que permite a los usuarios 
familiarizarse con facilidad a las opciones proporcionadas. Esto logrará que los usuarios puedan navegar de manera 
intuitiva.

En el Landing Page visualizará los siguientes botones de navegación:

<table style="text-align: center; width: 100%; border:1px">
	<tbody>
		<tr>
			<td>Etiqueta</td>
			<td>Descripción</td>
		</tr>
		<tr>
			<td>Inicio</td>
			<td>Apartado donde se muestra la información de la aplicación explicando sus características.</td>
		</tr>
		<tr>
			<td>Sobre Nosotros</td>
			<td>Apartado donde se informa al usuario sobre el equipo y el propósito.</td>
		</tr>
		<tr>
			<td>Servicios</td>
			<td>Apartado donde se muestra el tipo de usuario que puede ser y sus ventajas.</td>
		</tr>
		<tr>
			<td>Planes</td>
			<td>Apartado donde se muestran todos los planes de suscripción.</td>
		</tr>
		<tr>
			<td>Team</td>
			<td>Apartado donde el usuario puede comunicarse con nosotros.</td>
		</tr>
		<tr>
			<td>Empieza Ya!</td>
			<td>Apartado redirigir ir a la aplicación web.</td>
		</tr>
	</tbody>
</table>

Para la página es importante, un sistema de etiquetado efectivo para permitir que los usuarios encuentren fácilmente la 
información y los servicios que necesitan. Nuestro sistema de etiquetado considera cuidadosamente cómo presentar la 
información en el sitio web. Después de establecer la organización visual y los esquemas de categorización del contenido, 
se elegirá etiquetas claras y concisas que reflejan el lenguaje común y la comprensión del usuario con palabras comunes 
no pasan de tres palabras. Nos aseguraremos de utilizar etiquetas intuitivas y fáciles de recordar para representar los 
diferentes conjuntos de información y asociaciones entre ellos. También se utilizarán diferentes colores y diseños para 
resaltar y diferenciar las etiquetas y conjuntos de información en mi sitio web. Para evitar confusiones y asegurar la 
coherencia visual en todo el sitio web, se mantendrá un sistema de etiquetado consistente y se evitará el uso de términos 
técnicos o jerga que podría ser confuso para los usuarios.

En el parte superior derecho del home page de la aplicación web contando con tres botones: 
- Mi perfil: Muestrael perfil del usuario.
- Suscripción: Muestra las suscripciones disponibles o la suscripción que el usuario ha comprado.
- Scooters: Muestra tanto los scooters en alquiler como los scooters que el usuario ha puesto en alquiler.

### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems
En esta sección, implementaremos dos métodos para mejorar la experiencia de búsqueda de nuestros usuarios. Se utilizará un sistema de búsqueda por filtros para refinar las búsquedas de la siguiente manera:

**Filtros Disponibles:**  
- Disponibilidad de Ubicación: Este filtro permitirá a los usuarios buscar vehículos disponibles en ubicaciones específicas, lo que será útil para aquellos que deseen encontrar opciones cercanas a ellos.

Con la implementación de estos sistemas de búsqueda y filtros, esperamos mejorar significativamente la experiencia de nuestros usuarios al encontrar el vehículo perfecto para sus necesidades.  
![Filtro](https://github.com/user-attachments/assets/3b1cbc6a-b1ec-435a-b59d-c7eb5d019cab)

### 4.2.5. Navigation Systems
Como sistema de navegación en pantallas desktop optamos emplear una barra de menú horizontal que guiará al usuario por las diferentes secciones con títulos claves y estáticos, esto facilitará al usuario a tener todas las herramientas a la mano y así disfrutar de una mejor navegación. Mientras que en dispositivos móviles se optó por emplear una barra de navegación desplegable.
![Navbar web](https://github.com/user-attachments/assets/fda3de2b-4cc6-47a6-a8d1-b18697d6ea73)

![Navbar movil](https://github.com/user-attachments/assets/ad1b8a37-5013-4e80-8c20-b695133028ae)
  
## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up
## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.3. Web Applications Mock-ups  
<b>Mockups Web versión desktop</b>  
![Mockups web 1](https://github.com/user-attachments/assets/d87499a3-28d1-4f2b-a4c4-4ee9ebfc346f)
![Mockups web 2](https://github.com/user-attachments/assets/5d4b462d-38b2-44fb-9ef3-eea04d4cf6af)

<b>Mockups Web versión móvil</b>  
![Mockups movil 1](https://github.com/user-attachments/assets/b348156e-ecc3-40ca-b1d6-4bce866194df)
![Mockups movil 2](https://github.com/user-attachments/assets/e21ee357-f122-4ed0-97e6-d22d2b1c7867)
![Mockups movil 3](https://github.com/user-attachments/assets/89080d9d-ddbd-4602-86bf-12405794a04a)

### 4.4.4. Web Applications User Flow Diagrams
## 4.5. Web Applications Prototyping
## 4.6. Domain-Driven Software Architecture
### 4.6.1. Software Architecture Context Diagram

<img src="/assets/chapter-04/DataBase/DiagramaC4-Context.png"/>

### 4.6.2. Software Architecture Container Diagrams

<img src="/assets/chapter-04/DataBase/DiagramaC4-Container.png"/>

### 4.6.3. Software Architecture Components Diagrams
## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams

<img src="/assets/chapter-04/Diagram/Diagram.png"/>

### 4.7.2. Class Dictionary

<table>
	<tbody>
		<tr>
			<td>Clase</td>
			<td>Descripción</td>
			<td>Tipo de dato</td>
		</tr>
		<tr>
			<td rowspan="3">Owner</td>
			<td>id: Es el indentificador único del usuario</td>
			<td>Int</td>
		</tr>
		<tr>
			<td>nombre: Es el nombre del usuario</td>
			<td>String</td>
		</tr>
		<tr>
			<td>correo: Dirección de correo electrónico del usuario</td>
			<td>String</td>
		</tr>
		<tr>
			<td rowspan="3"></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td rowspan="3"></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td rowspan="4"></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td rowspan="4"></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td rowspan="4"></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td rowspan="5">Usuario</td>
			<td>id: Es el indentificador único del usuario</td>
			<td>Int</td>
		</tr>
		<tr>
			<td>nombre: Es el nombre del usuario</td>
			<td>String</td>
		</tr>
		<tr>
			<td>correo: Dirección de correo electrónico del usuario</td>
			<td>String</td>
		</tr>
		<tr>
			<td>contraseña: Es la contraseña del usuario para acceder al sistema</td>
			<td>String</td>
		</tr>
		<tr>
			<td>tipo: Se encarga de identificar al tipo de usuario</td>
			<td>String</td>
		</tr>
		<tr>
			<td rowspan="7"></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

## 4.8. Database Design
### 4.8.1. Database Diagram
Para desarrollar la estructura de diagrama de base de datos usamos la herramienta de Vertabelo. A continuación, muestra las tabla de diseño de base de datos.

![DatabaseDiagram](https://github.com/user-attachments/assets/b8f690f2-babf-4e25-ab85-86626d7d8dfb)


---
