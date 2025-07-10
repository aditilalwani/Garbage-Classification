# Garbage-Classification– Edunet–Shell Skills4Future AICTE Internship
This repository documents my work for Weeks 1 to 3 of the Garbage Classification project completed under the Edunet–Shell Skills4Future AICTE Internship, focused on Green skills & AI.
The goal is too develop an accurate and efficient garbage classification model using EfficientNetV2B2 and transfer learning for automated waste sorting.

## 🌱 Project Objective

Manual garbage sorting is inefficient and error-prone. This project aims to automate the process by 
- Building an AI-powered system to **classify waste images** into categories like plastic, paper, metal, glass, cardboard, and trash.
- Use **transfer learning** to achieve high accuracy with limited data and compute.
- Explore real-world applications of deep learning for **environmental sustainability**.

---

## 🛠️ Tech Stack

| Category          | Tools/Technologies                            |
|-------------------|-----------------------------------------------|
| Programming       | Python                                        |
| Frameworks        | TensorFlow, Keras                             |
| Model             | EfficientNetV2B2 (ImageNet pretrained)        |
| Data Handling     | ImageDataGenerator, NumPy, Pandas             |
| Visualization     | Matplotlib, Seaborn                           |
| Platform          | Google Colab (with GPU)                       |
| Others (optional) | EarlyStopping, Dropout (for regularization)   |

---

## 🚀 Outcome

- Successfully trained a deep learning model to classify garbage images with **high accuracy** (insert exact %).
- Demonstrated effective use of **transfer learning** for sustainable AI applications.
- Developed skills in **data preprocessing, model building, evaluation, and visualization**.
- Contributed to the idea of **smart waste segregation systems**, aiding recycling efforts.

---

## 🗂️ Dataset

- Custom dataset with 6 classes: `plastic`, `glass`, `metal`, `cardboard`, `paper`, `trash`
- Preprocessed using resizing, normalization, and augmentation.

---

## 🧠 Methodology

1. **Preprocessing**: Image resizing, normalization, augmentation  
2. **Model Building**: EfficientNetV2B2 base + custom dense layers  
3. **Training**: Optimizer - Adam; Loss - Categorical Crossentropy  
4. **Evaluation**: Accuracy/loss trends, confusion matrix, predictions

