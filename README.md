# 📝 Automated Handwritten Text Recognition for Historical Archives

A web-based platform for automated recognition and transcription of historical handwritten documents, with a special focus on palm leaf manuscripts and regional scripts like Tamil. This project aims to preserve, digitize, and provide accessible digital copies of ancient records using cutting-edge computer vision and deep learning technologies.


---

## 🧾 About the Project

Historical documents, such as **palm leaf manuscripts**, are invaluable cultural artifacts containing centuries-old knowledge, religious scripts, scientific data, and literary works. However, they are highly susceptible to damage due to ink fading, material aging, and environmental factors. Traditional manual transcription is time-consuming and error-prone, particularly with diverse regional scripts and handwriting styles.

This project presents an **automated solution** using deep learning, OCR, and image processing techniques to recognize and transcribe text from these historical documents. The system is designed to work effectively with **Tamil scripts**, **Tamil numerals**, and manuscripts with noise and distortion.

---

## 🚀 Key Features

- 🖼️ **Image Preprocessing**: Includes binarization, noise reduction and line segmentation.
- 🔍 **OCR Engine**: Custom-trained deep learning models for handwritten Tamil character recognition.
- 🔢 **Tamil Numeral Detection**: Specialized support for recognizing Tamil digits.
- 🌐 **Web-based Platform**: Clean, user-friendly UI for uploading, processing and downloading results.
- 🏷️ **Annotation & Review Tools**:  Allows manual correction and verification.
- 📜 **Support for Palm Leaf Manuscripts**

---

## 🧑‍💻 Tech Stack

| Layer             | Technology                          |
|------------------|-------------------------------------|
| Frontend         | HTML, CSS, JavaScript |
| Backend          | Python, Flask               |
| OCR & ML         | TensorFlow , OpenCV        |
| Image Processing | OpenCV, Scikit-image, PIL           |
| Model Training   | CNN             |
| Database (optional) | PostgreSQL             |

---


## 📂 Dataset

The system can be trained using:

- Public datasets of Tamil handwritten characters (e.g., HP-HCD)
- Custom annotated palm leaf manuscript images
- Augmentation techniques to simulate real-world noise and wear

> **Note**: Due to data sensitivity, some datasets may not be included in the public repo.

---

## ⚙️ Installation

### Prerequisites

- Python 3.8+
- pip
- virtualenv (optional)
- Git

### Clone the Repository

```bash
git clone https://github.com/sptyogesh/Automated-Handwritten-Text-Recognition-for-Historical-Archives.Git

```
- Install Dependencies neccssery package

Start the Application
```bash
python app.py
```
Open your browser and go to: http://localhost:5000

🧪 Usage
Open the web platform.

- Upload a scanned image of a historical manuscript.

- The system will preprocess the image.

- Recognized text is displayed for review.

- Download the transcribed output as .txt or .csv.


🧩 Add handwriting style adaptation using Transfer Learning

🧾 Export to searchable PDF or structured XML

📈 Model performance dashboard (accuracy, confidence scores)

☁️ Cloud deployment with GPU acceleration

🤝 Contributing

- We welcome contributions! Here's how you can help:

- Report issues and bugs

- Suggest new features

- Submit pull requests

- To contribute: Fork the repository

- Create a new branch:

```bash
git checkout -b feature/your-feature
```
- Commit your changes

- Push to the branch:

```bash
git push origin feature/your-feature
```
- Create a Pull Request

🛡️ License
This project is licensed under the MIT License.

📬 Contact
If you have any questions or feedback, feel free to reach out.


