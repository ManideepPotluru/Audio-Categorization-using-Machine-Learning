# Audio-Categorization-using-Machine-Learning
Classifying mp3 files into respective genres using a plethora of machine learning classifiers(XGBoost/Random Forests/Logistic Regression/Convolution Neural Networks/SVM) and various audio data representations(MFCC/PCA/Spectrograms/STFT)

This Project is done as a part of CS529 along with Aditya Thalluri and Sharat Tangella

We used the FMA dataset for this project.

Code for the project is available as the single jupyter notebook AudioCategorization.ipynb.

Unzip the dataset and move the notebook into the same folder containing Datasets train, test and csv files train.csv, test_idx.csv. Notebook expects those folders and csv files to be in the same directory.

Open the AudioCategorization Jupyter Notebook and Run All Cells in the Cell Tab.

For each Data Representation, we get two csv files containing the predictions on test data from each of two classifiers compared on that Data Representation.

Also, the confusion matrix, accuracies, confidance intervals for each pair of classifers are plotted. Their Results along with Bias are discussed in the same section.

Future enhancements has been suggested.
