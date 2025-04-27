### 🔍 Project Overview

Phishing websites are deceptive platforms designed to mimic legitimate sites, tricking users into divulging sensitive information such as passwords and credit card details. This project seeks to detect such malicious sites by analyzing various features extracted from URLs and webpage content, employing machine learning models to classify them as either legitimate or phishing. 

---

### 🧰 Repository Structure

The repository is organized into several key directories: ([Need Help with Feature Selection for Phishing Detection using ML]
- **`notebooks/`**: Contains Jupyter notebooks for feature extraction and model training.
- **`raw_datasets/`**: Houses raw data collected from various sources.
- **`extracted_csv_files/`**: Includes processed datasets ready for model training.
- **`Phishing website detection using UI/`**: Comprises the user interface components developed using FastAPI and Streamlit. s.

---

### 🧠 Machine Learning Approach

**Feature Extraction**: The project emphasizes extracting meaningful features from URLs and webpage content. Features include URL length, presence of special characters, use of HTTPS, and more. These features are crucial for training effective machine learning models. 

**Model Training**: Various classifiers have been employed, including: ([(PDF) Detection of Phishing Website Using Machine Learning and ...]
- **Random Forest**: Known for its robustness and accuracy in classification tasks.
- **Decision Tree**: Offers interpretability and simplicity.
The models are trained and evaluated using metrics such as accuracy, precision, recall, and F1-score to ensure reliable performance.

---

### 🖥️ User Interface

To make the detection system accessible, a user-friendly interface has been developed using FastAPI and Streamlit. This allows users to input URLs and receive immediate feedback on their legitimacy. The UI components are located in the `Phishing website detection using UI/` directory. 
---

### 📊 Evaluation Metrics

The project's models are evaluated using standard classification metrics:

- **Accuracy**: Measures the overall correctness of the model.
- **Precision**: Indicates the proportion of true positives among all positive predictions.
- **Recall**: Reflects the model's ability to identify all actual positives.
- **F1-Score**: Provides a balance between precision and recall. 
These metrics ensure a comprehensive assessment of the model's performance. 
---

### ✅ Strengths

- **Comprehensive Feature Set**: The project extracts a wide range of features, enhancing model accuracy.
- **Multiple Classifiers**: Utilizing different machine learning models allows for comparative analysis and optimization.
- **Interactive UI**: The user interface makes the tool accessible to non-technical users. 

---

### ⚠️ Areas for Improvement

- **Dataset Diversity**: Incorporating more diverse and up-to-date datasets could improve model generalizability.
- **Advanced Models**: Exploring deep learning techniques might enhance detection capabilities.
- **Real-Time Detection**: Implementing real-time URL scanning could make the tool more practical for end-users.

---

### 📌 Conclusion

The Phishing-Website-Detection project is a valuable contribution to cybersecurity efforts, offering a machine learning-based approach to identifying phishing websites. Its combination of comprehensive feature extraction, multiple classifiers, and an interactive user interface makes it a practical tool for both researchers and end-users. With further enhancements, it has the potential to become an even more robust solution in combating phishing attacks.

--- 
By- Vidhi Jaju
