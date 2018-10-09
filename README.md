# triplets-extraction
paper: Joint Extraction of Entities and Relations Based on a Novel Tagging Scheme
Theano version: Theano 0.8 (21th of March, 2016)
The keras version: 0.3.3

## Setup

1. get the data from the link [NYT](https://drive.google.com/drive/folders/0B--ZKWD8ahE4UktManVsY1REOUk?usp=sharing) and unzip the data in 
````data/demo/````

2. generate the train_tag.json:

   First, we need to create a new file:

   ````touch data/demo/train_tag.json````

   Then run the TaggingScheme.py

   ````python TaggingScheme.py````


