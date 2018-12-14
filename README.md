# Diabetic-Retinopathy
Detection of Anamolies in ratina using Deep Learning.

# What is Diabetic retinopathy?

![Alt text](DR.jpg?raw=true "Title")

People with diabetes can have an eye disease known as diabetic retinopathy. This disease is one of the leading cause of blindness among the peoples in united states. Detection of this disease is possible with the neural network over the ratinal image using several algorithms in deep learning. When the retinal image is given to fully trained convolutional neural network it identifies the anomalies in the retinal image which are the leading cause of the diabetic retinopathy. There are several anomalies in the retinal image if the person is sufferers such as macula, exudates, hemorrhage etc. Sometimes an ophthalmologist also not able to detect them. So using Convolutional neural network we can extract the deep feature of an image which correctly identifies infected macula and exudates. To Identified the anomalies in the retinal image I use Faster RNN NAS which segment outs the infected objects in the retinal image.

# Our Approach 

I used InceptionV3 CNN deep neural network. I used 'transfer learning method' [ in this method the neural net can use the past experience of training to learn new things more efficiently when trained again for doing other tasks] and modified its final layers and then trained the CNN with the training images captured by fundus camera from Kaggle dataset to detect the optical disk and macula and then classify diseased and non-diseased eye images in the diabetic retinopathy medical images (work was done in center of excellence for image and signal processing at my college). The results were really excellent. The error rate was less than 4-5%

# Our Results
Following are the results obtained with CNN.

![Alt text](disc_macula_results/img1.png?raw=true "Title")
![Alt text](disc_macula_results/img2.png?raw=true "Title")
![Alt text](disc_macula_results/img3.png?raw=true "Title")
![Alt text](disc_macula_results/img4.png?raw=true "Title")!
[Alt text](disc_macula_results/img5.png?raw=true "Title")

