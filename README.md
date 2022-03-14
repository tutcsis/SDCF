# The SDCF: Semi-automatically structured Dataset of Citation Functions

This repository stores an official dataset of citation functions of the paper **"SDCF: Semi-automatically structured Dataset of Citation Functions"**. This research aims to build a new dataset of citation functions. Our work was motivated by the fact that existing datasets consist of limited labels and contains few instances. Moreover, most of existing labels of citation function were built using limited research scopes.

The contribrution of this paper provided in this repository are:
1. A new [labeling scheme](#labeling-scheme-of-citation-functions) of citation functions containing five coarse labels and 21 fine-grained labels.
2. A [labeling guidance](https://github.com/tutcsis/SDCF/tree/main/Labeling%20instructions), for annotators.
3. A [development dataset](https://github.com/tutcsis/SDCF/tree/main/Development%20datasets), which consists of 5,668 manually labeled instances.
4. A [final dataset](https://drive.google.com/drive/u/0/folders/12CE9pPUqks5-tdnUSSPxfD-WdGGhC4Y4), which consists of 1,840,815 automatically labeled instances.

## Proposed System Architecture
The proposed dataset was developed by following two sub-stages. 
* In the first stage, this research proposes a new labeling scheme of citation functions. 
* In the second stage, we develop a new dataset of citation functions using semiautomatic approach. 
  * The semiautomatic approach is implemented by creating a development dataset (manually labeled dataset), and the final dataset (autmatically labeled dataset). 
* Furthermore, we apply the Active Learning (AL) method as low resurce scenarios. 

The whole stages of dataset building is shown in the following figure.

![picture alt](https://github.com/tutcsis/SDCF/blob/main/Images/new-whole-diagram.png "Title is optional")


The below figure represents the AL approach:
![picture alt](https://github.com/tutcsis/SDCF/blob/main/Images/New-Active-Learning.png "Title is optional")

## Labeling scheme of citation functions
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

## Dataset of Citation Functions
The finel dataset of citation functions is organized as follow:
columns-0  | columns-1  | columns-2  | columns-3  | columns-4  | columns-5
------------- | ------------- | ------------- | ------------- | ------------- | -------------
paper-id  | published-date-in-ArXiv  | paper-title  | line-number  | citing-sentence  | label

* Inter-annotation Agreement results 
* Classification Results 
  * Filtering stages 
  * Fine-grained Classification 

## Citation
If you find that our datasets are useful, please cite:

 

## Contact Us
Further questions, reach us on: setio@is.cs.tut.ac.jp   
