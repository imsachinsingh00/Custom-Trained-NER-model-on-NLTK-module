# Custom Trained NER using NLTK

This project demonstrates training a custom Named Entity Recognition (NER) model using the NLTK module in Python.

## 📁 Project Structure

- `NER_model.ipynb`: Notebook for training and evaluating the custom NER model.
- `Entity.txt`: Example training data formatted for NLTK.
- `README.md`: Documentation.

## 🔧 How It Works

The project uses a custom dataset to train a model using the `nltk.chunk` module. It demonstrates:
- Tokenization
- Part-of-Speech (POS) tagging
- Chunking for Named Entity Recognition

## 📚 Dependencies

- Python 3.x
- nltk
- pandas

Install via:
```bash
pip install nltk pandas
```

Run the following in Python to download required NLTK packages:
```python
import nltk
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
```

## 🚀 How to Run

1. Clone or download the repository.
2. Open `NER_model.ipynb` in Jupyter Notebook.
3. Run the cells to load data, train, and evaluate the custom NER model.

## 🧾 Example

Training input (Entity.txt):
```
Sachin B-PER
Tendulkar I-PER
is O
a O
cricketer O
. O
```

## 📌 Notes

- The format follows BIO tagging for NER: B- for beginning, I- for inside, and O for outside any named entity.
- Extend `Entity.txt` to improve accuracy.

## 📄 License

MIT License.
