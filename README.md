 Project  Classifying DNA sequences into Promoter and Non-promoter classes


### Problem Definition:
As the DNA sequence data are growing rapidly nowadays, the maintenance and annotation of these data are now of great importance. A promoter is necessary for a DNA sequence to be transcribed. With knowing the position of the promoter in the sequence, we can get the starting position of the transcription region that will later be translated into protein sequence. If we have the knowledge of which part of a DNA sequence is a promoter sequence, that promoter sequence can be used to keep the rate of translation from DNA into protein under control. Thus identifying the promoter is essential for DNA sequence analysis. So far many methods and tools have been developed for this purpose and many have achieved high accuracy. In this project, you will train your own model(s) to classify whether a given DNA sequence is a promoter sequence or not.

### Training Data

| Class of Data | Link |
| --- | --- |
| Positive (Promoter) | [Link](https://raw.githubusercontent.com/ram89toronto/Genetics_prediction_hackathon_ga/main/PromoterSequence.txt)
| Negative (Non-Promoter) | [Link](https://raw.githubusercontent.com/ram89toronto/Genetics_prediction_hackathon_ga/main/NonPromoterSequence.txt)

### Test Data
Predict the classes of the sequences given in [this](./data/test.csv) csv file. The predictions should be either 0 (non-promoter) or 1 (promoter). In the test.csv, create a new column called **predictions** and submit the csv file in the link below.

I was able to get best accuracy of 89%, Hoping to see someone get better result than this :)


Thank you !
