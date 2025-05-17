# 🚦 Traffic Volume Prediction with Deep Learning (PyTorch)

![Traffic](traffic.png)

This project applies **deep learning techniques using PyTorch** to predict hourly traffic volume. The goal is to support solutions for **road congestion, urban planning, and smarter commutes** by building a predictive model that learns from weather, time, and holiday data.

> 🧠 Developed as part of a DataCamp challenge on time-series and deep learning.

---

## 📊 Dataset Description

The dataset, sourced from the **UCI Machine Learning Repository**, includes hourly traffic data on an interstate highway in Minnesota, USA. It contains both numerical and categorical features like temperature, weather conditions, and holidays.

### 🎯 Target Variable
- `traffic_volume`: Number of vehicles passing a specific location per hour.

### 📁 Data Files
- `train_scaled.csv`
- `test_scaled.csv`

These datasets are preprocessed and normalized.

---

## 🛠️ Project Tasks

### ✅ Build a Deep Learning Model
A PyTorch model was built to predict traffic volume. It is saved as:

```python
traffic_model
```

---

### 📉 Train and Evaluate the Model
The model was trained using a suitable loss function. The final training loss is:

```python
final_training_loss  # Tensor, expected to be < 20
```

---

### 🔍 Test the Model
Predictions were generated on the test set and evaluated using Mean Squared Error (MSE):

```python
test_mse  # Float tensor
```

---

## 🧪 Technologies Used

- Python 3.x
- PyTorch
- Pandas & NumPy
- Matplotlib & Seaborn

---

## 📂 Repository Structure

```bash
.
├── data/                  # Scaled training and test CSV files
├── notebook.ipynb         # Main notebook with model training & evaluation
├── traffic.png            # Header image
├── README.md              # Project overview
└── models/                # (Optional) Saved PyTorch model
```

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/traffic-volume-prediction.git
   cd traffic-volume-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook notebook.ipynb
   ```

---

## 👨‍💻 Author

**Your Name**  
📧 your.email@example.com  
🔗 [LinkedIn](https://linkedin.com/in/yourprofile)

---

## 📃 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## 🌟 Motivation

Accurate traffic prediction enables:
- 🚘 Less congestion
- 🛣️ Better infrastructure planning
- 📅 Smarter commutes

Let’s use deep learning to make traffic more predictable — and life more manageable.