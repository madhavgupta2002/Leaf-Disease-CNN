
# Potato and Tomato Disease Classification

A deep learning project to classify diseases in potato and tomato plants using CNN models built with TensorFlow.

## Dataset

Dataset used: [Plant Village Dataset](https://www.kaggle.com/datasets/arjuntejaswi/plant-village)

Credit: @arjuntejaswi on Kaggle

### Classes

#### Potato Diseases:
- Early Blight
- Late Blight
- Healthy

#### Tomato Diseases:
- Target Spot
- Tomato Mosaic Virus
- Yellow Leaf Curl Virus
- Bacterial Spot
- Early Blight
- Healthy
- Late Blight
- Leaf Mold
- Septoria Leaf Spot
- Spider Mites

## Project Structure

- Data preprocessing and augmentation
- Model architecture with CNN layers
- Training with validation
- Performance evaluation
- Visualization of results

## Requirements

```python
tensorflow
matplotlib
gdown
numpy
scikit-learn
seaborn
```

## Model Architecture

### Potato Model
- Input Image Size: 256x256
- 6 Convolutional layers
- MaxPooling layers
- Dense layers for classification
- Data augmentation including random flips and rotations

### Tomato Model
- Input Image Size: 128x128
- 4 Convolutional layers with dropout
- MaxPooling layers
- Dense layers with dropout for classification
- Enhanced data augmentation

## Performance

Both models include:
- Training/validation accuracy plots
- Confusion matrix visualization
- Example predictions with confidence scores


![Screenshot 2024-11-07 141302](https://github.com/user-attachments/assets/6b62fc01-7bfd-47b5-93bd-950472959f04)

## Usage

1. Install dependencies:
```bash
pip install tensorflow matplotlib gdown numpy scikit-learn seaborn
```

2. Download the dataset (automatically handled in the notebook)

3. Run the training:
- For potato disease classification
- For tomato disease classification

## Model Outputs

The models save:
- Model architecture (.keras format)
- Model weights (.h5 format)

## Results Visualization

The notebook includes:
- Training/validation accuracy curves
- Loss curves
- Confusion matrices
- Sample predictions with actual vs predicted labels

## License

This project is licensed under the MIT License.

## Acknowledgments

- Dataset: Plant Village Dataset from Kaggle
- TensorFlow and Keras documentation
- Scientific Python community
