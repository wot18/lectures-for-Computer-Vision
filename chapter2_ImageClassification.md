# Computer Vision(Machine Vision) for Oversea Phd Candidate

## Chapter 2 Image Classification

Five main points to be discussed in this chapter:

1. "What is an image classification task, and what are its application scenarios?" This section will presumably define image classification and explore various real-world applications where this technology is utilized.

2. "What are the difficulties in image classification tasks?" Here, the challenges and limitations faced when performing image classification tasks will likely be addressed.

3. "Is it feasible to use rule-based methods?" This point discusses the viability and effectiveness of using rule-based or deterministic approaches in image classification compared to more modern techniques.

4. "What is data-driven image classification?" This part will probably introduce and explain the concept of data-driven image classification, which relies on statistical models trained with large amounts of data to make predictions.

5. "What are the common evaluation indicators for classification tasks?" Lastly, this section will likely outline key performance metrics used to assess the accuracy and efficiency of different image classification algorithms.

### What is an image classification task, and what are its application scenarios?

Image classification is one of core tasks in computer vision, whose goal is to distinguish images of different categories based on the different characteristics reflected in the image information.

It can be simplely treated as **selecting a category label for a given input image from a set of known category labels**.

<center> <img src='.\\figures\\fig2-1.jpg'> </center>

<center> Fig.2-1 Image classification task </center>

**Application of Image Classification: Flower Recognition**

Image classification plays a crucial role in recognizing and categorizing objects within digital images, and one of its fascinating applications is in the field of botany, specifically for flower recognition. By leveraging advanced machine learning algorithms, particularly deep convolutional neural networks (CNNs), computers can now accurately identify various species of flowers from images with high precision.

In the context of the provided image, the process of flower recognition begins by collecting a dataset of labeled flower images, each tagged with its corresponding species name. This dataset is then used to train a classification model. During training, the model learns to extract features from the images, such as color patterns, petal shapes, and leaf structures, which are characteristic of different flower species.

Once the model has been sufficiently trained, it can be deployed to classify new, unseen images of flowers. When an image is fed into the system, the model processes the image, extracts the relevant features, and compares them against the learned patterns to predict the most likely species of the flower depicted in the image.

This technology not only aids amateur botanists and enthusiasts in identifying flowers they encounter but also supports professionals in fields such as environmental science, where accurate identification of plant species is essential for ecological studies and conservation efforts.

<center> <img src='.\\figures\\fig2-2.jpg'> </center>

<center> Fig.2-2 Flower recognition </center>

**Application of Image Classification: Dog Identification**

Image classification plays a significant role in recognizing and categorizing objects within digital images, and one of its popular applications is in the field of animal recognition, particularly for dog identification. By leveraging advanced machine learning algorithms, particularly deep convolutional neural networks (CNNs), computers can now accurately identify various dog breeds from images with high precision.

In the context of the provided image, the process of dog identification begins by collecting a dataset of labeled dog images, each tagged with its corresponding breed name. This dataset is then used to train a classification model. During training, the model learns to extract features from the images, such as facial structure, coat length, and color patterns, which are characteristic of different dog breeds.

Once the model has been sufficiently trained, it can be deployed to classify new, unseen images of dogs. When an image is fed into the system, the model processes the image, extracts the relevant features, and compares them against the learned patterns to predict the most likely breed of the dog(s) depicted in the image.

This technology not only aids pet owners and enthusiasts in identifying dog breeds they encounter but also supports professionals in fields such as veterinary medicine, where accurate identification of dog breeds is essential for understanding potential health risks and providing appropriate care.

Moreover, image classification for dog identification can have broader implications in areas such as lost pet recovery, where accurate breed determination can assist in matching lost pets with their owners through online databases and social media platforms.

In conclusion, image classification technology offers valuable assistance in accurately identifying dog breeds in digital images, contributing to improved pet care, lost pet recovery, and overall appreciation of our four-legged friends.

<center> <img src='.\\figures\\fig2-3.jpg'> </center>

<center> Fig.2-3 Dog breed identification using image classification. </center>

### What are the difficulties in image classification tasks?

**Bridging the semantic gap** is considered a major difficulty in image classification because it involves developing computational models that can interpret visual data in a way that aligns with human understanding. 

In other words, the goal is to create systems that can not only recognize objects and scenes but also understand their meaning and context, just as humans do. 

Achieving this level of comprehension requires sophisticated algorithms and deep learning techniques to enable artificial intelligence to infer meaning from raw pixel data.

<center> <img src='.\\figures\\fig1-4.jpg'> </center>

<center> Fig.2-4 The semantic gap in image classification. </center>

Specifically, the main challenges faced in image classification include: 

* viewpoint variations, 

* lighting changes, 

* scale variations, 

* occlusions, 

* deformations, 

* background clutter, 

* intra-class variations, 

* motion blur, 

* a large number of categories.

**Viewpoint variations** 

When discussing the application of image classification technology, we often encounter such a challenge: assume that our image classification algorithm can exhibit excellent accuracy on images captured at specific angles. However, once the perspective changes, it leads to significant variations in the appearance of the images. In such cases, our meticulously designed algorithms may fail to maintain their original effectiveness. This is one of the reasons why we need to continuously optimize and improve our algorithms in practice, to ensure they can operate stably in various complex and changing environments and adapt to image features from different perspectives.

<center> <img src='.\\figures\\fig2-5.jpg'> </center>

<center> Fig.2-5 Viewpoint variations in image classification. </center>

**Lighting changes**

Lighting conditions can significantly affect the appearance of an object in an image. For example, consider the case of penguin statues. In bright sunlight, the penguin statues may appear white, while in dimly lit conditions, the they may appear darker. This variation in lighting can lead to significant changes in the pixel values of the image, which can in turn affect the performance of the image classification algorithm.

<center> <img src='.\\figures\\fig2-6.jpg'> </center>

<center> Fig.2-6 Lighting changes in image classification. </center>

**Scale variations**

Scale variations refer to the changes in the size of an object in an image. For example, consider the case of a mac. In right part of the image, the mac may appear quite big, about half of the person's height, while in right part of the image, the mac may appear small, mays only as big as Yao's hand. This variation in scale can lead to significant changes in the pixel values of the image, which can in turn affect the performance of the image classification algorithm.

<center> <img src='.\\figures\\fig2-7.jpg'> </center>

<center> Fig.2-7 Scale variations in image classification. </center>

**Occlusions**

Occlusions refer to the blocking or covering of an object in an image. For example, Can we recognize the cat if only part of its face or tail is visible outside the sofa or the grass, when the cat hides in such a way?. This variation in occlusions can lead to significant changes in the pixel values of the image, which can in turn affect the performance of the image classification algorithm.

<center> <img src='.\\figures\\fig2-8.jpg'> </center>

<center> Fig.2-8 Occlusions in image classification. </center>

**Deformations**

Deformations refer to the changes in the shape of an object in an image. Deformations are common in image recognition tasks targeting humans or animals. For example, a cat in an image may show significant changes in appearance depending on whether it is lying down, sitting, or walking. Can image classification algorithms identify it as the same cat despite these changes?

<center> <img src='.\\figures\\fig2-9.jpg'> </center>

<center> Fig.2-9 Deformations in image classification. </center>

**Background clutter**

Background clutter refers to the presence of irrelevant objects or elements in the background of an image. When the object we want to recognize is very similar to the background, can image classification algorithms still capture enough distinguishing features to separate the target from the background?

<center> <img src='.\\figures\\fig2-10.jpg'> </center>

<center> Fig.2-10 Background clutter in image classification. </center>

**Intra-class variations**

Intra-class variations refer to the variations within a class of objects. For example, different chairs may have different colors, sizes, and shapes. Can image classification algorithms distinguish between different chairs within the same class? Even if humans have never sat on or seen a particular chair before, they can still recognize it as a chair, regardless of its shape or form.

<center> <img src='.\\figures\\fig2-11.jpg'> </center>

<center> Fig.2-11 Intra-class variations in image classification. </center>

**Motion blur**

Motion blur refers to the blurring of an image caused by the movement of the object or the camera. Motion blur in visual recognition can lead to issues such as decreased accuracy in object detection and recognition, increased difficulty in feature extraction, higher complexity in tracking tasks, increased errors in 3D reconstruction and pose estimation, as well as limitations in scene understanding, all of which affect the overall performance of visual processing.

<center> <img src='.\\figures\\fig2-12.jpg'> </center>

<center> Fig.2-12 Motion blur in image classification. </center>

**A large number of categories**

A large number of categories refers to the presence of a large number of different classes in an image classification task. This can lead to increased complexity in the classification process, as the algorithm must learn to distinguish between a large number of different classes. Additionally, it can also lead to increased computational cost and memory requirements, as the algorithm must store and process a large number of different features and labels.

<center> <img src='.\\figures\\fig2-13.jpg'> </center>

<center> Fig.2-13 A large number of categories in image classification. </center>

### Is it feasible to use rule-based methods?

There is a paradigm for rule-based methods in image classification as shown in Fig.2-14. It is usually recognize a object through hard-coded rules. 

<center> <img src='.\\figures\\fig2-14.jpg'> </center>

<center> Fig.2-14 Rule-based methods in image classification. </center>

For example, to recognize a cat, how can hard-coded approaches be utilized?. We can identify the angle of a cat's ears through edge detection first, and then specifying rules for recognizing cat ears based on the angular relationships.

<center> <img src='.\\figures\\fig2-15.jpg'> </center>

<center> Fig.2-15 A hard-coded method for cat. </center>

However, identifying and formulating precise and reliable rules to accurately define and recognize a real-world object is typically a challenging endeavor, as it requires not only a deep understanding of the object's characteristics but also the ability to account for variations and exceptions that may occur under different conditions or environments.

### What is data-driven image classification?

Data-driven image classification refers to a method of image classification that relies on the use of data to train a model to recognize objects or patterns in images. This method involves collecting a large dataset of images that contain the objects or patterns that the model is intended to recognize, and then using this dataset to train the model to learn the features and characteristics of these objects or patterns. The model is then used to classify new images based on the features and characteristics that it has learned from the training data.

Typically, data-driven image classsification methods include three steps:

1. Data set construction

2. Classifier design and learning

3. Classifier decision

The classifier design and learning process can be depicted in Fig.2-16.

<center> <img src='.\\figures\\fig2-16.jpg'> </center>

<center> Fig.2-16 The classifier design and learning process. </center>

The classifier decision process can be depicted in Fig.2-17.

<center> <img src='.\\figures\\fig2-17.jpg'> </center>

<center> Fig.2-17 The classifier decision process. </center>

**Image representation** is the first step in the classifier design and learning process. The image representation process involves converting the raw pixel data of an image into a format that can be used by the classifier to recognize objects or patterns. This can involve techniques such as edge detection, color histogram, and feature extraction.

Three image representation methods are listed bellow:

1. Pixel representation

2. Global feature representation, such as color histogram, texture, and shape

3. Local feature representation, such as SIFT, SURF, and HOG
* Pixel representation is the simplest image representation method, which uses the raw pixel values of an image as the input to the classifier. However, this method has several limitations, such as sensitivity to noise and lack of spatial information.

<center> <img src='.\\figures\\fig2-18.jpg'> </center>

<center> Fig.2-18 Pixel representation. </center>

* Global feature representation methods use a set of global features to represent an image. These methods are more robust to noise and can capture the overall structure of an image. However, they may not be able to capture the local details of an image.

<center> <img src='.\\figures\\fig2-19.jpg'> </center>

<center> Fig.2-19 Global feature representation. </center>

* Local feature representation methods use a set of local features to represent an image. These methods are more robust to noise and can capture the local details of an image. However, they may not be able to capture the overall structure of an image.

<center> <img src='.\\figures\\fig2-20.jpg'> </center>

<center> Fig.2-20 Local feature representation. </center>

Based on local feature representation, a classifier paradigm called "Bag of Visual Words" (BoVW) is proposed. The BoVW method is a popular approach for image classification, which is based on the bag-of-words (BoW) model. The BoVW method is a combination of local feature extraction and BoW model.

The BoVW method can be depicted in Fig.2-21.

<center> <img src='.\\figures\\fig2-21.jpg'> </center>

<center> Fig.2-21 The BoVW method. </center>

The BoVW method can be divided into three steps:

1. Local feature extraction: Extract local features from the image, such as SIFT, SURF, and HOG.

2. Vocabulary construction: Construct a visual vocabulary using the extracted local features. The visual vocabulary is a set of visual words, which are clusters of local features.

3. Image representation: Represent the image using the visual vocabulary. The image representation is a histogram of visual words, which is a bag-of-words model.

As to the **Classification Model**, the following lists six common machine learning algorithms:

- K-Nearest Neighbors (KNN) Classifier: This is an instance-based learning method that predicts the class of new samples based on one or more known nearest neighbors.

- Naive Bayes Classifier: Naive Bayes classification is a statistical classification technique that uses Bayes' theorem for probabilistic inference, classifying by calculating the posterior probabilities of each category.

- Linear Classifier: A linear classifier is a model that uses a linear function to classify data, including models such as Support Vector Machines (SVM).

- Support Vector Machine (SVM) Classifier: A Support Vector Machine (SVM) is a supervised learning model used for binary and multiclass classification tasks. Its core idea is to find an optimal hyperplane that separates data of different classes.

- Neural Network Classifier: A neural network is a mathematical model that mimics the structure of the human brain, capable of solving various complex problems, including classification and regression.

- Random Forest: Random Forest is an ensemble learning method that improves classification accuracy and robustness by constructing and combining multiple decision trees.

As to **Loss Function**, the following lists three common loss functions:

This image contains a list of loss functions commonly used in machine learning:

- 0-1 Loss: Also known as the 0-1 misclassification error, it measures the difference between the predicted label and the true label.

- Multiclass Support Vector Machine Loss: This loss function is used in support vector machines for multi-class classification tasks.

- Cross-Entropy Loss: Also called log loss, cross-entropy loss quantifies the dissimilarity between the predicted probability distribution and the true distribution.

As to "Optimization Algorithms", the following presents two categories of optimization methods commonly used in image classification:

- First-order Methods:
  
  - Gradient Descent: An iterative optimization algorithm that updates parameters using the derivative of the loss function with respect to the input variables.
  - Stochastic Gradient Descent: A variant of gradient descent where only one training example is used per iteration instead of the entire dataset.
  - Mini-batch Gradient Descent: A compromise between full batch gradient descent and stochastic gradient descent, where a small subset of the dataset is used at each iteration.

- Second-order Methods:
  
  - Newton's Method: An optimization algorithm that uses the Hessian matrix to estimate curvature and find minima faster than first-order methods.
  - BFGS: A popular quasi-Newton method that approximates the Hessian matrix without explicitly computing its values.
  - L-BFGS: Limited-memory BFGS, a variant of BFGS that reduces computational complexity by storing only a few terms of the Hessian approximation.

The **Training Process** mainly has the following steps:

This image outlines several steps involved in the process of training a machine learning model:

- Data Partitioning: Splitting the dataset into separate parts, typically train/test sets, for model development and evaluation.

- Data Preprocessing: Cleaning, transforming, and preparing raw data for analysis, which can include feature scaling, encoding categorical variables, and handling missing values.

- Data Augmentation: Generating additional training examples from existing ones by applying random transformations, increasing the diversity of the dataset and improving generalization.

- Underfitting vs. Overfitting: Balancing the trade-off between underfitting (high bias), which occurs when the model is too simple, and overfitting (high variance), which happens when the model becomes too complex and fits the noise in the data rather than the underlying patterns.
  
  - Reducing Algorithm Complexity: Adjusting model complexity to avoid overfitting, often achieved through techniques like regularization or simpler model architectures.
  
  - Weight Regularization: Techniques like L1 and L2 regularization, which add penalties to the loss function to discourage large weights and promote simpler models.
  
  - Dropout Regularization: A technique that randomly drops neurons during training to prevent co-adaptation and improve generalization.

- Hyperparameter Tuning: Selecting optimal values for model parameters that are not learned directly from the data, such as learning rate, regularization strength, or number of hidden layers.

- Model Ensemble: Combining predictions from multiple models to improve performance and reduce errors, often done through techniques like bagging, boosting, or stacking.

### What are the common evaluation indicators for classification tasks?

The simplest evaluation metrics for image classification tasks are:

- Accuracy: The proportion of correctly classified samples out of all samples. Mathematically, it can be expressed as:

$$
\text{Accuracy} = \frac{\text{Number of correctly classified samples}}{\text{Total number of samples}}  \tag{2-1}
$$

- Error Rate: Complementary to accuracy, it represents the proportion of incorrectly classified samples. It can be calculated as:

$$
\text{Error Rate} = 1 - \text{Accuracy}  \tag{2-2}
$$

These metrics provide a basic understanding of how well a classification model performs overall, but they do not account for potential imbalances in the dataset. For datasets with unequal class distributions, other metrics like precision, recall, F1 score, or area under the ROC curve (AUC-ROC) may offer a more comprehensive assessment.

The difference between top-1 and top-5 accuracy is that top-1 accuracy measures the proportion of samples where the model's predicted class matches the true class exactly, while top-5 accuracy measures the proportion of samples where the true class is among the top 5 predicted classes.

For example, if a model predicts the top 5 classes for a sample as [Class A, Class B, Class C, Class D, Class E], and the true class is Class B, the sample would be considered correctly classified for top-5 accuracy but not for top-1 accuracy.

Therefore, top-1 accuracy is a stricter measure than top-5 accuracy, as it requires the model to predict the exact correct class, while top-5 accuracy allows for some margin of error by considering the true class among the top 5 predicted classes.

<center> <img src='.\\figures\\fig2-22.jpg'> </center>

<center> Fig.2-22 The top-1 accuracy. </center>

<center> <img src='.\\figures\\fig2-23.jpg'> </center>

<center> Fig.2-22 The top-5 accuracy. </center>

Therefore, look back to 2015, the success of ResNet is limited to top-5 accuracy, and the dataset is limited to ImageNet.

<center> <image src='.\\figures\\fig1-24.jpg' width='800' ></center>

<center>Fig.2-23 The success of ResNet.</center>