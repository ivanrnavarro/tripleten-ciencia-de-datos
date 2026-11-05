# Bootcamp de Ciencia de Datos — TripleTen

Proyectos desarrollados por **Iván Ricardo Navarro Espinosa** (Ingeniero Químico, MSc) durante el bootcamp de Ciencia de Datos de TripleTen (enero – noviembre 2026).

El repositorio reúne los proyectos de cada sprint, desde la limpieza de datos con Python básico hasta modelos de machine learning, series temporales, procesamiento de lenguaje natural y visión por computadora. Cada carpeta contiene el notebook final del proyecto con su código, gráficos, observaciones y conclusiones.

## Proyectos destacados

| Proyecto | Tema | Resultado |
|---|---|---|
| [Interconnect](19_Interconnect_Prediccion_fuga_clientes_Proyecto_final) | Predicción de fuga de clientes (proyecto final) | ROC-AUC de 0,91 |
| [Zyfra](13_Zyfra_Prediccion_recuperacion_de_oro) | Predicción de la recuperación de oro en un proceso industrial | sMAPE final de 9,73 % |
| [Sweet Lift Taxi](16_SweetLiftTaxi_Pronostico_pedidos_series_temporales) | Pronóstico de pedidos por hora con series temporales | RECM en prueba bajo el umbral de 48 |
| [Film Junky Union](17_FilmJunky_Clasificacion_resenas_NLP) | Clasificación de reseñas de películas (NLP) | F1 de 0,88 |
| [OilyGiant](12_OilyGiant_Seleccion_region_pozos_petroleo_bootstrap) | Selección de región para pozos petroleros con bootstrapping | Región elegida con riesgo de pérdida menor al 2,5 % |

## Todos los proyectos

| Sprint | Proyecto | Descripción | Técnicas y herramientas |
|---|---|---|---|
| 1 | [Store 1 — Limpieza de datos](01_Store1_Limpieza_datos_clientes_Python) | Limpieza y estandarización de registros de clientes | Python · cadenas · listas |
| 2 | [Store 1 — Procesamiento de datos](02_Store1_Procesamiento_datos_clientes_listas_y_bucles) | Procesamiento de una base cruda de clientes y sus compras | Python · listas anidadas · bucles · funciones |
| 3 | [Preferencias musicales](03_Preferencias_musicales_Springfield_vs_Shelbyville) | Comparación de hábitos de escucha entre dos ciudades | pandas · duplicados y valores ausentes |
| 4 | [Instacart](04_Instacart_Analisis_habitos_de_compra) | Análisis de hábitos de compra en una plataforma de mercado | pandas · matplotlib · EDA |
| 5 | [Megaline — Tarifas](05_Megaline_Comparacion_tarifas_prueba_de_hipotesis) | Comparación de ingresos entre dos planes de telefonía | pandas · seaborn · SciPy · pruebas de hipótesis |
| 6 | [Ice — Videojuegos](06_Ice_Analisis_ventas_videojuegos) | Patrones de venta por plataforma, género y región para planear la campaña 2017 | pandas · seaborn · SciPy · prueba t |
| 8 | [Zuber — Taxis en Chicago](08_Zuber_Viajes_taxi_Chicago_prueba_de_hipotesis) | Viajes por empresa y barrio, y efecto del clima en la duración | pandas · seaborn · SciPy · pruebas de hipótesis |
| 10 | [Megaline — Recomendación de planes](10_Megaline_Clasificacion_recomendacion_de_planes) | Clasificador para recomendar el plan Smart o Ultra | scikit-learn · árbol de decisión · bosque aleatorio · regresión logística |
| 11 | [Beta Bank](11_BetaBank_Prediccion_abandono_clientes) | Predicción de abandono de clientes con clases desbalanceadas | scikit-learn · sobremuestreo · F1 · ROC-AUC |
| 12 | [OilyGiant](12_OilyGiant_Seleccion_region_pozos_petroleo_bootstrap) | Selección de la región más rentable para nuevos pozos | scikit-learn · regresión lineal · bootstrapping · análisis de riesgo |
| 13 | [Zyfra](13_Zyfra_Prediccion_recuperacion_de_oro) | Predicción de la recuperación de oro por etapa del proceso | scikit-learn · validación cruzada · sMAPE |
| 14 | [Sure Tomorrow](14_SureTomorrow_Algebra_lineal_y_ofuscacion_de_datos) | Clientes similares, predicción de prestaciones y ofuscación de datos personales | NumPy · álgebra lineal · kNN · regresión lineal propia |
| 15 | [Rusty Bargain](15_RustyBargain_Prediccion_precio_autos_usados) | Predicción del precio de autos usados priorizando calidad y tiempo de entrenamiento | LightGBM · CatBoost · XGBoost · scikit-learn |
| 16 | [Sweet Lift Taxi](16_SweetLiftTaxi_Pronostico_pedidos_series_temporales) | Pronóstico de pedidos de taxi para la próxima hora | statsmodels · ingeniería de características · scikit-learn |
| 17 | [Film Junky Union](17_FilmJunky_Clasificacion_resenas_NLP) | Detección automática de reseñas negativas | NLTK · spaCy · TF-IDF · LightGBM · BERT |
| 18 | [Good Seed](18_GoodSeed_Estimacion_edad_vision_por_computadora) | Estimación de la edad de clientes a partir de fotografías | TensorFlow / Keras · ResNet50 · EAM |
| 19 | [Interconnect](19_Interconnect_Prediccion_fuga_clientes_Proyecto_final) | Sistema de predicción de cancelación de clientes (proyecto final) | scikit-learn · LightGBM · ajuste de umbral · ROC-AUC |

## Sobre los datos

Los conjuntos de datos fueron proporcionados por la plataforma de TripleTen y se leían desde rutas internas (`/datasets/...`), por lo que no se incluyen en este repositorio. Los notebooks conservan las salidas de la ejecución original, así que los resultados y gráficos pueden consultarse sin volver a ejecutarlos.

## Herramientas

Python · pandas · NumPy · Matplotlib · seaborn · SciPy · statsmodels · scikit-learn · LightGBM · CatBoost · XGBoost · NLTK · spaCy · Transformers · PyTorch · TensorFlow / Keras · Jupyter

Las dependencias están en [`requirements.txt`](requirements.txt).

## Contacto

- GitHub: [ivanrnavarro](https://github.com/ivanrnavarro)
- Correo: ivanrnavarro@gmail.com
