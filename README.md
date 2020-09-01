# d0 May 3, 2020
setup complete. most of the code will be uploaded at [riyadhrazzaq/pywork](https://github.com/riyadhrazzaq/pywork.git) or at [kaggle/riyadhrazzaq](https://kaggle.com/riyadhrazzaq)

# d1 May 7, 2020
Read up on Decision Tree Regressor theory. 
https://www.saedsayad.com/decision_tree_reg.htm

# d2 May 8, 2020
Stuck in implementation of Decision Tree Regressor. will updated if completed.
# d3 May 10, 2020
Decision Tree Regressor Implementation. [SCRIPT](https://github.com/riyadhrazzaq/pywork/blob/master/scripts/mlfromscratch/DecisionTreeRegressor.py) [THEORY](https://www.saedsayad.com/decision_tree_reg.htm)
# d4 May 13, 2020
Decision Tree Classifier implementation. [[SCRIPT]](https://github.com/riyadhrazzaq/pywork/blob/master/scripts/mlfromscratch/DecisionTreeClassifier.py) [[theory]](https://www.saedsayad.com/decision_tree.htm)
# d5 May 15, 2020
SVM Theory [[theory]](https://cling.csd.uwo.ca/cs860/papers/SVM_Explained.pdf)
# d6 May 18, 2020
Quadratic Optimization for SVM, resources-
* https://courses.csail.mit.edu/6.867/wiki/images/a/a7/Qp-cvxopt.pdf
* https://scaron.info/blog/quadratic-programming-in-python.html
# d7 May 19, 2020
SVM Implementation(binary, linear kernel) [[theory]](https://cling.csd.uwo.ca/cs860/papers/SVM_Explained.pdf) [[SCRIPT]](https://github.com/riyadhrazzaq/pywork/blob/master/scripts/mlfromscratch/svm.py) 

Quadratic Programming code/format taken from https://pythonprogramming.net/soft-margin-kernel-cvxopt-svm-machine-learning-tutorial/ , they have credited http://mblondel.org/ for the original code. 
# d8 June 1, 2020
Netflix Dataset EDA
# d9 June 5, 2020
Netflix EDA Complete
# d10 June 6, 2020
Netflix Recommender. Cosine Similarity with Word Embedding, TfIdf.
# d11 June 7, 2020
Netflix titles analysis and recommender based on clustering. [[NOTEBOOK]](https://www.kaggle.com/riyadhrazzaq/netflix-eda-recommender)
# d12 June 8, 2020
Collaborative Filtering with SGD. [[THEORY]](https://developers.google.com/machine-learning/recommendation/collaborative/matrix)
# d13 June 9, 2020
Spent the whole day trying to fix CF w/ SGD implementation from scratch. I made a mistake in SGD. Will fix later in sha Allah. 
# d14 June 11, 2020
As I was stuck because of simple SGD implementation, I realized I need backward propagation for a minute. Here is Linear Regression

w/ Gradient Descent [[NOTEBOOK]](https://www.kaggle.com/riyadhrazzaq/gradient-descent-for-linear-regression?scriptVersionId=35945683)

w/ Stochastic Gradient Descent [[SCRIPT]](https://github.com/riyadhrazzaq/pywork/tree/master/scripts/mlfromscratch/linear_regression.py)
# d15 June 13, 2020
Non-negative Matrix Factorization w/ SGD. [[NOTEBOOK]](https://www.kaggle.com/riyadhrazzaq/collaborative-filtering-w-mf-from-scratch)
# d16 June 15, 2020
 Ridge Regression. [[SCRIPT]](https://github.com/riyadhrazzaq/pywork/blob/master/scripts/mlfromscratch/ridge_regression.py)
# d17 June 29, 2020
Lasso Regression [[NOTEBOOK]](https://www.kaggle.com/riyadhrazzaq/lasso-regression-scratch) This implementation is really buggy. But I did not understand the theory clearly to code further. Maybe later, in sha Allah.
# d18 July 1, 2020
Gaussian Naive Bayes [[NOTEBOOK]](https://www.kaggle.com/riyadhrazzaq/gaussian-naive-bayes-classifier/). Really proud of this implementation. Spent the whole day on Bayes Theorem, Normal Distribution. 3Blue1Brown's video on [Bayes Theorem](https://www.youtube.com/watch?v=HZGCoVF3YvM&t=467s) helped the most. Never seen such an intuitive video about probability. This is the first code in ML that I have written had the lowest number of bugs. 1, actually. Forgot to add `tmp+=1` inside function `def predict()` in class `GaussNB`
# d19 July 3, 2020
Multinomial Naive Bayes implementation. Can't fix a bug.
# d20 July 5, 2020
This gave a lot of trouble. Lesson learned- read the theory from multiple sources if possible, even after you understand it. Multinomial NB implementation complete. [[NOTEBOOk]](https://www.kaggle.com/riyadhrazzaq/multinomial-naive-bayes-from-scratch) with Spam Classification. [[SCRIPT]](https://github.com/riyadhrazzaq/scratched-ml/blob/master/mlfromscratch/multinomial_naive_bayes.py)
# d21 July 7, 2020
Logistic Regression theory from ISLR and ESL. Plan to read [this](http://www.stat.cmu.edu/~cshalizi/uADA/12/lectures/ch12.pdf) too. 
# d22 July 9, 2020
Logistic Regression from Scratch using Batch Gradient Descent. [[NOTEBOOK]](https://www.kaggle.com/riyadhrazzaq/logistic-regression-from-scratch)
# d23 July 11, 2020
Linear Algebra [[MITOPENCOURSEWARE]](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/assignments/). EDA. will post link if I work on it further.
# d24 July 13, 2020
ICU Prediction of COVID-19 Patients. [[NOTEBOOK]](https://www.kaggle.com/riyadhrazzaq/early-icu-prediction-w-basic-eda-roc-auc-0-90)
# d25 July 14, 2020
Linear Regression, *Python for Data Analysis* exercises on Pandas. 
# d26 July 25, 2020
Cross Validation. Notebook on DrivenData competition DengAI
# d27 July 26, 2020
Bagging, Random Forest, DengAI, Boosting(AdaBoost)
# d28 July 29, 2020
Best Subset Selection notebook partially done. Practiced few sections from Python for Data Analysis, Wes McKinney. 
# d29 July 31, 2020
Best Subset complete. [[NOTEBOOK]](https://www.kaggle.com/riyadhrazzaq/subset-selection)
# d30 Aug 3, 2020
Hyperparameter tuning with RandomSearchCV from scratch. [[NOTEBOOK]](https://www.kaggle.com/riyadhrazzaq/randomized-search-cv)
# d31 Aug 4, 2020
Handling Multiclass Classification with 1vsRest, 1vs1 from scratch. [[NOTEBOOK]](https://www.kaggle.com/riyadhrazzaq/handling-multiclass-classification)
# d32 Aug 6, 2020
House Price Revisited.
# d33 Aug 8, 2020
Hierarchical Clustering. Theory from ISLR book. Code partially done.
# d34 Aug 9, 2020
Hierarchical Clustering - Agglomerative approach, code complete for linkage types: single, complete.
# d31 Sept 1, 2020
Feature Preprocessing and feature generation review. Currently reading chapter 4 of ILA by Prof. G. Strang.
