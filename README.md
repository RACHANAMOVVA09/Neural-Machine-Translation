# Neural-Machine-Translation

This Project runs an experiment on Neural machine Translation with use case as English to French

#Overview:

Machine translation uses software to translate text or speech from one language to another. Machine translation engine performs simple substitution of words in one language for words in another, but that alone doesn’t usually produce the highest quality translation of a text. For more accurate translation, recognition of whole phrases and their closest counterparts in the target language is needed.
Although big players like Google Translate and Microsoft Translator offer near-accurate, real-time translations, some “domains” or industries call for highly-specific training data related to the particular domain in order to improve accuracy and relevancy.


# Requirements
1.Python 3.6 and higher
2. Keras
3. Tensorflow
4. Knowledge on computing platforms such as AWS and gcp
5. Knwowledge on Google colab


# Appoach
The idea is to use one LSTM to read the input sequence, one timestep at a time, to obtain large fixed dimensional vector representation, and then to use another LSTM to extract the output sequence from that vector. The second LSTM (handles long term dependencies) is essentially a recurrent neural network language model except that it is conditioned on the input sequence. 


The encoder creates a matrix representation of the sentence. The decoder takes this matrix as input and predicts the translation as output.
