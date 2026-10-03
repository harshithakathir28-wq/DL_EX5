# Experiment 5: Implementation of a Recurrent Neural Network for Text Generation

## Aim

To implement a Recurrent Neural Network (RNN) for text generation and evaluate its ability to generate meaningful text by predicting the next word in a sequence.

## Tools and Technologies

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Scikit-learn
* Hugging Face Datasets
* Google Colab
* GitHub

## Dataset

The Tiny Shakespeare dataset was obtained from Hugging Face and used for text generation.

The dataset contains Shakespearean text that can be used to learn word sequences and generate new text.

## Tasks Performed

### Task A – Dataset Preparation

* Loaded the Tiny Shakespeare dataset from Hugging Face.
* Explored the text samples.
* Converted the text to lowercase.
* Tokenized the text into individual words.
* Created a vocabulary and assigned integer indices to words.
* Generated sequences for next-word prediction.
* Applied sequence padding.
* Split the data into training and validation datasets.

### Task B – RNN Model Implementation

The RNN model consists of:

* Embedding Layer
* Simple RNN Layer with 128 units
* Dense Output Layer
* Softmax Activation

The model was compiled using the Adam optimizer and sparse categorical cross-entropy loss.

### Task C – Model Training and Evaluation

* Trained the RNN model for 10 epochs.
* Used a batch size of 128.
* Recorded training and validation accuracy.
* Recorded training and validation loss.
* Visualized accuracy and loss against epochs.

### Task D – Text Generation

* Provided different seed sentences as input.
* Predicted the next word repeatedly using the trained RNN.
* Generated multiple text samples.
* Compared the generated text for coherence and contextual relevance.

## Model Architecture

Embedding Layer → Simple RNN → Dense Layer → Softmax Output

## Results

The RNN learned patterns from the Tiny Shakespeare dataset and generated text based on different seed inputs. Training and validation accuracy and loss were analyzed using performance graphs.

## Conclusion

A Simple RNN was successfully implemented for text generation using the Tiny Shakespeare dataset. The experiment demonstrated how an RNN processes sequential text and predicts the next word using information from previous words.
