# Chapter III: Requirements Specification
----
## 3.1. To-Be Scenario Mapping.

**Segmento objetivo:** Administrador de la empresa que brinda almuerzo a sus empleados

![To-be-business](/assets/img/chapter-III/To-be-map-business-segment.jpg)

## 3.2. User Stories.

#### Epics:
| Epics ID  | Titulo    | Descripcón|
|-----------|-----------|-----------|
| EP001 | Gestión de cuenta | Como usuario quiero poder acceder a mi cuenta de manera segura y personalizar mis datos de perfil para hacer uso de sus funcionalidades. |
| EP002 | Gestión de Pedidos Corporativos | Como administrador de empresa suscrita, Quiero poder realizar pedidos en nombre de todos los empleados desde una única cuenta corporativa, Para simplificar y agilizar el proceso de pedido de almuerzos y garantizar una alimentación adecuada para todos los empleados |
| EP003 | Gestión de Restaurantes Afiliados | Como administrador del restaurante afiliado quiero poder actualizar los menús diarios y recibir las órdenes a través de la plataforma para que el flujo del trabajo sea más optimizado. |
| EP004 | Gestión y Análisis de Datos para Restaurantes Afiliados | Como administrador del restaurante afiliado, quiero tener acceso a herramientas y análisis que me permitan ver las métricas clave de mi negocio, para tomar decisiones informadas y optimizar la rentabilidad y eficiencia de mi restaurante. |
| EP005 | Control de Inventario y Gestión de Productos | Como administrador del restaurante afiliado, quiero poder registrar y actualizar fácilmente los productos e ingredientes en mi control de inventario, para asegurarme de que tenga suficientes insumos para preparar los pedidos. |
| EP006 | Procesamiento de Pagos y Facturación | Como usuario quiero poder registrar una tarjeta de crédito para realizar los movimientos financieros como pago de la suscripción o retiro de ganancias Para garantizar un proceso de pago sin complicaciones y de manera segura. |
| EP007 | Información de la aplicación web | Como visitante quiero saber información de la aplicación web para ver si me interesa sus funcionalidades. |

#### User stories: 
Aqui se describira los user stories de la aplicación web y de la landing page.

| Story ID | Título | Descripción | Criterios de aceptación | Relación con (Epic ID)  |
|-----------|-----------|-----------|-----------|-----------|
| HU001 | Registrar nuevo usuario| Como usuario quiero poder registrarme en la aplicación web para acceder a las funcionalidades que se me ofrece | Celda 1,4 | EP001 |
| HU002 | Iniciar Sesión | Como usuario quiero poder iniciar sesión con mi correo y contraseña para acceder a la plataforma | Celda 2,4 | EP001 |
| HU003 | Restablecer contraseña | Como usuario quiero poder restablecer mi contraseña a través de una verificación desde mi correo para garantizar la seguridad de mi cuenta | Celda 3,4 | EP001 |
| HU004 | Actualizar información de la cuenta | Como usuario, necesito la capacidad de actualizar fácilmente mis datos de perfil para garantizar que la información asociada con mi cuenta esté siempre actualizada y precisa. | Celda 4,4 | Celda EP001|
| HU005 | Acceder a catalogo diario de menú | Como administrador de la empresa suscrita, quiero poder acceder al catálogo de menús diarios proporcionados por los restaurantes afiliados, para seleccionar fácilmente los almuerzos que se ofrecerán a los empleados y garantizar una variedad adecuada de opciones. | Celda 5,4 | EP002 |
| HU006 | Personalización de pedidos     | Como administrador de la empresa suscrita, quiero tener la capacidad de personalizar los menús disponibles en función de las preferencias y restricciones dietéticas de los empleados, para garantizar que todos los empleados tengan opciones de almuerzo que se ajusten a sus necesidades individuales. | ...       | EP002  |
| HU007 | Realización de pedidos| Como administrador de la empresa suscrita, quiero poder realizar pedidos de almuerzos en nombre de los empleados y programar la entrega de los mismos, para garantizar que los empleados reciban sus almuerzos de manera oportuna y conveniente| Celda 30,4| EP002|
| HU008 | Notificación de estado de pedidos| Como administrador de la empresa suscrita, quiero recibir notificaciones sobre el estado de los pedidos realizados, así como confirmaciones de entrega, para mantenerme informado y asegurarme de que los empleados reciban sus almuerzos según lo programado. |  ........ | EP002|
| HU009 |Acceder a Registro de pedidos. |Como administrador de la empresa suscrita, quiero poder acceder a un historial completo de pedidos realizados, para tener un registro de las órdenes hechas a cada restaurante y fechas correspondientes.|  ........ |EP002|
| HU010 |Actualización de menú diario | Como administrador del restaurante afiliado, quiero tener la capacidad de actualizar rápidamente el menú diario en la plataforma, para garantizar que los clientes corporativos tengan acceso a información actualizada sobre las opciones de almuerzo.|  ........ | EP003 |
| HU011 | Notificación de pedidos realizados|Como administrador del restaurante afiliado, quiero recibir notificaciones cada vez que se realice un nuevo pedido a través de la plataforma, para poder preparar los pedidos con anticipación y garantizar una buena atención|  ........ | EP003 |
| HU012 | Seguimiento de estado del pedido|Como administrador del restaurante afiliado, quiero tener un registro dentro plataforma donde pueda ver un resumen de todos los pedidos recibidos, incluido su estado actual (pendiente, en preparación, entregado), para facilitar la gestión y seguimiento de los pedidos.|  ........ | EP003 |
| HU013 | Establecer horario de atención |Como administrador del restaurante afiliado, quiero tener la opción de establecer horarios durante los cuales mi restaurante estará disponible para recibir pedidos a través de la plataforma, para garantizar que los pedidos se ajusten a la capacidad de mi cocina y personal. |  ........ | EP003 |
| HU014 |Actualización del estado del restaurante| Como administrador del restaurante afiliado, quiero tener la opción de cambiar el estado de mi restaurante a cerrado dentro de la plataforma en caso de vacaciones o eventos especiales para evitar conflictos de información con los clientes corporativos.|  ........ | EP003|
| HU015 | Acceder a métricas y análisis del negocio |Como administrador del restaurante afiliado, quiero poder acceder a gráficos y análisis que muestren las métricas clave de mi negocio para tomar decisión informadas respecto al restaurante. |  ........ |EP004|
| HU016 |Análisis de popularidad de los platos del menú | Como administrador del restaurante afiliado, quiero tener herramientas de análisis que me permitan analizar la popularidad de cada plato en mi menú a lo largo del tiempo, para administrar más recursos en su elaboración|  ........ | EP004 |
| HU017 |Análisis de costos y márgenes de ganancia del restaurante| Como administrador del restaurante, quiero poder observar a través de gráficos los costos y márgenes de ganancia, para tomar decisiones más informadas|  ........ | EP004 |
| HU018 |Acceso a análisis y métricas generales del negocio| Como administrador del restaurante afiliado, quiero tener la capacidad de acceder a métricas del negocio a través de la plataforma, como las ventas totales generadas y el promedio de pedidos diarios realizados, para comprender mejor el rendimiento de mi restaurante y tomar decisiones informadas. |  ........ | EP004|
| HU019 | Registrar nuevos insumos o productos al inventario. | Como administrador del restaurante afiliado, quiero poder registrar nuevos insumos y productos en el sistema, incluyendo detalles como nombre, cantidad disponible y fecha de vencimiento, para mantener un registro preciso del inventario.|  ........ |EP005 |
| HU020 | Actualización del inventario|Como administrador del restaurante afiliado, quiero poder actualizar el inventario a medida que se utilizan los productos, para garantizar una visibilidad precisa de los niveles de stock en todo momento. |  ........ | EP005 |
| HU021 |Alerta por niveles bajos de stock de un producto|Como administrador del restaurante afiliado, quiero recibir notificaciones automáticas cuando los niveles de stock de ciertos productos caigan por debajo de un umbral predefinido, para poder realizar pedidos del producto y evitar interrupciones en el servicio. |  ........ | EP005|
| HU022 |Gestionar inventario por etiquetas| Como administrador del restaurante afiliado, quiero poder organizar y gestionar mi inventario por categorías o secciones, como alimentos, bebidas y suministros, para facilitar la búsqueda y gestión de productos relacionados. |  ........ | EP005 |
| HU023 |Opción de exportación de informes|Como developer, quiero desarrollar la opción de exportación de los informes del inventario en formato CSV o PDF, para que puedan realizar análisis fuera de la plataforma.|  ........ | EP005|
| HU024 | Registrar tarjeta de crédito|  Como usuario, quiero tener la capacidad de registrar una tarjeta de crédito en mi cuenta a través de la plataforma, para poder realizar pagos de suscripción de manera conveniente y segura, así como retirar ganancias acumuladas.|  ........ | EP006|
| HU025 | Recibir confirmación de transacciones financieras| Como administrador del restaurante afiliado, quiero recibir confirmaciones automáticas a través de la plataforma cada vez que se realice un retiro de ganancias a una tarjeta de crédito, para tener la tranquilidad de que los fondos se han transferido correctamente.|  ........ | EP006 |
| HU026 | Hipervínculos de navegación | Como visitante quiero tener la opción de dirigirse a secciones específicas de la landing page, para navegar más rápido a esa información.|  ........ | EP007|
| HU027 | Acceso a la información del uso de la aplicación| Como visitante quiero poder tener acceso a la información del uso de la aplicación web para tener una idea de las funcionalidades que me ofrece. |  ........ | EP007 |
| HU028 |Acceso a Información de Beneficios y Planes | Como visitante interesado en la plataforma, quiero poder acceder fácilmente a información detallada sobre los beneficios de utilizar el servicio y los planes de suscripción disponibles, para comprender rápidamente el valor y las opciones que ofrece la plataforma. |  ........ |EP007 |
| HU029 |Acceso rápido a registro y suscripción| Como visitante de la landing page, deseo encontrar botones prominentes y llamativos que me permitan acceder rápidamente a las opciones de creación de cuenta o compra de suscripción, para poder comenzar el proceso de afiliación de  manera rápida y sencilla.|  ........ |  EP007  |
| HU030 | Acceso a la información de la startup y su contacto| Como visitante de la landing page, quiero encontrar fácilmente información sobre la startup así como un medio claro y accesible para ponerme en contacto con la empresa, para obtener más detalles sobre sus servicios o hacer consultas. |  ........ | EP007 |


## 3.3. Impact Mapping.

## 3.4. Product Backlog.