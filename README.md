# Arabic Handwritten Characters Recognition - AI-Pro - ITI
Can you recognize Arabic handwritten characters?

## Data Description
You are provided arabic handwritten characters images that you should classify each image and give it a label.
 
## File descriptions
- train/ - Folder containing training set photos of the form {id}.png, where {id} is a unique image ID.
- train.csv - The id column gives the image ID and label gives the label.
- test/ - Folder containing test set photos of the form {id}.png, where {id} is a unique image ID.
- test.csv - The id column gives the image ID.
- sample_submission.csv - a sample submission file in the correct format

## Data fields
- id - image ID.
- label - the label of the image. It ranges from 1 to 28 and corresponds to the Arabic characters.

## Evaluation
The evaluation metric for this competition is accuracy.

## Compition Linke
[Arabic Handwritten Characters Recognition](https://www.kaggle.com/c/arabic-hwr-ai-pro-intake1)

## Acknowledgement
- [dependent paper in the solution](https://link.springer.com/content/pdf/10.1007/s00521-020-05070-8.pdf)
- The dataset provided in this competition is obtained from [here](https://www.kaggle.com/mloey1/ahcd1).
*This competition is for educational purposes only.*
