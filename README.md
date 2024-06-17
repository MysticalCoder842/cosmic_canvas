// Generate random RGB values
const red = Math.floor(Math.random() * 255);
const green = Math.floor(Math.random() * 255);
const blue = Math.floor(Math.random() * 255);

// Create a random color string
const randColor = `rgb(${red}, ${green}, ${blue})`;

// Now you can use this color to fill your canvas shapes
context.fillStyle = randColor;
// Draw your shape here (e.g., rectangle, circle, etc.)
