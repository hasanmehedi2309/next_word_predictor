
# Next Word Generator


The Next Word Generator is an innovative Natural Language Processing (NLP) project designed to predict the next word in a sequence of text. Leveraging advanced deep learning techniques, the model architecture consists of three key components: an Embedding layer, a Long Short-Term Memory (LSTM) layer, and a Dense layer.



## Model Architecture

         +----------+          +----------+          +----------+
         |  Input   | ------> | Embedding| ------> |  LSTM    | ------> |  Dense   | ------> Output (Word Probability)
         | Layer    |          | Layer    |          | Layer    |          | Layer    |
         +----------+          +----------+          +----------+          +----------+
              |                 |                  |                     ^ (Most Likely Next Word)
              |                 |                  |
         (Sequence of Word Indices)  (Sequence of Embedding Vectors)  (Context Representation)



**Embedding Layer:** The Embedding layer converts text data into dense numerical vectors, representing each word in a high-dimensional space. This transformation enables the model to capture semantic relationships between words and learn meaningful representations of the input text.

**LSTM Layer:** The LSTM layer, short for Long Short-Term Memory, serves as the core of the model for sequence prediction tasks. LSTM networks are well-suited for handling sequential data due to their ability to capture long-term dependencies and remember important information over time. By processing input sequences word by word, the LSTM layer captures contextual information and patterns within the text data.

**Dense Layer:** The Dense layer, also known as a fully connected layer, receives the output from the LSTM layer and performs the final prediction task. This layer applies mathematical operations to transform the LSTM output into a probability distribution over the vocabulary space, indicating the likelihood of each word being the next in the sequence.
## 🛠 Skills
Tensorflow, LSTM, Embedding, pandas, numpy...

