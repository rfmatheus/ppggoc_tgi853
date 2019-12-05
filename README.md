# 2019_2 - TÓPICOS ESP. EM GESTÃO E TECNOLOGIA II - A

*Disciplina:* Representação Distribuída de Textos e Modelagem de Tópicos (2019/2) 
*Universidade/Escola/Programa:* UFMG/ECI/PPGGOC (doutorado) 

*Prof.:* Renato Rocha 
*Aluno:* Renato Fabiano Matheus 

## AVISO
Repositório criado a partir da clonagem do repositório [rsouza/FGV_Intro_DS em github](https://github.com/rsouza/FGV_Intro_DS). \n
O conteúdo original deste documento está ao final do mesmo a partir do texto ("CONTEÚDO ORIGINAL"). 

## ATIVIDADES E AVALIAÇÃO DA DISCIPLINA TGI853 

1) Criação do repositório no GitHub (5 pt)

RESPOSTA: criado repositório [rfmatheus/ppggoc_tgi853](https://github.com/rfmatheus/ppggoc_tgi853) a partir do conteúdo clonado de rsouza/FGV_Intro_DS.

2) Preparação do notebook de processamento de textos e modelagem de tópicos com corpus próprio a ser escolhido (e tratado), tendo como exemplo [ML_UNSUP_TopicModeling_Clustering.ipynb em rsouza](https://github.com/rsouza/FGV_Intro_DS/blob/master/notebooks/ML_UNSUP_TopicModeling_Clustering.ipynb) e [ML_UNSUP_Word2Vec_Example.ipynb em rsouza](https://github.com/rsouza/FGV_Intro_DS/blob/master/notebooks/ML_UNSUP_Word2Vec_Example.ipynb) (35 pt)

RESPOSTA: 
+ [ML_UNSUP_Word2Vec_Example.ipynb em rfmatheus](https://github.com/rfmatheus/ppggoc_tgi853/blob/master/notebooks/ML_UNSUP_Word2Vec_Example.ipynb) 

+ [ML_UNSUP_TopicModeling_Clustering.ipynb em rfmatheus](https://github.com/rfmatheus/ppggoc_tgi853/blob/master/notebooks/ML_UNSUP_TopicModeling_Clustering.ipynb)

3) Projeto final de word embeddings com o corpus escolhido segundo este notebook (https://github.com/rsouza/FGV_Intro_DS/blob/master/notebooks/ML_UNSUP_Word2Vec_Example.ipynb) (50 pt)

RESPOSTA: 

4) Resenha de auto-avaliação e avaliação da disciplina (10 pt)

RESPOSTA: 

# CONTEÚDO ORIGINAL DO DOCUMENTO EM https://github.com/rsouza/FGV_Intro_DS

# FGV_Intro_DS
Introduction to Data Science @ FGV

Instructor: [Renato Rocha Souza](http://emap.fgv.br/corpo-docente/renato-rocha-souza)

This is the repository of code for the "Introduction to Data Science"

This class is about the Data Science process, in which we seek to gain useful predictions and insights from data.
Through real-world examples and code snippets, we introduce methods for:

+ data munging, scraping, sampling andcleaning in order to get an informative, manageable data set;
+ data storage and management in order to be able to access data (even if big data);
+ exploratory data analysis (EDA) to generate hypotheses and intuition about the data;
+ prediction based on statistical learning tools;
+ communication of results through visualization, stories, and interpretable summaries

Detailed Syllabus:

+ Propaedeutic [ref1](https://medium.com/technomancy/the-math-required-for-machine-learning-af0d90db3903), [ref2](https://medium.com/technomancy/the-blunt-guide-to-mathematically-rigorous-machine-learning-c53263d45c7b), [ref3](https://towardsdatascience.com/how-much-maths-does-an-it-engineer-need-to-learn-to-get-into-data-science-machine-learning-7d6a42f79516), [ref4](https://towardsdatascience.com/essential-math-for-data-science-why-and-how-e88271367fbd), [ref5](https://becominghuman.ai/a-short-machine-learning-explanation-in-terms-of-linear-algebra-probability-and-calculus-f7660aa4b06c), [ref6](https://www.analyticsvidhya.com/blog/2019/10/mathematics-behind-machine-learning/)  
+ Related Courses [cs109](https://github.com/cs109/a-2017), [cs229](http://cs229.stanford.edu/), [ML Andrew Ng](https://www.coursera.org/learn/machine-learning)
+ Data Science Concepts [ref1](https://towardsdatascience.com/the-what-where-and-how-of-data-science-6dda1af98671), [ref2](https://docs.google.com/presentation/d/1ysQroWAcUJBizt00v7q-Ss1lalJlojZBlRInLQTDJV8/), [ref3](https://towardsdatascience.com/data-science-for-startups-introduction-80d022a18aec), [ref4](https://medium.com/trainingcenter/data-science-um-panorama-geral-87edbbd35885), [book1](http://www.datascienceassn.org/sites/default/files/Foundations%20of%20Data%20Science%20-%20Textbook.pdf), [book2](http://proquest.safaribooksonline.com/book/databases/9781449363871), [book3](https://www.amazon.com/Applied-Predictive-Analytics-Principles-Professional/dp/1118727967)
  + Data Scientists [ref1](https://towardsdatascience.com/data-scientist-from-good-to-great-5e6aed447b69), [re2](https://towardsdatascience.com/data-scientist-from-good-to-great-part-2-614f1ed2aaeb), [ref3](https://towardsdatascience.com/whats-the-secret-sauce-to-transforming-into-a-unicorn-in-data-science-94082b01c39d), [learning path](https://trainings.analyticsvidhya.com/courses/course-v1:AnalyticsVidhya+Python-Final-Jan-Feb+Python-Session-1/about)
  + Statistics [book1](http://www-bcf.usc.edu/~gareth/ISL/), [book2](http://greenteapress.com/thinkstats2/html/index.html), [ref1](https://towardsdatascience.com/introduction-to-statistics-e9d72d818745), [ref2](https://towardsdatascience.com/inferential-statistics-basics-294512909a33), [ref3](https://medium.com/cracking-the-data-science-interview/the-10-statistical-techniques-data-scientists-need-to-master-1ef6dbd531f7), [ref4](https://towardsdatascience.com/applying-statistics-in-python-part-i-6ea73363b571)  
  + AI [ref1](https://www.datasciencecentral.com/profiles/blogs/difference-between-machine-learning-data-science-ai-deep-learning)
    + AI and Game Theory [ref1](https://www.analyticsvidhya.com/blog/2019/11/game-theory-ai/)
  + Machine Learning [ref1](https://medium.com/@lizzie_turner/lets-talk-about-machine-learning-ddca914e9dd1), [ref2](https://medium.com/@ageitgey/machine-learning-is-fun-80ea3ec3c471), [book](https://cs.nyu.edu/~mohri/mlbook/)  
  + Business Intelligence [ref1](https://en.wikipedia.org/wiki/Business_intelligence)
+ Data Science Process [ref1](https://towardsdatascience.com/a-complete-machine-learning-walk-through-in-python-part-one-c62152f39420), [ref2](https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining)  
  + Data Formats [ref1](https://en.wikipedia.org/wiki/Comparison_of_data_serialization_formats)
  + Data Acquisition [ref1](http://metah.ch/blog/2014/09/introduction-to-machine-learning-from-data-acquisition-to-a-production-service-2/)  
  + Data Engineering [ref1](https://medium.freecodecamp.org/the-rise-of-the-data-engineer-91be18f1e603), [ref2](https://medium.com/@rchang/a-beginners-guide-to-data-engineering-part-i-4227c5c457d7), [ref3](https://becominghuman.ai/effective-data-preprocessing-and-feature-engineering-452d3a948262)  
    + Handling Missing Values [ref1](http://www.ritchieng.com/pandas-handling-missing-values/)
    + Changing Datatypes [ref1](http://www.ritchieng.com/pandas-changing-datatype/)
  + Exploratory Data Analysis [ref1](http://people.duke.edu/~ccc14/sta-663-2017/#), [book](oreilly.com/catalog/9780596802363/)  
  + Data Visualization [ref1](https://towardsdatascience.com/5-quick-and-easy-data-visualizations-in-python-with-code-a2284bae952f), [ref2](https://www.linuxlinks.com/best-free-python-visualization-packages/)  
  
+ Model Selection [ref1](https://towardsdatascience.com/data-science-simplified-part-6-model-selection-methods-2511cbdf7cb0)
  + Feature Engineering [ref1](https://machinelearningmastery.com/discover-feature-engineering-how-to-engineer-features-and-how-to-get-good-at-it/), [ref2](https://towardsdatascience.com/using-machine-learning-algorithms-d47711ff4732), [book](http://www.feat.engineering/index.html)  
    + Automated Feature Engineering  
      [featuretools](https://www.featuretools.com/)
  + Feature Selection [ref1](https://towardsdatascience.com/the-5-feature-selection-algorithms-every-data-scientist-need-to-know-3a6b566efd2), [ref2](http://scikit-learn.org/stable/modules/feature_selection.html), [ref3](https://towardsdatascience.com/feature-selection-with-pandas-e3690ad8504b)  
    + Numeric Data [ref1](https://towardsdatascience.com/understanding-feature-engineering-part-1-continuous-numeric-data-da4e47099a7b)
    + Discrete/Categorical Data [ref1](https://towardsdatascience.com/understanding-feature-engineering-part-2-categorical-data-f54324193e63)
    + Textual Data [ref1](https://towardsdatascience.com/understanding-feature-engineering-part-3-traditional-methods-for-text-data-f6f7d70acd41), [ref2](https://towardsdatascience.com/understanding-feature-engineering-part-4-deep-learning-methods-for-text-data-96c44370bbfa)
  + Hiperparameter Search [ref1](https://towardsdatascience.com/automated-machine-learning-hyperparameter-tuning-in-python-dfda59b72f8a)
  + Cross Validation [ref1](https://www.analyticsvidhya.com/blog/2018/05/improve-model-performance-cross-validation-in-python-r/), [video1](https://www.coursera.org/learn/deep-neural-network/lecture/cxG1s/train-dev-test-sets)
  + Oversampling and Undersampling [ref1](https://www.cs.cmu.edu/afs/cs/project/jair/pub/volume16/chawla02a-html/)
  + Regularization [ref1](https://towardsdatascience.com/regularization-in-machine-learning-76441ddcf99a), [ref2](https://www.analyticsvidhya.com/blog/2015/02/avoid-over-fitting-regularization/)https://towardsdatascience.com/illustrated-10-cnn-architectures-95d78ace614d
  + Bias and Variance [ref1](https://towardsdatascience.com/balancing-bias-and-variance-to-control-errors-in-machine-learning-16ced95724db)
  + Overfitting and Underfitting [ref1](https://towardsdatascience.com/overfitting-vs-underfitting-a-conceptual-explanation-d94ee20ca7f9)
  + Evaluation Metrics [ref1](https://towardsdatascience.com/choosing-the-right-metric-for-machine-learning-models-part-1-a99d7d7414e4), [ref2](https://towardsdatascience.com/choosing-the-right-metric-for-evaluating-machine-learning-models-part-2-86d5649a5428), [ref3](https://www.analyticsvidhya.com/blog/2019/08/11-important-model-evaluation-error-metrics/)  

+ Machine Learning Algorithms [ref1](http://cdn.intechopen.com/pdfs-wm/10694.pdf), [ref2](https://machinelearningmastery.com/a-tour-of-machine-learning-algorithms/), [ref3](https://towardsdatascience.com/a-tour-of-the-top-10-algorithms-for-machine-learning-newbies-dde4edffae11), [ref4](https://www.analyticsvidhya.com/blog/2017/09/common-machine-learning-algorithms/), [ref5](https://blogs.sas.com/content/subconsciousmusings/2017/04/12/machine-learning-algorithm-use/), [ref6](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)
  + Unsupervised [ref1](https://towardsdatascience.com/unsupervised-learning-with-python-173c51dc7f03)
    + Dimensionality reduction [ref1](https://towardsdatascience.com/reducing-dimensionality-from-dimensionality-reduction-techniques-f658aec24dfe)
      + PCA [ref1](https://towardsdatascience.com/pca-using-python-scikit-learn-e653f8989e60)
      + SVD [ref1](https://machinelearningmastery.com/singular-value-decomposition-for-machine-learning/)
      + t-SNE [ref1](https://towardsdatascience.com/checking-out-dimensionality-reduction-with-t-sne-78309b2ca67d)
    + Clustering [ref1](https://www.analyticsvidhya.com/blog/2016/11/an-introduction-to-clustering-and-different-methods-of-clustering/), [ref2](https://dataaspirant.com/2016/09/24/classification-clustering-alogrithms/), [ref3](https://www.analyticsvidhya.com/blog/2013/11/getting-clustering-right/), [ref4](https://towardsdatascience.com/cluster-analysis-create-visualize-and-interpret-customer-segments-474e55d00ebb), [ref5](https://medium.com/@b.terryjack/unsupervised-learning-to-aid-labelling-for-supervised-learning-253fe2d8e06b),[ref6](https://www.analyticsvidhya.com/blog/2019/05/beginners-guide-hierarchical-clustering/)   
      + K-Means [ref1](https://towardsdatascience.com/clustering-using-k-means-algorithm-81da00f156f6)  
      + Hierarchical Clustering [ref1](https://towardsdatascience.com/clustering-unsupervised-learning-788b215b074b)  
      + K-Modes [ref1](https://github.com/nicodv/kmodes)  
    + Topic Modeling [ref1](https://medium.com/mlreview/topic-modeling-with-scikit-learn-e80d33668730), [ref2](https://datascienceplus.com/evaluation-of-topic-modeling-topic-coherence/), [ref3](https://towardsdatascience.com/topic-modeling-and-latent-dirichlet-allocation-in-python-9bf156893c24), [ref4](https://towardsdatascience.com/topic-modelling-in-python-with-nltk-and-gensim-4ef03213cd21)  
      + LDA [ref1](https://towardsdatascience.com/light-on-math-machine-learning-intuitive-guide-to-latent-dirichlet-allocation-437c81220158), [ref2](https://medium.com/nanonets/topic-modeling-with-lsa-psla-lda-and-lda2vec-555ff65b0b05)  
    + Unsupervised Deep Learning [ref1](https://www.analyticsvidhya.com/blog/2018/05/essentials-of-deep-learning-trudging-into-unsupervised-deep-learning/)  
  + Supervised
    + Regression [ref1](https://www.analyticsvidhya.com/blog/2015/10/regression-python-beginners/), [ref2](https://towardsdatascience.com/my-journey-into-machine-learning-class-5-regression-cb6f04006b29), [ref3](https://towardsdatascience.com/5-types-of-regression-and-their-properties-c5e1fa12d55e), [ref4](https://www.analyticsvidhya.com/blog/2015/08/comprehensive-guide-regression/), [ref5](https://towardsdatascience.com/selecting-the-best-machine-learning-algorithm-for-your-regression-problem-20c330bad4ef)  
    + Classification [ref1](https://towardsdatascience.com/machine-learning-classifiers-a5cc4e1b0623), [ref2](https://medium.com/@sifium/machine-learning-types-of-classification-9497bd4f2e14), [ref3](https://www.analyticsvidhya.com/blog/2018/04/a-comprehensive-guide-to-understand-and-implement-text-classification-in-python/), [ref3](https://towardsdatascience.com/building-a-deployable-ml-classifier-in-python-46ba55e1d720)
    + Linear Models [ref1](https://towardsdatascience.com/generalized-linear-models-8738ae0fb97d)
      + Linear Regression [ref1](https://www.analyticsvidhya.com/blog/2017/06/a-comprehensive-guide-for-linear-ridge-and-lasso-regression/)
        + Polynomial Regression [ref1](https://towardsdatascience.com/machine-learning-with-python-easy-and-robust-method-to-fit-nonlinear-data-19e8a1ddbd49) [ref2](http://scikit-learn.org/stable/modules/linear_model.html#polynomial-regression-extending-linear-models-with-basis-functions)
        + Stepwise Regression [ref1](https://planspace.org/20150423-forward_selection_with_statsmodels/)
        + Ridge Regression [ref1](https://www.analyticsvidhya.com/blog/2017/06/a-comprehensive-guide-for-linear-ridge-and-lasso-regression/), [ref2](https://towardsdatascience.com/ridge-and-lasso-regression-a-complete-guide-with-python-scikit-learn-e20e34bcbf0b)  
        + Lasso Regression [ref1](https://www.analyticsvidhya.com/blog/2017/06/a-comprehensive-guide-for-linear-ridge-and-lasso-regression/), [package](http://scikit-learn.org/stable/modules/linear_model.html#lasso)
        + ElasticNet Regression [ref1](https://towardsdatascience.com/5-types-of-regression-and-their-properties-c5e1fa12d55e)  
      + Logistic Regression (Categorical) [ref1](https://en.wikipedia.org/wiki/Logistic_regression), [ref2](https://towardsdatascience.com/building-a-logistic-regression-in-python-step-by-step-becd4d56c9c8),  [ref3](https://www.analyticsvidhya.com/blog/2015/11/beginners-guide-on-logistic-regression-in-r), [ref4](https://towardsdatascience.com/support-vector-machine-vs-logistic-regression-94cc2975433f)  

      + Support Vector Machines [ref1](https://towardsdatascience.com/i-support-vector-machines-and-so-should-you-7af122b6748), [ref2](https://towardsdatascience.com/support-vector-machine-introduction-to-machine-learning-algorithms-934a444fca47), [ref3](https://www.analyticsvidhya.com/blog/2017/09/understaing-support-vector-machine-example-code/), [ref4](https://towardsdatascience.com/svm-feature-selection-and-kernels-840781cc1a6c), [paper](http://users.ecs.soton.ac.uk/srg/publications/pdf/SVM.pdf), [video](https://www.youtube.com/watch?v=_PwhiWxHK8o)  
        + SVR [ref1](http://kernelsvm.tripod.com/), [ref2](https://alex.smola.org/papers/2003/SmoSch03b.pdf)    
        + SVC [ref1](http://www.robots.ox.ac.uk/~az/lectures/ml/lect2.pdf), [ref2](https://www.sciencedirect.com/science/article/pii/S0925231203003758)  
      + Passive-Aggressive [ref1](https://www.bonaccorso.eu/2017/10/06/ml-algorithms-addendum-passive-aggressive-algorithms/)
      + Perceptron [ref1](https://towardsdatascience.com/what-the-hell-is-perceptron-626217814f53), [ref2](https://towardsdatascience.com/from-biology-to-ai-the-perceptron-81abfdc788bf)  
    + Bayesian Models
      + Naive Bayes [ref1](https://www.analyticsvidhya.com/blog/2017/09/naive-bayes-explained/)
      + Gaussian Naive Bayes [ref1](http://i.stanford.edu/pub/cstr/reports/cs/tr/79/773/CS-TR-79-773.pdf)
      + Bernoulli Naive Bayes [ref1](http://mattshomepage.com/articles/2016/Jun/07/bernoulli_nb/)
    + Guassian Mixtures [ref1](http://katbailey.github.io/post/gaussian-processes-for-dummies/) [package](http://scikit-learn.org/stable/modules/classes.html#module-sklearn.gaussian_process)
    + k Nearest Neighbors (kNN) [ref1](http://stackabuse.com/k-nearest-neighbors-algorithm-in-python-and-scikit-learn/)
    + Decision Tree [ref1](https://towardsdatascience.com/random-forest-mystery-revealed-69ca18b82ff5), [ref2](https://www.analyticsvidhya.com/blog/2016/04/complete-tutorial-tree-based-modeling-scratch-in-python/)
    + Ensemble Models [ref1](https://en.wikipedia.org/wiki/Ensemble_learning), [ref2](https://www.analyticsvidhya.com/blog/2015/08/introduction-ensemble-learning/) [ref3](https://www.analyticsvidhya.com/blog/2015/09/questions-ensemble-modeling/), [package](http://scikit-learn.org/stable/modules/ensemble.html)
      + Bagging [ref1](https://machinelearningmastery.com/bagging-and-random-forest-ensemble-algorithms-for-machine-learning/)  
        + Random Forest [ref1](https://www.analyticsvidhya.com/blog/2014/06/introduction-random-forest-simplified/)   
        + Extremely Randomized Trees [ref1](https://orbi.uliege.be/bitstream/2268/9357/1/geurts-mlj-advance.pdf)
        + Bagging Classifier [ref1](https://www.cs.cmu.edu/afs/cs/project/jair/pub/volume11/opitz99a-html/node3.html), [package](http://scikit-learn.org/stable/modules/generated/sklearn.ensemble.BaggingClassifier.html)
      + Boosting [ref1](https://en.wikipedia.org/wiki/Boosting_(machine_learning))
        + Adaboost [ref1](https://towardsdatascience.com/boosting-algorithm-adaboost-b6737a9ee60c)
        + GBM [ref1](https://towardsdatascience.com/boosting-algorithm-gbm-97737c63daa3)
        + XGBoost [ref1](https://towardsdatascience.com/boosting-algorithm-xgboost-4d9ec0207d), [ref2](https://www.analyticsvidhya.com/blog/2018/09/an-end-to-end-guide-to-understand-the-math-behind-xgboost/), [package](https://github.com/dmlc/xgboost)  
        + LightGBM [ref1](https://towardsdatascience.com/a-case-for-lightgbm-2d05a53c589c)
        + CatBoost [ref1](https://towardsdatascience.com/catboost-vs-light-gbm-vs-xgboost-5f93620723db)
        + Regularized Greedy Forests [ref1](https://www.analyticsvidhya.com/blog/2018/02/introductory-guide-regularized-greedy-forests-rgf-python/), [package](https://github.com/fukatani/rgf_python)
      + Stacking [ref1](http://blog.kaggle.com/2016/12/27/a-kagglers-guide-to-model-stacking-in-practice/)
      + Voting [ref1](https://towardsdatascience.com/ensemble-learning-in-machine-learning-getting-started-4ed85eb38e00)

    + Genetic Algorithms [ref1](https://www.analyticsvidhya.com/blog/2017/07/introduction-to-genetic-algorithm/), [ref2](https://towardsdatascience.com/evolution-of-a-salesman-a-complete-genetic-algorithm-tutorial-for-python-6fe5d2b3ca35), [ref3](https://towardsdatascience.com/genetic-algorithm-implementation-in-python-5ab67bb124a6)  
        + [TPOT](https://github.com/EpistasisLab/tpot),
        + [Auto SKLearn](https://github.com/automl/auto-sklearn)  
        + [Auto Keras](https://towardsdatascience.com/autokeras-the-killer-of-googles-automl-9e84c552a319)
        + [AutoML](https://towardsdatascience.com/everything-you-need-to-know-about-automl-and-neural-architecture-search-8db1863682bf)  

    + Neural Networks and Deep Learning [ref1](http://neuralnetworksanddeeplearning.com/chap1.html), [ref2](https://towardsdatascience.com/neural-network-architectures-156e5bad51ba), [ref3](https://medium.com/intuitive-deep-learning/intuitive-deep-learning-part-1a-introduction-to-neural-networks-d7b16ebf6b99), [ref4](https://towardsdatascience.com/a-weird-introduction-to-deep-learning-7828803693b0),  [ref5](https://ujjwalkarn.me/2016/08/09/quick-intro-neural-networks/), [ref6](https://www.analyticsvidhya.com/blog/2018/05/deep-learning-faq/), [ref7](https://www.kdnuggets.com/2018/02/8-neural-network-architectures-machine-learning-researchers-need-learn.html), [ref8](https://towardsdatascience.com/newbies-guide-to-deep-learning-6bf601c5a98e), [ref9](https://towardsdatascience.com/understanding-neural-networks-19020b758230), [ref10](https://towardsdatascience.com/understanding-neural-networks-what-how-and-why-18ec703ebd31), [simple implementation](https://towardsdatascience.com/lets-code-a-neural-network-in-plain-numpy-ae7e74410795), [book](http://www.deeplearningbook.org/contents/TOC.html), [viz](https://towardsdatascience.com/activation-maps-for-deep-learning-models-in-a-few-lines-of-code-ed9ced1e8d21), [video](https://www.youtube.com/watch?v=aircAruvnKk&t=0s&index=1&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi), [meme](https://indico.io/blog/wp-content/uploads/2016/02/inception_meme.jpg)
    + Neural Network concepts
        + [General Math](https://towardsdatascience.com/https-medium-com-piotr-skalski92-deep-dive-into-deep-networks-math-17660bc376ba)
        + [Linear](https://medium.com/datathings/linear-layers-explained-in-a-simple-way-2319a9c2d1aa) and [dense](https://medium.com/datathings/dense-layers-explained-in-a-simple-way-62fe1db0ed75) layers  
        + Weight Initialization [ref1](https://towardsdatascience.com/deep-learning-best-practices-1-weight-initialization-14e5c0295b94), [ref2](https://towardsdatascience.com/random-initialization-for-neural-networks-a-thing-of-the-past-bfcdd806bf9e)
        + Weight Averaging [ref1](https://towardsdatascience.com/stochastic-weight-averaging-a-new-way-to-get-state-of-the-art-results-in-deep-learning-c639ccf36a)
        + Hyperparameter Tuning [ref1](https://www.analyticsvidhya.com/blog/2018/11/neural-networks-hyperparameter-tuning-regularization-deeplearning/), [ref2](https://towardsdatascience.com/hyper-parameters-in-action-a524bf5bf1c)  
        + Gradient Descent [ref1](https://towardsdatascience.com/gradient-descent-algorithm-and-its-variants-10f652806a3), [ref2](https://towardsdatascience.com/learning-parameters-part-5-65a2f3583f7d), [video](https://www.youtube.com/watch?v=IHZwWFHWa-w&t=0s&index=2&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)
        + Backpropagation [ref1](https://www.youtube.com/watch?v=Ilg3gGewQ5U&t=0s&index=3&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)  
        + Loss Functions [ref1](https://medium.com/deep-learning-demystified/loss-functions-explained-3098e8ff2b27)  
      + Convolutional Neural Networks [ref1](https://towardsdatascience.com/intuitively-understanding-convolutions-for-deep-learning-1f6f42faee1), [ref2](https://towardsdatascience.com/light-on-math-machine-learning-intuitive-guide-to-convolution-neural-networks-e3f054dd5daa), [ref3](https://adeshpande3.github.io/A-Beginner%27s-Guide-To-Understanding-Convolutional-Neural-Networks/), [ref4](https://towardsdatascience.com/gentle-dive-into-math-behind-convolutional-neural-networks-79a07dd44cf9), [ref5](https://www.saama.com/blog/different-kinds-convolutional-filters/), [ref6](https://software.intel.com/en-us/articles/hands-on-ai-part-16-modern-deep-neural-network-architectures-for-image-classification), [ref6](https://towardsdatascience.com/convolutional-neural-networks-the-biologically-inspired-model-f2d23a301f71), [ref7](https://medium.com/analytics-vidhya/deep-learning-methods-1700548a3093), [ref8](https://towardsdatascience.com/advanced-topics-in-deep-convolutional-neural-networks-71ef1190522d), [viz](https://towardsdatascience.com/understanding-your-convolution-network-with-visualizations-a4883441533b), [architectures](https://towardsdatascience.com/illustrated-10-cnn-architectures-95d78ace614d)  
        + CNNs for NLP [ref1](http://www.wildml.com/2015/11/understanding-convolutional-neural-networks-for-nlp/), [ref2](https://towardsdatascience.com/deep-learning-for-nlp-anns-rnns-and-lstms-explained-95866c1db2e4) 
        + CNNs for object detection [ref1](https://towardsdatascience.com/evolution-of-object-detection-and-localization-algorithms-e241021d8bad)  
        + CNNs for Time Series [ref1](https://blog.goodaudience.com/introduction-to-1d-convolutional-neural-networks-in-keras-for-time-sequences-3a7ff801a2cf)    
        + Capsule Networks [ref1](https://medium.com/ai%C2%B3-theory-practice-business/understanding-hintons-capsule-networks-part-i-intuition-b4b559d1159b)  
      + RNNs (Sequence Models) [ref1](http://www.wildml.com/2015/09/recurrent-neural-networks-tutorial-part-1-introduction-to-rnns/)  
        + Attention Models [ref1](https://towardsdatascience.com/breaking-bert-down-430461f60efb)  
        + LSTMs and GRUs [ref1](https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21), [ref2](https://towardsdatascience.com/what-is-a-recurrent-nns-and-gated-recurrent-unit-grus-ea71d2a05a69), [ref3](https://towardsdatascience.com/forward-and-backpropagation-in-grus-derived-deep-learning-5764f374f3f5), [ref4](https://towardsdatascience.com/understanding-gru-networks-2ef37df6c9be), [ref5](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)  
        + Word Embeedings [ref1](https://towardsdatascience.com/introduction-to-word-embeddings-4cf857b12edc), [ref2](https://towardsdatascience.com/introduction-to-word-embedding-and-word2vec-652d0c2060fa)  
          + Word2vec [ref1](https://towardsdatascience.com/using-word2vec-for-better-embeddings-of-categorical-features-de75020e1233), [ref2](https://towardsdatascience.com/light-on-math-machine-learning-intuitive-guide-to-understanding-word2vec-e0128a460f0f), [ref3](https://www.analyticsvidhya.com/blog/2017/06/word-embeddings-count-word2veec/), [en-us trained models](http://ahogrammer.com/2017/01/20/the-list-of-pretrained-word-embeddings/), [ref4](https://towardsdatascience.com/an-implementation-guide-to-word2vec-using-numpy-and-google-sheets-13445eebd281), [pt-br trained models](http://www.nilc.icmc.usp.br/nilc/index.php/repositorio-de-word-embeddings-do-nilc), [ge-de trained models](https://deepset.ai/german-word-embeddings)  
          + Doc2vec [ref1](https://medium.com/scaleabout/a-gentle-introduction-to-doc2vec-db3e8c0cce5e)  
          + Char2vec [ref1](https://hackernoon.com/chars2vec-character-based-language-model-for-handling-real-world-texts-with-spelling-errors-and-a3e4053a147d)  
          + Glove [ref1](https://towardsdatascience.com/light-on-math-ml-intuitive-guide-to-understanding-glove-embeddings-b13b4f19c010)  
        + BERT [ref1](https://towardsdatascience.com/bert-for-dummies-step-by-step-tutorial-fb90890ffe03), [ref2](https://medium.com/swlh/a-simple-guide-on-using-bert-for-text-classification-bbf041ac8d04), [ref3](https://www.analyticsvidhya.com/blog/2019/09/demystifying-bert-groundbreaking-nlp-framework/), [ref4](https://towardsdatascience.com/bert-explained-state-of-the-art-language-model-for-nlp-f8b21a9b6270), [ref5](https://medium.com/sciforce/googles-bert-changing-the-nlp-landscape-5f4a7bf65cc5)  
        + XLNet [ref1](https://towardsdatascience.com/what-is-xlnet-and-why-it-outperforms-bert-8d8fce710335)   
      + Reinforcement Learning [ref1](https://towardsdatascience.com/introduction-to-various-reinforcement-learning-algorithms-i-q-learning-sarsa-dqn-ddpg-72a5e0cb6287), [ref2](https://towardsdatascience.com/introduction-to-various-reinforcement-learning-algorithms-part-ii-trpo-ppo-87f2c5919bb9), [ref3](https://towardsdatascience.com/reinforcement-learning-demystified-36c39c11ec14), [ref4](https://towardsdatascience.com/reinforcement-learning-demystified-markov-decision-processes-part-1-bf00dda41690), [ref5](https://blog.insightdatascience.com/reinforcement-learning-from-scratch-819b65f074d8), [ref6](https://towardsdatascience.com/reinforcement-learning-with-python-8ef0242a2fa2), [programming resource](https://gym.openai.com/docs/)  
      + Transfer Learning [ref1](https://towardsdatascience.com/a-comprehensive-hands-on-guide-to-transfer-learning-with-real-world-applications-in-deep-learning-212bf3b2f27a), [ref2](https://towardsdatascience.com/transfer-learning-from-pre-trained-models-f2393f124751), [ref3](https://towardsdatascience.com/style-up-your-photos-with-a-touch-of-deep-learning-magic-60a003c676f9), [ref4](https://towardsdatascience.com/transfer-learning-and-image-classification-using-keras-on-kaggle-kernels-c76d3b030649), [ref5](https://towardsdatascience.com/advanced-topics-in-neural-networks-f27fbcc638ae)  
      + Autoencoders [ref1](https://medium.com/intuitive-deep-learning/autoencoders-neural-networks-for-unsupervised-learning-83af5f092f0b), [ref2](https://towardsdatascience.com/a-high-level-guide-to-autoencoders-b103ccd45924), [ref3](https://towardsdatascience.com/auto-encoder-what-is-it-and-what-is-it-used-for-part-1-3e5c6f017726), [ref4](https://towardsdatascience.com/everything-you-need-to-know-about-autoencoders-in-tensorflow-b6a63e8255f0)  
         + Generative Adversarial Networks [ref1](https://www.analyticsvidhya.com/blog/2017/06/introductory-generative-adversarial-networks-gans/), [ref2](https://towardsdatascience.com/an-easy-introduction-to-generative-adversarial-networks-6f8498dc4bcd), [ref3](https://towardsdatascience.com/gan-by-example-using-keras-on-tensorflow-backend-1a6d515a60d0), [ref4](https://medium.com/@mattiaspinelli/simple-generative-adversarial-network-gans-with-keras-1fe578e44a87)  

+ Data Science Tasks
  + Time Series Analysis [ref1](https://www.analyticsvidhya.com/blog/2016/02/time-series-forecasting-codes-python/), [ref2](https://www.analyticsvidhya.com/blog/2015/12/complete-tutorial-time-series-modeling/), [ref3](http://www.blackarbs.com/blog/time-series-analysis-in-python-linear-models-to-garch/11/1/2016), [ref4](https://machinelearningmastery.com/how-to-use-the-timeseriesgenerator-for-time-series-forecasting-in-keras/), [video](https://www.youtube.com/watch?v=e8Yw4alG16Q)  
  + NLP and Text Mining [ref1](https://towardsdatascience.com/lessons-learned-from-applying-deep-learning-for-nlp-without-big-data-d470db4f27bf), [ref2](https://medium.com/@datamonsters/text-preprocessing-in-python-steps-tools-and-examples-bf025f872908), [ref3](https://medium.com/towards-artificial-intelligence/text-mining-in-python-steps-and-examples-78b3f8fd913b)   
  + Information Retrieval [ref1](https://towardsdatascience.com/https-towardsdatascience-com-search-engines-and-neural-networks-97e0df4f088d), [ref2](https://towardsdatascience.com/building-a-search-engine-with-bert-and-tensorflow-c6fdc0186c8a)  
  + Graphs and Network Analysis  
  + Sentiment Analysis [ref1](https://towardsdatascience.com/another-twitter-sentiment-analysis-bb5b01ebad90), [ref2](https://towardsdatascience.com/another-twitter-sentiment-analysis-with-python-part-2-333514854913), [ref3](https://towardsdatascience.com/another-twitter-sentiment-analysis-with-python-part-3-zipfs-law-data-visualisation-fc9eadda71e7), [ref4](https://towardsdatascience.com/another-twitter-sentiment-analysis-with-python-part-4-count-vectorizer-b3f4944e51b5), [ref5](https://towardsdatascience.com/another-twitter-sentiment-analysis-with-python-part-5-50b4e87d9bdd), [ref6](https://towardsdatascience.com/basic-data-cleaning-engineering-session-twitter-sentiment-data-95e5bd2869ec), [ref7](https://towardsdatascience.com/a-beginners-guide-on-sentiment-analysis-with-rnn-9e100627c02e)
  + Recommender Systems [ref1](https://www.analyticsvidhya.com/blog/2018/06/comprehensive-guide-recommendation-engine-python/), [ref2](https://www.datacamp.com/community/tutorials/recommender-systems-python), [ref3](https://www.analyticsvidhya.com/blog/2016/06/quick-guide-build-recommendation-engine-python/), [ref4](https://towardsdatascience.com/introduction-to-recommender-systems-6c66cf15ada), [ref5](https://towardsdatascience.com/recommender-systems-using-deep-learning-in-pytorch-from-scratch-f661b8f391d7), [ref6](https://www.analyticsvidhya.com/blog/2019/07/how-to-build-recommendation-system-word2vec-python/)    
  + Text Summarization [ref1](https://towardsdatascience.com/text-summarization-in-python-3f5a25418606)  
  + Text Generation [ref1](https://www.analyticsvidhya.com/blog/2019/07/openai-gpt2-text-generator-python/)  
  + Music Classification [ref1](https://towardsdatascience.com/music-genre-classification-with-python-c714d032f0d8)  

+ Preparing the Environment
  + [Linux, Python, Virtualenv](https://towardsdatascience.com/how-to-setup-a-python-environment-for-machine-learning-354d6c29a264)  
  
  + Versioning Tools
    + [Git](https://git-scm.com/book/en/v2)
    + [Github](https://guides.github.com/)
    + [GIT Large File Versioning](https://git-lfs.github.com/)
    + [Gitlab](https://about.gitlab.com/)
  + Exploratory Data Analysis Tools
    + Jupyter [ref1](http://jupyter.org/), [ref2](https://github.com/jupyterlab/jupyterlab), [ref3](https://www.analyticsvidhya.com/blog/2018/05/starters-guide-jupyter-notebook/), [ref4](https://towardsdatascience.com/data-science-for-startups-r-python-2ca2cd149c5c), [ref5](https://towardsdatascience.com/a-very-simple-demo-of-interactive-controls-on-jupyter-notebook-4429cf46aabd), [ref6](https://towardsdatascience.com/10-simple-hacks-to-speed-up-your-data-analysis-in-python-ec18c6396e6b)  
    + Numpy [ref1](https://docs.scipy.org/doc/numpy-dev/user/quickstart.html), [ref2](https://www.datacamp.com/community/tutorials/python-numpy-tutorial)
    + Pandas [ref1](http://proquest.safaribooksonline.com/9781449323592), [ref2](http://pandas.pydata.org/pandas-docs/stable/), [ref3](https://www.machinelearningplus.com/python/101-pandas-exercises-python/)  
      + [Pandas Machine Learning](http://pandas-ml.readthedocs.io/en/stable/)
      + [SKLearn Pandas](https://github.com/scikit-learn-contrib/sklearn-pandas)
      + [Geopandas](http://geopandas.org/)
      + [Framequery](https://pypi.org/project/framequery/)
    + [Statsmodels](http://www.statsmodels.org/stable/index.html)
  + Machine Learning Tools
    + [Scikit-Learn](http://scikit-learn.org/stable/)
        + [Inbalanced Learn](http://contrib.scikit-learn.org/imbalanced-learn/stable/#)
        + [ForestCI](https://github.com/scikit-learn-contrib/forest-confidence-interval)
    + Tensor Flow [ref1](https://www.tensorflow.org/),  [ref2](https://towardsdatascience.com/battle-of-the-deep-learning-frameworks-part-i-cff0e3841750)  
        + TF.Text [ref1](https://medium.com/tensorflow/introducing-tf-text-438c8552bd5e)  
        + TF Datasets [ref1](https://medium.com/tensorflow/introducing-tensorflow-datasets-c7f01f7e19f3)  
    + Keras [ref1](https://keras.io/), [ref2](https://blog.keras.io/keras-as-a-simplified-interface-to-tensorflow-tutorial.html), [ref3](https://towardsdatascience.com/4-awesome-things-you-can-do-with-keras-and-the-code-you-need-to-make-it-happen-858f022eec85)  
    + PyTorch [ref1](https://pytorch.org/), [Comparison Tensorflow vs PyTorch](https://towardsdatascience.com/pytorch-vs-tensorflow-spotting-the-difference-25c75777377b)  
    + [Gensim](https://radimrehurek.com/gensim/)  
    + [Orange](https://orange.biolab.si/)
  + NLP Tools
    + [NLTK](https://www.nltk.org/)
    + [Spacy](https://spacy.io/)
    + [TextBlob](http://textblob.readthedocs.io/en/dev/)  
  + Visualization Tools [ref1](https://medium.com/@alark/we-need-more-interactive-data-visualization-tools-for-the-web-in-python-ad80ec3f440e)  
    + [Matplotlib](https://matplotlib.org/)
    + [Seaborn](https://seaborn.pydata.org/)
    + Bokeh [ref1](https://bokeh.pydata.org/en/latest/), [example](https://towardsdatascience.com/data-visualization-with-bokeh-in-python-part-iii-a-complete-dashboard-dc6a86aa6e23)
    + [Plotly](https://plot.ly/)
    + [Altair](https://altair-viz.github.io/)
    + [GGPlot2](http://ggplot.yhathq.com/)
    + [MPLD3](http://mpld3.github.io/)
      + [d3.js](https://d3js.org/)
    + [HoloViews](http://holoviews.org/)
    + [Folium](http://python-visualization.github.io/folium/)
      + [Leaflet](http://leafletjs.com/)
    + Neural Networks  visualization  
      + TensorBoard [ref1](https://www.tensorflow.org/guide/summaries_and_tensorboard), [ref2](https://github.com/tensorflow/tensorboard)  
      + Tensor Flow Playground [ref1](https://playground.tensorflow.org/)  
      + Tensor Flow Projector [ref1](https://projector.tensorflow.org/)   
      + Deep Replay [ref1](https://github.com/dvgodoy/deepreplay)  
  + Big Data and Distributed computing
    + Map Reduce
    + [Spark](https://towardsdatascience.com/deploy-a-python-model-more-efficiently-over-spark-497fc03e0a8d)
    + [Dask](https://towardsdatascience.com/why-every-data-scientist-should-use-dask-81b2b850e15b)
  + Analytical Pipelines
    + Scikit-Learn Pipelines [ref1](http://scikit-learn.org/stable/modules/generated/sklearn.pipeline.Pipeline.html)  
    + Luigi [ref1](https://github.com/spotify/luigi)  
    + Airflow [ref1](https://airflow.apache.org/), [ref2](https://towardsdatascience.com/data-pipelines-luigi-airflow-everything-you-need-to-know-18dc741449b7)  
  + Other Tools   
    + [NetworkX](https://networkx.github.io/)  
    + ETE Toolkit [ref1](http://etetoolkit.org/)  
    + ODO [ref1](https://odo.readthedocs.io/en/latest/)  
    + Docker [ref1](https://docs.docker.com/get-started/), [ref2](https://towardsdatascience.com/learn-enough-docker-to-be-useful-b7ba70caeb4b)  
  + Relational databases and SQL
  + NoSQL Databases
    + [Elastic Search](http://blog.adnansiddiqi.me/getting-started-with-elasticsearch-in-python/) 
    + Graph Databases  
      + [Graph Theory](https://towardsdatascience.com/graph-theory-history-overview-f89a3efc0478)  
  + Machine Learning Datasets [ref1](https://medium.com/datadriveninvestor/the-50-best-public-datasets-for-machine-learning-d80e9f030279)  
    
    
We are using https://git-lfs.github.com because the /datasets files can be large. [Install](https://github.com/git-lfs/git-lfs/wiki/Installation) it before the git clone.  
