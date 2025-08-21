# Astrostatistic and Machine Learning

N.B. The code for the exam must be upload in the directory "working" in your fork of "astrostatics_bicocca_2025"

## Lecture 1: Introduction                                     03/03/2025
Github installation and test

## Lecture 2: Probability and Statistic I                      10/03/2025
Introduction to probability  
Monty Hall Problem simulation

## Lecture 3: Probability and Statistic II                     13/03/2025
Monte Carlo integration  
Descriptive statistic  
Univariate distributions  
Introduction to scipy.stats

## Lecture 4: Probability and Statistic III                    17/03/2025
Central Limit Theorem  
Bivariate and Multivariate pdfs  
Correlation coefficients: Pearson, Spearman and Kendall  
Sampling from arbitrary distribution: Rejection Sampling and Inverse Transform Sampling

## Lecture 5: Frequentist Statistical Inference I              20/03/2025
Statistical Inference  
Frequentist vs. Bayesian Inference  
Maximum Likelihood Estimation (MLE)  
MLE applied to a Homoscedastic Gaussian  
Quantifying Estimate Uncertainty  
MLE applied to a Heteroscedastic Gaussian  
Non-Gaussian Likelihoods  

## Lecture 6: Frequentist Statistical Inference II             31/03/2025
Fitting a Line To Data  
Least Squares Fitting  
Modifyng the Likelihood: Huber loss function  
Goodness of Fit  
Model Comparison  
Confidence Estimating: Bootstrap and Jackknife  

## Lecture 7: Frequentist Statistical Inference III            03/04/2025
Hypothesis Testing: p-value  
False Positive and False Negative  
Comparing Distribution: Kolmogorov-Smirnov Test (KS Test)  
Nonparametric Modeling and Histrograms  
Kernel Density Estimation (KDE)  

## Lecture 8: Bayesian Statistical Inference I                 07/04/2025
Introduction to Bayesian Statistic  
Bayesian Statistical Inference  
Bayesian priors: the principle of indifference, invariance (or consistency) and maximum entropy  
Conjugate Priors  
Hierarchical Bayes  
Bayesian credible regions  
Nuisance Parameters and Marginarization  

## Lecture 9: Bayesian Statistical Inference II                07/04/2025
Underlying Gaussian distribution with heteroscedastic Gaussian uncertainties  
Gaussian distribution embedded in a uniform background distribution  
Bayesian Model Comparison  

## Lecture 10: Bayesian Statistical Inference III              08/04/2025
Monte Carlo Methods and Markov Chains Introduction  
Markov Chain Monte Carlo (MCMC) Techniques  
Metropolis-Hastings Algorithm  

## Lecture 11: Bayesian Statistical Inference IV               10/04/2025
Practical MCMC chain checks  
Computing autocorrelation times  
Optimizing sampling  
MCMC Parameter Estimation: emcee and PyMC  
MCMC with emcee  
MCMC with PyMC (optional)  
Gibbs Sampling  

## Lecture 12: Bayesian Statistical Inference V                14/04/2025
Pratical Evidence Evaluation and Model Selection  
Savage-Dickey Density Ratio  
Product-space Sampling  
Thermodynamic Integration  
Nested Sampling  
Dynesty  

## Lecture 13: Introduction to Data Mining & Machine Learning  24/04/2025
Categories of Machine Learning: Supervised and Unsupervised  
Scikit-Learn  
Representation of Data in Scikit-learn  
Basic Principles of Machine Learning  
The Scikit-learn Estimator Object  
Supervised Learning: Classification and Regression  
Unsupervised Learning: Dimensionality Reduction and Clustering  
Model Validation  
How to Choose your Estimator  

## Lecture 14: Clustering                                      28/04/2025
Determinate the optimal algorithm: K-fold cross validation  
Clustering  
K-Means Clustering  
Mean-shift Clustering  

## Lecture 15: Dimensional Reduction I                         05/05/2025
Curse of Dimensionality  
Principal Component Analysis (PCA)  
Preparing data for PCA  
Interpreting the PCA  
Missing Data  
Non-negative Matrix Factorization (NMF)  
Independent Component Analysis (ICA)  

## Lecture 16: Dimensional Reduction II                        12/05/2025
Non-linear Dimensional Reduction  
Local Linear Embedding (LLE)  
Isometric Mapping (IsoMap)  
t-distributed Stochastic Neighbor Embedding (t-SNE)  
Drawbacks of non-linear embeddings tecniques  
Recap: Density Estimation  
- Nonparametric Density Estimation: KDE, 2D KDE, Nearest-Neighbor Density Estimation  
- Parametric Density Estimation: Gaussian Mixture Models (GMM)  

Pills of modern research  

## Lecture 17: Regression I                                    15/05/2025
Regression = Fit  
2-D Linear Regression  
Homoscedastic uncertainty scenario  
Heteroscedastic uncertainty scenario  
A Word of Caution: always visualize your data  
Multivariate Linear Regression  
Polynomial Regression  
Basis Function Regression  
Kernel Regression  
Over/Under-fitting  
Cross-Validation  
Learning Curves  

## Lecture 18: Regression II                                   19/05/2025
Regularization  
Ridge Regression (or Tikhonov Regularization)  
Least Absolute Shrinkage and Selection (LASSO) Regularization  
Elastic Net and Deep Learning  
Non-linear Regression  
Gaussian Process Regression (GPR)  
Uncertainties All Round -- Total Least Squares (TLS)  

## Lecture 19: Classification I                                22/05/2025
Generative vs. Discriminative Classification  
Assessing your Results  
Comparing the Performance of Classifier  
Generative Classification  
Naive Bayes Classifier  
Gaussian Naive Bayes Classifier  
Linear & Quadratic Discriminant Analysis  
Gaussian Mixture Models (GMM) and Bayes Classification  
K-Nearest Neighbor Classifier  

## Lecture 20: Classification II                               26/05/2025
Discriminative Classification  
Logistic Regression  
Support Vector Machines  
Kernel Methods  
Decision Trees  
Decision Trees Splitting Criteria  
Ensemble Learning: Bagging and Random Forests  
Boosting  

## Lecture 21: Deep Learning I                                 27/05/2025
Loss Functions  
Gradient Descent  
AdaBoost  
Neural Network  
Backpropagation  
Computational Digrassion  
Number of Layers  
Number of Neurons  
Activation Functions  
Vanishing and Exploding Gradients  
Regularization  
Batch normalization  
Data Augmentation  
Faster Optimizzers  
Training, Validation and Test Set  
