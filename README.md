# Proyecto de Análisis de Clusters en Datos UFC

## Descripción General
Este proyecto se centra en la aplicación de técnicas de clustering para identificar y analizar diferentes perfiles de luchadores en la UFC (Ultimate Fighting Championship). El objetivo principal es descubrir patrones naturales y agrupaciones entre los luchadores basándose en sus características físicas, estilo de lucha y rendimiento histórico.

## Descripción del Dataset
El dataset contiene información de 6,478 peleas con 118 características, que incluyen:

### Información del Luchador
- Detalles básicos (nombres, edad, categoría de peso, género)
- Atributos físicos (altura, alcance, peso, postura)
- Rankings en diferentes categorías de peso

### Estadísticas de Combate
- Precisión de golpes significativos
- Porcentaje de derribos exitosos
- Frecuencia de intentos de sumisión
- Métodos preferidos de victoria

### Métricas de Rendimiento
- Rachas de victorias/derrotas
- Historial de victorias por método (KO, sumisión, decisión)
- Experiencia en rounds totales
- Participación en peleas por título

## Objetivos del Análisis de Clusters

1. **Identificación de Perfiles de Luchadores**
   - Agrupar luchadores según sus características compartidas
   - Descubrir patrones en estilos de lucha
   - Identificar similitudes en atributos físicos y rendimiento

2. **Análisis de Variables Clave**
Las variables seleccionadas para el clustering incluyen:
   - Atributos físicos
     * Altura (HeightCms)
     * Alcance (ReachCms)
     * Peso (WeightLbs)
   - Estadísticas de desempeño
     * Precisión de golpes (AvgSigStrPct)
     * Efectividad de derribos (AvgTDPct)
     * Intentos de sumisión (AvgSubAtt)
   - Indicadores de éxito
     * Rachas de victorias
     * Métodos de victoria predominantes
     * Experiencia en rounds totales

3. **Interpretación de Clusters**
   - Análisis de características distintivas de cada grupo
   - Evaluación de patrones de éxito dentro de cada cluster
   - Identificación de estilos de lucha predominantes

## Metodología de Clustering

### Preparación de Datos
- Selección de variables relevantes
- Normalización de datos
- Tratamiento de valores faltantes

### Técnicas de Clustering Aplicadas
- Análisis de clustering jerárquico
- K-means para identificación de grupos principales
- Validación de clusters mediante métricas de calidad

### Visualización de Resultados
- Gráficos de dispersión por clusters
- Diagramas de características principales
- Visualizaciones de perfiles de cluster

## Aplicaciones del Análisis

1. **Análisis de Estilos**
   - Identificación de patrones de éxito en diferentes estilos de lucha
   - Comprensión de ventajas y desventajas de cada perfil

2. **Análisis Competitivo**
   - Evaluación de matchups basada en perfiles de cluster
   - Identificación de fortalezas y debilidades por grupo

3. **Desarrollo de Talento**
   - Identificación de características clave por perfil de luchador
   - Comprensión de patrones de desarrollo exitosos

## Contacto
javieri@msmk.university

---
*Nota: Este proyecto se centra exclusivamente en el análisis de clusters para identificar patrones y perfiles en los datos de la UFC. No incluye elementos predictivos ni de machine learning más allá del clustering.*
