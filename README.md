## ScerePhoSite

### 1 Description
Protein phosphorylation plays a vital role in signal transduction pathways and diverse cellular processes. To date, a tremendous number of in silico tools have been developed for phosphorylation site identification, but few of them are suitable for the prediction of fungal phosphorylation sites.
In this paper, we present ScerePhoSite, a machine learning method of fungal phosphorylation site identification. 
The source code and datasets are accessible at https://github.com/wangchao-malab/ScerePhoSite/.

### 2. Availability
#### 2.1. Datasets and source code are available at:
https://github.com/wangchao-malab/ScerePhoSite/.

#### 2.2 Local running

2.2.1 Environment

Before running, please make sure the following packages are installed in Python environment:

pandas==1.1.3

python==3.7.3

biopython==1.7.8

numpy==1.19.2

scikit-learn==0.24.2


For convenience, we strongly recommended users to install the Anaconda Python 3.7.3 (or above) in your local computer.

2.2.2 Running
Changing working dir to ScerePhoSite-master_source_code, and then running the following command:

python ScerePhoSite.py -i testing.fasta -t s/y/t -o prediction_results.csv

-i: name of input_file in fasta format   # folder “sequence” is the default file path of the input_file 

-t: phosphorylation_type, it should be s, y, or t

-o name of output_file              # folder “results” is the default file path for result save.
