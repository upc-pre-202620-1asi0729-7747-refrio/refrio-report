# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

**Refrio** es una startup tecnológica peruana dedicada al diseño y desarrollo de soluciones digitales innovadoras para la gestión de inventario, el monitoreo de temperatura y la distribución eficiente de productos perecibles. La empresa nace con la firme convicción de que la tecnología y el Internet de las Cosas (IoT) pueden convertirse en herramientas clave para reducir pérdidas económicas, evitar el desperdicio de alimentos y asegurar la trazabilidad en la cadena de frío.

Este propósito responde a una problemática crítica en el contexto nacional: cada año se pierden o desechan en el Perú aproximadamente 12.8 millones de toneladas de alimentos, lo que equivale al 47.76% de la producción total del país (Ministerio de Desarrollo Agrario y Riego [MIDAGRI], 2022). Para hacer frente a este desafío, **Refrio** trabaja bajo un enfoque centrado en el usuario para lograr una gestión de stock automatizada, predictiva y en tiempo real. Al integrar alertas inteligentes de vencimiento y telemetría de temperatura constante, la plataforma ayuda a empresas distribuidoras y comerciantes locales a optimizar la rotación del inventario mediante políticas FEFO (*First Expired, First Out*).

La relevancia de esta propuesta radica en que la implementación de un sistema de gestión de almacenes digitalizado no solo permite reducir los costos operativos, sino que optimiza significativamente la organización y la eficiencia de todos los procesos logísticos implicados (Ñiquén & Ríos, 2024). Asimismo, una adecuada administración de las operaciones logísticas y de distribución es fundamental para mejorar el rendimiento empresarial global, reducir pérdidas y garantizar un servicio de alta calidad para el cliente (Heizer & Render, 2020).

**Misión:** Optimizar la gestión de inventarios y salvaguardar la cadena de frío de productos perecibles mediante soluciones tecnológicas eficientes, accesibles y confiables.

**Visión:** Ser la plataforma líder en el monitoreo inteligente de temperatura y distribución de productos perecibles a nivel nacional.


### 1.1.2. Perfiles de integrantes del equipo

| Foto | Descripción |
|:---:|:---|
| <img src="../assets/Alca Morán, César Alejandro - U20241F027 - Profile.jpg" alt="Foto" width="120"> | **Alca Morán, César Alejandro - U20241F027**<br>Soy estudiante de Ingeniería de Software. Aporto conocimientos en desarrollo web, programación y capacidad para trabajar en equipo. Me considero una persona responsable, proactiva y comprometida con el aprendizaje continuo y el crecimiento profesional.|
| <img src="../assets/Centeno León, Adriano Samir - U20241D920 - Profile.jpg" alt="Foto" width="120"> | **Centeno León, Adriano Samir - U20241D920**<br>Estudiante de la carrera de Ingeniería de Software con conocimientos en programación, bases de datos y gestión de proyectos mediante Github. Referente a la gestión de trabajos en equipo, me gusta mantenerme organizado y cumplir con los plazos establecidos. |
| <img src="../assets/Rivas Méndez, Bernie Aarón - U20241F109 - Profile.PNG" alt="Foto" width="120"> | **Rivas Méndez, Bernie Aarón - U20241F109**<br>Soy un estudiante de la carrera de Ingeniería de Software y curso el 5to ciclo de la carrera. En cuanto a los trabajos me gusta revisar y que estén completos a la hora de entregarlos. En cuanto a la programación me gusta ser ordenado y que tenga lógica, por lo cual prefiero programar el BackEnd, pero también hago el FrontEnd.|
| <img src="../assets/Saavedra Flores, Rodrigo - U20241D811 - Profile.png" width="120"> | **Saavedra Flores, Rodrigo Andree - U20241D811**<br>Soy estudiante de Ingeniería de Software. Aporto conocimientos en desarrollo backend, diseño de bases de datos y control de versiones con Git. En cuanto al trabajo en equipo, me caracterizo por mi buena comunicación, resolución rápida de problemas y compromiso para cumplir con los entregables en las fechas establecidas. |
| <img src="../assets/Tello Lima, Jose Alejandro - U202421618 - Profile.png" alt="Foto" width="120"> | **Tello Lima, Jose Alejandro - U202421618**<br>Soy estudiante de Ingeniería de Software. Aporto conocimientos en diseño de experiencias de usuario, interfaces web responsivas y mapeo de trayectorias utilizando herramientas como Figma y UXPressia, asegurando que la plataforma sea altamente intuitiva para el cliente. |

## 1.2. Solution Profile

La sección **Solution Profile** describe la base estratégica de la solución tecnológica **Refrio**. A través de este perfil, se identifican las raíces del problema mediante un análisis riguroso y se aplica el marco de trabajo *Lean UX* para definir las hipótesis, suposiciones y el Canvas del producto. El objetivo principal es alinear el desarrollo de software con las necesidades de negocio y los dolores de los usuarios finales en el sector de la cadena de frío.

### 1.2.1. Antecedentes y problemática
**Contexto y desarrollo de la problemática**

En los últimos años, el mercado de distribución de alimentos perecibles —como lácteos, carnes y embutidos— ha experimentado un crecimiento sostenido en el Perú, lo que exige estándares cada vez más rigurosos para garantizar la inocuidad y calidad de los productos. Según el Instituto Nacional de Estadística e Informática (INEI, 2023), el Perú cuenta con más de 427,000 bodegas y puestos de mercado registrados, de los cuales el 68% comercializa productos perecibles de forma habitual. Sin embargo, la cadena de suministro y la logística de frío enfrentan desafíos estructurales y operativos críticos: históricamente, las pequeñas y medianas empresas (pymes) distribuidoras, así como los comercializadores mayoristas y minoristas, han gestionado sus operaciones basándose en procesos manuales, registros en papel o herramientas ofimáticas básicas como hojas de cálculo desconectadas.

Esta carencia de digitalización y automatización es el origen de una problemática central: la gestión ineficiente de los inventarios perecibles y la vulnerabilidad de la cadena de frío. Al no contar con visibilidad del stock en tiempo real ni telemetría que monitoree las condiciones ambientales, las empresas sufren de "puntos ciegos" durante el almacenamiento temporal y, sobre todo, durante el transporte terrestre. Las fluctuaciones térmicas no detectadas y la imposibilidad de aplicar rigurosamente políticas de rotación de inventario —como el método FEFO (*First Expired, First Out*)— provocan el deterioro prematuro de la mercadería.

El impacto de estas deficiencias es severo en múltiples niveles. A nivel macroeconómico y social, el problema es alarmante: en el Perú se pierden o desechan anualmente alrededor de 12.8 millones de toneladas de alimentos, lo que equivale al 47.76% de la producción total del país, siendo las fallas logísticas en la cadena de frío una de las causas principales (Ministerio de Desarrollo Agrario y Riego [MIDAGRI], 2022). A nivel microeconómico, las empresas enfrentan mermas excesivas por productos caducados, quiebres de stock en los puntos de venta, un incremento drástico en los costos operativos —reposición, desecho, horas-hombre en auditorías manuales— y devoluciones constantes, lo que erosiona la rentabilidad del negocio y la confianza del consumidor final. Un estudio del diario *Gestión* (2023) señala que las distribuidoras medianas del sector alimentos en Lima Metropolitana pierden entre el 12% y el 20% de su facturación anual por causas directamente vinculadas a fallas en el control de temperatura y en la gestión del inventario.

**Análisis de la problemática (Técnica 5W2H)**

Para dimensionar, estructurar y abordar de manera sistémica este problema, se aplica la técnica de las cinco 'W's y dos 'H's:

**Who? (¿Quiénes?):**
*   Los actores directamente afectados son los jefes de almacén y supervisores logísticos de distribuidoras medianas de alimentos perecibles, quienes no cuentan con herramientas de monitoreo en tiempo real y deben gestionar el control de temperatura de manera manual; los propietarios y administradores de bodegas y puestos en mercados de abastos que comercializan lácteos, carnes, frutas y verduras sin ningún sistema formal de control de vencimientos; y el consumidor final, quien asume el riesgo sanitario de adquirir productos que han perdido su cadena de frío sin que el comerciante lo advierta.

**What? (¿Qué?):**
*   El problema central es la pérdida económica y sanitaria derivada de la ruptura de la cadena de frío por ausencia de monitoreo continuo de temperatura en almacenes y unidades de transporte; la caducidad no detectada a tiempo de productos perecibles por falta de sistemas de alerta de vencimiento; y la rotación ineficiente del inventario, que provoca tanto mermas por vencimiento como desabastecimiento de productos con alta demanda. La carencia de integración entre el control de temperatura y la gestión del inventario agrava ambos problemas de forma simultánea.

**Where? (¿Dónde?):**
*   El problema ocurre a lo largo de toda la cadena de distribución: en los almacenes refrigerados de las distribuidoras, en las unidades de transporte frigorífico durante el trayecto a los puntos de venta, y en los establecimientos de venta al público —bodegas y mercados de abastos—, principalmente en Lima Metropolitana y ciudades intermedias como Arequipa, Trujillo y Piura, donde la infraestructura de la cadena de frío es más deficiente.

**When? (¿Cuándo?):**
*   Los incidentes de temperatura fuera de rango se producen con mayor probabilidad en dos momentos críticos: fuera del horario laboral, cuando no hay personal que realice revisiones físicas —lo que implica que un fallo en la madrugada puede arruinar un almacén completo antes de ser detectado al día siguiente—; y durante picos de temperatura ambiental (diciembre–marzo en Lima), cuando la demanda sobre los sistemas de refrigeración es mayor. Las mermas y caducidades, por su parte, se descubren típicamente durante el inventario físico semanal o mensual, es decir, cuando la pérdida ya es irrecuperable.

**Why? (¿Por qué?):**
*   El control logístico en este sector sigue siendo mayoritariamente reactivo porque las herramientas tecnológicas de monitoreo IoT han sido históricamente costosas e inaccesibles para pymes; no existía en el mercado peruano una solución integrada que combinara el monitoreo de temperatura e inventario FEFO (*First Expired, First Out*) en un solo producto orientado a este segmento (vacío que **Refrio** busca cubrir); y existe una baja cultura de digitalización entre los operadores del sector, quienes desconfían de la tecnología si no perciben un retorno de inversión inmediato y tangible (Comisión de Promoción del Perú para la Exportación y el Turismo [PROMPERÚ], 2022).

**How? (¿Cómo?):**
*   La ineficiencia operativa se manifiesta en pérdidas económicas directas —productos que deben descartarse—, pérdidas indirectas —horas-hombre invertidas en auditorías físicas manuales y procesos de doble digitación—, devoluciones de clientes por productos en mal estado, y costos de imagen y confianza que impactan la fidelización de clientes B2B. Una ruptura térmica durante el transporte puede inutilizar un cargamento completo y desencadenar un proceso de cuarentena y desecho que paraliza la operación durante horas.

**How Much? (¿Cuánto?):**
*   Según el Ministerio de Desarrollo Agrario y Riego (MIDAGRI, 2022), el Perú pierde anualmente 12.8 millones de toneladas de alimentos, equivalentes al 47.76% de la producción total. Para una distribuidora mediana de Lima Metropolitana, las mermas representan entre el 12% y el 20% de la facturación anual (diario *Gestión*, 2023). En el caso de bodegas pequeñas, las pérdidas mensuales por vencimiento oscilan entre S/ 150 y S/ 400, según los datos recopilados en las entrevistas de este proyecto. A nivel del tiempo invertido, se estima que los supervisores de almacén dedican entre 1.5 y 3 horas diarias a tareas de verificación manual de temperatura e inventario, tiempo que una solución automatizada como **Refrio** podría reducir en un 80%.

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

The current state of **cold-chain management and perishable inventory tracking in Peru** has focused mainly on **manual verification processes, disconnected spreadsheets, and basic local thermometer checks**, primarily used by mid-size food distributors and small retail store owners (*bodegueros*). These actors still rely on periodic physical inspections and paper logs to monitor product temperatures and expiry dates, with no real-time visibility or automated alerting.

What existing products and services fail to address is **an affordable, integrated solution that simultaneously combines real-time IoT-based temperature monitoring with intelligent expiry-date alerting and FEFO-based inventory rotation, designed specifically for the operational reality and budget constraints of Peruvian SMEs in the perishable food distribution sector**. Currently available alternatives are either too expensive and hardware-intensive for large enterprises, or too generic without specialization in perishable goods.

Our product, **Refrio**, will address this gap by **offering a web platform that consolidates IoT-based temperature telemetry, automated near-expiry alerts, FEFO stock rotation logic, multi-location inventory dashboards, and exportable analytics reports into a single, intuitive and mobile-responsive interface, accessible without requiring specialized or proprietary hardware investment**.

Our initial focus will be on **mid-size perishable goods distributors operating one or more refrigerated warehouses in Lima Metropolitana, and small retail store owners (*bodegueros*) who manage daily perishable stock without formal inventory systems, both characterized by low to moderate technology adoption and a high tolerance for direct economic pain caused by waste and cold-chain failure**.

We will know we are successful when we see **a measurable reduction of at least 30% in product losses due to temperature breaches or expiry among active users, a daily active usage rate of 70% or above within 60 days of onboarding, and a Net Promoter Score (NPS) above 40 within the first 6 months of commercial operation**.


#### 1.2.2.2. Lean UX Assumptions

Las suposiciones representan las creencias fundamentales de nuestro equipo de desarrollo con respecto a la viabilidad comercial, las necesidades de los usuarios y las características tecnológicas de la plataforma **Refrio**. Estas declaraciones de creencia sirven como base directa para la posterior formulación de nuestras hipótesis de trabajo.

**A. Business Assumptions**
1. Creemos que existe un mercado viable y desatendido de empresas distribuidoras de alimentos perecibles de mediana escala en el Perú que están dispuestas a pagar una suscripción mensual recurrente por una plataforma integrada de monitoreo de temperatura y gestión de inventario.
2. Creemos que el modelo de negocio *SaaS* (*Software as a Service*) con planes escalonados —básico, estándar y premium— es financieramente sostenible y permite atender simultáneamente a los dos segmentos objetivo con diferentes niveles de funcionalidad y precio.
3. Creemos que la principal barrera de adopción tecnológica en el segmento de bodegas es el precio mensual: ofrecer un plan de entrada por debajo de S/ 60 al mes incrementará significativamente la tasa de conversión en este segmento.
4. Creemos que la compatibilidad con sensores IoT (*Internet of Things*) de bajo costo ya disponibles en el mercado local —sin necesidad de hardware propietario— eliminará la barrera de inversión inicial y acelerará la adopción en el segmento de distribuidoras medianas.
5. Creemos que alianzas estratégicas con gremios del sector alimentario peruano —como la Asociación de Bodegueros del Perú (ABP) y asociaciones de distribuidoras de alimentos— ampliarán el alcance comercial de **Refrio** y reducirán el costo de adquisición de clientes (*CAC*).

**B. Business Outcome Assumptions**
1. Creemos que lograremos 200 empresas o negocios suscritos —entre distribuidoras y bodegas— en los primeros 8 meses de operación comercial.
2. Creemos que una tasa de retención mensual superior al 85% entre los usuarios activos validará la propuesta de valor de la plataforma y la satisfacción del cliente.
3. Creemos que el costo de adquisición de clientes (*CAC*) disminuirá un 20% a partir del sexto mes de operación gracias al efecto de referidos orgánicos entre distribuidores del mismo rubro.
4. Creemos que el ingreso mensual recurrente (*MRR*) superará los S/ 20,000 al finalizar el primer año de operación, sustentado en actualizaciones de plan (*upgrades*) motivadas por el valor percibido.

**C. User Assumptions**
1. Creemos que los usuarios primarios del Segmento 1 son jefes de almacén y supervisores logísticos de distribuidoras de alimentos perecibles, con edades entre 28 y 50 años, con educación técnica o universitaria en logística o administración, y con acceso a computadoras de escritorio y teléfonos inteligentes (*smartphones*) Android en su entorno laboral.
2. Creemos que los usuarios primarios del Segmento 2 son propietarios o administradores de bodegas de barrio o puestos en mercados de abastos, con edades entre 30 y 60 años, con nivel educativo de secundaria o técnico básico, y que utilizan principalmente teléfonos inteligentes (*smartphones*) Android de gama media para todas sus actividades digitales.
3. Creemos que ambos segmentos utilizan WhatsApp como canal principal de comunicación laboral y digital, lo que lo convierte en un canal crítico para el envío de notificaciones automáticas de la plataforma.
4. Creemos que los usuarios del Segmento 1 tienen mayor tolerancia y disposición a adoptar tecnología si se les demuestra un retorno de inversión (*ROI*) claro, mientras que los usuarios del Segmento 2 necesitan una interfaz extremadamente simple, en español, con un proceso de inducción (*onboarding*) guiado y soporte constante.

**D. User Outcome and Benefit Assumptions**
1. Creemos que los supervisores de almacén del Segmento 1 desean recuperar al menos 2 horas diarias actualmente destinadas a la verificación manual de temperatura e inventario, para redirigirlas a tareas de mayor valor logístico.
2. Creemos que los jefes logísticos del Segmento 1 desean obtener visibilidad en tiempo real del estado de su inventario y sus cámaras frigoríficas desde cualquier dispositivo, incluso fuera del horario laboral, para responder ante incidentes térmicos antes de que generen pérdidas económicas.
3. Creemos que los propietarios de bodegas del Segmento 2 desean recibir alertas anticipadas —al menos 7 días antes del vencimiento— que les permitan aplicar estrategias de promoción o ajustar pedidos futuros, evitando el desecho físico de productos y recuperando entre S/ 100 y S/ 300 mensuales de pérdidas actuales.
4. Creemos que ambos segmentos de usuarios valoran la generación automática de reportes de mermas porque les permite justificar pérdidas ante proveedores, clientes o gerencias con datos objetivos y auditables en lugar de estimaciones.

**E. Feature Assumptions**
1. Creemos que un **panel de control interactivo (*dashboard*) de monitoreo de temperatura en tiempo real** con alertas configurables por umbral reducirá los incidentes de ruptura de cadena de frío al permitir una respuesta preventiva e inmediata.
2. Creemos que un **módulo de gestión de inventario con política FEFO** (*First Expired, First Out*) y alertas automáticas de vencimiento a los 15, 7 y 3 días permitirá a los usuarios reducir las mermas por caducidad en al menos un 35%.
3. Creemos que un **módulo de reportes y analítica** con gráficos de rotación de stock, histórico de temperaturas y mermas por período facilitará la toma de decisiones logísticas y la negociación de reposición con proveedores.
4. Creemos que una **funcionalidad de trazabilidad de lotes** vinculada a la cadena de distribución permitirá a las distribuidoras medianas cumplir con los requisitos de rastreabilidad exigidos por SENASA y DIGESA, abriendo así una ventaja competitiva de carácter regulatorio.
5. Creemos que un **sistema de notificaciones multicanal** —notificaciones internas en la aplicación (*in-app*), correo electrónico y SMS— incrementará la tasa de respuesta ante alertas térmicas críticas hasta superar el 80% en menos de 15 minutos.
6. Creemos que un **módulo de gestión de usuarios y roles** —administrador, supervisor y operario— facilitará la adopción en empresas con equipos de trabajo de múltiples personas, incrementando el ticket promedio mensual por cuenta corporativa.

#### 1.2.2.3. Lean UX Hypothesis Statements

A partir de las suposiciones de características (*Feature Assumptions*) definidas para la plataforma **Refrio**, se formulan los siguientes enunciados de hipótesis. Estas declaraciones siguen de forma estricta la estructura formal del proceso *Lean UX*: *"We believe we will achieve [business outcome] if [personas] attain [benefit/user outcome] with [feature or solution]"*.

**Hypothesis 1 — Real-Time Temperature Monitoring Dashboard**
We believe we will achieve **a reduction of at least 30% in cold-chain breach incidents reported by active distributor accounts** if **warehouse supervisors and logistics managers** attain **real-time visibility and configurable threshold alerts for all their refrigeration units, accessible from any device** with **a real-time temperature monitoring dashboard connected to IoT sensors, with color-coded status indicators and automatic alert generation**.

**Hypothesis 2 — Inventory Management Module & FEFO Expiry Alerts**
We believe we will achieve **a reduction of at least 35% in economic losses due to product expiry among active users within 3 months of onboarding** if **warehouse supervisors and bodega owners** attain **automated early warnings at 15, 7 and 3 days before expiry and a FEFO-sorted stock list that makes rotation decisions self-evident** with **an inventory management module that tracks batch-level expiry dates, enforces FEFO ordering, and sends multichannel near-expiry notifications**.

**Hypothesis 3 — Analytics and Reporting Module**
We believe we will achieve **an improvement of at least 40% in the speed of logistics decision-making, measured by the reduction of time from data collection to action** if **logistics managers and company administrators** attain **automated weekly and monthly consolidated reports on stock rotation, waste history and temperature averages per storage unit** with **an analytics and reporting module featuring interactive charts and one-click PDF/CSV export functionality**.

**Hypothesis 4 — Batch Registration & Traceability Module**
We believe we will achieve **that at least 80% of subscribed distributor companies comply with SENASA and DIGESA lot-traceability requirements without additional manual effort** if **logistics managers and quality supervisors** attain **full lot-level traceability from product reception to distribution, linked to supplier and client records within the platform** with **a batch registration and traceability module integrated into the standard inventory workflow, generating audit-ready traceability reports on demand**.

**Hypothesis 5 — Multichannel Notification System**
We believe we will achieve **a critical-alert response rate above 80% within 15 minutes of alert issuance** if **warehouse supervisors and store owners** attain **timely awareness of critical temperature and expiry events regardless of whether they are actively using the platform at the time of the alert** with **a multichannel notification system delivering simultaneous in-app, email and SMS alerts for all configurable critical events, with alert acknowledgment tracking**.

**Hypothesis 6 — User and Role Management Module**
We believe we will achieve **that at least 60% of subscribed company accounts have 3 or more active users within 90 days of registration** if **company administrators** attain **the ability to assign differentiated access permissions (administrator, supervisor, operator) and monitor individual activity and contribution within the platform** with **a user and role management module that supports multi-user collaboration within a single account, with invitation by email and audit logs per user**.

#### 1.2.2.4. Lean UX Canvas

El **Lean UX Canvas** sintetiza visualmente el enfoque ágil del proyecto **Refrio**, alineando el problema del negocio, los resultados comerciales esperados, las características del usuario y las propuestas de solución para guiar el desarrollo de software bajo un ciclo de aprendizaje continuo:

| Bloque | Contenido de Negocio y Producto para **Refrio** |
| :--- | :--- |
| **1. Business Problem** | Las distribuidoras medianas de alimentos perecibles y los comerciantes minoristas (*bodegueros*) en el Perú pierden entre el 12% y el 20% de su facturación anual —y entre S/ 150 y S/ 400 mensuales en el caso de bodegas pequeñas— por ruptura de la cadena de frío y caducidad no detectada a tiempo. No existen en el mercado peruano herramientas tecnológicas accesibles y especializadas que integren monitoreo continuo de temperatura e inventario inteligente FEFO en un solo producto orientado a pymes. |
| **2. Business Outcomes** | - Lograr un mínimo de 200 empresas o negocios suscritos en los primeros 8 meses de operación comercial.<br/>- Mantener una tasa de retención mensual superior o igual al 85%.<br/>- Alcanzar una reducción declarada del 30% en pérdidas por mermas entre los usuarios activos de la plataforma.<br/>- Obtener un *Net Promoter Score* (NPS) mayor o igual a 40 al sexto mes de lanzamiento.<br/>- Superar un ingreso mensual recurrente (MRR) de S/ 20,000 al cierre del primer año. |
| **3. Users & Customers** | **Segmento 1 (Empresas distribuidoras):** Supervisores de almacén y jefes logísticos de distribuidoras medianas de alimentos perecibles con operaciones en Lima Metropolitana y ciudades intermedias.<br/><br/>**Segmento 2 (Comercios locales):** Propietarios y administradores de bodegas de barrio y puestos en mercados de abastos que comercializan productos perecibles. |
| **4. User Benefits** | - Visibilidad y control en tiempo real de la temperatura y el estado real de todo el inventario.<br/>- Reducción de 1.5 a 3 horas diarias en las tareas de verificación física manual.<br/>- Recepción de alertas tempranas automáticas que permiten actuar preventivamente antes de sufrir pérdidas económicas.<br/>- Generación de reportes automáticos para sustentar mermas de forma objetiva ante gerencias y proveedores.<br/>- Control ágil de trazabilidad de lotes para facilitar el cumplimiento regulatorio local. |
| **5. Solution Ideas** | - Panel de control interactivo (*dashboard*) de monitoreo de temperatura IoT en tiempo real.<br/>- Módulo de gestión de inventario FEFO (*First Expired, First Out*) con alertas automáticas de vencimiento.<br/>- Módulo de analítica, historial térmico y reportes exportables en formato PDF/CSV [3].<br/>- Sistema de trazabilidad de lotes integrado al flujo logístico estándar.<br/>- Sistema de notificaciones críticas simultáneas por múltiples canales (aplicación, correo y SMS).<br/>- Módulo de administración de usuarios con gestión de roles y permisos diferenciados. |
| **6. Hypotheses** | Ver sección 1.2.2.3: se estructuran de forma correlativa seis declaraciones de hipótesis de trabajo construidas para cada una de las ideas de solución, siguiendo la plantilla estándar de *Lean UX* (*outcome — persona — benefit — feature*). |
| **7. What's the Most Important Thing We Need to Learn First?** | - ¿Están realmente los jefes y supervisores logísticos del Segmento 1 dispuestos a pagar una suscripción mensual recurrente por un software que integre el monitoreo térmico con la gestión de su stock?<br/>- ¿Adoptarán los comerciantes y bodegueros del Segmento 2 esta solución digital si la interfaz es extremadamente simple y el costo del plan es menor a S/ 60 mensuales? |
| **8. What's the Least Amount of Work We Need to Learn the Next Most Important Thing?** | - Realizar 6 entrevistas cualitativas semiestructuradas (3 por cada segmento objetivo) para validar su disposición de pago, dolores operacionales críticos y características más deseadas.<br/>- Diseñar un prototipo interactivo de media/alta fidelidad en Figma que simule el dashboard del inventario y el panel de alertas de temperatura para ejecutar pruebas de usabilidad guiadas de 30 minutos con usuarios reales. |

## 1.3. Segmentos objetivo

**Refrio** dirige su propuesta de valor a dos segmentos objetivo claramente diferenciados dentro de la cadena de distribución de productos perecibles en el Perú. Ambos comparten el mismo dolor central —pérdidas económicas por ruptura de la cadena de frío y caducidad no controlada—, pero difieren en su escala operativa, perfil tecnológico y capacidad de inversión.

---
### Segmento 1: Jefes de almacén y supervisores logísticos de distribuidoras medianas de alimentos perecibles

*   **Descripción general:** Este segmento está conformado por los responsables operativos de la gestión logística en empresas distribuidoras medianas de alimentos perecibles —como lácteos, carnes, embutidos, frutas y verduras— que operan uno o más almacenes refrigerados y, en muchos casos, flotas de transporte frigorífico. Se ubican principalmente en Lima Metropolitana y ciudades intermedias con mercado logístico activo como Arequipa, Trujillo, Piura y Cusco.
*   **Características demográficas:**
    *   **Edad:** Entre 28 y 50 años.
    *   **Género:** Predominantemente masculino (aproximadamente 65%), aunque la participación femenina crece en roles de supervisión logística.
    *   **Nivel educativo:** Técnico superior o universitario en carreras de Administración de Empresas, Logística y Cadena de Suministro, o Ingeniería Industrial.
    *   **Ubicación:** Lima Metropolitana (distritos industriales como Ate, San Juan de Lurigancho, Villa El Salvador y Lurín) y principales ciudades del interior del país.
*   **Características conductuales y tecnológicas:**
    *   Utilizan *smartphones* Android de gama media-alta y computadoras de escritorio con Windows en el entorno laboral.
    *   Su adopción tecnológica se concentra en *WhatsApp Business*, Gmail, Microsoft Excel y —en empresas más formalizadas— algún ERP básico o software de facturación electrónica vinculado a la SUNAT.
    *   Están abiertos a adoptar nuevas tecnologías si perciben un retorno de inversión (*ROI*) claro, rápido y demostrable con datos objetivos.
    *   Las decisiones de compra de herramientas tecnológicas se toman en conjunto con la gerencia general o el área financiera, por lo que el ciclo de ventas requiere de una demostración de valor cuantificable.
*   **Necesidades y dolores principales:**
    *   Necesitan monitorear la temperatura de sus cámaras frigoríficas de forma continua y remota, sin depender de revisiones físicas periódicas.
    *   Requieren alertas automáticas ante desviaciones térmicas para actuar antes de que los productos se deterioren.
    *   Buscan un sistema que les permita gestionar el inventario con criterio FEFO (*First Expired, First Out*) para reducir mermas por vencimiento y cumplir con las políticas de rotación exigidas por sus clientes.
    *   Necesitan reportes exportables que les permitan justificar pérdidas y mermas ante clientes, proveedores y gerencias con datos objetivos.
    *   Requieren visibilidad multisede en tiempo real cuando operan más de un almacén o punto de distribución.
*   **Datos de sustento logístico y estadístico:** La relevancia de este segmento queda demostrada por Ñiquén y Ríos (2024), quienes señalan que la implementación de un sistema de almacenes digitalizado puede reducir drásticamente los costos operativos, mejorando la organización y la eficiencia de todos los procesos logísticos implicados. Esto es crítico en la realidad peruana, ya que, según el INEI (2023), en el país operan aproximadamente 3,800 empresas formales dedicadas a la distribución mayorista de alimentos perecibles, de las cuales el 74% corresponde a la categoría de mediana empresa (entre 11 y 100 trabajadores). De este universo, el 71% no utiliza ningún sistema de monitoreo automatizado de temperatura, y el 83% gestiona su inventario con hojas de cálculo o registros manuales. Paralelamente, el mercado de soluciones *SaaS* para logística en Latinoamérica creció un 21% en 2023, con proyección de mantener un crecimiento de dos dígitos hasta 2027 (IDC, 2024), lo que evidencia una ventana de oportunidad directamente aplicable para **Refrio** en el contexto nacional.

---
### Segmento 2: Propietarios y administradores de bodegas y puestos en mercados de abastos

*   **Descripción general:** Este segmento está compuesto por comerciantes minoristas propietarios de bodegas de barrio y puestos en mercados de abastos que comercializan productos perecibles —principalmente lácteos, embutidos, frutas, verduras y productos de panadería— y que cuentan con equipos de refrigeración básicos: refrigeradoras domésticas o comerciales de pequeña capacidad y, en algunos casos, congeladores de baja potencia. Su operación es mayoritariamente semi-formal o informal, con una parte de sus ventas realizadas mediante transacciones en efectivo.
*   **Características demográficas:**
    *   **Edad:** Entre 30 y 60 años.
    *   **Género:** Equilibrado (aproximadamente 50% femenino y 50% masculino), con mayor proporción de mujeres propietarias en el subsegmento de puestos de mercado.
    *   **Nivel educativo:** Secundaria completa o técnico básico.
    *   **Ubicación:** Lima Metropolitana —con especial concentración en los distritos de los conos norte, sur y este (Los Olivos, Comas, San Juan de Lurigancho, Villa El Salvador y Ate)— y ciudades intermedias del interior del país.
*   **Características conductuales y tecnológicas:**
    *   Utilizan principalmente *smartphones* Android de gama baja o media, con acceso a internet a través de datos móviles.
    *   Su actividad digital se concentra en *WhatsApp* —herramienta principal de comunicación con proveedores y clientes—, Facebook —para difundir promociones del negocio— y aplicaciones de pagos digitales como Yape y Plin.
    *   Tienen baja experiencia con software de gestión empresarial, pero poseen una alta disposición a aprender si la herramienta es intuitiva, en español y resuelve un dolor económico concreto e inmediato.
    *   Las decisiones de inversión son unipersonales y están condicionadas por el costo mensual: priorizan opciones de bajo costo con una demostración de ahorro tangible.
*   **Necesidades y dolores principales:**
    *   Pierden productos por vencimiento de manera recurrente porque no llevan un registro ordenado de fechas de caducidad y la revisión es enteramente manual y periódica.
    *   No detectan a tiempo cuándo su refrigeradora deja de funcionar correctamente, lo que genera pérdidas inesperadas —especialmente durante la noche o los fines de semana.
    *   Necesitan una herramienta simple que les avise con anticipación cuándo un producto está próximo a vencer, para poder realizar descuentos o ajustar los pedidos antes de incurrir en pérdidas totales.
    *   Buscan visibilidad básica del stock disponible para mejorar sus decisiones de reposición y evitar el desabastecimiento de productos de alta rotación .
*   **Datos de sustento logístico y estadístico:** En el caso del comercio minorista, Heizer y Render (2020) sostienen que una adecuada administración de las operaciones logísticas y de distribución es fundamental para mejorar el rendimiento empresarial global, reducir pérdidas y garantizar un servicio de alta calidad para el cliente. Esta teoría se vuelve indispensable al analizar los datos del INEI (2023), que registra más de 427,000 bodegas formales en el Perú, siendo Lima Metropolitana la región con mayor concentración (aproximadamente 130,000 establecimientos), de las cuales el 68% comercializa productos perecibles de forma regular. Según datos de la Asociación de Bodegueros del Perú (ABP, 2023), el 52% de sus asociados reporta pérdidas mensuales por vencimiento de productos perecibles superiores a S/ 200, pérdidas que en su totalidad se atribuyen a la falta de sistemas de control de fechas de caducidad. Frente a esta realidad, el Organismo Supervisor de Inversión Privada en Telecomunicaciones (OSIPTEL, 2023) reporta que la penetración de *smartphones* en Lima Metropolitana alcanza el 87%, con un uso activo de aplicaciones de mensajería y pagos digitales, lo que confirma la factibilidad de alcanzar a este segmento mediante la solución móvil de **Refrio**.
