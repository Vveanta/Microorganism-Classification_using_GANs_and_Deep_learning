# Microorganism Image Classification Using Deep Learning

## Repository Structure
- `Microorganism-Classification_using_GANs_and_Deep_learning/`
  - `codes/`: Contains all the code notebooks.
    - `GAN_Model/`: Includes `GanMain.ipynb` for GAN model training and `image_saver_for_hydra_generated.ipynb` for generating synthetic images.
    - `Classification/`: Contains classification notebooks (`adaboost-on-micro.ipynb`, `resnet50-on-micro.ipynb`, `inception-for-micro.ipynb`, `xgboost-on-micro.ipynb`).
  - `micro-dataset.zip`: The dataset with original images of Paramecium and Hydra.

## Installation and Usage
- Prerequisites: Python 3, Jupyter Notebook, TensorFlow, Keras, XGBoost.
- Clone the repository and install required libraries.
- Start with training the GAN model (`GAN_Model/GanMain.ipynb`), save the `.h5` file.
- Use `image_saver_for_hydra_generated.ipynb` to generate the augmented dataset.
- Apply one of the classification methods from the `Classification` folder on the augmented dataset.

## Research Paper
The paper is still in publication will be added as soon as published

## Contributions and Acknowledgements
Thanks to [Contributors' Names].

## Dataset
The `micro-dataset.zip` contains the original images of Paramecium and Hydra.
