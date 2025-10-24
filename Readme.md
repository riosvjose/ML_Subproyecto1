#Introducción 

El presente documento describe el desarrollo del subproyecto de minería de datos centrado en el análisis del Ames Housing Dataset, un conjunto de datos de referencia en el sector inmobiliario.

El objetivo principal de este estudio es aplicar y evaluar modelos avanzados de regresión (Ridge, Lasso y ElasticNet) para predecir el precio de las viviendas. Adicionalmente, se busca identificar e interpretar aquellas variables con mayor poder predictivo, con el fin de extraer conclusiones valiosas sobre los factores que determinan el valor de mercado de una propiedad.

#Requisitos del Sistema

Para garantizar la correcta ejecución del notebook, se deben cumplir los siguientes requisitos:

Versión de Python: Se requiere Python 3.10 o una versión superior. Puede verificar su versión ejecutando en su terminal:

python --version


Conexión a Internet: 
Es imprescindible contar con acceso a Internet durante la ejecución, ya que el notebook gestiona automáticamente la descarga de librerías especializadas (como pandas, scikit-learn o plotly) y, en su caso, del dataset desde repositorios públicos.
Además, se realiza la descarga del dataset desde Google drive, por ello es fundamental la conexión a internet.

#Entorno de Ejecución Recomendado

El código ha sido diseñado para ser ejecutado en los siguientes entornos, siendo Google Colab la opción recomendada para una puesta en marcha rápida y sin configuración adicional:

Google Colab (recomendado)

Jupyter Notebook (instalación local)

Visual Studio Code con la extensión de Jupyter

#Instalación de Dependencias

Si opta por una ejecución local (Jupyter o VS Code), asegúrese de tener instaladas las librerías necesarias mediante el siguiente comando

pip install -U numpy pandas scikit-learn matplotlib seaborn plotly nbformat

En Google Colab, el propio notebook incluye celdas que instalan las dependencias automáticamente.

#Ejecución del notebook

Abra el archivo Subproyecto1_MineriaDatos.ipynb en su entorno de preferencia (Google Colab, Jupyter, etc.).

Ejecute las celdas de código en orden secuencial, desde el inicio hasta el final del documento.

Durante la primera ejecución, es normal que la instalación de librerías requiera unos minutos. Le recomendamos aguardar a que este proceso finalice.

Una vez completado, podrá revisar los resultados, que incluyen gráficos, métricas de rendimiento y los coeficientes de los modelos.
