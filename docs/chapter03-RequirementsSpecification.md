
---
# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping
## 3.2. User Stories

<table border="1px" style="text-align: center; width: 100%;">
  <tr>
    <td valign="top"> Epic / Story ID </td>
    <td valign="top"> Título </td>
    <td valign="top"> Descripción </td>
    <td valign="top"> Criterios de Aceptación </td>
    <td valign="top"> Epic ID </td>
  </tr>
  <tr>
    <td valign="top"> US01 </td>
    <td valign="top"> Registro de Usuarios </td>
    <td valign="top"> Como cliente, quiero registrarme en la plataforma para poder alquilar scooters eléctricos. </td>
    <td valign="top"> Dado que un nuevo usuario desea utilizar la plataforma, Cuando el usuario proporciona su correo electrónico, Google o Facebook para registrarse, Luego el sistema verifica la identidad del usuario y crea una nueva cuenta. </td>
    <td valign="top"> EP01 </td>
  </tr>
  <tr>
    <td valign="top"> US02 </td>
    <td valign="top"> Inicio de Sesión </td>
    <td valign="top"> Como cliente registrado, quiero iniciar sesión en la plataforma para acceder a los scooters disponibles. </td>
    <td valign="top"> Dado que un cliente registrado desea acceder a su cuenta, Cuando el cliente introduce sus credenciales (correo electrónico y contraseña, Google o Facebook), Luego el sistema autentica al cliente y lo redirige a la página principal de la plataforma. </td>
    <td valign="top"> EP01 </td>
  </tr>
  <tr>
    <td valign="top"> US03 </td>
    <td valign="top"> Alquiler de Scooter </td>
    <td valign="top"> Como cliente registrado, quiero alquilar un scooter eléctrico desde mi ubicación actual para transportarme. </td>
    <td valign="top"> Dado que el cliente está autenticado en la plataforma, Cuando el cliente selecciona un scooter disponible en su ubicación, Luego el sistema desbloquea el scooter y muestra el costo estimado del alquiler antes de que el cliente confirme la acción. </td>
    <td valign="top"> EP01 </td>
  </tr>
  <tr>
    <td valign="top"> US04 </td>
    <td valign="top"> Finalización del Alquiler </td>
    <td valign="top"> Como cliente, quiero finalizar el alquiler del scooter cuando llegue a mi destino para detener el cobro. </td>
    <td valign="top"> Dado que el cliente ha llegado a su destino, Cuando el cliente selecciona la opción de finalizar el alquiler en la aplicación, Luego el sistema bloquea el scooter, calcula el costo total del viaje, y muestra un resumen del mismo. </td>
    <td valign="top"> EP01 </td>
  </tr>
  <tr>
    <td valign="top"> US05 </td>
    <td valign="top"> Pago del Servicio </td>
    <td valign="top"> Como cliente, quiero poder pagar mi alquiler de scooter de manera rápida y segura para completar mi viaje. </td>
    <td valign="top"> Dado que el cliente ha finalizado un viaje, Cuando el cliente confirma el costo total del viaje, Luego el sistema procesa el pago automáticamente usando el método de pago predeterminado y muestra un recibo de la transacción. </td>
    <td valign="top"> EP01 </td>
  </tr>
  <tr>
    <td valign="top"> US06 </td>
    <td valign="top"> Historial de viajes </td>
    <td valign="top"> Como cliente, quiero ver un historial de mis alquileres para revisar mis gastos y destinos anteriores. </td>
    <td valign="top"> Dado que el cliente ha realizado varios viajes, Cuando el cliente accede a la sección de historial de viajes en su perfil, Luego puede ver una lista con detalles como fechas, horas, costos y destinos, y descargar un resumen en formato PDF.
 </td>
    <td valign="top"> EP01 </td>
  </tr>
  <tr>
    <td valign="top"> US07 </td>
    <td valign="top"> Registrar un Vehículo  </td>
    <td valign="top"> Cómo Owner quiero registrar los detalles de mi vehículo en la aplicación web para que mis potenciales clientes puedan elegirlo para el alquiler </td>
    <td valign="top"> Dado que el owner tiene acceso a la aplicación, Cuando registra el scooter, ingresa los detalles y características, ubicación del vehículo, Luego el sistema valida la información, Y confirma su registro de manera satisfactoria. </td>
    <td valign="top"> EP01 </td>
  </tr>
  <tr>
    <td valign="top"> US08 </td>
    <td valign="top"> Establecer Tarifas </td>
    <td valign="top"> Como Owner, quiero definir el precio de alquiler de mi vehículo para maximizar mis ingresos y asegurar una compensación justa por su uso </td>
    <td valign="top"> Dado que el Owner tiene un scooter registrado, Cuando establece la tarifa e ingresa el costo por hora, día y semana, Luego el sistema procesa la información correctamente, Y el scooter queda configurado con las tarifas y disponibilidad establecidas. </td>
    <td valign="top"> EP01 </td>
  </tr>
  <tr>
    <td valign="top"> US09 </td>
    <td valign="top"> Visualización del Recorrido </td>
    <td valign="top"> Como Owner, quiero visualizar el recorrido y tiempo de uso de los vehículos. </td>
    <td valign="top"> Dado que el Owner tiene acceso al sistema, Cuando selecciona su scooter en estado de alquiler. Luego la plataforma muestra en tiempo real el recorrido del vehículo en el mapa y el tiempo total de uso durante un período específico. </td>
    <td valign="top"> EP01 </td>
  </tr>
  <tr>
    <td valign="top"> US10 </td>
    <td valign="top"> Historial de reserva </td>
    <td valign="top"> Como Owner quiero acceder al historial de mis vehículos reservados para monitorear su uso. </td>
    <td valign="top"> Dado que el Owner tiene acceso al sistema Cuando Accede al historial de reservas desde la plataforma. y Selecciona su scooter para revisar su historial de reservas. Luego el sistema muestra el historial completo de todas las reservas realizadas para ese scooter. </td>
    <td valign="top"> EP01 </td>
  </tr>
  <tr>
    <td valign="top"> US11 </td>
    <td valign="top"> Visualización del perfil de cliente </td>
    <td valign="top"> Como Owner quiero visualizar el perfil del cliente que hace uso de mi vehículo para conocer a mi cliente </td>
    <td valign="top"> Dado que el Owner tiene acceso al sistema Cuando accede a la gestión de clientes desde la plataforma. Y Selecciona el perfil de un cliente que ha hecho uso de su scooter. Luego el sistema le muestra la información detallada del cliente, como nombre, contacto, fotografía y comentarios. </td>
    <td valign="top"> EP01 </td>
  </tr>
   <tr>
    <td valign="top"> US12 </td>
    <td valign="top"> Visualización del perfil de cliente </td>
    <td valign="top"> Como Owner quiero visualizar el perfil del cliente que hace uso de mi vehículo para conocer a mi cliente </td>
    <td valign="top"> Dado que el Owner tiene acceso al sistema Cuando accede a la gestión de clientes desde la plataforma. Y Selecciona el perfil de un cliente que ha hecho uso de su scooter. Luego el sistema le muestra la información detallada del cliente, como nombre, contacto, fotografía y comentarios. </td>
    <td valign="top"> EP01 </td>
  </tr>
   <tr>
    <td valign="top"> US11 </td>
    <td valign="top"> Visualización del perfil de cliente </td>
    <td valign="top"> Como Owner quiero visualizar el perfil del cliente que hace uso de mi vehículo para conocer a mi cliente </td>
    <td valign="top"> Dado que el Owner tiene acceso al sistema Cuando accede a la gestión de clientes desde la plataforma. Y Selecciona el perfil de un cliente que ha hecho uso de su scooter. Luego el sistema le muestra la información detallada del cliente, como nombre, contacto, fotografía y comentarios. </td>
    <td valign="top"> EP14 </td>
  </tr>
   <tr>
    <td valign="top"> US11 </td>
    <td valign="top"> Visualización del perfil de cliente </td>
    <td valign="top"> Como Owner quiero visualizar el perfil del cliente que hace uso de mi vehículo para conocer a mi cliente </td>
    <td valign="top"> Dado que el Owner tiene acceso al sistema Cuando accede a la gestión de clientes desde la plataforma. Y Selecciona el perfil de un cliente que ha hecho uso de su scooter. Luego el sistema le muestra la información detallada del cliente, como nombre, contacto, fotografía y comentarios. </td>
    <td valign="top"> EP01 </td>
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
    <td valign="top"> US05 </td>
    <td valign="top"> Pago del servicio </td>
    <td valign="top"> Como cliente, quiero poder pagar mi alquiler de scooter de manera rápida y segura para completar mi viaje. </td>
    <td valign="top"> 4 </td>
  </tr>
  <tr>
    <td valign="top"> 09 </td>
    <td valign="top"> US05 </td>
    <td valign="top"> Pago del servicio </td>
    <td valign="top"> Como cliente, quiero poder pagar mi alquiler de scooter de manera rápida y segura para completar mi viaje. </td>
    <td valign="top"> 4 </td>
  </tr>
  <tr>
    <td valign="top"> 10 </td>
    <td valign="top"> US05 </td>
    <td valign="top"> Pago del servicio </td>
    <td valign="top"> Como cliente, quiero poder pagar mi alquiler de scooter de manera rápida y segura para completar mi viaje. </td>
    <td valign="top"> 4 </td>
  </tr>
  <tr>
    <td valign="top"> 11 </td>
    <td valign="top"> US05 </td>
    <td valign="top"> Pago del servicio </td>
    <td valign="top"> Como cliente, quiero poder pagar mi alquiler de scooter de manera rápida y segura para completar mi viaje. </td>
    <td valign="top"> 4 </td>
  </tr>
  <tr>
    <td valign="top"> 12 </td>
    <td valign="top"> US05 </td>
    <td valign="top"> Pago del servicio </td>
    <td valign="top"> Como cliente, quiero poder pagar mi alquiler de scooter de manera rápida y segura para completar mi viaje. </td>
    <td valign="top"> 4 </td>
  </tr>
</table>

---
