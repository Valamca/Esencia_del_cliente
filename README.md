#  Esencia del cliente | Python | Data Science | Alura
<br>

![alchemyrefiner_alchemymagic_0_d4d504ef-4fa9-4606-ba97-54474a8c0361_0](https://github.com/Valamca/Esencia_del_cliente/assets/129345721/90b605a2-8e2f-4c77-9af0-d50dbb87f402)

<ul align = center>

<img src="https://img.shields.io/badge/_Python-f7e172?style=flat&logo=python" />
  <img src="https://img.shields.io/badge/_Jupyter_Notebook-767677?style=flat&logo=jupyter"/>
  <img src="https://img.shields.io/badge/_Pandas-e00484?style=flat&logo=pandas"/>
  <img src="https://img.shields.io/badge/_scikit-learn-f89a36?style=flat&logo=scikit-learn"/>
  
</ul>


## Descripción: :page_facing_up: 🤖
Este proyecto tiene como objetivo presentar un análisis de ciencia de datos sobre la base de clientes de una cadena de supermercados. Se centra en la clusterización de los clientes para lograr un enfoque más efectivo hacia ellos.

### Configuración del ambiente: :computer: 
Para empezar, se puede utilizar cualquier entorno de Python, tan sólo asegúrate que sea una versión 3.X, el base es Jupyter Notebook, también necesitarás instalar algunas librerías de Python que son esenciales para este proyecto, como: <br>
<br>
- Pandas 
- Numpy 
- Matplotlib
- Scikit-learn
- Seaborn

### Obtención de datos: :page_with_curl: 
Los datos para el presente proyecto fueron obtenidos del siguiente repositorio: [Kaggle](https://www.kaggle.com/datasets/ramjasmaurya/medias-cost-prediction-in-foodmart)<br> 

![image](https://github.com/Valamca/Esencia_del_cliente/assets/129345721/44f73d78-999e-4cad-9c71-2238ade1be17)

### Exploración de los datos  :mag_right:

Como el dataset original está en inglés,se tradujo todo a español para tener una mejor comprensión del mismo.
La exploración visual de datos permite a los científicos de datos examinar y explorar grandes volúmenes de datos de manera intuitiva y eficiente. Al representar los datos visualmente, se pueden identificar características importantes, como valores atípicos, distribuciones, correlaciones y agrupaciones, que podrían no ser evidentes al examinar solo los números o las tablas de datos.

Haciendo uso de Matplotlib y Seaborn se generaron diversos gráficos para entender mejor los datos.

### Preprocesamiento

En esta fase se codificaron las variables categóricas para que el modelo de clusterización las pueda reconocer. además de seleccionarse algunas variables que demostraron ser mas relevantes que otras

### Clusterización y Validación

El algoritmo elegido para la clusterización fue Kmeans, se usaron tanto datos en bruto como datos estandarizados para observar su distribución y % de ajuste a los diferentes métodos de clusterización. <br>
Para realizar la estandarización de datos se recurrió al algoritmo de StandarScaler.

Para la **Validación** se usaron las métricas:<br>
 - Silhouette.
 - Davies-Bouldin.
 - Calinski and Harabasz.

### Descripción de cluster

Una vez se realizó la clusterización, se generaron las descripciones de que tipo de información fueron asignados a cada tipo de cluster, y algunas de las recomendaciones que se dan para abordar a cada tipo de segmentación de cliente.


**Desarrollador** :wink: 

 <img src="https://avatars.githubusercontent.com/u/129345721?v=4" width=115>
 
 **Francisco Valam Cortes**  <br>[<sub>GitHub</sub>](https://github.com/ValamCA) <img src="https://i.postimg.cc/hPxhb2YB/icons8-github-50.png" width =16>
 <br>[<sub>Linkedin </sub> ](https://www.linkedin.com/in/franciscovalamca/)<img src="https://i.postimg.cc/C5LJHycc/icons8-linkedin-48.png" width =16 ><br>
 [<sub>Twitter</sub>](https://twitter.com/FNiggalam)<img src="https://i.postimg.cc/xTrL2ND9/icons8-twitter-48.png" width =16 ><br>
