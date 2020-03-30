# Training a Sentinet Analysis Model

In order to train this model, we will be using the IMDB Large Movie Review Dataset provided by the stanford at this page: http://ai.stanford.edu/~amaas/data/sentiment/

The files are contained in tar.gz and you can extract them in the following way:

Mind though that the aclImdb_v1.tar.gz contains more than 100k files and it will take several minutes for those files to be extracted (the tar.gz is 82MB while the disk size of the extracted files is 376MB).

How to extract the files.

1. Create a folder where you will exctract all the files e.g. sentiment-analysis

2. Place the aclImdb_v1.tar.gz inside the sentiment-analysis folder

3. Go inside the sentiment-analysis folder and right-click somewhere inside that folder but not on a file. In the shortcut menu that appears, select "Open PowerShell here" and the powershell window will open.

Then, inside the powershell window type either:

tar -xvzf FileName.tar.gz

or 

tar -xzf FileName.tar.gz

Note: the first option will log all the extraction steps, which will take more time, while the second option ommits this step and just extracts the files.

Alternatively, just for testing purposes, there's a folder named aclImdb-sample inside this repository which contains only a small number of reviews i.e. only 500 revies out of the 50K reviews that are included in the original file.

