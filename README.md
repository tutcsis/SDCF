# SDCF
# The SDCF: Semi-automatically structured Dataset of Citation Functions #

This repository stores an official dataset of citation functions of the paper, SDCF: Semi-automatically structured Dataset of Citation Functions. 

The developed datasets consist of two parts: 
1. Development dataset, manually labeled and is used for building the annotation scheme of citation functions.
2. Final dataset, which is built automatically based on the best models on the development stages.



## Proposed System Architecture ## 
This is the whole system architecture
![picture alt](https://github.com/tutcsis/SDCF/blob/main/Images/new-whole-diagram.png "Title is optional")

This is the active learning scenario
![picture alt](https://github.com/tutcsis/SDCF/blob/main/Images/New-Active-Learning.png "Title is optional")

## Labeling scheme of citation functions ## 
The proposed scheme consists of two parts, five coarse labels and 21 fine-grained labels.

coarse labels  | fine-grained labels
------------- | -------------
background  | definition
background  | suggest
background  | judgment
background  | technical
background  | trend
citing paper work  | citing_paper_corroboration
citing paper work  | citing_paper_based_on
citing paper work  | citing_paper_use
citing paper work | citing_paper_extend
citing paper work | citing_paper_dominant
citing paper work  | citing_paper_future
cited paper work  | cited_paper_propose
cited paper work  | cited_paper_success
cited paper work  | cited_paper_weakness
cited paper work  | cited_paper_result
cited paper work  | cited_paper_dominant
compare and contrast  | compare
compare and contrast  | contrast
other  | other_cited_paper_comparison
other  | other_multiple_intent
other  | other_other

## Dataset Evaluation ## 
* Inter-annotation Agreement results 
* Classification Results 
  * Filtering stages 
  * Fine-grained Classification 

## Citation ## 
If you find that our datasets are useful, please cite:

 

## Contact Us ##
Further questions, reach us on: setio@is.cs.tut.ac.jp   
