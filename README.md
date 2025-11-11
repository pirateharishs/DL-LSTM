# DL- Developing a Deep Learning Model for NER using LSTM

## AIM
To develop an LSTM-based model for recognizing the named entities in the text.

## THEORY
An LSTM-based model for recognizing named entities is a type of neural network that uses Long Short-Term Memory (LSTM) layers to identify and classify proper names and entities within a text, such as person names, locations, organizations, dates, etc. It is commonly employed in Named Entity Recognition (NER) tasks because LSTMs are effective at capturing sequential dependencies and context within text. Typically, these models process tokenized input data, learn contextual representations, and output labels for each token indicating whether it belongs to a specific entity type. This approach improves the accuracy of extracting meaningful information from unstructured text data.

## Neural Network Model
Include the neural network model diagram.

## DESIGN STEPS
### STEP 1: 
Load data, create word/tag mappings, and group sentences.

### STEP 2: 
Convert sentences to index sequences, pad to fixed length, and split into training/testing sets.

### STEP 3: 
Define dataset and DataLoader for batching.

### STEP 4: 
Build a bidirectional LSTM model for sequence tagging.

### STEP 5: 
Train the model over multiple epochs, tracking loss.

### STEP 6: 
Evaluate model accuracy, plot loss curves, and visualize predictions on a sample.

## RESULT
Thus, an LSTM-based model for recognizing the named entities in the text has been developed successfully.

