# Ahmad Al-Jabbouri | Portfolio

This repository contains my web portfolio, showcasing my skills, achievements, and background as a software engineer. Below is an overview of the project's structure and the concepts of web programming applied in its development.

## Project Structure

The project consists of three HTML files:

1. **index.html**: This is the main page of the portfolio.
2. **courses.html**: This page displays my academic journey in the form of a course list. Users can search for specific courses, filter them by level, and sort them in ascending or descending order.
3. **resume.html**: This page presents my resume. It includes an embedded PDF file viewer showcasing my skills and work experience.

Additionally, the project includes a **style.css** file, containing the custom styling for the HTML pages. External stylesheets, such as the Font Awesome library, are used for icons and other stylings.

## Concepts of Web Programming

1. **HTML Structure**: Each HTML file follows the standard structure, consisting of the `<!DOCTYPE html>` declaration, the `<html>` root element, `<head>` section containing metadata, and the `<body>` section containing the visible content.

2. **CSS Styling**: Custom CSS styles are applied to enhance the visual appearance of the portfolio. Stylesheets are linked using `<link>` tags in the `<head>` section, while inline styles and class selectors are utilized throughout the pages.

3. **Responsive Design**: The use of `<meta>` tags in the `<head>` section ensures the web pages are responsive and adapt well to different screen sizes, making the portfolio accessible across various devices.

4. **Navigation**: The `<header>` element contains a logo and a navigation bar (`<nav>`) that allows users to easily navigate between different sections of the portfolio using anchor links (`<a href="#section-id">`). The "active" class is applied to highlight the current page in the navigation bar.

5. **Semantic Elements**: Semantic HTML elements such as `<header>`, `<main>`, `<section>`, `<footer>`, and `<nav>` are used to provide meaningful structure to the content, making it more accessible and easily interpretable by search engines and screen readers.

6. **Hyperlinks**: Hyperlinks (`<a>`) are utilized to link to external websites (LinkedIn and GitHub profiles).

7. **JavaScript**: The project includes inline JavaScript code to implement dynamic functionality, such as searching and filtering courses on the courses.html page. JavaScript events (e.g., `onkeyup`, `onchange`) are used to trigger these actions.

8. **Image Usage**: Images (`<img>`) are employed to display my logo, profile picture, and course thumbnails. The `alt` attribute is used to provide alternative text for screen readers and for scenarios when the image cannot be displayed.

9. **External Resources**: External resources, like the Font Awesome library (`<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">`), are used to easily incorporate icons into the web pages.

10. **PDF Embedding**: In the resume.html page, the `<object>` element is used to embed my resume PDF file. The user can download the PDF if it cannot be displayed.

11. **Commenting**: Comments in HTML and JavaScript (`<!-- ... -->`) are added to describe the purpose of each section and clarify the code for anyone reading the files.

## Conclusion

My web portfolio showcases my skills not only in software engineering but also in web programming. The project is built with a clear structure, responsive design, and dynamic functionality, making it accessible and user-friendly.
