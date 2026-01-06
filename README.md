# MACHINE LEARNING-DRIVEN CLASSIFICATION OF ELECTROCHEMICAL SYSTEM COMPATIBILITY: THE ROLE OF DIELECTRIC CONSTANT

📌 Project Overview
This project applies machine learning classification models to predict the compatibility of electrochemical material systems using physicochemical properties, with a special focus on the dielectric constant. The goal is to support material screening and system design in energy-related electrochemical applications.
🏆 Presented on 1st International Conference on Science and Humanities for Sustainable Development (ICSHSD- 2025), DUET (Poster Presentation)
<img width="863" height="141" alt="image" src="https://github.com/user-attachments/assets/541d62eb-a922-4abb-a836-5fdbd1750aea" />


👤 Author
Saidul Islam | MS Research Fellow | Machine Learning & Chemometrics Enthusiast | M.Sc. in Inorganic Chemistry | Hajee Mohammad Danesh Science and Technology University, Dinajpur-5200

🔬 Dataset
Source: Public Kaggle Dataset
Samples: 4,252 material combinations
Features: 12 physicochemical & electronic properties
Target: Compatibility class

⚙️ Models Implemented
Support Vector Machine (SVM)
Random Forest (RF)
K-Nearest Neighbors (KNN)

All models were:
Standardized using StandardScaler
Optimized via GridSearchCV
Validated using 7-fold cross-validation
Evaluated on an 80:20 train–test split

📊 Key Results
![Uploading image.png…]()



✔ SVM outperformed all models, showing strong generalization and low bias.

🔍 Key Findings

Dielectric constant is the most influential feature (permutation importance).
Pearson correlation shows a moderate positive relationship with compatibility (r = 0.58).
Results highlight ML’s potential for rapid material compatibility screening.

🛠️ Tools & Libraries
Python
scikit-learn
NumPy, Pandas
Matplotlib, Seaborn

🚀 Applications

Electrochemical system design
Energy storage materials screening
Data-driven materials science research
