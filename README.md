# Etch-a-Sketch
# Etch-a-Sketch

This is a simple Etch-a-Sketch project built with HTML, CSS (using Flexbox), and JavaScript. The project allows users to draw on a grid by hovering over the individual cells. The grid can be resized dynamically by clicking a button and entering a new grid size. 

## Features

- **16x16 Grid**: The initial grid consists of 16x16 square cells.
- **Hover Drawing**: As you hover over the cells, they change color, leaving a trail like a pen drawing.
- **Resizable Grid**: You can resize the grid by clicking the button and entering a new number of cells per side (up to 100).
- **Flexbox Layout**: The grid is created using Flexbox to ensure proper alignment of the cells.

## How to Use

1. **Initial Grid**: When you open the page, a 16x16 grid will be displayed.
2. **Drawing**: Move your mouse over the grid cells to change their color and draw on the grid.
3. **Resize Grid**:
   - Click the **Resize Grid** button.
   - Enter a new number of squares per side (up to 100).
   - The grid will resize and adjust to fit the new dimensions, while keeping the total width and height the same (960px x 960px).
4. **Interaction**: The color of the grid cells will change to black as you hover over them, simulating a "pen" effect.

## Installation

To run the Etch-a-Sketch project locally:

1. Clone the repository or download the project files.
2. Open `index.html` in your browser.

No server setup is required as this is a front-end only project.

## Files Structure

- `index.html`: The main HTML structure of the project.
- `styles.css`: The CSS stylesheet to style the page and grid.
- `script.js`: JavaScript that creates the grid, handles the hover effect, and resizes the grid.

## Technologies Used

- **HTML5**: Structure of the page and grid layout.
- **CSS3**: Styling, including Flexbox for the grid layout.
- **JavaScript**: Dynamic grid creation, hover functionality, and grid resizing.

