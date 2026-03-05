# Lotto Number Generator

## Overview

This project is a simple web application that generates random lottery numbers. The user can click a button to get a new set of 6 unique numbers between 1 and 45.

## Design and Features

*   **UI:** The user interface is clean and simple, with a clear title, a display for the generated numbers, and a button to generate them.
*   **Styling:** Modern CSS is used for styling, including flexbox for layout, custom properties for colors, and a responsive design. The design will be visually appealing with a modern aesthetic.
*   **Interactivity:** The user can generate new lottery numbers by clicking a button.
*   **Components:** A Web Component is used to display each lottery number ball, encapsulating its style and behavior.

## Current Plan

*   **index.html:** Set up the basic HTML structure with a title, a container for the lottery numbers, and a generation button.
*   **style.css:** Apply styles to the body, container, title, number display, and button to create a visually appealing and modern design.
*   **main.js:**
    *   Create a custom element `<lotto-ball>` to display each number.
    *   Implement the logic to generate 6 unique random numbers between 1 and 45.
    *   Add an event listener to the button to trigger the number generation and display the results using the `<lotto-ball>` component.
