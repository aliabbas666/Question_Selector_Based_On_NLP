# Question_Selector_Based_On_NLP
INTRODUCTION
Program will take paragraph as input.And will provide best questions related to the input paragraph from our text file containing more than 1 lac Questions.

TOOLS and TECHNICS
Used Python language for building logics .
Used Nltk library for Natural Language Processing.
Used Cosine Similarity Algorithm

How Our Code Works:
1) Take Paragraph as Input.
2) Tokenize the paragraph(break the paragraph into sentences).
3) Tokenize each sentence of paragraph(break the sentences into words).
4) Remove punctuation and stopwords from tokenized sentences.
5) Do 3 (tokenize each question) & 4 for the all questions provided in the text file.
6) Use Cosine Similarity Algorithm (matching the each question(Only Important words ) with the each sentence(only important words of sentence) of Input Paragraph)
7) Output total number questions required by user.
