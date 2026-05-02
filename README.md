🧠 Customer Segmentation using Boltzmann Machine (RBM)

📌 Objective

The objective of this project is to categorize customers based on their shopping habits using a Restricted Boltzmann Machine (RBM), an unsupervised deep learning model.

📊 Dataset

- Dataset: Online Retail Dataset
- Data Type: Transactional data
- Features: Customer ID, StockCode, Quantity, Price, Country

⚙️ Technologies Used

- Python
- NumPy & Pandas
- Scikit-learn
- Matplotlib

🔍 Project Workflow

1. Load dataset and clean data
2. Remove missing values and invalid entries
3. Encode categorical data (Country, StockCode)
4. Scale numerical features (Quantity, Price)
5. Transform data into binary user-item matrix
6. Train Restricted Boltzmann Machine (RBM)

🧹 Data Cleaning

- Removed missing Customer IDs and descriptions
- Removed cancelled transactions
- Filtered invalid quantities and prices

🔄 Data Preprocessing

- Label Encoding for categorical variables
- Standard Scaling for numerical features

🔢 Data Transformation

- Created user-item matrix
- Converted data into binary format (purchased / not purchased)

🧠 Model Used

- Restricted Boltzmann Machine (RBM)
- Unsupervised learning model

🏋️ Model Training

- Used BernoulliRBM from Scikit-learn
- Trained on binary transaction data

📈 Results

The model learns hidden patterns in customer purchase behavior and identifies customer segments based on item co-occurrence.

🔍 Observations

- Data cleaning significantly improves model quality
- Binary transformation helps capture purchase patterns
- RBM identifies latent customer groups

🚀 Future Improvements

- Use clustering algorithms (K-Means) on RBM output
- Apply recommendation systems
- Tune hyperparameters (n_components, learning_rate)

👨‍💻 Author

Avdhut Kale
