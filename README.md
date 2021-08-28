# Data-Science-Portfolio
**Objective -** 
This is a repository created in line with my understanding &amp; implementation of the major complex ideas in Machine Learning &amp; Inferential Statistics. The motivation behind creating this open source resource is to validate my theoretical knowledge about these models and give back to the online community in terms of a structured and exhaustive format of learning fundamental concepts and best practices of Data Science in the industry.

**Constituent Elements -** 
This repository includes the following elements broadly:
1. **Tutorial/comparison/benchmarking notebooks (In the form of end-to-end ML mini projects)** for most of the popular ML and associated data science algorithms like sampling, feature selection, model interpretability, hypothesis testing in the following manner:

      1. **Statistical Inference** - Most of the major hypothesis tests and their pre-requisites/use-cases clearly outlined through a hierarchy
      2. **Pre-Processing of data** - Handling extreme imbalance in classes through statistical sampling
      3. **Feature Selection** - Generating feature importances and performing feature selection corresponding to supervised learning
      4. **Explainable ML** - Interpreting the intuition of predictions emanating out of the complex black box models 
      
2. **From-scratch implementations (using numpy)** of most of the commonly used ML models like linear models, CART, gradient boosting, DBSCAN, artificial neural networks etc. These from-scratch implementations have been created based on extensive personal research from online resources available and validated against the necessary benchmarks like Scikit-Learn, Tensorflow, Scipy etc. For all the cases, the manual implementations have matched up or outperformed the open source python benchmarking libraries mentioned above.   
These include the following:
      1. **Statistical Inference from scratch** - Manual implementation of popular hypothesis tests like t-test, Kruskal Wallis, Friedmans's test etc. for higher visibility into the inner workings. _These have been benchmarked against the available scipy & statsmodels versions_
      2. **Supervised ML from scratch** - Manual implementation of popular classical ML algorithms used for classification & regression. _These have been benchmarked against the available Scikit-Learn or relevant versions_. These include the following:  
      
            1. K-Nearest Neighbors (KNN) from scratch
            2. [Linear Regression](https://github.com/srikhetramohanty/Data-Science-Portfolio/blob/main/ML%20From%20Scratch/Supervised%20ML%20From%20Scratch/Generalised%20Linear%20Models%20(GLM)%20family/linear-regression-from-scratch.ipynb) (+Lasso +Ridge Regressions) from scratch
            3. Logistic Regression (with Stochastic Gradient Descent & Regularization) from scratch
            4. Decision Tree (~CART) for classification from scratch
            5. Bagging Ensemble for classification from scratch
            6. Random Forest ensemble for classification from scratch
            7. Stacking ensemble for classification from scratch
            8. Gradient Boosting Machine (GBMs) ensemble for regression from scratch
            9. Gradient Boosting Machine (GBMs) ensemble for classification from scratch
            
      3. **Unsupervised ML from scratch** - Manual implementation of popular classical ML algorithms used for data exploration & pattern finding exercises. _These have been benchmarked against the available Scikit-Learn or relevant versions_. These include the following:
      
            1. Principal Component Analysis (PCA) from scratch
            2. K-Means Clustering from scratch
            3. Density-Based Spatial Clustering of Applications with Noise (DBSCAN) from scratch
            
      4. **Artificial Neural Networks (ANN) from scratch** - Manual implementation of deep neural networks with dynamic hyper-parameters as offered in the tensorflow packages. _These have been benchmarked against the available Tensorflow, Keras or relevant versions_. These include the following:
      
            1. ANN with L-layers & SGD from scratch
            2. ANN with regularization & SGD from scratch
            3. ANN with regularization, SGD & Dropout from scratch
