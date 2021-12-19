# Fashion Mnist : The Hello World Of Computer Vision
This will be a sequence of repositories. A step towards perfecting the skills in Deep Learning and Computer Vision. Beginning from the fundamental CNN Architectures and driving towards the GANs, AutoEncoders, and Attention-CNNs..

Starting with standard imports like importing Tensorflow, NumPy, and Matplotlib. 

Then downloaded the data using Keras, scaled it down to ranging between 0 - 1 and Visualized the data to understand it better.

Here comes the most pleasing part, making the model's architecture.
This architecture is a simple CNN consisting only of Convolutional Layers(plus pooling and Dense layers). 

1. First, build a BaseLine Model in order to make a threshold for the forthcoming models.

2. Created the first version of the CNN Architecture, went through a series of revising the model's architecture. Saw various ups and downs.

3. Made 6 Models with different architectures, then decided the best model based on accuracy.

4. Using the best model(so far) to make predictions and visualize them, did something amazing to get insights into the model's performance.

5. Once again compared the model on the ground of Precision, Recall and F1 Score. This was a game-changer. Have a look at the code.

# CNN Architectures : Analysing And Making Different Models

Discussed the most popular and state-of-the-Art(SoTA) Computer Vision models i.e CNN Architecture. Discussed everything from the insights of the Architecture to the important judgment we can make from the model and finally coded them from scratch with the CIFAR10 dataset. The list encloses : 

1. LeNet
2. AlexNet
3. ZF-Net
4. GoogLeNet
5. ResNet
6. Xception
7. SENet

# Transfer Learning : Using Pretrained CNN models for custom task

Used some of the well-known models like the ResNet and Xception. These models were pre-trained on the imagenet Dataset. 

1. In the initial part learned to import the pre-trained models from Keras and performed the preprocessing steps required for the Models. 

2. In the second part learned to change the pre-trained models as per our requirements and train them to learn our dataset.

# OpenCV - The Computer Vision Library

OpenCV is a library of programming functions mainly aimed at real-time computer vision. Originally developed by Intel, it was later supported by Willow Garage then Itseez. The library is cross-platform and free for use under the open-source Apache 2 License.

1. Learned to use OpenCV to read Images/Videos from your Machine.
2. Performed transformations in the Image like Resizing, Color Channels, etc.
4. Drawing bounding boxes, Contour Detection, Edge Detection, Blurring & Smoothning Techniques, and Masking Images.
5. Also plotted the Histograms for gray and color channels.
