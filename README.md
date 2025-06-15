# Transfer Learning Project with Cats vs Dogs Dataset

This project was developed as part of the practical activity for the **Digital Innovation One (DIO)** course, in the challenge:

> **Transfer Learning Project in Python**

---

## Introduction

The proposal involves applying **Transfer Learning** using a convolutional neural network (CNN) in **Python**, either in the **Google Colab** environment or locally with Keras/TensorFlow libraries, as I used myself.

In this project, I used the famous **"Cats vs Dogs" image dataset**, available from the [Microsoft repository](https://www.microsoft.com/en-us/download/details.aspx?id=54765).

---

## Project Objective

Train two models to classify images between **cats** and **dogs**:

1. **Base Model (from scratch)**  
   Convolutional neural network built from scratch with `Conv2D`, `MaxPooling2D`, `Dropout` and `Dense`.

2. **Transfer Learning Model**  
   Using the **VGG16** model pre-trained on the ImageNet dataset. The last layer is replaced to perform binary classification (cat or dog), and the rest of the network is frozen.

---

## Practical Applications

This project was designed to demonstrate how neural networks are applied in visual classification systems. This type of model can serve as a basis for systems that verify images like CAPTCHAs, which distinguish humans from bots.

---

## Technologies Used

- Python 3.10
- TensorFlow / Keras  
- Matplotlib and NumPy  
- Google Colab (or local Jupyter Notebook)  
- Dataset: [Cats vs Dogs - Microsoft Research](https://www.microsoft.com/en-us/download/details.aspx?id=54765)

---

## Code Structure

- Dataset extraction and reading
- Normalization, resizing and labeling
- Data split into training, validation and test sets
- Building a base model from scratch
- Applying Transfer Learning with VGG16 architecture
- Model training and evaluation
- Metric visualization and performance charts
- Prediction testing with individual images

---

## Expected Results

After training both models, charts are generated comparing **accuracy** and **validation loss**, demonstrating how **Transfer Learning** can accelerate and improve network performance, even with limited data volume.

---

## How to Run

1. Download the dataset at: [https://www.microsoft.com/en-us/download/details.aspx?id=54765](https://www.microsoft.com/en-us/download/details.aspx?id=54765)  
2. Extract the files and set the correct path in the script.
3. Run the code in [Google Colab](https://colab.research.google.com/) or your local environment.
4. View the results and test with any image you want.

---

## References

This project is a practical activity from the **Digital Innovation One (DIO)** course:  
[https://github.com/digitalinnovationone](https://github.com/digitalinnovationone)
