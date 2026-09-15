# mumbai-after-dark
mumbai-after-dark
Mumbai After Dark
An interactive parallax scrolling website that explores Mumbai’s transition from sunset to night.

The project was created for an Interactive Parallax Scrolling Page assignment. It uses layered animations, city illustrations, scroll-based movement, and storytelling to create a sense of depth while navigating through the page.

Live Demo
Add your GitHub Pages link here:

text
[https://github.com/pralhad-saw/mumbai-after-dark/](url)
About the Project
Mumbai is a city that never stops moving. This website represents the city’s changing rhythm throughout the evening:

The sky changes from sunset to night.

Buildings move at different speeds.

Cars and roads create foreground movement.

City lights represent the people and stories behind every window.

Each section describes a different part of Mumbai after dark.

The main goal was to create a website that is not only visually attractive but also has a meaningful story behind its parallax effect.

Features
Multi-layer parallax scrolling.

Responsive design for desktop, tablet, and mobile.

Animated sunset and clouds.

Multiple city skyline layers.

Foreground cars and road animation.

Scroll progress indicator.

Story-based content sections.

Interactive “Return to the start” button.

Reduced-motion support for accessibility.

No external JavaScript libraries required.

Technologies Used
HTML5

CSS3

JavaScript

CSS gradients

CSS transforms

Responsive media queries

Google Fonts

How Parallax Works
Different visual layers move at different speeds while the user scrolls:

Layer	Movement
Sun and clouds	Slowest
Distant buildings	Slow
Middle buildings	Medium
Foreground buildings	Faster
Road and cars	Fastest
This difference in movement creates the illusion of depth.

The JavaScript updates the position of each layer based on its assigned speed:

javascript
const movement = scrollY * (1 - speed);
layer.style.transform = `translate3d(0, ${movement}px, 0)`;
A speed below 1 makes an element move more slowly than the page, while a speed above 1 makes it appear closer to the viewer.

Project Structure
text
mumbai-after-dark/
│
└── index.html
The project is currently contained in a single HTML file so it can be easily opened, tested, and hosted.

Running Locally
Clone the repository:

bash
git clone [(https://github.com/pralhad-saw/mumbai-after-dark/edit/main/README.md)](https://github.com/pralhad-saw/mumbai-after-dark/edit/main/README.md)
Open the project folder:

bash
cd YOUR-REPOSITORY-NAME
Open index.html in a web browser.

No installation or build process is required.

Hosting with GitHub Pages
Open the repository on GitHub.

Go to Settings.

Select Pages from the sidebar.

Under Build and deployment, select:

Source: Deploy from a branch

Branch: main

Folder: /root

Click Save.

Wait for GitHub to generate the website link.

Your website will be available at:

text[
https://pralhad-saw.github.io/mumbai-after-dark/](url)
Accessibility
The website includes support for users who prefer reduced motion. When reduced motion is enabled on the device, the parallax movement is disabled while the content remains fully accessible.

Credits
Concept and design: Student project

Location theme: Mumbai, Maharashtra

Fonts: Space Grotesk and DM Mono from Google Fonts

Built using HTML, CSS, and JavaScript

Assignment Objective
The objective of this project was to build a webpage that uses parallax scrolling to create an engaging and visually interesting experience through:

Multiple visual layers.

Different movement speeds.

Smooth scrolling.

Clean layout.

Meaningful storytelling.

Responsive design.

Author
Created by Pralhad Saw

GitHub: [https://github.com/pralhad-saw/](url)

Location: Mumbai, Maharashtra, India

Project: Interactive Parallax Scrolling Page

