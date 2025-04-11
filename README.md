# 🐟 FishML

**FishML** is a machine learning project aimed at diagnosing fish diseases through image classification. By leveraging convolutional neural networks (CNNs), the project supports fish farmers and aquaculture professionals with early detection and monitoring of fish health.

---

## 📌 Project Overview

The goal of **FishML** is to accurately classify images of fish into two categories:

- ✅ **Healthy**
- ⚠️ **Diseased**

This tool can be used for:

- 🧪 **Early Disease Detection**
- 🌊 **Aquaculture Stock Monitoring**
- 🎓 **Educational Demonstrations for ML in Agriculture**

---

## 🧠 Features

- 🔍 **Image Classification** via CNN
- ⚙️ **Modular Python Script** (no notebooks required)
- 📊 **Visual Evaluation Tools**: Confusion matrix, accuracy curves, F1 scores
- 🔄 **Easily Extensible** for more disease categories or transfer learning

---

## 🛠️ Installation

### 1. Clone the Repository
```bash
git clone https://github.com/VarunP2304/FishML.git
cd FishML
```

### 2. (Optional) Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

> 🐍 **Python 3.6+ required**

---

## 📂 Dataset

To prepare the dataset:

1. Download or collect images of healthy and diseased fish.

2. Organize them as:

```
Dataset.csv/
🔼── training_set/
├🔼── healthy/
└🔼── diseased/
🔼── validation_set/
├🔼── healthy/
└🔼── diseased/
🔼── testing_set/
 ├🔼── healthy/
 └🔼── diseased/
```

> ⚠️ The folder is named `Dataset.csv` just to match the code — it's actually a directory, not a file.

---

## 🚀 Usage

Run the full training and evaluation pipeline from the terminal:

```bash
python main.py
```

This will:

- Load and preprocess the images.
- Train a CNN on the training set.
- Evaluate performance on the validation set.
- Display a classification report, confusion matrix, and F1 score.

---

## 📈 Model Evaluation

The script automatically shows:

- 📉 **Training vs. Validation Accuracy**
- 📋 **Classification Report** (Precision, Recall, F1)
- 📌 **Confusion Matrix**
- ⭐ **Weighted F1 Score**

---

## 🤝 Contributing

Want to improve FishML?

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit and push your changes.
4. Submit a pull request!

We welcome new features, bug fixes, or new disease-class support.

---

## 📄 License

MIT License. See [LICENSE](LICENSE) for details.

---

## 🙏 Acknowledgments

Big thanks to **kidscoots101** for their original work that inspired this project:
[https://github.com/kidscoots101/FishML/tree/main](https://github.com/kidscoots101/FishML/tree/main)

