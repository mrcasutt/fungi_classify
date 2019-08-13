A naive approach to classify mushrooms. 
Following the Fastai course, I decided to try and build a mushroom classification model to learn the basics of image classification.
The model uses a systematic approach to improve recognition through training the model on different sizes of images fed to the model. 
As of now, the model is about 78% accurate, which isn't too bad, but could be better. 
  - Things to do: 
    - Clean Dataset more
    - Use larger images for training
    - Use original dataset from Kaggle 
    - Find a way to clean data efficiently

Fungi Data originaly found through a kaggle competition on Fungi classification Original Kaggle competition can be found here: https://github.com/visipedia/fgvcx_fungi_comp#data https://svampe.databasen.org/citation

Original Data can be found here: 'https://data.deic.dk/public.php?service=files&t=2fd47962a38e2a70570f3be027cea57f&download'

The original data is 13GB in size, after the transform the folder is 'only' approx 856 MB

Downloaded the file and resized all images locally with a quick python script
