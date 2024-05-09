### Instructions:
- **Project Name**：User State Prediction-Group13

- **Description**：This project employs LSTM to predict the interaction states between users and items. Due to the mismatch between the header length of the raw data and the dimensionality of the data features, dynamic header setting was performed during data preprocessing. The model in the file "Final_Project_Group13.ipynb" does not utilize some optimization strategies but instead sets hyperparameters based on multiple training experiences. On the other hand, the model in the file "Final_Project_Group13_Opt.ipynb" incorporates a strategy combining dynamic learning rate adjustment and epoch selection. It utilizes a learning rate scheduler to automatically adjust the learning rate during training and implements early stopping to automatically determine the optimal number of epochs, thereby stopping training when the model achieves its best performance to avoid overfitting.

- **Usage**：Download and unzip the compressed file, then install the required deep learning libraries on your local computer or server to run.

- **Contact**：dpan771@connect.hkust-gz.edu.cn
