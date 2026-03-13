# ECG Classification using CNN–LSTM

A hybrid deep learning model that classifies ECG signals by combining **Convolutional Neural Networks (CNN)** for spatial feature extraction and **Long Short-Term Memory (LSTM)** networks for temporal pattern recognition. Built with PyTorch and trained on the MIT-BIH Arrhythmia Database.

---

## Model Architecture

### CNN Blocks
Extract spatial features from ECG waveforms, identifying characteristic patterns like P-waves, QRS complexes, and T-waves.

### LSTM Layers
Capture temporal dependencies in heartbeat sequences, recognizing long-term patterns critical for arrhythmia detection.

### Fully Connected Classifier
Maps learned features to final arrhythmia class predictions.

---


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


## License

MIT License

---


