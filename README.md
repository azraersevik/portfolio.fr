<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Azra Ersevik - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <div class="container">
            <h1>Azra Ersevik</h1>
        </div>
    </header>

    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <!-- Omettre la description comme demandé -->
        </div>
    </section>

    <section id="projects">
        <div class="container">
            <h2>Projects</h2>
            <div class="project">
                <img src="stockholm_lights.jpg" alt="Stockholm Lights" />
                <!-- Image de lumières de Stockholm en noir et blanc -->
            </div>
            <div class="project">
                <img src="stockholm_friends.jpg" alt="Stockholm Friends" />
                <!-- Image d'amis à Stockholm en noir et blanc -->
            </div>
            <div class="project">
                <img src="stockholm_autumn.jpg" alt="Stockholm Autumn" />
                <!-- Image d'automne à Stockholm en noir et blanc -->
            </div>
            <div class="project">
                <img src="stockholm_hiking.jpg" alt="Stockholm Hiking" />
                <!-- Image de randonnée à Stockholm en noir et blanc -->
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 Azra Ersevik. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>

body {
    font-family: 'Helvetica', 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 30px 0;
}

header h1 {
    margin: 0;
}

section {
    padding: 40px 0;
}

h2 {
    color: #333;
}

.project {
    margin-bottom: 20px;
}

.project img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}

/* Style spécifique au thème scandinave */
body, header, section, footer {
    border: 1px solid #e0e0e0;
    border-radius: 8px;
}

.container {
    background-color: #fff;
}

h1, h2 {
    color: #333;
}

.project img {
    border: 1px solid #e0e0e0;
}
