# Text Summarization (NLTK Keyword Extractor)

A simple frequency-based keyword extraction script built with NLTK. Given a text file, it tokenizes the text, strips stopwords and punctuation, counts word frequency, and returns the most frequent terms as a quick gist of the document's key topics.

This is an early, minimal implementation — frequency counting rather than sentence-level or abstractive summarization. Kept here as a first step before the more complete summarization work in [voice-to-insight](https://github.com/syedashraf2211/voice-to-insight), which uses a transformer-based BART model.

## Run it

```bash
pip install nltk pandas
python -c "import nltk; nltk.download('stopwords'); nltk.download('punkt')"
```

Open `Text Summariztion Project.ipynb` in Jupyter, point it at a `.txt` file, and run all cells.

## Tech stack

Python · NLTK
