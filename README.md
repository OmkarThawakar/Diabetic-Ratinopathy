# Diabetic-Retinopathy
Detection of Anamolies in ratina using Deep Learning.

# What is Diabetic retinopathy?

![Alt text](DR.jpg?raw=true "Title")

People with diabetes can have an eye disease known as diabetic retinopathy. This disease is one of the leading cause of blindness among the peoples in united states. Detection of this disease is possible with the neural network over the ratinal image using several algorithms in deep learning. When the retinal image is given to fully trained convolutional neural network it identifies the anomalies in the retinal image which are the leading cause of the diabetic retinopathy. There are several anomalies in the retinal image if the person is sufferers such as macula, exudates, hemorrhage etc. Sometimes an ophthalmologist also not able to detect them. So using Convolutional neural network we can extract the deep feature of an image which correctly identifies infected macula and exudates. To Identified the anomalies in the retinal image I use Faster RNN NAS which segment outs the infected objects in the retinal image.

# Our Approach 

FasterRNN_NAS and InceptionV3 CNN Deep Neural Network Architecture are used for the detection and classification of vital parts from the human eye. The 'Transfer Learning Method' [ In this method the neural net can use the past training experience to learn new things efficiently when trained again for doing analogically similar tasks] and modified its final layers [Desicion layers] and then trained the CNN with the training images captured by fundus camera from Kaggle dataset to detect the optical disk and macula and then classify diseased and non-diseased eye images in the diabetic retinopathy medical images (work was done in Center of Excellence for Image and Signal Processing at SGGS). The results were promising. The detection error rate was less than 4-5%.

New CNN architecture is making old Image processing algorithms absolete. The amount of human labour required for developing just a feature extraction method was huge compared to the current method. The CNN can be used in detection of specific components from biomedical images with ease. Some architecture like NASNet are being developed by Google AUTOML project with which no human developed algorithm can compete.




# Our Results
Following are the results obtained with CNN.

![Alt text](disc_macula_results/img1.png?raw=true "Title")
![Alt text](disc_macula_results/img14.png?raw=true "Title")
![Alt text](disc_macula_results/img11.png?raw=true "Title")
![Alt text](disc_macula_results/img12.png?raw=true "Title")!



CNN Training Info: PC : Workstation Xeon Processor, 16GB GPU, Xenial Xerus Ubuntu OS.
Dataset: Kaggle Ratinal Image dataset for Diabetic Retinopathy.









