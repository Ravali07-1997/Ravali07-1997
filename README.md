<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Streaming Website</title>
 <style>
 body {
 margin: 0;
 padding: 0;
 font-family: Arial, sans-serif;
 }
 header {
 background-color: #333;
 color: #fff;
 padding: 10px;
 text-align: center;
 }
 nav {
 background-color: #444;
 padding: 10px;
 }
 nav a {
 color: #fff;
 text-decoration: none;
 margin: 0 10px;
 }
 section {
 padding: 20px;
 }
 footer {
 background-color: #333;
 color: #fff;
 padding: 10px;
 text-align: center;
 position: fixed;
 bottom: 0;
 width: 100%;
 }
 .video-container {
 position: relative;
 padding-bottom: 56.25%;
 padding-top: 30px;
 height: 0;
 overflow: hidden;
 }
 .video-container iframe {
 position: absolute;
 top: 0;
 left: 0;
 width: 100%;
 height: 100%;
 }
 </style>
</head>
<body>
 <header>
 <h1>Streaming Website</h1>
 </header>
 <nav>
 <a href="#">Home</a>
 <a href="#">Movies</a>
 <a href="#">TV Shows</a>
 </nav>
 <section>
 <div class="video-container">
 <iframe src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0"
allowfullscreen></iframe>
 </div>
 <h2>Video Title</h2>
 <p>Description of the video goes here.</p>
 <button>Play</button>
 </section>
 <footer>
 <p>&copy; 2023 Streaming Website. All rights reserved.</p>
 </footer>
</body>
</html>
