# Drawing Web App

This project demonstrates how to create a drawing web app using HTML, CSS, and JavaScript. The app allows users to draw on a canvas, change the background color, and save their artwork.

## Demo

You can see a live demo of the project [here](https://logusivam.github.io/Drawing-web-app-2/).

## Features

- **Canvas Drawing**: Users can draw freely on the canvas using mouse or touch input.
- **Color Selection**: Choose from a variety of colors for drawing.
- **Brush Size**: Adjust the brush size to draw lines of different thickness.
- **Background Color**: Change the background color of the canvas.
- **Save Artwork**: Save the drawn artwork as an image file.

## Installation

To use this project, simply download or clone the repository:

```bash
git clone https://github.com/logusivam/drawing-web-app-2.git
```

Alternatively, you can directly copy the HTML, CSS, and JavaScript code into your project files.

## Usage
1. Include the CSS and JavaScript files in your HTML file:
```
<link rel="stylesheet" href="style.css" type="text/css" />
<script src="script.js" defer></script>
```
2. Add the following HTML structure:
```
<button class="clear">Clear</button>
        <button class="save">Save</button>
        <input type="color" id="favcolor" value="#FFFFFF">
        <input type="range" name="valInputName" id="valInputId" value="5" min="1" max="100" oninput="valOutputId.value = valInputId.value">
        <output id="valOutputId">5</output>
```
3. Customize the design and layout in the style.css file as needed.

## Contributing
Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.




















