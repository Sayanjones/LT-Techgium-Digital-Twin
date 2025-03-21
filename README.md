# Digital Twin(Swing Machine)

This project implements a **Digital Twin** model for a **swing machine in the textile industry**, using simulated data for Engineering Technology (ET), Operational Technology (OT), and Information Technology (IT) to predict machine behavior and visualize key metrics.

---

## 📊 Project Overview

![Swing Machine Overview](assets/swing-machine.png)

- **Goal:** Build a model that predicts machine requirements and visualizes parameters like torque, speed, vibration, and power.
- **Approach:**
  - ET, OT, and IT data generated using mathematical formulas.
  - Applied multiple regression models to analyze and predict machine performance.
  - Visualized results using Streamlit.

---

## Tech Stack

- **Python Libraries:**
  - `pandas` - Data manipulation
  - `numpy` - Numerical computation
  - `matplotlib` - Plotting
  - `sklearn` - Machine learning models
  - `streamlit` - Web application

---

## Features

- Visualizes ET, OT, and IT data using bar charts and line graphs.
- Trains multiple models and selects the best using R-squared and MSE metrics.
- Predicts torque, vibration, and power for varying machine parameters.
- Allows user input to predict power dynamically.

---

## Installation

1. **Clone the repository:**
```bash
https://github.com/your-username/swing-machine-digital-twin.git
```

2. **Navigate to the project directory:**
```bash
cd swing-machine-digital-twin
```

3. **Install required dependencies:**
```bash
pip install -r requirements.txt
```

---

## Run the Application

```bash
streamlit run app.py
```

---

## Dataset

The dataset is generated using mathematical formulas to simulate ET, OT, and IT data. It contains:
- **ET Data:** Speed, Torque, Power
- **OT Data:** Vibration, Temperature
- **IT Data:** Historical machine logs

---

## How It Works

1. **Load Data:** ET, OT, and IT data are loaded dynamically.
2. **Data Preprocessing:**
   - Handles missing values.
   - Scales and normalizes data.
3. **Model Training:**
   - Applies regression models for predictions.
   - Compares models based on performance metrics.
4. **Visualization:**
   - Plots graphs for metrics like R-squared and MSE.
   - Displays bar graphs comparing target variables.

---

## Model Evaluation

- **Metrics Used:**
  - R-squared (R²)
  - Mean Squared Error (MSE)

---

## Usage

1. **Visualize Data:**
   - Select the target parameter to analyze.
   - Observe bar charts for performance.
2. **Predict Power:**
   - Input speed to get real-time power predictions.

---

## 📂 Project Structure
```
📦 swing-machine-digital-twin
├── 📂 data
├── 📂 models
├── 📂 utils
├── 📄 app.py
├── 📄 requirements.txt
└── 📄 README.md
```

---

## 🤝 Contributing

Contributions are welcome! :))

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Submit a pull request.

---

## 📧 Contact

For questions or collaborations, feel free to reach out:
- 📧 Email: [your-email@example.com](mailto:your-email@example.com)
- 💼 LinkedIn: [Your LinkedIn](https://www.linkedin.com/in/yourprofile)

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

