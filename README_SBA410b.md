# Accessible Design Co. – SBA410 2.1

# .1 Project Description

For this project, the webpage for Accessible Design Co. was created

The main goal was to build a website that is easy to use, looks good on different screen sizes, and considers people with different accessibility needs.

The website was developed using HTML, CSS, and JavaScript. 
I used semantic HTML elements to organize the content and CSS Flexbox and Grid to arrange the different sections of the page.

# .2 

The website includes,

* Header and Navigation with the company name, logo, and navigation links to the main sections of the website.
* Home Section which introduces the company with a welcome message and a button that takes visitors to the contact section.
* About Us that is a short description of the company and its purpose.
* Services presenting  three services offered by the company using a grid layout.
* Contact Form allowing visitors to enter their name, email, subject, and message. It also includes instructions to help users complete the form.
* The Footer containing copyright information, contact details, and additional links.

I also added accessibility features such as labels for form fields, ARIA attributes, keyboard focus indicators, and different layout adjustments for smaller screens.

# .3 Tools used

The following tools were used to develop and test the project:

* Visual Studio Code (v1.144.0)
* Git Bash
* Live Server (Ritwick Dey)
* HTML
* CSS
* JS

# .4 How to open

To open the project using Visual Studio Code, follow these steps:

1. Open Visual Studio Code
2. Find and open the folder containing the project
3. Open the html file

# Reflection Questions

* 1. What accessibility challenges did you face, and how did you address them?
One difficult problem was making the page easy to use for blind people or those who use a keyboard instead of a mouse. I fixed it by using special ARIA tags like `role="navigation"`, adding alt descriptions to images, and adding `aria-describedby` in forms to explain what each user needs to write. I also created a visible focus with yellow borders so it is clear when navigating with the keyboard.

*2. How did you ensure that your design was responsive and accessible to all users?
To make it work on cell phones, computers, and tablets, I used Flexbox and CSS Grid, along with MEDIA QUERIES so the service cards organize themselves and do not crowd together. Additionally, I checked that the text and background colors had good contrast so they could be read without difficulty.



*3. What tools or resources did you find most helpful during this project?
Thinking on html as a body to identify labels. Also, it helped me a lot to use the browser developer tools to test how the page looks screens, verify the semantic HTML code (header, main, section, footer)

