# Augenblick2025_Status200

# Anomaly Detection and Predictive Maintenance

This project focuses on anomaly detection in industrial sensor data and predictive maintenance using multimodal data fusion. It implements an early warning system, anomaly detection models, and a time-to-failure prediction mechanism, all visualized through an interactive dashboard.

## Installation

Clone the repository and install dependencies:

bash
git clone https://github.com/Jatin-gorana/Augenblick2025_Status200.git
cd anomaly-detection
pip install -r requirements.txt


## Dataset

Condition monitoring of hydraulic systems: https://archive.ics.uci.edu/dataset/447/condition+monitoring+of+hydraulic+systems

## Features

- *Data Preprocessing*
  - Normalization of time-series data
  - Feature extraction from different sensor modalities
  - Handling missing values and outliers

- *Anomaly Detection*
  - Supervised detection for known failures
  - Unsupervised detection for novel anomalies

- *Time-to-Failure Prediction*
  - Predicts remaining useful life based on sensor data
  - Provides maintenance recommendations based on conditions

- *Dashboard and Visualization*
  - Interactive UI for real-time monitoring
  - Cross-modal visualization of sensor relationships
  - Graphs for false positive/negative rates



## Visualization Examples

- *Early Warning System*: Displays normal, warning, and critical conditions.
- *Anomaly Detection Results*: Highlights potential and severe anomalies.
- *Time-to-Failure Prediction*: Estimates remaining useful life and suggests actions.
- *False Positive/Negative Monitoring*: Tracks detection accuracy.

## Recommended Maintenance Actions

Based on sensor conditions, the system provides actionable insights, such as:
- Checking for minor leaks and lubrication in warning conditions.
- Immediate shutdown and inspection in critical conditions.
- Routine monitoring when all parameters are normal.

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss.
