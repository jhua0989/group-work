# Functional-prototype
### Interactive description with work

### Personal animation group code method details
- Animation driven
  I chose time as the driver of the animation.
  1. Circles appear one by one: Circles appear one at a time. 
  2. Overall animation: Once all circles appear, the overall animation effect will be triggered. 
   
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

