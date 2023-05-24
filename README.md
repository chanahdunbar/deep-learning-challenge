# Deep-Learning-Challenge

Overview:
The purpose of this analysis was to assist a nonprofit organization (Alphabet Soup) select the applicants for funding with the best chance of success in their ventures. Using the features in the provided dataset, I created a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup. 

Results: 

Data Preprocessing
- The column 'IS_SUCCESSFUL' was the target for my model. The number 1 was used to denote successful applicants and the number 0 was used to identify unsuccessful applicants.
- Columns 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'STATUS', 'INCOME_AMT', and 'ASK_AMT' were my features.
- Both columns,'EIN' and 'NAME' were removed for the dataset for a more efficient analysis.

Compiling, Training, and Evaluating the Model
- For my neural network model I used 3 layers (one input, one hidden, and one output), the first layer had 6 neurons, the hidden layer also had 6 neurons, and the output layer had 1 neuron.

Summary: 
In summary, the model reach 100% accuracy fairly early in the training sessions.
