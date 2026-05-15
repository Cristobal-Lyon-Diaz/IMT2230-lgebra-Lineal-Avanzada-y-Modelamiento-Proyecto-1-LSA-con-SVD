# IMT2230-lgebra-Lineal-Avanzada-y-Modelamiento-Proyecto-1-LSA-con-SVD


En este proyecto realizamos un análisis latente usando SVD, donde se creó un repositorio llamado “IMT2230-lgebra-Lineal-Avanzada-y-Modelamiento-Proyecto-1-LSA-con-SVD” , que incluye principalmente la carpeta data con los datos necesarios, el enunciado del proyecto y un Jupyter Notebook llamado “main.ipynb” donde se desarrolla todo el proyecto (para verlo se necesita ejecutar este archivo), el cual, tiene las siguientes librerías como requerimiento para ejecutarlo correctamente: “pandas”, “os”, “re”, “nltk”, “sklearn”, “matplotlib”, “adjustText”, “numpy”, “pathlib” y “random”.

	
  
Para el proyecto se escogió el corpus extraído del dataset de Nikhil Nayak (llamado carlosgdcj en Kaggle) publicado en Kaggle como “genius song lyrics with language information” , que se trata de la recopilación de mas de 5 millones de canciones, poemas y libros, de todos los idiomas, estilos y épocas, de las cuales solo se usaran 500 escogidas al azar en español entre el primer millón de obras literarias, para que sea un numero factible de procesar en cualquier dispositivo, para esto se filtraron primero todas las obras literarias a aquellas que solo estaban en español, y se usó “sample” con la semilla 23, para con ello tener muestras de obras de todos los estilos de forma aleatoria y que sea totalmente reproducible al siempre elegir la misma semilla. Después de extraer los 500 ejemplares, se creo un vector para analizar los términos totales y únicos de cada documento, y se guardo un archivo csv con las obras literarias que se usaran en el proyecto, ya que el archivo original, si bien se puede descargar perfectamente desde su fuente, al tener mas de 5 millones de documentos, no se puede subir al repositorio, por ende solo se subirán las obras que se usaran en el análisis.
  


Como hipótesis inicial se escogió esperar que con el análisis se pudiera clasificar cada obra literaria según su década al comparar el contenido de cada una de ellas, es decir, que se puede clasificar todos los de los años 80s por ejemplo en un grupo solo según las letras.

