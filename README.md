# Functional-prototype
### Interactive description with work

- Personal animation group code method details
  1. drawConcentricCircles(x, y, size) : Draw concentric circles, drawing multiple layers of concentric circles according to the given center coordinates and dimensions, and gradually decreasing the level size.
  2. drawEllipsesAroundCircle(centerX, centerY, circleSize) : Draws ellipses around a circle, the number and position of which depend on the given center coordinates and the size of the circle.
  3. drawZigzagLines(centerX, centerY, circleSize) : Draw zigzaglines, drawing lines in a zigzag shape along the perimeter of a given circle to create a dynamic effect.
  4. DrawFilledSurroundingCircles (centerX, centerY, circleSize) : filling and around the circle inside the small circle, small circle the location and size of the dynamic determined according to the size of the circle.
  5. drawSurroundingCircles(centerX, centerY, angle, numCircles, circleSize) : Draw small external circles around a large circle, with the position and number of small circles depending on the given parameters.
  6. drawExtendingLine(centerX, centerY, circleSize) : Draw an extension line that starts at the center of a given circle and extends a dynamically changing curve.
  7. animate() : A method of controlling the animation effect by updating the position or properties of the circle based on changes in time or other parameters.

- Animation driven
  I chose time as the driver of the animation.
  This animation code is primarily driven by time. The effect of the animation is achieved according to the passage of time and the rendering of each frame. The setInterval() method or frameRate() function sets a certain time interval or frame rate, and then updates the position, properties, or color of the graph at each interval or frame to create a dynamic effect.
   
- Animation of image properties
   1. Appearance of circles: The position, size, and color of the circles gradually change so that they appear on the canvas one after the other.
   2. Overall animation effect: The movement, rotation, and color changes of circles are driven by time to present a dynamic and smooth visual effect.
   
- Inspiration
  1. Appearance of circles: Inspired by the image below, my animation attempts to simulate this free-flowing form, The speed and frequency with which the circular patterns appear one by one also reflects this rhythmic atmosphere.
   ![](assets//截屏2024-05-27%20下午6.22.51.png)
   ![](assets//截屏2024-05-27%20下午6.22.59.png)
   ![](assets//截屏2024-05-27%20下午6.23.59.png)

  2. Overall animation effect: My animations create a vibrant and dynamic atmosphere through colorful colors. The color rhythm changes, creating a visual rhythm that echoes the effect of LED lights flashing on the surface of the CD player. 
  
- Technical specification
  I used the p5.js library to create the animation. The one-by-one occurrence of the circles is implemented by the setTimeout() function, which draws the circles one by one after a specified delay. The original animation effect is achieved through the time control in the draw() function, using the angle variable to control the movement, rotation, and color change of the circle.

- Change description
  1. I changed the arrangement of the circles from diagonal to square.
  2. An array is added to store the position and size of all the circles drawn for subsequent animation processing.
  3. The circle drawing logic is adjusted so that the drawing position can be dynamically calculated according to the window size and the number of circles.
  4. The frame rate and time interval of the animation are optimized for a more fluid and natural dynamic effect.

