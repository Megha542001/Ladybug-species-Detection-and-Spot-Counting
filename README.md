# Ladybug-Species-Detection-and-Spot-Counting

## I. Context

Harmonia axyridis, commonly known as the Asian lady beetle , was introduced massively in Europe during the 1980s for aphid control. However, their rapid proliferation has led to them being considered invasive due to their competition with local species for resources [1].

The aim of this lab project is to develop a Machine Learning approach to automatically detect the species of ladybugs and count the number of spots on an image.

## II. Material

The dataset consists of RGB images (`im-*bug id*_im.png`) and segmentations (`im-*bug id*_seg.png`) of 200 ladybugs. Each ladybug segmentation image associates homogeneous color regions with distinct numbers.

## III. Training phase

The training phase, spanning the first three sessions, involves:

- Spot counting on the training dataset and updating the `spot_number` column in `training_labels.csv`.
- Data exploration and quality control to understand dataset complexity and distribution.
- Feature extraction, visualization, and saving the features in a CSV file.
- Training machine learning algorithms for species classification, proposing clustering, and spot counting.

## IV. Test phase

The test phase, during the final session, applies the trained model on 50 unseen ladybugs from the test dataset and saves predictions in `test_labels.csv`.

## V. Expected outputs

At the end of the project session, one team member must submit two files on Moodle:

- The `.ipynb` code file with structured, commented code and team member names mentioned.
- The CSV prediction file with columns for test image identifiers, predicted labels, and the predicted number of spots.

## VI. Grading

Grading is divided into three parts:

- Justification of feature and ML framework choices, compliance, and quality of the `.ipynb` file 
- Clustering and visualization tasks 
- Accuracy for species classification and Root Mean Squared Error (RMSE) for spot counting tasks 

## VII. Reference

[1] [Source Article](https://france3-regions.francetvinfo.fr/grand-est/faut-il-se-mefier-coccinelles-asiatiques-1652776.htm)
