# analitica-avanzada
Curso Analítica Avanzada en ESCOM — Proyecto, entrega 1

**Tema:** contaminación del aire en la ZMVM: cuándo sube (meteorología diaria, RAMA + REDMET 2015-2024) y quién la respira (Censo 2020 + satélite + estación más cercana, del EDA anterior).

| Archivo | Contenido |
|---|---|
| `EDA_entrega1.ipynb` | Notebook completo: puntos 1 a 7 + conclusiones. Corre en Colab y en local |
| `datos/inegi_loc.csv`, `datos/cont_loc_mean.csv`, `datos/*_satelite_2020.nc`, `datos/municipios_cdmx_edomex.gpkg` | Datos del EDA anterior (censo, promedios por localidad, satélite, municipios) |
| `datos/dataset_localidades.csv` | Dataset por localidad: 5,085 localidades (censo + satélite + estación RAMA más cercana) |
| `datos/resumen_estaciones.csv` | Resumen por estación: días sobre la norma, promedios 2020 y satélite |
| `datos/rama/` | 20 archivos horarios originales (contaminantes y meteorología, 2015-2024) + catálogo de estaciones |
| `datos/dataset_final_diario.csv` | Dataset final: 3,653 días × 37 variables |
| `datos/diccionario_dataset_diario.csv` | Descripción de cada variable |
| `datos/rama_diario_estacion.csv.gz` | Promedios diarios por estación y parámetro |
| `datos/rama_perfil_horario.csv` | Promedio por hora del día |
| `figuras_rama/` | Figuras del reporte |
