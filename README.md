# 🧠 Retinal Image Enhancement Using GAN

A deep learning-based project that enhances the quality of retinal fundus images using a CycleGAN model. The enhanced images improve diagnostic accuracy for retinal diseases like diabetic retinopathy and glaucoma by denoising, sharpening, and preserving fine vessel structures.

---

## 🚀 Project Overview

This project aims to enhance low-quality retinal images using Generative Adversarial Networks (GANs), particularly CycleGAN, without needing paired data. Enhanced images aid ophthalmologists in better diagnosis and analysis.

---

## 🛠️ Tech Stack

- 🐍 **Python**
- 📦 **PyTorch**
- 🧠 **CycleGAN** (Generative Adversarial Network)
- 📊 **Matplotlib**, **OpenCV**, **NumPy**
- 🗃️ **Git, GitHub**
- 📁 **VS Code**

---

📁 Folder Structure

Retinal-Image-Enhancement-Using-GAN/
├── requirements.txt (for Python)/
├── results/
│ ├── enhanced_images/
├── src/
│ ├── main.py
│ ├── train.py
│ ├── evaluate.py
│ └── model.py
├── utils/
│ ├── helper.py
│ └── preprocessing/
│ └── helper2.py
├── README.md

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/jeevanar17/Retinal-Image-Enhancement-GAN.git
   cd Retinal-Image-Enhancement-GAN
2.Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
Install dependencies:

3.Install dependencies:
pip install -r requirements.txt


🚀 Usage
Update and run the main pipeline:
1.Update and run the main pipeline:
python src/main.py

2.To train the model:
python src/train.py
To evaluate:

3.To evaluate:
python src/evaluate.py
Make sure to place the training and test datasets in the correct subfolders before running.

📸 Sample Results
Original	Enhanced


🧠 Model
This project uses a modified CycleGAN architecture to enhance retinal images without the need for paired datasets. It learns the mapping from low-quality to high-quality retinal images using adversarial loss and cycle-consistency loss.

📄 License
This project is open source and available under the MIT License.
