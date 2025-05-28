# Translation Quality Evaluator
This project aims to evaluate the quality of translations in a structured, measurable way. It takes a source sentence and its translation and assigns scores across five key metrics: readability, naturalness, adequacy, terminology consistency, and cultural appropriateness.

## Metrics and Scoring Approach
Each metric is made up of several measurable features. These features are combined to produce a single, interpretable score per metric.
### 1. Readability
- Sentence complexity
- Part-of-speech (POS) structure patterns

### 2. Naturalness
- N-gram comparison with native text corpora
- Perplexity Scoring
- Vocabulary diversity indices (TTR)

### 3. Adequacy
- Semantic similarity between source and translation
- Back-translation
- Content overlap scoring

### 4. Terminology Consistency
- Match with reference dictionaries or glossaries

### 5. Cultural Appropriateness
- LLM-based evaluation for cultural relevance or mismatch