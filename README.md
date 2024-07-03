# Text-Summarization using LSTM and GRU

# Introduction 

By condensing large amounts of information into a concise summary, text summarization allows users to quickly get the gist of a document or article without having to read through every word.

Developers don’t have the time to read through every article or case. Text summarization can also be helpful for students who need to study large volumes of material, or for anyone who wants to stay informed without spending hours reading.

# Flowchart

![image](https://github.com/vinayparjapati5/Text-Summarization-Project/assets/114856104/022e50f2-4925-430f-81a3-5bf0d52b2ba4)

# Preprocessing Steps

## 1. Tokenization

It is the process of segmenting running text into sentences and words , cutting a text into pieces called tokens.


![image](https://github.com/vinayparjapati5/Text-Summarization-Project/assets/114856104/5cf3d4f9-350e-49de-b7f1-9c896dcc6756)

## 2. Stop Words

-> Getting rid of common language articles, pronouns and prepositions such as
“and”, “the” or to.

-> Some very common words that appear to provide little or no value  such as "to","the".

->NLP objective are filtered and excluded from the text to be processed.

->Every Language has its predefined Stop word list

## Steps

1. Import the required libraries.
   
2. Pre-process the documents by removing the stop-words.
   
3. Replacement Operations:
   The replace method is used to replace specific characters and patterns in the text. This step helps in normalizing the text by converting special characters to readable forms and handling common text patterns.

4. Tokenization:
   The word_tokenize method from NLTK is used to split the text into individual tokens (words). Tokenization is a crucial step in text preprocessing as it breaks down the text into manageable pieces.

5. Stop Words Removal:
   After tokenization, the tokens are filtered to remove common English stop words using the NLTK stopwords list. Stop words are generally removed to reduce noise in the text data and focus on meaningful words.

6. Joining Tokens:
   The filtered tokens are then joined back into a single string using ' '.join(filtered_tokens). This step ensures that the preprocessed text is in a suitable format for further processing and analysis.

# LSTM Architecture
![image](https://github.com/vinayparjapati5/Text-Summarization-Project/assets/114856104/8f6b5759-c04d-432e-ac8b-644d82f4175a)

# GRU Architecture
![image](https://github.com/vinayparjapati5/Text-Summarization-Project/assets/114856104/a7aa62a8-be55-4a64-9b47-495777c95b0f)

# Predicted Summary(Dataset uploaded)
![image](https://github.com/vinayparjapati5/Text-Summarization-Project/assets/114856104/8698ed8e-bae3-4e89-a472-f86ec76c6ff7)






