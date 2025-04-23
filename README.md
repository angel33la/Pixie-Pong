# Pixie-Pong
## The Requirements

You are required to create four rectangles in your PixiJS application. Each rectangle (or line) will represent a border in your application. Each line will occupy one side of a box and will be positioned at the very edge of each side of the screen.

Initially, each border will be colored a different color than the blue background. After the circle bounces off one of these borders, the application should remember which borders the circle has collided with.

Now, here’s the challenge: the application should stop only after the circle has bounced off all four borders. You must use a Promise to achieve this. The Promise will be responsible for ending the game once it resolves, which should happen only after all four borders have been hit. Once the circle has bounced off all four borders, the Promise should resolve, and an alert should pop up to notify the user that the application has completed.

### Final demonstration
![My Final demostration video](src="pingpong.mp4")[pingpong.mp4]

### Extra Requirement
10% of your grade for this activity will be based on your effort to go the extra mile by adding one of the following features to your PixiJS application. Note that none of these features were shown in the previous demonstration, and for good reason. You only need to implement one of the following features to earn the extra 10%. If left incomplete, the maximum grade you can achieve is 90%. Please choose one of the following features to fully implement:

* Pixel-Perfect Hit Detection: In the previous demonstration, you may have noticed that the circle slightly exceeds the border by a few pixels when bouncing. This is because the circle’s X,Y coordinates are based on its center. You will need to perform some quick calculations based on the border's width and the size of the circle to determine the exact hit detection spot, ensuring the edge of the circle bounces off the border perfectly without passing through it.
* Border Color Change: Once the circle hits a specific border, the border should change color to indicate that it has already been hit. In the previous example, all four borders are red, but with this feature, when the circle bounces off the right-side border, for instance, it could change to a different color, such as white or yellow.
* Random Circle Movement: Currently, the circle starts in the middle of the screen, with its velocity set to a simple 1px change in direction on each tick. For this feature, you’ll need to randomize the circle’s velocity and direction at the start of the application
