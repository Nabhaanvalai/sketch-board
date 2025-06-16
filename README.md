# Sketch Board

A simple web-based drawing application that allows users to create and save sketches.

## Features

- Draw with different colors and brush sizes
- Change the canvas background color
- Clear the canvas with a single click
- Save your artwork as a PNG file
- Undo changes

## Technology Stack

- HTML5 Canvas for drawing functionality
- TailwindCSS for styling
- Bootstrap for UI components

## Project Structure

```
sketch-board/
├── dist/                  # Distribution files
│   ├── index.html         # Main HTML file with drawing application
│   └── output.css         # Compiled CSS file
├── src/
│   └── input.css          # TailwindCSS input file
├── package.json           # Project dependencies
├── package-lock.json      # Dependency lock file
└── tailwind.config.js     # TailwindCSS configuration
```

## Getting Started

1. Clone this repository
2. Open `dist/index.html` in your browser to use the application

## Usage

- Select a color from the color picker
- Choose a brush size from the dropdown menu
- Draw on the canvas using your mouse
- Use the "Clear" button to reset the canvas
- Use the "Save and Exit" button to download your drawing as a PNG file
- Use the "Undo Changes" button to revert to the previously saved state

## Development

To modify the project:

1. Install dependencies:
   ```
   npm install
   ```

2. Run TailwindCSS build process:
   ```
   npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
   ```

3. Edit the HTML and JavaScript in `dist/index.html` 