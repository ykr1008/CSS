# CSS Layout and Styling Exercises

## Overview

This project demonstrates fundamental CSS concepts by building a responsive product listing page using plain HTML and CSS. It focuses on modern layout techniques, responsive design, positioning, and identifying and fixing common CSS bugs.

## Objectives

* Understand the CSS box model and global reset.
* Build page layouts using **CSS Grid** and **Flexbox**.
* Create responsive product grids without relying on media queries.
* Apply mobile-first responsive breakpoints.
* Use `rem` units for scalable and accessible sizing.
* Implement sticky headers and fixed modal overlays.
* Explore different CSS centering techniques.
* Identify and fix stacking context, specificity, and margin collapse issues.

## Technologies Used

* HTML5
* CSS3
* CSS Grid
* Flexbox
* Responsive design
* CSS positioning and stacking contexts

## Features and Exercises

### 1. Global Reset and Box Model

Implemented a global `box-sizing: border-box` reset to make element sizing more predictable.

### 2. Page Layout

Used CSS Grid to structure the main page layout and Flexbox for navigation, card content, and form rows.

### 3. Responsive Product Grid

Created a responsive product grid using `repeat(auto-fit, minmax())` to automatically adjust the number of columns according to available space.

### 4. Mobile-First Design

Applied minimum-width breakpoints to progressively enhance the layout for larger screens.

### 5. Scalable Units

Used `rem` units and tested how changing the root font size affects the layout.

### 6. Sticky Header and Modal

Implemented a sticky header and a fixed modal overlay, using `z-index` to control their stacking order.

### 7. Centering Techniques

Demonstrated four methods of centering elements:

* Flexbox
* CSS Grid
* Absolute positioning with `transform`
* Auto margins

### 8. CSS Debugging Exercises

Reproduced, investigated, and fixed three common CSS issues:

* **Stacking context:** Resolved an element appearing behind another element by adjusting the parent stacking order.
* **Specificity conflict:** Fixed conflicting ID and class selectors.
* **Margin collapse:** Used Flexbox with `gap` to prevent adjacent vertical margins from collapsing.

Screenshots and explanations of these exercises are included in the project folders.

## Project Structure

```text
CSS/
├── index.html
├── style.css
├── Results/
│   └── Screenshots of debugging exercises
├── Written answers/
│   └── Written answers to CSS theory questions
└── bug explanations and fixes/
    └── Explanations of CSS bugs and their solutions
```

## How to Run

1. Clone or download this repository.
2. Open the project folder in Visual Studio Code.
3. Open `index.html` in a browser, or use the Live Server extension.
4. Resize the browser window to test the responsive layout.
5. Review the screenshots and explanations to understand the debugging exercises.

## Key Learnings

This project strengthened my understanding of CSS layout systems, responsive design, scalable units, positioning, specificity, and debugging. It also helped me understand how different CSS properties interact when building accessible and maintainable web layouts.

## Author

Created as part of a frontend development learning assignment.
