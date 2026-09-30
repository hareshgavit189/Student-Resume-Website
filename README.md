# HTML Portfolio Website
## 📌 Project Overview

This project is a personal portfolio website developed using HTML5 only. The complete portfolio is contained in a single index.html file.

The project demonstrates the use of HTML5 semantic elements, tables, forms, multimedia, and hyperlinks without using CSS or JavaScript.

## 📂 Project Structure
portfolio/
└── index.html


All portfolio content, including the homepage, education, skills, projects, achievements, contact form, multimedia, and social links, is included in index.html.

## 🎯 Practical Tasks

The project fulfills the following practical requirements:

Create a homepage using HTML5 semantic elements.

Add Education, Skills, Projects, and Achievements sections.

Create a Contact section using an HTML form.

Include multimedia such as:

Profile photo

Video

Map

Social media links

Use HTML tables for structured information.

Use hyperlinks for navigation and external websites.

Validate the HTML page using the W3C Validator.

## 🛠️ Technologies Used

HTML5

Semantic HTML Elements

HTML Tables

HTML Forms

HTML Multimedia

HTML Hyperlinks

## 🏠 Portfolio Sections

The index.html file contains the following sections:

Header

Contains the portfolio title and personal introduction.

Navigation

Provides links to different sections of the same page:

<a href="#about">About</a>
<a href="#education">Education</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#achievements">Achievements</a>
<a href="#contact">Contact</a>

About

Contains personal information and a profile image.

Education

Education details are displayed using an HTML table.

Skills

Technical and professional skills are displayed using HTML lists.

Projects

Contains details about completed or academic projects.

Achievements

Contains academic, technical, or extracurricular achievements.

Multimedia

The portfolio demonstrates multimedia using HTML elements such as:

<img src="profile.jpg" alt="Profile Photo">

<video controls>
    <source src="intro.mp4" type="video/mp4">
    Your browser does not support the video element.
</video>


An embedded map can also be included using an <iframe>.

Contact

The Contact section contains an HTML form with fields such as:

Name

Email

Phone

Subject

Message

Submit button

Reset button

Example:

<form>
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">

    <label for="email">Email:</label>
    <input type="email" id="email" name="email">

    <label for="message">Message:</label>
    <textarea id="message" name="message"></textarea>

    <button type="submit">Submit</button>
    <button type="reset">Reset</button>
</form>

## 🧱 HTML5 Semantic Elements

The following semantic elements are used:

Element	Purpose
<header>	Website header
<nav>	Navigation links
<main>	Main portfolio content
<section>	Individual portfolio sections
<article>	Project/achievement content
<aside>	Additional information
<footer>	Footer information

## 📊 HTML Table

An HTML table is used for displaying education details.

<table border="1">
    <tr>
        <th>Qualification</th>
        <th>Institution</th>
        <th>Year</th>
    </tr>
    <tr>
        <td>Bachelor's Degree</td>
        <td>ABC University</td>
        <td>2026</td>
    </tr>
</table>

## 🔗 Hyperlinks

The portfolio uses hyperlinks for:

Page-section navigation

GitHub

LinkedIn

Email

Other relevant websites

Example:

<a href="https://github.com/" target="_blank">GitHub</a>
<a href="https://www.linkedin.com/" target="_blank">LinkedIn</a>

## 📚 Concepts Covered
Concept	Implementation
HTML5	Complete website structure
Semantic Elements	Header, nav, main, section, article, aside, footer
Tables	Education information
Forms	Contact form
Media	Image and video
Hyperlinks	Navigation and social media
iframe	Embedded map

## ✅ HTML Validation

The index.html file should be validated using the W3C Markup Validation Service.

Validation ensures that the HTML follows proper HTML5 syntax and helps identify markup errors.

Validation Process

Open the W3C HTML Validator.

Select or upload index.html.

Run the validation.

Fix any reported errors.

Validate the file again.

## 🚀 How to Run

Since the project contains only one HTML file:

Download the project.

Open index.html.

Open it in a web browser.

Navigate through the different sections using the navigation links.

## 📝 Conclusion

This project demonstrates the development of a complete personal portfolio using only HTML5 and a single index.html file. It covers semantic elements, tables, forms, multimedia, hyperlinks, and HTML validation.