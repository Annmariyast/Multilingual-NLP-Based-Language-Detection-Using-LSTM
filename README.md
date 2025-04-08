# Multilingual NLP-Based Language Detection Using LSTM

## 📌 Project Description
This project focuses on building a multilingual language detection system using a deep learning model based on Long Short-Term Memory (LSTM). The system can accurately detect the language of a given text input among various global languages, enabling a wide range of applications such as translation systems, intelligent chatbots, and multilingual content categorization.

## 🚀 Features
- Accepts text inputs in multiple global languages
- Uses LSTM to learn sequential patterns in language
- High accuracy in classification
- Evaluation metrics: Accuracy, Precision, Recall, F1-score
- Visual insights through confusion matrix and F1-score plots

## 🗂 Dataset
- **Source**: Public multilingual dataset with labeled language samples
- **Size**: 10,000+ text samples
- **Languages Covered**: English, Hindi, French, Spanish, and more

## 🔍 Exploratory Data Analysis (EDA)
- Class distribution visualization
- Sample sentence lengths
- Most frequent languages and tokens

## 🛠️ Preprocessing
- Tokenization using Keras Tokenizer
- Padding sequences
- Label encoding
- Train-test split

## 🧠 Model Architecture
- Embedding layer
- LSTM layer
- Dense layer with ReLU
- Softmax output layer for multi-class classification

## ⚙️ Key Hyperparameters
| Parameter | Value |
|-----------|-------|
| Embedding Dimension | 128 |
| LSTM Units | 128 |
| Dense Units | 64 |
| Optimizer | Adam |
| Epochs | 10 |
| Batch Size | 32 |

## 📈 Evaluation Metrics
- Classification report (precision, recall, F1-score)
- Confusion matrix
- F1-score visualization

## 📊 Sample Output
| Language | Precision | Recall | F1-Score |
|----------|-----------|--------|----------|
| English  | 0.96      | 0.94   | 0.95     |
| Hindi    | 0.97      | 0.96   | 0.96     |
| Spanish  | 0.95      | 0.95   | 0.95     |

## 🧪 Installation & Usage
```bash
# Clone the repository
git clone https://github.com/your-username/language-detection-lstm.git
cd language-detection-lstm

# Install dependencies
pip install -r requirements.txt

# Run the model (example script)
python main.py
```

## 📌 Future Enhancements
- Audio input via speech-to-text using Whisper
- Real-time deployment through Gradio or Flask
- Support for dialects and low-resource languages

## 📧 Author
**Ann Mariya**  
Christ University, Bangalore  
Email: stannmariya@gmail.com

---
Feel free to fork, star ⭐, and contribute to this project!

