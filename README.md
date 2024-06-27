<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ARIEVELO ART AND POEMS</title>
    <style>
        body {
            font-family: 'Times New Roman', Times, serif;
            margin: 0;
            padding: 0;
            background-color: #F4F3DD;
            color: #202C61;
        }
        header {
            background-color: #D13D47;
            color: white;
            padding: 20px;
            text-align: center;
            font-family: 'Anton', sans-serif;
        }
        nav {
            background-color: #A21923;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 18px;
        }
        section {
            padding: 20px;
        }
        .about, .art, .poems, .send-poem {
            margin: 20px 0;
        }
        .about h2, .art h2, .poems h2, .send-poem h2 {
            color: #A21923;
            font-family: 'Montaser Arabic', sans-serif;
        }
        .art img {
            max-width: 100%;
            height: auto;
        }
        footer {
            background-color: #202C61;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Arie's Art and Poems</h1>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#art">Art</a>
        <a href="#poems">Poems</a>
        <a href="#send-poem">Send Your Poem</a>
    </nav>
    <section id="about" class="about">
        <h2>About Me</h2>
        <p>Hello! I'm Arie, a young artist wishing to create a space to share my art, poems, and create a community.</p>
    </section>
    <section id="art" class="art">
        <h2>Art</h2>
        <p>Here is where my art will be showcased. Check back soon for updates!</p>
        <!-- You can add images like this -->
        <!-- <img src="path/to/your/art1.jpg" alt="Art 1"> -->
    </section>
    <section id="poems" class="poems">
        <h2>Poems</h2>
        <p>This section will feature my poems. Stay tuned!</p>
    </section>
    <section id="send-poem" class="send-poem">
        <h2>Send Your Poem</h2>
        <form>
            <label for="poem-title">Title:</label><br>
            <input type="text" id="poem-title" name="poem-title"><br>
            <label for="poem-content">Your Poem:</label><br>
            <textarea id="poem-content" name="poem-content" rows="10" cols="30"></textarea><br>
            <input type="submit" value="Submit">
        </form>
    </section>
    <footer>
        <p>Contact me at <a href="mailto:aarievelo@gmail.com">aarievelo@gmail.com</a></p>
        <p>Follow me on Instagram: <a href="https://instagram.com/arievelo_" target="_blank">@arievelo_</a></p>
    </footer>
</body>
</html>
