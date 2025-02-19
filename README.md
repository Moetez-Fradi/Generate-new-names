# Italian Name Generator

A lightweight machine learning model that generates unique and authentic Italian names based on existing ones. The model is trained using a character-level neural network, capturing linguistic patterns to create realistic and diverse outputs.

## How It Works

- The model encodes characters as numerical values.
- A simple feedforward neural network learns patterns from names.
- During inference, given a prefix, the model predicts the next character iteratively.
- The network can be trained on any name dataset, allowing flexibility in name generation.
- A graph visualizes the relationships between characters as learned by the model, helping to understand its internal structure.


## Generate Names in Any Language!

The implemented code is easily adaptable to generate names in different languages! Simply follow these steps:

1. **Obtain a dataset**  
   - Download a text file containing names in your target language from [this repository](https://github.com/RasaHQ/rasa-nlu-examples/tree/main/data/namelists) or another source.  

2. **Update the code**  
   - Change the imported dataset filename in the script.  
   - Determine the number of unique characters in the target language and update the `alphabet_length` variable accordingly.  

With these simple modifications, the model can generate names in any language with an available dataset!
