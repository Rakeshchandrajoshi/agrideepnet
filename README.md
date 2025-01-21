**AgriDeep-Net: Agricultural Image Classification Project**
This repository contains a deep learning-based image classification project using two agricultural datasets: ACHENY Dataset (Chenopodiaceae species) and Indian Basmati Paddy Seed Dataset. These datasets provide a unique challenge for classification due to their visual similarities within species and among classes, along with different environmental conditions for image acquisition.
Overview

**ACHENY Dataset (Chenopodiaceae)**
  •	**Content:** 27,030 RGB images of 30 species from the Chenopodiaceae family, captured under real-world conditions.
  •	**Challenge:** Visual similarities within and between species, along with intra-class diversity.
  •	**Image Quality:** Captured with Nikon COOLPIX S2800 (14.9MP) and Samsung SM-J701F (3.7MP) under varying weather conditions.
  •	**Data Split:**
        o	36% for training
        o	9% for validation
        o	5% for testing
  •	**Source:** https://data.mendeley.com/datasets/fpfty8nn7j/1

**Indian Basmati Paddy Seed Dataset**
  •	**Content:** 3,210 RGB images of 11 seed classes, including 10 different basmati paddy varieties, and an "Unknown" class.
  
  •	**Challenge:** Similar visual appearance among many classes.
  
  •	**Image Quality:** Captured with a Micromax Canvas TAB P802 (5MP) under controlled lighting conditions using two LED bulbs.
  
  •	**Data Split:**
        o	80% for training
        o	10% for validation
        o	10% for testing
  
  •	**Source:** http://dx.doi.org/10.17632/byms2fjzpw.2

**Project Goals**
The goal of this project is to develop deep learning models for image classification that can effectively differentiate between species and varieties in both datasets, despite the challenges of visual similarity and varying environmental conditions.


**Training the Model**
1.	**Data Preprocessing:** The data preprocessing steps can be found in the Jupyter notebooks in the notebooks/ folder. This includes resizing, normalization, and splitting of the datasets.
2.	**Model Architecture:** The model architecture is based on a convolutional neural network (CNN), which has been designed to work effectively with agricultural image datasets.
3.	**Training:** To train the model, use the training scripts in the scripts/ directory. A typical command for training the model would be:

**Evaluation:** After training, you can evaluate the model’s performance using the evaluate_model.py script, which will provide evaluation metrics such as accuracy, precision, and recall.

**Notebooks**
The Jupyter notebook titled “AgriDeep-Net_training_model.ipynb” is included for a step-by-step walkthrough of the process:

**References**
    **ACHENY Dataset:** https://doi.org/10.1016/j.dib.2021.107478
    **Indian Basmati Paddy Seed Dataset:** https://doi.org/10.1016/j.dib.2020.106460

**Contributing**
If you would like to contribute to this project, feel free to fork the repository, make improvements, and submit a pull request. Contributions are welcome!

**License**
This project is licensed under the MIT License.

