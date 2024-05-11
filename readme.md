# WBC Classification Project

This project aims to classify different types of White Blood Cells (WBCs) using deep learning techniques. The models are trained on the Rabin WBC dataset, which is available at the following link:

https://drive.google.com/file/d/1rkeLB3EU-Mlq1wJ8JifV\_Y6iGYkrTOPY/view?usp=sharing

## Models

The project implements four different model architectures using transfer learning:

1. **ResNet-50**
2. **ResNet-101**
3. **ConvNeXt Small**
4. **Inception V3**

All of these models achieve an accuracy of over 99% on the Rabin WBC dataset.

## Dependencies

This project is built using the following libraries:

- Python 3.7+
- PyTorch
- FastAI
- NumPy
- Matplotlib

## Installation

1. Clone the repository:
    git clone https://github.com/your-username/wbc-classification.git
2. Install the required dependencies:
    pip install -r requirements.txt

## Usage

1. Download the Rabin WBC dataset from the provided link and place it in the `data/` directory.

2. Run the appropriate notebook for the model you want to train or evaluate:

   - `resnet50.ipynb`
   - `resnet101.ipynb`
   - `convnext_small.ipynb`
   - `inception_v3.ipynb`

3. The notebooks contain code for data preprocessing, model training, and evaluation.

## References

The `papers/` directory contains various research papers that were referred to during the development of this project.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or bug fixes.

## License

This project is licensed under the [MIT License](LICENSE).