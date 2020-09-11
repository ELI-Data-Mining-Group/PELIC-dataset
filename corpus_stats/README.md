# corpus_stats

This folder contains PELIC frequency statistics. All of these frequency data can be calculated from the original files in the [`corpus_files`](https://github.com/ELI-Data-Mining-Group/PELIC-dataset/tree/master/corpus_files) folder or [`PELIC_compiled.csv`](https://github.com/ELI-Data-Mining-Group/PELIC-dataset/blob/master/PELIC_compiled.csv). However, for quicker access to frequency information, the files in this folder may be useful.

## Folder contents:
- [`README.md`](https://github.com/ELI-Data-Mining-Group/PELIC-dataset/blob/master/corpus_stats/README.md): this file describing the folder contents
- [`frequency_stats.ipynb`](https://github.com/ELI-Data-Mining-Group/PELIC-dataset/blob/master/corpus_stats/frequency_stats.ipynb): a jupyter notebook showing how the other files in this folder were created
- [`word_frequencies.csv`](https://github.com/ELI-Data-Mining-Group/PELIC-dataset/blob/master/corpus_stats/word_frequencies.csv): a csv file containing the total frequency and per million frequency for every word in PELIC
- [`lemma_frequencies.csv`](https://github.com/ELI-Data-Mining-Group/PELIC-dataset/blob/master/corpus_stats/lemma_frequencies.csv): a csv file containing the total frequency and per million frequency for every lemma in PELIC


## Notes:
- Distributions do not take capitalization into account – a capitalized word and the same non-capitalized word will go towards the same count.
- Frequencies are based on NLTK tokens. Therefore, punctuation is also included in the distributions. If considering frequency ranking (for example for frequency bands), it is important to exclude punctuation.
