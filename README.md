# Low-Resource Sentiment Analysis on the 2025 Steam Dataset Using HNSW and c-TF-IDF

Source Data: DOI 10.5281/zenodo.17266922, by Donald Fountain. 

Check out my [initial written report](Written%20Report_%20Low-Resource%20Sentiment%20Analysis%20of%202025%20Steam%20Dataset.pdf) for the more insights and findings!

The study has demonstrated a process which reduces the load on a memory-constrained environment while still providing competitive and improved results vs the baseline. We have shown that HNSW is effective for representing embeddings through neighborhood statistics. Furthermore, while domain-specific features prove critical for embedding models that lack inherent domain knowledge, their impact yields diminishing returns as the embedding model's semantic ranking performance improves.

This study has shown a direct relationship between embedding similarity evaluation and downstream classification model performance, while also illustrating how behavioral metrics influence sentiment analysis. For the 2025 Steam Dataset, the finetuned BGE-small-EN-v1.5
gave the best embeddings and when paired with Logistic Regression at a 45% threshold, this pipeline achieved the highest classification performance at a 93.49% macro-averaged F1-score.

Finally, the study reveals a highly diverse set of positive sentiment drivers, offering actionable considerations for game developers. Conversely, negative reviews exhibited tight semantic similarity, highlighting critical pitfalls and specific negative sentiment drivers that developers should actively avoid.

![Graphical_Abstract](Graphical%20Abstract_%20Low%20Resource%20Sentiment%20Analysis%20of%202025%20Steam%20Dataset.png)
