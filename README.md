# CS4487-MachineLearning-Project

<font size="6">**1.1 Background**</font> <br/>

<u>_What is deepfake?_</u>
When searching on the Internet, it is no surprise that fake images, manipulated videos and audios exist all over the Internet thanks to the advancement of the Internet and different editing software. In recent years,‘Deepfake’ technology has further put the authenticity and reliability of the media posted on the Internet in question. The term deepfake can be separated into two daily words: ‘deep’ and ‘fake’. For ‘deep’, it refers to the technique used, which is known as deep learning and for ‘fake’, it can be describing the creation of synthetic and falsified content. Deepfake can exist in various forms, one common usage is face-swapping in video and digital content, lip-syncing and face synthesis content are also common.
<u>_How deepfakes are made?_</u>

Deepfake has gone easier in these years with the help of powerful tools and algorithms. For the best deepfake performance, creating the models with **autoencoders** or the **generative adversarial network (GAN)** can be the most common deepfake creation algorithm. Using autoencoders, the common encoder can find and learn the similarity between two sets of face images. In the figure, a face image of face B is reconstructed with the mouth shape of face A (as the original mouth shape is upside-down, and now the mouth shape follows face A with a normal heart shape). In short, autoencoder combines the facial features of two target individuals to create a new ‘deepfake’ image.
For higher-level deepfake content creation, the generative adversarial network (GAN) can be adopted. During training, a combative process can be observed. In the GAN architecture, there are generator and discriminator. The generator uses random noise to produce images that are similar to the training data, meanwhile, the discriminator estimates the probability of images coming from real data samples, and also grades the generator for their resembling performance. Therefore, the generator can create high-quality deepfake images based on discriminator feedback, and at the same time it can be a useful tool to detect deepfake content.


<u>_Deepfake effects_</u>
The breakout of ‘Deepfake’ has made a lot of noise in the media space. Although it can create interesting memes for entertainment, deepfake also creates troubles in different aspects. It has been used to commit crimes from fraud to sexual harassment. Criminals use deepfake images and audio to impersonate a CEO to make violent threats. An AI firm also found that 96% of deepfake videos are pornographic by mapping the faces of female celebrities to porn stars. It also creates political and social issues, could you imagine the effect brought by impersonating the footage or the speech of presidents? Therefore, the effects of deepfake can be far beyond our imagination.

<font size="6">**1.2 Model Training - CNN & Resnet**</font> <br/>

<font size="6">**1.3 Results Interpretation**</font>
We have decided to dig into the effects of different parameters. For both CNN and ResNet model, the hyperparameters are as below
- Dropout Rate
- Learning Rate
- Patience of Early Stopping
- Batch Size

![cnn_accuracy](/screenshots/cnn_accuracy.PNG)
![resnet_accuracy](/screenshots/resnet_accuracy.png)
