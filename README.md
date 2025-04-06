# 🧠 Grammar Score Predictor for Spoken Audio

A Machine Learning project to **predict grammar scores** from spoken English audio using deep learning and natural language processing. The system processes audio files, extracts relevant features, trains a regression model, and evaluates its performance with visualizations.

---

## 📊 Sample Result

<p align="center">
  <img src="validation_scatter.png" alt="Validation Prediction vs Actual" width="400"/>
</p>

📌 **Observation**: The current model predicts grammar scores within a narrow range regardless of true score values. This highlights a potential bias that can be improved in future iterations.

---

## 🚀 Project Features

- 🎧 Audio Preprocessing using `librosa` and `torchaudio`
- 🧠 Feature Engineering with spectral and statistical descriptors
- 🔬 Regression Model using PyTorch
- 📉 Evaluation with validation plots and metrics
- 📦 Submission file generation in competition format

---

## 🛠️ Tech Stack

| Tool           | Purpose                      |
|----------------|-------------------------------|
| Python         | Core programming language     |
| NumPy / Pandas | Data manipulation             |
| Librosa        | Audio feature extraction      |
| Torch / torchaudio | Deep learning + audio tools |
| Matplotlib / Seaborn | Visualization           |
| Scikit-learn   | Metrics and preprocessing     |
| Transformers   | (Optional) Advanced embeddings |

---

## 📁 Directory Structure

```bash
.
├── train.csv                 # Training metadata
├── test.csv                  # Test metadata
├── sample_submission.csv     # Format for submission
├── submission.csv            # Your model's output
├── validation_scatter.png    # Prediction vs actual plot
├── requirements.txt          # Project dependencies
├── models/                   # (Optional) Saved models
├── audio/                    # (Optional) Audio data
└── main.ipynb or train.py    # Main training script
