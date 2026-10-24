# Clustering Amazon Search Queries (ESCI Dataset)

Clustering of Amazon search queries by semantic intent (text embeddings) and by geometric/structural traits (query length, numbers, specifiers).

## Overview

Clustering search queries helps e-commerce systems understand user intent, which can improve recommendations and search. This project compares several clustering algorithms on queries from the Amazon ESCI dataset using three representations:

1. **Geometric only**: number of words, characters, digits, special characters, etc.
2. **Semantic only**: text embeddings of the queries.
3. **Geometric + semantic**: both combined.

Clusters were compared with internal evaluation metrics and by inspecting them qualitatively.

## Key Findings

- **Geometric:** simple, well-structured clusters (e.g. short queries with no details vs. queries with many numbers and symbols).
- **Semantic:** clusters that match meaningful product categories.
- **Geometric + semantic:** a more complex clustering space.


Download the [Amazon ESCI dataset](https://github.com/amazon-science/esci-data) and run the notebooks in numeric order.

## Report

The full write-up is in [`report/`](report/) .

## Author

[ayoub-alla](https://github.com/ayoub-alla)
