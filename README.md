# Sonar-Mine-vs-Rock-Model

This project uses supervised machine learning to classify sonar signals as either **mines** or **rocks** based on data from the UCI Machine Learning Repository. The model is trained using a deep neural network (Keras Sequential model) and evaluated for accuracy and real-world prediction capability.

---

## 📌 About the Dataset

- **Source**: UCI Machine Learning Repository  
- **Samples**: 208 sonar signal records  
- **Features**: 60 continuous attributes (signal energy values)  
- **Target**:  
  - `M` = Mine  
  - `R` = Rock  

---

## 📂 Project Structure

```
Sonar-Mine-vs-Rock-Model/
├── Sonar_Mine_vs_Rock_Model.ipynb       # Main Jupyter notebook with full ML pipeline
├── sonar_dataset.csv                            # Dataset file
├── requirements.txt                     # Python dependencies
└── README.md                            # Project documentation
```

---

## ⚙️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- TensorFlow / Keras

---

## 🧠 Workflow Overview

1. **Data Loading**  
   - Load sonar_dataset.csv
2. **Data Exploration**  
   - Check shape, types, class distribution
3. **Label Encoding**  
   - Encode ‘M’ and ‘R’ to numerical values
4. **Train-Test Split**  
   - 75% training, 25% testing
5. **Model Training**  
   - Keras Sequential Neural Network
6. **Evaluation**  
   - Accuracy on training and test data
7. **Prediction on New Data**  
   - Custom sonar input tested on model

---

## 📈 Model Performance

| Metric   | Value     |
|----------|-----------|
| Accuracy | 90%       |
| Model    | Keras Sequential (Deep Neural Network) |

---



## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/9mithun9/Sonar-Mine-vs-Rock-Model.git
cd Sonar-Mine-vs-Rock-Model
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch the Notebook

```bash
jupyter notebook Sonar_Mine_vs_Rock_Model.ipynb
```

---

## 📜 License

This project is under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

**Mithun Marshal**  
🔗 GitHub: [@9mithun9](https://github.com/9mithun9)

---

## 📚 Reference

- [UCI Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks))
- [Keras Documentation](https://keras.io/)
