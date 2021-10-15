# Violence_DetectioNet
This paper examined the feature pooling approaches-based Deep Convolutional Neural Networks presented for violence detection in surveillance videos. First, sequential frames were obtained from video images. Then, deep features were extracted from these images using a pre-trained deep convolutional neural network based on the transfer learning approach. These deep features were combined using the Feature Concatenate, Feature Average Pooling, and Feature Standard Deviation approaches suggested in the study. Finally, fully connected, ReLU, fully connected, and Softmax layers were added sequentially after the pooling processes. The three public dataset with violent videos was utilized to test the proposed model. In the experimental results, the highest accuracy scores obtained using the MOVIE, SURV, and the Crowd datasets were 100%, 99.67%, and 98.78%, respectively. These results clearly showed that the proposed model achieved higher accuracy compared to previous studies. 

DATASET;

  - [Crowd violence dataset:](url)Hassner T, Itcher Y, Kliper-Gross O (2012) Violent flows: Real-time detection of violent crowd behavior. In 2012 IEEE Computer Society Conference on Computer Vision and Pattern Recognition Workshops, pp. 1-6.
  - [Fight-detection-surv-dataset-master (SURV)](url):Aktı Ş, Tataroğlu GA, Ekenel HK (2019) Vision-based fight detection from surveillance cameras. In 2019 Ninth International Conference on Image Processing Theory, Tools anD Applications (IPTA), pp. 1-6.
  - [MOVİE violence dataset](url):Serrano Gracia I, Deniz Suarez O, Bueno Garcia G, Kim TK (2015) Fast fight detection. PloS one, 10(4):e0120448.
