# DSP332_Practical_Assignment_2




Part_1

Data pre-processing/exploring

Goal: this part aims to familiarise the student team with the dataset, explore its characteristics and identify the features that will be used in the classification task.

The student team is required to do the following to complete this part of the assignment:

    Select and describe the dataset based on the information provided in the repository where the dataset is available.
    If the dataset retrieved from the repository is not in a format that is easy to work with (e.g. comma, comma-separated values or .csv file), transform it into the required format. 
    If the values of any features (attributes) are textual values (e.g. yes/no, positive/neutral/negative, etc.), transform them into numeric values.
    If some data objects have missing or outlier values for some features (attributes), find a way to deal with them by studying additional sources of information.
    Represent the dataset visually and calculate statistical indicators:

    create at least two 2- or 3-dimensional scatter plots illustrating class separability based on different features (attributes); students should avoid using the data object ID or class label as a variable in the scatter plots;
    create at least 2 histograms showing the separation of classes based on features (attributes) of interest;
    show the distribution of the 2 features (attributes) of interest;
    calculate statistical indicators (at least the central tendency and the dispersion of the feature values).

 
Include the following information in the report:
description of the dataset (including references to the information sources used) 	- title, source, creator and/or owner of the dataset
- description of the problem domain of the dataset
- the licensing conditions of the dataset (if any)
- the way in which the dataset was collected
description of the content of the dataset (including references to the information sources used) 	- number of data objects in the dataset
- the representation of the features (attributes) of the dataset together with their roles in the Orange tool (a clear representation of the target variable, used and skipped features)
- the number of classes in the dataset, the meaning of each class and the way the classes are represented (explanation of the labels corresponding to the classes); if the dataset provides several possible classifications of the data, the report must identify which classification exactly is being considered in the work
- the number of data objects belonging to each class
- the number and meaning of the features (attributes) in the dataset, as well as their value types and ranges (this information must be represented in a table, indicating the feature title, explanation, value type and range of values available in the dataset) 
- a snippet of the data file structure showing all columns of the data file and their values for at least some data objects
conclusions drawn from the analysis of scatter plots, histograms and distributions (see Step 5 of Part I) on the separability of the classes in the dataset. Students must answer the given questions 	- Are the classes in the dataset balanced, or does one class (or several classes) prevail? It is determined by judging how many data objects belong to each class.
- Does the visual representation of the data allow the structure of the data to be seen? It is about whether data objects belonging to different classes can be clearly separated.
- How many data groupings can be identified by studying the visual representation of the data? It is about whether there are any separable groupings of data or data objects of different classes are merged.
- Are the identified data groupings close to each other or far apart?
conclusions from the analysis of statistical indicators (at least the central tendency and the dispersion of the feature values) 	 
 
The Part I must end with conclusions about the features that will be used in futher analysis.





Part_2
Unsupervised machine learning

Goal: This part of the assignment aims to investigate the dataset further using clustering algorithms to see if the conclusions drawn earlier about the structure of the dataset and the separability of classes are valid.

The student team is required to do the following to complete this part of the assignment:

    Apply the two unsupervised machine learning algorithms considered in the study course: (1) Hierarchical clustering and (2)  K-means algorithm.
    For the Hierarchical clustering algorithm, perform at least 3 experiments by keeping the same linkage method and freely moving the cut-off line and analysing how the number and content of the clusters change.
    Calculate the Silhouette coefficient for the K-means algorithm for at least 5 different values of k and analyse the performance of the algorithm.

Include the following information into the report:

    Description of the hyperparameters available in the Orange tool and their meaning for each of the algorithms (including references to the information sources used).
    Description of the experiments performed with each of the algorithms, clearly indicating the values of the hyperparameters used and providing conclusions on the performance of the algorithm in terms of how the results obtained correspond to the known number of classes in the dataset.
    Conclusions whether the classes in the dataset are well or poorly separable based on the analysis of the performance of the two algorithms.





Part_3
Supervised machine learning

Goal: This part of the assignment aims to apply at least 3 classification algorithms to the previously analysed dataset and selected features of data objects.

One of the algorithms that must be used is artificial neural networks. The student team is free to choose two other algorithms.

The student team must do the following to complete this part of the assignment:

    Choose at least two supervised machine learning algorithms for the classification task. Students may use the algorithms covered in the study course or any other algorithms designed for the classification task. In the Orange tool these could be Logistic Regression, kNN, Tree, RandomForest, Gradient Boosting, SVM, Naive Bayes, AdaBoost.
    Split the dataset into training and test datasets.
    Perform at least 3 experiments with each algorithm using the training dataset, changing the values of the algorithm hyperparameters and analysing the performance metrics of the algorithms. 
    For each algorithm, select the trained model that provides the best algorithm performance.
    Apply the trained model for each algorithm to the test dataset.
    Evaluate and compare the performance of the trained models.

Include the following information into the report:

    A brief description (1/3 of an A4 page) of the two freely chosen algorithms and the rationale for their choice (excluding artificial neural networks), including references to the sources of information used.
    Description of all hyperparameters available in the Orange tool and their meaning for each of the algorithms.
    Information on the test and training datasets: (a) the total number of data objects added to the test and training datasets (number and %) and (b) information on how many data objects from each class are included in the training and test datasets (number and %).
    Hyperparameter values used in the experiments with each of the algorithms (in a table format) and screenshots showing these values and the performance metrics of the experiments.
    Conclusions on the performance of the models in the experiments performed, clearly identifying the model that will be used for testing.
    Results of the testing of the trained models and a comparison and interpretation of their performance, clearly separated from the training experiments. 

