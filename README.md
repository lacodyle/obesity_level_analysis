## Obesity Level Analysis of Adult Population in Latin America 
<i> Machine Learning Project for DSC478: Programming Machine Learning Applications at DePaul University </i><br>
<i>Highlights: Cluster Analysis and Feature Selection using Decision Trees</i><br>


Analysis of Obesity Levels including cluster analysis for data exploration, classification, and feature selection to analyze a dataset
containing obesity levels among adults from Mexico, Peru, and Columbia and determine which specific eating habit or daily activities most
affect the classification of obsesity levels. 

The dataset was obtained from the University of California Irvine (UCI) Machine Learning Repository. 

The approach and methodology begins with data preprocessing and cluster analysis. Cluster analysis is performend as an exploratory analysis to
determine any patterns in the data and if any patterns existed when age groups are binned to generational groups. Next several classifiers models
are fit to the dataset including K-NN, Decision Tree, Gradient Descent, and SVM, and models are evaluated using a classification report for best
performance. Lastly, the best performing model, in this case, Decision Tree, is used to perform feature selection and the top 15% of the most 
important features are selected and compared to determine which attributes are most salient in classifying obesity levels. 

Methodology:
1. Data Preprocessing: Data Exploration and Feature Transformations 
2. Cluster Analysis Exploration 
3. Classification and Model Selection
4. Feature Selection 
5. Results and Conclusion 

Summary of Results:
Results from the cluster analysis revealed that patterns existed betwen genders but not necessarily between age groups. Decision Tree classifer model had the best performance in classifying obesity levels at 94%. It was predicted that eating high calorie food frequently, eating between meals, and having  lower days of physical activity would be the most salient attributes in determining obesity levels. Results from the feature selection revealed that the most important factors in classifying obesity level are gender, weight, and family history with obesity. An individual's generational age group did not play an important factor in classifying obesity levels. 
