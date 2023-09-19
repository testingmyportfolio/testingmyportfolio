<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="about">
        <h2>About Me</h2>
        <p>Write a brief introduction about yourself here.</p>
    </section>
    <section id="portfolio">
        <h2>Portfolio</h2>
        <!-- Add your portfolio projects here -->
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>Contact information goes here.</p>
    </section>
</body>
</html>
styles.css (CSS for styling):

css
Copy code
/* Reset some default styles */
body, h1, h2, p {
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
}

header h1 {
    font-size: 2rem;
}

nav ul {
    list-style-type: none;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav a {
    text-decoration: none;
    color: #fff;
}

section {
    padding: 20px;
}

/* Add more CSS for styling as needed */
This example provides a basic structure for your portfolio website with a navigation menu and sections for "About Me," "Portfolio," and "Contact." You would add your actual content and style it according to your preferences. You can also create separate HTML and CSS files for each portfolio project and link to them from the "Portfolio" section.

For a more sophisticated and personalized portfolio, you may consider using a web development framework or a website builder that offers templates and customization options.






