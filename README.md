# Animal Classification with Transfer Learning

This project implements an animal image classification model using TensorFlow and Keras, leveraging transfer learning with EfficientNetB0. The model is trained to classify images into multiple animal categories, providing a practical example of deep learning for computer vision.

## Features

- **Transfer Learning:** Utilizes EfficientNetB0 pre-trained on ImageNet for robust feature extraction.
- **Data Augmentation:** Improves model generalization with random flips, rotations, zooms, and contrast adjustments.
- **Two-Phase Training:** Initial training with frozen base layers, followed by fine-tuning for improved accuracy.
- **Comprehensive Evaluation:** Includes accuracy/loss plots, classification report, and confusion matrix visualization.

## Project Structure

```
animal_classification/
├── dataset/
│   ├── class1/
│   ├── class2/
│   └── ...
├── Image Classification of animals.pdf
├── LICENSE
├── README.md
├── animal_classification_model.ipynb
├── initial_checkpoint.h5
```

## Getting Started

### Prerequisites

- Python 3.7+
- TensorFlow 2.x
- Keras
- NumPy, Matplotlib, Seaborn, scikit-learn

Install dependencies:
```
pip install tensorflow matplotlib seaborn scikit-learn
```

### Dataset

The `dataset/` folder is included in this repository and contains the images organized by class:
```
dataset/
  ├── class1/
  │     ├── img1.jpg
  │     └── ...
  ├── class2/
  │     ├── img1.jpg
  │     └── ...
  └── ...
```

### Usage

1. Clone this repository:
   ```
   git clone https://github.com/Abdullah2609/animal_classification_model.git
   cd animal_classification_model
   ```
2. (Optional) Add or update images in the `dataset/` folder as needed.
3. Open `animal_classification_model.ipynb` in Jupyter or VS Code.
4. Run the notebook cells to train, fine-tune, and evaluate the model.

## Results

- Training and validation accuracy/loss curves
- Classification report with precision, recall, and F1-score
- Confusion matrix visualization

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

**Author:** Abdullah Sakeeb
**Project:** Animal Classification Model with
