# Semantic Segmentation with MobileNetV2 and U-Net

This project demonstrates semantic image segmentation using a custom architecture that combines MobileNetV2 and U-Net. The goal is to accurately segment objects in images, showcasing a robust approach to image analysis.

## Project Overview

- The `u-net-on-carvana.ipynb` notebook contains the entire project pipeline, from data preprocessing to model training and evaluation.

## Prerequisites

- Python (>=3.6)
- PyTorch (>=1.0)
- torchvision
- tqdm
- matplotlib
- numpy
- PIL

## Project Structure

- `u-net-on-carvana.ipynb`: Jupyter Notebook containing the project code.
- `MobileNetV2_Unet_wts.pth`: Saved model weights.
- `MobileNetV2_Unet_model.pth`: Saved entire model (architecture and weights).

## Getting Started

1. Clone this repository: `git clone https://github.com/Rumit95/Semantic-Segmentation-of-Image`
2. Navigate to the project directory: `cd semantic-segmentation`
3. Open `u-net-on-carvana.ipynb` using Jupyter Notebook or Jupyter Lab.
4. Run each cell sequentially to execute the project steps.

## Usage

- Follow the steps in the notebook to preprocess data, create the custom MobileNetV2 U-Net model, train the model, and visualize results.
- You can modify hyperparameters, the number of training epochs, or experiment with different architectures to suit your needs.

## Model Architecture
- [Model Architecture](Model_architecture.svg)

## Credits

- The MobileNetV2 architecture is based on the original paper by Sandler et al. [https://arxiv.org/abs/1801.04381].
- U-Net architecture reference: Olaf Ronneberger, Philipp Fischer, Thomas Brox. "U-Net: Convolutional Networks for Biomedical Image Segmentation."

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.

Feel free to reach out if you have any questions or suggestions!



