
---
# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping

Aquí se expone el análisis de los escenarios, organizando una tabla que detalla la situación que necesita ser optimizada para el segmento objetivo. Se examinan los pasos a seguir y se describe cómo se perciben. 


<img src="..//assets/chapter-03/To-BeMapping.png" alt="Imagen To Be Mapping 1">


## 3.2. User Stories

<table >
    <tr>
        <th>Epic / Story ID</th>
        <th>Título</th>
        <th>Descripción</th>
        <th>Criterios de Aceptación</th>
        <th>Relacionado con (Epic ID)</th>
    </tr>
    <tr>
        <td>EP01</td>
        <td>Landing page para la aplicacion MoviTech</td>
        <td><b>Cómo</b> miembro de Movitech <b>Quiero</b> desarrollar una landing page <b>Para</b> informar acerca del servicio a los posibles clientes.</td>
        <td>No corresponde</td>
        <td>No corresponde</td>
    </tr>
    <tr>
        <td>EP02</td>
        <td>Gestion de cuenta de usuario</td>
        <td><b>Cómo</b> Owner/Cliente de Movitech <b>Quiero</b> crear, visualizar, eliminar y editar mi cuenta <b>Para</b> tener mis datos actualizados y comenzar a hacer uso de la aplicacion correctamente.</td>
        <td>No corresponde</td>
        <td>No corresponde</td>
    </tr>
    <tr>
        <td>EP03</td>
        <td>Gestion de scooters en alquier</td>
        <td><b>Cómo</b> Owner de Movitech <b>Quiero</b> agregar y gestionar mis vehiculos <b>Para</b> asegurarme que esten disponibles y en buen estado para el alquiler.</td>
        <td>No corresponde</td>
        <td>No corresponde</td>
    </tr>
    <tr>
        <td>EP04</td>
        <td>Gestion de reservas</td>
        <td><b>Cómo</b> cliente de Movitech <b>Quiero</b> gestionar mis reservas y el uso de vehiculos <b>Para</b> planificar y controlar mis recorridos. </td>
        <td>No corresponde</td>
        <td>No corresponde</td>
    </tr>
    <tr>
        <td>EP05</td>
        <td>Gestionar historial de reservas</td>
        <td><b>Cómo</b> usuario de Movitech <b>Quiero</b> poder ver el historial completo de las reservas realizadas<b>Para</b> consultar detalles como fechas de alquiler, tipo, lugar de recogida y devolucion. </td>
        <td>No corresponde</td>
        <td>No corresponde</td>
    </tr>
    <tr>
        <td>EP06</td>
        <td>Gestion de planes</td>
        <td><b>Cómo</b> cliente de Movitech <b>Quiero</b> tener una gestion y control de mi plan <b>Para</b> poder adquirirlo y comprarlo cuando lo requiera</td>
        <td>No corresponde</td>
        <td>No corresponde</td>
    </tr>
    <tr>
        <td>US01</td>
        <td>Descripcion de la aplicacion y startup</td>
        <td><b>Cómo</b>visitante interesado 
        <b>Quiero</b> ver una descripcion clara del producto
        <b>Para</b> entender sus beneficios y caracteristicas.</td>
        <td>
            <b>Scenario 1: Visualizar seccion Home</b> <br/>
            <b>Dado que</b> el owner tiene acceso a la aplicación, <br/>
            <b>Cuando</b> registra un nuevo vehículo <br/>
            <b>Entonces</b> Ingresa los detalles o caracteristicas del vehículo, como marca, modelo, tipo (bicicleta, scooter, moto eléctrica, etc.), disponibilidad, ubicación del vehículo, <br/>
            <b>Scenario 2: Acceder a la sección "About us</b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page <br/>
            <b>Cuando</b> navegue hasta la sección “About Us” <br/>
            <b>Entonces</b> se muestra información importante sobre la startup. <br/>
            <b>Scenario 3: Acceder a la sección "Services"</b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page<br/>
            <b>Cuando</b> navegue hasta la sección “Services” <br/>
            <b>Entonces</b> se muestra información sobre los servicios que ofrece MoviTech<br/>
            <b>Scenario 4: Explorar la sección "Pricing"</b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page<br/>
            <b>Cuando</b> navegue hasta la sección “Pricing” <br/>
            <b>Entonces</b> se muestra la información relacionada a los planes de pago que se ofrecen y cuáles son los beneficios de cada uno de estos.<br/>
            <b>Scenario 5: Conocer al equipo en "About The Team"</b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page <br/>
            <b>Cuando</b>  navegue hasta la sección “About The Team”<br/>
            <b>Entonces</b> se muestra la información correspondiente a los videos about the project y about the team, además de la información de cada uno de los miembros.<br/>
        <td>EP01</td>
    </tr>
    <tr>
        <td>US02</td>
        <td>Acceder a la aplicación desde la landing page </td>
        <td><b>Cómo</b> visitante de la landing page 
        <b>Quiero</b> poder acceder a la aplicación MoviTech desde la landing page
        <b>Para</b> comenzar a utilizar las funcionalidades ofrecidas</td>
        <td>
            <b>Scenario 1: Usuario ingresa a aplicación</b> <br/>
            <b>Dado que</b> el visitante se encuentra en la landing page <br/>
            <b>Cuando</b> seleccione la opción que permite el acceso al software elaborado<br/>
            <b>Entonces</b> es redirigido a la aplicación desplegada<br/>
            <b>Scenario 2: Fallo en el acceso a la aplicación</b> <br/>
            <b>Dado que</b> el visitante se encuentre en la landing page <br/>
            <b>Cuando</b> seleccione la opción que permite el acceso al software elaborado y ocurra un error en el proceso de redirección<br/>
            <b>Entonces</b> el usuario obtiene un mensaje de error.<br/>
        <td>EP01</td>
    </tr>
    <tr>
        <td>US03</td>
        <td>Registrar usuario</td>
        <td><b>Cómo</b>visitante de la aplicación web de MoviTech
        <b>Quiero</b> poder crear una cuenta personal
        <b>Para</b> comenzar a hacer uso de la aplicación como Owner/Cliente.</td>
        <td>
            <b>Scenario 1: Usuario ingresa credenciales válidas.</b> <br/>
            <b>Dado que</b> el visitante desee crear una cuenta personal en la aplicación MoviTech <br/>
            <b>Cuando</b> ingrese las credenciales de una cuenta inexistente en la base de datos MoviTech, una contraseña que cumple con todos los requisitos de seguridad, su DNI real y acepte los términos y condiciones de uso <br/>
            <b>Entonces</b> se creará la cuenta de usuario.<br/>
            <b>Scenario 2: Usuario ingresa credenciales incorrectas.</b> <br/>
            <b>Dado que</b> Usuario ingresa credenciales incorrectas. <br/>
            <b>Cuando</b> ingrese una dirección de correo electrónico o contraseña o DNI que no cumplen con los requisitos especificados<br/>
            <b>Entonces</b> se le denegará la operación<br/>
        <td>EP02</td>
    </tr>
    <tr>
        <td>US04</td>
        <td>Iniciar sesion</td>
        <td><b>Cómo</b>Owner/Cliente de MoviTech 
        <b>Quiero</b> iniciar sesión
        <b>Para</b> acceder a los beneficios que ofrece la aplicación.</td>
        <td>
            <b>Scenario 1: Usuario ingresa credenciales válidas </b> <br/>
            <b>Dado que</b> el usuario posee una cuenta en la aplicación MoviTech y desee iniciar sesión <br/>
            <b>Cuando</b> ingrese las credenciales necesarias correctamente<br/>
            <b>Entonces</b> el sistema permitirá el acceso a la aplicación<br/>
            <b>Scenario 2: Usuario ingresa credenciales incorrectas</b> <br/>
            <b>Dado que</b> el usuario posee una cuenta en la aplicación MoviTech y desea iniciar sesión <br/>
            <b>Cuando</b> ingrese alguna credencial de manera incorrecta <br/>
            <b>Entonces</b> el sistema denegará la solicitud<br/>
        <td>EP04</td>
    </tr>
    <tr>
        <td>US05</td>
        <td>Visualizar perfil de usuario</td>
        <td><b>Cómo</b>Owner/Cliente de MoviTech 
        <b>Quiero</b> visualizar mi perfil personal 
        <b>Para</b> visualizar mis datos actuales</td>
        <td>
            <b>Scenario 1: Acceder al perfil personal</b> <br/>
            <b>Dado que</b> el usuario desee visualizar su información personal <br/>
            <b>Cuando</b>  ingrese a su perfil <br/>
            <b>Entonces</b> obtendrá toda la información que registró previamente<br/>
            <b>Scenario 2: Problema al acceder al perfil personal </b> <br/>
            <b>Dado que</b> el usuario desee visualizar su información personal  <br/>
            <b>Cuando</b> intente ingresar a su perfil Y experimente un error de conexión o de servidor <br/>
            <b>Entonces</b> no se visualizarán los datos del perfil <br/>
        <td>EP02</td>
    </tr>
    <tr>
        <td>US06</td>
        <td>Cambiar datos personales </td>
        <td><b>Cómo</b>Owner/Cliente de MoviTech 
        <b>Quiero</b> cambiar los datos asociados a mi perfil
        <b>Para</b>actualizar la información</td>
        <td>
            <b>Scenario 1: Cambiar contraseña</b> <br/>
            <b>Dado que</b> el usuario quiera cambiar su contraseña <br/>
            <b>Cuando</b> ingrese la nueva contraseña, esta sea validada por el sistema y el usuario confirme su intención de proceder con el cambio<br/>
            <b>Entonces</b> la nueva clave será guardada y la información actualizada.<br/>
            <b>Scenario 2: Cambiar nombre</b> <br/>
            <b>Dado que</b> el usuario quiera cambiar su nombre<br/>
            <b>Cuando</b> ingrese el nuevo nombre, esta sea validada por el usuario y confirme su intención de proceder con el cambio <br/>
            <b>Entonces</b> el nuevo nombre será guardado y la información actualizada<br/>
            <b>Scenario 3: Cambiar foto</b> <br/>
            <b>Dado que</b> el usuario quiera cambiar su foto <br/>
            <b>Cuando</b> ingrese la nueva foto, esta sea validada por el usuario y confirme su intención de proceder con el cambio<br/>
            <b>Entonces</b> la nueva foto será guardada y la información actualizada<br/>
        <td>EP02</td>
    </tr>
    <tr>
        <td>US0000</td>
        <td>CA</td>
        <td><b>Cómo</b>CA 
        <b>Quiero</b> CA
        <b>Para</b> CA</td>
        <td>
            <b>Scenario CA: CA</b> <br/>
            <b>Dado que</b> CA <br/>
            <b>Cuando</b> CA<br/>
            <b>Entonces</b> CA<br/>
        <td>EP01</td>
    </tr>
</table>

## 3.3. Impact Mapping

## 3.4. Product Backlog.

<table border="1px" style="text-align: center; width: 100%;">
  <tr>
    <td valign="top"> #Orden </td>
    <td valign="top"> User Story Id </td>
    <td valign="top"> Título </td>
    <td valign="top"> Descripción </td>
    <td valign="top"> StoryPoints (1/2/3/5/8 </td>
  </tr>
  <tr>
    <td valign="top"> 01 </td>
    <td valign="top"> US01 </td>
    <td valign="top"> Registro de usuarios </td>
    <td valign="top"> Como cliente, quiero registrarme en la plataforma para poder alquilar scooters eléctricos. </td>
    <td valign="top"> 3 </td>
  </tr>
  <tr>
    <td valign="top"> 02 </td>
    <td valign="top"> US02 </td>
    <td valign="top"> Inicio de sesión </td>
    <td valign="top"> Como cliente, quiero registrarme en la plataforma para poder alquilar scooters eléctricos. </td>
    <td valign="top"> 3 </td>
  </tr>
  <tr>
    <td valign="top"> 03 </td>
    <td valign="top"> US03 </td>
    <td valign="top"> Alquiler de scooter </td>
    <td valign="top"> Como cliente registrado, quiero alquilar un scooter eléctrico desde mi ubicación actual para transportarme. </td>
    <td valign="top"> 3 </td>
  </tr>
  <tr>
    <td valign="top"> 04 </td>
    <td valign="top"> US04 </td>
    <td valign="top"> Finalización del alquiler </td>
    <td valign="top"> Como cliente, quiero finalizar el alquiler del scooter cuando llegue a mi destino para detener el cobro. </td>
    <td valign="top"> 3 </td>
  </tr>
  <tr>
    <td valign="top"> 05 </td>
    <td valign="top"> US05 </td>
    <td valign="top"> Pago del servicio </td>
    <td valign="top"> Como cliente, quiero poder pagar mi alquiler de scooter de manera rápida y segura para completar mi viaje. </td>
    <td valign="top"> 4 </td>
  </tr>
  <tr>
    <td valign="top"> 06 </td>
    <td valign="top"> US06 </td>
    <td valign="top"> Historial de viajes </td>
    <td valign="top"> Como cliente, quiero ver un historial de mis alquileres para revisar mis gastos y destinos anteriores. </td>
    <td valign="top"> 4 </td>
  </tr>
  <tr>
    <td valign="top"> 07 </td>
    <td valign="top"> US07 </td>
    <td valign="top"> Registrar un vehículo </td>
    <td valign="top"> Cómo Owner quiero registrar los detalles de mi vehículo en la aplicación web para que mis potenciales clientes puedan elegirlo para el alquiler </td>
    <td valign="top"> 4 </td>
  </tr>
  <tr>
    <td valign="top"> 08 </td>
    <td valign="top"> US08 </td>
    <td valign="top"> Pago del servicio </td>
    <td valign="top"> Como cliente, quiero poder pagar mi alquiler de scooter de manera rápida y segura para completar mi viaje. </td>
    <td valign="top"> 4 </td>
  </tr>
  <tr>
    <td valign="top"> 09 </td>
    <td valign="top"> US09 </td>
    <td valign="top"> Pago del servicio </td>
    <td valign="top"> Como cliente, quiero poder pagar mi alquiler de scooter de manera rápida y segura para completar mi viaje. </td>
    <td valign="top"> 4 </td>
  </tr>
  <tr>
    <td valign="top"> 10 </td>
    <td valign="top"> US10 </td>
    <td valign="top"> Pago del servicio </td>
    <td valign="top"> Como cliente, quiero poder pagar mi alquiler de scooter de manera rápida y segura para completar mi viaje. </td>
    <td valign="top"> 4 </td>
  </tr>
  <tr>
    <td valign="top"> 11 </td>
    <td valign="top"> US11 </td>
    <td valign="top"> Pago del servicio </td>
    <td valign="top"> Como cliente, quiero poder pagar mi alquiler de scooter de manera rápida y segura para completar mi viaje. </td>
    <td valign="top"> 4 </td>
  </tr>
  <tr>
    <td valign="top"> 12 </td>
    <td valign="top"> US12 </td>
    <td valign="top"> Pago del servicio </td>
    <td valign="top"> Como cliente, quiero poder pagar mi alquiler de scooter de manera rápida y segura para completar mi viaje. </td>
    <td valign="top"> 4 </td>
  </tr>
  <tr>
    <td valign="top"> 13 </td>
    <td valign="top"> US13 </td>
    <td valign="top"> Pago del servicio </td>
    <td valign="top"> Como cliente, quiero poder pagar mi alquiler de scooter de manera rápida y segura para completar mi viaje. </td>
    <td valign="top"> 4 </td>
  </tr>
</table>

---
