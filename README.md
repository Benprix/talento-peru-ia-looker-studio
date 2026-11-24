# Talento Perú IA — Dashboard en Looker Studio

Dashboard interactivo construido desde cero en **Looker Studio** para el proyecto **Talento Perú IA**, conectado a la fuente `TalentoPeruIA_1000` con soporte de actualización dinámica de datos y filtro cruzado (**Multifiltro**).

## Fuente de Datos y Actualización
- **Origen:** hoja vinculada `TalentoPeruIA_1000` (alimentada con registros de empleabilidad, postulaciones, entrevistas, riesgo y variables geográficas/temporales).
- **Prueba de reactividad:** se verificó la actualización del tablero al incorporar nuevos registros en la hoja de cálculo y refrescar los datos en Looker Studio.

## Indicadores Clave (KPIs)
- **Porcentaje en Riesgo:** promedio del nivel de riesgo (`NivelRiesgo`).
- **Score Promedio:** promedio del puntaje de empleabilidad (`ScoreEmpleabilidad`).
- **Record Count:** cantidad total de registros analizados.
- **Tasa Conversion:** relación de entrevistas frente a postulaciones (`NumEntrevistas` / `NumPostulaciones`).

## Controles y Visualizaciones
- **Filtros superiores:** `ZonaGeografica`, `Sector`, `NivelEducativo` y `Semaforo`.
- **Fila central:**
  - `Score Promedio` por `NivelEducativo`.
  - Distribución por `Semaforo` (`Alto`, `Medio`, `Bajo`).
  - Evolución temporal (`Record Count`).
- **Fila inferior (`ZonaGeografica`):**
  - `Porcentaje en Riesgo` por zona (`Costa`, `Sierra`, `Selva`).
  - Distribución porcentual de `Modalidad` (`Presencial`, `Híbrido`, `Remoto`) por zona geográfica.
- **Interactividad:** **Multifiltro** activo en los gráficos para filtrar el panel al seleccionar categorías.

## Entregables de Semana 13 (Revisión Previa)
- Enlace a este repositorio en GitHub.
- Video de demostración del dashboard.
- Diseño de póster digital del proyecto.
## Enlaces y Evidencias
- **Dashboard interactivo (Looker Studio):** [Ver panel Talento Perú IA](PEGA_AQUI_TU_ENLACE_DE_LOOKER_STUDIO)
- **Captura del dashboard:** `dashboard/dashboard.png`
