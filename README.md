# Building a Band Website with HTML

---

## Description

In this assignment, you will help a fictional band, "The Rockstars," build their website by integrating images and videos using HTML. Your task is to enhance the band's online presence by embedding engaging visual content, such as band photos, album covers, and music videos, directly into their web pages. This project will deepen your understanding of HTML by practicing key tags and attributes like <img> and <video>, allowing you to create visually appealing and accessible multimedia elements that bring the band's story to life.

## Learning Outcomes

- Understand basic HTML tags and attributes for images and videos
- Create responsive images
- Embed videos using HTML
- Implement accessibility features in HTML

---

## ToDo list ✅

[ ] Open your terminal (terminal, Git Bash) and navigate to the directory where you want to create your project using the `cd` command. Create a new directory named `band-website` for your project, `cd` into it, and open Visual Studio Code by running (one at a time):
```
mkdir band-website
cd band-website
code .
```

[ ] Create a new HTML file named `index.html` and add the basic HTML structure:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Rockstars</title>
</head>
<body>

    <header>
        <h1>Welcome to The Devs' Official Website</h1>
    </header>

    <main>
        <!-- Band logo will go here -->
        <!-- Concert pictures will go here -->
        <!-- Music video will go here -->
    </main>

</body>
</html>
```

[ ] Use the `<img>` tag to add the logo (located in `./assets/images`) to the webpage:
```
<header>
    <h1>Welcome to The Devs' Official Website</h1>
    <img src="./assets/images/band.jpg" alt="The Devs Band" width="200">
</header>
```

[ ]  Use the `<img>` tag to add concert images (located in `./assets/images`) to the webpage:
```
<main>
    <h2>Our Latest Concert</h2>
    <img src="./assets/images/concert1.jpg" alt="The Devs performing live" width="200">
    <img src="./assets/images/concert2.jpg" alt="Audience enjoying the concert" width="200">
</main>
```

[ ] Use the `<figure>` and `<figcaption>` tags to add a caption to one of the concert pictures:
```
<main>
    <h2>Our Latest Concert</h2>
    <figure>
        <img src="./assets/images/concert1.jpg" alt="The Devs performing live" width="200">
        <figcaption>The Devs rocking the stage!</figcaption>
    </figure>
    <img src="./assets/images/concert2.jpg" alt="Audience enjoying the concert" width="200">
</main>
```

[ ] Use the `<video>` tag to embed the band's latest music video under the images. Ensure the video has controls:
```
<h2>Watch Our Latest Music Video</h2>
<video src="./assets/videos/music-video.mp4" controls muted style="max-width: 100%;">
    Your browser does not support the video tag.
</video>
```
