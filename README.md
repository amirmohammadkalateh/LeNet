# LeNet
## LeNet: A Simple Convolutional Neural Network for Image Classification

LeNet is a pioneering convolutional neural network (CNN) architecture developed by Yann LeCun and colleagues in the late 1980s and early 1990s. It is historically significant as one of the first successful applications of CNNs, primarily designed for handwritten and machine-printed character recognition. LeNet laid the groundwork for many subsequent advancements in deep learning and computer vision.

### Key Features:

* **Convolutional Layers:** Utilize convolutional filters to automatically learn spatial hierarchies of features from input images.
* **Subsampling (Pooling) Layers:** Reduce the spatial dimensions of feature maps, providing translational invariance and reducing computational complexity.
* **Fully Connected Layers:** Combine the extracted features for final classification.
* **Activation Functions:** Introduce non-linearity, originally using the hyperbolic tangent (tanh) function in its earlier versions. Modern implementations often use ReLU.

### LeNet-5 Architecture (Most Well-Known Version):

The LeNet architecture typically refers to LeNet-5, which consists of the following layers:

1.  **Input Layer:** Accepts a grayscale image of a fixed size (e.g., 32x32 pixels).
2.  **Convolutional Layer (C1):** Applies convolutional filters to the input image, extracting local features.
3.  **Subsampling Layer (S2):** Performs pooling (typically average or max pooling) to reduce the spatial size of the feature maps from C1.
4.  **Convolutional Layer (C3):** Further extracts more complex features from the pooled feature maps.
5.  **Subsampling Layer (S4):** Again, performs pooling to reduce the spatial size of the feature maps from C3.
6.  **Fully Connected Layer (F5):** Flattens the output of the last pooling layer and connects it to a fully connected layer.
7.  **Fully Connected Layer (F6):** Another fully connected layer.
8.  **Output Layer:** Typically a fully connected layer with a number of neurons equal to the number of classes, often using a softmax activation function for classification.

### Significance:

LeNet demonstrated the effectiveness of CNNs for image recognition tasks and introduced fundamental concepts that are still crucial in modern CNN architectures. Its success in recognizing handwritten digits, for applications like postal code recognition and bank check processing, highlighted the potential of deep learning for real-world problems.
