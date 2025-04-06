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



⚙️ Getting Started
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/grammar-score-predictor.git
cd grammar-score-predictor
2. Install Dependencies
We recommend using a virtual environment.

bash
Copy
Edit
pip install -r requirements.txt
📌 How to Use
Place your audio files in the audio/ folder (if using raw audio).

Update the CSV files as needed (train.csv, test.csv).

Run the model training or inference script:

bash
Copy
Edit
python train.py
View the results in submission.csv and validation_scatter.png.

✅ Sample Output Format
csv
Copy
Edit
file_name,grammar_score
audio_001.wav,3.64
audio_002.wav,3.64
audio_003.wav,3.64
...
🚧 Future Improvements
🔊 Real-time evaluation from microphone input

🤖 Use pretrained transformer models (e.g., Wav2Vec2, HuBERT)

🧪 Hyperparameter optimization

📊 Interactive performance dashboard

🤝 Contributing
Contributions are welcome!
To contribute:

Fork the repository

Create a new branch: git checkout -b feature/your-feature

Commit your changes: git commit -am 'Add feature'

Push to the branch: git push origin feature/your-feature

Open a Pull Request

👤 Author
Developed by Your Name

📄 License
This project is licensed under the MIT License.

⭐ If you found this helpful, please give it a star!

yaml
Copy
Edit

