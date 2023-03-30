# Data and code accompanying the paper 'The performance of exceptional public buildings on social media – The case of Depot Boijmans'

The repository contains data and code which can be used to produce the findings in our [paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0282299).
- Data: `DepotBoijmans.csv`
- Code: 
	- `ImageAnalysis.ipynb`: Image clustering
	- `MetadataAnalysis.ipynb`: Post frequency and aggregate statistics
	- `NLPAnlaysis.ipynb`: Keyword analysis and topic modeling

Requirements:
- numpy 
- pandas
- seaborn
- matplotlib
- scipy
- sklearn
- tqdm
- [bertopic](https://github.com/MaartenGr/BERTopic): 0.9.4 (newer versions can have different function parameters and will require tweaking)
- hdbscan
- umap
- nltk
- spacy