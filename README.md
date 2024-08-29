# urban-grocers-API-testing
Registro y documentacion de resultados de pruebas realizadas para la version API de Urban Grocers
Urban.Grocers API Testing

## Descripción

Este repositorio está destinado a documentar y registrar los resultados de las pruebas realizadas para la nueva versión de la API de Urban Grocers. La nueva funcionalidad incluye la capacidad de trabajar con kits y servicios de entrega. Esta documentación servirá para garantizar que las nuevas funciones se comporten como se espera.

La interfaz API incluye:

    Trabajar con Kits: Permite agregar productos a un kit a través del endpoint POST /api/v1/kits/{id}/products. La longitud de la lista de productos no debe exceder 30 elementos para evitar un error 400 Bad Request.
    Servicios de Entrega: Permite verificar la disponibilidad del servicio de entrega "Order and Go" y calcular el costo a través del endpoint POST /order-and-go/v1/delivery.

## Instrucciones

    Preparar el entorno:
        Asegúrate de tener acceso a los entornos de prueba: La API se ejecuta en un servidor de prueba.

    Ejecutar las pruebas:
        Diseña y sigue las listas de comprobación para verificar las nuevas funcionalidades de la API.
        Utiliza Postman para ejecutar las pruebas.

    Documentar errores:
        Registra cualquier error encontrado en Jira.
        
## Estructura del Repositorio

    Documentación adicional y plantillas:
        Información relevante para el diseño de pruebas y la documentación de errores.

    Casos de prueba y resultados:
        Casos de prueba diseñados para verificar la funcionalidad de los kits y los servicios de entrega.
        Resultados de las pruebas.

    Informes de errores:
        Documentación de errores encontrados durante las pruebas.

    Plantillas y formatos:
        Plantillas para listas de comprobación y documentos de informes.

https://docs.google.com/spreadsheets/d/1wOf7Ofa3Sh6Y-0-beVjOc5Gs6OtzIwFg/edit?gid=382707264#gid=382707264
