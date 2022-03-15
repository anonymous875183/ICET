# ICET
 Implicit Causation from Explicit Transfer (ICET) dataset. Contains four datasets in comma separated variable format, each with two columns:
 
 * __sentence__: cleaned/ normalized sentences
 * __causal__: binary 1/0 indicator of causal semantics

The four datasets are 

* __ICET-Train.csv__: Training data, created using CauseNet and Wikipedia
* __ICET-Test.csv__: Testing data, created using CauseNet and Wikipedia
* __ICET-Explicit-Val.csv__: Validation data on explicitly causal sentences, created using SemEval and Wikipedia
* __ICET-Implicit-Val.csv__: Validation data on implictly causal sentences (no CauseNet markers), created using SemEval and Wikipedia
