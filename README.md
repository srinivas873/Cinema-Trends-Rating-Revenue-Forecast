# 🎬 Cinema-Trends-Rating-Revenue-Forecast

## 📌 Overview
This project leverages **machine learning** to predict **movie ratings and revenues** using datasets from **IMDB** and **TMDB**. We implemented **Random Forest Regressor, XGBoost, and Neural Networks** to analyze and predict the success of movies before their release. The project includes a **web-based interactive interface** to input movie details and view predictions.

## 🚀 Features
- **Predicts movie ratings and revenues** using machine learning models.
- **Uses IMDB and TMDB datasets** for feature extraction.
- **Implements three ML models**: 
  - Random Forest Regressor
  - XGBoost
  - Neural Networks
- **Web interface for user interaction** and prediction visualization.

---

## 💂️ Dataset and Features
We used two primary datasets:

1. **IMDB Dataset**: Contains movie reviews and sentiment data.
2. **TMDB Dataset**: Includes metadata such as budget, genre, popularity, and revenue.

### **Key Features Used**
- 🎭 **Genres**
- 🎬 **Cast**
- 💰 **Budget**
- 📅 **Release Date**
- 🎢 **Popularity**
- 🎥 **Director**
- ⭐ **IMDB Ratings**
- 💵 **Revenue**

---

## ⚙️ Installation

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/yourusername/Movie-Rating-Revenue-Prediction.git
cd Movie-Rating-Revenue-Prediction
```

### **2️⃣ Create a Virtual Environment**
```bash
python -m venv env
source env/bin/activate    # For MacOS/Linux
env\Scripts\activate       # For Windows
```

### **3️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **4️⃣ Download the Dataset**
- Download **IMDB and TMDB** datasets from:
  - [IMDB Dataset](https://www.imdb.com/interfaces/)
  - [TMDB Dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata)
- Place them in the `data/` folder.

---

## 🏢 Model Training

### **1️⃣ Preprocess Data**
```bash
python preprocess.py
```

### **2️⃣ Train Models**
```bash
python train.py
```

### **3️⃣ Evaluate Models**
```bash
python evaluate.py
```

### **4️⃣ Run Web Interface**
```bash
streamlit run app.py
```

---

## 📊 Results & Model Performance

### **🔹 Random Forest Regressor**
| Metric | Ratings Model | Revenue Model |
|--------|--------------|--------------|
| MAE    | 0.5766       | $41.4M       |
| RMSE   | 0.7784       | $87.0M       |
| R²     | 0.5103       | 0.7149       |

### **🔹 XGBoost**
| Metric | Ratings Model | Revenue Model |
|--------|--------------|--------------|
| MAE    | 0.6059       | $43.5M       |
| RMSE   | 0.8214       | $102.7M      |
| R²     | 0.4548       | 0.6031       |

### **🔹 Neural Networks**
| Metric | Ratings Model | Revenue Model |
|--------|--------------|--------------|
| MAE    | 396,270.53   | $56.7M       |
| RMSE   | 676,133.98   | $101.6M      |
| R²     | -369M        | 0.6114       |

📌 **Conclusion:**  
- **Random Forest performed the best** for revenue predictions.
- **XGBoost had moderate success** but requires tuning.
- **Neural Networks underperformed** due to overfitting.

---

## 🎨 Web Interface
The project includes a **Streamlit-based UI** for user-friendly predictions.

### **🔹 Features**
- **📅 Input movie details** (genre, cast, budget, release date).
- **📊 Display predicted rating and revenue**.
- **💡 Visualize feature importance and prediction confidence intervals**.

To run the web interface:
```bash
streamlit run app.py
```

---

## 🔮 Future Enhancements
- **🔗 Incorporate social media trends** for better predictions.
- **🎬 Use critic reviews** as an additional feature.
- **🤖 Improve Neural Network models** with deep learning techniques.
- **🛠️ Deploy as a cloud-based API** for broader accessibility.

---

## 📜 References
1. Ahmad, I. S., Bakar, A. A., Yaakub, M. R., & Muhammad, S. H. (2020). A survey on machine learning techniques in movie revenue prediction. *SN Computer Science, 1(4), 235*.
2. Chakraborty, P., Zahidur, M., & Rahman, S. (2019). Movie success prediction using historical and current data mining. *International Journal of Computer Applications, 178(47), 1-5*.



Showcasing my passion for data science, predictive analytics, and innovative problem-solving. Let’s collaborate and create something impactful together! 💡
---

## 📬 Contact
📧 Email: srinivasnarayanaramm@email.com  
🔗 GitHub: https://github.com/srinivas873 
🔗 LinkedIn: https://www.linkedin.com/feed/
