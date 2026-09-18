# 📊 Análisis del Impacto de la IA en el Riesgo de Despido Laboral

[![Ver video del dashboard](https://img.youtube.com/vi/GH1ixV-S0Fo/0.jpg)](https://youtu.be/GH1ixV-S0Fo)

---

## 🎯 Descripción del Proyecto

Dashboard analítico desarrollado en **Power BI** que explora la relación entre la adopción de Inteligencia Artificial y el riesgo de despido en **20,000 empleados**, aplicando la metodología **CRISP-DM** para garantizar un proceso estructurado de análisis.

El proyecto busca responder la siguiente pregunta de negocio:

> **¿Qué características demográficas, profesionales y de uso de IA están más fuertemente asociadas con un alto riesgo de despido?**

---

## 🔍 Contexto

La adopción acelerada de Inteligencia Artificial está transformando el mercado laboral. Las empresas necesitan entender qué perfiles de empleados son más vulnerables al desplazamiento laboral para implementar estrategias proactivas de reentrenamiento y retención de talento.

---

## 📈 Funcionalidades del Dashboard

### Tarjetas KPI
- Total de empleados: **20,000**
- Empleados con riesgo alto: **6,797**
- Porcentaje de riesgo alto: **34%**
- Promedio de tareas rutinarias: **52%**
- Promedio de edad: **40 años**

### Filtros Interactivos (Slicers)
- **Industry**: Industria del empleado
- **Company_Size**: Tamaño de la empresa
- **AI_Adoption_Level**: Nivel de adopción de IA

### Visualizaciones
- **Distribución de Riesgo por Industria** (Gráfico de barras apiladas)
- **Relación: Tareas Rutinarias vs Riesgo** (Gráfico de dispersión con línea de tendencia)
- **Promedio de Horas de IA por Nivel de Riesgo** (Gráfico de barras)
- **Métricas por Rol** (Tabla resumen)

---

## 💡 Hallazgos Principales

| # | Hallazgo | Evidencia |
|---|----------|------------|
| 1 | **Las tareas rutinarias aumentan el riesgo** | Los empleados con riesgo alto tienen **75,17%** de tareas rutinarias vs **28,54%** de riesgo bajo (diferencia de **46,63 puntos**) |
| 2 | **El uso de IA aumenta el riesgo** | Los empleados con riesgo alto usan IA **10,8 horas/semana** vs **3,3 horas** de riesgo bajo (diferencia de **7,5 horas**) |
| 3 | **La industria influye en el riesgo** | **Manufacturing, Retail y Finance** tienen mayor % de riesgo alto; **IT, Healthcare y Education** tienen menor % |
| 4 | **El nivel educativo no protege del riesgo** | No se encontró relación significativa entre nivel educativo y riesgo de despido |

---

## 🛠️ Herramientas Utilizadas

- **Power BI Desktop**: Desarrollo del dashboard interactivo
- **Power Query**: Limpieza y transformación de datos (ETL)
- **DAX**: Creación de medidas calculadas y KPIs
- **Metodología CRISP-DM**: Marco estructurado de 6 fases para el análisis

---

## 📐 Metodología CRISP-DM Aplicada

1. **Comprensión del Negocio**: Definición del problema, objetivos y criterios de éxito.
2. **Comprensión de los Datos**: Análisis exploratorio del dataset (20,000 registros, 16 variables).
3. **Preparación de los Datos**: Limpieza en Power Query, creación de columna `Risk_Score`.
4. **Modelado**: Construcción de medidas DAX y visualizaciones en Power BI.
5. **Evaluación**: Interpretación de hallazgos y validación de hipótesis.
6. **Despliegue**: Presentación de resultados mediante dashboard y recomendaciones.

---

## 📫 Contacto

**Juan Sebastián Ramírez Rodríguez**

⭐ Interesado en oportunidades como Analista de Datos o Business Intelligence
