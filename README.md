# REGRESION-PESO-BOVINOS
Este repositorio contiene los modelos de ML y Deeplearning de la estimación de peso de ganado bovino, el documentos estan dividios en branches
donde el 

Branch MODELOS_SVR_RF_XGBOOST-REGRESSOR contiene los modelos:

Los archivos de las datos tabulares se pueden encontrar como train y test convertidos con standartScaler() y OneHotEncoding()

Todos los archivos deben ser

1. V0_SVR_RF_BOVINO_REGRESSOR.ipyb
   Descripción: Contiene los modelos de SUPPORT VECTOR MACHINE REGRESSOR Y RANDOM FOREST REGRESSOR en un mismo archivo.
3. V0_XGBOOST_REGRESSION.ipyb
   Descripción: Contiene los modelos de XGboost REGRESSOR con mejoras.

En estos archivos se encuentran incluidos los modelos base y mejora o con grilla de busqueda de hiperparametros.

Branch MODELOS-MLP-REGRESOR
 
 1. SHP_V0_CROSS_VALID_MLP_REGRESSION.ipyb

    Nodelo base con modelo sencillo MLP.
    
 3. VO_CROSS_VALID_MLP_REGRESION.ipyb

     Nodelo base con modelo MLP con busqueda de parametros y K-FOLD validation implementados.

Branch MODELOS_MULTIMODALES-HIBRIDOS-PARALELO

1. V00_MOD_MULTI_PARALELO_SIN_RESNET50

   Modelo sin mejora o implementación de transfer learning usando.
   
3. V0_MOD_MULT_PARALELO_CON_RESNET50

    Modelo con mejora o implementación de transfer learning usando.

Branch MODELOS-MODALES-EN-SERIE

1. CNN+RF_MOD_SERIE

    Modelo sin mejora o implementación de transfer learning usando VGG16.
   
3. VGG16_B5+RF_MODELO_SERIE

   Modelo con mejora o implementación de transfer learning usando VGG16.
