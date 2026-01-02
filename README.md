# 📊 Proyecto 12. Análisis de Tendencias de Videos en YouTube | Dashboard en Tableau

## 🧩 Descripción del proyecto
Este repositorio consiste en el diseño y desarrollo de un dashboard interactivo en Tableau Public para analizar el historial de tendencias de videos en YouTube.  
El objetivo es apoyar la toma de decisiones en marketing digital, identificando qué categorías de videos son más populares, cómo se distribuyen por región y cómo evolucionan en el tiempo.

El dashboard fue desarrollado como un **caso real de negocio** para la agencia publicitaria Sterling & Draper.

---

## 🎯 Objetivo de negocio
- Analizar el comportamiento histórico de videos en tendencia.
- Identificar categorías más populares a nivel global y por país.
- Detectar diferencias de consumo entre Estados Unidos y otras regiones.

---

## 👥 Usuario objetivo
Gerentes de planificación de videos publicitarios y equipos de marketing.

---

## 📈 Contenido del dashboard
El dashboard incluye:

- **Historial de tendencias por fecha y categoría**
  - Valores absolutos (gráfico de área)
  - Porcentaje del total (gráfico de área)
- **Distribución de tendencias por país**
  - Gráfico de pastel con valores relativos
- **Tendencias por país y categoría**
  - Tabla con valores absolutos y formato condicional
- **Filtros interactivos**
  - Fecha
  - País

---

## 🗂️ Dataset
Fuente de datos: `trending_by_time.csv`

**Campos principales:**
- `record_id`: identificador único
- `region`: país
- `trending_date`: fecha de tendencia
- `category_title`: categoría del video
- `videos_count`: número de videos en tendencia

Los datos se actualizan cada 24 horas (UTC).

---

## 🔍 Principales insights
- **Entretenimiento** domina las tendencias en todas las regiones.
- Estados Unidos lidera en volumen de videos en tendencia, seguido de Francia, Rusia e India.
- Existen diferencias claras en preferencias por país, especialmente en categorías como:
  - Personas & Blogs
  - Noticias y Política
  - Tutoriales

Estos hallazgos permiten adaptar estrategias de marketing por región.

---

## 🛠️ Herramientas utilizadas
- Tableau Public – visualización y dashboard
- Python (Pandas) – exploración y validación de datos
- Jupyter Notebook – análisis preliminar

---

## 🔗 Dashboard interactivo
👉 [Ver dashboard en Tableau Public](https://public.tableau.com/views/DashboardProyectoSprint12/Dashboard1)
