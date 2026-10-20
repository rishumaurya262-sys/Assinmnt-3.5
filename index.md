 # Assignment 3.5 — Blog / Portfolio Mini-Project

## 1. Objective

The objective of this assignment is to learn how to create a personal blog or portfolio website using HTML and CSS. This website presents personal information, educational qualifications, technical skills, projects, useful links, and contact details.

## 2. Introduction

A portfolio website is a personal webpage that displays an individual's introduction, skills, education, interests, and projects. It helps students present their knowledge and work in an organized manner.

This project creates a simple personal portfolio website for Rishu Maurya, a B.Tech Mechanical Engineering student at Invertis University, Bareilly, who is interested in programming and web development.

## 3. HTML Code

Create a file named `index.html` and write the following code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rishu Maurya - Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header id="home">
        <h1>Rishu Maurya</h1>
        <p>B.Tech Student | Aspiring Software Developer</p>
    </header>

    <nav aria-label="Main navigation">
        <a href="#home">Home</a>
        <a href="#about">About Me</a>
        <a href="#skills">Skills</a>
        <a href="#education">Education</a>
        <a href="#projects">Projects</a>
        <a href="#links">Useful Links</a>
        <a href="#contact">Contact</a>
    </nav>

    <main>
        <section id="about">
            <h2>About Me</h2>
            <img src="index.jpg" alt="Rishu Maurya's profile photograph" width="180">

            <p>
                Hello! My name is Rishu Maurya. I am pursuing
                B.Tech in Mechanical Engineering at Invertis
                University, Bareilly.
            </p>

            <p>
                I am interested in web development, programming,
                and technology. My goal is to improve my technical
                skills, gain practical experience, and build a
                successful career in the technology industry.
            </p>
        </section>

        <hr>

        <section id="skills">
            <h2>My Skills and Interests</h2>
            <ul>
                <li>HTML - Creating webpage structures</li>
                <li>CSS - Styling webpages</li>
                <li>JavaScript - Learning webpage interactivity</li>
                <li>Java - Learning programming concepts</li>
                <li>Problem Solving</li>
                <li>Learning New Technologies</li>
            </ul>
        </section>

        <hr>

        <section id="education">
            <h2>My Education</h2>
            <ol>
                <li>
                    <strong>B.Tech - Mechanical Engineering</strong>
                    <p>Invertis University, Bareilly</p>
                    <p>Currently pursuing, 1st Year</p>
                </li>
                <li>
                    <strong>Class XII</strong>
                    <p>S R M Inter College, Bisalpur, Pilibhit</p>
                    <p>Year: 2026 | Percentage: 61.8%</p>
                </li>
                <li>
                    <strong>Class X</strong>
                    <p>S R M Inter College, Bisalpur, Pilibhit</p>
                    <p>Year: 2024 | Percentage: 86%</p>
                </li>
            </ol>
        </section>

        <hr>

        <section id="projects">
            <h2>My Projects and Learning Activities</h2>

            <article>
                <h3>1. Personal Portfolio Website</h3>
                <p>
                    This project presents my introduction, education,
                    skills, and contact information using HTML and CSS.
                </p>
            </article>

            <article>
                <h3>2. College Information Webpage</h3>
                <p>
                    This practice webpage demonstrates ordered lists,
                    unordered lists, nested lists, and description lists.
                </p>
            </article>

            <article>
                <h3>3. Programming Practice</h3>
                <p>
                    I am learning Java and JavaScript and practising
                    programming concepts to improve my problem-solving skills.
                </p>
            </article>
        </section>

        <hr>

        <section id="links">
            <h2>Useful Links</h2>
            <ul>
                <li>
                    <a href="https://github.com/rishumaurya262-sys"
                       target="_blank" rel="noopener noreferrer">
                        My GitHub Profile
                    </a>
                </li>
                <li>
                    <a href="https://leetcode.com/u/Rishumaurya4321/"
                       target="_blank" rel="noopener noreferrer">
                        My LeetCode Profile
                    </a>
                </li>
            </ul>
        </section>

        <hr>

        <section id="contact">
            <h2>Contact Details</h2>
            <p><strong>Name:</strong> Rishu Maurya</p>
            <p>
                <strong>Email:</strong>
                <a href="mailto:rishumaurya262@gmail.com">
                    rishumaurya262@gmail.com
                </a>
            </p>
            <p>
                <strong>Phone:</strong>
                <a href="tel:+917248516450">+91 7248516450</a>
            </p>
            <p>
                <strong>Location:</strong>
                Bisalpur, Pilibhit, Uttar Pradesh, India
            </p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Rishu Maurya</p>
        <p>Personal Blog / Portfolio Website</p>
        <a href="#home">Back to Top</a>
    </footer>

</body>
</html>
```

## 4. CSS Code

Create another file named `style.css` and write the following code:

```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    color: #222;
    background-color: white;
    line-height: 1.6;
}

header {
    text-align: center;
    padding: 25px;
    border-bottom: 1px solid #ccc;
}

nav {
    text-align: center;
    padding: 15px;
    border-bottom: 1px solid #ccc;
}

nav a {
    display: inline-block;
    color: black;
    text-decoration: none;
    margin: 5px 10px;
}

nav a:hover {
    text-decoration: underline;
}

main {
    width: 85%;
    max-width: 900px;
    margin: 20px auto;
}

section {
    padding: 20px 0;
}

h2 {
    border-bottom: 1px solid #ccc;
    padding-bottom: 8px;
}

h3 {
    margin-bottom: 5px;
}

img {
    display: block;
    max-width: 100%;
    height: auto;
    margin: 15px 0;
}

article {
    padding: 10px 0;
    border-bottom: 1px solid #eee;
}

a {
    color: #222;
}

footer {
    text-align: center;
    padding: 20px;
    border-top: 1px solid #ccc;
}

@media (max-width: 600px) {
    main {
        width: 90%;
    }

    nav a {
        margin: 5px;
    }

    header {
        padding: 15px;
    }
}
```

## 5. Explanation of HTML Tags

| HTML Tag | Purpose |
|---|---|
| `<header>` | Defines the webpage header. |
| `<nav>` | Creates the navigation bar. |
| `<main>` | Contains the main webpage content. |
| `<section>` | Groups related information. |
| `<article>` | Represents an individual project or post. |
| `<h1>` to `<h6>` | Define headings. |
| `<p>` | Defines a paragraph. |
| `<a>` | Creates a hyperlink. |
| `<img>` | Displays an image. |
| `<ul>` | Creates an unordered list. |
| `<ol>` | Creates an ordered list. |
| `<li>` | Defines a list item. |
| `<footer>` | Defines the webpage footer. |

Semantic HTML means using tags that describe the meaning of their content, such as `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>`.

## 9. Conclusion

In this assignment, I learned how to create a personal blog and portfolio website using HTML and CSS. I learned to use semantic HTML tags, navigation links, images, lists, and hyperlinks. I also learned how to organize personal information, educational qualifications, technical skills, and projects on a webpage.

This project helped me understand the basic structure of a personal portfolio website and how CSS can improve its readability and usability.
