# Hyppyear Webpage

This is a simple web page created to celebrate the New Year with a dynamic countdown and fireworks animation. The page displays a countdown to the New Year (January 1st, 2025), along with colorful fireworks that appear as the countdown progresses. When the countdown reaches zero, a popup appears to wish the user a "Happy New Year!"

## Features

- **New Year Countdown**: The page displays a real-time countdown to the New Year, showing the remaining days, hours, minutes, and seconds.
- **Fireworks Animation**: Colorful fireworks are shown on the page. They explode randomly, giving a celebratory feel.
- **Popup Message**: Once the countdown hits zero, a popup appears to wish the user a "Happy New Year!" with a festive message.
- **Responsive Design**: The page is responsive and adapts to different screen sizes.

## Technologies Used

- **HTML**: The structure and content of the webpage.
- **CSS**: Styling of the page, including layout, animations, and positioning.
- **JavaScript**: Logic for the countdown timer, fireworks animation, and popup display.
- **Bootstrap**: Used for basic styling and layout (through a CDN link).

## File Structure

The page consists of a single HTML file with embedded CSS and JavaScript. Below is the structure:


### Description of Sections:

1. **HTML Markup**:
   - The page consists of a countdown section displaying the time until the New Year and a canvas element that displays the fireworks animation.
   - A hidden popup is positioned in the center of the screen and becomes visible when triggered.

2. **CSS**:
   - The page has a dark background to allow the fireworks to stand out.
   - The countdown timer is centered in the page, and the popup has a fixed position that becomes visible once triggered.
   - The `canvas` element is used for drawing the fireworks, and the page's design is flexible for different screen sizes.

3. **JavaScript**:
   - The countdown timer updates every second using the `setInterval` function.
   - A random number of fireworks are created and animated on the canvas.
   - When the countdown reaches zero, the popup is displayed by toggling the visibility of the `.popup` div.

## How to Use

1. **Clone or Download**: 
   - You can clone this repository or download the `index.html` file to your computer.

2. **Open in Browser**:
   - Open the `index.html` file in any modern browser to see the countdown and fireworks animation in action.
   - The page will automatically update the countdown and show fireworks as the New Year approaches.

## License

This project is created by **Gurraoptimus Development** and is free to use for personal purposes. For commercial usage, please contact the developer.

## Acknowledgements

- The fireworks animation was custom-coded using JavaScript and the `<canvas>` element.
- The countdown timer uses basic JavaScript's `Date` object and the `setInterval` function to keep track of the time.
- Thanks to **Bootstrap** for providing simple and responsive styles via a CDN.
