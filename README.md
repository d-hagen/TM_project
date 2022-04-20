Author Profiling:
**Preprocessing the Data Set:**
to present the different Data Sets in the same format:
→ **tokenization**: removes noise from the data set and enables PoS tagging and using n-gram techniques (use the same tokenizer for all the data)
**→ remove URLs and HTML tags:** the URL strings are replaced by “url” since this info can be useful later → image links were replaced by “image”
**→ remove stopwords:** improve processing speed, stopwords do not carry any important info and just serve syntactic functions (use NLTK function)
**→ stemming:** reduces the number of different features and makes the text less noisy




**Feature implementation and Engineering:**
**→ TF-IDF:** presents the relative importance of a word in a corpus
**→ N-grams:** charcater based n-grams and word based n-grams to map them to different age groups
**→ Part of Speech:** compare different frequencies of PoS tags between age groups