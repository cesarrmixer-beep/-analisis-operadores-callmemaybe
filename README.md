# Análisis de Eficiencia de Operadores - CallMeMaybe

CallMeMaybe necesita desarrollar un sistema de supervisión que identifique a los operadores ineficientes. El objetivo es detectar operadores con alto número de llamadas entrantes perdidas, largos tiempos de espera y pocas llamadas salientes realizadas.

### 🎯 Objetivo del proyecto
Identificar diferencias significativas entre operadores eficientes e ineficientes para proponer un plan de mejora basado en datos.

### 🛠️ ¿Qué hice?
1.  **Limpieza de datos:** Tratamiento de valores ausentes, ajuste de formatos y verificación de calidad de la información.
2.  **Análisis de métricas clave:** Cálculo de promedio de tiempo de espera, % de llamadas perdidas y volumen de llamadas salientes.
3.  **Prueba estadística:** Aplicación de prueba de comparación de grupos (T-test) para validar estadísticamente la diferencia entre grupos.

### 🔎 Principales Hallazgos
* Se clasificaron dos grupos de operadores: **eficientes e ineficientes**.
* Existe una diferencia estadísticamente significativa en el tiempo promedio de espera entre ambos grupos.
* El grupo ineficiente presenta mayor tiempo de espera y mayor tasa de llamadas perdidas.

### 💼 Recomendaciones de Negocio
Se propone implementar un esquema de metas escalonadas para el grupo ineficiente:
* Metas diarias, luego semanales y finalmente mensuales.
* Dejar en claro que los resultados serán parte de la evaluación de desempeño y de la posible renovación de contrato con la empresa prestadora de servicio.

### 💻 Stack Tecnológico
Python, Pandas, NumPy, Matplotlib, SciPy (Pruebas estadísticas)

### 📊 Presentación del proyecto
[Ver presentación completa aquí](https://drive.google.com/file/d/16cTJkPTimB0diGoEHM1frn6MaGs1sH70/view?usp=sharing)
