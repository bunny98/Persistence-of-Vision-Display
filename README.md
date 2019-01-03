# Persistence-of-Vision-Display

Persistence Of Vision is the phenomenon of the eye by which an image seen by our eye persists for about 0.04s during which any other images that we see are merged together with this image.

This phenomenon is used in the POV Display as we turn the LEDs on and off in such a way that the different images overlap each other forming letters.

For example:

The formation of the letter E with 5 LEDs;

1 2 3 <- Time

1 1 1 <- Bulb 1

1 0 0 <- Bulb 2

1 1 1 <- Bulb 3

1 0 0 <- Bulb 4

1 1 1 <- Bulb 5

Each column represents the 5 LEDs we used to make the display. Each element in the row represents the state of the LED at that given time.

So at t = 1 Bulb 1,2,3,4,5 are all on

at t=2,3 Bulb 1,3,5 are on

This way we can visually see the letter E formed by the LEDs but the time interval would be very small in milliseconds and not as given in the example.

Due to the short time intervals and the ability of the LEDs to turn on and off very quickly we can see the letter E as all the 3 images merge. As the motor is spinning, as time passes the LEDs move from one position to the next so all these images are merged together.

For more information on how this works have a look at these links:

http://www.vision.org/visionmedia/article.aspx?id=...
http://en.wikipedia.org/wiki/Persistence_of_vision
Note: You can see in the above images how the 3 different pictures merge to form the letter E

