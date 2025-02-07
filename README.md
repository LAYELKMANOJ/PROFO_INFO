Here's an example HTML code for creating a simple web page with name and details, and connecting it with LinkedIn, Instagram, and GitHub:




 
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="about">
            <h1>Your Name</h1>
            <p>Your Profession/Student/Developer/etc.</p>
            <p>About you (brief bio)</p>
        </section>
        <section id="contact">
            <h2>Connect with me</h2>
            <ul>
                <li>
                    <a href="https://www.linkedin.com/in/your-linkedin-id/" target="_blank">
                        <img src="linkedin-icon.png" alt="LinkedIn">
                        LinkedIn
                    </a>
                </li>
                <li>
                    <a href="https://www.instagram.com/your-instagram-id/" target="_blank">
                        <img src="instagram-icon.png" alt="Instagram">
                        Instagram
                    </a>
                </li>
                <li>
                    <a href="https://github.com/your-github-id" target="_blank">
                        <img src="github-icon.png" alt="GitHub">
                        GitHub
                    </a>
                </li>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 Your Name</p>
    </footer>
</body>
</html>
```

You'll need to replace:

- `Your Name` with your actual name
- `Your Profession/Student/Developer/etc.` with your profession or student status
- `About you (brief bio)` with a brief bio about yourself
- `your-linkedin-id` with your actual LinkedIn ID
- `your-instagram-id` with your actual Instagram ID
- `your-github-id` with your actual GitHub ID

You'll also need to create a `styles.css` file to add some basic styling to your web page. Here's an example:

```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1em;
    text-align: center;
}

header nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: space-between;
}

header nav ul li {
    margin-right: 20px;
}

header nav a {
    color: #fff;
    text-decoration: none;
}

main {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 2em;
}

section {
    background-color: #f7f7f7;
    padding: 1em;
    margin-bottom: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h1 {
    font-size: 24px;
    margin-top: 0;
}

h2 {
    font-size: 18px;
    margin-top: 0;
}

ul {
    list-style: none;
    margin: 0;
    padding: 0;
}

li {
    margin-bottom: 10px;
}

a {
    text-decoration: none;
    color: #337ab7;
}

a:hover {
    color: #23527c;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 1em;
    text-align: center;
    clear: both;
}
```

This is just a basic example to get you started. You can customize the HTML and CSS to fit your needs and style.
