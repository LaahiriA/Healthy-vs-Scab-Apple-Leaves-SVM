# Healthy-vs-Scab-Apple-Leaves-SVM

This project focuses on classifying Apple leaf images as **healthy** or **scab-infected** using Support Vector Machine (SVM) classifier.

---

## Dataset

The images are sourced from the **PlantDoc** dataset, which contains a total of 2,598 images across 13 plant species and 17 disease classes. For this project, only Apple leaf images are considered:

- **Apple Scab (infected) images:** 630  
- **Healthy Apple leaf images:** 800  

---

## Objective

To develop a classifier that accurately distinguishes between healthy Apple leaves and those infected with Apple Scab.

---

## Approach

- Applied **Digital Image Processing** techniques to extract relevant features from leaf images.
- Trained a **Support Vector Machine (SVM)** classifier on the extracted features.
- Evaluated the model's performance in classifying healthy vs. scab-infected leaves.

---

## Results

- The SVM classifier achieved an accuracy of **94.06%**.


---

## Tools and Technologies

- Python  
- OpenCV (`cv2`) for image processing  
- Mahotas for texture feature extraction  
- NumPy for numerical operations  
- scikit-learn for machine learning (SVM, LabelEncoder, MinMaxScaler)
- pandas for data manipulation and analysis  
- matplotlib for visualization and plotting  

---

## References

- PlantDoc dataset: [[Link to paper](https://dl.acm.org/doi/10.1145/3371158.3371196)]  
- SVM documentation: https://scikit-learn.org/stable/modules/svm.html

