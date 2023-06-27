# Translation-model
This GitHub repository contains code for a machine translation model using TensorFlow. The model translates sentences from English to Spanish using a sequence-to-sequence architecture with a GRU-based encoder-decoder framework.



The repository includes the following main components:

1. Data preprocessing: The code downloads translation data from a specified URL and preprocesses it by tokenizing and cleaning the sentences.

2. Model creation: The code defines the model architecture, which consists of an embedding layer, GRU-based encoder, and GRU-based decoder. The model is compiled with an Adam optimizer and sparse categorical cross-entropy loss.

3. Training: The code splits the data into training and evaluation sets, creates TensorFlow datasets, and trains the model using the training dataset. It also provides an option to load pre-trained weights.

4. Translation: The code includes a function to decode input sequences and generate translations using the trained model. It demonstrates translation on provided example sentences and compares the machine translations with reference translations.

5. Model saving: If pre-trained weights are not loaded, the code saves the trained model, encoder, decoder, and tokenizers to disk for future use.

6. Evaluation Metric (BLEU): The code calculates BLEU scores (both BLEU-1 and BLEU-4) on the evaluation set to assess the translation quality of the model.

The repository enables training and evaluation of the machine translation model and provides a framework for further development and experimentation.
