📊 Proyecto de Análisis y Visualización de Datos Empresariales + Meteorológicos
Este repositorio reúne un conjunto de herramientas desarrolladas para la gestión, análisis y visualización de datos tanto en contextos empresariales como ambientales. Incluye soluciones en SQL Server, Excel avanzado con VBA y Power BI, integradas para cubrir el ciclo completo de procesamiento de datos: desde la consulta y transformación, hasta la visualización interactiva.

🧠 Tecnologías utilizadas
- SQL Server (T-SQL, Vistas, Funciones, Integridad referencial, Scripts portables)
- Excel con Power Query, Power Pivot y formularios avanzados en VBA
- Power BI (Métricas, Visualizaciones personalizadas, Shape Maps, Modelado climático predictivo)
- Python (Procesamiento de archivos CSV, automatización de carga y limpieza de datos climáticos)


📁 Contenido del repositorio
📂 SQL
- Ventas_Electricos.sql
Script universal para creación de base de datos con estructura optimizada, compatible con múltiples versiones de SQL Server. Incluye inserciones masivas, normalización de tablas y vistas analíticas personalizadas.
- Medina_ERP.sql
Esquema completo para sistema ERP enfocado en compras y ventas. Contiene relaciones entre proveedores, marcas, productos, clientes y órdenes. Se incorporan validaciones (CHECKs), uso de VARBINARY para imágenes y estructuras preparadas para integración analítica.
- ClimaMexico.sql
Base de datos para análisis climatológico con más de 148 millones de registros meteorológicos históricos descargados desde CONAGUA. Incluye funciones predictivas como fn_ModeloPorDiaMes, cálculo de regresión por fecha y modelado de tendencias de temperatura y precipitación a futuro.

📂 Excel
- Evaluacion_360_Empleado.xlsx
Plantilla interactiva de evaluación de desempeño con dimensiones, competencias y puntuaciones individuales; diseñada para facilitar decisiones estratégicas en RRHH.
- Grafica_de_Velocimetro.xlsx
Visualización tipo “speedometer” con cálculo dinámico de avance porcentual. Ideal para dashboards ejecutivos.
- Diagrama_de_Gantt.xlsx
Herramienta para planificación de proyectos con tareas, subtareas y cronograma visual semanal. Integra asignaciones, progreso y fechas clave.
- Formularios de Cotización y Venta (.xlsm)
Módulos en VBA que generan cotizaciones y ventas con cálculos dinámicos de montos, impuestos y descuentos. Incluyen búsqueda inteligente de proveedores o clientes, y están preparados para integrarse con Power BI o Power Query.
- Funcion_NumeroALetras.xlsm
Función personalizada que convierte valores numéricos a texto en español, incluyendo soporte para decimales. Útil para documentos fiscales como facturas y recibos.
- Medina_ERP.xlsm
Aplicación en Excel que conecta visualmente con SQL Server, permitiendo interacción directa con órdenes, registros, formularios y ahora también integración con datos meteorológicos.

📂 Power BI
- Dashboard Ventas Electricos.pbix
Informe interactivo que muestra tendencias de venta, rendimiento por producto y variación mensual mediante visualizaciones avanzadas, incluyendo mapas personalizados y métricas dinámicas.
- Dashboard ClimaMexico.pbix
Panel climático predictivo que consulta automáticamente funciones SQL y genera visualizaciones por fecha específica, incluyendo modelado histórico, regresión lineal y proyecciones personalizadas por temperatura y precipitación.
📥 El archivo es demasiado grande para alojarse en GitHub. Puedes descargarlo desde el siguiente enlace:
🔗 Descargar Dashboard ClimaMexico.pbix

🎯 Objetivos
- Automatizar la recolección, transformación y análisis de datos empresariales y climatológicos.
- Presentar insights mediante dashboards claros e intuitivos con proyecciones a futuro.
- Integrar múltiples tecnologías (SQL, Excel, Power BI) para brindar soluciones completas y reutilizables.
- Consolidar una base técnica robusta como portafolio profesional en gestión operativa y ambiental.

📜 Créditos
Desarrollado por Antonio Medina, con apoyo colaborativo de Microsoft Copilot para la integración analítica, modelado predictivo por fecha y conexión dinámica entre SQL Server y Power BI.
