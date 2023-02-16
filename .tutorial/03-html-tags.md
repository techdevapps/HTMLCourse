# HTML Tags

Congratulations on making it this far! You now have a solid understanding of some of the most common HTML elements. 🎉

In this chapter, we'll be exploring the world of HTML tags - the building blocks of a web page. HTML tags allow you to structure your content and create different types of elements like text, images, links, and tables.

Let's start by taking a look at some of the most commonly used HTML tags:

## Headings 📝

Headings are used to define the heading of a page or section. They range from `<h1>` to `<h6>`, with `<h1>` being the largest and most important.

```html
<h1>This is a Heading 1</h1>
<h2>This is a Heading 2</h2>
<h3>This is a Heading 3</h3>
```

Images 🌅
Images are used to display visual content on a web page.

```
<img src="path/to/image.jpg" alt="A beautiful picture of a sunset">
```

Semantic HTML5 Tags 🌐
Semantic HTML5 tags provide meaning to the content of a web page, making it easier for search engines and screen readers to understand the structure of the page. Some of the most commonly used semantic HTML5 tags include:

```
<header>
  <!-- Header content goes here -->
</header>

<nav>
  <!-- Navigation content goes here -->
</nav>

<main>
  <!-- Main content goes here -->
</main>

<footer>
  <!-- Footer content goes here -->
</footer>
```

Audio and Video 🎥
HTML5 introduced several new tags for multimedia content, making it easy to embed audio and video directly into a web page.

```
<audio src="path/to/audio.mp3" controls></audio>
<video src="path/to/video.mp4" controls></video>
```

The src attribute specifies the URL of the audio or video file, while the controls attribute adds basic controls for playing, pausing, and seeking through the media.

Canvas 🎨
The `<canvas>` tag provides a way to draw graphics and animations using JavaScript. It allows you to create dynamic and interactive web pages with custom animations, games, and visualizations.

```
<canvas id="myCanvas" width="200" height="100"></canvas>
```

You can then use JavaScript to manipulate the canvas and draw shapes, lines, and text.

SVG 🎭
The `<svg>` tag is used to define vector graphics on a web page. SVG images can be scaled without losing quality and are ideal for creating logos, icons, and other graphics.

```
<svg width="100" height="100">
  <rect x="10" y="10" width="80" height="80" fill="red" />
</svg>
```

In this example, we're using the `<rect>` tag to draw a rectangle inside the `<svg>` tag. The `x` and `y` attributes define the position of the rectangle, while the width and height attributes define its size.

Below is the full HTML code, including all the HTML elements we covered

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Web Page</title>
  </head>
  <body>
    <header>
      <h1>My Web Page</h1>
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <article>
        <h2>My Article</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod ante vitae felis lobortis auctor.</p>
        <p>Etiam vel lectus eu ex volutpat pulvinar at quis mauris. Aenean maximus volutpat tortor vel gravida.</p>
      </article>
      <aside>
        <h2>My Sidebar</h2>
        <ul>
          <li>Item 1</li>
          <li>Item 2</li>
          <li>Item 3</li>
        </ul>
      </aside>
    </main>
    <footer>
      <p>&copy; 2023 My Web Page</p>
    </footer>
    <audio src="path/to/audio.mp3" controls></audio>
    <video src="path/to/video.mp4" controls></video>
    <canvas id="myCanvas" width="200" height="100"></canvas>
    <svg width="100" height="100">
      <rect x="10" y="10" width="80" height="80" fill="red" />
    </svg>
  </body>
</html>

```

replace the content of index.html file with above code, and click `run` and see the result.
