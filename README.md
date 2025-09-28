# DermaScan_AndroidApp
📱 AI-powered Android app for early skin cancer detection using dermoscopic images, ensemble deep learning models, and on-device TensorFlow Lite inference.
---

## ✨ Features  
- 📸 **Image Input** – Upload or capture skin lesion images with your device camera.  
- 🤖 **AI Inference** – Powered by pre-trained CNN models: **ResNet152, VGG19, DenseNet121**.  
- 📊 **Multi-Class Classification** – Automatic classification into **7 skin lesion categories**.  
- 🔗 **Ensemble Learning** – Combines multiple models for robust decision-making.  
- 🧩 **Lesion Segmentation** – Attention U-Net for precise boundary detection.  
- 📚 **Awareness Content** – In-app educational resources for users.  

---

## 🛠 Tech Stack  
- **Android**: Java / Kotlin  
- **AI Models**: TensorFlow Lite (TFLite)  
- **Model Training**: Python (PyTorch/TensorFlow)  
- **Image Processing**: OpenCV  
- **Dataset**: [HAM10000](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000) (10,000+ dermoscopic images)  

---

## 📦 App Bundle Download  

The latest **app source** and **model files** are available in the [GitHub Releases](../../releases) section.  
Download both parts:  

- `SCapp_split.zip`  
- `SCapp_split.z01`  

Then extract them with a single command in your terminal:  unzip SCapp_split.zip

---
## 🎥 Demo  

A short video demo will be available soon.  
📂 Sample: `VIDEO-2025-04-22-15-00-28.mov`  

---

## 📊 Research Highlights  

This application was developed as part of the academic research study:  

**“Deep Learning-Based Skin Cancer Detection”**  
**Authors:** Andrew Bala Abhilash Polisetty, Siri Yellu, Akshay Krishna Varma Buddharaju  
**Advisor:** Dr. Sanghoon Lee  

- ✅ Implemented an **ensemble of ResNet152, VGG19, and DenseNet121**, achieving **89% classification accuracy**.  
- ✅ Integrated **Attention U-Net** for lesion segmentation, reaching **87% accuracy**.  
- ✅ Addressed dataset challenges such as **class imbalance and variability** in HAM10000 through **data augmentation and ensemble integration**.  

---

## 🙌 Acknowledgements  

We gratefully acknowledge the support of **Kennesaw State University**, our advisor, and collaborators whose contributions were vital to the success of this project.  

---

## 💡 Contact  

👤 **Akshay Krishna Varma Buddharaju**  
📩 [akshaykrishnavarma@gmail.com](mailto:akshaykrishnavarma@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/abuddhar/) | [GitHub](https://github.com/AKSHAYKRISHNAVARMA)  

👤 **Siri Yellu**  
📩 [siri.y0285@gmail.com](mailto:siri.y0285@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/siri-reddy-yellu) | [GitHub](https://github.com/SiriYellu)  

👤 **Andrew Bala Abhilash Polisetty**  
📩 [andrewbala99@gmail.com](mailto:andrewbala99@gmail.com)  
🔗 [LinkedIn](#) | [GitHub](#)  
