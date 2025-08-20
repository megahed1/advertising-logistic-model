# 📊 Logistic Regression on Advertising Dataset

This project applies **Logistic Regression** to predict whether a user will **click on an online advertisement** based on demographic and usage information.

---

## 📂 Dataset
The dataset contains the following features:
- **Daily Time Spent on Site**: Time spent by the user on the website (minutes).
- **Age**: Age of the user.
- **Area Income**: Average income of the user's geographical area.
- **Daily Internet Usage**: Average minutes a user spends on the Internet per day.
- **Ad Topic Line**: Headline of the advertisement.
- **City, Country**: User’s location.
- **Male**: Gender indicator (1 = Male, 0 = Female).
- **Timestamp**: Date and time of the activity.
- **Clicked on Ad**: Target variable (1 = Clicked, 0 = Did not click).

---

## ⚙️ Steps Performed

### 1. Data Exploration (EDA)
- Created histograms (e.g., Age distribution).
- Visualized relationships using `jointplot`:
  - **Age vs. Area Income**
  - **Age vs. Daily Time Spent on Site** (KDE distribution)
  - **Daily Time Spent on Site vs. Daily Internet Usage**
- Created a **pairplot** with hue = `Clicked on Ad`.

### 2. Data Preparation
- Selected relevant numerical features.
- Split the dataset into **Training** and **Testing** sets.

### 3. Model Building
- Implemented **Logistic Regression** using `sklearn`.
- Trained the model on training data.

### 4. Model Evaluation
- Evaluated predictions using:
  - **Confusion Matrix**
  - **Classification Report**
  - **Accuracy Score**

---

## 🛠️ Tools & Libraries
- **Python**
- **Pandas** for data handling  
- **Matplotlib / Seaborn** for visualizations  
- **Scikit-learn** for model building & evaluation  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Advertising-Logistic-Regression.git
