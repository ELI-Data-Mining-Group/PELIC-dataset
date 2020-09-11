# `tutorials` folder

This folder contains three tutorials relating to the PELIC dataset:

1. [`build_PELIC_compiled.ipynb`](https://github.com/ELI-Data-Mining-Group/PELIC-dataset/blob/master/tutorials/build_PELIC_compiled.ipynb)  
The build_PELIC_compiled notebook provides a tutorial for creating the [`PELIC_compiled.csv`](https://github.com/ELI-Data-Mining-Group/PELIC-dataset/blob/master/PELIC_compiled.csv) from the PELIC corpus files in the [`corpus_files`](https://github.com/ELI-Data-Mining-Group/PELIC-dataset/tree/master/corpus_files) folder. The final csv file is also available in the home directory. For more information on [`PELIC_compiled.csv`](https://github.com/ELI-Data-Mining-Group/PELIC-dataset/blob/master/PELIC_compiled.csv), see the [PELIC_compiled.csv](https://github.com/ELI-Data-Mining-Group/PELIC-dataset/blob/master/README.md#pelic_compiledcsv) section of the main [README.md](https://github.com/ELI-Data-Mining-Group/PELIC-dataset/blob/master/README.md) file for the dataset.

<br>

2. [`exploratory_data_analysis.ipynb`](https://github.com/ELI-Data-Mining-Group/PELIC-dataset/blob/master/tutorials/exploratory_data_analysis.ipynb)  
The exploratory_data_analysis notebook provides a standard first step (EDA) in any data exploration and corpus analysis. It presents and demonstrates basic statistics of PELIC's composition, including the figures and statistics presented in this file. The statistics relate to the aspects of the corpus such as the students, their first languages, their genders, the classes and semesters, and of course the texts themselves. There is also an html version of the [notebook](https://github.com/ELI-Data-Mining-Group/PELIC-dataset/blob/master/tutorials/exploratory_data_analysis.html) for access without using jupyter.

<br>

3. [`PELIC_concordancing_tutorial.ipynb`](https://github.com/ELI-Data-Mining-Group/PELIC-dataset/blob/master/tutorials/PELIC_concordancing_tutorial.ipynb)  
The PELIC_concordancing_tutorial notebook provides a short example of the type of linguistic investigation that can be carried out with the data in PELIC. The focus of the investigation is a set of verbs which are important indicators of syntactic complexity. The tutorial has two aims:
  - to present a straightforward and replicable way of accessing and processing the corpus data necessary to answer genuine research questions, using tools from the [Pitt ELI Toolkit (pelitk)](https://github.com/ELI-Data-Mining-Group/pelitk)
  - to demonstrate how to build a concordance list and dataframe using the PELIC data
