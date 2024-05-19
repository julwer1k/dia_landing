
# AIR (DIA): Craft a Captivating One-Page Website

This project provides the foundation for building a dynamic one-page website to showcase your company's offerings. With **dia_landing**, you can effortlessly create a streamlined online presence that informs visitors about your services, ignites their interest, and compels them to connect with you.

![](./src/images/example.gif)
## Technologies Used
- **HTML:** The website's core structure is built with organized and semantic HTML.
- **BEM (Block Element Modifier):** CSS classes follow the BEM convention for maintainability and reduced style conflicts, using the Block__Element--Modifier format.
- **SCSS (Sassy CSS):** Enhances maintainability and readability with features like:
  - **Mixins:** Reusable code snippets to keep styles DRY.
  - **Variables:** Consistent values stored for easy modification.
  - **Extends:** Base styles inherited and extended for specific elements.
  - **Nesting:** Nested selectors for managing complex layouts.
  - **CSS Rules:** Comprehensive rules covering layout, typography, colors, and more.
- **Adaptive Layout:** Responsive design with media queries ensures optimal viewing on all devices (desktop, tablet, mobile).
- **Style Reset:** A basic CSS reset normalizes default browser styles for a consistent foundation.
- **JavaScript (Light Usage):** Minimal JavaScript for minor interactive elements or functionalities (e.g., slider).
## Demo

Click the button below to experience the MyBike landing page:

[DEMO](https://julwer1k.github.io/dia_landing/)

[DESIGN](https://www.figma.com/design/7qwsWggv9BAxMi2VPhBuPr/Air-(formerly-Dia))
## Run Locally

This project uses Node.js 14. Switching to it ensures compatibility with project dependencies. Refer to [Node.js download](https://nodejs.org/en/blog/release/v14.21.3) for installation instructions.

Clone the project

```bash
  git clone https://github.com/julwer1k/dia_landing.git
```

Go to the project directory

```bash
  cd dia_landing
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```

Check linter [HTML, JavaScript, CSS]

```bash
  npm run lint
```

