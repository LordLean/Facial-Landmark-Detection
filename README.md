# Facial-Landmark-Detection

This paper uses a dataset of labelled sample images, labels come in the form of sixty-eight points (IBUG68, shown below) each represented by two separate values: x and y coordinates. Points are grouped in an ascending order depending on the area of the face they map. This is a supervised learning system where the labelled image data is fed into the neural network which will then predict sixty-eight landmarks per image throughout a test set. 
<img src="https://raw.githubusercontent.com/LordLean/Facial-Landmark-Detection/main/Images/figure_68_markup%20(1).jpg" width="500" />

Using metrics such as Euclidean Distance and mean squared error (mse) we can compare different CNN structures and their effects on performance during training.

Final TensorFlow model breakdown:


Example Predictions:


Some face segmentation and a fun filter!
