# The Written Work Corpus

`The Written Work Corpus` is an open and manually created data set of named occurrences of written work (books) in Swedish news text. It’s intended use is in named-entity recognition (NER) tasks. 

## Description

The corpus is annotated using the BILOU annotation scheme. The corpus is tab delimited and tokenized using the NLTK tokenizer with a Swedish language model. 

The focus on the data set is written works (books). All included articles contain at least one mention of a book. The corpus is also enriched with tags that denote other cultural artefacts. These are: ART, GAME, MOVIE, MUSIC, PLAY, RADIO and TV. A detailed description of the corpus can be found here: 

A detailed description of the algorithms used along with evaluations can be
found here:

 * [The Written Work Corpus](http://www.hillevihagglof.se/2018/09/08/the-written-work-corpus/).

## Issues

There are some things to be aware of:

 * The tokenization is not perfect. In some instances it has been manually corrected. 
 * There are no delimiters between articles. 
 * No inter-annotator agreement available. 

## Credits

The Written Work Corpus was created by Hillevi Hägglöf with randomly selected data from Dagens Nyheter's culture section.