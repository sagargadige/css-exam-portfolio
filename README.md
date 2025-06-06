# css-exam-portfolio
📄 Portfolio Website Documentation
📌 Project Title:
Personal Portfolio Website

👤 Developed By:
Sagar

📚 Table of Contents:
Project Overview

Technologies Used

Folder Structure

Website Structure

Header

Hero Section

Services Section

Portfolio Section

Blog Section

Footer

Bootstrap Icons

How to Run

Future Enhancements

Screenshots (Optional)

📖 Project Overview:
This project is a personal portfolio website designed to showcase your services, work samples, and blog content. It also includes contact information in the footer. The website is built using HTML5, CSS3, and Bootstrap Icons, making it responsive and visually appealing.

🛠️ Technologies Used:
Technology	Description
HTML5	Structure and content
CSS3	Styling and layout
Bootstrap Icons	Icons used across sections
Responsive Grid	Layout management using Bootstrap grid system

📁 Folder Structure:
pgsql
Copy
Edit
Portfolio/
│
├── index.html
├── css/
│   └── style.css
├── images/
│   ├── bird.jpg
│   └── tree.jpeg
🧱 Website Structure:
1. Header
Contains navigation links to each main section.

Uses <nav> inside a Bootstrap row and container.

2. Hero Section
Welcome message with a subtitle.

Center-aligned using Flexbox (d-flex align-items-center justify-content-center).

3. Services Section
Includes 6 service blocks, organized in two rows.

Each block contains an icon, title, and description.

Uses Bootstrap grid (col-4) and custom classes.

4. Portfolio Section
Displays 6 portfolio images (currently all the same).

Each image is wrapped in a col-6 to ensure a two-column layout.

5. Blog Section
Shows 3 blog cards with image, category, title, description, and a "Read more" link.

Organized in three col-4 columns.

6. Footer
Split into 3 equal columns (col-4) displaying:

Phone numbers

Address

Email

Includes icons for each item.

🔤 Bootstrap Icons:
The project includes icons from Bootstrap Icons CDN:

html
Copy
Edit
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.13.1/font/bootstrap-icons.min.css">
Used icons include:

bi-gear-fill

bi-brilliance

bi-front

bi-rocket-takeoff-fill

bi-plug-fill

bi-lightbulb

bi-phone

bi-geo-alt-fill

bi-envelope-at-fill

🖥️ How to Run:
Download or clone the repository.

Open the index.html file in any web browser.

Ensure the following files/folders exist:

css/style.css

images/bird.jpg

images/tree.jpeg

The website will load with all sections properly styled and responsive.

🚀 Future Enhancements:
Add animations using JavaScript or libraries like AOS.

Add a contact form with functionality (HTML + PHP or JS backend).

Improve accessibility (ARIA labels, keyboard navigation).

Add filtering in the portfolio section.

Make blog section dynamic with real blog data.