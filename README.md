## Repositorio de curso sobre Data Analytics

Business Analytics (BA) consiste en explorar y analizar grandes cantidades de datos para obtener información sobre el desempeño empresarial pasado con el fin de guiar la planificación empresarial futura. Este curso presenta un conjunto de métodos avanzados centrados en datos que cubren las tres direcciones principales de BA: descriptivo (“¿qué pasó?”), predictivo (“¿qué pasará?”) y prescriptivo (“¿qué debería pasar?”). Los métodos se aplicarán a varios casos de negocios con el objetivo de demostrar cómo extraer valor comercial de los datos, brindar soporte para la toma de decisiones basada en datos junto con principios efectivos de gestión de datos.
Materiales de soporte para la formación en Data Analytics

**Instructor:** Ulises Gonzalez ([Rizoma](http://www.rizo.ma/), [Linkedin](https://www.linkedin.com/in/ulisesgonzalez/)

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/justmarkham/DAT8)

Tuesday | Thursday
--- | ---
8/18: [Introduction to Data Science](#class-1-introduction-to-data-science) | 8/20: [Command Line, Version Control](#class-2-command-line-and-version-control)
8/25: [Data Reading and Cleaning](#class-3-data-reading-and-cleaning) | 8/27: [Exploratory Data Analysis](#class-4-exploratory-data-analysis)
9/1: [Visualization](#class-5-visualization) | 9/3: [Machine Learning](#class-6-machine-learning)
9/8: [Getting Data](#class-7-getting-data) | 9/10: [K-Nearest Neighbors](#class-8-k-nearest-neighbors)
9/15: [Basic Model Evaluation](#class-9-basic-model-evaluation) | 9/17: [Linear Regression](#class-10-linear-regression)
9/22: [First Project Presentation](#class-11-first-project-presentation) | 9/24: [Logistic Regression](#class-12-logistic-regression)
9/29: [Advanced Model Evaluation](#class-13-advanced-model-evaluation) | 10/1: [Naive Bayes and Text Data](#class-14-naive-bayes-and-text-data)
10/6: [Natural Language Processing](#class-15-natural-language-processing) | 10/8: [Kaggle Competition](#class-16-kaggle-competition)
10/13: [Decision Trees](#class-17-decision-trees) | 10/15: [Ensembling](#class-18-ensembling)
10/20: [Advanced scikit-learn, Clustering](#class-19-advanced-scikit-learn-and-clustering) | 10/22: [Regularization, Regex](#class-20-regularization-and-regular-expressions)
10/27: [Course Review](#class-21-course-review-and-final-project-presentation) | 10/29: [Final Project Presentation](#class-22-final-project-presentation)

<!-
### Antes de que comience el curso
* Instalar [git] (http://git-scm.com/downloads).
* Cree una cuenta en el sitio web [Github] (https://github.com/).
* No es necesario descargar "GitHub para Windows" o "Github para Mac"
* Instale la [Distribución Anaconda] (http://continuum.io/downloads) de Python 2.7x.
* Si elige no usar Anaconda, aquí hay una lista de los [paquetes Python] (otros/python_packages.md) Deberá instalar durante el curso.
* Nos gustaría verificar la configuración de su computadora portátil antes de que comience el curso:
* Puede verificar su computadora portátil antes del taller intermedio de Python el martes 8/11 (5:30 pm-6:30pm), en el [15th & K Starbucks] (http://www.yelp.com/biz/starbucks-Washington-15) el sábado 8/15 (1 pm-3pm), o antes de la clase el martes 8/18 (5:30 pm-6:30pm).
* Alternativamente, puede caminar por la [lista de verificación de configuración] (otro/setup_checklist.md) usted mismo.
* Una vez que reciba una invitación por correo electrónico de Slack, únase a nuestro "equipo DAT8" y agregue su foto.
* Practique Python utilizando los recursos a continuación.
->

### Recursos de Python
* [Codecademy's Python course](http://www.codecademy.com/en/tracks/python): Buen material para principiantes, incluidos toneladas de ejercicios en el navegador.
* [Dataquest](https://www.dataquest.io): Utiliza ejercicios interactivos para enseñar a Python en el contexto de la ciencia de datos.
* [Google's Python Class](https://developers.google.com/edu/python/): Un poco más avanzado, incluidas horas de videos útiles de conferencias y ejercicios descargables (con soluciones).
* [Introduction to Python](http://introtopython.org/): Una serie de cuadernos de iPython que hacen un gran trabajo explicando conceptos y estructuras de datos de Core Python.
* [Python for Informatics](http://www.pythonlearn.com/book.php): Un libro muy orientado a principiante, con asociado [slides](https://drive.google.com/folderview?id=0B7X1ycQalUnyal9yeUx3VW81VDg&usp=sharing) and [videos](https://www.youtube.com/playlist?list=PLlRFEj9H3Oj4JXIwMwN1_ss1Tk8wZShEJ).
* [A Crash Course in Python for Scientists](http://nbviewer.ipython.org/gist/rpmuller/5920182): Lea la sección de descripción general para una introducción muy rápida a Python.
* [Python 2.7 Quick Reference](https://github.com/justmarkham/python-reference/blob/master/reference.py):Mi guía orientada a principiantes que demuestra conceptos de pitón a través de un ejemplo corto y bien commentados.
* [Beginner](code/00_python_beginner_workshop.py) and [intermediate](code/00_python_intermediate_workshop.py) Código de taller: útil para revisión y referencia.
* [Python Tutor](http://pythontutor.com/): Le permite visualizar la ejecución del código Python.

<!--
### Formularios de presentación
* [Formulario de comentarios](http://bit.ly/dat8feedback)
* [Tarea y presentaciones de proyectos](http://bit.ly/dat8homework)
-->

### [Proyecto del curso](project/README.md)

### [Comparación de modelos de aprendizaje automático](other/model_comparison.md)

### [Comparación de procedimientos y métricas de evaluación del modelo](other/model_evaluation_comparison.md)

### [Consejo para mejorar en la ciencia de datos](other/advice.md)

### [Recursos adicionales](#additional-resources-1)

-----

### Class 1: Introducción al Business Analytics
* Bienvenida a la formación
* Resumen del curso([slides](slides/01_course_overview.pdf))
* Introducción al Business Analytics ([slides](slides/01_intro_to_data_science.pdf))
* Discuta el proyecto del curso: [requirements](project/README.md) and [example projects](https://github.com/justmarkham/DAT-project-examples)
* Tipos de datos([slides](slides/01_types_of_data.pdf)) and [public data sources](project/public_data.md)

**Asignación:**
* Work through GA's friendly [command line tutorial](http://generalassembly.github.io/prework/command-line/#/) using Terminal (Linux/Mac) or Git Bash (Windows).
* Read through this [command line reference](code/02_command_line.md), and complete the pre-class exercise at the bottom. (There's nothing you need to submit once you're done.)
* Watch videos 1 through 8 (21 minutes) of [Introduction to Git and GitHub](https://www.youtube.com/playlist?list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD), or read sections 1.1 through 2.2 of [Pro Git](http://git-scm.com/book/en/v2).
* If your laptop has any setup issues, please work with us to resolve them by Thursday. If your laptop has not yet been checked, you should come early on Thursday, or just walk through the [setup checklist](other/setup_checklist.md) yourself (and let us know you have done so).

**Recursos:**
*Para una mirada útil a los diferentes tipos de científicos de datos, lea [analizar los analizadores] (http://cdn.oreillystatic.com/oreilly/radarreport/0636920029014/analyzing_the_analyzers.pdf) (32 páginas).
* Para algunas ideas sobre lo que es ser un científico de datos, lea estas publicaciones breves de [Win-vector] (http://www.win-vector.com/blog/2012/09/on-being-a-data-Scientist/) y [DataScope Analytics] (http://datascopeopealytics.com/what-we-think/2014/07/31/six-qualities-of-a-great-data-scientist).
* Quora tiene una [FAQ de tema de ciencias de datos] (https://www.quora.com/data-science) con muchas preguntas y respuestas interesantes.
* Manténgase al día con los eventos locales relacionados con los datos a través del Data Community DC [Calendario de eventos] (http://www.datacommunitydc.org/calendar) o [boletín semanal] (http://www.datacommunitydc.org/newletter).
-----

### Clase 2: Línea de comandos y control de versiones
* Slack Tour
* Revise el ejercicio previo a la clase de la línea de comando ([code](code/02_command_line.md))
* Git and GitHub ([slides](slides/02_git_github.pdf))
* Línea de comando intermedia

**Tarea:**
* Completar la [command line homework assignment](homework/02_command_line_chipotle.md) con los datos de Chipotle.
* Revise el código del [beginner](code/00_python_beginner_workshop.py) and [intermediate](code/00_python_intermediate_workshop.py) Talleres de Python.Si no se siente cómodo con ninguno de los contenidos (excluyendo las secciones de "solicitudes" y "API"), debe pasar algún tiempo este fin de semana practicando Python:
    * [Introduction to Python](http://introtopython.org/)hace un gran trabajo explicando Python Essentials e incluye toneladas de código de ejemplo.
    * Si te gusta aprender de un libro, [Python for Informatics](http://www.pythonlearn.com/html-270/) Tiene capítulos útiles sobre cadenas, listas y diccionarios.
    * Si prefiere ejercicios interactivos, pruebe estas lecciones de [Codecademy](http://www.codecademy.com/en/tracks/python): "Python listas y diccionarios" y "un día en el supermercado".
    *Si tiene más tiempo, pruebe las misiones 2 y 3 de [DataQuest's Learning Python](https://www.dataquest.io/course/learning-python) curso.
    *Si ya ha dominado estos temas y quiere más desafío, intente resolver [Python Challenge](http://www.pythonchallenge.com/) nNúmero 1 (decodificando un mensaje) y envíeme su código en Slack.
* Para darle un marco para pensar en su proyecto, mire [What is machine learning, and how does it work?](https://www.youtube.com/watch?v=elojMnjn4kk) (10 minutes). (Este es el [IPython notebook](https://github.com/justmarkham/scikit-learn-videos/blob/master/01_machine_learning_intro.ipynb) shown en el video.) Alternativamente, lea [A Visual Introduction to Machine Learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/), que se centra en un modelo de aprendizaje automático específico llamado árboles de decisión.
* **Opcional:** Navegar por un poco más [example student projects](https://github.com/justmarkham/DAT-project-examples), ¡Lo que puede ayudar a inspirar su propio proyecto!

**Recursos Git y Markdown:**
* [Pro Git](http://git-scm.com/book/en/v2) esUnExcelenteLibroParaAprenderGitLeaLosDosPrimerosCapítulosParaObtenerUnaComprensiónMásProfundaDelControlDeVersionesYElComandoBásicos.
* siQuieresPracticarMuchoGit (yAprenderMuchosMásComandos), [Git Immersion](http://gitimmersion.com/) parecePrometedor
* siQuieresEntenderCómoContribuirEnGitHub,PrimeroTienesQueEntender [forks and pull requests](http://www.dataschool.io/simple-guide-to-forks-in-github-and-git/).
* [GitRef](http://gitref.org/)esMiGuíaDeReferenciaFavoritaParaLosComandosGit,Y [Git quick reference for beginners](http://www.dataschool.io/git-quick-reference-for-beginners/) isUnaGuíaMásCortaConComandosAgrupadosPorFlujoDeTrabajo
* [Cracking the Code to GitHub's Growth](https://growthhackers.com/growth-studies/github) explicaPorQuéGithubEsTanPopularEntreLosDesarrolladores
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) proporcionaUnConjuntoExhaustivoDeEjemplosDeMarkdownConExplicacionesConcisasGithub's[Mastering Markdown](https://guides.github.com/features/mastering-markdown/)esUnaGuíaMásSimpleYAtractiva,PeroEsMenosIntegral

**Recursos de línea de comandos:**
* Si quieres profundizar mucho en la línea de comando, [Data Science at the Command Line](http://shop.oreilly.com/product/0636920032823.do) es un gran libro.El [companion website](http://datascienceatthecommandline.com/) Proporciona instrucciones de instalación para una "caja de herramientas de ciencia de datos" (una máquina virtual con muchas más herramientas de línea de comandos), así como una larga guía de referencia para las herramientas de línea de comandos populares.
* Si desea hacer más en la línea de comando con archivos CSV, pruebe [csvkit](http://csvkit.readthedocs.org/), que se puede instalar a través de `pip`.

-----

### Clase 3: Lectura y limpieza de datos
* Git y Github Surtido consejos([slides](slides/02_git_github.pdf))
* Revisar la tarea de la línea de comando ([solution](homework/02_command_line_chipotle.md))
* Pitón:
* Interfaz Spyder
* Ejercicio de bucle
* Lección de lectura de archivos con datos de seguridad de la aerolínea ([code](code/03_file_reading.py), [data](data/airlines.csv), [article](http://fivethirtyeight.com/features/should-travelers-avoid-flying-airlines-that-have-had-crashes-in-the-past/))
    *Ejercicio de limpieza de datos
    * Tutorial de la tarea de Python con datos de chipotle ([code](code/03_python_homework_chipotle.py), [data](data/chipotle.tsv), [article](http://www.nytimes.com/interactive/2015/02/17/upshot/what-do-people-actually-order-at-chipotle.html))

**Tarea:**
* Completar la [Python homework assignment](code/03_python_homework_chipotle.py) Con los datos de Chipotle, agregue un script de Python comentado a su repositorio de GitHub y envíe un enlace utilizando el formulario de envío de tareas.Tienes hasta el martes (9/1) para completar esta tarea. (**Nota: ** Los pandas, que se cubren en la clase 4, no deben usarse para esta tarea).

**Resources:**
* [Want to understand Python's comprehensions? Think in Excel or SQL](http://blog.lerner.co.il/want-to-understand-pythons-comprehensions-think-like-an-accountant/) Puede ser útil si todavía está confundido por las comprensiones de la lista.
* [My code isn't working](http://www.tecoed.co.uk/uploads/1/4/2/4/14249012/624506_orig.png) es un gran diagrama de flujo que explica cómo depurar los errores de Python.
* [PEP 8](https://www.python.org/dev/peps/pep-0008/) es la guía de estilo "clásica" de Python, y vale la pena leer si desea escribir un código legible que sea consistente con el resto de la comunidad de Python.
* Si quieres entender a Python en un nivel más profundo, Ned Batchelder's [Loop Like A Native](http://nedbatchelder.com/text/iter.html)y [Python Names and Values](http://nedbatchelder.com/text/names1.html)son excelentes presentaciones.

-----

### Clase 4: Análisis de datos exploratorios
* Pandas ([code](code/04_pandas.py)):
    * MOVIELENS 100K Clasificaciones de películas ([data](data/u.user), [data dictionary](http://files.grouplens.org/datasets/movielens/ml-100k-README.txt), [website](http://grouplens.org/datasets/movielens/))
    * Consumo de alcohol por país ([data](data/drinks.csv), [article](http://fivethirtyeight.com/datalab/dear-mona-followup-where-do-people-drink-the-most-beer-wine-and-spirits/))
    * Informes de avistamientos de ovnis([data](data/ufo.csv), [website](http://www.nuforc.org/webreports.html))
* Ejercicio de preguntas del proyecto

**Tarea:**
* La fecha límite para discutir las ideas de su proyecto con un instructor es el martes (9/1), y la redacción de la pregunta de su proyecto se vence el juevesy (9/3).
* Leer[How Software in Half of NYC Cabs Generates $5.2 Million a Year in Extra Tips](http://iquantny.tumblr.com/post/107245431809/how-software-in-half-of-nyc-cabs-generates-5-2) Para un excelente ejemplo de análisis de datos exploratorios.
* Leer [Anscombe's Quartet, and Why Summary Statistics Don't Tell the Whole Story](http://data.heapanalytics.com/anscombes-quartet-and-why-summary-statistics-dont-tell-the-whole-story/) Para un ejemplo clásico de por qué la visualización es útil.

**Recursos:**
* Browsing or searching the Pandas [API Reference](http://pandas.pydata.org/pandas-docs/stable/api.html) es una excelente manera de localizar una función incluso si no sabe su nombre exacto.
* [What I do when I get a new data set as told through tweets](http://simplystatistics.org/2014/06/13/what-i-do-when-i-get-a-new-data-set-as-told-through-tweets/) es una mirada divertida (pero esclarecedora) al proceso de análisis de datos exploratorios.

-----

### Clase 5: Visualización
* Tarea de Python con los datos de Chipotle adeudados ([solution](code/03_python_homework_chipotle.py), [detailed explanation](notebooks/03_python_homework_chipotle_explained.ipynb))
* Parte 2 del análisis de datos exploratorios con pandas([code](code/04_pandas.py))
* Visualización con pandas y matplotlib ([notebook](notebooks/05_pandas_visualization.ipynb))

**Tarea:**
* El informe de su pregunta de su proyecto se debe el jueves.
* Completar la [Pandas homework assignment](code/05_pandas_homework_imdb.py) con el [IMDb data](data/imdb_1000.csv). Tiene hasta el martes (9/8) para completar esta tarea.
* IfNo estás usando Anaconda, instale el[Jupyter Notebook](http://jupyter.readthedocs.org/en/latest/install.html)(anteriormente conocido como el cuaderno de ipython) utilizando`pip`. (El cuaderno Jupyter o Ipython se incluye con Anaconda).

**Recursos de pandas:**
* Para obtener más pandas, lea esto [three-part tutorial](http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/), O revise estos dos cuadernos excelentes (pero extremadamente largos) en Pandas: [introduction](https://github.com/fonnesbeck/Bios8366/blob/master/notebooks/Section2_5-Introduction-to-Pandas.ipynb) and [data wrangling](https://github.com/fonnesbeck/Bios8366/blob/master/notebooks/Section2_6-Data-Wrangling-with-Pandas.ipynb).
* Si quieres profundizar en los pandas (y numpy), lee el libro [Python for Data Analysis](http://shop.oreilly.com/product/0636920023784.do),Escrito por el Creador de Pandas.
* Este cuaderno demuestra los diferentes tipos de[joins in Pandas](notebooks/05_pandas_merge.ipynb), para cuando necesite descubrir cómo fusionar dos marcos de datos.
* Este es un buen tutorial breve sobre [pivot tables](https://beta.oreilly.com/learning/pivot-tables) en pandas.
* Para trabajar con datos geoespaciales en Python, [GeoPandas](http://geopandas.org/index.html) parece prometedor.Este [tutorial](http://michelleful.github.io/code-blog/2015/04/24/sgmap/) Utiliza Geopandas (y Scikit-Learn) para construir un "mapa callejero lingüístico" de Singapur.

**Recursos de visualización:**
* Mirar [Look at Your Data](https://www.youtube.com/watch?v=coNDCIMH8bk) (18 minutos) Para un excelente ejemplo de por qué la visualización es útil para comprender sus datos.
* Fo más sobre los pandas tramando, lea esto [notebook](https://github.com/fonnesbeck/Bios8366/blob/master/notebooks/Section2_7-Plotting-with-Pandas.ipynb) o el [visualization page](http://pandas.pydata.org/pandas-docs/stable/visualization.html) De la documentación oficial de Pandas.
* Para aprender a personalizar aún más sus parcelas, navegue por este [notebook on matplotlib](https://github.com/fonnesbeck/Bios8366/blob/master/notebooks/Section2_4-Matplotlib.ipynb) o esto[similar notebook](https://github.com/jrjohansson/scientific-python-lectures/blob/master/Lecture-4-Matplotlib.ipynb).
* Leer [Overview of Python Visualization Tools](http://pbpython.com/visualization-tools-1.html) Para una comparación útil de matplotlib, pandas, seaborn, ggplot, bokeh, pygal y tramly.
* Para explorar diferentes tipos de visualizaciones y cuándo usarlas, [Choosing a Good Chart](http://extremepresentation.typepad.com/files/choosing-a-good-chart-09.pdf) y[The Graphic Continuum](http://www.coolinfographics.com/storage/post-images/The-Graphic-Continuum-POSTER.jpg) son buenas referencias de una página y el interactivo [R Graph Catalog](http://shiny.stat.ubc.ca/r-graph-catalog/) tiene prácticas capacidades de filtrado.
* Esta [PowerPoint presentation](http://www2.research.att.com/~volinsky/DataMining/Columbia2011/Slides/Topic2-EDAViz.ppt) De la clase de minería de datos de Columbia contiene muchos buenos consejos para usar adecuadamente los diferentes tipos de visualizaciones.
* [Harvard's Data Science course](http://cs109.github.io/2014/) Incluye una excelente conferencia sobre[Visualization Goals, Data Types, and Statistical Graphs](http://cm.dce.harvard.edu/2015/01/14328/L03/screen_H264LargeTalkingHead-16x9.shtml) (83 minutos), para el cual el [slides](https://docs.google.com/file/d/0B7IVstmtIvlHLTdTbXdEVENoRzQ/edit) también están disponibles.

-----

### Clase 6: Aprendizaje automático
* Parte 2 de la visualización con pandas y matplotlib([notebook](notebooks/05_pandas_visualization.ipynb))
*Breve introducción al cuaderno Jupyter/Ipython
*Ejercicio de "aprendizaje humano":
    * [Iris dataset](http://archive.ics.uci.edu/ml/datasets/Iris) Organizado por el repositorio de aprendizaje automático de UCI
    * [Iris photo](http://sebastianraschka.com/Images/2014_python_lda/iris_petal_sepal.png)
    * [Notebook](notebooks/06_human_learning_iris.ipynb)
* Introducción al aprendizaje automático ([slides](slides/06_machine_learning.pdf))

**Tarea:**
*** Opcional: ** Complete el ejercicio de bonificación en la lista de [human learning notebook](notebooks/06_human_learning_iris.ipynb). ¡Tomará el lugar de cualquier tarea que pierda, pasado o futuro!Esto se debe el martes (9/8).
* Si no está usando Anaconda, instale [requests](http://www.python-requests.org/en/latest/user/install/)y[Beautiful Soup 4](http://www.crummy.com/software/BeautifulSoup/bs4/doc/#installing-beautiful-soup)usando`pip`. (Ambos paquetes están incluidos con Anaconda).

**Recursos de aprendizaje automático:**
* Para un resumen muy rápido de los puntos clave sobre el aprendizaje automático, mire[What is machine learning, and how does it work?](https://www.youtube.com/watch?v=elojMnjn4kk) (10 minutos) o leer el [associated notebook](https://github.com/justmarkham/scikit-learn-videos/blob/master/01_machine_learning_intro.ipynb).
* Para una introducción más profunda al aprendizaje automático, lea la Sección 2.1 (14 páginas) del excelente libro de Hastie y Tibshirani, [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/). (¡Es una descarga gratuita de PDF!)
*La [Learning Paradigms](http://work.caltech.edu/library/014.html) Video (13 minutos) de [Caltech's Learning From Data course](http://work.caltech.edu/telecourse.html) Proporciona una buena comparación del aprendizaje supervisado versus no supervisado, así como una introducción al "aprendizaje de refuerzo".
* [Real-World Active Learning](https://beta.oreilly.com/ideas/real-world-active-learning) es una introducción legible y exhaustiva al "aprendizaje activo", una variación del aprendizaje automático en la que los humanos etiquetan solo las observaciones más "importantes".
* Para obtener una vista previa de parte del contenido de aprendizaje automático que cubriremos durante el curso, lea Sebastian Raschka's [overview of the supervised learning process](https://github.com/rasbt/pattern_classification/blob/master/machine_learning/supervised_intro/introduction_to_supervised_machine_learning.md).
* [Data Science, Machine Learning, and Statistics: What is in a Name?](http://www.win-vector.com/blog/2013/04/data-science-machine-learning-and-statistics-what-is-in-a-name/) Discute las diferencias entre estos (y otros) términos.
* [The Emoji Translation Project](https://www.kickstarter.com/projects/fred/the-emoji-translation-project)es una aplicación realmente divertida del aprendizaje automático.
* Busque el[characteristics of your zip code](http://www.esri.com/landing-pages/tapestry/), y luego lee sobre el [67 distinct segments](http://doc.arcgis.com/en/esri-demographics/data/tapestry-segmentation.htm) en detalle.

**Recursos de cuaderno de iPython**
* Para un resumen de la introducción del cuaderno de iPython (y una vista previa de Scikit-Learn), mire [scikit-learn and the IPython Notebook](https://www.youtube.com/watch?v=IsXXlYVBt1M) (15 minutos) o leer el[associated notebook](https://github.com/justmarkham/scikit-learn-videos/blob/master/02_machine_learning_setup.ipynb).
*Si desea aprender el cuaderno de iPython, el oficial[Notebook tutorials](https://github.com/jupyter/notebook/blob/master/docs/source/examples/Notebook/Examples%20and%20Tutorials%20Index.ipynb) Son útiles.
*Esta [Reddit discussion](https://www.reddit.com/r/Python/comments/3be5z2/do_you_prefer_ipython_notebook_over_ipython/) Compara las fortalezas relativas del cuaderno de Ipython y Spyder.

-----

### Clase 7: Obtener datos
* Tarea de pandas con los datos de IMDB adeudados ([solution](code/05_pandas_homework_imdb.py))
* Ejercicio opcional de "aprendizaje humano" con los datos de iris adeudados ([solution](notebooks/06_human_learning_iris.ipynb))
* APIs ([code](code/07_api.py))
    * [OMDb API](http://www.omdbapi.com/)
* Web scraping ([code](code/07_web_scraping.py))
    * [IMDb: robots.txt](http://www.imdb.com/robots.txt)
    * [Example web page](data/example.html)
    * [IMDb: The Shawshank Redemption](http://www.imdb.com/title/tt0111161/)

**Tarea:**
*** Opcional: ** Complete el ejercicio de tarea enumerado en el [web scraping code](code/07_web_scraping.py). ¡Tomará el lugar de cualquier tarea que pierda, pasado o futuro!Esto se debe el martes (15/09).
* **Opcional: ** Si no estás usando Anaconda, [install Seaborn](http://stanford.edu/~mwaskom/software/seaborn/installing.html) usando `pip`. Si está utilizando Anaconda, instale SeaBorn corriendo `conda install seaborn`en la línea de comando.(Tenga en cuenta que algunos estudiantes en cursos pasados ​​han tenido problemas con Anaconda después de instalar Seorn).

**Recursos API**
*Este guión de Python para [query the U.S. Census API](https://github.com/laurakurup/census-api) fue creado por un ex alumno de DA.Es un poco más complicado que el ejemplo que usamos en la clase, está muy bien comentado y puede proporcionar un marco útil para escribir su propio código para consultar las API.
* [Mashape](https://www.mashape.com/explore) y [Apigee](https://apigee.com/providers)Permitirle explorar toneladas de diferentes API.Alternativamente, un [Python API wrapper](http://www.pythonforbeginners.com/api/list-of-python-apis) está disponible para muchas API populares.
* the [Data Science Toolkit](http://www.datasciencetoolkit.org/) es una colección de API basadas en la ubicación y relacionadas con el texto.
* [API Integration in Python](https://realpython.com/blog/python/api-integration-in-python/) Proporciona una introducción muy legible a las API REST.
* Microsoft's [Face Detection API](https://www.projectoxford.ai/demo/face#detection), que poderes[How-Old.net](http://how-old.net/), es un gran ejemplo de cómo se puede aprovechar una API de aprendizaje automático para producir una aplicación web convincente.

**Recursos de raspado web:**
* La[Beautiful Soup documentation](http://www.crummy.com/software/BeautifulSoup/bs4/doc/) es increíblemente minucioso, pero es difícil de usar como guía de referencia.Sin embargo, la sección en[specifying a parser](http://www.crummy.com/software/BeautifulSoup/bs4/doc/#specifying-the-parser-to-use) Puede ser útil si la hermosa sopa parece estar analizando una página incorrectamente.
* Para más hermosos ejemplos de sopa y tutoriales, ver [Web Scraping 101 with Python](http://www.gregreda.com/2013/03/03/web-scraping-101-with-python/), Un cuaderno de un ex alumno de DAT bien comentado en[scraping Craigslist](https://github.com/Alexjmsherman/DataScience_GeneralAssembly/blob/master/Final_Project/1.%20Final_Project_Data%20Scraping.ipynb), this [notebook](http://web.stanford.edu/~zlotnick/TextAsData/Web_Scraping_with_Beautiful_Soup.html) del texto de Stanford como curso de datos, y esto[notebook](https://github.com/cs109/2014/blob/master/lectures/2014_09_23-lecture/data_scraping_transcript.ipynb) y asociado [video](http://cm.dce.harvard.edu/2015/01/14328/L07/screen_H264LargeTalkingHead-16x9.shtml)del curso de ciencia de datos de Harvard.
* Para un tutorial de raspado web mucho más largo que cubre la hermosa sopa, LXML, XPath y Selenium, reloj[Web Scraping with Python](https://www.youtube.com/watch?v=p1iX0uxM1w8) (3 horas 23 minutos) de Pycon 2014. La [slides](https://docs.google.com/presentation/d/1uHM_esB13VuSf7O1ScGueisnrtu-6usGFD3fs4z5YCE/edit#slide=id.p) y [code](https://github.com/kjam/python-web-scraping-tutorial) también están disponibles.
* Para proyectos de raspado web más complejos, [Scrapy](http://scrapy.org/) es un marco de aplicaciones popular que funciona con Python.Tiene excelente [documentation](http://doc.scrapy.org/en/1.0/index.html), Y aquí hay un [tutorial](https://github.com/rdempsey/ddl-data-wrangling) con diapositivas y código detallados.
* [robotstxt.org](http://www.robotstxt.org/robotstxt.html) tiene una explicación concisa de cómo escribir (y leer) el `robots.txt` file.
* [import.io](https://import.io/) y [Kimono](https://www.kimonolabs.com/) afirmar que le permite raspar sitios web sin escribir ningún código.
* [How a Math Genius Hacked OkCupid to Find True Love](http://www.wired.com/2014/01/how-to-hack-okcupid/all/) and [How Netflix Reverse Engineered Hollywood](http://www.theatlantic.com/technology/archive/2014/01/how-netflix-reverse-engineered-hollywood/282679/?single_page=true) son dos ejemplos divertidos de cómo se ha utilizado el raspado web para crear conjuntos de datos interesantes.

-----

### Clase 8: vecinos K-nears
* Breve revisión de pandas ([cuaderno] (cuadernos/08_pandas_review.ipynb)))
* K-Near más vecinos y scikit-learn ([cuaderno] (cuadernos/08_knn_sklearn.ipynb))
* Ejercicio con los datos del jugador de la NBA ([cuaderno] (cuaderno/08_nba_knn.ipynb), [data] (https://github.com/justmarkham/dat4-students/blob/master/kerry/final/nba_players_2015.csv), [Dicción de datos] (https://github.com/justmarkham/dat-project-examples/blob/master/pdf/nba_paper.pdf)))
* Explorando la compensación de varianza de sesgo ([cuaderno] (cuadernos/08_bias_variance.ipynb))

**Homework:**
* Reading assignment on the [bias-variance tradeoff](homework/09_bias_variance.md)
* Read Kevin's [introduction to reproducibility](http://www.dataschool.io/reproducibility-is-not-just-for-researchers/), read Jeff Leek's [guide to creating a reproducible analysis](https://github.com/jtleek/datasharing), and watch this related [Colbert Report video](http://thecolbertreport.cc.com/videos/dcyvro/austerity-s-spreadsheet-error) (8 minutes).
* Work on your project... your first project presentation is in less than two weeks!

**KNN Resources:**
* For a recap of the key points about KNN and scikit-learn, watch [Getting started in scikit-learn with the famous iris dataset](https://www.youtube.com/watch?v=hd1W4CyPX58) (15 minutes) and [Training a machine learning model with scikit-learn](https://www.youtube.com/watch?v=RlQuVL6-qe8) (20 minutes).
* KNN supports [distance metrics](http://scikit-learn.org/stable/modules/generated/sklearn.neighbors.DistanceMetric.html) other than Euclidean distance, such as [Mahalanobis distance](http://stats.stackexchange.com/questions/62092/bottom-to-top-explanation-of-the-mahalanobis-distance), which [takes the scale of the data into account](http://blogs.sas.com/content/iml/2012/02/15/what-is-mahalanobis-distance.html).
* [A Detailed Introduction to KNN](https://saravananthirumuruganathan.wordpress.com/2010/05/17/a-detailed-introduction-to-k-nearest-neighbor-knn-algorithm/) is a bit dense, but provides a more thorough introduction to KNN and its applications.
* This lecture on [Image Classification](http://cs231n.github.io/classification/) shows how KNN could be used for detecting similar images, and also touches on topics we will cover in future classes (hyperparameter tuning and cross-validation).
* Some applications for which KNN is well-suited are [object recognition](http://vlm1.uta.edu/~athitsos/nearest_neighbors/), [satellite image enhancement](http://land.umn.edu/documents/FS6.pdf), [document categorization](http://www.ceng.metu.edu.tr/~e120321/paper.pdf), and [gene expression analysis](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.208.993).

**Seaborn Resources:**
* To get started with Seaborn for visualization, the official website has a series of [detailed tutorials](http://web.stanford.edu/~mwaskom/software/seaborn/tutorial.html) and an [example gallery](http://web.stanford.edu/~mwaskom/software/seaborn/examples/index.html).
* [Data visualization with Seaborn](https://beta.oreilly.com/learning/data-visualization-with-seaborn) is a quick tour of some of the popular types of Seaborn plots.
* [Visualizing Google Forms Data with Seaborn](http://pbpython.com/pandas-google-forms-part2.html) and [How to Create NBA Shot Charts in Python](http://savvastjortjoglou.com/nba-shot-sharts.html) are both good examples of Seaborn usage on real-world data.

-----

### Class 9: Basic Model Evaluation
* Optional web scraping homework due ([solution](code/07_web_scraping.py#L136))
* Reproducibility
    * Discuss assigned readings: [introduction](http://www.dataschool.io/reproducibility-is-not-just-for-researchers/), [Colbert Report video](http://thecolbertreport.cc.com/videos/dcyvro/austerity-s-spreadsheet-error), [cabs article](http://iquantny.tumblr.com/post/107245431809/how-software-in-half-of-nyc-cabs-generates-5-2), [Tweet](https://twitter.com/jakevdp/status/519563939177197571), [creating a reproducible analysis](https://github.com/jtleek/datasharing)
    * Examples: [Classic rock](https://github.com/fivethirtyeight/data/tree/master/classic-rock), [student project 1](https://github.com/jwknobloch/DAT4_final_project), [student project 2](https://github.com/justmarkham/DAT4-students/tree/master/Jonathan_Bryan/Project_Files)
* Discuss the reading assignment on the [bias-variance tradeoff](homework/09_bias_variance.md)
* Model evaluation using train/test split ([notebook](notebooks/09_model_evaluation.ipynb))
* Exploring the scikit-learn documentation: [module reference](http://scikit-learn.org/stable/modules/classes.html), [user guide](http://scikit-learn.org/stable/user_guide.html), class and function documentation

**Homework:**
* Watch [Data science in Python](https://www.youtube.com/watch?v=3ZWuPVWq7p4) (35 minutes) for an introduction to linear regression (and a review of other course content), or at the very least, read through the [associated notebook](https://github.com/justmarkham/scikit-learn-videos/blob/master/06_linear_regression.ipynb).
* **Optional:** For another introduction to linear regression, watch [The Easiest Introduction to Regression Analysis](https://www.youtube.com/watch?v=k_OB1tWX9PM) (14 minutes).

**Model Evaluation Resources:**
* For a recap of some of the key points from today's lesson, watch [Comparing machine learning models in scikit-learn](https://www.youtube.com/watch?v=0pP4EwWJgIU) (27 minutes).
* For another explanation of training error versus testing error, the bias-variance tradeoff, and train/test split (also known as the "validation set approach"), watch Hastie and Tibshirani's video on [estimating prediction error](https://www.youtube.com/watch?v=_2ij6eaaSl0&t=2m34s) (12 minutes, starting at 2:34).
* Caltech's Learning From Data course includes a fantastic video on [visualizing bias and variance](http://work.caltech.edu/library/081.html) (15 minutes).
* [Random Test/Train Split is Not Always Enough](http://www.win-vector.com/blog/2015/01/random-testtrain-split-is-not-always-enough/) explains why random train/test split may not be a suitable model evaluation procedure if your data has a significant time element.

**Reproducibility Resources:**
* [What We've Learned About Sharing Our Data Analysis](https://source.opennews.org/en-US/articles/what-weve-learned-about-sharing-our-data-analysis/) includes tips from BuzzFeed News about how to publish a reproducible analysis.
* [Software development skills for data scientists](http://treycausey.com/software_dev_skills.html) discusses the importance of writing functions and proper code comments (among other skills), which are highly useful for creating a reproducible analysis.
* [Data science done well looks easy - and that is a big problem for data scientists](http://simplystatistics.org/2015/03/17/data-science-done-well-looks-easy-and-that-is-a-big-problem-for-data-scientists/) explains how a reproducible analysis demonstrates all of the work that goes into proper data science.

-----

### Class 10: Linear Regression
* Machine learning exercise ([article](http://blog.dominodatalab.com/10-interesting-uses-of-data-science/))
* Linear regression ([notebook](notebooks/10_linear_regression.ipynb))
    * [Capital Bikeshare dataset](data/bikeshare.csv) used in a Kaggle competition
    * [Data dictionary](https://www.kaggle.com/c/bike-sharing-demand/data)
* Feature engineering example: [Predicting User Engagement in Corporate Collaboration Network](https://github.com/mikeyea/DAT7_project/blob/master/final%20project/Class_Presention_MYea.ipynb)

**Homework:**
* Your first project presentation is on Tuesday (9/22)! Please submit a link to your project repository (with slides, code, data, and visualizations) by 6pm on Tuesday.
* Complete the [homework assignment](homework/10_yelp_votes.md) with the [Yelp data](data/yelp.csv). This is due on Thursday (9/24).

**Linear Regression Resources:**
* To go much more in-depth on linear regression, read Chapter 3 of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/). Alternatively, watch the [related videos](http://www.dataschool.io/15-hours-of-expert-machine-learning-videos/) or read my [quick reference guide](http://www.dataschool.io/applying-and-interpreting-linear-regression/) to the key points in that chapter.
* This [introduction to linear regression](http://people.duke.edu/~rnau/regintro.htm) is more detailed and mathematically thorough, and includes lots of good advice.
* This is a relatively quick post on the [assumptions of linear regression](http://pareonline.net/getvn.asp?n=2&v=8).
* Setosa has an [interactive visualization](http://setosa.io/ev/ordinary-least-squares-regression/) of linear regression.
* For a brief introduction to confidence intervals, hypothesis testing, p-values, and R-squared, as well as a comparison between scikit-learn code and [Statsmodels](http://statsmodels.sourceforge.net/) code, read my [DAT7 lesson on linear regression](https://github.com/justmarkham/DAT7/blob/master/notebooks/10_linear_regression.ipynb).
* Here is a useful explanation of [confidence intervals](http://www.quora.com/What-is-a-confidence-interval-in-laymans-terms/answer/Michael-Hochster) from Quora.
* [Hypothesis Testing: The Basics](http://20bits.com/article/hypothesis-testing-the-basics) provides a nice overview of the topic, and John Rauser's talk on [Statistics Without the Agonizing Pain](https://www.youtube.com/watch?v=5Dnw46eC-0o) (12 minutes) gives a great explanation of how the null hypothesis is rejected.
* Earlier this year, a major scientific journal banned the use of p-values:
    * Scientific American has a nice [summary](http://www.scientificamerican.com/article/scientists-perturbed-by-loss-of-stat-tools-to-sift-research-fudge-from-fact/) of the ban.
    * This [response](http://www.nature.com/news/statistics-p-values-are-just-the-tip-of-the-iceberg-1.17412) to the ban in Nature argues that "decisions that are made earlier in data analysis have a much greater impact on results".
    * Andrew Gelman has a readable [paper](http://www.stat.columbia.edu/~gelman/research/unpublished/p_hacking.pdf) in which he argues that "it's easy to find a p < .05 comparison even if nothing is going on, if you look hard enough".
    * [Science Isn't Broken](http://fivethirtyeight.com/features/science-isnt-broken/) includes a neat tool that allows you to "p-hack" your way to "statistically significant" results.
* [Accurately Measuring Model Prediction Error](http://scott.fortmann-roe.com/docs/MeasuringError.html) compares adjusted R-squared, AIC and BIC, train/test split, and cross-validation.

**Other Resources:**
* Section 3.3.1 of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/) (4 pages) has a great explanation of dummy encoding for categorical features.
* Kaggle has some nice [visualizations of the bikeshare data](https://www.kaggle.com/c/bike-sharing-demand/scripts?outputType=Visualization) we used today.

-----

### Class 11: First Project Presentation
* Project presentations!

**Homework:**
* Watch Rahul Patwari's videos on [probability](https://www.youtube.com/watch?v=o4QmoNfW3bI) (5 minutes) and [odds](https://www.youtube.com/watch?v=GxbXQjX7fC0) (8 minutes) if you're not comfortable with either of those terms.
* Read these excellent articles from BetterExplained: [An Intuitive Guide To Exponential Functions & e](http://betterexplained.com/articles/an-intuitive-guide-to-exponential-functions-e/) and [Demystifying the Natural Logarithm (ln)](http://betterexplained.com/articles/demystifying-the-natural-logarithm-ln/). Then, review this [brief summary](notebooks/12_e_log_examples.ipynb) of exponential functions and logarithms.

-----

### Class 12: Logistic Regression
* Yelp votes homework due ([solution](notebooks/10_yelp_votes_homework.ipynb))
* Logistic regression ([notebook](notebooks/12_logistic_regression.ipynb))
    * [Glass identification dataset](https://archive.ics.uci.edu/ml/datasets/Glass+Identification)
* Exercise with Titanic data ([notebook](notebooks/12_titanic_confusion.ipynb), [data](data/titanic.csv), [data dictionary](https://www.kaggle.com/c/titanic/data))
* Confusion matrix ([slides](slides/12_confusion_matrix.pdf), [notebook](notebooks/12_titanic_confusion.ipynb))

**Homework:**
* If you aren't yet comfortable with all of the confusion matrix terminology, watch Rahul Patwari's videos on [Intuitive sensitivity and specificity](https://www.youtube.com/watch?v=U4_3fditnWg) (9 minutes) and [The tradeoff between sensitivity and specificity](https://www.youtube.com/watch?v=vtYDyGGeQyo) (13 minutes).
* Video/reading assignment on [ROC curves and AUC](homework/13_roc_auc.md)
* Video/reading assignment on [cross-validation](homework/13_cross_validation.md)

**Logistic Regression Resources:**
* To go deeper into logistic regression, read the first three sections of Chapter 4 of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/), or watch the [first three videos](http://www.dataschool.io/15-hours-of-expert-machine-learning-videos/) (30 minutes) from that chapter.
* For a math-ier explanation of logistic regression, watch the first seven videos (71 minutes) from week 3 of Andrew Ng's [machine learning course](https://www.coursera.org/learn/machine-learning/home/info), or read the [related lecture notes](http://www.holehouse.org/mlclass/06_Logistic_Regression.html) compiled by a student.
* For more on interpreting logistic regression coefficients, read this excellent [guide](http://www.ats.ucla.edu/stat/mult_pkg/faq/general/odds_ratio.htm) by UCLA's IDRE and these [lecture notes](http://www.unm.edu/~schrader/biostat/bio2/Spr06/lec11.pdf) from the University of New Mexico.
* The scikit-learn documentation has a nice [explanation](http://scikit-learn.org/stable/modules/calibration.html) of what it means for a predicted probability to be calibrated.
* [Supervised learning superstitions cheat sheet](http://ryancompton.net/assets/ml_cheat_sheet/supervised_learning.html) is a very nice comparison of four classifiers we cover in the course (logistic regression, decision trees, KNN, Naive Bayes) and one classifier we do not cover (Support Vector Machines).

**Confusion Matrix Resources:**
* My [simple guide to confusion matrix terminology](http://www.dataschool.io/simple-guide-to-confusion-matrix-terminology/) may be useful to you as a reference.
* This blog post about [Amazon Machine Learning](https://aws.amazon.com/blogs/aws/amazon-machine-learning-make-data-driven-decisions-at-scale/) contains a neat [graphic](https://media.amazonwebservices.com/blog/2015/ml_adjust_model_1.png) showing how classification threshold affects different evaluation metrics.
* This notebook (from another DAT course) explains [how to calculate "expected value"](https://github.com/podopie/DAT18NYC/blob/master/classes/13-expected_value_cost_benefit_analysis.ipynb) from a confusion matrix by treating it as a cost-benefit matrix.

-----

### Class 13: Advanced Model Evaluation
* Data preparation ([notebook](notebooks/13_advanced_model_evaluation.ipynb))
    * Handling missing values
    * Handling categorical features (review)
* ROC curves and AUC
    * Discuss the [video/reading assignment](homework/13_roc_auc.md)
    * Exercise: drawing an ROC curve ([slides](slides/13_drawing_roc.pdf))
    * Return to the main notebook
* Cross-validation
    * Discuss the [video/reading assignment](homework/13_cross_validation.md) and associated [notebook](notebooks/13_cross_validation.ipynb)
    * Return to the main notebook
* Exercise with bank marketing data ([notebook](notebooks/13_bank_exercise.ipynb), [data](data/bank-additional.csv), [data dictionary](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing))

**Homework:**
* Reading assignment on [spam filtering](homework/14_spam_filtering.md)
* Read these [Introduction to Probability](https://docs.google.com/presentation/d/1cM2dVbJgTWMkHoVNmYlB9df6P2H8BrjaqAcZTaLe9dA/edit#slide=id.gfc3caad2_00) slides, or skim section 2.1 of the [OpenIntro Statistics textbook](https://www.openintro.org/stat/textbook.php?stat_book=os) (12 pages). Pay specific attention to the following terms: probability, mutually exclusive, sample space, independent.
* **Optional:** Try to gain an understanding of conditional probability from this [visualization](http://setosa.io/conditional/).
* **Optional:** For an intuitive introduction to Bayes' theorem, read these posts on [wealth and happiness](http://www.quora.com/What-is-an-intuitive-explanation-of-Bayes-Rule/answer/Michael-Hochster), [ducks](https://planspacedotorg.wordpress.com/2014/02/23/bayes-rule-for-ducks/), or [legos](http://www.countbayesie.com/blog/2015/2/18/bayes-theorem-with-lego).

**ROC Resources:**
* Rahul Patwari has a great video on [ROC Curves](https://www.youtube.com/watch?v=21Igj5Pr6u4) (12 minutes).
* [An introduction to ROC analysis](http://people.inf.elte.hu/kiss/13dwhdm/roc.pdf) is a very readable paper on the topic.
* ROC curves can be used across a wide variety of applications, such as [comparing different feature sets](http://research.microsoft.com/pubs/205472/aisec10-leontjeva.pdf) for detecting fraudulent Skype users, and [comparing different classifiers](http://www.cse.ust.hk/nevinZhangGroup/readings/yi/Bradley_PR97.pdf) on a number of popular datasets.

**Cross-Validation Resources:**
* For more on cross-validation, read section 5.1 of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/) (11 pages) or watch the related videos: [K-fold and leave-one-out cross-validation](https://www.youtube.com/watch?v=nZAM5OXrktY) (14 minutes), [cross-validation the right and wrong ways](https://www.youtube.com/watch?v=S06JpVoNaA0) (10 minutes).
* If you want to understand the different variations of cross-validation, this [paper](http://www.jcheminf.com/content/pdf/1758-2946-6-10.pdf) examines and compares them in detail.
* To learn how to use [GridSearchCV and RandomizedSearchCV](http://scikit-learn.org/stable/modules/grid_search.html) for parameter tuning, watch [How to find the best model parameters in scikit-learn](https://www.youtube.com/watch?v=Gol_qOgRqfA) (28 minutes) or read the [associated notebook](https://github.com/justmarkham/scikit-learn-videos/blob/master/08_grid_search.ipynb).

**Other Resources:**
* scikit-learn has extensive documentation on [model evaluation](http://scikit-learn.org/stable/modules/model_evaluation.html).
* [Counterfactual evaluation of machine learning models](https://www.youtube.com/watch?v=QWCSxAKR-h0) (45 minutes) is an excellent talk about the sophisticated way in which Stripe evaluates its fraud detection model. (These are the associated [slides](http://www.slideshare.net/MichaelManapat/counterfactual-evaluation-of-machine-learning-models).)
* [Visualizing Machine Learning Thresholds to Make Better Business Decisions](http://blog.insightdatalabs.com/visualizing-classifier-thresholds/) demonstrates how visualizing precision, recall, and "queue rate" at different thresholds can help you to maximize the business value of your classifier.

-----

### Class 14: Naive Bayes and Text Data
* Conditional probability and Bayes' theorem
    * [Slides](slides/14_bayes_theorem.pdf) (adapted from [Visualizing Bayes' theorem](http://oscarbonilla.com/2009/05/visualizing-bayes-theorem/))
    * Applying Bayes' theorem to iris classification ([notebook](notebooks/14_bayes_theorem_iris.ipynb))
* Naive Bayes classification
    * [Slides](slides/14_naive_bayes.pdf)
    * Spam filtering example ([notebook](notebooks/14_naive_bayes_spam.ipynb))
* Applying Naive Bayes to text data in scikit-learn ([notebook](notebooks/14_text_data_sklearn.ipynb))
    * [CountVectorizer](http://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html) documentation
    * SMS messages: [data](data/sms.tsv), [data dictionary](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)

**Homework:**
* Complete another [homework assignment](homework/14_yelp_review_text.md) with the [Yelp data](data/yelp.csv). This is due on Tuesday (10/6).
* Confirm that you have [TextBlob](https://textblob.readthedocs.org/) installed by running `import textblob` from within your preferred Python environment. If it's not installed, run `pip install textblob` at the command line (not from within Python).

**Resources:**
* Sebastian Raschka's article on [Naive Bayes and Text Classification](http://sebastianraschka.com/Articles/2014_naive_bayes_1.html) covers the conceptual material from today's class in much more detail.
* For more on conditional probability, read these [slides](https://docs.google.com/presentation/d/1psUIyig6OxHQngGEHr3TMkCvhdLInnKnclQoNUr4G4U/edit#slide=id.gfc69f484_00), or read section 2.2 of the [OpenIntro Statistics textbook](https://www.openintro.org/stat/textbook.php?stat_book=os) (15 pages).
* For an intuitive explanation of Naive Bayes classification, read this post on [airport security](http://www.quora.com/In-laymans-terms-how-does-Naive-Bayes-work/answer/Konstantin-Tt).
* For more details on Naive Bayes classification, Wikipedia has two excellent articles ([Naive Bayes classifier](http://en.wikipedia.org/wiki/Naive_Bayes_classifier) and [Naive Bayes spam filtering](http://en.wikipedia.org/wiki/Naive_Bayes_spam_filtering)), and Cross Validated has a good [Q&A](http://stats.stackexchange.com/questions/21822/understanding-naive-bayes).
* When applying Naive Bayes classification to a dataset with continuous features, it is better to use [GaussianNB](http://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.GaussianNB.html) rather than [MultinomialNB](http://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.MultinomialNB.html). This [notebook](notebooks/14_types_of_naive_bayes.ipynb) compares their performances on such a dataset. Wikipedia has a short [description](https://en.wikipedia.org/wiki/Naive_Bayes_classifier#Gaussian_naive_Bayes) of Gaussian Naive Bayes, as well as an excellent [example](https://en.wikipedia.org/wiki/Naive_Bayes_classifier#Sex_classification) of its usage.
* These [slides](http://www.umiacs.umd.edu/~jbg/teaching/DATA_DIGGING/lecture_05.pdf) from the University of Maryland provide more mathematical details on both logistic regression and Naive Bayes, and also explain how Naive Bayes is actually a "special case" of logistic regression.
* Andrew Ng has a [paper](http://ai.stanford.edu/~ang/papers/nips01-discriminativegenerative.pdf) comparing the performance of logistic regression and Naive Bayes across a variety of datasets.
* If you enjoyed Paul Graham's article, you can read [his follow-up article](http://www.paulgraham.com/better.html) on how he improved his spam filter and this [related paper](http://www.merl.com/publications/docs/TR2004-091.pdf) about state-of-the-art spam filtering in 2004.
* Yelp has found that Naive Bayes is more effective than Mechanical Turks at [categorizing businesses](http://engineeringblog.yelp.com/2011/02/towards-building-a-high-quality-workforce-with-mechanical-turk.html).

-----

### Class 15: Natural Language Processing
* Yelp review text homework due ([solution](notebooks/14_yelp_review_text_homework.ipynb))
* Natural language processing ([notebook](notebooks/15_natural_language_processing.ipynb))
* Introduction to our [Kaggle competition](https://inclass.kaggle.com/c/dat8-stack-overflow)
    * Create a Kaggle account, join the competition using the invitation link, download the sample submission, and then submit the sample submission (which will require SMS account verification).

**Homework:**
* Your draft paper is due on Thursday (10/8)! Please submit a link to your project repository (with paper, code, data, and visualizations) before class.
* Watch [Kaggle: How it Works](https://www.youtube.com/watch?v=PoD84TVdD-4) (4 minutes) for a brief overview of the Kaggle platform.
* Download the competition files, move them to the `DAT8/data` directory, and make sure you can open the CSV files using Pandas. If you have any problems opening the files, you probably need to turn off real-time virus scanning (especially Microsoft Security Essentials).
* **Optional:** Come up with some theories about which features might be relevant to predicting the response, and then explore the data to see if those theories appear to be true.
* **Optional:** Watch my [project presentation video](https://www.youtube.com/watch?v=HGr1yQV3Um0) (16 minutes) for a tour of the end-to-end machine learning process for a Kaggle competition, including feature engineering. (Or, just read through the [slides](https://speakerdeck.com/justmarkham/allstate-purchase-prediction-challenge-on-kaggle).)

**NLP Resources:**
* If you want to learn a lot more NLP, check out the excellent [video lectures](https://class.coursera.org/nlp/lecture) and [slides](http://web.stanford.edu/~jurafsky/NLPCourseraSlides.html) from this [Coursera course](https://www.coursera.org/course/nlp) (which is no longer being offered).
* This slide deck defines many of the [key NLP terms](https://github.com/ga-students/DAT_SF_9/blob/master/16_Text_Mining/DAT9_lec16_Text_Mining.pdf).
* [Natural Language Processing with Python](http://www.nltk.org/book/) is the most popular book for going in-depth with the [Natural Language Toolkit](http://www.nltk.org/) (NLTK).
* [A Smattering of NLP in Python](https://github.com/charlieg/A-Smattering-of-NLP-in-Python/blob/master/A%20Smattering%20of%20NLP%20in%20Python.ipynb) provides a nice overview of NLTK, as does this [notebook from DAT5](https://github.com/justmarkham/DAT5/blob/master/notebooks/14_nlp.ipynb).
* [spaCy](http://spacy.io/) is a newer Python library for text processing that is focused on performance (unlike NLTK).
* If you want to get serious about NLP, [Stanford CoreNLP](http://nlp.stanford.edu/software/corenlp.shtml) is a suite of tools (written in Java) that is highly regarded.
* When working with a large text corpus in scikit-learn, [HashingVectorizer](http://scikit-learn.org/stable/modules/feature_extraction.html#vectorizing-a-large-text-corpus-with-the-hashing-trick) is a useful alternative to CountVectorizer.
* [Automatically Categorizing Yelp Businesses](http://engineeringblog.yelp.com/2015/09/automatically-categorizing-yelp-businesses.html) discusses how Yelp uses NLP and scikit-learn to solve the problem of uncategorized businesses.
* [Modern Methods for Sentiment Analysis](http://districtdatalabs.silvrback.com/modern-methods-for-sentiment-analysis) shows how "word vectors" can be used for more accurate sentiment analysis.
* [Identifying Humorous Cartoon Captions](http://www.cs.huji.ac.il/~dshahaf/pHumor.pdf) is a readable paper about identifying funny captions submitted to the New Yorker Caption Contest.
* [DC Natural Language Processing](http://www.meetup.com/DC-NLP/) is an active Meetup group in our local area.

-----

### Class 16: Kaggle Competition
* Overview of how Kaggle works ([slides](slides/16_kaggle.pdf))
* Kaggle In-Class competition: [Predict whether a Stack Overflow question will be closed](https://inclass.kaggle.com/c/dat8-stack-overflow)
    * [Complete code file](code/16_kaggle.py)
    * [Minimal code file](code/16_kaggle_minimal.py): excludes all exploratory code
    * [Explanations of log loss](http://www.quora.com/What-is-an-intuitive-explanation-for-the-log-loss-function)

**Homework:**
* You will be assigned to review the project drafts of two of your peers. You have until Tuesday 10/20 to provide them with feedback, according to the [peer review guidelines](project/peer_review.md).
* Read [A Visual Introduction to Machine Learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/) for a brief overview of decision trees.
* Download and install [Graphviz](http://www.graphviz.org/), which will allow you to visualize decision trees in scikit-learn.
    * Windows users should also add Graphviz to your path: Go to Control Panel, System, Advanced System Settings, Environment Variables. Under system variables, edit "Path" to include the path to the "bin" folder, such as: `C:\Program Files (x86)\Graphviz2.38\bin`
* **Optional:** Keep working on our Kaggle competition! You can make up to 5 submissions per day, and the competition doesn't close until 6:30pm ET on Tuesday 10/27 (class 21).

**Resources:**
* [Specialist Knowledge Is Useless and Unhelpful](http://www.slate.com/articles/health_and_science/new_scientist/2012/12/kaggle_president_jeremy_howard_amateurs_beat_specialists_in_data_prediction.html) is a brief interview with Jeremy Howard (past president of Kaggle) in which he argues that data science skills are much more important than domain expertise for creating effective predictive models.
* [Getting in Shape for the Sport of Data Science](https://www.youtube.com/watch?v=kwt6XEh7U3g) (74 minutes), also by Jeremy Howard, contains a lot of tips for competitive machine learning.
* [Learning from the best](http://blog.kaggle.com/2014/08/01/learning-from-the-best/) is an excellent blog post covering top tips from Kaggle Masters on how to do well on Kaggle.
* [Feature Engineering Without Domain Expertise](https://www.youtube.com/watch?v=bL4b1sGnILU) (17 minutes), a talk by Kaggle Master Nick Kridler, provides some simple advice about how to iterate quickly and where to spend your time during a Kaggle competition.
* These examples may help you to better understand the process of feature engineering: predicting the number of [passengers at a train station](https://medium.com/@chris_bour/french-largest-data-science-challenge-ever-organized-shows-the-unreasonable-effectiveness-of-open-8399705a20ef), identifying [fraudulent users of an online store](https://docs.google.com/presentation/d/1UdI5NY-mlHyseiRVbpTLyvbrHxY8RciHp5Vc-ZLrwmU/edit#slide=id.p), identifying [bots in an online auction](https://www.kaggle.com/c/facebook-recruiting-iv-human-or-bot/forums/t/14628/share-your-secret-sauce), predicting who will [subscribe to the next season of an orchestra](http://blog.kaggle.com/2015/01/05/kaggle-inclass-stanfords-getting-a-handel-on-data-science-winners-report/), and evaluating the [quality of e-commerce search engine results](http://blog.kaggle.com/2015/07/22/crowdflower-winners-interview-3rd-place-team-quartet/).
* [Our perfect submission](https://www.kaggle.com/c/restaurant-revenue-prediction/forums/t/13950/our-perfect-submission) is a fun read about how great performance on the [public leaderboard](https://www.kaggle.com/c/restaurant-revenue-prediction/leaderboard/public) does not guarantee that a model will generalize to new data.

-----

### Class 17: Decision Trees
* Decision trees ([notebook](notebooks/17_decision_trees.ipynb))
* Exercise with Capital Bikeshare data ([notebook](notebooks/17_bikeshare_exercise.ipynb), [data](data/bikeshare.csv), [data dictionary](https://www.kaggle.com/c/bike-sharing-demand/data))

**Homework:**
* Read the "Wisdom of the crowds" section from MLWave's post on [Human Ensemble Learning](http://mlwave.com/human-ensemble-learning/).
* **Optional:** Read the abstract from [Do We Need Hundreds of Classifiers to Solve Real World Classification Problems?](http://jmlr.csail.mit.edu/papers/volume15/delgado14a/delgado14a.pdf), as well as Kaggle CTO Ben Hamner's [comment](https://news.ycombinator.com/item?id=8719723) about the paper, paying attention to the mentions of "Random Forests".

**Resources:**
* scikit-learn's documentation on [decision trees](http://scikit-learn.org/stable/modules/tree.html) includes a nice overview of trees as well as tips for proper usage.
* For a more thorough introduction to decision trees, read section 4.3 (23 pages) of [Introduction to Data Mining](http://www-users.cs.umn.edu/~kumar/dmbook/index.php). (Chapter 4 is available as a free download.)
* If you want to go deep into the different decision tree algorithms, this slide deck contains [A Brief History of Classification and Regression Trees](https://drive.google.com/file/d/0B-BKohKl-jUYQ3RpMEF0OGRUU3RHVGpHY203NFd3Z19Nc1ZF/view).
* [The Science of Singing Along](http://www.doc.gold.ac.uk/~mas03dm/papers/PawleyMullensiefen_Singalong_2012.pdf) contains a neat regression tree (page 136) for predicting the percentage of an audience at a music venue that will sing along to a pop song.
* Decision trees are common in the medical field for differential diagnosis, such as this classification tree for [identifying psychosis](http://www.psychcongress.com/sites/naccme.com/files/images/pcn/saundras/psychosis_decision_tree.pdf).

-----

### Class 18: Ensembling
* Finish decision trees lesson ([notebook](notebooks/17_decision_trees.ipynb))
* Ensembling ([notebook](notebooks/18_ensembling.ipynb))
    * [Major League Baseball player data](data/hitters.csv) from 1986-87
    * [Data dictionary](https://cran.r-project.org/web/packages/ISLR/ISLR.pdf) (page 7)

**Resources:**
* scikit-learn's documentation on [ensemble methods](http://scikit-learn.org/stable/modules/ensemble.html) covers both "averaging methods" (such as bagging and Random Forests) as well as "boosting methods" (such as AdaBoost and Gradient Tree Boosting).
* MLWave's [Kaggle Ensembling Guide](http://mlwave.com/kaggle-ensembling-guide/) is very thorough and shows the many different ways that ensembling can take place.
* Browse the excellent [solution paper](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/ChenglongChen/Kaggle_CrowdFlower/master/Doc/Kaggle_CrowdFlower_ChenglongChen.pdf) from the winner of Kaggle's [CrowdFlower competition](https://www.kaggle.com/c/crowdflower-search-relevance) for an example of the work and insight required to win a Kaggle competition.
* [Interpretable vs Powerful Predictive Models: Why We Need Them Both](https://medium.com/@chris_bour/interpretable-vs-powerful-predictive-models-why-we-need-them-both-990340074979) is a short post on how the tactics useful in a Kaggle competition are not always useful in the real world.
* [Not Even the People Who Write Algorithms Really Know How They Work](http://www.theatlantic.com/technology/archive/2015/09/not-even-the-people-who-write-algorithms-really-know-how-they-work/406099/) argues that the decreased interpretability of state-of-the-art machine learning models has a negative impact on society.
* For an intuitive explanation of Random Forests, read Edwin Chen's answer to [How do random forests work in layman's terms?](http://www.quora.com/Random-Forests/How-do-random-forests-work-in-laymans-terms/answer/Edwin-Chen-1)
* [Large Scale Decision Forests: Lessons Learned](http://blog.siftscience.com/blog/2015/large-scale-decision-forests-lessons-learned) is an excellent post from Sift Science about their custom implementation of Random Forests.
* [Unboxing the Random Forest Classifier](http://nerds.airbnb.com/unboxing-the-random-forest-classifier/) describes a way to interpret the inner workings of Random Forests beyond just feature importances.
* [Understanding Random Forests: From Theory to Practice](http://arxiv.org/pdf/1407.7502v3.pdf) is an in-depth academic analysis of Random Forests, including details of its implementation in scikit-learn.

-----

### Class 19: Advanced scikit-learn and Clustering
* Advanced scikit-learn ([notebook](notebooks/19_advanced_sklearn.ipynb))
    * [StandardScaler](http://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html): standardizing features
    * [Pipeline](http://scikit-learn.org/stable/modules/pipeline.html): chaining steps
* Clustering ([slides](slides/19_clustering.pdf), [notebook](notebooks/19_clustering.ipynb))
    * K-means: [documentation](http://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html), [visualization 1](http://tech.nitoyon.com/en/blog/2013/11/07/k-means/), [visualization 2](http://www.naftaliharris.com/blog/visualizing-k-means-clustering/)
    * DBSCAN: [documentation](http://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html), [visualization](http://www.naftaliharris.com/blog/visualizing-dbscan-clustering/)

**Homework:**
* Reread [Understanding the Bias-Variance Tradeoff](http://scott.fortmann-roe.com/docs/BiasVariance.html). (The "answers" to the [guiding questions](homework/09_bias_variance.md) have been posted and may be helpful to you.)
* **Optional:** Watch these two excellent (and related) videos from Caltech's Learning From Data course: [bias-variance tradeoff](http://work.caltech.edu/library/081.html) (15 minutes) and [regularization](http://work.caltech.edu/library/121.html) (8 minutes).

**scikit-learn Resources:**
* This is a longer example of [feature scaling](https://github.com/rasbt/pattern_classification/blob/master/preprocessing/about_standardization_normalization.ipynb) in scikit-learn, with additional discussion of the types of scaling you can use.
* [Practical Data Science in Python](http://radimrehurek.com/data_science_python/) is a long and well-written notebook that uses a few advanced scikit-learn features: pipelining, plotting a learning curve, and pickling a model.
* To learn how to use [GridSearchCV and RandomizedSearchCV](http://scikit-learn.org/stable/modules/grid_search.html) for parameter tuning, watch [How to find the best model parameters in scikit-learn](https://www.youtube.com/watch?v=Gol_qOgRqfA) (28 minutes) or read the [associated notebook](https://github.com/justmarkham/scikit-learn-videos/blob/master/08_grid_search.ipynb).
* Sebastian Raschka has a number of excellent resources for scikit-learn users, including a repository of [tutorials and examples](https://github.com/rasbt/pattern_classification), a library of machine learning [tools and extensions](http://rasbt.github.io/mlxtend/), a new [book](https://github.com/rasbt/python-machine-learning-book), and a semi-active [blog](http://sebastianraschka.com/blog/).
* scikit-learn has an incredibly active [mailing list](https://www.mail-archive.com/scikit-learn-general@lists.sourceforge.net/index.html) that is often much more useful than Stack Overflow for researching functions and asking questions.
* If you forget how to use a particular scikit-learn function that we have used in class, don't forget that this repository is fully searchable!

**Clustering Resources:**
* For a very thorough introduction to clustering, read chapter 8 (69 pages) of [Introduction to Data Mining](http://www-users.cs.umn.edu/~kumar/dmbook/index.php) (available as a free download), or browse through the chapter 8 slides.
* scikit-learn's user guide compares many different [types of clustering](http://scikit-learn.org/stable/modules/clustering.html).
* This [PowerPoint presentation](http://www2.research.att.com/~volinsky/DataMining/Columbia2011/Slides/Topic6-Clustering.ppt) from Columbia's Data Mining class provides a good introduction to clustering, including hierarchical clustering and alternative distance metrics.
* An Introduction to Statistical Learning has useful videos on [K-means clustering](https://www.youtube.com/watch?v=aIybuNt9ps4&list=PL5-da3qGB5IBC-MneTc9oBZz0C6kNJ-f2) (17 minutes) and [hierarchical clustering](https://www.youtube.com/watch?v=Tuuc9Y06tAc&list=PL5-da3qGB5IBC-MneTc9oBZz0C6kNJ-f2) (15 minutes).
* This is an excellent interactive visualization of [hierarchical clustering](https://joyofdata.shinyapps.io/hclust-shiny/).
* This is a nice animated explanation of [mean shift clustering](http://spin.atomicobject.com/2015/05/26/mean-shift-clustering/).
* The [K-modes algorithm](http://www.cs.ust.hk/~qyang/Teaching/537/Papers/huang98extensions.pdf) can be used for clustering datasets of categorical features without converting them to numerical values. Here is a [Python implementation](https://github.com/nicodv/kmodes).
* Here are some fun examples of clustering: [A Statistical Analysis of the Work of Bob Ross](http://fivethirtyeight.com/features/a-statistical-analysis-of-the-work-of-bob-ross/) (with [data and Python code](https://github.com/fivethirtyeight/data/tree/master/bob-ross)), [How a Math Genius Hacked OkCupid to Find True Love](http://www.wired.com/2014/01/how-to-hack-okcupid/all/), and [characteristics of your zip code](http://www.esri.com/landing-pages/tapestry/).

-----

### Class 20: Regularization and Regular Expressions
* Regularization ([notebook](notebooks/20_regularization.ipynb))
    * Regression: [Ridge](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Ridge.html), [RidgeCV](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.RidgeCV.html), [Lasso](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Lasso.html), [LassoCV](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LassoCV.html)
    * Classification: [LogisticRegression](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)
    * Helper functions: [Pipeline](http://scikit-learn.org/stable/modules/pipeline.html), [GridSearchCV](http://scikit-learn.org/stable/modules/grid_search.html)
* Regular expressions
    * [Baltimore homicide data](data/homicides.txt)
    * [Regular expressions 101](https://regex101.com/#python): real-time testing of regular expressions
    * [Reference guide](code/20_regex_reference.py)
    * [Exercise](code/20_regex_exercise.py)

**Homework:**
* Your final project is due next week!
* **Optional:** Make your final submissions to our Kaggle competition! It closes at 6:30pm ET on Tuesday 10/27.
* **Optional:** Read this classic paper, which may help you to connect many of the topics we have studied throughout the course: [A Few Useful Things to Know about Machine Learning](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf).

**Regularization Resources:**
* The scikit-learn user guide for [Generalized Linear Models](http://scikit-learn.org/stable/modules/linear_model.html) explains different variations of regularization.
* Section 6.2 of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/) (14 pages) introduces both lasso and ridge regression. Or, watch the related videos on [ridge regression](https://www.youtube.com/watch?v=cSKzqb0EKS0&list=PL5-da3qGB5IB-Xdpj_uXJpLGiRfv9UVXI&index=6) (13 minutes) and [lasso regression](https://www.youtube.com/watch?v=A5I1G1MfUmA&index=7&list=PL5-da3qGB5IB-Xdpj_uXJpLGiRfv9UVXI) (15 minutes).
* For more details on lasso regression, read Tibshirani's [original paper](http://statweb.stanford.edu/~tibs/lasso/lasso.pdf).
* For a math-ier explanation of regularization, watch the last four videos (30 minutes) from week 3 of Andrew Ng's [machine learning course](https://www.coursera.org/learn/machine-learning/), or read the [related lecture notes](http://www.holehouse.org/mlclass/07_Regularization.html) compiled by a student.
* This [notebook](https://github.com/luispedro/PenalizedRegression/blob/master/PenalizedRegression.ipynb) from chapter 7 of [Building Machine Learning Systems with Python](https://www.packtpub.com/big-data-and-business-intelligence/building-machine-learning-systems-python) has a nice long example of regularized linear regression.
* There are some special considerations when using dummy encoding for categorical features with a regularized model. This [Cross Validated Q&A](https://stats.stackexchange.com/questions/69568/whether-to-rescale-indicator-binary-dummy-predictors-for-lasso) debates whether the dummy variables should be standardized (along with the rest of the features), and a comment on this [blog post](http://appliedpredictivemodeling.com/blog/2013/10/23/the-basics-of-encoding-categorical-data-for-predictive-models) recommends that the baseline level should not be dropped.

**Regular Expressions Resources:**
* Google's Python Class includes an excellent [introductory lesson](https://developers.google.com/edu/python/regular-expressions) on regular expressions (which also has an associated [video](https://www.youtube.com/watch?v=kWyoYtvJpe4&index=4&list=PL5-da3qGB5IA5NwDxcEJ5dvt8F9OQP7q5)).
* Python for Informatics has a nice [chapter](http://www.pythonlearn.com/html-270/book012.html) on regular expressions. (If you want to run the examples, you'll need to download [mbox.txt](http://www.py4inf.com/code/mbox.txt) and [mbox-short.txt](http://www.py4inf.com/code/mbox-short.txt).)
* [Breaking the Ice with Regular Expressions](https://www.codeschool.com/courses/breaking-the-ice-with-regular-expressions/) is an interactive Code School course, though only the first "level" is free.
* If you want to go really deep with regular expressions, [RexEgg](http://www.rexegg.com/) includes endless articles and tutorials.
* [5 Tools You Didn't Know That Use Regular Expressions](http://blog.codeschool.io/2015/07/30/5-tools-you-didnt-know-that-use-regular-expressions/) demonstrates how regular expressions can be used with Excel, Word, Google Spreadsheets, Google Forms, text editors, and other tools.
* [Exploring Expressions of Emotions in GitHub Commit Messages](http://geeksta.net/geeklog/exploring-expressions-emotions-github-commit-messages/) is a fun example of how regular expressions can be used for data analysis, and [Emojineering](http://instagram-engineering.tumblr.com/post/118304328152/emojineering-part-2-implementing-hashtag-emoji) explains how Instagram uses regular expressions to detect emoji in hashtags.

-----

### Class 21: Course Review and Final Project Presentation
* Project presentations!
* [Data science review](https://docs.google.com/document/d/19gBCkmrbMpFFLPX8wa5daMnyl7J5BXhMV8JNJwgp1pk/edit?usp=sharing)

**Resources:**
* scikit-learn's [machine learning map](http://scikit-learn.org/stable/tutorial/machine_learning_map/) may help you to choose the "best" model for your task.
* [Choosing a Machine Learning Classifier](http://blog.echen.me/2011/04/27/choosing-a-machine-learning-classifier/) is a short and highly readable comparison of several classification models, [Classifier comparison](http://scikit-learn.org/stable/auto_examples/classification/plot_classifier_comparison.html) is scikit-learn's visualization of classifier decision boundaries, [Comparing supervised learning algorithms](http://www.dataschool.io/comparing-supervised-learning-algorithms/) is a model comparison table that I created, and [Supervised learning superstitions cheat sheet](http://ryancompton.net/assets/ml_cheat_sheet/supervised_learning.html) is a more thorough comparison (with links to lots of useful resources).
* [Machine Learning Done Wrong](http://ml.posthaven.com/machine-learning-done-wrong), [Machine Learning Gremlins](https://www.youtube.com/watch?v=tleeC-KlsKA) (31 minutes), [Clever Methods of Overfitting](http://hunch.net/?p=22), and [Common Pitfalls in Machine Learning](http://danielnee.com/?p=155) all offer thoughtful advice on how to avoid common mistakes in machine learning.
* [Practical machine learning tricks from the KDD 2011 best industry paper](http://blog.david-andrzejewski.com/machine-learning/practical-machine-learning-tricks-from-the-kdd-2011-best-industry-paper/) and Andrew Ng's [Advice for applying machine learning](http://cs229.stanford.edu/materials/ML-advice.pdf) include slightly more advanced advice than the resources above.
* [An Empirical Comparison of Supervised Learning Algorithms](http://www.cs.cornell.edu/~caruana/ctp/ct.papers/caruana.icml06.pdf) is a readable research paper from 2006, which was also presented as a [talk](http://videolectures.net/solomon_caruana_wslmw/) (77 minutes).

-----

### Class 22: Final Project Presentation
* Project presentations!
* [What's next?](other/advice.md)

-----

## Additional Resources

### Tidy Data
* [Good Data Management Practices for Data Analysis](https://www.prometheusresearch.com/good-data-management-practices-for-data-analysis-tidy-data-part-2/) briefly summarizes the principles of "tidy data".
* [Hadley Wickham's paper](http://www.jstatsoft.org/article/view/v059i10) explains tidy data in detail and includes lots of good examples.
* Example of a tidy dataset: [Bob Ross](https://github.com/fivethirtyeight/data/blob/master/bob-ross/elements-by-episode.csv)
* Examples of untidy datasets: [NFL ticket prices](https://github.com/fivethirtyeight/data/blob/master/nfl-ticket-prices/2014-average-ticket-price.csv), [airline safety](https://github.com/fivethirtyeight/data/blob/master/airline-safety/airline-safety.csv), [Jets ticket prices](https://github.com/fivethirtyeight/data/blob/master/nfl-ticket-prices/jets-buyer.csv), [Chipotle orders](https://github.com/TheUpshot/chipotle/blob/master/orders.tsv)
* If your co-workers tend to create spreadsheets that are [unreadable by computers](https://bosker.wordpress.com/2014/12/05/the-government-statistical-services-terrible-spreadsheet-advice/), they may benefit from reading these [tips for releasing data in spreadsheets](http://www.clean-sheet.org/). (There are some additional suggestions in this [answer](http://stats.stackexchange.com/questions/83614/best-practices-for-creating-tidy-data/83711#83711) from Cross Validated.)

### Databases and SQL
* This [GA slide deck](https://github.com/justmarkham/DAT5/blob/master/slides/20_sql.pdf) provides a brief introduction to databases and SQL. The [Python script](https://github.com/justmarkham/DAT5/blob/master/code/20_sql.py) from that lesson demonstrates basic SQL queries, as well as how to connect to a SQLite database from Python and how to query it using Pandas.
* The repository for this [SQL Bootcamp](https://github.com/brandonmburroughs/sql_bootcamp) contains an extremely well-commented SQL script that is suitable for walking through on your own.
* This [GA notebook](https://github.com/podopie/DAT18NYC/blob/master/classes/17-relational_databases.ipynb) provides a shorter introduction to databases and SQL that helpfully contrasts SQL queries with Pandas syntax.
* [SQLZOO](http://sqlzoo.net/wiki/SQL_Tutorial), [Mode Analytics](http://sqlschool.modeanalytics.com/), [Khan Academy](https://www.khanacademy.org/computing/computer-programming/sql), [Codecademy](https://www.codecademy.com/courses/learn-sql), [Datamonkey](http://datamonkey.pro/guess_sql/lessons/), and [Code School](http://campus.codeschool.com/courses/try-sql/contents) all have online beginner SQL tutorials that look promising. Code School also offers an [advanced tutorial](https://www.codeschool.com/courses/the-sequel-to-sql/), though it's not free.
* [w3schools](http://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all) has a sample database that allows you to practice SQL from your browser. Similarly, Kaggle allows you to query a large SQLite database of [Reddit Comments](https://www.kaggle.com/c/reddit-comments-may-2015/data) using their online "Scripts" application.
* [What Every Data Scientist Needs to Know about SQL](http://joshualande.com/data-science-sql/) is a brief series of posts about SQL basics, and [Introduction to SQL for Data Scientists](http://bensresearch.com/downloads/SQL.pdf) is a paper with similar goals.
* [10 Easy Steps to a Complete Understanding of SQL](https://web.archive.org/web/20150402234726/http://tech.pro/tutorial/1555/10-easy-steps-to-a-complete-understanding-of-sql) is a good article for those who have some SQL experience and want to understand it at a deeper level.
* SQLite's article on [Query Planning](http://www.sqlite.org/queryplanner.html) explains how SQL queries "work".
* [A Comparison Of Relational Database Management Systems](https://www.digitalocean.com/community/tutorials/sqlite-vs-mysql-vs-postgresql-a-comparison-of-relational-database-management-systems) gives the pros and cons of SQLite, MySQL, and PostgreSQL.
* If you want to go deeper into databases and SQL, Stanford has a well-respected series of [14 mini-courses](https://lagunita.stanford.edu/courses/DB/2014/SelfPaced/about).
* [Blaze](http://blaze.pydata.org) is a Python package enabling you to use Pandas-like syntax to query data living in a variety of data storage systems.

### Recommendation Systems
* This [GA slide deck](https://github.com/justmarkham/DAT4/blob/master/slides/18_recommendation_engines.pdf) provides a brief introduction to recommendation systems, and the [Python script](https://github.com/justmarkham/DAT4/blob/master/code/18_recommenders_soutions.py) from that lesson demonstrates how to build a simple recommender.
* Chapter 9 of [Mining of Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/bookL.pdf) (36 pages) is a more thorough introduction to recommendation systems.
* Chapters 2 through 4 of [A Programmer's Guide to Data Mining](http://guidetodatamining.com/) (165 pages) provides a friendlier introduction, with lots of Python code and exercises.
* The Netflix Prize was the famous competition for improving Netflix's recommendation system by 10%. Here are some useful articles about the Netflix Prize:
    * [Netflix Recommendations: Beyond the 5 stars](http://techblog.netflix.com/2012/04/netflix-recommendations-beyond-5-stars.html): Two posts from the Netflix blog summarizing the competition and their recommendation system
    * [Winning the Netflix Prize: A Summary](http://blog.echen.me/2011/10/24/winning-the-netflix-prize-a-summary/): Overview of the models and techniques that went into the winning solution
    * [A Perspective on the Netflix Prize](http://www2.research.att.com/~volinsky/papers/chance.pdf): A summary of the competition by the winning team
* This [paper](http://www.cs.umd.edu/~samir/498/Amazon-Recommendations.pdf) summarizes how Amazon.com's recommendation system works, and this [Stack Overflow Q&A](http://stackoverflow.com/questions/2323768/how-does-the-amazon-recommendation-feature-work) has some additional thoughts.
* [Facebook](https://code.facebook.com/posts/861999383875667/recommending-items-to-more-than-a-billion-people/) and [Etsy](https://codeascraft.com/2014/11/17/personalized-recommendations-at-etsy/) have blog posts about how their recommendation systems work.
* [The Global Network of Discovery](http://www.gnod.com/) provides some neat recommenders for music, authors, and movies.
* [The People Inside Your Machine](http://www.npr.org/blogs/money/2015/01/30/382657657/episode-600-the-people-inside-your-machine) (23 minutes) is a Planet Money podcast episode about how Amazon Mechanical Turks can assist with recommendation engines (and machine learning in general).
* Coursera has a [course](https://www.coursera.org/learn/recommender-systems) on recommendation systems, if you want to go even deeper into the material.
