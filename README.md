# Concrete Crack Image Classification Project

![FI](https://github.com/UmarQayyum16/CrackDetective-Concrete-Crack-Image-Classification-with-AI/assets/149918632/8dac7490-569e-474e-8aa7-b8a84d432e44)

## Welcome to the Concrete Crack Image Classification Project!

### Overview

Concrete cracks can be a serious threat to the safety and durability of buildings. Identifying and addressing these cracks promptly is crucial to prevent further damage. This project introduces an innovative approach to tackle this issue – an image classification model designed to identify concrete cracks automatically. By harnessing the power of deep learning, this project aims to revolutionize the way we detect and address structural vulnerabilities.

### Dataset

The dataset comprises 40,000 concrete images sourced from various METU Campus Buildings. With a resolution of 227 x 227 pixels and RGB channels, each image is a snapshot of the real-world challenges faced by concrete structures. The diversity in surface finish and illumination conditions provides a robust foundation for training the model. Gratitude is expressed to Özgenel and Sorguç (2018) and Zhang et al. (2016) for their valuable contributions.

**Dataset Source:** [Concrete Crack Images for Classification](https://data.mendeley.com/datasets/5y9wdsg2zt/2)

**Citation:**
- Özgenel, Ç.F., Gönenç Sorguç, A. (2018). "Performance Comparison of Pretrained Convolutional Neural Networks on Crack Detection in Buildings", ISARC 2018, Berlin.
- Zhang, L., Yang, F., Zhang, Y. D., & Zhu, Y. J. (2016). "Road Crack Detection Using Deep Convolutional Neural Network." In 2016 IEEE International Conference on Image Processing (ICIP). [DOI: 10.1109/ICIP.2016.7533052](http://doi.org/10.1109/ICIP.2016.7533052)

## Project Workflow

1. **Problem Formulation:**
   - This is an image classification task to classify concrete images as either containing cracks or not containing cracks.

2. **Data Preparation:**
   - The dataset contains over 40,000 images of concrete surfaces, labeled as either 'Positive' (crack present) or 'Negative' (no crack).
   - Data augmentation techniques were applied to increase the diversity of the training data.

3. **Model Development:**
   - Transfer learning was applied using MobileNetV2 as a pre-trained base.
   - The model was fine-tuned to achieve a training and validation accuracy of over 90%.

4. **Training Performance:**
   - ![performance_report](https://github.com/UmarQayyum16/CrackDetective-Concrete-Crack-Image-Classification-with-AI/assets/149918632/27d8fc57-0e0a-4212-a1e2-ab216ad068a4)

5. **TensorBoard Visualization:**
   - TensorBoard was used to monitor the training process. Here's a snapshot:
     <img width="533" alt="training_process_epoch_accuracy" src="https://github.com/UmarQayyum16/CrackDetective-Concrete-Crack-Image-Classification-with-AI/assets/149918632/79983780-645b-4810-bec9-d3a4432c78ed">
     <img width="539" alt="training_process_epoch_loss" src="https://github.com/UmarQayyum16/CrackDetective-Concrete-Crack-Image-Classification-with-AI/assets/149918632/f08ffb9c-5c9a-40bc-8a60-ce9bf69900a5">

6. **Model Architecture:**
   - The model architecture is visualized below:
     ![model_architecture](https://github.com/UmarQayyum16/CrackDetective-Concrete-Crack-Image-Classification-with-AI/assets/149918632/e1b52937-158e-45cf-9bb6-80591a8aff6e)

7. **Model Predictions:**
   - Sample predictions on test images:
     ![prediction](https://github.com/UmarQayyum16/CrackDetective-Concrete-Crack-Image-Classification-with-AI/assets/149918632/fec89931-dd59-4858-be51-eb90cf4c6f25)

### Conclusion

This project isn't just about cracking the code; it's about cracking the challenges that concrete structures face. Join us on this exploration of image classification, where AI meets architecture, and together, we redefine the future of structural safety.

🚀 Dive into the code, explore the dataset, and witness the evolution of the Concrete Crack Image Classifier!

**Remember:** Safety doesn't happen by accident; it happens by design.

---

*Disclaimer: This project is an educational exercise, and the model's predictions should not replace professional structural assessments.*
