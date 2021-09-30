# Academic-and-Formality-Rewriter
### GYAFC corpus:
The ownership of the GYAFC corpus belongs to Yahoo, Rao and Tetreault. Please contact Tetreault for access to the corpus. 
https://github.com/raosudha89/GYAFC-corpus

https://user-images.githubusercontent.com/44010415/135540002-d4646e72-dfe2-406c-9112-bd9a35df8ee8.mp4

### data preparation folder:
* __Substitution_Model.ipynb:__ <br>
This include the code for the substitution model that generates GYAFC-academic corpus from GYAFC. Notice that replacement words starting with '#' imply that they need to be manually rewrite.

* __GYAFC_Taboo_Dictionary.ipynb:__ <br>
This code is for collecting the taboo word statistics from the GYAFC corpus.

### model folder:
* __Classifier.ipynb:__ <br>
This code is for training Academic and Formality Classifier and Formality Classifier with BERT model. You can change the input file for different Classifier training.

* __Rewriter.ipynb:__ <br>
This code is for training Academic and Formality Rewriter with warm-started BERT2BERT model. Available input files are EM corpus, FR corpus, and EMFR corpus.

* __Get_Rewriter_Output.ipynb:__ <br>
This code is for getting the Rewriters' outputs on the test set and save them for later evaluation.

### evaluation folder:
* __Classify_Model_Outputs.ipynb:__ <br>
This code is for applying the Classifiers to classify the model outputs (including both warm-started transformer models and benchmark models) and collect statistics.

* __Grammar_Check.ipynb__: <br>
This code is for applying the Language Tool Python python package for checking the grammar accuracy of the model outputs.

* __Manual_Analysis.ipynb__: <br>
This code is for selecting sentences for manual analysis and their corresponding scores.
