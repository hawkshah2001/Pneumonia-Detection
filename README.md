# Pneumonia-Detection

![Capture27](https://github.com/user-attachments/assets/f354eb7b-7707-4ef3-80d6-6c7c3092799c)


This project on Pneumonia Detection outlines the critical importance of accurately diagnosing pneumonia to prevent both false positives, which lead to unnecessary medication, and false negatives, which can result in untreated conditions and complications. Pneumonia, an infection in the lungs that fills the alveoli with liquid, is a significant health issue, with about 1.5 million adults diagnosed annually in the US and roughly 50,000 deaths per year.

The objective of the project is to develop a highly accurate image classification model to detect pneumonia from chest X-rays. The dataset used for this project consists of 5,856 images, divided into training, testing, and validation sets. The images are preprocessed by resizing to 64x64 pixels and normalizing pixel values. The models tested include logistic regression and deep neural networks, aiming to achieve a performance close to that of a pulmonary specialist, who has about a 90% accuracy rate in diagnosing pneumonia.

The logistic regression model achieved a training accuracy of 72.92% and a testing accuracy of 73.89%. The deep neural network model, with two hidden layers and four hidden units, also showed similar performance with consistent accuracy around 72-73%. Various optimization techniques, including L2 regularization, dropout regularization, and batch normalization, were applied to enhance the model performance. The combination of L2 regularization and dropout yielded the best results, with a training accuracy of 94.87% and a testing accuracy of 93.01%.

The VGG model, which utilizes convolutional layers, showed promising results with a high rate of true positives, achieving a training accuracy of 95.55% and a testing accuracy of 94.29%. This model, although computationally expensive, demonstrated a good balance between recall and accuracy, making it competitive with other models tested.

The business implications of deploying such a model are substantial. Improved diagnostic accuracy can lead to significant cost savings for hospitals by reducing the rate of misdiagnosis and subsequent readmissions. For every 1,000 cases, hospitals could save between $20,000 to $50,000 annually. Additionally, faster and more accurate diagnoses can increase patient throughput, potentially generating over $500,000 in annual revenue from handling more patients. The overall potential savings, considering reduced diagnostic times and improved patient turnover, could reach up to $2 million annually.
