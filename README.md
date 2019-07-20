# X-ray Classifier 
![](https://i.imgur.com/82zQh3F.png)

## Highlights 
* [Local Binary Patterns](https://en.wikipedia.org/wiki/Local_binary_patterns)

* [Support-vector Machines](https://en.wikipedia.org/wiki/Support-vector_machine)

* [Lung X-Ray Dataset](http://dx.doi.org/10.17632/rscbjbr9sj.2#file-41d542e7-7f91-47f6-9ff2-dd8e5a5a7861 )


## Description
A Matlab application that allows users to classify Lung X-rays as **Healthy** or **Diseased**. 

It relies on the use of Local Binary Patterns (LBP) as a visual descriptor to compile a feature vector for image in the training dataset. LBP was mainly used used due to its low computational complexity and low sensitivity to changes in illumination. Once each feature vector is generated, it is stored in a 2D array.

It also relies on the binary linear classifier, Support Vector Machine (SVM). The application uses it to generate a predictive model based on the labels of each image and its corresponding feature vector from the 2D array. 

Finally, once the SVM has generated a classification model, the application uses it to classify unseen images.

### Additional features
The application also allows users to train and generate their own image classification model on a given datasets. Users can also test  their classification models to find out how well it performs.

## Success rate
On the given Test Data contained in the source above, the algorithm has a success rate of **64%**