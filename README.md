# TourismVR – Virtual Reality Experience using React 360

TourismVR is an interactive virtual reality application built with React 360. It presents a simple tourism experience featuring a welcome panel for Gdańsk, Poland, along with expandable VR information panels that respond to user interactions. The project demonstrates hover-based interactions, dynamic surface resizing, and modular VR UI design.

---

## Overview

The application begins with a welcome screen containing an introductory image and a VR button. After initiation, users can interact with multiple Info Panels placed in the VR environment. These panels expand on hover to reveal larger images and descriptive text, and return to their compact size when the pointer exits. The project showcases a straightforward approach to building interactive components within a React 360 VR scene.

---

## Features

- Hover-activated information panels.
- Dynamic VR surface resizing based on user interactions.
- Modular React components for clean organization.
- Image-driven interface for tourism content.
- Lightweight VR UI rendering using React 360 surfaces.

---

## Project Structure

.
├── index.js
├── InfoPanel.js
├── TourismVR.js
├── static_assets/
│   ├── info.png
│   ├── poland.png
│   ├── 1.jpg
│   ├── 2.jpg
│   └── 3.jpg
└── client.js

---

## Getting Started

### 1. Install Dependencies

Ensure that Node.js is installed. Then install the project dependencies:

```bash
npm install

Run the Development Server

Start the React 360 development server:

npm start

```
This launches the local packager and opens the VR environment in the browser.

---

## Core Components
### TourismVR

- Renders the primary welcome panel.

- Displays the introductory image and VR button.

- Triggers VR scene initialization through surfaceModule.start().

### InfoPanel

- Handles hover detection inside the VR environment.

- Expands surface dimensions on interaction.

- Loads larger images and displays corresponding content.

- Resets to the default icon when the pointer exits.

### Interaction Flow

- The user enters the VR environment.

- The welcome image and button are displayed.

- Clicking the button initializes additional VR panels.

- Hovering over an Info Panel enlarges it and loads the detailed image.

- Moving the pointer away restores the panel to its compact form.
  
---

## Technology Used

- React 360

- React (JavaScript)

- VR Surfaces and panel rendering

- Static image assets for content display
  
---

## License

This project is open for modification and personal use.


---
---

## Authors
**Manoj Dattatreya Myneni** – University of Illinois Chicago  

---

## License
This project is licensed under the **MIT License**.  






