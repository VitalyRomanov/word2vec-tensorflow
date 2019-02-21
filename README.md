Train word2vec in tensorflow.

### Input

Input data is a plain text file

### Tokenization

Process the file with `Vocabulary.py`. It will perform subsampling, tokenize the file and write the tokens to the disk.

### Training

Run `main.py` to train vectors. The result is regularly saved to the checkpoint in the current directory. The vectors will train only for the top N words in the vocabulary.