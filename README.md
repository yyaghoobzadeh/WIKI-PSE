# WIKI-PSE
## A Wikipedia-based resource for Probing Semantics in word Embeddings
This repository contains the datasets we used in the following paper:

```
@inproceedings{yaghoobzadeh2019probing,
  title     = {Probing for Semantic Classes: Diagnosing the Meaning Content of Word Embeddings},
  author    = {Yadollah Yaghoobzadeh, Katharina Kann, Eneko Agirre, Timothy J. Hazen and Hinrich Sch{\"{u}}tze},
  booktitle = {Proceedings of ACL},
}
```



### Data
(For only the (word, semantic-classes) datasets, please visit this directory:
[dataset](https://github.com/yyaghoobzadeh/WIKI-PSE/tree/master/dataset).)

All WIKI-PSE files, including the corpus and trained embeddings can be dowloaded from this link:

[data.zip](http://cistern.cis.lmu.de/WIKI-PSE/data.zip)

After unzipping the data.zip, in the root, "corpus.txt" is the corpus we used to train word embeddings (e,g, "@apple@").

In "word_sclass" subdirectory, there is another "corpus.txt". This one is used to train (word, semantic-class) embeddings (e.g., "@apple@-organization").





