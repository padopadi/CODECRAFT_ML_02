# CODECRAFT\_ML\_02: Regression Model for House Price Prediction 🏡📊

This project is part of my internship at **CodeCraft**. The task was to build a regression model that predicts house prices based on features such as square footage, number of bedrooms, and bathrooms.

## 📁 Project Structure

```
├── data/                  # Dataset used for training
│   └── house_prices.csv
├── CODECRAFT_ML_02.ipynb  # Jupyter Notebook with full workflow
├── README.md              # Project documentation
├── requirements.txt       # List of Python packages used
└── LICENSE                # MIT License
```

## 🧠 Objective

To build and evaluate a **Linear Regression Model** using scikit-learn to predict housing prices. Key steps include:

* Exploratory Data Analysis (EDA)
* Feature Engineering
* Model Training
* Evaluation using MSE and R² Score

## 📊 Results

After performing K-Means clustering, the following results were obtained:

- **Optimal Number of Clusters (k):** 5  *(determined using the Elbow Method)*
- **Final Inertia:** 7894.32
- **Cluster Centers:**
  - Center 0: [45.1, 60.3]
  - Center 1: [85.4, 20.1]
  - ...

A visual representation of the clustered data was also created, showing the separation between customer segments based on Annual Income and Spending Score.


![Elbow Method]

![Screenshot 2025-07-08 213053](https://github.com/user-attachments/assets/6287abf0-c5f8-46e7-8700-4817b33d662b)

![Cluster Visualization]

![Screenshot 2025-07-08 213004](https://github.com/user-attachments/assets/2039b445-939b-4515-a72d-63e7c3f423d8)


## 🛆 Dependencies

Install all dependencies using:

```bash
pip install -r requirements.txt
```

## 🔗 Dataset

Dataset is included in the `/data` folder and was used solely for this project.

## 🛠️ Tools Used

* Python
* NumPy
* Pandas
* Matplotlib / Seaborn
* scikit-learn

## 📝 License

This project is licensed under the [MIT License](./LICENSE) — feel free to use, modify, and distribute it with attribution.

## 👨‍💻 Author

**Krishna Chopra**  
Intern @ CodeCraft  
[LinkedIn Profile](https://www.linkedin.com/in/yashika-sharma-906932351)

[Github Profile](https://www.github.com/padopadi)

---

> This is the second project of my internship at CodeCraft under the domain of Machine Learning.
