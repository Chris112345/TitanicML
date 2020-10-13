# TitanicML

Author: Christopher Allan Liu
Date Created: 9/10/20
Date Updated: 10/13/20


## Description: 

This repository conatains work for the Kaggle competition: Titanic Machine Learning from Disaster.  For more information regarding the competition, access the website: https://www.kaggle.com/c/titanic/overview. 

## Libraries:

- pandas - https://pandas.pydata.org/
- Scikit Learn - https://scikit-learn.org/stable/index.html

## Files:

-Data (Folder)

	+ gender_submission.csv : This file, provided by Kaggle, acts as a template for solution submissions.

	+ train.csv : This file conatins the training data provided by Kaggle.

	+ test.csv : This file contains the test data provided by Kaggle.

-Methods (Folder)
	
	+ TreeAnalysis.ipynb : This file uses methods for tree machine learning models.

	+ DataAnalysis.ipnyb : This python notebook contains analysis information regarding the train.csv dataset.

	+ ScikitLearnDecisionTree : This file implements the decision tree classifier provided by Scikit Learn.
	
## Citations:

- Scikit Learn

@article{scikit-learn,
 title={Scikit-learn: Machine Learning in {P}ython},
 author={Pedregosa, F. and Varoquaux, G. and Gramfort, A. and Michel, V.
         and Thirion, B. and Grisel, O. and Blondel, M. and Prettenhofer, P.
         and Weiss, R. and Dubourg, V. and Vanderplas, J. and Passos, A. and
         Cournapeau, D. and Brucher, M. and Perrot, M. and Duchesnay, E.},
 journal={Journal of Machine Learning Research},
 volume={12},
 pages={2825--2830},
 year={2011}
}

@inproceedings{sklearn_api,
  author    = {Lars Buitinck and Gilles Louppe and Mathieu Blondel and
               Fabian Pedregosa and Andreas Mueller and Olivier Grisel and
               Vlad Niculae and Peter Prettenhofer and Alexandre Gramfort
               and Jaques Grobler and Robert Layton and Jake VanderPlas and
               Arnaud Joly and Brian Holt and Ga{\"{e}}l Varoquaux},
  title     = {{API} design for machine learning software: experiences from the scikit-learn
               project},
  booktitle = {ECML PKDD Workshop: Languages for Data Mining and Machine Learning},
  year      = {2013},
  pages = {108--122},
}

url: https://scikit-learn.org/stable/index.html


- pandas

@software{reback2020pandas,
    author       = {The pandas development team},
    title        = {pandas-dev/pandas: Pandas},
    month        = oct,
    year         = 2020,
    publisher    = {Zenodo},
    version      = {latest},
    doi          = {10.5281/zenodo.3509134},
    url          = {https://doi.org/10.5281/zenodo.3509134}
}

@InProceedings{ mckinney-proc-scipy-2010,
  author    = { {W}es {M}c{K}inney },
  title     = { {D}ata {S}tructures for {S}tatistical {C}omputing in {P}ython },
  booktitle = { {P}roceedings of the 9th {P}ython in {S}cience {C}onference },
  pages     = { 56 - 61 },
  year      = { 2010 },
  editor    = { {S}t\'efan van der {W}alt and {J}arrod {M}illman },
  doi       = { 10.25080/Majora-92bf1922-00a }
}

url: https://pandas.pydata.org/