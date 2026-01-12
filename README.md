**TFG – Respiratory Trace Analysis for DIBH Treatments**

Este repositorio contiene el código desarrollado y utilizado para el análisis de trazas respiratorias adquiridas durante tratamientos de DIBH en el contexto del TFG.

El repositorio se compone principalmente de dos notebooks:

📁 _TFG-Raw_Data_Analyser.ipynb_

Este notebook se encarga del procesado inicial de los datos brutos procedentes de las máquinas de tratamiento:

Lectura y estructuración de archivos de sesión.

Limpieza, concatenación temporal y gestión de solapamientos entre sesiones.

Construcción de líneas temporales coherentes para cada paciente y sesión.

Este módulo fue desarrollado previamente al TFG, pero ha sido utilizado y adaptado como base fundamental para el análisis posterior presentado en el trabajo.

📁 _TFG-Parameter_Evaluator.ipynb_

Este notebook ha sido desarrollado íntegramente desde cero para el TFG y constituye el núcleo del análisis cuantitativo:

Segmentación de las trazas en distintas fases respiratorias.

Evaluación de parámetros estadísticos (medianas, IQR, incrementos entre fases).

Análisis de la evolución intra- e inter-sesión.

Visualización mediante boxplots y representaciones comparativas.

📝 **Documentación interna**

Un aspecto clave del repositorio es que cada función definida en ambos notebooks está documentada en una celda de Markdown individual dentro del propio archivo, siguiendo un formato homogéneo y explicativo.
Esto permite:

Comprensión detallada del flujo del análisis.

Trazabilidad metodológica.

Reproducibilidad del estudio.

ℹ️ **Notas adicionales**

El código está orientado a un análisis exploratorio y cuantitativo, no a uso clínico directo.

Se ha priorizado la claridad metodológica y la coherencia estadística frente a la optimización computacional.

El repositorio está pensado para acompañar la memoria del TFG, sirviendo como soporte técnico y verificable de los resultados presentados.
