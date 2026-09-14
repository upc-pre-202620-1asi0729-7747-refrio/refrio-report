# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

### 5.1.2. Source Code Management

### 5.1.3. Source Code Style Guide & Conventions

### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

#### 5.2.1.2. Aspect Leaders and Collaborators

#### 5.2.1.3. Sprint Backlog 1

#### 5.2.1.4. Development Evidence for Sprint Review

#### 5.2.1.5. Execution Evidence for Sprint Review

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

#### 5.2.1.8. Team Collaboration Insights during Sprint

## 5.3. Validation Interviews

### 5.3.1. Diseño de Entrevistas

El objetivo de las entrevistas de validación es evaluar la experiencia de usuario (UX), la usabilidad (UI), la claridad de la propuesta de valor y la efectividad de los flujos principales (*happy paths*) de la plataforma Refrio. Durante estas sesiones, los entrevistados interactúan directamente con la Landing Page y la Aplicación Web/Móvil mientras responden a las siguientes preguntas estructuradas por segmento objetivo.

---

#### Segmento 1: Jefes de almacén y supervisores logísticos de distribuidoras medianas de alimentos perecibles

##### 1. Datos del entrevistado y perfil operativo
1. ¿Cuál es su nombre, edad y cargo dentro de la empresa distribuidora?
2. ¿En qué distrito se ubica el almacén principal de su empresa y cuántas sedes manejan actualmente?
3. ¿Qué categorías de productos perecibles distribuyen principalmente (lácteos, embutidos, carnes, congelados)?
4. ¿Cuál es su nivel de familiaridad diario con herramientas digitales corporativas o paneles de control web?
5. ¿Qué dispositivo utiliza con mayor frecuencia durante su jornada laboral en planta (computadora de escritorio, tablet, smartphone)?
6. ¿Con qué frecuencia revisa el estado térmico de sus cámaras o el inventario durante y fuera del horario de trabajo?

##### 2. Impresión general y claridad del Landing Page / Propuesta de Valor
7. Al navegar por la página principal (Landing Page) de Refrio, ¿queda claro en los primeros segundos qué problema resuelve la plataforma?
8. ¿La información sobre la combinación de telemetría IoT y gestión de inventario FEFO le resulta comprensible y relevante para su operación?
9. ¿Qué opinión le merecen los testimonios, métricas de ahorro y casos de éxito presentados en el portal web?
10. ¿El formulario para solicitar una demostración B2B le pareció ágil y con los campos adecuados para su empresa?

##### 3. Validación de usabilidad: Dashboard IoT y Monitoreo Térmico en Tiempo Real
11. Al observar el panel de control (Dashboard) principal, ¿los indicadores gráficos de temperatura por cámara frigorífica le resultan claros e intuitivos?
12. ¿Qué tan fácil le resulta identificar cuál cámara se encuentra en rango seguro y cuál presenta una oscilación térmica leve o crítica gracias a los códigos de color?
13. ¿La curva gráfica de historial térmico de las últimas 24 horas le aporta la información necesaria para auditar turnos nocturnos?
14. ¿Cómo valora la velocidad de actualización de las lecturas telemétricas en pantalla (cada 60 segundos) sin necesidad de recargar la página?

##### 4. Validación de usabilidad: Módulo de Inventario FEFO, Lotes y Trazabilidad
15. Al revisar la lista de inventario, ¿le resulta claro el ordenamiento automático bajo la política FEFO (*First Expired, First Out*)?
16. Al simular la creación de un plan de despacho o picking, ¿la plataforma le guía de forma fluida a seleccionar los lotes con vencimiento más próximo?
17. ¿La funcionalidad para generar e imprimir el certificado de cadena de frío con código QR en PDF cumple con los requerimientos que le exigen sus clientes o auditorías (DIGESA/SENASA)?

##### 5. Validación del Sistema de Alertas Multicanal y Reportes
18. Ante una simulación de ruptura térmica (Cold Breach), ¿la notificación recibida e indicadores en pantalla le parecieron lo suficientemente urgentes y visibles?
19. ¿Qué tan fácil le pareció el proceso para confirmar, justificar la causa y marcar como "Atendida" una alerta crítica?
20. ¿El reporte ejecutivo mensual de mermas evitadas y ahorro económico en soles le resulta útil para presentar ante la gerencia de la empresa?

##### 6. Evaluación de propuesta comercial, pricing y disposición de adopción
21. Al revisar la sección de Planes de Suscripción (Plan Básico, Profesional y Empresarial), ¿las diferencias entre funcionalidades y límites por plan son claras?
22. ¿Considera que el precio del Plan Profesional (S/ 129/mes) guarda relación con el valor y ahorro de mermas que la plataforma le genera a su almacén?
23. ¿Qué cambios, mejoras o funcionalidades adicionales consideraría indispensables antes de implementar Refrio de forma definitiva en sus operaciones?

---

#### Segmento 2: Propietarios y administradores de bodegas y puestos en mercados de abastos

##### 1. Datos del entrevistado y contexto del negocio
1. ¿Cuál es su nombre, edad y el nombre de su bodega o puesto comercial?
2. ¿En qué distrito se ubica su establecimiento y cuántos años lleva operando el negocio?
3. ¿Qué tipos de productos perecibles comercializa con mayor frecuencia en su mostrador (lácteos, embutidos, verduras, bebidas)?
4. ¿Cuántas personas atienden el negocio y quién se encarga directamente de revisar las fechas de vencimiento?
5. ¿Qué modelo de celular inteligente (Android) utiliza diariamente en su negocio y con qué aplicaciones está más familiarizado (WhatsApp, Yape)?
6. ¿A través de qué medio suele enterarse de ofertas o nuevas herramientas para mejorar su negocio?

##### 2. Impresión general y facilidad de navegación en el Landing Page / App Móvil
7. Al ingresar desde su celular a la versión móvil de Refrio, ¿los textos, imágenes y botones se leen de forma clara y sin esfuerzo visual?
8. ¿Le resulta claro el mensaje de cómo la aplicación le ayuda a evitar que los productos se le malogren en la refrigeradora o vitrina?
9. ¿El lenguaje utilizado en la aplicación le parece sencillo o contiene palabras técnicas difíciles de entender?
10. ¿Qué tan ágil le pareció el proceso de registro inicial con su número de teléfono celular?

##### 3. Validación de usabilidad: Escaneo de Caducidad e Ingreso Rápido de Stock
11. Al probar la función de registrar un producto escaneando el código de barras o tomando una foto a la fecha, ¿el sistema reconoció la información de manera rápida?
12. En caso de ingresar la fecha manualmente, ¿el teclado numérico y el selector de días le resultaron fáciles de usar mientras atiende a un cliente?
13. ¿Considera que registrar los productos en la aplicación le toma menos tiempo que su método habitual de anotar en cuaderno o revisar empaque por empaque?

##### 4. Validación de usabilidad: Semáforo Visual de Frescura y Oferta de Remate
14. Al ver la lista de productos con colores (Rojo para 3 días, Amarillo para 7 días, Verde para stock seguro), ¿entiende inmediatamente qué mercadería debe vender primero?
15. Al presionar sobre un producto en semáforo rojo, ¿la opción para aplicar un "Descuento de Remate / Liquidación" le pareció fácil de activar?
16. ¿La sugerencia de precios de remate le ayuda a tomar decisiones rápidas para recuperar su capital antes de que el producto venza?

##### 5. Validación de Alertas Sonoras Nocturnas y Resumen Mensual de Ahorros
17. Al simular la recepción de una alerta por desconexión o alza de temperatura nocturna en su refrigeradora, ¿el sonido y la notificación en el celular le parecieron efectivos para reaccionar a tiempo?
18. ¿Le resultó clara la pantalla de balance mensual "Mis Ahorros" que le muestra exactamente cuántos soles evitó perder en el mes?
19. ¿Siente que esta aplicación le brinda tranquilidad durante los fines de semana o cuando no se encuentra presente físicamente en su local?

##### 6. Evaluación de planes de suscripción, valor percibido y disposición de pago
20. Al revisar la tarifa del Plan Básico para bodegas (S/ 59 mensuales o aprox. S/ 2 diarios), ¿siente que el monto es accesible para la economía de su negocio?
21. Comparando los S/ 59 mensuales de la suscripción con los S/ 150 a S/ 300 que suele perder al mes botando productos vencidos, ¿considera que la aplicación se paga sola?
22. ¿Recomendaría Refrio a otros bodegueros o conocidos del mercado de abastos? ¿Por qué?



### 5.3.2. Registro de Entrevistas

### 5.3.3. Evaluaciones según heurísticas

## 5.4. Video About-the-Product
