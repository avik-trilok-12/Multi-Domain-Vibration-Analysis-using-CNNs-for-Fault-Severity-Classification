# Multi-Domain-Vibration-Analysis-using-CNNs-for-Fault-Severity-Classification

Dataset: ![Fault Classification Dataset](https://drive.google.com/file/d/1YuvPUeVTTA0rQGt3712Ov9eSsy0cRkCk/view?usp=sharing)

Using TensorFlow and Keras deep learning framework, a CNN model was developed. ReLU and softmax functions were used as activation functions. ‘categorical crossentropy’ was the loss function used. The data generated from the test rig was converted to grayscale images. The model was trained on the dataset for 100 epochs using a 70:20:10 split of the dataset for training, validation and testing. After training the model, the model produced a test accuracy of 95.40% on completely unseen data. The training and validation loss curves suggested that the model was a good fit for the dataset and is performing well on generalized data. Hence, this CNN architecture produced good results upon analysis of the training and validation plots.

![image](https://github.com/user-attachments/assets/fcc6abb0-d85a-4628-a240-997315887998)

![Screenshot 2024-05-13 200721](https://github.com/user-attachments/assets/49551afd-0f5e-4436-87a8-212f3b8ba02f)

![plot 1](https://github.com/user-attachments/assets/2da845c2-5c2e-42c2-9801-9840080694cd)
