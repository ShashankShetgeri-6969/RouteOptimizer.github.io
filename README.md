<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<style>
    /* Reset default margin and padding */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Global Styles */
body {
    font-family: 'Poppins', sans-serif;
    background-color: #f5f5f5;
    margin: 0;
    padding: 20px; /* Adding padding to the body to prevent sticking at the top */
    display: flex;
    justify-content: center;
    align-items: flex-start; /* Aligns content towards the top */
    min-height: 100vh;
}

/* Main Container */
section {
    background-color: white;
    padding: 2rem;
    width: 90%;
    max-width: 800px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    text-align: center;
    margin-top: 30px; /* Adding margin to ensure there's space from the top */
}

/* Header */
header {
    background-color: #4CAF50;
    color: white;
    padding: 2rem;
    border-radius: 8px;
    margin-bottom: 1.5rem;
}

header h1 {
    font-size: 2rem;
    margin: 0;
}

header p {
    margin: 1rem 0 0;
}

/* Section Titles */
h2 {
    color: #4CAF50;
    margin-bottom: 1rem;
}

/* List Items */
ul {
    list-style: none;
    padding: 0;
}

ul li {
    background-color: #e7f7e7;
    margin-bottom: 0.5rem;
    padding: 0.75rem;
    border-radius: 5px;
}

/* Links */
a {
    color: #4CAF50;
    text-decoration: none;
    font-weight: bold;
}

a:hover {
    text-decoration: underline;
}

/* Definition List */
dl dt {
    font-weight: bold;
    color: #333;
    margin-top: 1rem;
}

dl dd {
    margin-left: 1.5rem;
    color: #666;
}

/* Blockquote */
blockquote {
    font-style: italic;
    color: #555;
    border-left: 4px solid #4CAF50;
    padding-left: 1rem;
    margin-top: 2rem;
}

/* Responsive Design */
@media (max-width: 600px) {
    section {
        padding: 1.5rem;
    }

    header {
        padding: 1.5rem;
    }
}

</style>
<body>
    <header>
        <h1>Hello, I'm Anusha Rokhade 👋</h1>
        <p>I am passionate about technology and problem-solving. Here's a glimpse of my work:</p>
    </header>
    <section>
        <h2>🛠️ Projects</h2>
        <ul>
            <li><strong>Route Optimizer</strong>: The Route Optimizer problem aims to find the most efficient path or sequence of routes to visit a series of locations while considering constraints like distance, cost, time, and resources..</li>
        </ul>
        <h2>🚀 Skills</h2>
        <ul>
            <li>C++, Python, JavaScript</li>
            <li>Data Structures and Algorithms</li>
            <li>Full Stack Web Development</li>
        </ul>
        <h2>🌐 Find Me Online</h2>
        <ul>
            <li><a href="https://www.linkedin.com/in/anusha-rokhade-400946284/">LinkedIn</a></li>
            <li><a href="https://github.com/anusharokhade">GitHub</a></li>
        </ul>
        <h2>Portfolio Topic</h2>
        <dl>
            <dt>Course Name</dt>
            <dd>Design and Analysis of Algorithms</dd>
            <dt>Course Code</dt>
            <dd>24ECSC205</dd>
            <dt>Name</dt>
            <dd>Anusha Rokhade</dd>
            <dt>SRN</dt>
            <dd>02FE24BCS406</dd>
            <dt>Course Instructor</dt>
            <dd>Prof. Shankar Biradar</dd>
            <dt>University</dt>
            <dd>KLE Technological University, Belgaum</dd>
            <dt>Portfolio Topic/Domain</dt>
            <dd>Route Optimizer</dd>
        </dl>
        <blockquote>“The only way to do great work is to love what you do.” – Steve Jobs</blockquote>
    </section>
</body>
</html>
