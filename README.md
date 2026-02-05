Descripción general:

Este repositorio contiene la documentación, datos y procesos utilizados para el análisis exploratorio y modelado sobre una base de datos de salarios internacionales.
El objetivo del proyecto es estandarizar la información proveniente de múltiples países y monedas, aplicar procesos de limpieza y transformación de datos, y construir visualizaciones que permitan comparar ingresos entre distintas variables como industria, educación, ubicación geográfica y perfil demográfico.

Dashboard interactivo:

El dashboard principal del proyecto se encuentra publicado en Looker Studio:

https://lookerstudio.google.com/u/0/reporting/c7b78752-05c1-4614-bc74-8ed2e47d8931/page/TCHnF
  
  Este tablero incluye:
  
  Distribución geográfica de los encuestados
  
  Análisis de ingresos por industria
  
  Comparación de ingresos por nivel educativo
  
  Perfil general de los participantes (edad, género, educación)
  
  Métricas generales de la muestra

El dashboard utiliza datos previamente limpiados y transformados siguiendo el proceso documentado en este repositorio.


Contenido del repositorio:

Base de datos:

Se incluye la base de datos raw lista para ingresar al codigo de limpieza.

Mantiene la estructura original para facilitar futuras actualizaciones.

Script de limpieza (Country clean.py):
El archivo Python contiene el proceso de limpieza y estandarización, incluyendo:
*Normalización de textos.
*Limpieza y unificación de países (ej: variantes de USA → United States).
*Eliminación de valores no válidos o ambiguos.
*Creación de variables limpias listas para análisis.

Documentación:

La documentación incluye:

*Descripción detallada de variables.
*Tipos de datos.
*Procedimientos de limpieza.
*Conversión de divisas.
*Creación de variables derivadas.
*Implementación del modelado y lógica analítica.


Objetivo del repositorio:

Este repositorio funciona como un sitio centralizado de documentación y análisis, simulando una práctica común en equipos de analytics: crear micro-sitios o repositorios que integren datos, procesos y visualizaciones en un solo lugar para facilitar la replicabilidad y el mantenimiento del proyecto.
