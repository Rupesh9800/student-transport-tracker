# 🚌 Student Transport Tracker

A Python + CSV based project for managing **student transport registration** in colleges.  
This system allows students to register their details and helps administrators assign them to specific routes and buses.  
It also supports **querying, counting, and visualizing route-wise and bus-wise distributions** using Jupyter Notebook.  

---

## 📌 Repository Information

- **Repo Name:** `student-transport-tracker`  
- **Description:** A Python project for managing student transport registration with CSV storage, queries, and route-wise visualizations.  
- **Tags/Topics:** `python`, `csv`, `data-visualization`, `jupyter-notebook`, `transport-management`, `student-system`, `college-project`  

---

## 📌 Features

✅ Register new students with details: `Student_ID`, `Name`, `Route`, `Bus_No`  
✅ Store student data in **CSV format**  
✅ Query students by **Route** or **Bus**  
✅ Generate reports:  
- Route-wise student list  
- Bus-wise student list  
- Student count per Route / Bus  
✅ Data visualization with **Matplotlib + Seaborn**:  
- Students per Route (Bar Chart)  
- Students per Bus (Bar Chart)  
✅ Machine Learning (Decision Tree):  
- Predict **Route from Bus Number**  
- Show model accuracy  
✅ Bias Check:  
- Detect overloaded routes vs balanced routes  

---

## 📂 Project Structure

```
student-transport-tracker/
│
├── student_transport_tracker.ipynb   # Main Jupyter Notebook
├── student_transport_dataset.csv     # Sample dataset (with demo records)
├── README.md                         # Documentation
```

---

## ⚙️ Installation

Clone the repository:  

```bash
git clone https://github.com/your-username/student-transport-tracker.git
cd student-transport-tracker
```

Install dependencies:  

```bash
pip install pandas matplotlib seaborn scikit-learn
```

---

## ▶️ Usage

### In Jupyter Notebook  
Open `student_transport_tracker.ipynb` and run the cells.  

### Example Functions  

```python
# Show first 10 rows from dataset
import pandas as pd
df = pd.read_csv("student_transport_dataset.csv")
df.head(10)

# Get Route-wise student list
generate_route_list("R2")

# Get Bus-wise student list
generate_bus_list("B12")

# Count students per route
count_students_per_route()

# Plot students per route and bus
visualize_distribution()

# Run ML Model
simple_ml_model()

# Check bias in routes
bias_check()
```

---

## 📊 Sample Visualizations

📌 **Students per Route (Bar Chart)**  
📌 **Students per Bus (Bar Chart)**  

---

## 🔮 Future Improvements

- Add GUI with **Tkinter / Streamlit**  
- Integrate database (**SQLite/MySQL**) instead of CSV  
- Add student login portal with authentication  
- Add route optimization suggestion system  

---

## 👩‍💻 Author

**Rupesh Varma**
