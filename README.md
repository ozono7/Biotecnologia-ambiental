# Biotecnología Ambiental

Simulaciones en R del tratamiento biológico de aguas residuales: qué le
pasa a una planta cuando algo sale mal y cómo se comparan las
alternativas de tratamiento. Cada archivo simula un escenario real de
operación —choques de carga, vertidos tóxicos, tormentas, fallas de
sedimentación— y muestra el resultado con gráficas.

## Contenido

- **Choque de carga:** efecto de un aumento súbito de carga sobre el
  sistema biológico.
- **Estabilidad de lodos activados:** dinámica del sistema en cuatro
  estados críticos.
- **Sedimentación secundaria:** diseño y análisis hidráulico del
  sedimentador, impacto de una tormenta y falla por ingreso de
  desinfectantes clorados.
- **Vertidos tóxicos:** impacto sobre el tratamiento de aguas residuales
  de una planta de alimentos.
- **Casos por industria:** planta de procesados cárnicos y planta de
  alimentos.
- **Comparación de tecnologías:** torre biológica contra contactor
  biológico rotativo (RBC) y comparación de reactores biológicos.
- **Apoyo:** ejemplo básico de gráficos con ggplot2.

## Residuos peligrosos: clasificación CRETIB

- **01 Clasificación CRETIB de residuos peligrosos (NOM-052-SEMARNAT):**
  clasificación de residuos de laboratorio y de planta con los
  criterios CRETIB (Corrosivo, Reactivo, Explosivo, Tóxico ambiental,
  Inflamable y Biológico-infeccioso) a partir de mediciones de pH,
  punto de inflamación, prueba de extracción PECT y generación de
  gases.
- **Próximas lecciones:** listados de residuos peligrosos de la
  NOM-052, incompatibilidad y almacenamiento de residuos, y
  manifiesto de entrega y transporte.

## Ingeniería

Seguridad industrial, higiene y respuesta a emergencias en laboratorio
y planta (carpeta `ingenieria/`):

- **01 Análisis de riesgo:** matriz de probabilidad y severidad 5 x 5
  aplicada a peligros del laboratorio y la planta piloto.
- **02 Seguridad e higiene industrial:** identificación de peligros en
  un área de trabajo y medidas de control según la jerarquía de
  controles.
- **03 Análisis de gases:** monitoreo de exposición ocupacional a
  gases en aire frente a los valores límite de la NOM-010-STPS-2014.
- **04 Análisis de polvos:** monitoreo de exposición ocupacional a
  polvos en aire (fracciones respirable e inhalable) frente a la
  NOM-010-STPS-2014.
- **05 Análisis de químicos:** exposición ocupacional a solventes,
  con cálculo del promedio ponderado en el tiempo (TWA) de 8 horas.
- **06 Clasificación GHS/SGA:** pictogramas, frases H y palabra de
  advertencia de sustancias de laboratorio.
- **07 Reacción ante fugas, derrames y contaminantes:** respuesta a
  un derrame de ácido sulfúrico, neutralización, cronología y zonas
  de afectación.
- **Próximas lecciones:** HAZOP y análisis de riesgo por proceso,
  espacios confinados, investigación de incidentes y simulacros, y
  equipo de protección personal por tarea.

## Cómo usarlo

Cada archivo es una simulación independiente y documentada: ábrelo en R
o RStudio y ejecútalo completo. Solo necesitas R instalado; los paquetes
que usa cada archivo se indican al inicio del mismo.

## Autor

**Dr. José Juan Torres Martínez**
Docente de Ciencias Químicas
Universidad Autónoma de San Luis Potosí (UASLP), México

Material académico para estudiantes.
