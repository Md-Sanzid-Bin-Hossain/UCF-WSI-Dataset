# A Public Dataset of Histopathology Images for Deep Learning Model-Based Organ Classification
By Md Sanzid Bin Hossain, Yelena Piazza, Jacob Braun, Anthony Bilic, Michael Hsieh, Samir Fouissi, Chen Chen, Liqian Wang, Husain Mujtaba, Dexter Hadley

## Summary
In this paper, we introduce a challenging dataset, which contains 15 organ classes for deep learning model development and validation. Our publicly available dataset addresses a crucial gap in digital pathology by providing a large, diverse, and annotated collection of whole slide histopathology images, following FAIR principles. It serves as a benchmark for medical imaging analysis tasks like disease classification, and cancer and pneumonia cell segmentation, enabling improved diagnostics and treatment strategies. With its diverse organ classes and a vast number of patches, it is an ideal resource for transfer learning, accelerating research progress. Crucially, by introducing substantial publicly available data into this field, the dataset overcomes a fundamental challenge, paving the way for more robust deep-learning models in digital pathology. Overall approach of our work is provided in the following Figure:

![Alt text](Images/overall_process.png)

<br>


## Dataset
Our dataset is available on the following [link](https://stars.library.ucf.edu/ucfnecropsywsi/). Dataset contains 15 organ classes. A sample WSI image of each Organ class is provided in the following Figure.

![Alt text](Images/WSI_all_organs.png)

<br>

## Code
1. Code to run the patch extraction can be found in the following [Google Colab notebook](Patch_batch_processing.ipynb)
2. Code to run the classification task can be found in the following [Google Colab notebook](UCF_WSI_Classification_model.ipynb)
