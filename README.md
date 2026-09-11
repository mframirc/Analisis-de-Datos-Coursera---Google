
# ====================================================================
#   CYCLISTIC CASE STUDY _ Analisi de Datos Coursera
#   Autor: Mauricio Ramirez Cerda
#   Objetivo: Analizar diferencias entre miembros y usuarios casuales
# ===================================================================



## 1. Contexto del negocio
Cyclistic opera un sistema de bicicletas compartidas con más de 5.800 bicicletas y 600 estaciones en Chicago.  
El objetivo estratégico es aumentar las **membresías anuales**, más rentables que los usuarios casuales.
---

## 2. Pregunta empresarial
**¿Cómo difieren los usuarios casuales y los miembros anuales en su comportamiento de uso del sistema Cyclistic?**

---

## 3. Metodología
Proceso aplicado:

- Preguntar  
- Preparar  
- Procesar  
- Analizar  
- Compartir  
- Actuar  

---

## 4. Preparación y limpieza de datos

### Acciones realizadas:
- Conversión de fechas
- Cálculo de `ride_length`
- Eliminación de valores negativos
- Estandarización de `usertype`
- Creación de `day_of_week` en español
- Ordenamiento de días
- Manejo de outliers
- Exportación del dataset limpio

### Resultado:
**3.745.949 filas y 15 columnas**
---

## 5. Análisis descriptivo

### 5.1 Duración promedio
≈ **1.416 segundos** (~23,6 minutos)

### 5.2 Distribución
La mayoría de los viajes duran entre 400 y 1.200 segundos.  
Existen outliers extremos.

### 5.3 Patrones por día
- Member → lunes a viernes  
- Casual → sábado y domingo

### 5.4 Estaciones
- Member → zonas corporativas  
- Casual → zonas turísticas

### 5.5 Patrones por hora
- Member → 8:00 y 17:00  
- Casual → 11:00–17:00

---

## 6. Visualizaciones
- KPI de duración promedio  
- Barras por tipo de usuario  
- Histograma (< 3600)  
- Boxplot  
- Top estaciones  
- Heatmap día vs hora  
- Segmentadores  

---

## 7. Insights clave
1. Casual viajan más tiempo  
2. Member viajan más seguido  
3. Estaciones revelan segmentos distintos  
4. Fines de semana son clave  
5. Outliers deben filtrarse  

---

## 8. Recomendaciones
1. Campañas orientadas a conveniencia  
2. Incentivos para transformar uso recreativo en recurrente  
3. Segmentación geográfica inteligente  
4. Gamificación y descuentos iniciales  

---

## 9. Conclusión
Cyclistic puede aumentar membresías anuales mediante:

- Segmentación basada en comportamiento  
- Campañas inteligentes  
- Incentivos orientados a conveniencia  
- Estrategias geolocalizadas  

Los datos muestran el camino.  
La estrategia lo ejecuta.
