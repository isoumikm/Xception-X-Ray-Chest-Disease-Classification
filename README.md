# Xception-X-Ray-Chest-Disease-Classification
Classification of Chest Diseases from X Rays using Xception Model


# Introduction
Chest Radiography is one of the commonly used techniques to perform examination through X-rays. It involves a medical diagnostic test by exposing a part of a body to small dosages of ionized radiation particles to produce an image of the target. State-of-the-art algorithms have already been into development to detect specific pathological disorders, however detecting multiple pathologies from a chest radiograph is what we have aimed in this paper. This paper is built on the premise of building a model using the Xception model, which is trained from scratch and is used to detect and classify diseases from the NIH Clinical Center dataset on Chest X-Rays from more than 30,000 patients and a group of anonymized 100,000 chest X-ray scans. The Xception model is a deep convolutional neural network architecture, that involves depthwise separable convolutions. The concept behind the project is a traditional one, but the approach is novel. The Xception model gives a better accuracy and is faster than other unearthed approaches. The sole objective of this process is to remove the reliable and interpretable nature when it comes to dealing with images related to medical sciences and bring in artificial intelligence into the decision-making process.

# Dataset Used: 
National Institutes of Health Chest X-Ray Dataset
Chest X-ray exams are one of the most frequent and cost-effective medical imaging examinations available. However, clinical diagnosis of a chest X-ray can be challenging and sometimes more difficult than diagnosis via chest CT imaging. The lack of large publicly available datasets with annotations means it is still very difficult, if not impossible, to achieve clinically relevant computer-aided detection and diagnosis (CAD) in real world medical sites with chest X-rays. One major hurdle in creating large X-ray image datasets is the lack resources for labeling so many images. Prior to the release of this dataset, Openi was the largest publicly available source of chest X-ray images with 4,143 images available.

This NIH Chest X-ray Dataset is comprised of 112,120 X-ray images with disease labels from 30,805 unique patients. To create these labels, the authors used Natural Language Processing to text-mine disease classifications from the associated radiological reports. The labels are expected to be >90% accurate and suitable for weakly-supervised learning. The original radiology reports are not publicly available but you can find more details on the labeling process in this Open Access paper: "ChestX-ray8: Hospital-scale Chest X-ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases." (Wang et al.)

# Class descriptions
There are 15 classes (14 diseases, and one for "No findings"). Images can be classified as "No findings" or one or more disease classes:

Atelectasis
Consolidation
Infiltration
Pneumothorax
Edema
Emphysema
Fibrosis
Effusion
Pneumonia
Pleural_thickening
Cardiomegaly
Nodule Mass
Hernia

# Citations
Wang X, Peng Y, Lu L, Lu Z, Bagheri M, Summers RM. ChestX-ray8: Hospital-scale Chest X-ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases. IEEE CVPR 2017, ChestX-ray8Hospital-ScaleChestCVPR2017_paper.pdf

NIH News release: NIH Clinical Center provides one of the largest publicly available chest x-ray datasets to scientific community

Original source files and documents: https://nihcc.app.box.com/v/ChestXray-NIHCC/folder/36938765345




