<span class="hljs-section"># 📊 Análisis de Embudo y Retención — MercadoLibre</span>

<span class="hljs-section">## 🎯 Objetivo</span>
Identificar en qué etapa exacta del proceso de compra los usuarios abandonan 
y calcular la tasa de retención por cohortes para generar recomendaciones 
accionables al equipo de producto.

<span class="hljs-section">## 🔍 Problema de negocio</span>
MercadoLibre presentaba caída significativa en su tasa de conversión. 
Sin saber dónde ocurría el abandono, el equipo de producto no podía 
tomar decisiones concretas para mejorarlo.

<span class="hljs-section">## 🗄️ Dataset</span>
<span class="hljs-bullet">-</span> <span class="hljs-strong">**Fuente:**</span> Dataset de eventos de usuario e-commerce (TripleTen)
<span class="hljs-bullet">-</span> <span class="hljs-strong">**Variables:**</span> user<span class="hljs-emphasis">_id, event_</span>type, event<span class="hljs-emphasis">_date, session_</span>id
<span class="hljs-bullet">-</span> <span class="hljs-strong">**Etapas del funnel:**</span> visita → carrito → checkout → pago

<span class="hljs-section">## 🛠️ Herramientas</span>
![<span class="hljs-string">SQL</span>](<span class="hljs-link">https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white</span>)
![<span class="hljs-string">Excel</span>](<span class="hljs-link">https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white</span>)

<span class="hljs-section">## ⚙️ Proceso</span>
<span class="hljs-bullet">1.</span> Análisis del funnel por etapas con SQL
<span class="hljs-bullet">2.</span> Cálculo de porcentaje de abandono por etapa
<span class="hljs-bullet">3.</span> Identificación del cuello de botella principal (checkout)
<span class="hljs-bullet">4.</span> Análisis de cohortes en Excel: retención D7/D14/D21/D28
<span class="hljs-bullet">5.</span> Generación de recomendaciones accionables

<span class="hljs-section">## 📊 Principales hallazgos</span>
<span class="hljs-bullet">-</span> 🚨 El checkout concentraba <span class="hljs-strong">**más del 40% del abandono total**</span>
<span class="hljs-bullet">-</span> 📅 Cohortes de ciertos meses mostraban retención significativamente mayor
<span class="hljs-bullet">-</span> 💡 3 recomendaciones accionables generadas para reducir abandono

<span class="hljs-section">## 💡 Conclusión</span>
El dato más valioso fue identificar que el problema no estaba en la búsqueda 
ni en el carrito, sino específicamente en el checkout.

<span class="hljs-section">## 📁 Archivos</span>
<span class="hljs-bullet">-</span> <span class="hljs-code">`resumen_ejecutivo.xlsx`</span> — Análisis completo con funnel, cohortes y hallazgos

<span class="hljs-section">## 👤 Autor</span>
<span class="hljs-strong">**Javier Eduardo Ramos Rivera**</span>  
Junior Data Analyst | SQL · Python · Power BI  
📧 javierramos.analyst@gmail.com  
💼 [<span class="hljs-string">LinkedIn</span>](<span class="hljs-link">https://www.linkedin.com/in/javier-ramos-rivera/</span>)  
📁 [<span class="hljs-string">Portafolio Notion</span>](<span class="hljs-link">https://app.notion.com/p/Portafolio-Javier-Eduardo-Ramos-Rivera-Data-Analyst-Junior-31cade63135a80ce969acccf829d1b89</span>)
