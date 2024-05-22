# Digital Clock Web

This project is a simple digital clock created using HTML, CSS, and JavaScript. It displays the current time in hours, minutes, and seconds, updating every second.

## Project Structure

- `index.html`: The HTML file that defines the structure of the digital clock.
- `style.css`: The CSS file that styles the digital clock.
- `script.js`: The JavaScript file that updates the clock every second.

## Code Explanation

### HTML

The HTML file sets up the structure of the digital clock. It includes:
- A `div` with the class `hero` to act as the main container.
- Inside `hero`, a `div` with the class `container` centers the clock on the page.
- The `clock` `div` contains three `span` elements with IDs `hrs`, `min`, and `sec` to display hours, minutes, and seconds, respectively.
- A link to the `style.css` file for styling.
- A script tag to include the `script.js` file for functionality.

### CSS

The CSS file styles the digital clock with a modern look:
- It uses the Poppins font from Google Fonts.
- The `hero` class sets a gradient background and centers its content.
- The `container` class centers the clock on the page and includes decorative before and after pseudo-elements.
- The `clock` class styles the clock with a semi-transparent background and a blur effect.
- Each `span` inside the clock is styled to have a large font size for the time display, with smaller labels below each part of the time (hours, minutes, seconds).

### JavaScript

The JavaScript file handles the clock functionality:
- It selects the `span` elements by their IDs (`hrs`, `min`, `sec`).
- It uses `setInterval` to update the time every second.
- The current time is fetched using the `Date` object.
- Hours, minutes, and seconds are updated with leading zeros if necessary to always display two digits.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/digital-clock-web.git
