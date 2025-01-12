## Anomaly Detection Algorithm for Computer Internal Features

This repository contains a comprehensive anomaly detection algorithm designed to analyze and identify anomalies in computer internal features such as:
- CPU usage
- Temperature
- Battery status
- Memory usage
---
The dataset comprises **1GB of synthetic multivariate time series data**, collected from the internal features of a computer. It includes **8,712,000 samples**, intentionally augmented with extreme values to test and evaluate the performance of the anomaly detection algorithms.
## Algorithms Used
1. **Z-Score Method**:
   - Detects anomalies by calculating the standard score of each data point.
   - Data points with a z-score above or below a specified threshold are flagged as anomalies.
    
2. **Interquartile Range (IQR) Method**:
   - Identifies anomalies by analyzing the interquartile range of the data.
   - Data points falling outside the lower and upper bounds (calculated using the IQR) are considered anomalies.
### Visualization
The anomalies detected by the z-score method are visualized to provide clear insights into the data patterns and deviations. The visualizations highlight anomalies within the multivariate time series data for easier interpretation.

## Key Features
- Handles large-scale multivariate time series data effectively.
- Implements robust statistical methods for anomaly detection.
- Includes synthetic data with extreme values to test the reliability of the model.
## Applications
1. **System Monitoring**: Continuously monitor system performance and detect irregularities in real-time.
2. **Security**: Detect abnormal behavior that may indicate security breaches or potential threats.  
3. **Performance Optimization**: Gain insights into resource usage patterns and optimize system performance.
## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/Onnome-Joseph/Anomaly-detection.git
   ```
2. Navigate to the repository:
   ```bash
   cd Onome-Joseph
   ```
3. Run the anomaly detection script:
   ```bash
   python src/anomaly_detection.ipynb
   ```
4. View the visualizations in the `visualizations/` folder.

## Future Work

- Extend the algorithm to include machine learning-based anomaly detection techniques.
- Integrate real-time data streaming and detection.
- Explore additional visualization techniques for better data analysis.

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request for any improvements or suggestions.

