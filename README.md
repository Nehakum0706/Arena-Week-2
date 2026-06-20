Styled Portfolio Website

<!-- Project Overview -->

This project is a Styled Portfolio Website developed using HTML5 and CSS3 as part of the Developers Arena Internship Week 2 Task.
The objective of this project is to enhance the previously created HTML portfolio by applying CSS styling, improving visual appearance, implementing responsive design, and creating a better user experience.

<!-- Objectives -->

•	Learn CSS fundamentals and styling techniques
•	Create and link an external CSS file
•	Apply typography and colour schemes
•	Use Flexbox for layout design
•	Add hover effects and transitions
•	Implement responsive design using media queries
•	Improve website appearance and usability

<!-- CSS Concepts Learned -->

External Stylesheet
An external CSS file (style.css) was created and linked to the HTML document using the link tag.

<!-- CSS Selectors -->

The following CSS selectors were used:

Element Selector

body {
    font-family: 'Poppins', sans-serif;
}

Class Selector

.skills-list {
    display: flex;
}

ID Selector

#about {
    /* section styling */
}

These selectors help apply styles to different elements efficiently.

<!-- Typography -->

Google Fonts was used to improve the visual appearance of the website.

<!-- Font Used: -->
•	Poppins

Example:
font-family: 'Poppins', sans-serif;

<!-- Color Scheme -->

A consistent color scheme was applied throughout the website.

<!-- Colors Used: -->
•	Navy
•	White
•	Light Gray (#f5f7fa)
•	Blue (#2563eb)
The color palette provides a clean and professional appearance.

<!-- Flexbox Layout -->
Flexbox was used to organize navigation links and skill items.

Example:
nav {
    display: flex;
    justify-content: center;
}

<!-- Benefits: -->
•	Better alignment
•	Responsive layout
•	Easy spacing management

<!-- Hover Effects -->
Hover effects were implemented to improve user interaction.

Example:
nav a:hover {
    color: yellow;
}

button:hover {
    background-color: #2563eb;
}

<!-- Responsive Design -->

Media queries were used to make the website responsive on smaller screens.

Example:

@media(max-width:768px) {
    nav {
        flex-direction: column;
        align-items: center;
    }
}
This ensures the website remains usable on mobile devices.

Design Decisions

<!-- Typography Choice -->

The Poppins font was selected because it provides a modern and professional look.

<!-- Layout Choice -->
Flexbox was chosen because it simplifies alignment and responsiveness.

<!-- Color Selection -->
Navy and white colors were used to create a clean portfolio appearance while maintaining readability.

<!-- Responsive Approach -->

Media queries were implemented to ensure the website adapts to different screen sizes, especially mobile devices.

<!-- Portfolio Structure -->

Header
Contains:
•	Portfolio title
•	Navigation menu

Home Section
Contains:
•	Welcome message
•	Short introduction

About Section
Contains:
•	Profile image
•	Personal introduction
•	Academic background
•	Career goals
•	Social profile links

Skills Section
Contains:
•	Technical skills displayed using Flexbox

Contact Section
Contains:
•	Name field
•	Email field
•	Message field
•	Submit button

Footer
Contains copyright information.
Technologies Used
•	HTML5
•	CSS3
•	Google Fonts

Setup Instructions
1.	Download the project folder.
2.	Open the folder in Visual Studio Code.
3.	Ensure the following files are present:
o	index.html
o	style.css
o	images folder
4.	Open index.html.
5.	Run using a browser or Live Server.
6.	Verify responsiveness by resizing the browser window.

<!-- Code Structure -->

Project Folder Structure:
portfolio-website/
│
├── index.html
├── style.css
├── README.md
│
├── Images/
│   └── profile.png.png
│
└── screenshots/

<!-- File Description -->
•	index.html → Website structure and content
•	style.css → Website styling and responsiveness
•	Images/ → Stores profile image
•	screenshots/ → Stores project screenshots
•	README.md → Project documentation

<!-- Technical Requirements Completed -->

External CSS file created
Multiple CSS selectors used
Google Font integrated
Custom color scheme applied
Flexbox layout implemented
Hover effects added
Responsive design implemented
Form styling completed
Image styling completed
Mobile-friendly layout created

<!-- Visual Documentation -->

•	Homepage
•	About Section
•	Skills Section
•	Contact Section
•	Desktop View
•	Mobile View
Store screenshots inside the screenshots folder.

<!-- Technical Details -->
Architecture
The website follows a single-page portfolio architecture:
Header
↓
Navigation
↓
Main Content
Home
About
Skills
Contact
↓
Footer


<!-- Algorithms and Data Structures -->

This project does not use advanced algorithms or data structures because it is a static front-end website.
The implementation focuses on:
•	HTML structure
•	CSS styling
•	Responsive design
•	User interface improvements

<!-- Conclusion -->

This project enhanced my understanding of CSS styling, layout design, Flexbox, responsive web design, typography, color schemes, and user interface development. Through this project, I learned how to transform a basic HTML portfolio into a visually appealing and responsive website suitable for different screen sizes.

