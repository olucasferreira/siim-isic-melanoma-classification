# SIIM-ISIC Melanoma Classification

## Introduction

Melanoma is a deadly disease, but its prognosis improves significantly with early detection, often curable through minor surgery. Automating the diagnosis of melanoma using image analysis tools can enhance dermatologists' diagnostic accuracy, potentially positively impacting millions of lives. The SIIM-ISIC Melanoma Classification competition on Kaggle provided a platform to develop and showcase such tools.

This repository serves as documentation and a codebase for the Kaggle competition, outlining the key components of the completed notebook. The following sections provide an overview of the major components developed during the project.

## Notebook Components Overview

The notebook comprises the following key components, each completed during the model development process:

- **Data Exploration:** Explored the dataset to gain insights, understand its structure, and identify patterns influencing model development.

- **Data Formats:** Investigated different data formats provided in the competition, including DICOM, JPEG, and TFRecord formats. Successfully understood the nuances of each format for effective data utilization.

- **Model Building:** Developed two models within the notebook, utilizing both image and tabular data. The ensemble of these models was implemented to improve overall predictive performance.

- **Evaluation:** Assessed model performance using the AUC (Area Under the ROC Curve) metric, the primary evaluation metric for this competition.

## Disclaimer

This project was developed in 2020 for educational purposes. The models and code presented here may not be optimized for production use. Additionally, the dataset and competition context are specific to the SIIM-ISIC Melanoma Classification challenge on Kaggle as of 2020.

## How to Use This Repository

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/siim-isic-melanoma-classification.git
  
2. **Setup Environment:**

- Ensure that you have the required dependencies installed, as specified in the notebook.
- Set up a virtual environment if necessary.
- The completed notebook can also be accessed directly on the Kaggle platform [here](https://www.kaggle.com/code/olucasferreira/siim-isic-melanoma-ensemble-xgboost-effcentnet/notebook).

3. **Explore the Completed Notebook**

- Open and explore the notebook to understand the completed model development process.
- Modify and experiment with the code as needed for your own exploration.

4. **Contribute**

- If you have improvements, suggestions, or questions, feel free to contribute by commenting on the notebook.

5. **Acknowledgments**

- Acknowledge and give credit if you use or reference this code in your own work.

## Author

- Lucas Ferreira de Oliveira
- Contact: dolucasferreira@gmail.com
