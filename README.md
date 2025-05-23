# Donut Animation

This project is a JavaScript-based ASCII donut animation rendered in a web browser. The animation replicates the classic spinning donut effect, allowing users to interact with it by rotating the donut horizontally using mouse drag.

## Features

- **Interactive Rotation**: Rotate the donut horizontally by holding the left mouse button and dragging.
- **ASCII Art**: The donut is rendered using ASCII characters for a retro aesthetic.
- **Responsive Design**: The animation adjusts to fit the browser window.

## How It Works

The animation is achieved by calculating the 3D coordinates of points on a torus (donut shape) and projecting them onto a 2D plane. The brightness of each point is represented by different ASCII characters, creating the illusion of depth.

### Key Components

- **JavaScript**: Handles the 3D calculations and rendering.
- **HTML**: Provides the structure for the animation.
- **CSS**: Styles the page for a clean, centered display.

## Usage

1. Open the `index.html` file in any modern web browser.
2. Click and hold the left mouse button on the animation.
3. Drag the mouse horizontally to rotate the donut.

## File Structure

```
project-folder/
│
├── donut.html   # Main HTML file containing the animation
├── README.md    # Project documentation
```

## Customization

- **Canvas Dimensions**: Adjust the `width` and `height` variables in the JavaScript section of `donut.html` to change the size of the animation.
- **Rotation Speed**: Modify the `deltaX` multiplier in the mouse event listener to control the rotation speed.

## Requirements

- A modern web browser with JavaScript enabled.

## Credits

This project is inspired by the classic ASCII donut animation originally written in C. The JavaScript implementation brings the effect to the web, making it interactive and accessible.

## License

This project is open-source and available under the MIT License.