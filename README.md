# An NLP-based System Memorability Aid for Password Phrases


In today's digital landscape, password security is paramount. However, users often struggle to create memorable yet secure passwords, leading to the use of weak or reused passwords. This increases vulnerability to cyberattacks, posing risks to personal and organizational security.

This project presents a solution that utilizes deep learning to generate memorable password phrases. By transforming complex password requirements into easily memorable stories, users can enhance their security without sacrificing usability.

## Key Features
**Memorable Password Generation:** Leverages NLP techniques to create unique password phrases that users can easily remember.  
**Deep Learning Models:** Implements advanced models to ensure the generation of both secure and memorable phrases. 

**Deep Learning Models Includes: **  

** LSTM (Long Short-Term Memory): Utilized for sequence generation, allowing the model to understand context and improve the relevance of generated phrases.  
** Transformer-based Models: Leveraging Hugging Face's powerful transformer models, I implemented various architectures to generate coherent and memorable password phrases. These models utilize state-of-the-art NLP techniques to ensure high-quality outputs.

## Story Cloze Dataset  

The dataset used for training the models consists of corpus of common stories. 

Data Preparation

For the NLP-based System Memorability Aid for Password Phrases, we followed a structured data preparation process:  

**  Keyword Extraction: Using the KeyBERT library, we extracted important words from each sentence, leveraging BERT embeddings for relevance. SpaCy's 'en_core_web_sm' model helped us obtain the highest-scoring keywords efficiently.

** Dataset Cleaning: We ensured a clean dataset by removing stop words, punctuations, tags, and digits, and by converting all text to lowercase using regular expressions.  

**  Word Embeddings: We mapped words to frequency vectors through one-hot encoding, which allows the model to interpret the significance of each word.  

** Encoder-Decoder Tokens: Special start and end tokens were added to each story to enhance the model's understanding of sequence boundaries during training.  

