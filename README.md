# 📊 Análisis Correlacional NovaRetail+ 2024

## 🎯 Descripción del Proyecto

Análisis correlacional completo del comportamiento de clientes de NovaRetail+, una plataforma de comercio electrónico líder en Latinoamérica. Este proyecto investiga qué factores del comportamiento del cliente están más fuertemente asociados con el ingreso anual generado, proporcionando insights accionables para el equipo de Crecimiento y Retención.

## 🔍 Pregunta de Investigación
¿Qué factores del comportamiento del cliente están más fuertemente asociados con el ingreso anual generado?

## 📋 Objetivos
Integrar múltiples técnicas de correlación en un análisis unificado
Identificar relaciones significativas entre variables de comportamiento e ingresos
Detectar correlaciones engañosas y evitar interpretaciones causales incorrectas
Convertir hallazgos estadísticos en recomendaciones de negocio accionables
Documentar limitaciones y próximos pasos para futuras investigaciones

## 🗂️ Dataset
Fuente: novaretail_comportamiento_clientes_2024.csv
Tamaño: 15,000 registros de clientes

## **Variables Analizadas**
| Variable | Tipo | Descripción |
|---------|-------------|-------------------|
| ingreso_anual	| Numérica | Ingresos generados por cliente |
| edad | Numérica |	Edad del cliente |
| visitas_mes | Numérica	| Visitas mensuales a la plataforma |
| compras_mes	Numérica	| Compras realizadas por mes |
| gasto_publicidad_dirigida | Numérica | Inversión publicitaria asignada |
| satisfaccion	| Numérica	| Calificación 1-5 |
| miembro_premium | Binaria	| Suscripción premium (0/1) |
| tipo_dispositivo	| Categórica	| móvil / escritorio / tablet |
| region	Categórica | norte | / sur / oeste / este |

## 🛠️ Metodología
Técnicas de Correlación Aplicadas
Correlación de Pearson
Variables numéricas lineales
Correlación Punto-Biserial
Variables binarias vs numéricas
V de Cramér
Variables categóricas
Herramientas Utilizadas
pandas, numpy, seaborn, matplotlib, scipy.stats

## 🔄 Etapas del Análisis
Este proyecto sigue un flujo estructurado de análisis correlacional dividido en 6 etapas principales:

| Etapa	 | Descripción | Resultado Esperado |
|---------|-------------|-------------------|
| 1. Exploración Inicial | Cargar y explorar el dataset | Entender estructura, columnas, tipos y métricas clave |
| 2. Preparación de Datos	| Preparar datos y documentar supuestos |	Datos limpios y listos para análisis.
Variables relevantes definidas y reglas documentadas |
| 3. Visualización | Crear visualizaciones de relaciones iniciales |	Heatmap para patrones globales y Scatterplots para relaciones específicas |
| 4. Análisis Correlacional | Calcular correlaciones según tipo de variable	• Pearson/Spearman (numéricas) | 
• Punto biserial (binaria-numérica)
• V de Cramér (categóricas) |
| 5. Interpretación | Analizar resultados de forma responsable	| Evidencia → interpretación → implicaciones de negocio |
| 6. Conclusiones | Documentar limitaciones y próximos pasos | Claridad sobre qué NO se puede concluir + recomendaciones futuras |
 
### 🎯 Enfoque del Análisis
Naturaleza: Correlacional y exploratorio (no causal)
Variable objetivo: ingreso_anual (ingresos generados por cliente)
Tipos de relaciones analizadas:
Numéricas (lineales y monotónicas)
Binarias vs. numéricas
Categóricas

### 📊 Resultado Final
Un reporte de análisis de correlación que combina:

✅ Evidencia visual (gráficos y heatmaps)
✅ Evidencia numérica (coeficientes de correlación)
✅ Interpretación responsable (sin causalidad)
✅ Implicaciones de negocio accionables

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:
[Google Colab](https://colab.research.google.com/drive/19XPcNyRU4dZ6NQXEODzPa_fqd49ZdQ4q?usp=sharing)

## 📘 Cómo reproducir el análisis

1. Abre `notebooks/sprint7-final-project.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/`
