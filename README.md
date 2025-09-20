# Online-Food-Order-Prediction
This project uses **Machine Learning** to predict whether a customer is likely to order food online again based on their **demographics, income, occupation, and feedback**.   The model uses **Random Forest Classifier** to achieve accurate predictions.



README.md
# 🍔 Online Food Order Prediction

This project uses **Machine Learning** to predict whether a customer is likely to order food online again based on their **demographics, income, occupation, and feedback**.  
The model uses **Random Forest Classifier** to achieve accurate predictions.

---

## 📌 Features
- Predicts if a customer will place an order again (`Yes` / `No`)
- Uses demographic data such as Age, Gender, Marital Status, Occupation, Family Size, and Monthly Income
- Visualizes customer ordering behavior with interactive **Plotly** charts and **Seaborn** histograms
- Interactive input-based prediction for real-world simulation

---

## 📊 Dataset
Dataset used: **Customer Demographics and Food Ordering Behavior**  
📥 Download here: [Online Food Order Dataset (Kaggle)](https://www.kaggle.com/datasets/benroshan/factors-affecting-online-food-delivery)

Place the dataset in your working directory as `Age,Gender,Marital Status,Occupation.csv`.

---

## 🛠️ Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/online-food-order-prediction.git
cd online-food-order-prediction

2️⃣ Install Dependencies
pip install pandas numpy scikit-learn matplotlib seaborn plotly

3️⃣ Run the Script
python online_food_order_prediction.py

4️⃣ Provide Customer Details

Enter customer details (Age, Gender, Income, Feedback, etc.) when prompted, and the model will predict if they are likely to order again.

📈 Model Training

Preprocessing: Mapped categorical columns (Gender, Marital Status, Occupation, Feedback) to numerical values

Feature Selection: Used demographic, financial, and feedback data as input features

Model: RandomForestClassifier from sklearn.ensemble

Evaluation: Achieved high accuracy on test set (printed after training)

📊 Visualizations

Age vs. Orders – Histogram shows which age group orders most

Family Size vs. Orders – Analyzes ordering behavior by family size

Pie Charts – Show distribution of orders by Gender, Marital Status, Occupation, and Income level

🖼 Example
Enter the Age of the Customer: 25
Enter the Gender of the Customer (1 = Male, 0 = Female): 1
Marital Status of the Customer (1 = Single, 2 = Married, 3 = Not Revealed): 1
Occupation of the Customer (Student = 1, Employee = 2, Self Employeed = 3, House wife = 4): 2
Monthly Income: 25000
Educational Qualification (Graduate = 1, Post Graduate = 2, Ph.D = 3, School = 4, Uneducated = 5): 1
Family Size: 4
Pin Code: 110001
Review of the Last Order (1 = Positive, 0 = Negative): 1

Finding if the customer will order again: [1]


(Here, 1 = Yes, they will order again)

🔮 Future Improvements

Build a dashboard to visualize predictions for multiple customers

Deploy as a Flask / Streamlit web app for restaurants to use directly

Integrate with live customer data for automated recommendations

🤝 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss your ideas.

📜 License

This project is licensed under the MIT License.


---

Would you like me to include a **flowchart diagram (ML pipeline)** in the README (Data → Preprocessing → RandomForest → Prediction)?  
It would make the project visually appealing for GitHub visitors.


\

ChatGPT can make mistakes. Check important info. See Cookie Preferences.
