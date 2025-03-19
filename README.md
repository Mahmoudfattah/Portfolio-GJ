This is a personal portfolio website that showcases my skills, projects, education, and services. The website is built using modern web technologies and features a contact form powered by Email.js to send messages directly to my email.

Features
Responsive and modern UI/UX design.
Animated elements using AOS (Animate On Scroll) library.
A contact form that sends messages via Email.js.
Integration with social media links.
Display of skills, education, and completed projects.
Technologies Used
Front-End:
HTML5
CSS3
JavaScript (ES6+)
Bootstrap
AOS (Animate On Scroll)
Email.js (for handling contact form submissions)
Installation and Setup
To run this project locally, follow these steps:

Clone the repository

bash
نسخ
تحرير
git clone https://github.com/Mahmoudfattah/portfolio.git
cd portfolio
Open the project
If it's a static site, simply open index.html in a browser.

Configure Email.js

Create an account on Email.js.
Get your Service ID, Template ID, and User ID.
Add the configuration in your JavaScript file (index.js or similar):
js
نسخ
تحرير
emailjs.send("service_xxxxx", "template_xxxxx", {
  name: userName,
  email: userEmail,
  message: userMessage,
}, "your_user_id");
Contact Form Functionality
The contact form allows users to send messages directly to my email using Email.js, eliminating the need for a backend.

Live Demo
You can check the live demo here.

Author
Mahmoud Fattah

GitHub: Mahmoudfattah
LinkedIn: Profile
License
This project is licensed under the MIT License.

