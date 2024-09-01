# Budget 2024 Sentiment Analysis | NLP

## Project Overview

This project involves performing sentiment analysis on comments related to Budget 2024 from YouTube videos. Using natural language processing (NLP) techniques, the project analyzes public sentiment and provides insights into the overall reception of the budget. Various models and methods, including BiLSTM, GRU, and BERT, are employed to classify sentiments and analyze the results.

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Methodology](#methodology)
- [Results](#results)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)

## Project Description

The project aims to analyze sentiments expressed in YouTube comments about Budget 2024. By scraping comments using the YouTube Data API and applying various NLP techniques, the project evaluates public opinion on the budget. The analysis includes the use of traditional sentiment analysis tools and advanced deep learning models.

## Features

- **Data Collection:** Scraped YouTube comments related to Budget 2024 using the YouTube Data API.
- **Text Processing:** Processed text data using NLTK and spaCy for cleaning and tokenization.
- **Sentiment Labeling:** Utilized VADER for initial sentiment labeling.
- **Model Training:** Trained BiLSTM and GRU models with Word2Vec embeddings, achieving an F1 score of 82%.
- **Advanced Analysis:** Fine-tuned a BERT model from Hugging Face for sentiment analysis of 10,000 comments.
- **Sentiment Insights:** Analyzed and reported sentiment distribution of comments.

## Technologies Used

- **Data Collection:** YouTube Data API
- **Text Processing:** NLTK, spaCy
- **Sentiment Analysis:** VADER, Word2Vec, BiLSTM, GRU, BERT (Hugging Face)
- **Deep Learning Frameworks:** TensorFlow/Keras or PyTorch (depending on implementation)

## Methodology

### Data Collection

- **YouTube Data API:** Scraped comments from YouTube videos related to Budget 2024.

### Text Processing

- **NLTK & spaCy:** Cleaned and tokenized the text data to prepare it for sentiment analysis.

### Sentiment Labeling

- **VADER:** Used for initial sentiment labeling of comments.

### Model Training

- **BiLSTM & GRU:** Trained BiLSTM and GRU models using Word2Vec embeddings to classify sentiments, achieving an F1 score of 82%.

### Advanced Analysis

- **BERT Model:** Fine-tuned a BERT model from Hugging Face to analyze the sentiment of 10,000 comments.

## Results

- **Sentiment Distribution:** Found that 18% of comments expressed positive sentiment towards Budget 2024, while 56% of comments expressed negative sentiment.

## Usage

1. **Setup:** Ensure all dependencies are installed, including necessary libraries for data collection, processing, and model training.
2. **Data Collection:** Use the YouTube Data API to collect comments on Budget 2024 related videos.
3. **Text Processing:** Clean and tokenize the collected comments using NLTK and spaCy.
4. **Sentiment Analysis:** Apply VADER for initial labeling, train BiLSTM and GRU models with Word2Vec embeddings, and fine-tune BERT for in-depth sentiment analysis.
5. **Analyze Results:** Review the sentiment distribution and interpret the findings.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests. For more details, see the [CONTRIBUTING](CONTRIBUTING.md) guidelines.
