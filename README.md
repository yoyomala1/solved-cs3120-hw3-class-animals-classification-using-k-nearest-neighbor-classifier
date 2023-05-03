Download Link: https://assignmentchef.com/product/solved-cs3120-hw3-class-animals-classification-using-k-nearest-neighbor-classifier
<br>
(NumPy and data visualization packages are allowed.)

(SKLearn models are allowed.)

<strong>Reference: Slide6 in blackboard</strong>

<strong>Given:</strong>

<strong>K = [3, 5, 7] </strong>

<strong>Distance metrics: L1 and L2 </strong>

<strong>Dataset: animals.zip</strong>

<ol>

 <li><strong>Gather the Dataset</strong>: The Animals datasets consists of 3,000 images with 1,000 images per dog, cat, and panda class, respectively. Each image is represented in the RGB color space. You will preprocess each image by resizing it to 32×32 pixels. Taking into account the three RGB channels, the resized image dimensions imply that each image in the dataset is represented by 32x32x3 = 3,072 integers. <strong>(2pts code)</strong></li>

</ol>




<ol start="2">

 <li><strong>Split the Dataset</strong>: You’ll be using three splits of the data. One split for training, one split for validation and the other for testing. Please randomly partition the data into these three splits. For example, 70% for training, 10% for validation and 20% for testing. Report your final performance only using the testing dataset.</li>

</ol>




<ol start="3">

 <li>Your k-NN classifier will be trained on the raw pixel intensities of the images in the training set. You need to convert the images to data vectors with label.</li>

</ol>




<ol start="4">

 <li><strong>Train the Classifier</strong>: k-NN classifier from sklearn or your own function could be used to train the model. <strong>(2pts code)</strong></li>

</ol>




<ol start="5">

 <li><strong>Evaluate</strong>: Once your k-NN classifier is trained, you should evaluate performance (accuracy, precision, recall, F-measure) on the test set. These scores need to be included in your report. <strong>(2pts)</strong></li>

</ol>




<ol start="6">

 <li>What is the best value of K to use? What is the best distance to use? Answer or analysis of this question needs to be included in your report. <strong>(2pts)</strong></li>

</ol>




<ol start="7">

 <li><strong>Bonus up to 2 pts</strong> for who used own developed KNN model.</li>

</ol>







<strong>Submission</strong>:




Write a report to describe /answer required questions (5 and 6) of your design.

Upload your code with comments as a separate .py or zip file.

<strong>e.g.</strong>

<strong>File1: Assignment3_FirstnameLastname.doc/.pdf (this is the report)</strong>

<strong>+</strong>

<strong>File2: Assignment3_ FirstnameLastname.py (this is the code. only “.py” files accepted. </strong>

<strong><em>            OR</em></strong>

<strong><em>          Assignment3_ FirstnameLastname.zip if you have multiple “.py” files.</em></strong>