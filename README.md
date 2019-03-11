# datasets

This repo is for datasets built from different corpora. they can be used for statistical modelling. 

The WSJ NOCE dataset:
To build the dataset, all occurrences of the three proforms 'this', 'it' and 'that' were extracted from the WSJ (Marcus, Marcinkiewicz, and Santorini 1993) and NOCE (Díaz-Negrillo and Garcia-Cumbreras 2007) corpora. 
This was achieved with a program selecting tokens tagged as pronouns by TreeTagger. As each occurrence was placed in a vector,
other features of this occurrence were also collected by looking up its POS context and other annotation layers before being
placed in the same vector. As a result each vector of the dataset corresponds to one proform occurrence and its linguistic features which are subsequently treated as variables in the modelling process. 
The purpose of the dataset is to include the linguistic variables that may influence the selection of any of the three forms.

Please refer journal article:
Gaillat, Thomas. 2019. “A Multifactorial Analysis of This, That and It Proforms in Anaphoric Constructions in Learner English.” Cahiers de Praxématique 71.
