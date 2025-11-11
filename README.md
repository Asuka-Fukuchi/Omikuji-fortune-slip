# Omikuji-fortune-slip

## Overview

This is a simple web app inspired by a tutorial video on YouTube. The app lets users draw a virtual omikuji (a fortune slip) with a fun animation and displays a random result each time. It was built for learning HTML, CSS, and JavaScript and to showcase on GitHub.

## Features
- Draw a fortune (omikuji) by clicking a button.
- Animated drawing and reveal of the result.
- Several possible outcomes (e.g., “Great blessing”, “Middle blessing”, “Small blessing”, “Curse”).
- Responsive design for both desktop and mobile.
- Simple and clean UI for ease of use.

## Technologies
- HTML5
- CSS3 (including animations and transitions)
- JavaScript (ES6+)

## Getting Started
### Prerequisites

You only need a modern web browser (Chrome, Firefox, Edge, Safari) to run the app locally.

### Installation

1. Clone this repository
```bash
git clone https://github.com/your-username/omikuji-app.git
```

2. Navigate into the project folder
```bash
cd omikuji-app
```

3. Open index.html in your browser, or serve the folder via a local development server if you prefer.

## Usage
Click the “Draw Fortune” (or equivalent) button.
Watch the animation as the omikuji draws.
A random fortune will appear.
You can click again to draw a new fortune.

## Customization
To add more fortune results, edit the fortunes array in script.js and add your own messages.
To change the styling, update styles.css for colors, fonts, animations, etc.
To adjust the animation timing or effects, modify the relevant CSS keyframes or JavaScript logic.

## Project Structure
```bash
/omikuji-app
├── /images
├── index.html
├── styles.css
├── script.js
└── README.md
```

## Why I Built This
I wanted to practice front-end web development and create a fun, interactive mini-project.
Following the tutorial helped reinforce my understanding of JavaScript animations, DOM manipulation, and CSS transitions.

## Next Steps / Future Improvements
Add sound effects or background music when drawing the fortune.
Save the user’s results (e.g., localStorage or backend) so they can track their fortunes over time.
Add localization (Japanese/English) so the app can serve both languages.

## Reference
This app was created as a learning project based on the tutorial video:
[How to Create Omikuji App with JavaScript](https://www.youtube.com/watch?v=lEk_NxeP1vw).  
I followed the tutorial to learn DOM manipulation and animation techniques.

Make it into a PWA (Progressive Web App) so users can install it on mobile.

Improve the design and add more animations or interactive elements.
