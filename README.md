📊 Análisis Correlacional NovaRetail+ 2024

🎯 Descripción del Proyecto

Análisis correlacional completo del comportamiento de clientes de NovaRetail+, una plataforma de comercio electrónico líder en Latinoamérica. Este proyecto investiga qué factores del comportamiento del cliente están más fuertemente asociados con el ingreso anual generado, proporcionando insights accionables para el equipo de Crecimiento y Retención.

🔍 Pregunta de Investigación
¿Qué factores del comportamiento del cliente están más fuertemente asociados con el ingreso anual generado?

📋 Objetivos
Integrar múltiples técnicas de correlación en un análisis unificado
Identificar relaciones significativas entre variables de comportamiento e ingresos
Detectar correlaciones engañosas y evitar interpretaciones causales incorrectas
Convertir hallazgos estadísticos en recomendaciones de negocio accionables
Documentar limitaciones y próximos pasos para futuras investigaciones

🗂️ Dataset
Fuente: novaretail_comportamiento_clientes_2024.csv
Tamaño: 15,000 registros de clientes

**Variables Analizadas**
Variable	Tipo	Descripción
ingreso_anual	Numérica	Variable objetivo - Ingresos generados por cliente
edad	Numérica	Edad del cliente
visitas_mes	Numérica	Visitas mensuales a la plataforma
compras_mes	Numérica	Compras realizadas por mes
gasto_publicidad_dirigida	Numérica	Inversión publicitaria asignada
satisfaccion	Numérica	Calificación 1-5
miembro_premium	Binaria	Suscripción premium (0/1)
tipo_dispositivo	Categórica	móvil / escritorio / tablet
region	Categórica	norte / sur / oeste / este

🛠️ Metodología
Técnicas de Correlación Aplicadas
Correlación de Pearson
Variables numéricas lineales
Correlación Punto-Biserial
Variables binarias vs numéricas
V de Cramér
Variables categóricas
Herramientas Utilizadas
pandas, numpy, seaborn, matplotlib, scipy.stats

📈 Principales Hallazgos
### 🔍 Hallazgo 1: Tipo de dispositivo no tiene impacto en los ingresos anuales
- Distribución de uso: Móvil 65%, Escritorio 25%, Tablet 10%
- V de Cramér: 0.0124 (asociación muy débil)
- Implicación: Estrategias de marketing pueden ser consistentes entre regiones

### 💎 Hallazgo 2: Oportunidad perdida - Membresía Premium no genera valor diferencial
- Correlaciones punto-biserial extremadamente débiles:
  - Compras mensuales: 0.0034
  - Visitas mensuales: -0.0127
  - Ingresos anuales: 0.0931
- Implicación: Necesidad urgente de reestructurar programa premium
