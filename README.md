# Facial-Landmark-Detection

This paper uses a dataset of labelled sample images, labels come in the form of sixty-eight points (IBUG68, shown below) each represented by two separate values: x and y coordinates. Points are grouped in an ascending order depending on the area of the face they map. This is a supervised learning system where the labelled image data is fed into the neural network which will then predict sixty-eight landmarks per image throughout a test set. 
<br>
<p align="center">
  <img src="https://raw.githubusercontent.com/LordLean/Facial-Landmark-Detection/main/Images/figure_68_markup%20(1).jpg" width="300" />
</p>

Using metrics such as Euclidean Distance and mean squared error (mse) we can compare different CNN structures and their effects on performance during training.

Final TensorFlow model breakdown:
<br>
<p align="center">
  <img src="https://raw.githubusercontent.com/LordLean/Facial-Landmark-Detection/main/Images/final_model_flow%20(1).png" width="800" />
</p>

Example Predictions:
<br>
<p align="center">
  <img src="https://raw.githubusercontent.com/LordLean/Facial-Landmark-Detection/main/Images/Example%20Images%20(1).png" width="700" />
</p>

Some face segmentation and a fun filter!
Flow            |  Demo
:-------------------------:|:-------------------------:
![](https://raw.githubusercontent.com/LordLean/Facial-Landmark-Detection/main/Images/graphical_demo%20(1).png)  |  ![](https://raw.githubusercontent.com/LordLean/Facial-Landmark-Detection/main/Images/predicted_graphical_effect.png)
