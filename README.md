# hungarian_accenter

## Usage of ipython notebooks
* To use one of the ipython notebooks training is needed. I did not uploaded my train data, because it's too big.
* Every text file (with Hungarian text) can be used as train data.
* The models will train on the first words of every non empty lines.
* Only the containing folder of the text file(s) shall be provided:
```
TRAIN_DATA_DIRS = [
                   'comments_20131001-20131201.nlp',
                   'comments_20131201-20140519.nlp',
                   'comments_20140519-20140921.nlp',
                  ]
```
* After training, the input word can be given to the "m.accent" funtcion and in return the networks prediction will be shown on the output.
