A naive approach to classify mushrooms for educational puposes
Following the Fastai course, I decided to try and build a mushroom classification model to learn the basics of image classification.
The model uses a systematic approach to improve recognition through training the model on different sizes of images fed to the model. 
As of now, the model is about 78% accurate, which isn't too bad, but could be better. 
  - Things to do: 
    - Clean Dataset more
    - Use larger images for training
    - Use original dataset from Kaggle 
    - Find a way to clean data efficiently

Fungi Data originaly found through a kaggle competition on Fungi classification Original Kaggle competition can be found here: https://github.com/visipedia/fgvcx_fungi_comp#data 

The Data used may not be used for comercial purposes.
Data was created by:
“Danish Mycological Society (2016). Danish fungal records database, contributed, maintained and validated by Frøslev, T., Heilmann-Clausen, J., Lange, C., Læssøe, T., Petersen, J.H., Søchting, U., Jeppesen, T.S., Vesterholt, J†., online www.svampeatlas.dk (first download: 6.8.2019)
https://svampe.databasen.org/citation

The original data is 13GB in size, after the transform the folder is 'only' approx 856 MB

Downloaded the file and resized all images locally with a quick python script (provided in repo)
