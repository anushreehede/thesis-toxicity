# A Data-Driven Analysis of Toxicity Detection Models

A compiled repository of the notebooks used during my Master's Thesis at the University of Pennsylvania. I was advised by Dr. Ani Nenkova and Dr. Byron C. Wallace. The thesis manuscript is linked [here](https://drive.google.com/file/d/1ewN3Lpj8y6pa5oZ8L4bSYVoA54SqWW9i/view?usp=sharing). 

* `Toxicity_Train_Perspective.ipynb`: Picks a sample of comments from the Toxic Comments data set with their true toxicity label, computes the [Perspective API](https://perspectiveapi.com/) toxicity score for the comment and computes the "error".  
* `Analysis Regression on [Toxicity_Train/Perspective] Errors.ipynb`: Analyzes the errors by building a regression model that predicts the error of a comment made by Perspective API. 
* `BERT_Toxicity_Tuning`: Fine-tunes a BERT model on the toxicity task using a subset of the Toxic Comments dataset. Code inspired from <https://github.com/Noixas/BERT-Toxicity>.  
* `BERT-Toxicity-Errors.ipynb`: Computes the BERT-Toxicity scores for the same subset of comments analyzed above. Contains scripts to get the template-based comparison analysis as well as the BERT-Toxicity scores for the [American News data](https://github.com/anushreehede/incivility_in_news) from my [earlier work](https://www.aclweb.org/anthology/2021.eacl-main.225/). These scores were used to repeat the experiments from this work and see how BERT-Toxicity compares against the Perspective API.    
* `Analysis of Regression [BERT Toxicity].ipynb`: Analyzes the errors by building a regression model that predicts the error of a comment made by the BERT-Toxicity model.  
* `Copy of Misc Tasks.ipynb`: Contains some miscellaneous tasks such as measuring the regression stability and the template-based analysis.  
* `/Misc_Expts`: Contains notebooks with experiments that didn't make it to the final thesis.  

Data was sourced from [Jigsaw's Kaggle competition](https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/).   
For detailed versions of datasets and word-lists, please email me at <anushree.hede@gmail.com>.     

 
