# 📊 Análisis de Embudo y Retención — MercadoLibre

**🎯 Objetivo**
Identificar en qué etapa exacta del proceso de compra los usuarios abandonan y calcular la tasa de retención por cohortes para generar recomendaciones accionables al equipo de producto.

**🔍 Problema de negocio**
MercadoLibre presentaba caída significativa en su tasa de conversión. Sin saber dónde ocurría el abandono, el equipo de producto no podía tomar decisiones concretas para mejorarlo.

**🗄️ Dataset**
- **Fuente:** Dataset de eventos de usuario e-commerce (TripleTen)
- **Variables:** user_id, event_type, event_date, session_id
- **Etapas del funnel:** visita → carrito → checkout → pago

**🛠️ Herramientas**
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)

**⚙️ Proceso**
1. Análisis del funnel por etapas con SQL
2. Cálculo de porcentaje de abandono por etapa
3. Identificación del cuello de botella principal (checkout)
4. Análisis de cohortes en Excel: retención D7/D14/D21/D28
5. Generación de recomendaciones accionables

**📊 Principales hallazgos**
- 🚨 El checkout concentraba **más del 40% del abandono total**
- 📅 Cohortes de ciertos meses mostraban retención significativamente mayor
- 💡 3 recomendaciones accionables generadas para reducir abandono

**💡 Conclusión**
El dato más valioso fue identificar que el problema no estaba en la búsqueda ni en el carrito, sino específicamente en el checkout.

**📁 Archivos**
- `resumen_ejecutivo.xlsx` — Análisis completo con funnel, cohortes y hallazgos

**👤 Autor**
**Javier Eduardo Ramos Rivera**
Junior Data Analyst | SQL · Python · Power BI
📧 javierramos.analyst@gmail.com
💼 [LinkedIn](https://www.linkedin.com/in/javier-ramos-rivera/)
📁 [Portafolio Notion](https://app.notion.so/...)
