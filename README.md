
This repository demonstrates the application of two AI explainability methods, LIME (Local Interpretable Model-agnostic Explanations) and SIDU (Saliency-based Identification and Visualization), on the predictions of a ResNet50 image classification model.

## Overview
The project contains two Jupyter notebooks that serve as guides on how to apply LIME and SIDU on the given model:

- `lime_explanation_resnet50.ipynb`: This notebook showcases the application of the LIME method for interpreting ResNet50 predictions. The generated explanation is a binary mask that indicates the image regions that were most influential for the model's prediction.

- `sidu_explanation_resnet50.ipynb`: This notebook showcases the application of the SIDU method for interpreting ResNet50 predictions. The generated explanation is a saliency map that highlights the importance of different image regions in the context of the model's prediction.

## How to use
To run the notebooks and replicate the results, you need to install the necessary Python packages listed in `requirements.txt`. Ensure you have a Python environment (version 3.6 or newer) set up before proceeding.
1. Clone this repository to your local machine.
    ```
    git clone https://github.com/AnnaTz/resnet50-explanation-lime-sidu
    ```
2. Navigate to the cloned directory.
    ```
    cd resnet50-explanation-lime-sidu
    ```
3. Install the required Python packages.
    ```
    pip install -r requirements.txt
    ```
After installing the dependencies, you can open the Jupyter notebooks in your preferred environment (e.g., Jupyter Lab, Jupyter Notebook, or VS Code) and follow the instructions within to explore the interpretability methods.

## References
- Ribeiro, M., Singh, S., & Guestrin, C. (2016). "Why Should I Trust You?": Explaining the Predictions of Any Classifier. Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining. [Available online](https://arxiv.org/abs/1602.04938).
- Muddamsetty, S.M., Jahromi, M.N., Ciontos, A., Fenoy, L.M., & Moeslund, T.B. (2021). Visual explanation of black-box model: Similarity Difference and Uniqueness (SIDU) method. Pattern Recognit., 127, 108604. [Available online](https://arxiv.org/abs/2101.10710).
