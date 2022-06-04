# AI-Virtual-Painter
An application to draw aerially.The major idea of this project is to proovide a solution for developing a tool that could help young children or the teachers who teach them,to draw some simple drawings or definite shapes to make learning interesting.  

In the modern era of computer, various new technologies have been arising. One such thing is touchless applications that is used or controlled aerially with hand gestures and movements. Augmented reality and virtual reality have come into use which is controlled by gesture controls. Applications that work with gesture controls has started targeting all kinds of users. 
The virtual painter will basically start from getting our hand landmarks and then using the points we can draw on the screen. The main idea is we will be using two fingers for selection of the color or shape or any of the parameters we want to configure and one finger for drawing aerially where the whole process is performed in real-time. 
The major features included in our model are:
1)	A group of colors
2)	Different geometric shapes such as circle, rectangle and ellipse.
3)	Free hand writing
4)	Variable size for the eraser
5)	Changeable parameters of geometric shapes such as radius of the circle.

AI virtual painter mainly uses two python libraries Mediapipe and OpenCv one for getting hand landmarks and other for drawing aerially.

![fd](https://user-images.githubusercontent.com/81897096/172018175-34c539d0-fb3e-479e-a9e6-ccbaf64d9a11.png)
The above figure illustrates the 21 handmarks present in human hand and through which we will be tracking the position of each fingers and decide if it is selection mode or drawing mode.

The Steps to run the code:

Step1: Import the Handlandmark module which contais palms detected adn hand landmarks used to get the position.

Step2: Check number of fingers up which is done while we run the Virtual painter code and place our hand paralled to the web camera of laptop.

Step3: Then the options such as scribble, use different geometric options will be available when you use two fingers which indicates the selection mode you can select different colours and shapes.

Step4: Configure different parameters like the radius pf circe and thickness of erases using the thumb and first finger by changing the distance between them.

Step5: Finally enjoy drawing aerially!!!
