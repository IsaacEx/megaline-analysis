# Análisis de ingresos y comportamiento de planes en Megaline

## Descripción
Análisis de datos de clientes de la empresa de telecomunicaciones **Megaline** para determinar cuál de los planes de servicio —**Surf** o **Ultimate**— genera mayores ingresos promedio por usuario. El proyecto incluyó limpieza y preparación de datos, análisis exploratorio y pruebas estadísticas para validar hipótesis.

## Objetivo
Identificar diferencias en el consumo y los ingresos generados por cada plan, así como evaluar si existen variaciones significativas por región, con el fin de orientar estrategias comerciales y de optimización de planes.

---

## Herramientas utilizadas
- Python
- Pandas
- Matplotlib
- Seaborn
- NumPy
- SciPy (pruebas de hipótesis)

---

## Flujo de trabajo del análisis

Carga y limpieza de datos <br>
↓ <br>
Transformación y creación de variables (unidades, fechas, meses de actividad)<br>
↓ <br>
Análisis exploratorio del uso (llamadas, mensajes, datos)<br>
↓ <br>
Cálculo de ingresos por usuario y plan<br>
↓ <br>
Pruebas de hipótesis para comparar planes y regiones<br>
↓ <br>
Conclusiones y recomendaciones 

---

## Principales hallazgos

### Limpieza y preparación de los datos
- Corrección de tipos de datos (fechas y formatos).
- Conversión de unidades (MB a GB).
- Creación de columnas adicionales como meses de actividad por usuario.

### Comportamiento de uso
- No se encontraron diferencias significativas en el tiempo promedio de llamadas entre planes.
- Los usuarios del plan **Ultimate** envían más mensajes y consumen más datos que los del plan **Surf**.

### Ingresos
- El plan **Ultimate** genera ingresos más altos y estables.
- El plan **Surf** presenta mayor variabilidad, con ingresos adicionales provenientes de usuarios que exceden los límites del plan.
- Ambos planes muestran incremento de ingresos hacia fin de año, lo que indica mayor consumo con el tiempo.

### Resultados estadísticos
- **Planes**: Se rechazó la hipótesis nula → existe una **diferencia estadísticamente significativa** en los ingresos promedio entre **Surf** y **Ultimate**.
- **Regiones**: No se rechazó la hipótesis nula → no hay evidencia de que los ingresos promedio sean distintos entre usuarios de Nueva York-Nueva Jersey y el resto del país.

---

## Conclusiones y recomendaciones
- **Plan Ultimate**: Genera mayores ingresos promedio sin depender del consumo excesivo. Es más rentable para promocionar.
- **Plan Surf**: Aunque su tarifa base es menor, debería optimizarse o complementarse con campañas dirigidas a usuarios de alto consumo para incrementar rentabilidad sin perjudicar la experiencia del cliente.

---

## Dataset
Datos proporcionados con fines académicos para el desarrollo del proyecto.
