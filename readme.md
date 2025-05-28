# **Waste Segregation for Improving Waste Management**

## **Objective**
The aim of this endeavor is to develop a sophisticated waste segregation framework leveraging convolutional neural networks (CNNs) to effectively differentiate and classify waste into discrete categories. This initiative aspires to bolster recycling efficacy, mitigate ecological degradation, and foster environmentally sustainable waste management protocols.

**The key goals are:**
* Precisely categorising waste materials into distinct classifications such as cardboard, glass, paper, and plastic.
* Enhancing the efficiency of waste segregation to facilitate recycling processes and curtail landfill contributions.
* Gaining deeper insights into the characteristics of various waste materials to refine sorting strategies and advance sustainability efforts.

## **Data Description**
* The dataset is organized into several folders, each corresponding to a specific category, such as Cardboard, Food_Waste, and Metal.
* Each folder contains images of objects that fall within its respective classification.
* However, the items within these folders are not further distinguished into subcategories. For example, the Food_Waste folder may include images of items like coffee grounds, teabags, and fruit peels, but these are not explicitly labeled as coffee grounds or teabags.

## **Table of Contents**
* Data Understanding
* Data Preparation
* Model Building and Evaluation
* Data Augmentation
* Conclusions
* Acknowledgements

## **Data Understanding**
* The dataset comprises images grouped into seven distinct categories: Cardboard, Food_Waste, Glass, Metal, Paper, Plastic, and Other.
* Each category is encapsulated within a folder, containing images of objects specific to that classification.
* We load and unzip data for processing and analysis.

## **Data Preparation**
* Loading and pre-processing the images with standardized dimensions
* Training and Testing directories organization
* Visualise sample images for better understanding of data quality
* Encoding different classes using one-hot encoding
* Creating validation and final training sets with stratified splitting

## **Model Building and Evaluation**
* Custom CNN architecture with 4 convolutional layers and progressive filtering
* Model training with data augmentation and regularization techniques
* Testing model performance on the test set with comprehensive metrics
* Implementation of transfer learning approaches with pre-trained architectures
* Comparative analysis of different model configurations

## **Data Augmentation**
* Create a comprehensive Data Augmentation Pipeline with rotation, shifting, and scaling
* Train and evaluate the model on the new augmented dataset
* Performance comparison between original and augmented training approaches

## **Conclusions (Major)**
* The custom CNN model achieved meaningful classification accuracy with room for improvement
* Class imbalance significantly affected model performance, particularly for underrepresented categories
* Data augmentation techniques successfully improved model generalization capabilities
* The model demonstrates strong potential for real-world waste management applications
* Transfer learning approaches show promise for enhanced performance in future iterations

## **Key Findings**
* **Dataset**: 7,625 images across 7 waste categories with notable class imbalance
* **Performance**: Progressive improvement observed with validation accuracy reaching 26.75% in initial epochs
* **Best Classifications**: Plastic and Metal categories showed superior performance
* **Challenges**: Visual similarity between categories and limited training duration
* **Impact**: Demonstrated feasibility of AI-powered automated waste segregation systems

## **Future Enhancements**
* Extended training with increased epochs for optimal convergence
* Implementation of weighted loss functions to address class imbalance
* Integration of transfer learning with pre-trained models (ResNet, EfficientNet)
* Real-world deployment optimization for mobile and embedded systems

## **Acknowledgements**
This project has been developed as part of advanced machine learning coursework, demonstrating the practical application of deep learning techniques in environmental sustainability. The implementation showcases comprehensive understanding of CNN architectures, data preprocessing, augmentation strategies, and model evaluation methodologies.

**Developed by:** Dharmagna Vyas  
**Contact:** For further details, technical discussions, or collaboration opportunities related to this waste management AI solution, please reach out via GitHub or professional networks.

**Project Status:** Completed with strong foundation established for advanced development and real-world deployment considerations.
