# 🐱🐶 Cat vs Dog Classifier using CIFAR-10

## ✅ Objective
Build a simple machine learning classifier to distinguish between **cats and dogs** using the **CIFAR-10** image dataset with a **Support Vector Machine (SVM)**.

---

## 📁 Dataset: CIFAR-10
- Built-in Keras dataset with 60,000 32x32 color images in 10 classes.
- We filter out only:
  - **Cats** → Label `3`
  - **Dogs** → Label `5`
- We convert these color images to grayscale and flatten them into 1D arrays for ML processing.

---

## 🧪 ML Process
### ✅ Steps Followed:
1. **Import Libraries**  
   Numpy, Matplotlib, CIFAR-10, SVM from scikit-learn.
   
2. **Load Dataset**  
   Merge training and test sets.

3. **Filter Cats & Dogs**  
   Only use labels `3` and `5`.

4. **Convert to Grayscale**  
   Reduce color info and flatten for SVM.

5. **Binary Labeling**  
   - Cat → `0`
   - Dog → `1`

6. **Train/Test Split**  
   80% for training, 20% for testing.

7. **Train SVM Model**  
   Using linear kernel, limited to first 2000 training samples for speed.

8. **Evaluate Model**  
   Accuracy printed and 5 predictions visualized.

---

## 📊 Output
- 🎯 Model Accuracy: ~**XX.XX%**
- ✅ Sample predictions shown using `matplotlib`.

---

## 📌 Requirements
- `tensorflow`
- `scikit-learn`
- `matplotlib`
- `numpy`

Install them using:
```bash
pip install tensorflow scikit-learn matplotlib numpy
