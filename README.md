# DC Motor Fault Detection using CNN and Kalman Filter

This repository contains research code and datasets for the detection and classification of open-circuit and short-circuit faults in DC motors using signal processing, Kalman filtering, and CNN-based classification models.

## 📄 Paper Abstract (Work in Progress)
> This paper introduces an effective methodology for fault detection and classification in DC motors by leveraging Kalman filtering for signal smoothing and Convolutional Neural Networks (CNNs) for intelligent classification. Simulations are conducted under three operating conditions: normal (healthy), short-circuit, and open-circuit faults. The sensor data (current and speed) from each scenario is filtered using a Kalman Filter to reduce noise. These filtered signals are segmented and labeled to form a dataset for training multiple classification models. Comparative evaluation shows CNN outperforms other techniques. The proposed system proves promising for real-time industrial diagnostics.
_Introduction_
DC motors are foundational components in industrial systems due to their controllability and robust design. Despite this, electrical faults such as short and open-circuits in armature windings can compromise their functionality. Prompt detection and classification of such issues are vital for reducing downtime and preventing equipment degradation. This paper details an approach that combines data filtering and machine learning for predictive maintenance.

## 🗂️ Project Structure

- `data/`: Contains datasets
- `src/`: Python source code (CNN, Kalman Filter, utilities)
- `notebooks/`: Jupyter notebooks for step-by-step execution
- `plots/`: Visualizations and result charts

## 📊 Results (Sample)
![Accuracy](plots/accuracy_comparison.png)

## 🛠️ How to Run

1. Clone the repo:
    ```bash
    git clone https://github.com/YOUR_USERNAME/dc-motor-fault-detection.git
    cd dc-motor-fault-detection
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run notebooks or Python scripts in `src/`

## 📌 Dependencies

List in `requirements.txt`:
