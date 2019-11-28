:uk: [Go to english version](https://github.com/iseka-dev/Galicia-datathon/blob/master/README.md)

# :alien: Dataton Galicia :alien:

Este proyecto fue desarrollado en ocasión de la Datatón organizada por el Banco Galicia en Kaggle.

El objetivo de la competencia era predecir aquellos clientes del banco Galicia que fueran a realizar *conversiones positivas* durante el primer trimestre del 2019. Para ese propósito fue dado un dataset con con el comportamiento de los usarios en el sitio web del banco Galicia durante el año 2018 y el primer trimestre del 2019, y que también incluía aquellos usuarios que realizaron conversiones positivas durante el año 2018.
El dataset puede descargarse desde [aquí](https://www.kaggle.com/c/banco-galicia-dataton-2019/data).

Este [notebook - galicia1.ipynb](https://github.com/iseka-dev/Galicia-datathon/blob/master/galicia1.ipynb) contiene los modelos que fueron entrenados y optimizados. A continuación, una lista exhaustiva de los modelos implementados: *light gradient boosting* (kernel), *Decision Tree*, *AdaBoost*, *RandomForestClaslsifier*, CATboost*, XGBoosting*, *SupportVectorMachine*, *Clustering*, y final mente una solución por *stacking* fue presentada a la competición. En el notebook también se hizo selección de features a través de PCA y selectKbest(). Los modelos fueron entrenados y validados usando diferentes tipos de segmentación (KFold o train/test splitting). 
Vale notar que, si bien finalice en el primer tercio de competidores, la participación fue una oportunidad para implementar diferentes modelos.

[respuesta_final.csv](https://github.com/iseka-dev/Galicia-datathon/blob/master/respuesta_final) provee la *solución* presentada al datatón. Es el resultado de la predicción por stacking. Si bien el notebook también produce archivos .zip con las soluciones al desafio según cada modelo por separado, estos archivos no son provistos. La principal razón es que las soluciones sólo pueden ser evaluadas en comparación con las conversión reales durante el primer trimestre del 2019, pero Kaggle no provee esta data, que sirve para determinar los ganadores de la competición.

**skills**: python, pandas, PCA, feature selection, scikit-learn (decision tree, SVM, RandomForest, Clustering), LGBM, XGBoosting, CATboost, Stacking.
