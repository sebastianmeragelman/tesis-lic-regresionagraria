
En este proyecto se propone desarrollar un modelo predictivo del rendimiento agrícola en Argentina utilizando variables climáticas como principales insumos de análisis.
Dado que no existen actualmente registros públicos que vinculen de forma directa la producción agrícola con las variables climáticas correspondientes a cada campaña, el proyecto comienza con una etapa de búsqueda, selección y transformación de datos provenientes de diversas fuentes. Para ello, se trabajó con bases de datos públicas del INTA, el portal de Datos Abiertos de la República Argentina y la NASA, complementadas con información adicional obtenida de otras fuentes relevantes.
El objetivo principal es unificar estas tres fuentes de datos en una única dimensión analítica, que permita modelar el comportamiento del rendimiento agrícola en función de las variables climáticas. A partir de este modelo, se busca también identificar posibles relaciones y patrones que puedan servir de base para futuras investigaciones en el ámbito agroclimático.

Palabras clave: Aprendizaje Automático, Argentina, Clima, Radiación Solar, Agricultura
Temática de Interés en Ciencia de Datos: Reducción dimensional,Selección de features

Para el desarrollo de esta investigación comenzamos buscando fuentes de datos confiables que puedan aportarnos material para poder trabajar sobre cada eje por separado:
Registros meteorológicos en la República Argentina desagregados por región y con datos diarios en un periodo no menor a 20 años.
Registros de áreas sembradas,cultivadas, rinde, y otros posibles datos relacionados a la producción agraria, desagregado por región y con un periodo de registro no menor a 20 años
Registros de radiación solar sobre el territorio Argentino

Una vez determinadas las fuentes de datos viables procederemos a clasificar los datos según su utilidad para esta investigación, Se prevé la posibilidad de múltiples fuentes, por lo cual se seleccionará aquella que aporte mayor utilidad para el análisis.

Ya clasificados los set de datos finales con los cuales vamos a trabajar, procederemos a generar un esquema de directorios y archivos para poder ordenar nuestro catálogo de información y maquetar el proyecto a desarrollar.

Una vez que esté toda la estructura delineada pasaremos a unificar los archivos que se puedan para simplificar los análisis y realizar un EDA sobre cada uno de los set de datos.

Con el EDA realizado se procesarán los documentos incluyendo limpieza, creación de nuevas variables, eliminación de registros inservibles.

Obtendremos los primeros resultados preliminares para obtener una hipótesis del comportamiento de los datos y con esto comenzaremos a modelar los datos para poder diseñar los experimentos que sean necesarios para evaluar la veracidad de la hipótesis planteada.

Posterior al desarrollo, puesta a prueba y obtención de las métricas de los experimentos podremos obtener ya resultados finales para desarrollar las conclusiones de la investigación.
