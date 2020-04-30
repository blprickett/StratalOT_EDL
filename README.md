# StratalOT_EDL
A Stratal OT Model (Kiparsky 2000), that finds pairwise ranking probabilities using Expectation Driven Learning (Jarosz 2015). The software is in the form of a .ipynb file (meant to be used with [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb)) and example input files are also included (which are meant to be uploayded to [Google Drive](https://www.google.com/drive/), prior to running the script in Colab).

Hyperparameters for the model are all in the notebook's second block of code. Currently, the software is designed to test the model on a very specific set of test data, but you can easily edit the words it's tested on by changing the values of *TEST_DATUM* and *TEST_DATUM_OUTPUTS*, which are also initialized in the second block of code.

## References
Jarosz, G. (2015). *Expectation driven learning of phonology*. Ms., University of Massachusetts Amherst.
Kiparsky, P. (2000). Opacity and cyclicity. *The linguistic review, 17(2-4)*, 351-366.
