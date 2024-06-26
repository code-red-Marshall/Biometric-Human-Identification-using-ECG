# Biometric Human Identification for Patient Classification using ECG

## Electrocardiogram or ECG
An Electrocardiogram (ECG or EKG) is a tool used to measure and visualize the electrical activity of the heart.
The electrocardiographic waves are called P, Q, R, S, T, U (in that order) and they are connected to each other by an isoelectric line. Each of these waves represents different phases of the cardiac cycle.
The QRS complex plays a crucial role in ECG signal analysis and classification due to its representation of critical cardiac activity and its utility in diagnosing various heart conditions.

![OIP](https://github.com/code-red-Marshall/Biometric-Human-Identification/assets/82904501/a883064e-4a7b-4a36-b0ef-3f41f728a9a3)



This project involves the development of a machine learning model for patient classification. The model is built using Python, TensorFlow, and Keras. The dataset used in this project is a CSV file containing patient data that is being prepared from the public free source dataset named "PTB Diagnostic ECG Database". We have used Pan-Tompkins Algo for R peak Detection using the Moving Integrated Window.

##Pan-Tompkins model:

![pan tompkin](https://github.com/code-red-Marshall/Biometric-Human-Identification-/assets/82904501/69e50a46-2481-4a31-b2d6-8fef4a9f4262)


## Pan-Tompkins Plot
![Pan-Tompkins Algo](https://github.com/code-red-Marshall/Biometric-Human-Identification-/assets/82904501/6646b850-d883-49d5-a87b-6878f463e95f)

## Project Structure

The project is divided into several sections. Below is a flow chart of the entire project: 

![Block diagram of PM](https://github.com/code-red-Marshall/Biometric-Human-Identification-/assets/82904501/50591d2d-3dcc-40db-ab89-bc7a9d6e3987)

1. **Importing Libraries**: This section involves importing necessary libraries such as numpy, pandas, tensorflow, keras, sklearn, and matplotlib.

2. **Data Preprocessing**: In this section, the dataset is imported and preprocessed. The preprocessing steps include dropping unnecessary columns, label encoding, and splitting the dataset into training and testing sets.

3. **Building the Model**: This section involves building the machine learning model using TensorFlow and Keras. The model is an ANN model with multiple dense layers.

![model_plot](https://github.com/code-red-Marshall/Biometric-Human-Identification-/assets/82904501/9626dbfb-b035-4de6-be22-99eb59b76123)

4. **Training the Model**: In this section, the model is trained using the training data. The model's performance is evaluated using accuracy and loss metrics for both training and validation data.

##Model Accuracy and Model Loss:

![Figure_1](https://github.com/code-red-Marshall/Biometric-Human-Identification-/assets/82904501/d996bf57-cdf2-4d46-a16a-9f6feafcd2a6)
![Figure_2](https://github.com/code-red-Marshall/Biometric-Human-Identification-/assets/82904501/614e861c-064c-4f49-9a7a-737244ad453f)

5. **Evaluating the Model**: This section involves evaluating the model's performance using various metrics such as F1-score, precision, recall, and accuracy. The model's performance is also visualized using accuracy and loss plots.

6. **Making Predictions**: In this section, the model is used to make predictions on the training data.

7. **Model Performance Evaluation**: This section involves evaluating the model's performance using a confusion matrix, F1-score, precision, recall, and accuracy. The performance is also visualized using ROC curves.

##ConfusionMatrix
![CM](https://github.com/code-red-Marshall/Biometric-Human-Identification-/assets/82904501/b27f5c80-029e-4232-8e4b-3f831cf363c5)

##Evaluation_Metrics

![Screenshot 2024-04-25 133520](https://github.com/code-red-Marshall/Biometric-Human-Identification-/assets/82904501/bcd648f3-b31b-4c4c-a4cb-6c1a0a99b18d)



## Usage

To use this project, follow these steps:

1. Clone the repository to your local machine.
2. Install the necessary libraries mentioned in the 'Importing Libraries' section in main.py.
3. Run the Python script to train the model and evaluate its performance.
4. The database.py is a demo to how the dataset has been organised. 

## Contributing

Contributions to this project are welcome. Please fork the repository and create a pull request with your changes.

## Contact

For any queries or suggestions, please open an issue on GitHub.
