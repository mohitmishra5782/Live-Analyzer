# Live Analyzer — NLP Sentiment Analysis Suite

An end-to-end Natural Language Processing (NLP) project for text sentiment classification. The project showcases a machine-learning workflow using text preprocessing, TF-IDF features, and multiple classification models.

**Author:** Mohit Mishra

## Project Overview

The application presents an interactive sentiment-analysis experience and a model-benchmarking showcase. Its stated approach uses TF-IDF vectorization and scikit-learn classifiers for text classification.

## Key Concepts

- Text preprocessing and feature extraction
- TF-IDF vectorization
- Supervised text classification
- Comparing multiple machine-learning models
- Running sentiment predictions through an interactive interface

## Tech Stack

- Python
- scikit-learn
- TF-IDF
- HTML, CSS, and JavaScript for the project showcase

## Live Demo

Open the GitHub Pages deployment from the repository's **About** section, if configured. The static entry page is `index.html`.

## Run the Showcase Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/mohitmishra5782/Live-Analyzer.git
   cd Live-Analyzer
   ```
2. Open `index.html` in your browser, or start a local server:
   ```bash
   python -m http.server 8000
   ```
3. Visit http://localhost:8000.

## Repository Notes

- The repository includes a GitHub Actions workflow for static-site deployment.
- Ensure GitHub Pages is configured to use the deployment workflow/environment under **Settings → Pages**.
- Add the training notebook or Python scripts, dataset source, dependency list, and measured model metrics as they become available. Do not claim benchmark scores unless reproducible from the committed code and data.

## Future Improvements

- Document the dataset and its license/source.
- Add reproducible training and evaluation instructions.
- Include a model comparison table with actual measured metrics.
- Add screenshots or a short demo GIF.
- Add tests for preprocessing and prediction behavior.

## Author

Mohit Mishra — https://github.com/mohitmishra5782
