# Medicare_Fraud_Detection
#Improving Medicare Fraud Detection Accuracy in Deep Learning by Exploring Chi-Square, Mutual Info, and Data Sampling Techniques

The project, titled "Improving Medicare Fraud Detection Accuracy in Deep Learning by Exploring Chi-Square, Mutual Info, and Data Sampling Techniques," aims to enhance the accuracy of Medicare fraud detection using various techniques. The project is organized into different sections, covering traditional machine learning algorithms, deep learning methods, feature selection methods, and data sampling techniques. Let's summarize the key aspects of each section:

1. Traditional Machine Learning Algorithms:

    The project begins by loading and preparing the dataset, utilizing important libraries such as pandas and scikit-learn.
    Traditional machine learning algorithms like Decision Trees, Support Vector Machines (SVM), Random Forest, and K-Nearest Neighbors (KNN) are implemented for fraud detection.
    The accuracy of each model is evaluated, with Random Forest achieving an accuracy of 91.43%.

2. Deep Learning Method:

    A deep neural network is built using the Keras library, consisting of multiple layers with ReLU activation functions.
    The model is trained on the dataset, and its performance is evaluated with accuracy and loss curves.
    The deep learning model is saved in h5 format for future use.

3. Feature Selection Methods:

    Feature selection is explored using two methods: Chi-Square and Mutual Information.
    Chi-Square is applied to select the top k features based on their importance, and the dataset is updated accordingly.
    Mutual Information is used for feature selection, and the top features are visualized through bar plots.

4. Data Sampling in Deep Learning Model:

    Three data sampling techniques—Random Over Sampling, Random Under Sampling, and SMOTE—are implemented to address class imbalance.
    Each technique is applied, and the resulting datasets are visualized to showcase the impact on class distribution.
    A neural network model is trained on each sampled dataset, and the performance is evaluated.

5. Feature Selection and Data Sampling Together:

    Chi-Square feature selection is combined with SMOTE data sampling.
    The top features selected by Chi-Square are retained, and SMOTE is applied to balance the dataset.
    A neural network model is trained on the combined approach, and the performance is assessed.

Overall, the project demonstrates a comprehensive exploration of techniques to improve Medicare fraud detection accuracy, combining traditional machine learning algorithms, deep learning methods, feature selection, and data sampling. The results and insights obtained from these experiments contribute to a more robust and accurate fraud detection system.
