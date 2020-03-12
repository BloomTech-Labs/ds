# Big Data

What if your data doesn’t fit in memory?

My advice: Try to “scale up” (use a server with more memory) before you try to “scale out” (use distributed computing frameworks).

If you’re looking at frameworks, try something lightweight like Dask before something heavy-duty like Spark. https://docs.dask.org/en/latest/spark.html

If you’re fitting models, figure out whether more data is actually useful:
- http://technocalifornia.blogspot.com/2012/07/more-data-or-better-models.html
- https://jakevdp.github.io/PythonDataScienceHandbook/05.03-hyperparameters-and-model-validation.html#Learning-curves-in-Scikit-Learn

Then, decide whether to use a smaller sample that does fit in memory, or, try “incremental learning”:
- https://scikit-learn.org/0.15/modules/scaling_strategies.html
- https://examples.dask.org/machine-learning/incremental.html 