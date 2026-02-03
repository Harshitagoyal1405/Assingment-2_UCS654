# Assingment-2_UCS654 (Sampling)


## 📂 Dataset
- **Source**: [Credit Card Dataset](https://github.com/AnjulaMehto/Sampling_Assignment/blob/main/Creditcard_data.csv)
- **Original Distribution**: 
  - Class 0: 763 samples
  - Class 1: 9 samples
- **Balanced Distribution**: 
  - Class 0: 763 samples
  - Class 1: 763 samples (after Random Over Sampling)
- **Total Samples**: 1526

## 🔬 Methodology

### Sampling Techniques Used
| Technique | Description |
|-----------|-------------|
| **Sampling1** | Simple Random Sampling - Random selection with equal probability |
| **Sampling2** | Systematic Sampling - Selection at regular intervals |
| **Sampling3** | Stratified Sampling - Maintains class distribution |
| **Sampling4** | Cluster Sampling - Selection based on clusters |
| **Sampling5** | Bootstrap Sampling - Sampling with replacement |

### Machine Learning Models
| Model | Algorithm |
|-------|-----------|
| **M1** | Logistic Regression |
| **M2** | Decision Tree Classifier |
| **M3** | Random Forest Classifier |
| **M4** | Support Vector Machine (SVM) |
| **M5** | K-Nearest Neighbors (KNN) |

## 📊 Results

### Accuracy Comparison Table

|       | Sampling1 | Sampling2 | Sampling3 | Sampling4 | Sampling5 |
|-------|-----------|-----------|-----------|-----------|-----------|
| **M1** | 89.5 | 89.0 | 92.5 | 89.5 | 90.5 |
| **M2** | 97.5 | 96.0 | 95.0 | 96.0 | 97.0 |
| **M3** | 99.5 | 99.0 | 100.0 | 99.5 | 99.5 |
| **M4** | 76.0 | 66.5 | 68.0 | 64.5 | 74.0 |
| **M5** | 90.5 | 88.0 | 89.0 | 88.0 | 91.5 |

### Best Sampling Technique for Each Model

| Model | Model Name | Best Sampling | Accuracy (%) |
|-------|------------|---------------|--------------|
| M1 | Stratified Sampling | Sampling3 | 92.50% |
| M2 | Simple Random Sampling | Sampling1 | 97.50% |
| M3 | Stratified Sampling | Sampling3 | 100.00% |
| M4 | Simple Random Sampling | SamplingX | 76.00% |
| M5 | Bootstrap Sampling | Sampling5 | 91.50% |

### 🏆 Overall Best Combination
- **Model**: M3 (Random Forest Classifier)
- **Sampling Technique**: Sampling3
- **Accuracy**: 100.00%
