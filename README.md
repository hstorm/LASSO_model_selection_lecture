# Lecture Advanced model specification with LASSO

Guest Lecture: Advanced Applied Econometrics, Master of Agricultural and 
Food Economics, SS2023, Uni Bonn 
  
*Hugo Storm (hugo.storm@ilr.uni-bonn.de),  May 2023*


## Learning aims

### Section 1: Lasso and friends
- Understand intuition of Regularized estimators (LASSO, ridge regression, etc) 
- Understand how LASSO can be used for model selection 

### Section 2: Approaches for model selection using LASSO  
- Understand difference between model selection for prediction and causal analysis
- Understand connection to econometrics model selection 
- Understand “Post-Lasso” model selection and its limitations
- Understand better approach for model selection using Lasso when doing causal analysis


## Lecture Slides 
available under: https://docs.google.com/presentation/d/15KhGbBiptpBqisdCcfm1GV7wqHx7bh2P9RuMSQ1-hxw/edit?usp=sharing

## Examples
See folder: ```/examples``` 

- ```housing_lasso.Rmd```  (Example on how to use Lasso for variable selection 
in an prediction context)
- ```wages_lasso.Rmd``` (Example on how to use Lasso for variable selection in 
causal interpretation context)

* Note 1: the datasets to run the notebooks are available on request.* 

* Note 2: in the folder ```/examples``` there are also html files for each 
notebook if you clone this repository (or download it) you can open those 
files in a browser. Those files give the code as well as rendered outputs. 
(Sadly github has in issue with those files an no preview is provided, so you 
actually need to download those files). * 


## Lecture Videos form 2021
available under: https://youtu.be/oDVATVVYOnk


## Recommended Readings

**Paper on double selection**
Belloni, Alexandre, Victor Chernozhukov, and Christian Hansen. 2014. “High-Dimensional Methods and Inference on Structural and Treatment Effects.” The Journal of Economic Perspectives 28 (2): 29–50. https://pubs.aeaweb.org/doi/pdfplus/10.1257/jep.28.2.29


**Full book on LASSO**
Hastie, Trevor, Robert Tibshirani, and Martin Wainwright. 2015. Statistical Learning with Sparsity: The Lasso and Generalizations. Chapman & Hall/CRC Monographs on Statistics and Applied Probability. Philadelphia, PA: Chapman & Hall/CRC. *pdf available at* http://web.stanford.edu/~hastie/StatLearnSparsity/



