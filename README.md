# Analysis of Y2H combinatorial library of human-mouse STAT2 variants
With Matt Evans, Ethan Veit, Blake Richardson, et al. at Mount Sinai. 
Analysis by Caroline Kikawa.

## Background
STAT2 is an innate immune signaling protein that can be bound and signaled for degradation by flaviviral non-structural protein 5. Human STAT2 is vulnerable to this targeting by NS5, but murine (mouse) STAT2 is not. 

A yeast-2-hybrid (Y2H) library of STAT2 was created by the Evans lab. This library was designed to contain mutations in the 198-209 amino acid region of STAT2, where are all possible combinations of the 8 amino acid differences between human and mouse STAT2 were created. With 2^8 possible combinations, this results in 256 unique sequences. 

They selected for yeast that uptook expression plasmids with '2x' media. They also selected the same library with '4x+' media, which selected for expression plasmid uptake as well as binding by NS5. Here, I analyze the result of barcoded subamplicon sequencing these libraries. 

## Results
For a summary of the results, see [analysis_notebook.ipynb](analysis_notebook.ipynb).
For interactive graphs, see the linked GitHub pages [https://jbloomlab.github.io/ZIKV_Y2H_198-209_combinatorial_library/](https://jbloomlab.github.io/ZIKV_Y2H_198-209_combinatorial_library/).

## Input data
The input data are in [./data/](data):