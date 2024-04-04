# Data-extraction-and-NLP
Objective:
This project aims to leverage Natural Language Processing (NLP) techniques to extract textual data articles from provided URLs and conduct comprehensive text analysis to compute various linguistic features.

Data Extraction:
The input data is stored in the file named Input.xlsx.
For each article listed in Input.xlsx, the program extracts the article text and saves it in a separate text file. Each file is named based on the URL_ID associated with the article.
During the extraction process, only the article title and text are retrieved, excluding any extraneous content such as website headers and footers.

Data Analysis:
Following text extraction, the program employs NLP methods to analyze the extracted texts and compute a range of linguistic features including:
POSITIVE SCORE
NEGATIVE SCORE
POLARITY SCORE
SUBJECTIVITY SCORE
AVG SENTENCE LENGTH
PERCENTAGE OF COMPLEX WORDS
FOG INDEX
AVG NUMBER OF WORDS PER SENTENCE
COMPLEX WORD COUNT
WORD COUNT
SYLLABLE PER WORD
PERSONAL PRONOUNS
AVG WORD LENGTH

Output Data Structure:
The output adheres to the structure outlined in the output structure excel file.
It encompasses all input variables from Input.xlsx alongside the computed linguistic features derived from NLP analysis.
