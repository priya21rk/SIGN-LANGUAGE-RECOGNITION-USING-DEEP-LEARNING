# Indian Sign Language (ISL) Recognition

## Overview
Sign language is an essential means of communication for individuals when verbal communication is impractical or undesired. However, comprehension among non-signers is often limited, creating barriers for the hearing-impaired. This project addresses this challenge by developing a robust and inclusive Indian Sign Language (ISL) recognition system using advanced deep learning techniques.

## Features
- **Dataset Integration**: Five datasets are leveraged, including four publicly available datasets from Kaggle and one custom dataset created by our team.
- **Deep Learning Models**: Implementation of custom Convolutional Neural Networks (CNNs) and transfer learning techniques using:
  - InceptionV3
  - ResNet50V2
  - MobileNetV2
  - VGG19
- **Comprehensive ISL Recognition**: Classification of hand poses representing digits (0-9) and English alphabet letters across multiple datasets.

## Datasets
1. **Dataset 1**:
   - Images: 10,752
   - Classes: 33 (10 digits + 23 letters)
   - Accuracy: 99.07% (VGG19)
2. **Dataset 2**:
   - Images: 24,355
   - Classes: 36 (10 digits + 26 letters)
   - Accuracy: 99.75% (VGG19)
3. **Dataset 3**:
   - Images: 36,000 (ISLRTC dataset)
   - Classes: 36 (10 digits + 26 letters)
   - Accuracy: 98.69% (MobileNetV2)
4. **Dataset 4**:
   - Images: 42,745
   - Classes: 36 (10 digits + 26 letters)
   - Accuracy: 100% (CNN, MobileNetV2, ResNet50V2, VGG19)
5. **Custom Dataset**:
   - Images: 17,500
   - Classes: 35 (10 digits + 25 letters)
   - Accuracy: 99.94% (Custom CNN Model)

## Technologies Used
- **Programming Language**: Python
- **Frameworks**: TensorFlow, Keras
- **Deep Learning Models**: Custom CNN, Transfer Learning Models (InceptionV3, ResNet50V2, MobileNetV2, VGG19)
- **Tools and Libraries**:
  - NumPy, Pandas
  - OpenCV
  - Matplotlib, Seaborn

## Results
This project demonstrates the power of deep learning architectures in accurately classifying ISL gestures, with the highest accuracy of 100% achieved on Dataset 4. The custom CNN model also performed exceptionally well on the custom dataset, achieving 99.94% accuracy.

## Applications
- Enhancing accessibility and communication for the hearing-impaired.
- Developing real-time ISL translation systems.
- Facilitating inclusive interaction between signers and non-signers.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ISL-Recognition.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the training scripts for the desired model and dataset:
   ```bash
   python train_model.py --dataset dataset_name --model model_name
   ```
4. Use the pre-trained model for predictions:
   ```bash
   python predict.py --image image_path
   ```

## Contribution
Contributions are welcome! Please follow the steps below:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.


## Acknowledgements
- Kaggle for providing publicly available datasets.
- The hearing-impaired community for inspiring this work.


---
Together, let's bridge the gap in communication and make the world more inclusive.

