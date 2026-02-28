<h1 align="center">Fake Review Detector</h1>

## Project Structure

```
FakeReviewDetector/
├── data/
│   ├── fakereviews.csv
│   └── Preprocessed Fake Reviews Detection Dataset.csv
├── models/
│   ├── fake_review_model.pkl
│   ├── fake_review_model2.pkl
│   └── vectorizer.pkl
├── notebooks/
│   ├── fake_review_training.ipynb
│   └── fake_review_training2.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

## Installation Guide

Follow these steps to set up the project on your system.

### 1. Clone the Repository

```bash
git clone https://github.com/amitabhanmolpain/FakeReviewDetector.git
cd FakeReviewDetector
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

### 3. Activate the Virtual Environment

**Windows:**
```bash
venv\Scripts\activate
```

**Mac / Linux:**
```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Install NLTK Stopwords

Start Python and run:

```bash
python
```
Then in the Python shell:
```python
import nltk
nltk.download("stopwords")
exit()
```

### 6. Run the Training Notebook

Open the notebook in VS Code or Jupyter:

```
notebooks/fake_review_training.ipynb
```
Run all cells to train the model.