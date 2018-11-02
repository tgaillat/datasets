# datasets
datasets built from corpora
To build the dataset, all occurrences of the three proforms 'this', 'it' and 'that' were extracted from the WSJ and NOCE corpora. 
This was achieved with a program selecting tokens tagged as pronouns by TreeTagger. As each occurrence was placed in a vector,
other features of this occurrence were also collected by looking up its POS context and other annotation layers before being
placed in the same vector. As a result each vector of the dataset corresponds to one proform occurrence and its linguistic features which are subsequently treated as variables in the modelling process. 
The purpose of the dataset is to include the linguistic variables that may influence the selection of any of the three forms.
