# Smart Parking Management System 🚗📊

This project presents a Smart Parking Management System using Industrial Internet of Things (IIoT) and machine learning to predict and optimize parking availability. It utilizes sensor data to provide real-time parking slot occupancy and predictive analytics to improve parking efficiency.

## 📁 Project Structure

- `Smart_Parking_management(coding).ipynb` — The main Jupyter notebook with data analysis, preprocessing, modeling, and results.
- `IIoT_Smart_Parking_Management datasets (1).csv` — The dataset used in this project, containing timestamped parking slot occupancy data and sensor readings.

## 📊 Dataset Overview

The dataset includes:
- **Timestamp** — Date and time of the reading
- **Slot IDs** — Each row indicates a reading from various parking slots
- **Sensor data** — Indicates whether a slot is occupied (`1`) or free (`0`)

## 🚀 Features Implemented

- **Data Cleaning & Preprocessing**: Handling missing values and formatting timestamps.
- **Visualization**: Trends of parking slot usage over time.
- **Machine Learning**:
  - Classification model (e.g., Decision Tree, Logistic Regression) to predict slot availability.
  - Model evaluation using accuracy, precision, recall, and confusion matrix.

## 🛠️ Technologies Used

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## 🧠 How to Run

1. Clone or download the repository.
2. Open the notebook using Jupyter:
   ```bash
   jupyter notebook Smart_Parking_management(coding).ipynb
   ```
3. Run all cells to reproduce the analysis and model predictions.

## 💡 Future Improvements

- Integration with a live sensor feed.
- Web dashboard for real-time slot availability.
- Advanced ML models for better prediction accuracy.
- Support for mobile app integration.

## 👨‍💻 Author

Made by [Your Name] — a project for applying IIoT in smart city parking systems.
