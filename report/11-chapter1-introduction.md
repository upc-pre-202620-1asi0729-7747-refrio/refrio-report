# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

**Refrio** es una startup tecnológica peruana dedicada al diseño y desarrollo de soluciones digitales innovadoras para la gestión de inventario, el monitoreo de temperatura y la distribución eficiente de productos perecibles. La empresa nace con la firme convicción de que la tecnología y el Internet de las Cosas (IoT) pueden convertirse en herramientas clave para reducir pérdidas económicas, evitar el desperdicio de alimentos y asegurar la trazabilidad en la cadena de frío.

Este propósito responde a una problemática crítica en el contexto nacional: cada año se pierden o desechan en el Perú aproximadamente 12.8 millones de toneladas de alimentos, lo que equivale al 47.76% de la producción total del país (Ministerio de Desarrollo Agrario y Riego [MIDAGRI], 2022). Para hacer frente a este desafío, **Refrio** trabaja bajo un enfoque centrado en el usuario para lograr una gestión de stock automatizada, predictiva y en tiempo real. Al integrar alertas inteligentes de vencimiento y telemetría de temperatura constante, la plataforma ayuda a empresas distribuidoras y comerciantes locales a optimizar la rotación del inventario mediante políticas FEFO (*First Expired, First Out*).

La relevancia de esta propuesta radica en que la implementación de un sistema de gestión de almacenes digitalizado no solo permite reducir los costos operativos, sino que optimiza significativamente la organización y la eficiencia de todos los procesos logísticos implicados (Ñiquén & Ríos, 2024). Asimismo, una adecuada administración de las operaciones logísticas y de distribución es fundamental para mejorar el rendimiento empresarial global, reducir pérdidas y garantizar un servicio de alta calidad para el cliente (Heizer & Render, 2020).

*   **Misión:** Optimizar la gestión de inventarios y salvaguardar la cadena de frío de productos perecibles mediante soluciones tecnológicas eficientes, accesibles y confiables.
*   **Visión:** Ser la plataforma líder en el monitoreo inteligente de temperatura y distribución de productos perecibles a nivel nacional.


### 1.1.2. Perfiles de integrantes del equipo

| Foto | Descripción |
|:---:|:---|
| <img src="ruta/a/tu/imagen.jpg" alt="Foto" width="120"> | **Alca Morán, César Alejandro - U20241F027**<br>descripción |
| <img src="ruta/a/tu/imagen.jpg" alt="Foto" width="120"> | **Centeno León, Adriano Samir - U20241D920**<br>descripción |
| <img src="../assets/Rivas Méndez, Bernie Aarón - U20241F109 - Profile.PNG" alt="Foto" width="120"> | **Rivas Méndez, Bernie Aarón - U20241F109**<br>Soy un estudiante de la carrera de Ingeniería de Software y curso el 5to ciclo de la carrera. En cuanto a los trabajos me gusta revisar y que estén completos a la hora de entregarlos. En cuanto a la programación me gusta ser ordenado y que tenga lógica, por lo cual prefiero programar el BackEnd, pero también hago el FrontEnd.|
| <img src="ruta/a/tu/imagen.jpg" alt="Foto" width="120"> | **Saavedra Flores, Rodrigo Andree - U20241D811**<br>descripción |
| <img src="ruta/a/tu/imagen.jpg" alt="Foto" width="120"> | **Tello Lima, Jose Alejandro - U202421618**<br>descripción |

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

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo
