# Nico Robin Landing Page

## Description

This project is a reproduction of a landing page dedicated to the character **Nico Robin** from the _One Piece_ universe. The page is designed to be responsive and includes interactive sections, modern styles, and a well-organized structure.

## Features

- **Navigation Bar**: Includes a search field, login links, and a burger menu.
- **Main Sections**:
  - Character introduction with detailed statistics.
  - Information about her role in _One Piece_.
  - Gallery and interactive content.
- **Footer**: Contains links to Fandom properties, social networks, and apps.

## Project Structure

```
index.html
README.md
assets/
  img/          # Contains the images used in the project
  pages/        # SCSS files for the different sections
    _aside.scss
    _footer.scss
    _header.scss
    _nav-fixed.scss
    _section-1.scss
    _section-2.scss
    _section-3.scss
  style/
    _settings.scss  # SCSS variables and mixins
    index.css       # Compiled CSS file
    index.scss      # Main SCSS file
```

## Technologies Used

- **HTML5**: Page structure.
- **CSS3/SCSS**: Advanced styles and modular file organization.
- **Font Awesome**: Icons to enhance aesthetics.
- **Responsive Design**: Adaptation for different devices.

## Installation

1. Clone the repository:
   ```bash
   git clone <repo-url>
   ```
2. Open the `index.html` file in your browser.

## Development

To modify SCSS styles:

1. Make sure you have **Node.js** and **Sass** installed.
2. Compile the SCSS files into CSS:
   ```bash
   sass assets/style/index.scss assets/style/index.css
   ```

## Preview

Here is a preview of the landing page:

![Landing Page Preview](assets/img/Capture%20d'écran%202025-11-16%20164259.png)

## Author

- **Djocod** - Creator of the landing page.
