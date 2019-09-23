# Information-Retrieval-Model

This project is intended to build a information retrieval system and evaluate and compare
their performance levels in terms of retrieval effectiveness.

# Snippet Generation

![Snippet](/images/snippet_generation.PNG)

# Query Suggestion

![Query Suggestion ](/images/query_suggestion.PNG)

# Comparison Results

|                             | MAP (Mean Average Precision) | MRR (Mean Reciprocal Rank) |
|:---------------------------:|:----------------------------:|:--------------------------:|
|             BM25            |            0.3231            |           0.7265           |
|            TF-IDF           |            0.2007            |           0.5466           |
|       Query Likelihood      |            0.2409            |           0.6068           |
|            Lucene           |            0.3871            |           0.6462           |
|           Stemming          |            0.3174            |           0.7202           |
|       Pseudo-Relevance      |            0.2759            |           0.6306           |
|        Stopping-BM25        |            0.3085            |           0.6841           |
|       Stopping-Tf-idf       |            0.2145            |           0.5379           |
| Pseudo Relevance [stopping] |            0.2516            |           0.5746           |
