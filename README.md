# How To Build A Search Engine

## 💬 About:
- This is a project I did to demonstrate the (very) basics of how to build a search engine. What this Python notebook does is download a bunch of articles from Wikipedia via the API, process the returned results to build an index based on [TF-IDF](https://www.capitalone.com/tech/machine-learning/understanding-tf-idf/) and then to run queries against the index using [Cosine Similarity](https://www.sciencedirect.com/topics/computer-science/cosine-similarity) to return documents that 'match' the query.

## 💾 Files in this repo are:
- **how_to_build_a_search_engine.ipynb** - this is the Python notebook that contains the code for pulling in the data from the Wikipedia API, processing the result and running queries against the 'index' .
  
## ⚡ Next Steps:
- The advantage of this approach is that it is simple to implement and computationally cheap, however TF-IDF doesn't capture semantic meaning and this can be seen in the some of the results that are returned for queries. Particularly ones that are fairly generic as the simplicity of the model doesn't capture the semantic nuance. It would be interesting to re-implement this using [embeddings](https://www.cloudflare.com/en-gb/learning/ai/what-are-embeddings/) to see if the process improves.
