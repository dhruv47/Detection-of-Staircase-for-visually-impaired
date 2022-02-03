
# Staircase Detection for Visually Impaired

This project proposes a solution to the problem faced by the visually impaired people for identification of staircase direction.
Step up is more visible than step down which makes it less fatal as compared to step down. The project's model is trained on approx. 3000 images each of Upstairs, Downstairs and no stairs. The model works well with outdoor stair images as well as indoor which depicts it feasible outdoors.  In this paper five classifiers are implemented such as SVM, KNN, Random Forest and Decision tree. Random forest classifier gives the highest accuracy for classification as 93.63%.

Link to download dataset: [Dataset](https://drive.google.com/drive/folders/19afuAHWZhoKWs5v22ezsCQSncACr7h20?usp=sharing)

## Methodology

- A machine learning approach has been implemented to detect the presence and direction of the staircase.  
- The images are captured through the camera module resized and converted to gray scale. 
- SIFT feature extractor extract the feature of these images. 
- K Mean Clustering and PCA techniques are used for dimensionality reduction. 
- The class is predicted based on training data.



## Flowchart

![image](https://user-images.githubusercontent.com/69969189/152385796-06d68f4d-5f58-4984-b5b3-b3e1de879d6e.png)


## Conclusion

The approach presented will detect the type of staircase or no stairs. This will give the user understanding about the surroundings. Blurred or noisy images given as input to the model can lead to wrong predictions. Images taken while the user is constantly moving or traveling can get noisy and may lead to wrong predictions. The system is not able to classify spiral stairs.

Comparison of accuracies of different classifiers used:

![image](https://user-images.githubusercontent.com/69969189/152387354-735d38e3-3099-4ae1-a053-adce6b68c017.png)
