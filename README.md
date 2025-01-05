# Play-Generator
## Overview
The Play Generator is a text generation model built using TensorFlow and Keras, trained on the works of William Shakespeare. This model utilizes a character-based approach to generate text that mimics the style of Shakespearean plays.

## Features
- Downloads and preprocesses Shakespeare's text data.
- Encodes characters into integers for model training.
- Creates training examples and targets for the model.
- Builds a recurrent neural network (RNN) using LSTM layers.
- Implements a custom loss function for training.
- Saves model checkpoints during training.
- Generates text based on a user-provided starting string.

## Requirements
- Python 3.x
- TensorFlow
- Keras
- NumPy
- Other dependencies as specified in the code

## Training the Model
- The model is trained for 50 epochs on the Shakespeare dataset. You can adjust the number of epochs in the training section of the notebook.
## Generating Text
- After training, you can generate text by providing a starting string. The model will produce a continuation of the text in the style of Shakespeare.

## Working
```python
inp = input("Type a starting string: ")
print(generate_text(model, inp))
```

## Checkpoints
- The model saves checkpoints during training, allowing you to resume training or load a pre-trained model.
## Contributing
- Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## Acknowledgments
- Inspired by the works of William Shakespeare.
- Utilizes TensorFlow and Keras for deep learning.
