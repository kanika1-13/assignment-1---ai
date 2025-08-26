Movie Semantic Search Assignment

Author: Kanika Malhotra (221020431, DSAI)

This project implements semantic search on movie plots using SentenceTransformers with the model all-MiniLM-L6-v2. Each plot is converted to embeddings, and cosine similarity is used to retrieve the most relevant titles for a given query.

Work Done

Implemented search in movie_search.py

Used movies.csv (titles + plots) as sample data

Added CLI for querying top-N results

Wrote unit tests (tests/test_movie_search.py) to check output size, range, and ranking

Documented setup and issues

Files

movie_search.py – core code

movies.csv – dataset

tests/test_movie_search.py – tests

requirements.txt – dependencies

README.md – documentation

Notes

Model: sentence-transformers/all-MiniLM-L6-v2

Metric: cosine similarity (0–1 scale)

Example: Query “spy thriller in Paris” should return spy movie on top