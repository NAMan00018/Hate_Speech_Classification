Hate Speech Classification Project

**Overview**

This project aims to detect hate speech using an LSTM (Long Short-Term Memory) model. The model was trained on merged datasets, preprocessed for text cleaning, and vectorized for feature engineering. The final model was tested using a Gradio application for real-time predictions.


**Steps Involved**:-

1. **Data Merging**
   
    I have combined two datasets: raw_data and imbalance_data. These datasets provide a comprehensive foundation for training the model and are available in this repository.

2. **Text Preprocessing**
   
    Text preprocessing is a crucial step to clean and prepare the data for model training. I used nltk and re libraries for this purpose. The following custom cleaning function was employed:


![image](https://github.com/user-attachments/assets/a98d9394-6aa1-4ae6-8451-3f89731abeb0)

3. **Feature Engineering**
   
    For feature engineering, I implemented text vectorization using the embedding layer from Keras. This step converts text into numerical representations suitable for input into the LSTM model. I also used     padsequences to ensure consistent input lengths.

Here’s a brief overview of the code used for feature engineering:
![image](https://github.com/user-attachments/assets/99c6dac0-9da9-482f-9cd8-b7ac81adc96b)

4. **Model Training**
   
    I trained the LSTM model using the Rmsprop optimizer and sigmoid activation function. This configuration was chosen for its effectiveness in binary classification tasks, such as hate speech detection.
![image](https://github.com/user-attachments/assets/bedda3e1-3b6f-4cec-90ff-d1a7c12c030b)

6. **Model Testing**
   
    To test the model, I used a Gradio application, providing a user-friendly interface for real-time predictions. This allowed me to ensure the model’s performance and usability in practical scenarios.
   
    ![image](https://github.com/user-attachments/assets/8889c69a-e43d-4f82-884e-ef5fd9259f93)
  ![image](https://github.com/user-attachments/assets/8cc7ae8b-7f51-4b27-a243-fdbc9d208c49)



**Conclusion**

This project demonstrates the process of building an LSTM model for hate speech detection, from data preparation to real-time testing. For more details, explore the project files and code in this repository.




