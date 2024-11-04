# Smoke Effect Animation

This project showcases a text animation with a "smoke" effect when hovered over. Each letter disperses with a blur, movement, and color change, giving a smoky effect as it fades away.

## Preview
When you hover over the text "please hover over me!!!," each letter will animate individually with a smooth smoke effect, adding a unique visual experience.

## Features
- **Animated Smoke Effect**: The letters disperse with a blur and rotation effect when hovered over, simulating smoke.
- **Dynamic Span Wrapping**: JavaScript dynamically wraps each letter in a `<span>` to apply the effect individually.
- **CSS Keyframes**: Keyframes create the blur, rotation, scaling, and movement, delivering a smooth transition.

## Technologies Used
- **HTML**: Basic structure of the webpage.
- **CSS**: Styling, animations, and keyframes for the smoke effect.
- **JavaScript**: DOM manipulation to wrap each letter in `<span>` elements, enabling the individual animation effect.

## How to Use
1. **Clone the Repository**: Download or clone this repository to your local machine.
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
Code Explanation
HTML: Contains a single h1 element with the text "please hover over me!!!" wrapped in a section.
CSS:
Sets up a background gradient, centers the text, and defines the animation styles.
Defines the @keyframes smoke animation that blurs, rotates, and fades each letter when the .active class is applied.
JavaScript:
Replaces each character in the text with <span> elements to target individual letters.
Adds a mouseover event listener to each <span> that applies the active class and triggers the animation.

Setup
No special setup is required. Simply open the index.html file in any modern web browser.

Demo

License
This project is open-source and available under the MIT License. Feel free to use, modify, and distribute it as needed.

Acknowledgments
Inspired by creative CSS and JavaScript animation techniques to make simple text interactions more engaging.
