# Performing-Clustering-and-Supervised-ML-for-an-Industrial-Problem
1. This task is based upon having unstructured data pool received from current sensors of a 3-phase induction motor at a rate of 10K - 15K instances per second.
2. The Dataset included 3 phase AC motor(3.2 hp) current readings of 3 phases.
3. I performed data cleaning, extraction, transformation and manipulation while combining all text files into a single list which inturn was converted into DatFrame.
4. Next part was EDA, getting basic information about the features, Visaulization using Seaborn and Matplotlib, Outlier Detection
5. With all the features I applied K Means Clustering to get hold of the data and getting insights from it.
5. After this I did Feature Engineering and added 3 new features and scaled all features for all features to be on same scale and no discruptions occur at the end.
6. Then Removed few most correlated features and started by choosing best supervised algorithm for the data.
7. Choose K Neighbors Classifier as the final method to build the model and also performed HPT using Optuna library.
8. I am attaching the pickle file and python notebook alongside it.
