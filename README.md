# kaggle-predicting-molecular-properties  
  
Codes for kaggle competition (top 6%).

[Predicting Molecular Properties](https://www.kaggle.com/c/champs-scalar-coupling)

<br>

Notebooks
=========

`feature_engineering/distance_each_other.ipynb`: calculate distance each pair of atoms in molecular

`feature_engineering/geometry_information.ipynb`: calculate distance of top n(set in notebook) closest pair of atoms in molecular

`feature_engineering/feature_engineering_final.ipynb`: merge above features, add some features such as anglea and potential and then separate data based on types

`all_type_at_once.ipynb`: train separate models for each type

`blending.ipynb`: make a blend of models

`merge_each_type.ipynb`: merge predictions on each molecular types into one submission file
