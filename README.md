### Hi there 👋

<!--
**lahuudang1504/lahuudang1504** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
html
<!DOCTYPE html>
<html>
<head>
    <title>PUBG Mobile Website</title>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
    <header>
        <h1>PUBG Mobile Website</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">News</a></li>
            <li><a href="#">Gameplay</a></li>
            <li><a href="#">Weapons</a></li>
            <li><a href="#">Maps</a></li>
            <li><a href="#">About</a></li>
        </ul>
    </nav>

    <main>
        <section>
            <h2>Latest News</h2>
            <div class="news-container">
                <div class="news-item">
                    <img src="news1.jpg" alt="News 1">
                    <h3>Update 1.0: New Map and Features</h3>
                    <p>Explore the new Livik map and experience exciting gameplay improvements.</p>
                </div>
                <div class="news-item">
                    <img src="news2.jpg" alt="News 2">
                    <h3>New Weapon: Famas</h3>
                    <p>Master the Famas assault rifle and dominate your enemies on the battlefield.</p>
                </div>
                <div class="news-item">
                    <img src="news3.jpg" alt="News 3">
                    <h3>Esports Championship 2022</h3>
                    <p>Witness the intense battles as the top PUBG Mobile teams compete for the championship title.</p>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2022 PUBG Mobile Website. All rights reserved.</p>
    </footer>
</body>
</html>
CSS (style.css):
css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #111;
    color: #fff;
    padding: 20px;
    text-align: center;
}

nav {
    background-color: #333;
    color: #fff;
    padding: 10px;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 10px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 20px;
}

h2 {
    color: #333;
}

.news-container {
    display: flex;
    flex-wrap: wrap;
}

.news-item {
    flex-basis: 33.33%;
    padding: 10px;
}

.news-item img {
    width: 100%;
    height: auto;
}

.news-item h3 {
    margin-top: 10px;
    color: #333;
}

.news-item p {
    color: #555;
}

footer {
    background-color: #111;
    color: #fff;
    padding: 10px;
    text-align: center;
}
