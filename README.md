# CatBoost-in-Python-ML

CatBoost is a machine learning algorithm that uses gradient boosting on decision trees. It is available as an open source library.It is a powerfull library build by Yandex community. This note book deals with indepth understanding of how to implement the catboost algorithm on the data and improving the accuracy of the model.

Main advantages of CatBoost:
  - Superior quality when [compared](https://github.com/catboost/benchmarks/blob/master/README.md) with other GBDT libraries on many datasets.
  - Best in class [prediction](https://catboost.ai/docs/concepts/c-plus-plus-api.html) speed.
  - Support for both [numerical and categorical](https://catboost.ai/docs/concepts/algorithm-main-stages.html) features.
  - Fast GPU and multi-GPU support for training out of the box.
  - Visualization tools [included](https://catboost.ai/docs/features/visualization.html).
  
Implementation of CatBoost in machine learning in Python on brest cancer dataset

Refrences
-------
- All CatBoost documentation is available [here](https://catboost.ai/docs/concepts/about.html)
- [dataset link](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic))
- https://catboost.ai/docs/concepts/python-reference_parameters-list.html

Reference Paper
-------
Anna Veronika Dorogush, Andrey Gulin, Gleb Gusev, Nikita Kazeev, Liudmila Ostroumova Prokhorenkova, Aleksandr Vorobev ["Fighting biases with dynamic boosting"](https://arxiv.org/abs/1706.09516). arXiv:1706.09516, 2017.

Anna Veronika Dorogush, Vasily Ershov, Andrey Gulin ["CatBoost: gradient boosting with categorical features support"](http://learningsys.org/nips17/assets/papers/paper_11.pdf). Workshop on ML Systems
