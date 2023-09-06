# Background Properties

## Hosted link : https://saifulislam05.github.io/bg-properties/
## Project Description
This project showcases various CSS background properties, including gradient backgrounds, background images, and background size adjustments. The project is divided into different sections, each demonstrating different background-related CSS properties.

## HTML Structure

### Nav Section (`.nav`)
![image](https://github.com/saifulislam05/bg-properties/assets/73392705/ff35bf07-6cad-4d99-9a48-6f1afd9a8efd)
- Contains navigation items with a gradient background.
- Navigation items are displayed horizontally with a margin between them.
- The active navigation item has a different background color.

### Hero Section (`.hero`)
![image](https://github.com/saifulislam05/bg-properties/assets/73392705/06ff373a-d8d6-4439-87fb-c53b1e5eaf2b)
- Displays a full-width hero section with a background image.
- The background image covers the entire section.

### Service Section (`.service`)
![image](https://github.com/saifulislam05/bg-properties/assets/73392705/51c6f201-ed08-4cdc-a0ce-a3aae225e4a3)
- Demonstrates the use of background images within a container.
- Each image is displayed with a specific width, height, and margin.

### About Section (`.about`)
![image](https://github.com/saifulislam05/bg-properties/assets/73392705/cd777a88-6684-47e6-8553-71cba1b35383)
- Utilizes a black background with padding.
- Contains textual content and an image displayed side by side.

## CSS Styles and Properties

### Global Styles (`*`)
- Resets margin, padding, and box-sizing for all elements to create a consistent layout.

### Nav Section (`.nav`)
- `.nav`:
  - `width: 100%;`: Makes the navigation span the entire width.
  - `padding: 2%;`: Adds 2% padding to the navigation.
  - `background`: Creates a gradient background for the navigation using the `linear-gradient` function.

- `.nav .nav_item`:
  - `display: inline-block;`: Displays navigation items as inline blocks.
  - `margin-inline: 5%;`: Sets margins between navigation items.
  - `color: #ffffff;`: Sets the text color to white.

- `.nav_active`:
  - Defines styles for the active navigation item, including a different background color and text color.

### Hero Section (`.hero`)
- `.hero`:
  - `width: 100%;`: Makes the hero section span the entire width.
  - `height: 500px;`: Sets the height of the hero section to 500 pixels.
  - `background`: Sets the background image using a URL.
  - `background-repeat: no-repeat;`: Prevents background image repetition.
  - `background-size: cover;`: Scales the background image to cover the entire section.

### Service Section (`.service`)
- `.service`:
  - `width: 100%;`: Makes the service section span the entire width.
  - `height: 500px;`: Sets the height of the service section to 500 pixels.

- `.service img`:
  - `width: 29%;`: Sets the width of each image to 29% of the container.
  - `height: 90%;`: Sets the height of each image to 90% of the container.
  - `margin: 2%;`: Adds a 2% margin around each image.

### About Section (`.about`)
- `.about`:
  - `width: 100%;`: Makes the about section span the entire width.
  - `height: 500px;`: Sets the height of the about section to 500 pixels.
  - `background: #000000;`: Sets the background color to black.
  - `padding: 2%;`: Adds 2% padding to the about section.

- `.about .about_content`:
  - `width: 45%;`: Sets the width of the content section to 45%.
  - `display: inline-block;`: Displays content as inline blocks.
  - `color: #ffffff;`: Sets the text color to white.

- `.about .about_image`:
  - `width: 45%;`: Sets the width of the image section to 45%.
  - `margin: 1%;`: Adds a 1% margin around the image.
  - `display: inline-block;`: Displays the image as an inline block.

