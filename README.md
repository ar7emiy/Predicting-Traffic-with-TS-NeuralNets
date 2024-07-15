# Predicting-Traffic-with-TS-NeuralNets
DePaul's CSC 578 (Neural Networks) course Final Project's Kaggle Competition
www.kaggle.com/competitions/csc-578-final-project-spring-2024/overview/description

# Description

The goal of the project is to apply deep learning to do time series forecasting. In particular, you create deep learning models to predict future traffic volume at a location in Minnesota, between Minneapolis and St Paul. The dataset is a cleaned-up version of UCI for hosting the Metro Interstate traffic volume.

The specific goal will be to predict from a 12-hour input window, just the traffic volume for 3 hours past the end of the window. That is a little different from the single-step, multi-step, and multi-output RNN with LSTM examples from the TensorFlow Time Series Tutorial, but it will be much simpler to compare results within Kaggle. For further details, see the detailed task description.

# Evaluation
The evaluation metric for this competition is Mean Absolute Error (MAE).

# Submission Format
For every author in the dataset, submission files should contain two columns: id and prediction, where id should be 0-based indices for the rows in the test set, and prediction should be the predicted traffic volume of the row. The id number/index should start with 35589. The submission file must start with a header row, and be followed by 4986 rows of predictions (for ids from 35589 to 40574). No comma within id numbers predictions should be used -- commas should be used only as a delimiter between the two columns. Also there should be no space between the two columns..


id,prediction
35589,3481.280499629291
35590,2876.958684404887
35591,3417.846569017333
35592,3293.5700851714946
...
40572,3947.3713909650096
40573,3542.831172174818
40574,2781.3480226893225

