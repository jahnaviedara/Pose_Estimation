# Pose_Estimation
Human pose estimation is a computer vision task that involves predicting the positions and orientations of a person's body joints or body parts from an image or video. It aims to capture the spatial configuration of the human body, including the positions of joints like the nose, shoulders, elbows, wrists, hips, knees, and ankles.

This technique has gained significant attention in computer vision research due to its wide range of applications. Pose estimation can be used in various domains such as action recognition, sports analysis, human-computer interaction, augmented reality, virtual reality, surveillance, healthcare, and animation.

In the code, the libraries are imported.

In computer vision, specifically using the OpenCV library, the code net = cv.dnn.readNetFromTensorflow("graph_opt.pb") is used to load a deep neural network (DNN) model from a TensorFlow format file.

The variables inWidth, inHeight, and thr are commonly used to specify parameters for processing an input image using a pre-trained deep learning model.
The BODY_PARTS and POSE_PAIRS are dictionaries used to define the body parts and pose pairs for human pose estimation. These definitions are commonly used in pose estimation algorithms based on deep learning models.

The code provided reads an image file named "image.jpg" using the cv.imread() function from the OpenCV library. The image is then displayed using plt.imshow() from the matplotlib library and as the next part the BGR is changed to RGB.

The definitions for the pose estimation of image and video are written.
