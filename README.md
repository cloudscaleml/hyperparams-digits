# Hyper-parameter tuning

Hyper-parameters are adjustable parameters you choose for model training that guide the training process. The HyperDrive package helps you automate choosing these parameters. For example, you can define the parameter search space as discrete or continuous, and a sampling method over the search space as random, grid, or Bayesian. Also, you can specify a primary metric to optimize in the hyperparameter tuning experiment, and whether to minimize or maximize that metric. You can also define early termination policies in which poorly performing experiment runs are canceled and new ones started. To define a reusable machine learning workflow for HyperDrive, use hyper_drive_step to create a Pipeline.


[Hyper Drive Docs link](https://docs.microsoft.com/en-us/python/api/azureml-train-core/azureml.train.hyperdrive?view=azure-ml-py)
