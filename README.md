# Student Resume Website

**Mapped CO:** CO1, CO2

**Objective:** Develop a professional personal resume website using only HTML5.

---

## Table of Contents

* [Project Overview](#project-overview)
* [Architecture Overview](#architecture-overview)
* [Tech Stack](#tech-stack)
* [Project Structure](#project-structure)
* [Prerequisites](#prerequisites)
* [Quick Start](#quick-start)
* [HTML5 Semantic Structure](#html5-semantic-structure)
* [Resume Sections](#resume-sections)
* [Education Table](#education-table)
* [Skills Section](#skills-section)
* [Projects Section](#projects-section)
* [Achievements Section](#achievements-section)
* [Multimedia](#multimedia)
* [Contact Form](#contact-form)
* [Hyperlinks & Social Media](#hyperlinks--social-media)
* [HTML Concepts Covered](#html-concepts-covered)
* [W3C HTML Validation](#w3c-html-validation)
* [Project Workflow](#project-workflow)
* [Key Features](#key-features)
* [Learning Outcomes](#learning-outcomes)
* [Practical Checklist](#practical-checklist)
* [Conclusion](#conclusion)

---

## Project Overview

The **Student Resume Website** is a personal portfolio and resume website developed using **HTML5 only**.

The complete website is contained in a single `index.html` file. It demonstrates the use of HTML5 semantic elements, tables, forms, multimedia, hyperlinks, and navigation.

The website provides sections for:

* About
* Education
* Skills
* Projects
* Achievements
* Multimedia
* Contact

> The project focuses on building a structured and professional resume website using HTML5 without CSS or JavaScript.

---

## Architecture Overview

The website follows a simple **single-page HTML architecture**.

```text
                    Student Resume Website
                             |
                         index.html
                             |
        ┌────────────────────┼────────────────────┐
        |                    |                    |
      Header              Main Content          Footer
        |                    |
    Navigation       ┌──────┼─────────┐
                     |      |         |
                   About  Education  Skills
                     |
              ┌──────┼──────────────┐
              |                     |
           Projects             Achievements
              |
        ┌─────┼──────┐
        |            |
    Multimedia     Contact
```

Navigation links are used to move between different sections of the same HTML page.

---

## Tech Stack

| Technology          | Purpose                     |
| ------------------- | --------------------------- |
| **HTML5**           | Website structure           |
| **Semantic HTML**   | Meaningful page structure   |
| **HTML Tables**     | Education information       |
| **HTML Forms**      | Contact form                |
| **HTML Media**      | Profile image and video     |
| **HTML Hyperlinks** | Navigation and social links |
| **iframe**          | Embedded map                |

> No CSS or JavaScript is required for the practical implementation.

---

## Project Structure

```text
Student-Resume-Website/
│
├── index.html
├── telephone.png
└── README.md
```

The main website content is implemented inside:

```text
index.html
```

The repository contains the HTML resume website and its supporting image asset.

---

## Prerequisites

No special software or framework is required.

You need:

* A modern web browser
* A text editor such as **VS Code**
* Basic knowledge of HTML5

Optional:

* Internet connection for external links and embedded online content
* W3C Validator for HTML validation

---

## Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/hareshgavit189/Student-Resume-Website.git
```

### 2. Open the Project

```bash
cd Student-Resume-Website
```

### 3. Open the Website

Open:

```text
index.html
```

in any modern web browser.

### 4. Navigate Through the Website

Use the navigation links to access:

```text
About
Education
Skills
Projects
Achievements
Contact
```

---

## HTML5 Semantic Structure

The website uses HTML5 semantic elements to organize the page.

| Element     | Purpose                         |
| ----------- | ------------------------------- |
| `<header>`  | Website header and introduction |
| `<nav>`     | Navigation links                |
| `<main>`    | Main website content            |
| `<section>` | Individual resume sections      |
| `<article>` | Independent content             |
| `<aside>`   | Additional information          |
| `<footer>`  | Footer information              |

Example:

```html
<header>
    <h1>Student Resume</h1>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#education">Education</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
</nav>

<main>
    <section id="about">
        <h2>About Me</h2>
    </section>
</main>

<footer>
    <p>Student Resume Website</p>
</footer>
```

---

## Resume Sections

The `index.html` file contains multiple sections for presenting student information.

### About

The About section provides:

* Student introduction
* Personal information
* Profile image

### Education

The Education section displays academic information using an HTML table.

### Skills

The Skills section lists technical and professional skills.

### Projects

The Projects section contains information about academic or personal projects.

### Achievements

The Achievements section presents academic, technical, or extracurricular achievements.

### Contact

The Contact section provides an HTML form through which visitors can enter their information.

---

## Education Table

HTML tables are used to organize educational information.

Example:

```html
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
```

The table provides structured information using:

* `<table>`
* `<tr>`
* `<th>`
* `<td>`

---

## Skills Section

The Skills section uses HTML lists to display skills.

Example:

```html
<ul>
    <li>HTML5</li>
    <li>CSS</li>
    <li>JavaScript</li>
    <li>Node.js</li>
</ul>
```

Lists make the skills easy to organize and read.

---

## Projects Section

The Projects section presents details about completed or academic projects.

Example:

```html
<section id="projects">
    <h2>Projects</h2>

    <article>
        <h3>Student Management System</h3>
        <p>
            A project developed to manage student information.
        </p>
    </article>
</section>
```

The `<article>` element can be used to represent an individual project.

---

## Achievements Section

The Achievements section displays important academic, technical, or extracurricular achievements.

Example:

```html
<section id="achievements">
    <h2>Achievements</h2>

    <ul>
        <li>Completed academic projects</li>
        <li>Participated in technical events</li>
        <li>Completed online certifications</li>
    </ul>
</section>
```

---

## Multimedia

The website demonstrates HTML multimedia elements.

### Profile Image

```html
<img src="profile.jpg"
     alt="Student Profile Photo"
     width="200">
```

### Video

HTML5 provides the `<video>` element for displaying video content.

```html
<video controls width="400">
    <source src="profile-video.mp4" type="video/mp4">
</video>
```

### Embedded Map

An online map can be embedded using an `<iframe>`.

```html
<iframe
    src="MAP_URL"
    width="600"
    height="450">
</iframe>
```

The project documentation specifically demonstrates multimedia including a profile photo, video, map, and social links.

---

## Contact Form

The Contact section uses HTML forms to collect visitor information.

Example:

```html
<form>

    <label for="name">Name:</label>
    <input type="text" id="name" name="name">

    <br><br>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email">

    <br><br>

    <label for="phone">Phone:</label>
    <input type="tel" id="phone" name="phone">

    <br><br>

    <label for="subject">Subject:</label>
    <input type="text" id="subject" name="subject">

    <br><br>

    <label for="message">Message:</label>
    <textarea id="message" name="message"></textarea>

    <br><br>

    <button type="submit">Submit</button>
    <button type="reset">Reset</button>

</form>
```

### Form Elements Used

| Element      | Purpose                 |
| ------------ | ----------------------- |
| `<form>`     | Creates the form        |
| `<label>`    | Defines field labels    |
| `<input>`    | Accepts user input      |
| `<textarea>` | Accepts longer messages |
| `<button>`   | Submit/reset actions    |

---

## Hyperlinks & Social Media

Hyperlinks are used for:

* Internal page navigation
* GitHub
* LinkedIn
* Email
* Other websites

Example:

```html
<a href="#education">Education</a>

<a href="#projects">Projects</a>

<a href="https://github.com/">
    GitHub
</a>

<a href="https://www.linkedin.com/">
    LinkedIn
</a>

<a href="mailto:example@gmail.com">
    Email
</a>
```

The navigation links connect the different sections of the single-page resume.

---

## HTML Concepts Covered

| Concept               | Implementation                                     |
| --------------------- | -------------------------------------------------- |
| **HTML5**             | Complete website structure                         |
| **Semantic Elements** | Header, nav, main, section, article, aside, footer |
| **Tables**            | Education information                              |
| **Forms**             | Contact form                                       |
| **Media**             | Image and video                                    |
| **Hyperlinks**        | Navigation and social media                        |
| **iframe**            | Embedded map                                       |

---

## W3C HTML Validation

The HTML page should be validated using the **W3C Markup Validation Service**.

### Validation Process

1. Open the W3C HTML Validator.
2. Select or upload `index.html`.
3. Run the validation.
4. Check the reported errors and warnings.
5. Correct any HTML errors.
6. Validate the page again.

> HTML validation helps ensure that the page follows proper HTML5 syntax and structure.

---

## Project Workflow

```text
Create HTML File
       |
       v
Create HTML5 Structure
       |
       v
Add Semantic Elements
       |
       v
Create Resume Sections
       |
       v
Add Education Table
       |
       v
Add Skills & Projects
       |
       v
Add Achievements
       |
       v
Add Multimedia
       |
       v
Create Contact Form
       |
       v
Add Hyperlinks
       |
       v
Validate Using W3C
       |
       v
Complete Resume Website
```

---

## Key Features

* **HTML5-only implementation**
* Semantic HTML5 structure
* Single-page resume website
* About section
* Education section
* Skills section
* Projects section
* Achievements section
* Contact form
* Profile image
* Video support
* Embedded map
* Social media links
* Internal navigation
* HTML table
* W3C HTML validation

These features correspond to the practical requirements documented in the repository.

---

## Learning Outcomes

After completing this practical, the student will be able to:

* [x] Create a webpage using HTML5.
* [x] Use HTML5 semantic elements.
* [x] Create structured resume sections.
* [x] Create and format HTML tables.
* [x] Create HTML forms.
* [x] Add images and videos.
* [x] Embed external content using `<iframe>`.
* [x] Create internal and external hyperlinks.
* [x] Validate HTML using the W3C Validator.

---

## Practical Checklist

* [x] Homepage created using HTML5
* [x] Semantic elements implemented
* [x] Education section added
* [x] Skills section added
* [x] Projects section added
* [x] Achievements section added
* [x] Contact form created
* [x] Profile image included
* [x] Multimedia included
* [x] Map embedded
* [x] Social links included
* [x] HTML table implemented
* [x] Hyperlinks implemented
* [x] W3C validation performed

---

## Conclusion

The **Student Resume Website** demonstrates how to create a professional personal resume using **HTML5**.

The project covers important HTML concepts including **semantic elements, tables, forms, multimedia, hyperlinks, and embedded content**. The complete website is implemented through a single `index.html` file.

> **Result:** A professional Student Resume Website was successfully developed using HTML5 and the required HTML concepts were implemented.
