There should be a directory in the same directory as where your project directory is located named 'project start data'.
This should contain the raw (unziped) data from: https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset

The git directory contains a yml file, which can be used to build the right environment.

I think it is best to make jupyter notebooks (ipython notebooks) that modifies the original data and saves a modified copy away from the project directory.
This way the data can always be recreated and we don't have to upload big files to github.
