🖼️ Image Caption Generator (BLIP + Tkinter)
This is a Python GUI application that automatically generates a descriptive caption for an uploaded image using a deep learning model from Hugging Face (BLIP - Bootstrapped Language-Image Pretraining). The interface is built using Tkinter.

🔍 Features
Upload any .jpg, .jpeg, or .png image

View the uploaded image in the app

Automatically generates a caption using a pre-trained AI model

Clean and minimal graphical interface (GUI) using Tkinter

🛠️ Requirements
Python 3.8 or higher

Required libraries:

transformers

torch

pillow

tkinter (included by default in most Python installations)

📦 Installation
Clone or download this repository to your local machine.

Install dependencies using pip:

bash
Copy
Edit
pip install transformers torch pillow
(Optional but recommended) Create a virtual environment:

bash
Copy
Edit
python -m venv venv
venv\Scripts\activate  # On Windows
🚀 How to Run
From your terminal or command prompt, navigate to the project directory and run:

bash
Copy
Edit
python ImgCaption.py
The GUI window will open. Click “Upload Image”, choose a file, and the AI will generate a caption for it.

🧠 Model Used
Model: Salesforce/blip-image-captioning-base

Framework: Hugging Face Transformers

Device: CPU (you can modify it to use CUDA/GPU for faster inference)

🖼️ Example
(Include a screenshot of the UI here if you like)

💡 Possible Improvements
Add “Copy Caption” button

Show progress bar or spinner while generating captions

Support drag-and-drop image uploads

Add multilingual captioning with translation APIs

📝 License
This project is open-source and available under the MIT License.

🙋‍♀️ Contributing
Pull requests and suggestions are welcome! Please open an issue to discuss major changes before submitting a PR.

