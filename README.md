# Profesionales de Medicina (Argentina & EE. UU.)

 ## 📘 Autor
**Héctor Alejandro Roa**  
*Proyecto Final – Data Science – Coderhouse (2025)*  
[GitHub Repository](https://github.com/roahalejandro/ProyectoDS_)

---

## Objetivo General
Analizar la composición, distribución y evolución del cuerpo médico argentino entre 2012 y 2021 — considerando sexo, edad, provincia de residencia, institución formadora y país de nacimiento — y contrastarla con los patrones observados en Estados Unidos según el *FSMB Census of Licensed Physicians (2024)*.

El propósito final es **evaluar la dependencia relativa de cada país respecto de los médicos extranjeros** y comprender cómo las diferencias demográficas y formativas influyen en la sostenibilidad de los sistemas de salud.

## Parte I – Exploración y Caracterización del Cuerpo Médico Argentino

La primera fase del proyecto se centró en un **Análisis Exploratorio de Datos (EDA)** sobre la base “Serie de Profesionales de Medicina (2012–2021)” publicada por el Ministerio de Salud de la Nación Argentina.  
El trabajo abordó la depuración, transformación y análisis visual del dataset con el fin de **identificar patrones estructurales** del ejercicio profesional en el país.

**Aspectos destacados:**
- Distribución por **sexo y grupo etario**, evidenciando un proceso sostenido de feminización de la profesión.  
- Concentración territorial del cuerpo médico en la **Ciudad Autónoma de Buenos Aires y provincias del centro**, en contraste con menor densidad en regiones del norte y sur.  
- Análisis de **instituciones formadoras**, donde la Universidad de Buenos Aires (UBA) aparece como principal núcleo de formación.  
- Evaluación de la **evolución temporal (2012–2021)**, mostrando un crecimiento estable en el total de médicos matriculados.  
- Implementación de técnicas de detección de **outliers (IQR)** para depurar valores atípicos y mejorar la consistencia estadística del conjunto.

La fase concluyó con la generación de visualizaciones descriptivas y la formulación de hipótesis sobre el grado de dependencia del sistema respecto de profesionales extranjeros.

## Parte II – Comparación Internacional (Argentina vs. Estados Unidos)

La segunda etapa amplía el análisis incorporando datos agregados del **FSMB Census of Licensed Physicians (EE. UU., 2024)**.  
A partir del EDA de la Parte I, se desarrollaron procesos de **armonización de variables** (edad, nacionalidad, origen formativo) para permitir comparaciones directas entre ambos países.

**Enfoques analíticos implementados:**
1. **Composición Nativo vs. Extranjero (%):** comparación de dependencia relativa.  
2. **Estructura Etaria Estandarizada:** detección de patrones de envejecimiento profesional.  
3. **Origen de la Formación Médica:** identificación de flujos educativos nacionales e internacionales.  
4. **Modelado Predictivo:** regresión logística y *random forest* para estimar la probabilidad de origen extranjero a partir de variables demográficas y formativas.

Los resultados confirman que la dependencia de médicos extranjeros en Argentina es **estructuralmente menor y más predecible**, mientras que en EE. UU. el fenómeno es más marcado y concentrado en ciertas regiones y grupos etarios.

---
## Datos
- Dataset oficial (no versionado aquí por tamaño):  https://datos.gob.ar/dataset/salud-serie-profesionales-medicina
- Copia personal en Google Drive (montado en Colab):
https://docs.google.com/spreadsheets/d/e/2PACX-1vQF_cDlS_VWW7WW7ExBAK8FQl9S90M7gnsMhcJzKr9zF_WxJQ7i2gy_h3R528CO06NiJPb9n3TAwxaL/pubhtml?gid=2126580806&single=true
- FSMB Census of Licensed Physicians in the United States, 2024: https://meridian.allenpress.com/jmr/article/111/2/7/507660/FSMB-Census-of-Licensed-Physicians-in-the-United
