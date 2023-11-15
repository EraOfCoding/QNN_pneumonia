# Hybrid Quantum-Classical Convolutional Neural Networks for the Chest X-Ray Pneumonia Classification

### Abstract 
Hybrid quantum machine learning applications are developing rapidly, and while they still have not shown a practical advantage over classical machine learning applications, promising technologies have emerged in recent years. Hybrid Quantum-Classical Convolutional Neural Networks, i.e., Quanvolutional Neural Networks, are remarkable technologies for image classification tasks, which step us closer to the goal of achieving the practical advantage of quantum computing. In this work, we implement Hybrid Quantum-Classical Neural Networks for the classification of pneumonia through chest x-ray images, as well as compare the model performance with different encoding strategies and a noise model. As a result of this work, we showed that the simulated noisy Quanvolutional Neural Networks with different encoding strategies outperformed classical CNNs.

### Results
In this work, we have demonstrated Hybrid Quantum-Classical Neural Networks for pneumonia classification with angle, threshold, and higher order encoding strategies. As we can see from the evaluation of the models on a testing dataset in Table, all of the QNN models without noise have outperformed the CNN. QNN with an angle encoding strategy showed the best accuracy of 94.95%, followed by its noisy analog, which performed slightly worse with an accuracy of 91.92%. On the other hand, noisy QNN with a higher order encoding had the lowest accuracy of 87.88%. This relative inefficiency could result from the complex encoding implementation, which might cause slightly worse data processing, in our case, processing of chest X-ray images. It is also important to note that the results for the noisy QNNs were insignificantly worse or did not differ at all from the QNN without noise.

### Table representing the accuracy of each model: QNN - Hybrid Quantum-Classical, Neural Network and CNN - Convolutional Neural Network 
![Results on validation for all models](https://raw.githubusercontent.com/EraOfCoding/QNN_pneumonia/main/tableofaccuracy.png)

### Plot representing the accuraccy and loss based on the training dataset
![Results on training for all models](https://raw.githubusercontent.com/EraOfCoding/QNN_pneumonia/main/quantum_noisy_models/all_train.png)

### Plot representing the accuraccy and loss based on the validation dataset
![Results on training for all models](https://raw.githubusercontent.com/EraOfCoding/QNN_pneumonia/main/quantum_noisy_models/all_val.png)
