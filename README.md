# js-18_Parallax_card-fliping
CSS parallax card hover flipping by using HTML, and CSS For project review purposes

#Preview
![parallax](https://github.com/abdul-1432/js-18_Parallax_card-fliping/assets/124916666/60b39844-e351-4415-8c6c-de14bd925bb5)


# CSS Parallax Card Flipping

This repository provides a CSS-based parallax card flipping effect for creating interactive and visually appealing card transitions on your website. The parallax effect adds depth and dimension to the card flip animation, providing an engaging user experience.

## Demo

You can see a live demo of the CSS parallax card flipping effect [Demo](https://codepen.io/abdul-1432/pen/GRwvGgv).

## Features

- Easy integration into your web projects.
- Smooth and immersive card-flipping animation.
- Adjustable parallax effect for depth perception.
- Customizable content and styling.
- Lightweight and optimized for performance.
- Compatible with modern browsers.

## Getting Started

### Installation

To use the CSS parallax card flipping effect in your project, follow these steps:

1. Download the repository as a ZIP file or clone it using the following command:

   ```bash
   https://github.com/abdul-1432/js-18_Parallax_card-fliping
   ```

2. Copy the necessary files (HTML, CSS, and JavaScript) to your project directory.

### Usage

To add the CSS parallax card flipping effect to your website, follow these steps:

1. Include the required CSS and JavaScript files in the `<head>` section of your HTML file:

   ```HTML
   <link rel="stylesheet" href="path/to/css-parallax-card-flipping.css">
   <script src="path/to/css-parallax-card-flipping.js"></script>
   ```

2. Create the HTML structure for the card:

   ```HTML
   <div class="card">
     <div class="card-front">
       <!-- Front content of the card -->
     </div>
     <div class="card-back">
       <!-- Back content of the card -->
     </div>
   </div>
   ```

3. Customize the content and styling of the card as needed.

4. Initialize the CSS parallax card flipping effect by calling the `initCardFlip()` function:

   ```javascript
   <script>
     document.addEventListener('DOMContentLoaded', function () {
       initCardFlip();
     });
   </script>
   ```

   The `initCardFlip()` function will add the necessary event listeners and handle the card-flipping animation on hover.

For more detailed instructions and examples, please take a look at the [documentation](docs/README.md).

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please create an issue or submit a pull request.

## License
Copyright (c) 2023 by Mohammad Abdul Gafoor (https://codepen.io/abdul-1432/pen/GRwvGgv)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT, OR OTHERWISE, ARISING FROM, OUT OF, OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

