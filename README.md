# Reproducible_Research_Proyct_02

# Introducción
Las tormentas y otros eventos climáticos severos pueden causar problemas económicos y de salud pública para las comunidades y municipios. Muchos eventos severos pueden resultar en muertes, lesiones y daños a la propiedad, y prevenir tales resultados en la medida de lo posible es una preocupación clave.

Este proyecto implica explorar la base de datos de tormentas de la Administración Nacional Oceánica y Atmosférica de los Estados Unidos (NOAA). Esta base de datos rastrea las características de las principales tormentas y eventos climáticos en los Estados Unidos, incluido cuándo y dónde ocurren, así como estimaciones de las muertes, lesiones y daños a la propiedad.

# Datos
Los datos para esta asignación vienen en forma de un archivo de valores separados por comas comprimido mediante el algoritmo bzip2 para reducir su tamaño. Puede descargar el archivo desde el sitio web del curso:

1. Storm Data [47Mb] También hay disponible cierta documentación de la base de datos. Aquí encontrará cómo se construyen / definen algunas de las variables.

2. Documentación de datos de tormentas del Servicio Meteorológico Nacional

3. Preguntas frecuentes sobre eventos de tormentas en el Centro Nacional de Datos Climáticos

Los eventos en la base de datos comienzan en el año 1950 y terminan en noviembre de 2011. En los primeros años de la base de datos generalmente hay menos eventos registrados, probablemente debido a la falta de buenos registros. Los años más recientes deben considerarse más completos.

# Asignación
El objetivo básico de esta tarea es explorar la base de datos de tormentas de la NOAA y responder algunas preguntas básicas sobre eventos climáticos severos. Debe utilizar la base de datos para responder las preguntas a continuación y mostrar el código para todo su análisis. Su análisis puede constar de tablas, figuras u otros resúmenes. Puede utilizar cualquier paquete de R que desee para respaldar su análisis.

# Preguntas
Su análisis de datos debe abordar las siguientes preguntas:

1. En todo Estados Unidos, ¿qué tipos de eventos (como se indica en la EVTYPEvariable) son más dañinos con respecto a la salud de la población?

2. En todo Estados Unidos, ¿qué tipo de eventos tienen las mayores consecuencias económicas?

Considere la posibilidad de escribir su informe como si fuera a ser leído por un administrador del gobierno o municipal que podría ser responsable de prepararse para eventos climáticos severos y necesitará priorizar recursos para diferentes tipos de eventos. Sin embargo, no es necesario hacer recomendaciones específicas en su informe.

# Requisitos
Para esta tarea necesitará algunas herramientas específicas

* RStudio: necesitará RStudio para publicar su documento de análisis completo en RPubs. También puede utilizar RStudio para editar / escribir su análisis.

* knitr: necesitará el paquete knitr para compilar su documento R Markdown y convertirlo a HTML

# Disposición del documento
* Idioma: Su documento debe estar escrito en inglés.

* Título: su documento debe tener un título que resuma brevemente su análisis de datos

* Sinopsis: Inmediatamente después del título, debe haber una sinopsis que describa y resuma su análisis en un máximo de 10 oraciones completas .

* Debe haber una sección titulada Procesamiento de datos que describa (en palabras y código) cómo se cargaron los datos en R y se procesaron para su análisis. En particular, su análisis debe comenzar desde el archivo CSV sin procesar que contiene los datos. No puede realizar ningún procesamiento previo fuera del documento. Si el preprocesamiento requiere mucho tiempo, puede considerar usar la cache = TRUEopción para ciertos fragmentos de código.

* Debe haber una sección titulada Resultados en la que se presenten los resultados.

* Es posible que tenga otras secciones en su análisis, pero el procesamiento de datos y los resultados son obligatorios .

* El documento de análisis debe tener al menos una figura que contenga un gráfico .

* Su análisis no debe tener más de tres cifras . Las figuras pueden tener múltiples gráficos (es decir, gráficos de panel), pero no puede haber más de tres figuras en total.

* Debe mostrar todo su código para el trabajo en su documento de análisis. Esto puede hacer que el documento sea un poco detallado, pero está bien. En general, debe asegurarse de que echo = TRUEpara cada fragmento de código (esta es la configuración predeterminada en knitr).

# Publicar su análisis
Para esta tarea, deberá publicar su análisis en RPubs.com . Si aún no tiene una cuenta, deberá crear una nueva. Una vez que haya terminado de escribir su análisis en RStudio, puede publicarlo en RPubs haciendo lo siguiente:

1. En RStudio, asegúrese de que su documento R Markdown document ( .Rmd) esté cargado en el editor

2. Haga clic en el Knit HTMLbotón en la barra de herramientas del documento para obtener una vista previa de su documento.

3. En la ventana de vista previa, haga clic en el Publishbotón.

Una vez que su documento se publica en RPubs, debe obtener una URL única para ese documento. Anote esta URL, ya que la necesitará para enviar su tarea.

NOTA : Si tiene problemas para conectarse con RPubs debido a problemas relacionados con el proxy o de otro tipo, puede cargar el archivo del documento de análisis final como PDF en Coursera.

# Envío de su asignación
Para enviar esta tarea, debe copiar la URL de RPubs de su documento de análisis de datos completado en la pregunta de evaluación por pares.



EL ENLACE PARA VER LA PUBLICACION EN RPubs:

https://rpubs.com/RudyVC/Reproducible_Research_Project_2
