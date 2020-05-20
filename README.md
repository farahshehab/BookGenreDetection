# BookGenreDetection
The project we’re working on aims to identify the genre(s) of a certain book simply by conducting an analysis on its front cover. This could be of great help in big libraries, where instead of a having a person look up the genre of a book manually, the librarian would just scan the cover of the book and let the program do the job on his/her behalf. The program would make the process go faster, smoother and less prone to mistakes - such as typing in the wrong genre for a book - mainly caused by human inattention.

# Dataset
We used the dataset found in this link - task 1 only:
https://github.com/uchidalab/book-dataset

# Requirements [Python 3.]
- Jupyter Notebook
- sklearn
- tensorflow
- keras
- pandas 
- numpy
- Matplotlib 
- nltk


# Glove Embeddings file
glove.6B.100d.txt

# Models
We tried different approaches to this problem:
- using visual features alone (Pre-trained models such as ResNet, InceptionResNetV2 & VGGNet)
- using textual features alone (LSTM and Bag Of Words)
- combining both (Multi-model)

For more information about our approach check the paper and the poster in the repository.
