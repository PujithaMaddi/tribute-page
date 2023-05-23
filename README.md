# tribute-page
# HTMl

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tribute to Albert Einstein</title>
    <link rel="stylesheet" href="styles5.css">
</head>
<body>
    <header>
        <h1>Tribute to Albert Einstein</h1>
        <img src="C:\Users\91994\OneDrive\task5t.jpg",alt="Profile Picture">
    </header>

    <main>
        <section id="introduction">
            <h2>About Albert Einstein</h2>
            <p>
                Albert Einstein was a German-born theoretical physicist who developed the theory of relativity, one of the two pillars of modern physics. 
                His equation E=mc², which arises from the theory of special relativity, is one of the most famous equations in the world.
            </p>
        </section>

        <section id="early-life">
            <h2>Early Life</h2>
            <p>
                Albert Einstein was born on March 14, 1879, in Ulm, in the Kingdom of Württemberg in the German Empire. 
                His family moved to Munich when he was a year old. Einstein showed a strong interest in mathematics and physics from a young age.
            </p>
        </section>

        <section id="achievements">
            <h2>Achievements</h2>
            <ul>
                <li>The Nobel Prize in Physics in 1921</li>
                <li>Development of the theory of general relativity</li>
                <li>Contributions to quantum mechanics</li>
                <li>Explaining the photoelectric effect</li>
            </ul>
        </section>

        <section id="legacy">
            <h2>Legacy</h2>
            <p>
                Albert Einstein's work has had a profound impact on the development of modern physics and our understanding of the universe. 
                His theories and discoveries continue to inspire and influence scientists around the world.
            </p>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 Tribute to Albert Einstein. All rights reserved.</p>
    </footer>
</body>
</html>

# css
body, h1, h2, p, ul {
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

h1 {
    font-size: 30px;
    margin-bottom: 10px;
}

main {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
}

section {
    margin-bottom: 20px;
}

h2 {
    font-size: 24px;
    margin-bottom: 10px;
}

p, ul {
    margin-bottom: 10px;
    line-height: 1.5;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 10px;
    text-align: center;
}
