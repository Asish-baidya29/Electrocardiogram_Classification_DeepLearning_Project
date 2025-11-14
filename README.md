# ECG Classification using CNN–LSTM

A hybrid deep learning model that classifies ECG signals by combining **Convolutional Neural Networks (CNN)** for spatial feature extraction and **Long Short-Term Memory (LSTM)** networks for temporal pattern recognition. Built with PyTorch and trained on the MIT-BIH Arrhythmia Database.

---

## Features

- **Hybrid CNN–LSTM architecture** combining spatial and temporal modeling
- **PyTorch implementation** with modular, readable code
- **Complete preprocessing pipeline** for ECG signal processing
- **Comprehensive evaluation** with accuracy metrics, confusion matrices, and classification reports
- **Visualization tools** for ECG signals, training curves, and model performance

---

## Model Architecture

### CNN Blocks
Extract spatial features from ECG waveforms, identifying characteristic patterns like P-waves, QRS complexes, and T-waves.

### LSTM Layers
Capture temporal dependencies in heartbeat sequences, recognizing long-term patterns critical for arrhythmia detection.

### Fully Connected Classifier
Maps learned features to final arrhythmia class predictions.

---

## Dataset

**MIT-BIH Arrhythmia Database**
- 48 half-hour ECG recordings
- Annotated heartbeat classifications
- Standard benchmark for cardiac arrhythmia research

Download and preprocess the dataset before training.

---

## Getting Started

### Installation

```bash
pip install -r requirements.txt
```

### Running the Project

```bash
jupyter notebook ECG_CNN_LSTM.ipynb
```

Execute all cells sequentially to:
1. Preprocess the data
2. Split into train/validation sets
3. Train the model
4. Evaluate performance

---

## Evaluation Metrics

The model is evaluated using:
- **Accuracy**
- **Precision, Recall, F1-Score** (per class)
- **Confusion Matrix**
- **Training/Validation Loss Curves**
- **Detailed Classification Report**

---

## Results

Typical performance metrics:
- **Accuracy:** 95–98%
- CNN layers effectively extract spatial ECG features
- LSTM layers capture temporal heartbeat patterns

*Results vary based on preprocessing methods and data splits.*

---

## Tech Stack

- **Language:** Python
- **Framework:** PyTorch
- **Libraries:** NumPy, Pandas, Matplotlib, Scikit-Learn, Seaborn

---

## Future Enhancements

- Refactor notebook into production-ready Python package
- Implement GRU-based architecture for comparison
- Deploy with FastAPI backend and Streamlit frontend
- Export to ONNX for edge device deployment
- Add real-time ECG classification capabilities

---

## License

MIT License

---

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

---

## Contact

For questions or collaboration opportunities, please open an issue in the repository.
