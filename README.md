
# Projecto - Prueba Practica

En este documento se encuentran las soluciones para los 3 problemas planteados en el archivo prueba_practica.docx.
Los cuales se dividen en lo siguiente:

    1- Natural Language Processing 
    2- Computer Vision
    3- 3.Architecture and AWS

### Natural Languague Processing

La solucion a el primer punto viene en el archivo:
- Ejercicio1.ipynb
Dentro de este documento viene la solucion al problema de clasificacion utilizando un modelo con arquitectura transformer,bajo la libreria distilbert de hugging face. 
El archivo contiene una explicacion del modelo y del codigo, ademas de algunas diferencias que se encontraron entre la solucion propuesta y el articulo - It Takes Two to Lie: One to Lie, and One to Listen, Denis Peskov, Benny Cheng.

El documento consta de los siguientes pasos:

    a- Carga de los datos
    b- Tratamiento del texto (Normalizados)
    c- Modelo LLMS - distilbert-base-uncased
    d- Tokenizados - distilbert-base-uncased
    e- Analisis de las palabras mas frecuentes
    f- Se define la metrica de evaluacion - Accuracy
    g- Modelo Baseline - LoRA config
    h- resultados y conclusion modelo baseline
    i- Modelo 2 - balanceo de clases 
    j- resultados y conclusiones modelo 2
    k- Modelo 3 - balanceo de clases / Game_score 
    l- resultados y conclusion modelo 3
    m- Modelo 4 -  balanceo clases / variables exogenas
    n- resultados y conclusiones modelo 4
    o- Comparacion articulo y solucion propuesta


### Computer Vision

La solucion al segundo punto viene en el archivo:
- ejercicio2.ipynb 

Dentro del documento se encuentra la solucion al problema desarrollado en codigo python (Google -Collab) que recibe un archivo JSON o PDF, que es posteriormente cargado con el fin de extraer el Numero de matricula, la fecha (YYYY-MM-DD), el departamento, el municipio, la vereda y el estatus del folio.

El documento consta de los siguientes pasos:

    a- Funcion para cargar y extraer la informacion:
    dentro de esta funcion es posible seleccionar el 
    tipo de archivo JSON o PDF.
    b- Si es pdf, la funcion utiliza el modelo textract de AWS, convierte 
    el pdf en imagen y extre la informacion requerida.
    c- Si es formato json, la funcion extrae la informacion requerida. 

### Architecture and AWS

La solucion al tercer punto viene en los archivos:

    a- ejercicio3.png
    b- ejercicio3.PDF

En el documento (a) se encuentra el diagrama de arquitectura simple construido en la pagina: http://app.diagrams.net, para llevar a cabo un modelo de machine learning y crear una arquitectura de nube en AWS y ser lanzado en una API. 

En el documento (b) se encuentra la explicacion de los pasos del diagrama para llevar a cabo la tarea anterior. 
## Deployment

Para correr el jupyter notebook ejercicio1.ipynb es necesario instalar las librerias siguientes.

```bash
  pip intall requirements.txt
```


## Authors

- [@camilopulzara](https://github.com/camilopulzara)

