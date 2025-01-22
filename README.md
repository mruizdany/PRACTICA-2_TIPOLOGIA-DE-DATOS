# Análisis de Accidentes de Tránsito en Bogotá

## Introducción
Este proyecto tiene como objetivo analizar un conjunto de datos de accidentes de tránsito en Bogotá con el fin de:
- Identificar los factores de riesgo asociados.
- Localizar las zonas de mayor vulnerabilidad.
- Proponer medidas para mejorar la seguridad vial.

## Objetivos
1. Identificar los factores que influyen en la ocurrencia de accidentes de tránsito en Bogotá.
2. Localizar las zonas de la ciudad con mayor concentración de accidentes.
3. Evaluar la efectividad de las políticas de seguridad vial implementadas.

## Datos
El análisis se basa en un conjunto de datos proporcionado por **[Fuente de los datos]**, que incluye información de accidentes de tránsito en Bogotá durante el período **[Rango de fechas]**. Las principales variables incluidas son:

- **Geográficas**: Longitud, latitud, dirección, zona.
- **Temporales**: Fecha, hora, día de la semana.
- **Vehículo**: Tipo de vehículo, servicio, sistema de transporte.
- **Actor vial**: Rol, condición, edad, género.
- **Contexto**: Condiciones climáticas, estado de la vía, tipo de siniestro.

## Metodología
1. **Limpieza de datos**:
   - Eliminación de registros duplicados.
   - Corrección de errores tipográficos.
   - Imputación de valores faltantes.

2. **Análisis exploratorio**:
   - Visualización de la distribución de las variables.
   - Identificación de patrones iniciales mediante gráficos descriptivos.

3. **Modelado**:
   - Construcción de modelos de regresión logística para identificar factores significativos en la gravedad de los accidentes.

4. **Análisis espacial**:
   - Uso de herramientas de geoprocesamiento para identificar zonas de alto riesgo.
   - Análisis de la distribución espacial de los accidentes mediante mapas de calor.

## Resultados
- **Frecuencia de accidentes**: La mayoría de los accidentes ocurren durante las horas pico y los fines de semana.
- **Zonas críticas**: Alta concentración de accidentes en zonas céntricas y principales vías de la ciudad.
- **Factores clave**:
  - Edad del conductor.
  - Condiciones climáticas adversas.
  - Tipo de vía.

## Visualizaciones
1. **Distribución temporal de accidentes**:
   - Gráficos de barras mostrando accidentes por día de la semana.
   - Series de tiempo para accidentes diarios.
2. **Mapas espaciales**:
   - Mapas de calor destacando las zonas con mayor cantidad de accidentes.

## Conclusiones
1. **Principales hallazgos**:
   - Los accidentes son más frecuentes en horarios de alta movilidad y en condiciones climáticas desfavorables.
   - La infraestructura vial en zonas críticas necesita atención inmediata.

2. **Implicaciones**:
   - Los resultados subrayan la necesidad de políticas públicas enfocadas en horarios críticos y zonas vulnerables.

3. **Limitaciones**:
   - La calidad de los datos depende de los registros proporcionados.
   - Algunas variables pueden tener datos incompletos.

4. **Recomendaciones**:
   - Implementar campañas de educación vial enfocadas en los horarios de mayor riesgo.
   - Mejorar la infraestructura en zonas identificadas como críticas.
   - Ampliar los estudios a períodos más largos para identificar tendencias a largo plazo.

## Herramientas Utilizadas
- **Lenguaje de programación**: R
- **Librerías principales**: `tidyverse`, `ggplot2`, `leaflet`, `sf`, `caret`
- **Entorno de desarrollo**: RStudio

## Contribuciones
Para contribuir, envía tus sugerencias a través de un pull request o contacta con el equipo del proyecto.
