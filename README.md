# Lightweight Age Detection Model

This repository contains a lightweight age detection model that predicts age from images. The project follows a complete Machine Learning Pipeline, starting from data gathering from Kaggle to data processing and model building.

## Background
The motivation behind this project stemmed from the need for an efficient age detection model that could be integrated into various applications, such as security systems, personalized marketing, and age-restricted content filtering. Traditional methods of age detection often involve complex algorithms and heavy computational resources. This project aimed to develop a lightweight solution without compromising accuracy.

## Approach
### Data Gathering
The dataset for training the model was obtained from Kaggle, comprising a diverse set of images with corresponding age labels.

### Data Processing
The dataset underwent preprocessing steps to ensure uniformity and compatibility with the model architecture. This involved resizing, normalization, and augmentation techniques to enhance the robustness of the model.

### Model Building
Two approaches were explored for age prediction: classification and regression.
- **Classification Approach**: Initially, a classification model was built using MobileNet V2 as the base architecture. However, the accuracy of this model was suboptimal, and the Mean Squared Error (MSE) was high.
- **Regression Approach**: To address the limitations of the classification model, a regression model was implemented using the same base architecture. Additionally, data augmentation techniques were applied to enrich the training dataset. This resulted in a significant reduction in MSE, indicating improved performance.

### Further Research
Continued research was conducted to refine the model further and explore additional methodologies for age prediction. Future enhancements may include experimenting with alternative architectures, incorporating ensemble techniques, and leveraging advanced data augmentation strategies.

## Storytelling Approach
To enhance engagement and understanding, a storytelling approach was adopted throughout the project documentation. This included narratives detailing the evolution of the project, challenges faced, breakthroughs achieved, and the significance of age detection in real-world scenarios. Additionally, GIFs were integrated to visually illustrate key concepts and stages of the project.


## License
This project is licensed under the [MIT License](LICENSE).
