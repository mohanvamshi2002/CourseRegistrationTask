# CourseRegistrationTask

100xlearning Online Course Registration Platform
This repository contains the front-end HTML pages for the 100xlearning online course registration platform, styled with Tailwind CSS to give it a distinct gaming theme. Each page represents a step in the user journey for course registration.

Table of Contents
Overview

Pages

Setup and Usage

Styling

Contact Information

1. Overview
The 100xlearning platform is a fictitious online course registration system designed to provide a seamless and engaging user experience. It features a gaming-inspired aesthetic with dark backgrounds, neon shadows, and interactive buttons.

2. Pages
The platform consists of five interconnected HTML pages:

index.html (Landing Page)

Purpose: Introduces "100xlearning" and invites users to explore courses or register.

Navigation: Links to course.html (Browse Courses) and register.html (Register Now).

course.html (Course Details Page)

Purpose: Displays details about the "Datascience learning" program, including featured courses (Data Science, Machine Learning, Deep Learning, Data Visualization) and skills acquired (Python, SQL, R, Pandas, NumPy, Scikit-learn, Tableau, Jupyter Notebook).

Navigation: Links to register.html (Enroll Now!) and index.html (Back to Home).

register.html (Application/Registration Form Page)

Purpose: Allows users to fill out a registration form, selecting their desired course from a dropdown.

Navigation: Submits to confirmation.html and provides a link back to course.html.

confirmation.html (Thank You Page)

Purpose: Confirms successful registration and thanks the user.

Navigation: Links back to index.html.

about.html (Generic About/Contact Page)

Purpose: Provides information about 100xlearning's mission and contact details.

Contact Info:

Email: mohanvamshi2024@gmail.com

Phone: +91 8790123453

Address: Hyderabad

Navigation: Links back to index.html.

3. Setup and Usage
To view these pages locally:

Save the files: Create five separate .html files in the same directory: index.html, course.html, register.html, confirmation.html, and about.html. Copy the respective HTML content into each file.

Open in Browser: Open index.html in your web browser.

Navigate: Use the provided links and buttons to move between the different pages.

Note: These are static HTML pages. The form submission on register.html uses method="GET" and redirects to confirmation.html. No actual data processing or backend integration is included.

4. Styling
The platform is styled using Tailwind CSS, loaded via a CDN. Custom CSS has been added directly within the <style> tags of each HTML file to implement the gaming theme, including:

Backgrounds: bg-gradient-to-br classes provide distinct dark gradients for each page.

Neon Shadows: Custom utility classes like shadow-neon-blue-lg, shadow-neon-green-lg, etc., apply glowing box-shadows to main content containers and buttons.

Chunky Buttons: Custom chunky-button class with enhanced border, transition, and hover/active states for a tactile, game-like feel.

Font: The 'Inter' font is used for a modern, clean look.

5. Contact Information
For any inquiries, you can reach out via:

Email: mohanvamshi2024@gmail.com

Phone: +91 8790123453

Address: Hyderabad
