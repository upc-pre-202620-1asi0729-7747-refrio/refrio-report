# Capítulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines
El objetivo es garantizar la consistencia en todos los puntos de contacto con el usuario, facilitando la construcción de una identidad sólida, clara y accesible. Al establecer criterios claros en cuanto al empleo de colores, tipografías, iconos, espaciados y estilo comunicativo, garantizamos una experiencia de usuario práctica y uniforme, que se pueda desplegar de manera efectiva.

**a) Branding**<br>
Nuestro logo representa simbólicamente a Refrio. La letra "R" estilizada con un copo de nieve hace alusión a la refrigeración y conservación; mientras que su estructura sólida representa la gestión y la tecnología.

<div align="center">
<img src="../assets/Logo_Refrio.png" width="700"/>
</div>

**b) Typography**<br>
Se utilizarán fuentes sans-serif (como Arial, Roboto y Montserrat) por su alta legibilidad y modernidad.
* Arial: Empleada como fuente complementaria y de respaldo universal por su claridad, neutralidad y óptima lectura en cualquier sistema operativo o navegador.

* Roboto: Utilizada como la tipografía base para los textos principales, listados de inventario, tablas de productos y descripciones, garantizando nitidez en tamaños reducidos y pantallas de diversa densidad.

* Montserrat: Aplicada en títulos, encabezados principales y cifras destacadas, aportando un estilo geométrico, moderno y un alto impacto visual que refuerza la identidad corporativa de la plataforma.

| Arial | Roboto | Montserrat |
|---|---|---|
| <img src="../assets/Font_Arial.jpg" width="300"/> | <img src="../assets/Font_Roboto.png" width="300"/> | <img src="../assets/Font_Montserrat.png" width="300"/> |

Componentes de interfaz:
- Dashboards con gráficos: Integración de gráficos de líneas, barras e indicadores circulares para representar información operativa sobre el inventario y proyección de mermas de alimentos.  
- Tarjetas (cards): Diseñadas para mostrar métricas clave y datos individuales de los insumos (nombre del alimento, fecha de caducidad, días restantes y ubicación en refrigeración) de forma compacta y visual.  
- Botones: Cada una con acciones claras y visibles.

Diseño responsive:
- El sistema será adaptable a diferentes dispositivos (escritorio, tablets y smartphones) mediante una arquitectura web responsiva.
  
Accesibilidad:
- Uso adecuado de contraste de colores: Cumplimiento de estándares de contraste entre fondos y textos para asegurar la legibilidad por parte de todo tipo de usuarios, incluidos adultos mayores.

**c) Colors**<br>
Inspirada en el logotipo, la paleta refleja limpieza, tecnología y conservación térmica.
- Paleta de colores:
  - Deep Navy (#163358): Se utiliza para los títulos y resaltar algún elemento importante.
  - Cerulean Blue (#2379B6): Para botones, enlaces y elementos interactivos.
  - Off-White (#FEFFFB): Forma parte del fondo de la página en a lo largo de las secciones y para resaltar el título principal.
  - Glacier Blue (#57C4D7): Se uso para resltar los iconos.
  - Steel Blue (#2E6199): Complementa como fondo de la pagina en algunas secciones.

<div align="center">
<img src="../assets/Paleta_Colores_Refrio.jpeg" width="700"/>
</div>

**d) Spacing**<br>
El sistema de espaciado de Refrio se basa en una cuadrícula de 4 píxeles, permitiendo mantener consistencia entre los diferentes componentes de la interfaz. A partir de esta unidad base se utilizan principalmente valores de 4, 8, 12, 16, 24 y 32 píxeles, dependiendo de la relación existente entre los elementos y del nivel de separación requerido.

Los espacios de 4 px se emplean entre elementos estrechamente relacionados, como un icono y su etiqueta. Los 8 px permiten separar controles o elementos pertenecientes al mismo grupo, mientras que los 12 px se utilizan en componentes pequeños o separaciones internas frecuentes.

Los 16 px se emplean principalmente como espaciado interno de tarjetas, formularios y grupos de información. Los 24 px permiten establecer una separación visual más clara entre componentes o subsecciones.

La escala de espaciado utilizada en Refrio es:

- 4 px: separación mínima.
- 8 px: elementos relacionados.
- 12 px: componentes pequeños.
- 16 px: separación interna de componentes.
- 24 px: tarjetas y secciones.

Este sistema facilita la organización visual de información relacionada con operaciones logísticas, como tarjetas de envíos, formularios de registro, información del vehículo, conductor, incidencias y estados de transporte.

Asimismo, permite evitar la saturación visual y mantener una experiencia predecible entre las distintas vistas de la plataforma, especialmente cuando el usuario necesita revisar una cantidad considerable de información operativa.

**e) Iconography**<br>
La iconografía de Refrio sigue un estilo simple, lineal, reconocible y consistente, orientado a facilitar la identificación rápida de las principales funciones de la plataforma. Los iconos funcionan como apoyo visual para elementos de navegación, acciones, formularios, estados y diferentes procesos relacionados con la logística y control de inventario.

Se priorizan iconos de apariencia limpia, evitando ilustraciones excesivamente complejas que puedan aumentar la carga visual de la interfaz. Los iconos mantienen proporciones y estilos similares dentro de cada contexto de uso, contribuyendo a generar una experiencia visual uniforme.

Entre los principales elementos representados mediante iconografía se encuentran:

- Dashboard
- Inventario
- Orden de pedidos
- Proveedores / Clientes
- Notificaciones
- Buscar
- Análisis
- Alertas
- Configuración
- Regresar
- Salir
- Perfil

Los iconos asociados a acciones principales pueden utilizar los tonos azules de Refrio, mientras que los elementos secundarios emplean colores neutros. Los estados críticos pueden utilizar el Error Red (#D32F2F) y las advertencias el Accent Orange (#F39C12).

Los iconos no reemplazan por completo al contenido textual en las operaciones importantes. Cuando una acción puede resultar ambigua, se acompaña de una etiqueta descriptiva, por ejemplo “Registrar envío”, “Notificaciones”, “Configuración” o “Ver detalles”.

Este enfoque reduce la carga cognitiva del usuario y permite reconocer más rápidamente las acciones disponibles, especialmente en vistas que contienen múltiples operaciones, vehículos, conductores o notificaciones.

![Icons](../assets/Iconos.png)

**f) Tone of Communication and Applied Language**<br>
El tono de comunicación de Refrio es claro, profesional, respetuoso, sereno y orientado a la acción, priorizando la precisión sobre la certeza absoluta. Dado que la plataforma es dirigida para un público no tan familiarizado con la tecnología, se evitan tecnicismos innecesarios y expresiones absolutas.

De acuerdo con las dimensiones de **Refrio**, este se comunica de la siguiente manera:
- Formal pero accesible: Evitando tecnicismos informáticos complejos, utilizando un lenguaje amigable para la gestión del hogar.
- Serio y Entusiasta: Se toma muy en serio la reducción del desperdicio de alimentos y el ahorro económico, pero motiva al usuario celebrando sus logros de consumo responsable.
- Respetuoso: Siempre enfocado en asistir al usuario sin juzgar sus hábitos previos de compra.

### 4.1.2. Web Style Guidelines

En el diseño visual de Refrio se adopta una línea gráfica moderna, profesional y funcional, enfocada en la eficiencia operativa, el control de la cadena de frío y la claridad en la gestión de inventarios perecibles. La jerarquía visual se construye mediante el uso de tipografías legibles como Roboto, Inter y Montserrat, tamaños diferenciados y colores de alto contraste inspirados en su identidad corporativa (azul marino profundo #163358, azul cerúleo #2379B6 y celeste glaciar #57C4D7), complementados con alertas semánticas que permiten identificar al instante estados críticos de caducidad y variaciones térmicas.

El uso de tarjetas (cards) con bordes suaves y elevaciones sutiles organiza la información de lotes, vitrinas y despachos de forma limpia, evitando sobrecargas cognitivas durante el seguimiento de productos y la rotación FEFO. Asimismo, los componentes mantienen una estricta consistencia en toda la plataforma, agilizando la navegación y reduciendo la curva de aprendizaje tanto para empresas distribuidoras como para comerciantes locales y bodegueros. Cada elemento de la interfaz responde a un propósito operativo directo, asegurando una experiencia rápida y confiable donde la frescura y la preservación de los alimentos son esenciales. 

Por último, el diseño integra principios de arquitectura web responsiva, garantizando accesibilidad, legibilidad y un rendimiento óptimo en monitores de escritorio, tabletas y teléfonos móviles, tanto en la aplicación web como en el Landing Page.

## 4.2. Information Architecture
La arquitectura de la información de Refrio ha sido estructurada para optimizar el acceso, la organización y la visibilidad de los datos telemétricos e inventarios perecibles, delimitando los límites funcionales de los Bounded Contexts y adaptándose a la escala operativa de los planes de suscripción de la plataforma.

### 4.2.1. Organization Systems
El sistema organiza la información mediante enfoques complementarios que responden a los límites del dominio:
- Organización jerárquica:
  - Un Dashboard central como punto de entrada y monitoreo en tiempo real.
  - Módulos funcionales de primer nivel: Inventory, Shipments, Suppliers, Analytics y Alerts.
- Organización por planes de suscripción (Subscription Plans):
  - Plan Básico (S/ 59/mes - Para pequeñas operaciones / Bodegas): Orientado a la gestión ágil de hasta 3 congeladoras registradas, monitoreo básico, control de temperatura, reportes mensuales y alertas preventivas de vencimiento.
  - Plan Profesional (S/ 129/mes - Para operaciones en crecimiento / Distribuidoras medianas): Incluye todas las prestaciones del plan básico, ampliando la capacidad hasta 25 unidades de frío, analítica avanzada con IA, registro masivo por lotes, telemetría de frío en tránsito y soporte prioritario 24/7.
  - Plan Empresarial (S/ 249/mes - Para grandes flotas y corporativos): Incluye la totalidad del plan profesional, sumando módulos personalizados, SLA garantizado, gestor de cuenta dedicado y API de integración completa.
- **Organización por procesos (Flujo del Perecible):**
  - Recepción y registro de lote $\rightarrow$ Almacenamiento y telemetría  $\rightarrow$ Detección y notificación  $\rightarrow$ Despacho prioritario  $\rightarrow$ Auditoría.
- **Organización por datos (Bounded Contexts Core):**
  - Identidades y cuentas: Cuentas, usuarios, credenciales, RUC y sedes.
  - Series temporales telemétricas: Temperatura, humedad, MAC, heartbeats y estado de conectividad.
  - Inventario perecible: Lotes, fechas de caducidad y categorías.
  - Incidencias y alertas: Brechas térmicas, reglas de escalamiento, incidentes y acuses de recibo.
  - Trazabilidad: Reportes de frío y órdenes de despacho.
  - Métricas e impacto: KPIs de merma evitada, capital ahorrado y eficiencia FEFO.

### 4.2.2. Labeling Systems
El sistema implementa etiquetas estandarizadas y alineadas al menú de navegación de la plataforma y al lenguaje ubicuo:
- **Dashboard:** Centro de control general de unidades de frío y estado operativo del sistema.
- **Inventory:** Catálogo de productos, registro de lotes y fechas de caducidad.
- **Shipments:** Gestión de despachos, control de rutas, órdenes de salida y telemetría en tránsito.
- **Suppliers:** Registro de proveedores, lotes recibidos y trazabilidad de procedencia comercial.
- **Analytics:** Indicadores clave de rendimiento, merma evitada y capital ahorrado.
- **Alerts:** Centro de notificaciones, registro de incidentes térmicos, confirmación y reglas de escalamiento.
- **Planes:** Selector de tarifas (Básico, Profesional y Empresarial) y gestión de suscripciones.

### 4.2.3. SEO Tags and Meta Tags
Para optimizar el posicionamiento del portal público de captación y la verificación de certificados, se configuran las siguientes etiquetas:

- `<title>`: Refrio - Plataforma IoT de monitoreo de temperatura e inventario FEFO  
- `<meta name="description">`: Solución integral para resguardar la cadena de frío, monitorear unidades de refrigeración en tiempo real y telemetría IoT.  
- `<meta name="keywords">`: refrio, monitoreo de frio iot, telemetria temperatura, gestion inventario fefo, cadena de frio peru, control mermas perecibles, camaras frigorificas  

**Adicionalmente:**

- **Uso de encabezados semánticos:**
  - `<h1>`: Título principal de módulo o vista (ej. "Dashboard", "Planes de Suscripción").
  - `<h2>`: Subsecciones funcionales (ej. "Unidades de Frío Activas", "Lotes Críticos").
  - `<h3>`: Tarjetas de telemetría, métricas y detalles de lotes.

- **Estructura de URLs:**
  - `/dashboard`
  - `/inventory`
  - `/shipments`
  - `/suppliers`
  - `/analytics`
  - `/alerts`
  - `/planes`

### 4.2.4. Searching Systems
El sistema provee mecanismos de búsqueda ágiles para localizar rápidamente activos, lotes y estados térmicos en operaciones de alta exigencia:

- **Criterios de búsqueda directa:**
  - Identificador único de lote.
  - Código de barras o token QR del lote/pallet.
  - Dirección física o identificador del nodo sensor IoT.
  - Nombre o identificador de la unidad de frío.
  - Razón social o RUC del proveedor.

- **Filtros avanzados y segmentación:**
  - Por ventana de caducidad: En fecha crítica, por vencer (3/5/7 días), vigente.
  - Por estado térmico: Rango seguro, oscilación moderada, ruptura crítica.
  - Por categoría de alimento: Lácteos, carnes, embutidos, masas refrigeradas.
  - Por plan/sede: Filtro por almacén central, sede regional o unidad móvil en tránsito.

- **Resultados en tiempo real:** Respuestas automáticas mediante endpoints reactivos para la mitigación inmediata de incidentes.

### 4.2.5. Navigation Systems
La navegación de Refrio asegura transiciones fluidas entre la supervisión estratégica y la ejecución operativa en planta o mostrador:

- **Menú de navegación principal (Sidebar):**
  - Dashboard  
  - Inventory  
  - Shipments  
  - Suppliers  
  - Analytics  
  - Alerts  

- **Navegación contextual:**
  - Acceso directo a la ficha del lote o unidad de frío al interactuar con una alerta en el centro de notificaciones.
  - Salto directo desde el listado de inventario hacia la generación del plan de despacho con un clic.
  - Visualización del certificado de frío asociado a una orden directamente desde el módulo de Shipments.

- **Elementos de apoyo a la navegación:**
  - Breadcrumbs: Indicadores de jerarquía (ej. Inventory > Batches > Lote LOT-2026-001).
  - Botones de acción rápida: Accesos fijos para "Nuevo Lote", "Alertas" y "Cerrar sesión".

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

El wireframe establece la estructura de la página de aterrizaje en escala de grises. Se prioriza la propuesta de valor en la sección Hero, seguida de los beneficios, planes de suscripción y un formulario de contacto. Elaborado utilizando Figma.

### Wireframes Desktop de la Landing Page

**Landing Wireframe Desktop 1**

![Landing Wireframe Desktop 1](../assets/LandingDW1.png)

**Landing Wireframe Desktop 2**

![Landing Wireframe Desktop 2](../assets/LandingDW2.png)

**Landing Wireframe Desktop 3**

![Landing Wireframe Desktop 3](../assets/LandingDW3.png)

**Landing Wireframe Desktop 4**

![Landing Wireframe Desktop 4](../assets/LandingDW4.png)

**Landing Wireframe Desktop 5**

![Landing Wireframe Desktop 5](../assets/LandingDW5.png)

**Landing Wireframe Desktop 6**

![Landing Wireframe Desktop 6](../assets/LandingDW6.png)

**Landing Wireframe Desktop 7**

![Landing Wireframe Desktop 7](../assets/LandingDW7.png)

**Landing Wireframe Desktop 8**

![Landing Wireframe Desktop 8](../assets/LandingDW8.png)

**Landing Wireframe Desktop 9**

![Landing Wireframe Desktop 9](../assets/LandingDW9.png)

### Wireframes Mobile de la Landing Page

**Landing Wireframe Mobile 1**

![Landing Wireframe Mobile 1](../assets/LandingMW1.png)

**Landing Wireframe Mobile 2**

![Landing Wireframe Mobile 2](../assets/LandingMW2.png)

**Landing Wireframe Mobile 3**

![Landing Wireframe Mobile 3](../assets/LandingMW3.png)

**Landing Wireframe Mobile 4**

![Landing Wireframe Mobile 4](../assets/LandingMW4.png)

**Landing Wireframe Mobile 5**

![Landing Wireframe Mobile 5](../assets/LandingMW5.png)

**Landing Wireframe Mobile 6**

![Landing Wireframe Mobile 6](../assets/LandingMW6.png)

**Landing Wireframe Mobile 7**

![Landing Wireframe Mobile 7](../assets/LandingMW7.png)

**Landing Wireframe Mobile 8**

![Landing Wireframe Mobile 8](../assets/LandingMW8.png)

**Landing Wireframe Mobile 9**

![Landing Wireframe Mobile 9](../assets/LandingMW9.png)

**Link de figma:** [Ver en Figma](https://www.figma.com/design/Lwm01etaYmdrIBXZvc4gdc/Landing-Page---Refrio?node-id=0-1&t=2zBsZuwWfCntnQbN-1)

### 4.3.2. Landing Page Mock-up

El Mock-up de alta fidelidad integra el isotipo de Refrio, la paleta de colores oficial y tipografía Roboto con Montserrat. Se evidencia la aplicación de atributos ARIA para accesibilidad (a11y) y selectores de idioma.

### Mockups Desktop de la Landing Page

**Landing Mockup Desktop 1**

![Landing Mockup Desktop 1](../assets/LandingDM1.png)

**Landing Mockup Desktop 2**

![Landing Mockup Desktop 2](../assets/LandingDM2.png)

**Landing Mockup Desktop 3**

![Landing Mockup Desktop 3](../assets/LandingDM3.png)

**Landing Mockup Desktop 4**

![Landing Mockup Desktop 4](../assets/LandingDM4.png)

**Landing Mockup Desktop 5**

![Landing Mockup Desktop 5](../assets/LandingDM5.png)

**Landing Mockup Desktop 6**

![Landing Mockup Desktop 6](../assets/LandingDM6.png)

**Landing Mockup Desktop 7**

![Landing Mockup Desktop 7](../assets/LandingDM7.png)

**Landing Mockup Desktop 8**

![Landing Mockup Desktop 8](../assets/LandingDM8.png)

**Landing Mockup Desktop 9**

![Landing Mockup Desktop 9](../assets/LandingDM9.png)


### Mockups Mobile de la Landing Page

**Landing Mockup Mobile 1**

![Landing Mockup Mobile 1](../assets/LandingMM1.png)

**Landing Mockup Mobile 2**

![Landing Mockup Mobile 2](../assets/LandingMM2.png)

**Landing Mockup Mobile 3**

![Landing Mockup Mobile 3](../assets/LandingMM3.png)

**Landing Mockup Mobile 4**

![Landing Mockup Mobile 4](../assets/LandingMM4.png)

**Landing Mockup Mobile 5**

![Landing Mockup Mobile 5](../assets/LandingMM5.png)

**Landing Mockup Mobile 6**

![Landing Mockup Mobile 6](../assets/LandingMM6.png)

**Landing Mockup Mobile 7**

![Landing Mockup Mobile 7](../assets/LandingMM7.png)

**Landing Mockup Mobile 8**

![Landing Mockup Mobile 8](../assets/LandingMM8.png)

**Landing Mockup Mobile 9**

![Landing Mockup Mobile 9](../assets/LandingMM9.png)

**Link de figma:** [Ver en Figma](https://www.figma.com/design/Lwm01etaYmdrIBXZvc4gdc/Landing-Page---Refrio?node-id=0-1&t=2zBsZuwWfCntnQbN-1)

## 4.4. Web Applications UX/UI Design

El diseño de la aplicacion web de Refrio organiza las experiencias de los dos roles principales: Empresa distribuidora, encargado de gestionar los envíos, y bodeguero, responsable de la gestión de inventario y recepción de productos.

El trabajo registrado en Figma comprende wireframes, mockups y represtaciones de flujos. Su relación con las historias de usuario permite revisar que las interfaces respondan a las tareas del negocio y que las acciones ofrecidas sean coherentes con el rol y el estado de cada operacion.

### 4.4.1. Web Applications Wireframes

Los wireframes elaborados establecen la distribución estructural de los contenidos y controles de la aplicación Refrio. En el dashboard principal se diseñó una composición equilibrada donde el 50% del espacio superior se destina a la gráfica de tendencias de inventario y envíos junto con el desempeño térmico de los almacenes, y el 50% restante a la distribución de productos por categoría y la tabla de envíos recientes con sus lecturas de temperatura. Esta distribución cuenta con una adaptación responsiva para navegadores móviles, reorganizando los paneles en una columna fluida que conserva la información esencial, como alertas de caducidad FEFO y el estado de la cadena de frío, sin saturar la pantalla ni reducir excesivamente el tamaño de los elementos interactivos.

![Login](../assets/Refrio%20-%20Login%20(Wireframe).png)
![Register](../assets/Refrio%20-%20Registro%20(Wireframe).png)
![Reset Password](../assets/Refrio%20-%20Reset%20Password%20Paso%201%20(Wireframe).png)
![Reset Password Confirmation](../assets/Refrio%20-%20Reset%20Password%20Paso%202%20(Wireframe).png)
![Plans](../assets/Refrio%20-%20Planes%20de%20Registro%20(Wireframe).png)
![Dashboard Basic](../assets/Refrio%20-%20Dashboard%20Basic%20(Wireframe).png)
![Dashboard Professional](../assets/Dashboard%20Professional%20Wireframe.png)
![Inventory](../assets/Refrio%20-%20Inventory%20(Wireframe).png)
![Shipments](../assets/Refrio%20-%20Shipments%20(Wireframe).png)
![Suppliers](../assets/Refrio%20-%20Suppliers%20(Wireframe).png)
![Analytics](../assets/Refrio%20-%20Analytics%20(Wireframe).png)
![Alerts](../assets/Refrio%20-%20Alerts%20(Wireframe).png)
![Order history](../assets/Refrio%20-%20Order%20History%20(Wireframe).png)
![Clients](../assets/Refrio%20-%20Clients%20(Wireframe).png)
![View Product](../assets/Refrio%20-%20View%20Product%20(Wireframe).png)
![View Batch](../assets/Refrio%20-%20View%20Batch%20(Wireframe).png)
![View Shipment Professional](../assets/Refrio%20-%20View%20Shipments%20Profesional%20(Wireframe).png)
![Notification - Order](../assets/Refrio%20-%20Notification%20-_%20Pedido%20(Wireframe).png)
![Settings Basic](../assets/Refrio%20-%20Perfil%20Básico%20(Wireframe).png)
![Settings Professional](../assets/Refrio%20-%20Perfil%20Profesional%20(Wireframe).png)
![Settings Plans](../assets/Refrio%20-%20Planes%20y%20Facturación%20(Wireframe).png)
![QR Code](../assets/Refrio%20-%20My%20QR%20(Wireframe).png)
![Add Batch](../assets/Refrio%20-%20Add%20Batch%20(Wireframe).png)
![Add Product](../assets/Refrio%20-%20Add%20Product%20(Wireframe).png)
![Edit Product](../assets/Refrio%20-%20Edit%20Product%20(Wireframe).png)
![Create Shipment](../assets/Refrio%20-%20Create%20Shipment%20(Wireframe).png)
![Add Supplier](../assets/Refrio%20-%20Add%20Supplier%20(Wireframe).png)
![Add Client](../assets/Refrio%20-%20Add%20Client%20(Wireframe).png)

### 4.4.2. Web Applications Wireflow Diagrams

Los wireflows organizan la secuencia de pantallas que recorre el usuario para alcanzar un objetivo. El registro de elaboración incluye estos artefactos, cuya revisión permite relacionar las acciones del usuario con los cambios representados en las interfaces.

![Wireflow Diagram 1](../assets/Wireflow_diagram1.png)
![Wireflow Diagram 2](../assets/Wireflow_diagram2.png)
![Wireflow Diagram 3](../assets/Wireflow_diagram3.png)

### 4.4.3. Web Applications Mock-ups

Los mockups desarrollan las interfaces de Refrio con mayor detalle visual, incorporando la organización de contenidos, los controles, los estados de las operaciones de frío y los elementos de navegación para la gestión de productos perecibles. El trabajo registrado incluye el dashboard segmentado (Control Tower y panel del comerciante), el inventario con control de caducidad FEFO, el seguimiento de despachos con telemetría en tiempo real y los modales conectados para el registro de productos y lotes.

La propuesta toma como referencia un diseño basado en Material Design, compatible con la posterior implementación en Angular y Angular Material. Los mockups representan decisiones visuales y de experiencia de usuario.

La diferenciación entre roles constituye un criterio central de revisión: la empresa distribuidora dispone de acciones avanzadas de despacho, gestión masiva de lotes y supervisión térmica de flotas, mientras que el bodeguero consulta de manera simplificada sus pedidos entrantes, el estado de frescura de la carga y las alertas de vencimiento para la rotación en mostrador.

![Log in](../assets/Landing%20page%20Login.png)
![Register](../assets/Landing%20page%20Register.png)
![Reset Password](../assets/Landing%20page%20reset%20your%20password%20-%201.png)
![Reset Password Confirmation](../assets/Reset%20your%20password%20-%202.png)
![Plans](../assets/Landing%20Register%20-_%20Plans.png)
![Dashboard Basic](../assets/Dashboard%20Basic.png)
![Dashboard Professional](../assets/Dashboard%20Profesional.png)
![Inventory](../assets/Inventory.png)
![Shipments](../assets/Shipments.png)
![Suppliers](../assets/Suppliers.png)
![Analytics](../assets/Analytics.png)
![Alerts](../assets/Alerts.png)
![Order history](../assets/Order_history.png)
![Clients](../assets/Clients.png)
![View Product](../assets/View%20Product.png)
![View Batch](../assets/View%20Batch.png)
![View Shipment Professional](../assets/View%20Shipments%20Profesional.png)
![Notification - Order](../assets/Notification%20-_%20Pedido.png)
![Settings Basic](../assets/Profile%20Basic.png)
![Settings Professional](../assets/Profile%20Professional.png)
![Settings Plans](../assets/Plans.png)
![QR Code](../assets/My%20code.png)
![Add Batch](../assets/Add%20Batch.png)
![Add Product](../assets/Add%20Product.png)
![Edit Product](../assets/Edit%20Product.png)
![Create Shipment](../assets/Create%20Shipment.png)
![Add Supplier](../assets/Add%20Supplier.png)
![Add Client](../assets/Add%20Client.png)

### 4.4.4. Web Applications User Flow Diagrams

### Happy Path 1 - Comerciante (Bodeguero) - Agregar a un nuevo proveedor 

1. El comerciante ingresa a la aplicación web
2. Se dirige a la sección de proveedores (Suppliers)

3. El sistema muestra:
    - Nombre de los proveedores existentes
    - Categoría de productos que suministran
    - Cantidad de pedidos realizados
    - Los botones de acción: "Agregar proveedor" y "Escanear QR de proveedor"

4. El comerciante hace clic en "Agregar proveedor"
5. El sistema despliega un formulario para registrar un nuevo proveedor, solicitando:
    - Código único del proveedor
    - Espacio para escribir alguna observación adicional

6. El comerciante completa los campos requeridos y hace clic en "Añadir proveedor"
7. El sistema registra el nuevo proveedor y lo muestra en la lista de proveedores.

![Happy Path 1](../assets/UserFlows1.png)

### Happy Path 2 - Comerciante (Bodeguero) - Agregar un nuevo lote de producto

1. El comerciante ingresa a la aplicación web
2. Se dirige a la sección de inventario (Inventory)
3. El sistema muestra:
    - Lista de productos organizados por categoría
    - Prodcuctos que expirarán pronto
    - Todos los productos disponibles registrados en el inventario
    - Botón de acción: "Agregar lote" y "Escanear QR de lote"

4. El comerciante hace clic en "Agregar lote"
5. El sistema despliega un formulario para registrar un nuevo lote, solicitando:
    - Nombre del producto
    - Código único del lote
    - Cantidad
    - Día de recepción
    - Fecha de caducidad
    - Proveedor

6. El comerciante completa los campos requeridos y hace clic en "Añadir lote"
7. El sistema registra el nuevo lote y lo muestra en la lista de inventario.
8. El sistema lo redirige al producto con los otros lotes registrados.
9. El comerciante ingresa al lote creado y puede visualizar toda la información.

![Happy Path 2](../assets/UserFlows2.png)

### Happy Path 3 - Empresa distribuidora - Registrar un nuevo envío

1. La persona encargada de la logística en la empresa distribuidora ingresa a la aplicación web
2. Se dirige a la sección de envíos (Shipments)
3. El sistema muestra:
    - Unas tarjetas con información resumida de cada envío
    - Mapa con la ubicación de los envíos en tránsito
    - Todos los envíos realizados, pendientes y en tránsito
    - Botón de acción: "Crear nuevo envío" y "Ver todas las rutas"

4. La persona encargada hace clic en "Crear nuevo envío"
5. El sistema despliega un formulario para registrar un nuevo envío, solicitando:
    - Nombre del producto
    - Código único del lote
    - Lugar de origen
    - Lugar de destino
    - Tempertura de transporte requerida
    - Tiempo estimado de entrega

6. La persona encargada completa los campos requeridos y hace clic en "Crear envío"
7. El sistema registra el nuevo envío y lo muestra en la lista de envíos, actualizando el mapa con la nueva ruta.
8. Ingresa al envío creado y puede visualizar toda la información del envío, incluyendo la temperatura de la carga, el conductor y el estado del envío,el detalle del producto y el progreso del envío en vivo.

![Happy Path 3](../assets/UserFlows3.png)

### Unhappy Path - Comerciante (Bodeguero) - Rechazar un lote de producto por alguna incidencia

1. El comerciante se encuentra en su tienda y recibe una notificación de que un lote de producto ha llegado con una incidencia (por ejemplo, temperatura fuera del rango seguro).
2. Entonces, el comerciante abre la aplicación web y se dirige a la sección de notificaciones o "Historial de pedidos".
3. El sistema muestra los pedidos realizados anteriormente y el pedido con la incidencia resaltado con los datos de:
    - Código del pedido
    - Fecha/hora de entrega
    - Mercadería
    - Proveedor
    - Monto 
    - Estado del pedido
4. El comerciante ingresa al detalle del pedido con la incidencia y presiona "¿El producto llegó caliente o con daño? Reportar incidencia / Rechazar carga".

5. El sistema actualiza ese pedido como "Rechazado".

![Unhappy Path](../assets/UserFlows4.png)

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture

Refrio adopta el enfoque de Domain-Driven Design (DDD) con el propósito de alinear estrechamente la arquitectura de software con los desafíos operativos de la cadena de frío y el control de inventarios perecibles en el Perú. El sistema se organiza modularmente en 7 Bounded Contexts principales:

| Bounded Context | Descripción |
| :--- | :--- |
| **BC 01: IAM (Identity & Access Management)** | Gestión integral de autenticación (JWT), control de accesos basado en roles (Supervisor, Operario, Minorista) y administración de sedes y planes de suscripción (Básico, Profesional y Empresarial). |
| **BC 02: Storage & Device Telemetry Context** | Ingesta de alta frecuencia de series temporales de temperatura y humedad, monitoreo de heartbeats, calibración técnica (offsets) y control de cámaras frigoríficas, visicoolers y telemetría en tránsito. |
| **BC 03: Inventory & FEFO Dispatch Context** | Núcleo de gestión de inventario perecible: catalogación, fechas de caducidad, auditoría nocturna de vencimientos y generación de planes de picking según la política First-Expired, First-Out. |
| **BC 04: Alerting & Incident Management Context** | Evaluación de desviaciones térmicas y caducidades críticas contra umbrales seguros, despacho de notificaciones multicanal (WhatsApp, Push, SMS), escalamiento jerárquico y cierre justificado de incidentes. |
| **BC 05: Cold Chain Traceability & Certification Context** | Consolidación del historial térmico continuo de lotes almacenados o despachados, generación de certificados de frío en PDF con firma digital, verificación pública vía QR y registro contable de mermas. |
| **BC 06: Analytics & Business Impact Context** | Procesamiento analítico de mermas evitadas, capital salvado en soles, eficiencia de rotación FEFO, modelos de IA predictivos para fallas en compresores y exportación de datasets. |
| **BC 07: Customer Acquisition & Public Portal Context** | Plataforma pública de captación comercial (Landing Page), tarificador de planes de suscripción, formularios para leads B2B y portal de verificación pública de certificados de frío. |

---

### 4.6.1. Design-Level EventStorming
A través de la sesión de EventStorming a nivel de diseño, se modelaron los comandos, agregados, políticas de negocio y eventos de dominio que integran los 7 Bounded Contexts, asegurando una arquitectura reactiva orientada a eventos para erradicar las mermas por ruptura térmica y falta de rotación oportuna.

A continuación, se detalla la matriz de interdependencias e integración entre los módulos del sistema:

| Origen (Evento) | Destino (Comando) | Descripción |
| :--- | :--- | :--- |
| **IAM:** SubscriptionPlanAssigned | **Storage & Telemetry:** Enforce Device Quotas | Configura los límites operativos según el plan contratado (hasta 3 congeladoras en Básico, hasta 25 en Pro, ilimitadas en Empresarial). |
| **Storage & Telemetry:** ColdBreachDetected | **Alerting:** Trigger Thermal Breach Incident | La detección de temperaturas fuera del umbral seguro por más de 15 minutos inicializa un incidente crítico en el centro de alertas. |
| **Storage & Telemetry:** SensorOfflineDetected | **Alerting:** Trigger Offline Emergency Protocol | La pérdida de comunicación telemétrica por más de 10 minutos activa la alerta por posible corte de suministro eléctrico. |
| **Inventory & FEFO:** BatchCriticalExpirationDetected | **Alerting:** Broadcast Expiration Warning | La rutina nocturna de auditoría de caducidades dispara avisos preventivos a la app móvil y canales configurados. |
| **Inventory & FEFO:** BatchDispatched | **Cold Chain Traceability:** Consolidate Thermal Journey | La confirmación de salida de un lote inicia la consolidación de toda su historia térmica registrada para la emisión de su certificado. |
| **Alerting:** IncidentResolved | **Alerting:** Acknowledge Incident | Registra de forma obligatoria la causa y la acción correctiva realizada por el operario para detener el escalamiento automático. |
| **Cold Chain Traceability:** ShrinkageLogged | **Analytics:** Ingest Operational Historical Data | Alimenta los modelos analíticos y paneles ejecutivos con los costos y kilogramos de productos dados de baja. |

---

#### Diagrama General — Event Storming Design Level

El siguiente diagrama presenta la visión integral de los 7 Bounded Contexts del sistema Refrio, ilustrando el flujo cronológico de comandos, agregados, políticas y eventos de dominio, así como las líneas de integración desacopladas que conectan la telemetría IoT, la gestión FEFO y las alertas críticas.

![Event Storming General](../assets/00-general-event-storming.png)

---

#### BC1 — IAM (Identity & Access Management)

Este Bounded Context gestiona el ciclo de vida de las cuentas y credenciales corporativas. Los agregados Account, Session y Subscription procesan comandos como `RegisterCompany`, `LoginWithCredentials` y `SelectSubscriptionTier`, emitiendo eventos como `CompanyAccountRegistered`, `UserLoggedIn` y `SubscriptionPlanAssigned`. Aplica políticas estrictas de validación de formato de RUC (11 dígitos), unicidad de correo y asignación de cuotas según la tarifa seleccionada.

![Event Storming IAM](../assets/01-iam-event-storming.png)

---

#### BC2 — Storage & Device Telemetry Context

Administra los nodos sensores IoT, la ingesta de telemetría y el estado operativo de cámaras frigoríficas, visicoolers y transporte refrigerado. Los agregados ColdRoom, SensorNode y Telemetry procesan comandos como `PairSensorNode`, `CalibrateSensorOffset` e `IngestThermalMetricStream`, emitiendo eventos como `SensorNodePaired`, `ThermalMetricRecorded` y `SensorOfflineDetected`.

![Event Storming Storage Telemetry](../assets/02-storage-telemetry-event-storming.png)

##### Detalle de Procesamiento: Telemetría, Evaluación Térmica y Salud del Enlace
A continuación se detalla la arquitectura de ingestión paralela del contexto, organizada en 3 carriles operativos donde se evalúan concurrentemente los rangos seguros de temperatura y humedad, la degradación de vida útil del perecible y el pulso de conectividad del hardware:

![Event Storming Monitoring and Telemetry Detail](../assets/04-1-monitoring-telemetry-detail.png)

---

#### BC3 — Inventory & FEFO Dispatch Operations Context

Núcleo operativo encargado de gestionar la vida útil de los productos perecibles[cite: 1]. Los agregados Batch, FoodCategory y PickingPlan procesan comandos como `RegisterBatchIntake`, `AuditExpirationWindows` y `GenerateFEFOPickingPlan`, emitiendo eventos clave como `BatchIntakeRecorded`, `BatchCriticalExpirationDetected` y `BatchDispatched`. El algoritmo FEFO asegura que las órdenes de picking prioricen automáticamente los lotes más antiguos antes de permitir la validación de salida.

![Event Storming Inventory FEFO](../assets/03-inventory-fefo-event-storming.png)

---

#### BC4 — Incident, Alert & Audit Management Context

Centraliza la respuesta operativa ante contingencias térmicas o riesgos de caducidad. Los agregados Incident, Notification y Escalation procesan comandos como `TriggerThermalBreachIncident`, `AcknowledgeIncident` y `EscalateUnresolvedAlert`. Al generarse `ColdBreachDetected`, despacha alertas urgentes vía WhatsApp Cloud API, Firebase Push y SMS, exigiendo el registro de una acción correctiva justificada para archivar el incidente.

![Event Storming Incident Alert](../assets/04-incident-alert-event-storming.png)

---

#### BC5 — Cold Chain Traceability & Certification Context

Garantiza la inalterabilidad de los registros de frío y formaliza las bajas técnicas. Los agregados Traceability, ColdCertificate y ShrinkageRecord procesan comandos como `ConsolidateThermalJourney`, `GenerateColdCertificate` y `RecordFormalShrinkage`, emitiendo eventos como `ThermalHistoryConsolidated`, `ColdCertificateGenerated` y `ShrinkageLogged`.

![Event Storming Cold Chain Traceability](../assets/05-traceability-certification-event-storming.png)

---

#### BC6 — Analytics & Business Impact Context

Procesa las métricas operativas y económicas para la toma de decisiones gerenciales. Los agregados Analytics, PredictionEngine y ExportJob procesan comandos como `AggregateBusinessMetrics`, `RunPredictiveCompressorModel` y `RequestDatasetExport`, emitiendo eventos como `BusinessMetricsCalculated` y `CompressorFailureRiskPredicted`.

![Event Storming Analytics Impact](../assets/06-analytics-impact-event-storming.png)

---

#### BC7 — Customer Acquisition & Public Portal Context

Gestiona el punto de contacto inicial con el mercado y la validación abierta de certificados. Los agregados Lead, PricingPlan y PublicVerification procesan comandos como `SubmitCommercialDemoForm`, `SelectPricingPlan` y `ScanCertificateQR`, emitiendo eventos como `LeadSubmitted` y `PublicCertificateVerified`.

![Event Storming Customer Acquisition](../assets/07-customer-acquisition-event-storming.png)

---

Para visualizar el EventStorming original y navegar por el detalle de cada Bounded Context:
[Visualizar EventStorming en Miro](https://miro.com/app/board/uXjVHn63Wg4=/?share_link_id=370048675014)

### 4.6.2. Software Architecture Context Level Diagram

En esta sección se presenta el diagrama de contexto correspondiente al Nivel 1 del Modelo C4 para Refrio. El propósito de este nivel es ilustrar el sistema central en el centro de su ecosistema operativo, delimitando las fronteras del software e identificando claramente a los actores humanos y los sistemas externos con los cuales interactúa a través de protocolos seguros sobre la red.

El ecosistema está liderado por dos perfiles de usuario fundamentales: el Supervisor Logístico (quien administra las cámaras frigoríficas, supervisa las existencias perecibles y programa los despachos bajo política FEFO en distribuidoras medianas) y la Comerciante Minorista (propietaria o administradora de bodega o puesto de mercado que gestiona la refrigeración comercial de vitrinas, controla fechas de caducidad y activa promociones de remate preventivo). Para garantizar la integridad ininterrumpida de la cadena de frío y una supervisión reactiva en tiempo real, Refrio se integra con cinco plataformas externas clave: MQTT Broker / IoT Gateway para la ingesta continua de series telemétricas (temperatura y humedad) transmitidas por nodos sensores (ESP32/DHT22); Firebase Cloud Messaging (FCM) para el despacho inmediato de notificaciones push en tiempo real ante eventos críticos; WhatsApp Cloud API para la transmisión directa de alertas urgentes de ruptura térmica al teléfono de los encargados; SendGrid para el envío de correos transaccionales, reportes periódicos y certificados de trazabilidad en PDF; y una Pasarela de Pagos (Payment Gateway) para la gestión y procesamiento recurrente de las suscripciones a los planes comerciales de la plataforma (Básico, Profesional y Empresarial).

<p align="center">
  <img src="../assets/SystemContext-Refrio.png" title="System Context Diagram - Refrio" width="1000">
</p>
<p align="center">
  <em>Nota.</em> Diagrama de Contexto del Sistema elaborado con Structurizr aplicando el Modelo C4.
</p>

---

### 4.6.3. Software Architecture Container Level Diagrams

A continuación, se detalla el diagrama de contenedores (Nivel 2 del Modelo C4), el cual realiza un acercamiento a la frontera del sistema Refrio para exponer sus unidades de ejecución y despliegue independientes, sus responsabilidades primarias y las decisiones tecnológicas seleccionadas para cada componente de software.

La arquitectura de ejecución se descompone en contenedores especializados:
1. **Web Application (Static Web Hosting / Web Server):** Responsable de servir el Landing Page corporativo con la presentación de la propuesta de valor, el catálogo de planes de suscripción y entregar los paquetes optimizados de la aplicación cliente hacia los navegadores web.
2. **Single-Page Application (SPA):** Desarrollada con React y TypeScript, provee una interfaz de usuario reactiva para dashboards de telemetría térmica en vivo, administración del catálogo de lotes perecibles, planificación de despachos FEFO y reportes analíticos de merma en entornos de escritorio y estaciones de supervisión en andén.
3. **Mobile Web App:** Versión adaptada en formato PWA para dispositivos móviles, optimizada para comerciantes de bodegas y operarios de almacén que requieren escanear rápidamente fechas de caducidad, visualizar el semáforo de frescura de stock y recibir alertas sonoras inmediatas.
4. **Backend API:** Núcleo desarrollado en ASP.NET Core / Node.js bajo un diseño modular alineado a Domain-Driven Design (DDD), encargado de procesar peticiones RESTful protegidas mediante tokens JWT, ejecutar las políticas de rotación FEFO, evaluar reglas de infracción térmica y orquestar eventos de dominio.
5. **Database:** Base de datos relacional y de series temporales sobre PostgreSQL / TimescaleDB, encargada de persistir de forma estructurada los registros de usuarios, empresas, unidades de almacenamiento frigorífico, existencias de lotes y el flujo masivo de mediciones telemétricas bajo garantías de integridad transaccional (ACID).

<p align="center">
  <img src="../assets/Containers-Refrio.png" title="Container Diagram - Refrio" width="1000">
</p>
<p align="center">
  <em>Nota.</em> Diagrama de Contenedores elaborado con Structurizr aplicando el Modelo C4.
</p>

---

### 4.6.4. Software Architecture Component Level Diagrams

Este diagrama de componentes (Nivel 3 del Modelo C4) descompone internamente el contenedor del Backend API, reflejando cómo se estructura la lógica del servidor a través de una arquitectura modular basada en los Bounded Contexts identificados durante las fases de needfinding y EventStorming.

El diseño interno organiza la solución en módulos de dominio cohesivos y desacoplados:
* **IAM Module (Identity & Access Management):** Procesa el registro de cuentas (diferenciando flujos fiscales con RUC para distribuidoras y altas ágiles para bodegas), autenticación con firma de tokens JWT, control de roles (Supervisor, Operario, Minorista) y verificación de cuotas operativas según el plan de suscripción contratado (Básico, Profesional o Empresarial).
* **Storage & Telemetry Module:** Ingesta y procesa métricas telemétricas de temperatura y humedad en tiempo real, administra el emparejamiento y calibración técnica (offsets) de sensores IoT, monitorea el pulso de conectividad (heartbeat) y controla tanto cámaras fijas como unidades de frío en tránsito.
* **Inventory & FEFO Module:** Administra el catálogo de alimentos perecibles, la vinculación con proveedores, el registro de lotes (Batches) y sus fechas críticas de expiración, ejecutando el algoritmo de priorización FEFO para emitir planes de picking sugeridos y guiar la rotación en mostrador o andén.
* **Incident & Alert Module:** Evalúa las desviaciones térmicas y las ventanas críticas de caducidad contra políticas de tolerancia, coordina la difusión de alertas multicanal (WhatsApp, FCM, SMS), gestiona el escalamiento jerárquico automatizado y audita el cierre formal de incidentes con justificación obligatoria.
* **Cold Chain Traceability Module:** Consolida el historial térmico inalterable de cada lote durante su permanencia en cámara o furgón de despacho, genera certificados de frío auditables en formato PDF con firma digital y expone la validación pública mediante códigos QR.
* **Analytics & IA Module:** Calcula KPIs de negocio consolidados (soles ahorrados, volumen de merma evitada, porcentaje de reducción de desperdicio) y ejecuta modelos analíticos predictivos para anticipar fallas en compresores e identificar patrones de riesgo térmico.
* **Shared Module:** Provee abstracciones transversales, bus interno de eventos de dominio, formateadores de datos, manejo global de excepciones y utilitarios comunes de persistencia y logging para todos los módulos del backend.

<p align="center">
  <img src="../assets/Components-Refrio.png" title="Component Diagram - Refrio Backend API" width="1000">
</p>
<p align="center">
  <em>Nota.</em> Diagrama de Componentes del Backend API elaborado con Structurizr aplicando el Modelo C4 y Domain-Driven Design.
</p>

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

## 4.8. Database Design

### 4.8.1. Database Diagrams
