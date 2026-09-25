# carousel
A minimalist image slider UI component built entirely with pure HTML and CSS, demonstrating the power of absolute and relative positioning without the use of Flexbox or CSS Grid.
# Pure CSS Positioning Slider UI

A lightweight, dependency-free image slider and carousel user interface created using plain HTML and CSS. This project serves as a practical demonstration of core CSS positioning mechanics (`position: relative` and `position: absolute`), built entirely without modern layout modules like Flexbox or CSS Grid.


## Features
* **Pure HTML & CSS:** No JavaScript, no frameworks, and no external libraries required.
* **Classic Positioning:** Built exclusively using `position: relative` for the parent container and `position: absolute` for the UI controls.
* **Perfect Centering:** Uses `top: 50%`, `left: 50%`, and CSS `transform: translate()` for pixel-perfect vertical and horizontal centering.
* **Overlapping Elements:** Demonstrates how to break elements out of the document flow to overlap container edges (e.g., the left and right navigation arrows).

## Usage
1. Clone the repository to your local machine.
2. Open `index.html` in any modern web browser.
3. Modify the CSS variables or hardcoded values in the `<style>` tag to adjust colors, dimensions, and styling to fit your project.

## Concepts Demonstrated
This project is an excellent reference for understanding how to manipulate elements in the CSS box model:
* Establishing a containing block with `position: relative`.
* Anchoring children to specific edges using `top`, `bottom`, `left`, and `right`.
* Using negative positioning values to pull elements outside their parent container.
