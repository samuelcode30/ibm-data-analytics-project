# Análisis Histórico de Acciones e Ingresos: Tesla y GameStop 📊

Este proyecto es una demostración práctica de extracción, limpieza y visualización de datos financieros utilizando Python. El objetivo principal es analizar la relación histórica entre los ingresos trimestrales y el precio de las acciones de dos grandes compañías: Tesla y GameStop.

## 🛠️ Tecnologías y Herramientas Utilizadas
- **Python:** Lenguaje principal de análisis.
- **Pandas:** Para la manipulación, limpieza y estructuración de los datos.
- **BeautifulSoup (bs4):** Para realizar Web Scraping y extraer tablas de ingresos desde código HTML.
- **yfinance:** Para la extracción de datos históricos de mercado a través de la API de Yahoo Finance.
- **Plotly:** Para la creación de dashboards y gráficos interactivos.

## ⚙️ Metodología del Proyecto
1. **Extracción mediante API:** Obtención del histórico de precios de las acciones (`TSLA` y `GME`) usando la librería `yfinance`.
2. **Web Scraping:** Extracción de datos de ingresos históricos desde una página web estructurada parseando el HTML con `BeautifulSoup`.
3. **Limpieza de Datos (Data Cleaning):**
   - Eliminación de caracteres especiales (signos `$` y comas) de la columna de ingresos utilizando expresiones regulares (Regex).
   - Tratamiento de valores nulos (NaN) y cadenas vacías para asegurar la integridad de la información.
4. **Visualización:** Generación de un dashboard comparativo (Precio de la acción vs. Ingresos) para identificar tendencias a lo largo del tiempo, como el crecimiento exponencial de Tesla y la volatilidad histórica de GameStop.

## 📈 Resultados y Visualizaciones
*(Nota: GitHub no renderiza gráficos dinámicos de Plotly directamente en el visor de código. A continuación se muestran capturas de pantalla de los resultados. Puedes interactuar con el código haciendo clic en el botón "Open in Colab" del archivo `.ipynb`).*

**Dashboard de Tesla:**
<img width="1015" height="900" alt="Tesla" src="https://github.com/user-attachments/assets/3a82adbe-2c39-42e1-8387-92b260d9c13e" />

**Dashboard de GameStop:**
<img width="1015" height="900" alt="GameStop" src="https://github.com/user-attachments/assets/174a61a5-5714-4536-8419-4d43b7b30297" />


## 👨‍💻 Autor
**Samuel Chaupis**
* Analista de Datos Junior 
* [Mi Perfil de LinkedIn] https://www.linkedin.com/in/samuel-chaupis/
