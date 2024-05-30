# Evaluating the Impact of Data Augmentation on MobileNet Performance in Handwritten Signature Identification

*The thesis paper is yet to be published in DiVA portal.*

### Abstract

The primary objective of this thesis is to explore how data augmentation techniques influence the performance of MobileNet, specifically the MobileNetV3-Small architecture, in the context of handwritten signature identification. The study implements affine transformations such as rotation, scaling, and translation to augment the dataset and examines the resultant improvements in model accuracy and generalization capabilities.

### Objectives

1. Implement the MobileNetV3-Small CNN architecture for handwritten signature identification.
2. Develop a data augmentation pipeline applying affine transformations.
3. Evaluate the model's performance with and without augmented data using metrics like accuracy, precision, recall, F1 score, and loss.

### Key Findings

- The MobileNetV3-Small model trained with augmented data demonstrated significantly improved accuracy (85.94%) compared to the model trained without augmentation (75.26%).

## Repository Contents

- `Model_with_DA.ipynb`: Jupyter Notebook containing the implementation of the MobileNetV3-Small model with data augmentation techniques applied.
- `Model_without_DA.ipynb`: Jupyter Notebook containing the implementation of the MobileNetV3-Small model without any data augmentation.
- `LICENSE`: The MIT License file for the repository.
- `README.md`: This README file.

## Installation and Usage

### Prerequisites

- Python 3.10 or higher
- JupyterLab
- TensorFlow
- NumPy
- Matplotlib

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2. Install the required Python packages:

    ```bash
    pip install tensorflow numpy matplotlib jupyterlab
    ```

### Running the Notebooks

1. Open JupyterLab:

    ```bash
    jupyter lab
    ```

2. Open and run the `Model_with_DA.ipynb` notebook to see the implementation with data augmentation.
3. Open and run the `Model_without_DA.ipynb` notebook to see the implementation without data augmentation.

## Results

### Training and Validation Accuracy

- **With Data Augmentation**: Achieved a validation accuracy of 85.94%.
- **Without Data Augmentation**: Achieved a validation accuracy of 75.26%.

### Training and Validation F1 Score

- **With Data Augmentation**: Higher F1 score indicating better balance between precision and recall.
- **Without Data Augmentation**: Lower F1 score compared to the augmented model.

### Training and Validation Loss

- **With Data Augmentation**: Showed improved generalization with lower validation loss.
- **Without Data Augmentation**: Higher validation loss indicating potential overfitting.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please contact the authors:

- Charvi Sri Bodagala: [chbd23@student.bth.se](mailto:chbd23@student.bth.se)
- Sai Guru Rishit Reddy Palle: [sapl23@student.bth.se](mailto:sapl23@student.bth.se)



## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
