
# Paddy Disease Classification

## Introduction
Paddy Disease Classification is a deep learning-based project aimed at identifying different paddy leaf diseases using image classification techniques. This project utilizes a Convolutional Neural Network (CNN) to detect and diagnose diseases, helping farmers take early preventive measures.

## Motivation
Being from a farming background, I have seen firsthand the impact of paddy diseases on crop yield. Many farmers struggle to correctly identify diseases, often leading to ineffective treatments. This project aims to provide an AI-powered solution for disease identification, reducing crop losses and improving productivity.

## Dataset
The dataset consists of **10,407 labeled images**, categorized into **nine disease types and one normal leaf class**. The data is split into **75% training, 15% validation, and 10% testing** to ensure robust model evaluation.

## Model Architecture
- **Convolutional Neural Network (CNN)** with multiple convolutional layers.
- Max pooling layers to reduce dimensionality and improve feature extraction.
- Fully connected layers leading to a Softmax output for classification.
- Adam optimizer for efficient training and improved accuracy.

## Performance
- Achieved **81.36% test accuracy** on the dataset.
- Hyperparameter tuning and data augmentation used to enhance model performance.

## Installation
```bash
# Clone the repository
git clone https://github.com/your-username/paddy-disease-classification.git

# Navigate to the project directory
cd paddy-disease-classification

# Install required dependencies
pip install tensorflow numpy pandas matplotlib opencv-python
```

## Usage
```bash
# Run the classification script with an input image
python paddy_disease_classifier.py --image path/to/image.jpg
```

## Future Scope
- Improve classification accuracy using more advanced deep learning models.
- Deploy the model as a web or mobile application for real-time disease detection.
- Collaborate with agricultural organizations for large-scale testing.

## Contributing
Contributions are always welcome! If you have any improvements, feel free to submit a pull request.

## License
This project is licensed under the **MIT License**.

## Contact
For any inquiries or suggestions, please reach out at **deepakgangwar856@gmail.com**.
```

