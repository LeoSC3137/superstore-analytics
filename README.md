# 📊 Superstore Analytics — Portafolio de Consultoría Financiera

> **Análisis completo de rentabilidad, modelado financiero automatizado y forecasting de negocios.**
> Proyecto de práctica diseñado para demostrar habilidades en consultoría de datos, análisis financiero y automatización.

---

## 📈 Hallazgos Principales (Impacto de Negocio)
Antes de ver el código, estos son los descubrimientos estratégicos clave derivados del análisis:

* **Involución en Mobiliario:** La categoría *Furniture* opera con un margen crítico del **2.5%** en comparación con el **17%** que genera *Technology*.
* **El Peligro de las Promociones:** Los **descuentos superiores al 20%** destruyen el valor, generando pérdidas promedio por cada transacción.
* **Proyección de Crecimiento (2018):** El modelo predictivo estima **\$819K USD** en ventas totales, lo que representa un crecimiento del **11.7%** interanual.
* **Fuga de Margen Regional:** La *Región Central* se encuentra **4 puntos porcentuales por debajo** del promedio de margen global debido a ineficiencias operativas.

---

## 🛠️ Stack Tecnológico

![Python](https://shields.io)
![Pandas](https://shields.io)
![SQLite](https://shields.io)
![Power BI](https://img.shields.io/badge/Power%20BI-Ready-blue)



---

## 📂 Módulos y Proyectos Incluidos

### 1. Análisis de Rentabilidad y Márgenes
Estudio a fondo del impacto de las políticas de precios en la rentabilidad corporativa.
* **Alcance:** Rentabilidad por categoría/sub-categoría e impacto de los descuentos en los márgenes de ganancia.
* **Herramientas:** `Python`, `pandas`, `matplotlib`, `seaborn`.

### 2. Arquitectura de Base de Datos Relacional
Diseño y consulta de la infraestructura de datos para asegurar una única fuente de verdad.
* **Alcance:** Creación de un modelo de 4 tablas (*customers, orders, products, order_items*) y desarrollo de queries analíticos avanzados utilizando `JOIN`, `GROUP BY` y `HAVING`.
* **Herramientas:** `Python`, `SQLite`, `SQL`.

### 3. Modelo P&L Automatizado (Estado de Resultados)
Automatización de reportes financieros estándar para la toma de decisiones directivas.
* **Alcance:** Construcción de un Estado de Resultados (P&L) por año y categoría, con exportación automatizada a archivos Excel con formato ejecutivo preestablecido.
* **Herramientas:** `Python`, `pandas`, `openpyxl`.

### 4. Dashboard Ejecutivo Interactiva
Visualización dinámica de datos para el monitoreo de indicadores clave de rendimiento (KPIs).
* **Alcance:** Modelado de KPIs interactivos mediante segmentadores de datos por región y creación de medidas `DAX` para el cálculo dinámico de márgenes comerciales.
* **Herramientas:** `Power BI`, `DAX`.

### 5. Forecasting Financiero de Ventas
Predicción de flujos de caja y demanda para la planificación financiera estratégica.
* **Alcance:** Análisis de series de tiempo mensuales (periodo 2014-2017) con una proyección a 12 meses vista e intervalos de confianza.
* **Herramientas:** `Python`, `Prophet`.

### 6. Caso de Consultoría Automatizado
Generación de entregables listos para la mesa directiva (C-Suite).
* **Alcance:** Reporte automatizado en formato de presentación ejecutiva de 6 diapositivas que sintetiza de forma visual los hallazgos estratégicos y las recomendaciones de negocio.
* **Herramientas:** `Python`, `python-pptx`.

---

## 🏃‍♂️ Guía de Uso Rápido

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com
   ```
2. **Instalar dependencias necesarias:**
   ```bash
   pip install pandas matplotlib sqlite3 openpyxl prophet python-pptx seaborn
   ```
3. **Ejecutar el pipeline principal:**
   ```bash
   python main.py
   ```
