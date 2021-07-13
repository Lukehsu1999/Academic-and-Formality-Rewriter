# Academic-and-Formality-Rewriter
### GYAFC corpus:
The ownership of the GYAFC corpus belongs to Yahoo, Rao and Tetreault. Please contact Tetreault for access to the corpus. 
https://github.com/raosudha89/GYAFC-corpus

### data preparation folder:
* SubstitutionModel.ipynb: <br>
This include the code for the substitution model that generates GYAFC-academic corpus from GYAFC. Notice that replacement words starting with '#' imply that they need to be manually rewrite.

* GYAFC_Taboo_Dictionary.ipynb: <br>
This code is for collecting the taboo word statistics from the GYAFC corpus.

### model folder:
* Classifier.ipynb: <br>
This code is for training Academic and Formality Classifier and Formality Classifier with BERT model. You can change the input file for different Classifier training.

* Rewriter.ipynb: <br>
This code is for training Academic and Formality Rewriter with warm-started BERT2BERT model. Available input files are EM corpus, FR corpus, and EMFR corpus.

* GetRewriterOutput.ipynb: <br>
This code is for getting the Rewriters' outputs on the test set and save them for later evaluation.

### evaluation folder:
* Classify_Model_Outputs.ipynb:
* GrammarCheck.ipynb:
* Manual_Analysis.ipynb:
