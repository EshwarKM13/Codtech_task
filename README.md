# Codtech Internship Tasks

A collection of machine learning and deep learning projects developed using Google Colab. This repository contains four comprehensive tasks showcasing various ML techniques including classification, sentiment analysis, computer vision, and recommendation systems.

## 📋 Project Overview

This repository contains four Jupyter notebooks completed as part of an internship program, covering fundamental to intermediate machine learning concepts.

---

## 🚀 Projects

### 1. **Task 1: Decision Tree Classification on UCI Adult Income Dataset**
**File:** `CodtechTask1.ipynb`

#### Description
This project implements a Decision Tree Classifier to predict income levels (<=50K or >50K) using the UCI Adult Income Dataset. The project demonstrates the complete ML workflow from data loading to model evaluation.

#### Key Features
- **Dataset:** UCI Adult Income Dataset (32,561 records, 14 features)
- **Preprocessing:**
  - Data loading from UCI ML repository
  - Missing value handling using mode imputation
  - Label encoding for categorical features
  - Train-test split (70-30)

- **Model:** Decision Tree Classifier
- **Evaluation Metrics:**
  - Accuracy Score
  - Classification Report
  - Feature importance analysis

#### Libraries Used
```python
pandas, numpy, scikit-learn, matplotlib, seaborn
```

#### Key Insights
- Handles mixed data types (numerical and categorical)
- Demonstrates data preprocessing best practices
- Provides model performance metrics and classification reports

---

### 2. **Task 2: Sentiment Analysis with TF-IDF and Logistic Regression**
**File:** `codtechTask2.ipynb`

#### Description
This project implements a sentiment analysis pipeline that classifies customer reviews into three categories: positive, negative, and neutral. It leverages Natural Language Processing (NLP) techniques and machine learning for text classification.

#### Key Features
- **Text Preprocessing Pipeline:**
  - Lowercasing and special character removal
  - Tokenization
  - Stop word removal using NLTK
  - Lemmatization using WordNetLemmatizer

- **Feature Extraction:** TF-IDF Vectorization (max 5,000 features)
- **Model:** Logistic Regression with 1,000 iterations
- **Evaluation:**
  - Accuracy Score
  - Classification Report (precision, recall, F1-score)
  - Confusion Matrix visualization

#### Libraries Used
```python
pandas, scikit-learn, nltk, matplotlib, seaborn
```

#### Dataset
- Synthetic dataset of 10 customer reviews (demonstrative)
- Expandable to real-world datasets (e.g., Movie Reviews, Product Reviews)

#### Key Insights
- Demonstrates text preprocessing importance
- Shows TF-IDF feature extraction for NLP
- Illustrates classification metrics interpretation

---

### 3. **Task 3: Convolutional Neural Network (CNN) for Image Classification with CIFAR-10**
**File:** `CodtechTask3.ipynb`

#### Description
This project builds a Convolutional Neural Network using TensorFlow/Keras to classify images from the CIFAR-10 dataset into 10 object categories. It showcases deep learning fundamentals and computer vision techniques.

#### Key Features
- **Dataset:** CIFAR-10 (60,000 32x32 RGB images, 10 classes)
  - 50,000 training images
  - 10,000 test images
  - Classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck

- **Model Architecture:**
  - Conv2D layer (32 filters, 3x3 kernel, ReLU activation)
  - MaxPooling2D layer (2x2 pool size)
  - Conv2D layer (64 filters, 3x3 kernel, ReLU activation)
  - MaxPooling2D layer (2x2 pool size)
  - Conv2D layer (64 filters, 3x3 kernel, ReLU activation)
  - Total Parameters: 56,320

- **Preprocessing:**
  - Pixel normalization (0-1 range)
  - Image visualization

#### Libraries Used
```python
tensorflow, keras, numpy, matplotlib
```

#### Key Insights
- Demonstrates CNN architecture for image classification
- Shows convolutional and pooling layer effectiveness
- Illustrates deep learning model structure and parameter counting

---

### 4. **Task 4: Collaborative Filtering Recommendation System**
**File:** `CodTechTask4.ipynb`

#### Description
This project implements a collaborative filtering recommendation system using the MovieLens dataset. It demonstrates user-based similarity calculations and movie recommendations using the K-Nearest Neighbors algorithm.

#### Key Features
- **Dataset:** MovieLens ML-Latest-Small
  - User ratings data
  - 610 users and 193,609 ratings

- **Recommendation Approach:**
  - User-Movie matrix construction
  - Cosine similarity calculation
  - K-Nearest Neighbors (k=3) for finding similar users
  - Movie recommendations based on similar user preferences

- **Algorithm Flow:**
  1. Create user-item rating matrix
  2. Calculate user similarity using cosine similarity
  3. Train KNN model with cosine metric
  4. Find k nearest users to target user
  5. Recommend highly-rated movies from similar users

- **Evaluation:**
  - User similarity scores visualization
  - Average similarity metric
  - Recommendation quality assessment

#### Libraries Used
```python
pandas, numpy, scikit-learn, matplotlib, requests
```

#### Key Insights
- Demonstrates collaborative filtering concept
- Shows practical recommendation system implementation
- Illustrates similarity metrics and KNN application in RS

---

## 🛠️ Environment & Tools

### Platform
- **Google Colab** - All projects developed and tested on Google Colab
- **Python 3.x**

### Key Libraries
- **Data Processing:** pandas, numpy
- **Machine Learning:** scikit-learn
- **Deep Learning:** tensorflow, keras
- **NLP:** nltk
- **Visualization:** matplotlib, seaborn
- **Web Requests:** requests

---

## 📦 Installation & Setup

### Prerequisites
- Google Colab account (or Jupyter Notebook locally)
- Python 3.7+

### Running on Google Colab
1. Upload the `.ipynb` files to Google Drive
2. Open with Google Colab
3. Run cells sequentially (Shift + Enter)
4. Install missing dependencies using `!pip install package_name`

### Running Locally
```bash
# Clone the repository
git clone https://github.com/EshwarKM13/Codtech_task.git
cd Codtech_task

# Install dependencies
pip install -r requirements.txt

# Open Jupyter Notebook
jupyter notebook
```

---

## 📊 Key Concepts Covered

### Machine Learning
- ✅ Supervised Learning (Classification)
- ✅ Data Preprocessing & Feature Engineering
- ✅ Train-Test Split & Model Evaluation
- ✅ Classification Metrics (Accuracy, Precision, Recall, F1-Score)

### Natural Language Processing
- ✅ Text Preprocessing (Tokenization, Lemmatization, Stop Words)
- ✅ Feature Extraction (TF-IDF)
- ✅ Text Classification

### Deep Learning
- ✅ Convolutional Neural Networks (CNNs)
- ✅ Image Classification
- ✅ Neural Network Architecture Design

### Recommendation Systems
- ✅ Collaborative Filtering
- ✅ Similarity Metrics (Cosine Similarity)
- ✅ K-Nearest Neighbors
- ✅ User-Based Recommendations

---

## 📈 Results Summary

| Task | Model | Dataset | Key Feature |
|------|-------|---------|------------|
| Task 1 | Decision Tree | UCI Adult Income | Income Prediction |
| Task 2 | Logistic Regression | Synthetic Reviews | Sentiment Classification |
| Task 3 | CNN | CIFAR-10 | Image Recognition |
| Task 4 | KNN + Cosine Similarity | MovieLens | Movie Recommendations |

---

## 🎯 Learning Outcomes

After completing these projects, you will understand:

1. **Classification Tasks:** How to build and evaluate classifiers using decision trees
2. **NLP Pipelines:** Text processing and sentiment analysis workflows
3. **Deep Learning:** CNN architecture for image recognition
4. **Recommendation Systems:** Collaborative filtering and similarity-based recommendations
5. **Data Handling:** Preprocessing, feature engineering, and model evaluation

---

## 📝 Notes

- All notebooks are compatible with Google Colab
- External datasets are downloaded automatically (UCI ML, CIFAR-10, MovieLens)
- Cell outputs are included for reference
- Each task is standalone and can be run independently

---

## 👨‍💻 Author

**Eshwar KM**  
Codtech Internship Projects

---

## 📄 License

This project is open source and available under the MIT License.

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome! Feel free to open issues or pull requests.

---

## 📚 References

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/)
- [CIFAR-10 Dataset](https://www.cs.toronto.edu/~kriz/cifar.html)
- [MovieLens Dataset](https://grouplens.org/datasets/movielens/)
- [Scikit-Learn Documentation](https://scikit-learn.org/)
- [TensorFlow Keras Documentation](https://www.tensorflow.org/api_docs/python/tf/keras)
- [NLTK Documentation](https://www.nltk.org/)

---

**Happy Learning! 🚀**
