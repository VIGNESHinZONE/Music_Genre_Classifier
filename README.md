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

## PreProcessing

All the .au files were converted to .wav using Pydub library or can also be done in the command line directly by changing extensions

# Feature_Extraction
'tempo','zcr','spec_bandwidth','rms','spec_centroid','spec_rolloff','chrom_spec'
Data has extracted using Librosa library. Features Extracted were the following:-

1)Zero Crossing Rate

2)Spectral Centroid

3)Spectral Rolloff

4)Mel-Frequency Cepstral Coefficients(mfcc)

5)Chroma Frequencies

6)Spectral Bandwidth

7)RootMeanSquare

8)tempo

And these 8 features appended to give a 57 length feature which is later reduced to 37 length feature

# Exploratory_Data_Analysis
Used to identify the redundant features

# Classifaction
Diffrent classification and Deep Learning models were used to classify data. Diffrent parameters were used to tune the model

# Results
SVM gave the highest test accuracy with .82 percent and seemed to perform very well in predicting Classical, Metal,Pop genres. But gave poor accuracy with Reggae, Disco, Country genres

# Acknowledgement

Thank ACM Student Chapter for giving this oppurtunity
