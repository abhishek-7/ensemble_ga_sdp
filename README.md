

# Adaptive Selection of Ensemble-Fitness Function Combination in Software Defect Prediction
In this study, we select a Genetic function Ensemble Combination (GEC) to make an enhanced software defect predictor
In this study, we consider three fitness functions, Accuracy, F Measure,and GMean and use them to select features in twenty-four software datasets for feature selection. Based on the performance of a classifier on these selected features, using the DSF algorithm we select the fitness function which is most likely to correctly predict the defect susceptibility of a new class intance.
Post which we use three ensembles to classify these class instances as defective or non defective


## Dataset used
All datasets for the purpose of this project have been taken from the PROMISE repository of open source software- http://openscience.us/repo/defect


## Using this repository
dataset/dataset contains all the preprocessed datasets which are input to DSE pipeline  
dataset/annotated contains output of first fold of cassification, including results of all fitness-function ensemble combinations 
dataset/GEC contains additional columns containing predictions of GEC and probabilities  
dataset/metrics includes performance metrics   
dataset/finalResults contain only the OO metrics and the output of GEC to improve readabiltiy
results contain performance metrics of GEC

