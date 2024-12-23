# HemoClassifier

HemoClassifier is a neural network designed to classify images of blood cells with high accuracy. This repository contains our work on experimenting with different pretrained models, expanding and adapting them for this specific task. The models we tested, ranked from the worst to the best performing, are:

1. ResNet  
2. ConvNext Base  
3. ConvNext Large  

## Key Steps in Our Workflow

1. **Data Loading and Inspection**  
   - We carefully inspected the dataset to remove outliers and "fake blood cells" (images of singers added to verify dataset validation).  

2. **Data Augmentation**  
   - We applied advanced augmentation techniques, such as RandAugment and AugMix, to generate diverse samples and enhance model robustness.

3. **Model Training and Saving**  
   - The models were trained on the prepared dataset, and checkpoints were saved for later use.

4. **Performance Evaluation**  
   - The performance of each model was rigorously evaluated on both clean and noisy datasets.

## Results

- **ConvNext Large Model Accuracy**:  
  - **97.10%** on clean blood cell images (real-world scenario).  
  - **87%** on a noisy dataset.

## Why HemoClassifier?

This project demonstrates the effectiveness of leveraging state-of-the-art pretrained models and applying rigorous data preparation techniques to achieve high classification accuracy in medical imaging tasks. HemoClassifier is a step forward in creating reliable and robust solutions for blood cell image classification.

Feel free to explore the code, and contributions are welcome!
