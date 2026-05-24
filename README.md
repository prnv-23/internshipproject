# internshipproject


# **Spam Email & SMS Classifier**

A self-contained Machine Learning project built using Python to identify and filter out unwanted spam text messages/emails from legitimate communications (**ham**). The project trains, optimizes, and evaluates multiple classic textual classification algorithms on the **Kaggle/UCI SMS Spam Collection Dataset** using Term Frequency-Inverse Document Frequency (**TF-IDF**) feature vectorization.

---

# Key Project Features
* **Production-Grade NLP Pipeline:** Cleans unformatted, raw text by processing character case, filtering out digit/punctuation noise, tokenizing, and stripping standard English stop words.
* **Offline-Ready Execution:** Engineered to run safely without structural internet dependencies or dynamic dataset resource downloads.
* **Multi-Algorithm Assessment:** Evaluates and compares three benchmark models: **Multinomial Naive Bayes**, **Logistic Regression**, and **Support Vector Machine (SVM)**.
* **High-Precision Deployment Configuration:** Optimized to achieve **100% Precision** using a linear-kernel SVM configuration to guarantee zero False Positives (legitimate messages mistakenly flagged as spam).


<img width="964" height="1029" alt="output" src="https://github.com/user-attachments/assets/1f25bafa-6dd5-4937-aaf1-024a02de6dd2" />

---

# End-to-End Workflow & Architecture

The system treats textual analysis as a sequential pipeline, converting unstructured strings into deterministic binary outcomes:

1. Text Preprocessing: Case mapping $\rightarrow$ Regex pattern purification $\rightarrow$ Token splitting $\rightarrow$ Stopword removal.
2. Feature Extraction (TF-IDF):Transforms text tokens into a statistical numerical feature matrix representing the top 3,000 highest-signal words.
3. Data Partitioning: Uses an 80/20 train/test split utilizing target stratification to handle severe category imbalances (86.6% Ham vs. 13.4% Spam).
4. Supervised Training & Evaluation: Fits multiple statistical classifiers and returns exact comparative matrices.

---

**Face Recognition Attendance System**

An AI-based attendance system that uses face recognition to automatically detect and mark attendance in real-time using a webcam.

 Features
- Real-time face detection and recognition
-Deep learning-based face embeddings (FaceNet)
-Automatic attendance logging (CSV file)
-Fast and contactless system
-Simple and easy-to-use interface


<img width="676" height="425" alt="face recognition output" src="https://github.com/user-attachments/assets/b3e6ef55-d0a9-40a2-b0a3-f6d6b653369a" />
<img width="692" height="428" alt="terminal output" src="https://github.com/user-attachments/assets/5f7e0f14-9da1-4d83-a8d2-65ed84b947fe" />
<img width="677" height="396" alt="attendance log" src="https://github.com/user-attachments/assets/38912c59-9f10-4677-b63a-c4856f669b69" />


