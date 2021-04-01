# Interactive wave pattern 🍃

Experimenting with CSS animation to create an interactive wave pattern. 

### Links 🔗

+ [Live demo](https://css-conic-gradient-wave-pattern.rolandjlevy.repl.co/)
+ [Source code](https://replit.com/@RolandJLevy/css-conic-gradient-wave-pattern)
+ [Github repo](https://github.com/rolandjlevy/css-conic-gradient-spinner-pattern-wave)

![Spinners](https://raw.githubusercontent.com/rolandjlevy/css-conic-gradient-spinner-pattern-wave/master/images/spinner-wave-pattern.png)

### How it works ⚙️
- The grid is made up of spinning circles or spinners
- Each spinner uses a conic-gradient background to make a 4-quartered circle
- With each 360 degree rotation the opacity transitions from 0 to 1
- The varied animation delay creates the wave effect
- The overall speed and colours are controlled by the sliders

### Conic Gradients
The conic-gradient() CSS function creates an image consisting of a gradient with color transitions rotated around a center point (rather than radiating from the center). [Find out more](https://developer.mozilla.org/en-US/docs/Web/CSS/conic-gradient())

- Here is an example of a conic gradient:
```css
 background: conic-gradient( 
  black 0deg 90deg, 
  green, 90deg 180deg, 
  black 180deg 270deg,
  turquoise, 270deg
);
```