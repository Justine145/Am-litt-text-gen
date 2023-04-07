# Am-litt-text-gen 
## American Literature Text Generator

### This repository contains a small personal project on text generation.

The aim was to train a model on a chapter from a classic American novel, Moby Dick. This is the file "textgen_model".
\
The LSTM based model is created using Keras.
\
The American novel used to train the model comes from the publicly available ressource Gutenberg Project (https://www.gutenberg.org/). 
The chapter from this novel has been added as a .txt file.

Afterwards, the model is able to generate a new text based on a few given words (a seed). This is the file "textgen_output".

The output can be displayed using the API Gradio (see https://c1c1f9a9ad0f8f08.gradio.app/ , available until April 10th).

