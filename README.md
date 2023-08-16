# Human-Language-Technologies Projects

Welcome to the repository for two Human Language Technology projects completed as part of my academic assignments at University College Dublin (UCD). These projects delve into various aspects of natural language processing and analysis, showcasing the application of advanced techniques to explore language patterns and styles.
<img src="https://github.com/yinfangrtz/AI-Powered-Data-Pattern-Discovery/assets/106718273/e5211d6d-7bbc-41b5-9f16-fde9e44bc8d0" width="50%" alt="Image">

### Project 1: Language Style Analysis across Subreddits

### Research Question

This research project explores the language styles across different subreddits on the social media platform Reddit. The main question addressed is whether it is possible to infer topics and distinguish between subreddits based on their unique language styles. The study investigates various linguistic features, including lexical diversity, frequency distribution, and part-of-speech tagging, to identify patterns that differentiate subreddits.

### Methods
Data Collection and Selection
A web crawler was employed to collect raw text data from eight selected subreddits, which were grouped into four categories: Art and Design, Gaming and PS4, Ireland and England, and Science and Technology. Each category contained two closely related subreddits.

Data Pre-processing
The collected data underwent several pre-processing steps, including tokenization, lowercasing, punctuation and stop word removal, and stemming, to prepare it for analysis.

Analysis Techniques
Lexical Diversity Analysis: Lexical diversity scores were calculated for both pre-processed and original texts. This provided insights into the variation of words used in each subreddit.
Frequency Distribution and Most Common Tokens: The most frequently used words in each subreddit were identified, and their frequency distributions were examined. This helped in understanding the dominant topics and language features of each subreddit.
Part-of-Speech (POS) Tagging: Part-of-speech tagging was performed to categorize words into different linguistic classes, such as adjectives (JJ) and singular nouns (NN). This analysis revealed the types of words and language styles prevalent in each subreddit.
Results

Lexical Diversity
The analysis of lexical diversity scores indicated variations between different subreddits. For instance, the "england" subreddit exhibited the highest lexical diversity, while "ireland" had the lowest.

Frequency Distribution and Most Common Tokens
Comparing the most common tokens provided insights into the dominant topics and language styles of each subreddit. Subreddits with similar topics sometimes exhibited differences in their language use. For example, "art" and "design" subreddits shared some similarities but had distinct differences in terms of specific design-related words.

Part-of-Speech (POS) Tagging
By analyzing the most common adjectives (JJ) and singular nouns (NN), unique language styles of each subreddit were revealed. Different subreddits emphasized certain categories of words, reflecting their respective themes and subject matters.

### Discussion

The results of the study highlighted that distinct language styles exist across various subreddits. By examining lexical diversity, frequency distributions, and part-of-speech tagging, this research demonstrates the feasibility of identifying unique linguistic features that characterize each subreddit. The analysis also revealed the influence of different topics, social dynamics, and cultural norms on language style.

### Limitations and Future Work

While the study provides valuable insights, further analysis of named entity recognition (NER) and verb/adverb usage could enhance the depth and accuracy of text analysis. Exploring more advanced linguistic features and analysis techniques could offer a more nuanced understanding of language styles within subreddits.

### Project 2: N-gram Algorithm for Sentence and Word Generation

### Overview
In this project, the focus is on the utilization of the n-gram algorithm for sentence and word generation. The n-gram algorithm is employed to analyze linguistic structures and generate coherent sentences and words based on the provided corpus. The project is divided into two main components:

Similarity Between Words: The pre-trained Word2Vec model is used to determine the similarity between words within a given corpus. This technique aids in understanding the semantic relationships and structure of words. The model's ability to identify meaningful connections between words is explored by analyzing its output for a selected set of words.
Generating Sentences and Words Using n-gram Algorithm: The n-gram algorithm is applied to build a word-based model for sentence and word generation. The corpus is tokenized, and punctuation is removed to create a structured dataset. The n-gram model is trained to predict words based on their preceding context, and sentences and words are generated using this model.

### Key Findings
The Word2Vec model effectively captures semantic relationships between words, demonstrating the potential of natural language models to understand language structure.
The n-gram algorithm generates sentences that reflect adjacent word relationships, highlighting the algorithm's ability to predict words based on context.
The choice of corpus significantly impacts the quality of generated sentences, showcasing the algorithm's dependence on diverse and representative input data.
Seed text selection plays a crucial role in generating coherent and meaningful sentences using the n-gram model.
