**CASO DE USO N°1**: **CREACIÓN DE REPORTES DE GESTIÓN**

**A) Situación:**
  
  En noviembre de 2022 una empresa de bebidas requería reportes de gestión de gastos completos y precisos desde enero de 2021 hasta la fecha actual. Estos informes eran esenciales para analizar patrones de gasto, identificar áreas de ahorro potencial y tomar decisiones informadas sobre la asignación de recursos.

**B) Solución:**
  
  Implementé un proceso de tres pasos en general para lograr este objetivo:
  
***1. Preparación de datos y diseño inicial en Excel:***
  - Recopilación de datos: Comencé recopilando todos los datos de facturación desde enero de 2021 hasta la fecha actual. Esto implicó revisar diversas fuentes de archivos digitales, ya que eran 3 tipos de servicio de 25 centros operativos más 1 embotelladora.
  - Limpieza y organización de datos: Una vez recopilados, limpié y organicé los datos para garantizar su precisión y consistencia. Elimine filas duplicadas, correjí errores de formato y aseguré que todos los campos tuvieran nombres y formatos uniformes.
  - Consolidación de datos: Los consolidé en un único archivo de Excel para facilitar el análisis posterior.
  - Creación de un tablero preliminar en Excel: Diseñé un tablero en Excel **(Imágenes 1 y 2)** como base para la elaboración de informes en Power BI. Esto me permitió definir los KPIs y métricas con claridad y consistencia, y comenzar a ajustar las visualizaciones a las necesidades de los usuarios, las cuales eran evidenciadas en cada reunión que teníamos para exponer los resultados del mes en curso.

***2. Creación de informes en Power BI:***
  - Importación de datos: Importé el archivo de Excel consolidado a Power BI.
  - Modelado de datos: Creé un modelo de datos que representaba las relaciones entre las diferentes tablas de datos. Esto me permitió realizar análisis más profundos, complejos y precisos.
  - Visualizaciones: Utilicé diversas visualizaciones de Power BI, como gráficos de barras, de líneas, circular y matrices, para presentar los datos de manera clara, concisa y atractiva.
  - Reportes: Agrupé los cuadros de mando y visualizaciones creadas en reportes completos **(Imágenes 3, 4, 5 y 6)** que proporcionaban una visión general de los gastos de la empresa.

***3. Gestión de los informes en Power BI:***
  - Obtener Licencias Pro de Power BI: Gestioné la obtención de las licencias para los usuarios de los informes con el Área de Compras y resolví junto con TI las incidencias que surgieron para su ejecución.
  - Compartir informes: Compartí los informes con las partes interesadas, como los gerentes y administradores generales, para así facilitar la toma de decisiones.
  - Implementación de los reportes: Implementé mejoras y nuevas visualizaciones en los reportes para atender las nuevas necesidades de información que iban surgiendo de los usuarios.

**C)  Beneficios:**
  
  La implementación de este proceso permitió obtener varios beneficios:
  - Análisis mejorado de gastos: Pude analizar los datos en detalle, identificando las causas de las variaciones de los gastos y generando oportunidades para optimizar la asignación de recursos.
  - Mayor visibilidad de patrones de gasto: Las visualizaciones de Power BI facilitaron la identificación de tendencias y anomalías en los patrones de gasto de la empresa.
  - Reportes completos y dinámicos: Creé reportes completos, interactivos y fáciles de entender que fueron bien recibidos por las partes interesadas.

**D) Conclusión:**
  
  La creación de informes de gestión de gastos en Power BI resultó ser una experiencia enriquecedora que profundizó mis conocimientos y destrezas en análisis de datos. Al seguir los pasos descritos en este caso de uso y utilizar las herramientas y técnicas adecuadas, pude solucionar la necesidad de contar con estos informes para la toma de decisiones informadas de la empresa de bebidas.

  

**CASO DE USO N°2**: **CREACIÓN DE PLANTILLAS DE PAGO VARIABLE**

**A) Situación:**

Una empresa de consumo masivo necesitaba un nuevo sistema para calcular y pagar las variables de los colaboradores del canal moderno ya que los KPI habían cambiado y sus escalas de pago también. 

**B) Solución:**

Observé dos conjuntos de KPI: KPI por tienda y KPI por colaborador, por lo que creé dos plantillas de pago de variables automatizadas utilizando herramientas de análisis de datos:

***1) Plantilla 1: Consolidación de pagos por cumplimiento de colaborador***

- Objetivo: Calcular el pago total de cada colaborador en base a su porcentaje de cumplimiento individual de los KPI.
- Procedimiento:
  Importar datos de KPI por colaborador.
  Crear columnas con fórmulas para obtener el porcentaje de cumplimiento de cada colaborador en cada KPI.
  Crear tablas dinámicas **(imagen 7)** para relacionar el porcentaje de cumplimiento con una escala de pago predefinida.
  Generar una columna con fórmulas **(imagen 8)** para obtener el pago total según el desempeño individual de cada colaborador.
- Beneficios:
Medir el pago basado en el rendimiento individual.
Incentivar el logro de objetivos específicos por parte de los colaboradores.

***2) Plantilla 2: Cálculo del porcentaje de cumplimiento por tienda***

- Objetivo: Determinar el porcentaje de cumplimiento general de cada tienda en base a los KPI.
- Procedimiento:
  Importar datos de KPI por tienda, limpiar la data y filtrar solo las tiendas activas del canal moderno.
  Crear columnas con fórmulas para obtener el porcentaje de cumplimiento por tienda **(imagen 9)**.
- Beneficios:
Identifica tiendas con bajo rendimiento para implementar acciones correctivas.
Permite establecer comparaciones entre el rendimiento de las tiendas.

***3) Integración de plantillas:***

Se creó una plantilla final que consolidaba los resultados de las dos plantillas anteriores **(imagen 10)**.
Esta plantilla final mostraba el pago total de cada colaborador, considerando tanto su desempeño individual como el cumplimiento general de la tienda.
La plantilla final proporcionaba una visión completa del rendimiento individual y por tienda, facilitando la toma de decisiones informadas para el pago de variables.

**C) Resultados:**

- Se automatizó el proceso de cálculo y pago de variables, eliminando errores manuales y mejorando la eficiencia.
- Se incrementó la transparencia y la equidad en el sistema de pago de variables.
- Se obtuvo una mejor comprensión del rendimiento individual y por tienda, permitiendo identificar áreas de mejora y oportunidades de incentivo.
- Se fomentó la motivación y el compromiso de los colaboradores al vincular directamente su pago con el logro de objetivos.
  
**D)Conclusión:**

La creación de plantillas de pago de variables automatizadas utilizando herramientas de análisis de datos representó una solución efectiva para la empresa. Este caso de uso demuestra el poder de los datos y las herramientas analíticas para optimizar procesos, mejorar la toma de decisiones y alcanzar mejores resultados.
