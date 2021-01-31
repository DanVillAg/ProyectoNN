# ProyectoNN
## UNAM facultad de Ciencias Proyecto materia de Redes neuronales
### Redes covolucionaltes y LTSM para clasificación musical

* Profesora: Verónica Esther Arriola Ríos
* Ayudante: Dimitri Semenov Flores
* Ayud. Lab.:	Osvaldo Baruch Acevedo Badillo

## Integrante:
* Daniel Villegas Aguilar

El reporte principal es el archivo Experimento_Convolución2d, el otro contiene un segundo intento con otra arquitectura, inspirado en el siguiente artículo (aunque con el cambio de un lstm en lugar de una red recurrente):

 * https://arxiv.org/pdf/1609.04243.pdf

En general, al menos segun lo consultado en la litratura, el reconocimiento de audio por medio de redes convolucionales presenta un reto bastante dificil. Los resultados alcanzados no fueron los deseados, ya que no se obtuvo un buen predictor. Ambos métodos intentados no superaron el 30% de accuracy.

Se trabajó con los datos obtenidos en la siguientes ligas:

* https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification
* http://millionsongdataset.com/pages/getting-dataset/
* https://github.com/mdeff/fma

Se consultaron las siguientes ligas de referencia:
* http://proceedings.mlr.press/v9/glorot10a/glorot10a.pdf
* http://www2.ece.rochester.edu/~zduan/teaching/ece477/projects/2017/MingqingYun_JingBi_ReportFinal.pdf
* https://www.uio.no/studier/emner/matnat/ifi/IN5490/h18/project-presentations-october-15/cnn-vs.-rnn-for-music-generation.pdf
* https://sigport.org/sites/default/files/docs/ISCSLP2016_JiaDai_pptA4.pdf

Existen 2 archivos .ipynb con los resultados de las 2 implementaciones realizadas.
