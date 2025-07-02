# Data Discovery
- Topic Analysis
  - Topical (dis-)similarity between authors
  - Making sure it is not turning into a topic classification task (balance is important)
  - Measure the difference between two authors' topic probability distribution (using KL divergence).
- Style Analysis

# Classifier
- Adding a layer of emotional/sentiment analysis (if by using a different classifying method)
- Exploring POS
- Exploring the existence/frequency of NE
- Stylometric features include lexical, syntactic, structural, and content-specific features.
  - Transformers capture all those features. Should we contribute to adding concentration on a certain feature?
- Maybe we will need to split the large texts (to prevent bias towards large texts).
- We should experiment with little and much preprocessing.
- Can LLMs capture metaphorical expressions?
  - Measure the usage of metaphors for every author.
- Identify features that are meant to affect the style of the authors.
  - Topics
  - Metaphors
  - Lexicon Richness
  - Syntax/Structure Complexity
  - Text Length
