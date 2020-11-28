# AKT-Image-Classification-Blaha-Piringer-Gratzl
## Team
 - Blaha Dominik
 - Piringer David
 - Gratzl Maximilian
 
## Aufgabe
Image-Classification of following animals:
 - chicken
 - elefant
 - sheep
 - spider

## [Dataset](https://www.kaggle.com/alessiocorrado99/animals10)

## Challenges
### Selection of a dataset
The selected dataset contained a lot of pictures that showed only parts of animals or even completely different animals.
We decided to remove such images from the dataset which dramatically increased the accuracy of the network.

### Overfitting
As we encountered massive overfitting (training accuracy was much higher than the validation accuracy) we tried to mitigate this problem with following actions:
 - Addition of a dropout layer