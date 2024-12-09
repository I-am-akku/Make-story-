<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Picture & Story</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Story</h1>
        <div class="button-container">
            <button onclick="toggleStory()">Show/Hide Story</button>
            <button onclick="changeBackgroundColor()">Change Background Color</button>
            <button onclick="toggleImage()">Change Picture</button>
        </div>
    </header>
    <main>
        <section class="image-story">
            <img id="storyImage" src="your-picture.jpg" alt="My Picture">
            <div class="story">
                <h2>My Story</h2>
                <p id="storyText">This is where you write your story about the picture. It can be as long or as short as you'd like!</p>
            </div>
        </section>
    </main>
    <footer>
        <p>© 2024 Your Name</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
