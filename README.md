# Handwritten Digit Recognizer 

A desktop application that recognizes handwritten digits (0–9) using a **Convolutional Neural Network (CNN)** trained on the **MNIST dataset**.  
The application is built using **Python**, **TensorFlow**, and **Tkinter**.

---

##  Features

- Upload an image of a handwritten digit
- Image preprocessing (grayscale, resize, normalization)
- CNN-based digit prediction
- Simple and clean desktop UI using Tkinter

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pillow (PIL)
- Tkinter (Desktop UI)

---

## Input Image Guidelines 

- Image should contain one digit (0–9)

- Prefer black digit on white background

- Supported formats: .png, .jpg, .jpeg

---

## Project Structure

handwritten_digit_recognizer/
│
├── app.py # Tkinter desktop application
├── train_model.py # CNN model training script
│
├── saved_model/
│ └── mnist_cnn_model.h5 # Trained CNN model
│
├── requirements.txt
├── README.md