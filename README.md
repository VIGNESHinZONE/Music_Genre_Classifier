# Music_Genre_Classifier
An attempt to classify genres across music and imitate behaviour of popular streaming services

#Dowloading_datasets
We use GTZAN genre collection dataset for classification. 
http://marsyas.info/downloads/datasets.html
This dataset was used for the well known paper in genre classification " Musical genre classification of audio signals " by G. Tzanetakis and P. Cook in IEEE Transactions on Audio and Speech Processing 2002.
The dataset consists of 10 genres i.e
Blues
Classical
Country
Disco
Hiphop
Jazz
Metal
Pop
Reggae
Rock
Each genre contains 100 songs. Total dataset: 1000 songs

#PreProcessing
All the .au files were converted to .wav using Pydub library or can also be done in the command line directly by changing extensions
