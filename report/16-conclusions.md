# Conclusiones

## Conclusiones

El desarrollo e implementación del proyecto Refrio ha validado que la dependencia de procesos semimanuales (como hojas de cálculo y registros en papel) es la causa principal de mermas económicas por caducidad y quiebres térmicos, generando pérdidas de entre S/ 6,000 y S/ 9,000 mensuales en distribuidoras medianas. A partir de las entrevistas de validación con supervisores logísticos y comerciantes minoristas, se comprobó que el mercado necesita urgentemente una solución unificada que integre el monitoreo térmico en tiempo real con una gestión de inventario basada estrictamente en el método FEFO (Primero en Vencer, Primero en Salir). 

Las plataformas que existen actualmente en el mercado resultan ser demasiado costosas, están enfocadas en corporaciones transnacionales o carecen de funciones integradas de control de temperatura, dejando un vacío importante. Refrio cubre este espacio mediante una arquitectura escalable (monolito modular con Domain-Driven Design en Spring Boot y Angular) que ha demostrado, a través de pruebas de usabilidad, un impacto directo en la reducción de errores de *picking* y despacho. 

Asimismo, se concluye que para lograr una alta tasa de adopción tecnológica —especialmente en el sector de comerciantes minoristas— es vital ofrecer una plataforma sumamente intuitiva, utilizar semáforos visuales de frescura y demostrar de forma inmediata el ahorro económico (retorno de inversión) generado por el sistema. En general, la automatización de la cadena de frío no solo previene pérdidas económicas directas que oscilan entre el 12% y el 20% de la facturación, sino que también respalda la trazabilidad ante auditorías y mejora la confianza del consumidor final.

## Recomendaciones

Para asegurar la escalabilidad operativa y el éxito comercial de la plataforma, se plantean las siguientes recomendaciones, directamente alineadas con los hallazgos de las evaluaciones heurísticas y las entrevistas de validación:

*   **Implementación de notificaciones multicanal (Push/WhatsApp/SMS):** Es crítico habilitar alertas inmediatas fuera de la aplicación para las incidencias térmicas. Los supervisores y dueños de negocio necesitan recibir retroalimentación en tiempo real en sus celulares para actuar antes de que ocurra una ruptura irreversible en la cadena de frío.
*   **Visibilidad del Retorno de Inversión (ROI):** Se recomienda integrar un *widget* o sección analítica en el Dashboard del Supervisor que cuantifique el ahorro económico mensual derivado de las mermas evitadas por la rotación FEFO. Esto facilitará la justificación de la adopción del software ante las gerencias.
*   **Exportación de Reportes y Trazabilidad:** Habilitar operativamente la generación y descarga de certificados de cadena de frío e historiales térmicos en formatos estándar (PDF o Excel), para respaldar a los usuarios ante auditorías sanitarias y reclamos comerciales.
*   **Optimización Móvil y Prevención de Errores:** Adaptar las vistas de inventario en dispositivos móviles mediante tarjetas (*cards*) colapsables para no saturar de información al usuario minorista durante su jornada. Además, se debe implementar diálogos de confirmación modal antes de ejecutar "bajas de lote" o mermas, para evitar descuadres accidentales de stock.
*   **Alianzas Estratégicas y Capacitación:** Establecer convenios con proveedores locales de sensores IoT para mantener los costos de implementación de hardware lo más bajos posibles. De la misma forma, diseñar un *onboarding* guiado y tutoriales en video didácticos para mitigar la resistencia cultural al cambio en el segmento de bodegueros.
