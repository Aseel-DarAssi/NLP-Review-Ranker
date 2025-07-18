# NLP Project: Ranking Product Reviews 

This project uses Natural Language Processing techniques to rank Amazon product reviews based on usefulness and relevance, helping users make smarter shopping decisions.

## Dataset
- Category: Beauty products
- 1000 reviews
- Fields: `review_body`, `star_rating`, `helpful_votes`, `verified_purchase`, etc.

## Features used in ranking
- Sentiment Subjectivity & Polarity
- Keyword relevance using YAKE
- Helpfulness score (Wilson Score)
- Review length & verified purchase

## Technologies
- `pandas`, `textblob`, `spacy`, `sentence-transformers`, `yake`, `scipy`, `numpy`

## Output
Each review is assigned a score, and reviews are sorted from most to least helpful.

## Presentation
See [`NLP_Presentation.pdf`](./NLP_Presentation.pdf).

