Estructura del repositorio:

	- data_warehouse : directorio en donde se descarga, guarda y pre-procesan datos
		- data_mart.ipynb : Descargar información de productos para almacenar dentro del directorio products
		- products : Se almacena csv de productos en formato cdv
		- semantic_similarity : Se almacena información de similitud semántica en formato csv
		- thumbnail_manager : Descargar las thumbnails usando la información de products para almacenar dentro del directorio: thumbnails.
		- thumbnail_similarity : Se almacena información de similitud de las thumbnails en formato csv
		- thumbnails : Se almacenan las thumbnails en formato jpg

	- eda.ipynb : Análisis exploratorio inicial de la información del directorio products
	- semantic_similarity_score.ipynb : Calcular la similitud semántica y almacenarla en el directorio semantic_similarity
	- thumbnail_similarity_score.ipynb : Calcular la similitud entre thumbnails y almacenarla en el directorio thumbnail_similarity
	- visualize_similarity_1D.ipynb: Visualizaciones de similitud de un solo tipo.
	- visualize_similarity_2D.ipynb: Visualizaciones de similitud de dos tipos.


Notas Adicionales:
	- todo se hizo en notebooks por simplicidad
	- se emuló vagamente la estructura de un repositorio de un proyecto de ciencia de datos