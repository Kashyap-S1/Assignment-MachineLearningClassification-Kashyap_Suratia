# ABOUT PROJECT

Sometimes a model may have a very high accuracy due to target variable feature imbalance. The model may perform poorly in the field. Imbalance learning balances the target variable features. 

## Installation of the modules

You can install `sklearn` and 'imblearn' modules via the terminal by;
```
pip install sklearn
pip install imblearn
```
 or via the Jupyter notebook cell;

 ```
 !pip install sklearn
 !pip install imblearn
 ```

 ## Imbalanced learning techniques

 There are different approaches to imbalanced learning;
 * Oversampling
 * Undersampling
 * (Over and Under) Sampling

 ### Oversampling
 Oversampling randomly chooses data from the minority and adds to the dataset without replacement. The oversampling techniques used here were;
 * Naive Random Oversampling
 * SMOTE Oversampling

 ### Undersampling
 Undersampling randoms deletes the majority form the dataset to create a balance. The appraoches used in this project include;
 * Cluster centroids

 ### (Over and Under) Sampling 

THis is a resampling technique that combines both over and under sampling. The SMOTEENN approach was used here.


The balanced dataset was therefore trained on Logistic Regression for the first project.

The second project involved ensemble learning from imblearn module. Multiple models are applied here including resampling, classifiers and regression. The techniques used were;
* Balanced Random Forest Classifier,
* Easy Ensemble Classifier.