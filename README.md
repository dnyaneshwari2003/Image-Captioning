# 🖼️ Image Caption Generator (BLIP + Tkinter)

This is a Python GUI application that automatically generates a descriptive caption for an uploaded image using a deep learning model from Hugging Face (BLIP - Bootstrapped Language-Image Pretraining). The interface is built using Tkinter.



## 🔍 Features

* Upload any `.jpg`, `.jpeg`, or `.png` image
* View the uploaded image in the app
* Automatically generates a caption using a pre-trained AI model
* Clean and minimal graphical interface (GUI) using Tkinter



## 🛠️ Requirements

* Python 3.8 or higher
* Required libraries:

  * `transformers`
  * `torch`
  * `pillow`
  * `tkinter` (included by default in most Python installations)





## 🚀 How to Run

From your terminal or command prompt, navigate to the project directory and run:

```bash
python ImgCaption.py
```

The GUI window will open. Click **“Upload Image”**, choose a file, and the AI will generate a caption for it.



## 🧠 Model Used

* **Model**: [Salesforce/blip-image-captioning-base](https://huggingface.co/Salesforce/blip-image-captioning-base)
* **Framework**: Hugging Face Transformers
* **Device**: CPU (you can modify it to use CUDA/GPU for faster inference)



## 🖼️ Example

![image](https://github.com/user-attachments/assets/533f4b8d-33f4-42f7-a75f-8d63b354d465)







