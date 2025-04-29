# 🎟️ Showz: Optimización de Gastos de Marketing en la Venta de Entradas

## 📝 Contexto
**Showz** es una empresa dedicada a la venta de entradas para eventos, y se encuentra buscando optimizar sus gastos de marketing para maximizar su rentabilidad. A través de este proyecto, se analizan los registros de visitas a su plataforma, los pedidos realizados, y los gastos de marketing del periodo de enero de 2017 a diciembre de 2018. El objetivo es comprender cómo los usuarios interactúan con la plataforma, cuándo se convierten en compradores, cuánto aportan a la empresa y cuándo los ingresos cubren el costo de adquisición de clientes. 

El análisis se centra en responder preguntas clave sobre la adquisición y retención de clientes, y en recomendar cómo asignar de manera más efectiva los presupuestos de marketing.

## 🛠️ Herramientas Utilizadas
- **Python**: Análisis de datos y modelado estadístico.
- **Pandas**: Limpieza, transformación y análisis de datos.
- **Matplotlib** y **Seaborn**: Visualización de patrones y tendencias en las visitas, compras y gastos de marketing.
- **SciPy**: Análisis de significancia y validación de hipótesis.
- **Jupyter Notebook**: Documentación interactiva y detallada del análisis.

## 📈 Análisis de Resultados
El proyecto se estructuró en varias fases:

1. **Preprocesamiento de Datos**:
   - Carga y limpieza de los datos de visitas, pedidos y gastos de marketing desde los archivos proporcionados.
   - Verificación de los tipos de datos de cada columna y asegurarse de que cada dato esté en el formato correcto para el análisis.
   - Generación de métricas clave, como la duración de las sesiones y el número de sesiones por usuario.

2. **Análisis Descriptivo**:
   - **Visitas**:
     - Análisis del número de usuarios diarios, semanales y mensuales.
     - Cálculo de la duración promedio de las sesiones.
     - Determinación de la frecuencia con la que los usuarios regresan al sitio web.
   - **Ventas**:
     - Determinación del tiempo transcurrido entre el registro de los usuarios y su primera compra.
     - Cálculo del tamaño promedio de compra y el valor total aportado por cada cliente (LTV).
   - **Marketing**:
     - Análisis de los gastos de marketing por fuente y a lo largo del tiempo.
     - Cálculo del costo de adquisición de clientes (CAC) por fuente de adquisición.
     - Análisis de la rentabilidad de las inversiones en marketing (ROMI).

3. **Visualización de Datos**:
   - Gráficos de líneas y barras para mostrar las tendencias de visitas y ventas por mes.
   - Gráficos que comparan el ROMI y el CAC de cada fuente de adquisición.
   - Visualización de la distribución de la duración de las sesiones y el tiempo entre visitas consecutivas.

4. **Conclusiones**:
   - **ROMI**: Las fuentes de adquisición con un ROMI superior a 1 (como las fuentes 1, 2 y 5) son las más rentables y deberían ser prioritarias en las inversiones de marketing.
   - **Plataformas**: A pesar de que la mayoría de los usuarios utilizan la plataforma "Desktop", las inversiones de marketing deben ser diversificadas para impulsar la plataforma "Touch", que es más económica y tiene un mayor retorno por cliente.
   - **Fuentes de Adquisición**: Las fuentes de adquisición 3, 4 y 5 tienen altos costos de adquisición de clientes y generan un ROMI bajo. Se recomienda optimizar las inversiones en las fuentes 1 y 2, que son más rentables y tienen costos de adquisición más bajos.
   - **Usuarios y Ventas**: Los picos de usuarios y ventas en los meses de agosto de 2017 a enero de 2018 indican una oportunidad para concentrar esfuerzos de marketing en esos períodos.
   - **Satisfacción del Cliente**: La mayoría de los usuarios regresan en menos de 10 días, lo que refleja una alta satisfacción del cliente y la posibilidad de fomentar recomendaciones y fidelización.

## 📋 Recomendaciones
- **Fuentes de Adquisición**: Priorizar las fuentes con un ROMI alto (1, 2 y 5) y optimizar las fuentes con un alto costo de adquisición (3, 4 y 5).
- **Plataformas**: Diversificar el marketing para aumentar la participación en la plataforma "Touch", que ofrece un mejor retorno sobre la inversión.
- **Gastos de Marketing**: Aumentar la inversión en los meses con mayores picos de usuarios y ventas, ajustando la estrategia en base a la estacionalidad de la demanda.

Este análisis proporciona información clave para que Showz optimice su asignación de presupuesto en marketing, mejore su ROI y maximice la retención y satisfacción de sus clientes.
