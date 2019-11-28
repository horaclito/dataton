:es: [Ir a versión en español](https://github.com/iseka-dev/Galicia-datathon/blob/master/README.sp.md)

# :alien: Galicia Datathon :alien:

This project was developed on occasion of the **Galicia Dathaton**, hosted in Kaggle.

The competition aimed to predict *positive conversions* among Galicia's clients, in the first trimester of 2019. To that purpose, a dataset with user's behavior in Galicia's website and actual conversions in 2018 were given.
The dataset can be downloaded from [here](https://www.kaggle.com/c/banco-galicia-dataton-2019/data).

This [notebook - galicia1.ipynb](https://github.com/iseka-dev/Galicia-datathon/blob/master/galicia1.ipynb) contains trained and optimised -when appropriated- models. Here is an **exhaustive list of implemented models**: *light gradient boosting* (kernel), *Decision Tree*, *AdaBoost*, *RandomForestClaslsifier*, CATboost*, XGBoosting*, *SupportVectorMachine*, *Clustering*, and finally a stacking solution was submitted to the Kaggle competition. Feature selection was done through PCA and selectKbest(). And models were trained and validated through different kinds of splittings (KFold or simple train/test splitting). 
It's worth noting that, even if I ended up in the first third of competitors, the participation was more an excuse to implement different models.

[respuesta_final.csv](https://github.com/iseka-dev/Galicia-datathon/blob/master/respuesta_final) provides the *submitted solution* to the Datathon. It is the result of the stacking prediction. If well the code produces .zip files with solutions for each model alone, these are not provided. Anyway, these solutions could be only checked with actual conversions in the first trimester of 2019, but Kaggle doesn't provide this data, which was used to evaluate competitors.

**skills**: python, pandas, PCA, feature selection, scikit-learn (decision tree, SVM, RandomForest, Clustering), LGBM, XGBoosting, CATboost, Stacking.
