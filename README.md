# TOPSIS-Based Evaluation of Pre-trained NLP Models

## 📌 Overview
This project applies the **TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution)** method to evaluate and rank pre-trained NLP models for **text classification** based on multiple performance criteria.

## 🏆 Models Evaluated
- **BERT**
- **RoBERTa**
- **XLNet**
- **DistilBERT**
- **ALBERT**

## 📊 Evaluation Criteria
The models are ranked based on the following criteria:

| Criterion            | Type     | Weight |
|---------------------|---------|--------|
| Accuracy (%)       | Benefit | 0.40   |
| F1 Score (%)       | Benefit | 0.30   |
| Inference Time (s) | Cost    | 0.15   |
| Model Size (MB)    | Cost    | 0.15   |

## 🏅 TOPSIS Ranking Results
The final ranking of the models based on their TOPSIS score:

| Rank | Model      | TOPSIS Score |
|------|-----------|--------------|
| 🥇  | ALBERT    | 0.935395     |
| 🥈  | DistilBERT| 0.751880     |
| 🥉  | RoBERTa   | 0.320117     |
| 4️⃣  | BERT      | 0.295476     |
| 5️⃣  | XLNet     | 0.075154     |

## 📈 Visualizations
The project includes the following visualizations:
- **Bar Chart**: Ranking of models based on TOPSIS score.
- **Radar Chart**: Performance distribution of each model.
- **Heatmap**: Weighted normalized decision matrix.
- **Pairwise Scatter Plot Matrix**: Relationship between evaluation metrics.

## 🛠 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/topsis-nlp-ranking.git
   cd topsis-nlp-ranking
   ```
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn
   ```
3. Run the script:
   ```bash
   python topsis_analysis.py
   ```
4. View the results and visualizations.

## 📂 Project Structure
```
📦 topsis-nlp-ranking
├── 📜 README.md  # This file
├── 📜 topsis_analysis.py  # Python script for TOPSIS calculation
├── 📊 results/  # Folder for storing output graphs and tables
└── 📁 data/  # Folder for datasets (if any)
```

## 🚀 Contribution
Feel free to fork this repository and enhance the analysis! 😊

## 📌 References
- [TOPSIS Method - Wikipedia](https://en.wikipedia.org/wiki/TOPSIS)
- [Hugging Face Model Hub](https://huggingface.co/models)

---
💡 **Created as part of an academic assignment**
