# graduate_admission_prediction
This project uses a Deep Learning Artificial Neural Network (ANN) to predict a student's Chance of Admit into a master's program based on several academic and profile-related parameters.

📁 Dataset Description
The dataset includes the following features:

GRE Score (out of 340)

TOEFL Score (out of 120)

University Rating (1 to 5)

Statement of Purpose (SOP) strength (1 to 5)

Letter of Recommendation (LOR) strength (1 to 5)

Undergraduate GPA (out of 10)

Research Experience (0 or 1)

Chance of Admit (target variable, ranging from 0.0 to 1.0)

📌 Objective
To build and train an Artificial Neural Network (ANN) that can effectively predict the Chance of Admit based on the provided features.

🛠️ Technologies Used
Python

NumPy, Pandas

Scikit-learn (for preprocessing)

TensorFlow / Keras (for building the ANN)

Matplotlib, Seaborn (for data visualization)

🧠 ANN Model Architecture
Input Layer: 7 input features

Hidden Layers: 2 Dense layers with ReLU activation

Output Layer: 1 neuron with Sigmoid activation (for regression output in [0,1])

Loss Function: Mean Squared Error (MSE)

Optimizer: Adam

🔄 Workflow
Data Preprocessing

Handling missing values (if any)

Feature scaling using MinMaxScaler or StandardScaler

Train-test split

Model Building

Define ANN model using Keras Sequential API

Compile the model

Train the model with training data

Model Evaluation

Evaluate performance on test data

Visualize loss curves and predictions vs actuals
