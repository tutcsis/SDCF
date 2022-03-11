# SDCF
# The SDCF: Semi-automatically structured Dataset of Citation Functions #

This repository stores an official dataset of citation functions of the paper, SDCF: Semi-automatically structured Dataset of Citation Functions. 

Summary of our repository contribution:
1. A new labeling scheme of citation functions containing five coarse labels and 21 fine-grained labels.
2. A labeling guidance.
3. A development dataset of citation functions which consists of 5,668 manually labeled instances.
4. A final dataset of citation functions which consists of 1,840,815 automatically labeled instances.

## Proposed System Architecture ## 
This is the whole system architecture for building the dataset, which consists of two sub-stages. First, this research proposes a new labeling scheme of citation functions that has not been covered in existing works. Second, we develop a new dataset of citation functions using semiautomatic approach. The approach is started by creating a development dataset through manually labeled dataset, and the final dataset which is labeled autmatically using the best model obtained from previous step. Moreover, we apply the Active Learning method as a low resurce scenario.

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
