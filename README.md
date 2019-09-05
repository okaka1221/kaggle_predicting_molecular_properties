# kaggle-predicting-molecular-properties  
  
Codes for kaggle competition (top 6%).

[Predicting Molecular Properties](https://www.kaggle.com/c/champs-scalar-coupling)

<br>

Notebooks
=========

`feature_engineering/distance_each_other.ipynb`: calculates distance each pair of atoms in molecular

`feature_engineering/geometry_information.ipynb`: calculates distance of top n(set in notebook) closest pair of atoms in molecular

`feature_engineering/feature_engineering_final.ipynb`: merge above features, add some features such as anglea and potential and then separate data based on types

`all_type_at_once.ipynb`: train separate models for each type
