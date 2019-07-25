### The (word, semantic-classes) dataset
In this directory, you can find train and test splits of the (word, semantic-classes) dataset.

Each line in [train.tsv](https://github.com/yyaghoobzadeh/WIKI-PSE/blob/master/dataset/train.tsv) 
or [test.tsv](https://github.com/yyaghoobzadeh/WIKI-PSE/blob/master/dataset/test.tsv) has the following format:

```
word semantic-class1=freq1 <SPACe> semantic-class2=freq2 <SPACE> ...
```

For example:

```
@apple@	-organization=1652 -food=117 -art=16 -living_thing=14 -product=6 -person=3
```

Each frequency represents the number of occurrences of the word in the corpus.

Also, the list of 34 semantic-classes are in [semantic-class.txt](https://github.com/yyaghoobzadeh/WIKI-PSE/blob/master/dataset/semantic_classes.txt).

