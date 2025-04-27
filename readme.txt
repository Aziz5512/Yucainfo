YUCCAINFO Website - README
Overview
YUCCAINFO is a modern, responsive website for a technology company specializing in web development, mobile applications, POS solutions, ERP integration, and SEO services. This repository contains all the code for the website.

Features
Responsive Design: Works on all devices (desktop, tablet, mobile)

Modern UI: Clean, professional design with animations

Interactive Elements:

Smooth scrolling navigation

Animated service cards

Contact form with validation

Performance Optimized: Fast loading times

SEO Friendly: Proper meta tags and semantic HTML

Technologies Used
HTML5

CSS3 (with Flexbox and Grid)

JavaScript (ES6)

Font Awesome (for icons)

Google Fonts (Poppins)

Installation
No installation required for viewing. Simply open index.html in any modern web browser.

For development:

Clone the repository:

bash
git clone https://github.com/yourusername/yuccainfo-website.git
Open the project folder

Start editing files

File Structure
yuccainfo-website/
├── index.html          # Main HTML file
├── style.css           # All CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
How to Customize
Change Content:

Edit text directly in index.html

Update services in the Services section

Modify contact information in the footer

Change Styling:

Edit colors in the :root variables in style.css

Adjust spacing and layouts in the CSS

Modify animations in the @keyframes sections

Add Pages:

Create new HTML files

Link them in the navigation

Add corresponding CSS styles

Form Submission
The contact form currently shows a success message when submitted. To make it actually send data:

Replace the form submission handler in script.js with actual AJAX code

Point it to your backend endpoint

Example using Fetch API:

javascript
fetch('your-backend-url', {
  method: 'POST',
  headers: {
    'Content-Type': 'application/json',
  },
  body: JSON.stringify(formData)
})
.then(response => response.json())
.then(data => {
  showToast('Message sent successfully!', 'success');
})
.catch(error => {
  showToast('Error sending message', 'error');
});
Browser Support
The website supports all modern browsers including:

Chrome (latest)

Firefox (latest)

Safari (latest)

Edge (latest)

Deployment
To deploy the website:

Upload all files to your web hosting service

Make sure the file structure is preserved

Test all links and forms

License
This project is open source and available under the MIT License.

Contact
For any questions or support, please contact:

Email: hmayedaziz@gmail.com

Phone: +216 29 887 895

Tunisien wolfes team