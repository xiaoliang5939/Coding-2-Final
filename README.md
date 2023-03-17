# Coding-2-Final
In ofApp.cpp, we need to implement the setup(), update(), draw(), mouseMoved(), generateCircles() and updateCircles() functions.

In this program, we also need to initialize the camera and texture in the setup() function and set the camera's frame rate and device ID. We also need to use the getColor() function in the draw() function to get the color of the pixel and select the pink color based on the brightness value. We use the ofDrawRectangle() function to draw the Mosaic rectangle for each pixel. We calculate the speed of each small circle based on mouse position in the mouseMoved() function. In the generateCircles() function, we initialize 100 small circles and randomly distribute them in the window. In the updateCircles() function, we update the position of the small circle and regenerate it if necessary.

By adding a Mosaic effect to the camera footage, we simplify the complex and changing nature scene into a grid of colors. The shades of the colors represent different levels of brightness and hue. This suggests that when viewing natural landscapes, people may go through a variety of simplifying and filtering processes to make them more consistent with our perception and cognition.

![image](https://user-images.githubusercontent.com/76156342/225954118-154773f1-a40d-4b38-a5cd-5e2200a627d4.gif)

And in this simplified natural scene, we added the element of small white dots. These little dots represent the human presence, moving through nature at different speeds and in different ways. At the same time, they follow the mouse when it appears. This symbolizes the presence and interaction of human beings in the natural environment, and they are free to adapt to the environment and interact with nature.

Through this work, we can feel the harmonious coexistence between nature and human beings. In this design, nature and human beings are not isolated, but connected and interacting with each other. Through this work, we can reflect on the way we exist in the natural environment and how to live in harmony with nature
