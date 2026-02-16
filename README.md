# NLP Movie Sentiment

Sentiment classification of Rotten Tomatoes movie reviews using TF-IDF and machine learning, built with Python (Scikit-learn, Pandas, NumPy).

## Tools & Skills Used

## Quick Access

## Setup & Installation

### Prerequisites

- Python 3.12+
- [uv](https://docs.astral.sh/uv/getting-started/installation/) package manager

### 1. Clone the Repository

```bash
git clone https://github.com/krauseannelize/nlp-movie-sentiment.git
cd nlp-movie-sentiment
```

### 2. Install Dependencies

```bash
uv sync
```

### 3. Data Acquisition

The dataset is hosted on [Kaggle](https://www.kaggle.com/datasets/nltkdata/sentence-polarity). Download and place files in the `data/` folder:

- `rt-polarity.pos` — 5,331 positive sentiment sentences
- `rt-polarity.neg` — 5,331 negative sentiment sentences

### 4. Run the Project

```bash
uv run jupyter lab
```

📌 **Note:** `uv run` automatically uses the project's virtual environment, no manual activation needed
