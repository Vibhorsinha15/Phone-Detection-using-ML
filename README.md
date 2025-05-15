# 📱 Phone Usage Detection from Images using Machine Learning

This project detects whether a person is using a **mobile phone** in an image using a Convolutional Neural Network (CNN). It helps in monitoring distracted behavior (e.g., drivers using phones) for safety and surveillance applications.

---

## 🧠 Objective

To build a machine learning model that classifies images into two categories:
- **Phone** (person is using a phone)
- **No Phone** (person is not using a phone)

---

## 🛠️ Tech Stack

- **Language**: Python
- **Libraries**:
  - TensorFlow / Keras (for deep learning)
  - OpenCV (for image preprocessing)
  - NumPy, Matplotlib, Pandas
  - Scikit-learn (for metrics & evaluation)

---

## 🧪 Workflow

1. **Dataset Preparation**
   - Images labeled as `phone` and `no_phone`
   - Preprocessing: resizing, normalization

2. **Model Architecture**
   - Custom CNN model with Conv2D, MaxPooling, and Dense layers
   - Trained to minimize binary cross-entropy loss

3. **Training & Evaluation**
   - Training/Validation split
   - Accuracy and loss tracked over epochs
   - Confusion matrix and classification report for performance analysis

4. **Testing**
   - Run predictions on new images
   - Visual output showing predictions

---

## 📊 Results

- High classification accuracy achieved on test data.
- Model successfully distinguishes between phone and no-phone scenarios.
- Can be extended for real-time detection (video feed/CCTV).

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/phone-detection-ml.git
   cd phone-detection-ml
