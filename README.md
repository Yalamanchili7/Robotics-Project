# Robotics-Project
Project a: Build a self balancing bike  https://drive.google.com/drive/folders/10-d80_GrTbm9J_UEKpSA1n_Wq1KBIYUA?usp=drive_link

a.1: Test external mode with WiFi 

a.2: Balance with straight motion : The bike should travel in a straight line

a.3: Balancing with Steering : The bike should travel in a circle ( or make an 8)


Project b: Build a Webcam controlled  rover: Build and program a rover that can navigate between given reference points using a camera to locate its position and move objects with a forklift mechanism

b.1:

Throughout the previous exercises, you saw how the rover can plan its path from a starting location to the target and finally to a specified endpoint location. One caveat with this approach is that there is no feedback on rover position other than the encoder data. If the wheels start slipping or the encoder data is noisy, you'll have problems.

It would be a good practice to have multiple sensors providing feedback on rover position to mitigate these potential issues. As you saw in section 7, you can send signals from desktop MATLAB to a deployed Simulink model using Wi-Fi blocks. For the final challenge, implement a path-planning algorithm on the rover that uses the localization algorithm from section 5 to provide additional feedback.

This is your final challenge. Go create an awesome Webcam controlled rover!


Project c: Build a Drawing robot: Build and program a robot that can duplicate any drawing it’s given on a whiteboard

c.1

Throughout this project, you've drawn images on the whiteboard using only one marker. However, your drawing robot can hold two markers. It would be nice if you could draw images that have more than one color. How might you go about doing this?

The simplest approach would be to alternate colors for each line segment. Another approach might be to group the objects in the image based on how close they are to one another and draw each group with the same color. Or, combine two different images and draw each in a different color. Maybe you could identify line traces of different colors within a single image and draw them separately. How would you do that using image processing? Try using the Color Thresholder app from Image Processing Toolbox. Your final challenge is to come up with an interesting way to create drawings that use multiple marker colors. You can try one of the ideas listed above or come up with your own. Implement the solution in MATLAB, and then draw a multicolor image with your robot.
