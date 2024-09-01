# Pruebas de la API de Urban.Grocers 

## Descripción del Proyecto

En este proyecto, se realizaron pruebas exhaustivas para la nueva funcionalidad de la API de **Urban.Grocers**. El propósito de esta API es gestionar kits de comestibles y verificar los servicios de entrega. Se ha añadido nueva funcionalidad para permitir la adición de productos a kits y para comprobar la disponibilidad y el costo del servicio de entrega **"Order and Go"**.

### Funcionalidades Principales

- **Gestión de Kits:** 
   - Endpoint POST /api/v1/kits/{id}/products para agregar productos a un kit.
   - El endpoint devuelve un error 400 Bad Request si la longitud de la lista de productos excede 30.
- **Servicios de Entrega:** 
   - Endpoint POST /order-and-go/v1/delivery para verificar la disponibilidad y el costo del servicio de entrega "Order and Go".
  
## Tecnologías Utilizadas

- **Google Sheets:** Para la gestión y documentación de las listas de comprobación y resultados de las pruebas.
- **Postman:** Herramienta utilizada para ejecutar las pruebas de la API.
- **Jira:** Para documentar y gestionar los informes.

## Cómo Empezar

1. **Iniciar el Servidor:**
   - Haz clic en el botón "Iniciar el servidor" para lanzar el servidor local de la aplicación.
   - Espera hasta 2 minutos para que el servidor se inicie completamente.
   - Si ves un enlace antes de que todos los componentes estén listos, es posible que recibas el mensaje "Intenta desplegar el servidor primero". Espera a que todos los componentes estén operativos antes de acceder.

2. **Preparar la Documentación de Prueba:**
   - Revisa los requisitos de las nuevas funciones en la documentación de la API en ApiDoc.
   - Diseña tus pruebas en una lista de comprobación en una hoja de cálculo de Google. Crea una copia de la plantilla proporcionada.

3. **Ejecutar las Pruebas:**
   - Usa Postman para probar los endpoints de la API según las listas de comprobación diseñadas.
   - Documenta los resultados de las pruebas en la hoja de cálculo de Google.
   - Para cada caso de prueba.
       - **ID:** Identificador único del caso.
       - **Título del Caso de Prueba:** Descripción breve del caso.
       - **Condición Previa:** Requisitos previos necesarios.
       - **Paso/Descripción del Paso:** Acciones a realizar.
       - **Resultado Esperado:** Resultado esperado después de realizar los pasos.

   - **Estado:** Actualiza el estado con Aprobada, No Aprobada, o Omitida.
   - **ID de Error:** Si un caso de prueba falla, crea un informe de error en Jira y agrega el ID correspondiente en la hoja de cálculo.

4. **Crear Informes de Errores:**
   - Documenta todos los errores encontrados en la pestaña "Informes de errores" de la hoja de cálculo de Google.
   - Completa los campos: ID, título, pasos, resultado esperado, resultado actual, y severidad (Bloqueador, Crítico, Grave, Menor, Trivial).

## Implementación del Proyecto

Para completar el proyecto:
1. **Accede a Google Sheets:** Inicia sesión con tu cuenta de Google o regístrate.
2. **Completa la Plantilla:**
   - Ejecuta los casos de prueba y marca el estado correspondiente.
   - Crea informes de errores para las pruebas no aprobadas.
   - Agrega los ID de los informes de errores para las pruebas fallidas.

## Estructura del Repositorio

- **Documentación Adicional y Plantillas:** Contiene documentación adicional y plantillas utilizadas durante el proyecto.
- **Casos de Prueba y Resultados:**
  - Casos de prueba para la nueva funcionalidad de la API.
  - Resultados de las pruebas.
- **Informes de Errores:** Contiene los informes de errores generados durante las pruebas.

¡Gracias por tu contribución a las pruebas de la API de Urban.Grocers! Si tienes alguna pregunta o necesitas más información, no dudes en contactarme.

https://docs.google.com/spreadsheets/d/1wOf7Ofa3Sh6Y-0-beVjOc5Gs6OtzIwFg/edit?gid=382707264#gid=382707264

![1](https://github.com/user-attachments/assets/e849744e-9c5a-4043-b9c1-269e5c41f4bb)

![2](https://github.com/user-attachments/assets/837e81d6-1885-4487-9be5-dcce4838cb49)

![3](https://github.com/user-attachments/assets/6183911d-9549-4a89-a101-49d3b9070da3)

![4](https://github.com/user-attachments/assets/69d513a2-f762-4014-9caf-a6ebda3b91d6)




