# Predictive-Maintenance-of-Industrial-Machines-using-Machine-Learning-Models
Predictive maintenance of machines using various machines learning models. 

An end-to-end Machine Learning pipeline designed to predict mechanical failures and classify failure types before they occur. This project leverages historical sensor logs (temperature, torque, rotational speed, and tool wear) to optimize maintenance scheduling, minimize unplanned downtime, and reduce operational costs in manufacturing environments.

## ⚙️ Key Features
* **Multi-Class Failure Classification:** Identifies specific failure modes, including Heat Dissipation, Power, Overstrain, Tool Wear, and Random Failures.
* **Feature Engineering & Selection:** Drops uninformative high-cardinality metadata (`UDI`, `Product ID`) to streamline model training.
* **Sensor Target Analytics:** In-depth evaluation of continuous sensor feeds against categorical operational failures.

## 📊 Dataset Structure
The dataset (`predictive_maintenance.csv`) contains 10,000 operational data points across the following attributes:
* **Air Temperature [K]**: Ambient temperature surrounding the machine.
* **Process Temperature [K]**: Internal temperature during operational cycles.
* **Rotational Speed [rpm]**: Spindle rotation frequency.
* **Torque [Nm]**: Torsional force exerted.
* **Tool Wear [min]**: Cumulative runtime strain on the machine tool.
* **Type:** Product quality variants (L, M, H).
* **Failure Type (Target):** The specific classification of mechanical failure (e.g., *Heat Dissipation Failure*, *Power Failure*, etc.).

## 🛠️ Installation & Setup

1. **Clone the repository:**
```bash
   git clone [https://github.com/your-username/Predictive-Maintenance-ML.git](https://github.com/your-username/Predictive-Maintenance-ML.git)
   cd Predictive-Maintenance-ML
