# Evaluating the Impact of Data Augmentation on MobileNet Performance in Handwritten Signature Identification

*The thesis paper is published in DiVA portal.*

### Abstract

The primary objective of this thesis is to explore how data augmentation techniques influence the performance of MobileNet, specifically the MobileNetV3-Small architecture, in the context of handwritten signature identification. The study implements affine transformations such as rotation, scaling, and translation to augment the dataset and examines the resultant improvements in model accuracy and generalization capabilities.

### Objectives

1. Implement the MobileNetV3-Small CNN architecture for handwritten signature identification.
2. Develop a data augmentation pipeline applying affine transformations.
3. Evaluate the model's performance with and without augmented data using metrics like accuracy, precision, recall, F1 score, and loss.

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


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please contact the authors:

- Sai Guru Rishit Reddy Palle: [rishitpalle@gmail.com](mailto:rishitpalle@gmail.com) | [LinkedIn](https://www.linkedin.com/in/rishit-reddy-palle/)
- Charvi Sri Bodagala: [charvisri.muni@gmail.com](mailto:charvisri.muni@gmail.com) | [LinkedIn](https://www.linkedin.com/in/charvi-sri-bodagala-2900a9217/)


