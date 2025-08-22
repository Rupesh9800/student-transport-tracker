# 🚌 Student Transport Registration Tracker

This project is a **Student Transport Registration Tracker** that allows schools/colleges to manage student transport details, visualize distributions, and run simple machine learning predictions.

---

## 📂 Features

1. **CSV File Handling**
   - Initialize CSV with headers
   - Add (register) new students

2. **Data Analytics**
   - Count students per route
   - Generate route-wise student lists
   - Generate bus-wise student lists

3. **Visualization (Dashboard)**
   - Plot students per route
   - Plot students per bus

4. **Machine Learning**
   - Predict route from bus number using a Decision Tree Classifier
   - Show model accuracy

5. **Ethical & Bias Awareness**
   - Check for unbalanced student distributions across routes

---

## 📊 Dataset Format

The CSV file should have the following columns:

```csv
Student_ID,Name,Route,Bus_No
S101,Arjun,R2,B12
S102,Lavanya,R3,B13
S103,Rupesh,R2,B12
S104,Preethi,R3,B13
S105,Kiran,R4,B14
```

---

## ⚙️ Installation & Setup

1. Clone or download the repository.
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook student_transport_tracker.ipynb
   ```

---

## 🚀 Usage

- **Initialize CSV:** Creates file if not exists
- **Register students:** Adds student details to CSV
- **View reports:**
  - `count_students_per_route()`
  - `generate_route_list("R2")`
  - `generate_bus_list("B13")`
- **Visualize:**
  - `visualize_distribution()`
- **Machine Learning:**
  - `simple_ml_model()` → Predicts route from bus number
- **Bias Check:**
  - `bias_check()` → Detects route imbalance

---

## 📈 Example Output

- **Students per Route (table)**
- **Bar charts** for route and bus distribution
- **ML Model Accuracy:** `0.99` (example)
- **Bias Check:**
  ```
  Some routes are overloaded compared to others.
  ```

---

## 📌 Notes

- Ensure your CSV file follows the required format.
- Visualizations open inline when using Jupyter Notebook.
- Accuracy depends on dataset size and balance.
