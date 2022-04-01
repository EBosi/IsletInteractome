# IsletInteractome

## What is this
This repository details the analytical steps used to generate the result of the manuscript "A single-cell human islet interactome atlas identifies disrupted autocrine and paracrine communications in type 2 diabetes", currently under review in NAR Genomics and Bioinformatics (and hopefully accepted in the future!).

## How can I use it
If you want to replicate the analyses, all necessary input files are provided. There is no dependency list because I'm lazy, briefly the needed software is Python3 and some widely used packages (matplotlib, scipy, numpy, pandas, seaborn and networkx). The whole thing has not been tested in a system beside mine, so if you need support please let me know!

## More details on the context
I invite you to read the manuscript as soon as it's available, briefly I used CellPhoneDB to generate a set of interactions in an integrated [dataset I previously published](https://pubmed.ncbi.nlm.nih.gov/33575641/), separately for cells from ND and T2D donors. The two sets of interactions (interactomes) are then studied to mine insights into relevant interactions for T2D pysiopathology. If you are curious please do read the manuscript or text me.   
