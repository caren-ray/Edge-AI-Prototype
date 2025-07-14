# 🌟 Edge AI Prototype: Image Classification with TensorFlow Lite

This project demonstrates how Edge AI can be used for real-time image classification. It uses a lightweight Convolutional Neural Network (CNN) model trained on the **Rock-Paper-Scissors** dataset and converts it to a TensorFlow Lite (TFLite) model suitable for edge devices like smartphones, Raspberry Pi, or microcontrollers.

---

## 📌 Project Goals

- ✅ Train an image classification model using TensorFlow.
- ✅ Convert the model to TensorFlow Lite format.
- ✅ Simulate Edge AI deployment (on Google Colab).
- ✅ Explain the benefits of Edge AI in real-time applications.

---

## 🧠 Tools & Libraries

- Python 3.x
- TensorFlow 2.x
- TensorFlow Datasets
- Matplotlib (for visualization)

---

## 🗂️ Dataset

- **Rock-Paper-Scissors** from [TensorFlow Datasets](https://www.tensorflow.org/datasets/catalog/rock_paper_scissors)
- 2,892 training images and 372 test images
- 3 classes: rock, paper, scissors

---

## 🚀 How to Run

1. Open the Colab Notebook: `edge_ai_prototype.ipynb`
2. Run all cells step-by-step.
3. The model will be trained, evaluated, and converted to `.tflite`.
4. Final model will be downloadable as `edge_ai_model.tflite`.

---

## 📊 Results

- **Test Accuracy**: ~92% (varies slightly depending on random init)
- **Model Format**: TFLite (`.tflite`)
- **Deployment Ready**: Yes, for real-time edge applications

---

## 💡 Why Edge AI?

Edge AI enables machine learning models to run **locally** on edge devices rather than sending data to the cloud. This leads to:

- ⚡ Low Latency: Faster decisions and responses
- 🔒 Enhanced Privacy: No need to transmit sensitive data
- 🌐 Offline Capability: Works without internet
- 🔋 Energy Efficiency: Optimized for low-power devices

---

## 📁 Files in this Repo

- `edge_ai_prototype.ipynb` – Google Colab notebook with training & conversion code.
- `edge_ai_model.tflite` – Trained and converted TFLite model.
- `README.md` – Project overview and instructions.

---

## 📌 Author

**Caren Rayon**  


---

## 📜 License

This project is open-source and available for educational use.

