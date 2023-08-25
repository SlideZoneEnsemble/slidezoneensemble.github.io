<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Slide Zone Ensemble</title>
<style>
  /* Styles for body, header, container, and segments (same as before) */
  .video-box {
    max-width: 800px;
    margin: 0 auto;
  }
  .video-container {
    position: relative;
    padding-bottom: 56.25%; /* 16:9 aspect ratio */
    height: 0;
    overflow: hidden;
  }
  .video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
  }
  /* Additional styles for description and calendar go here */
  .social-links {
    text-align: center;
    margin-top: 20px;
  }
  .social-icon {
    font-size: 24px;
    margin: 0 10px;
    color: #333;
  }
</style>
</head>
<body>
  <div class="header">
    <h1>Slide Zone Ensemble</h1>
  </div>
  <div class="segment" id="segment1">
    <div class="video-box">
      <div class="video-container">
        <iframe class="video" src="https://www.youtube.com/embed/your-video-id" frameborder="0" allowfullscreen></iframe>
      </div>
    </div>
  </div>
  <div class="segment" id="segment2">
    <h2>About Slide Zone Ensemble</h2>
    <p>We are a group of passionate musicians dedicated to creating mesmerizing melodies and harmonious compositions. With a diverse range of instruments and styles, we aim to captivate audiences around the world.</p>
  </div>
  <div class="segment" id="segment3">
    <h2>Upcoming Events</h2>
    <div class="calendar">
      <!-- Calendar content goes here -->
    </div>
    <div class="social-links">
      <a href="#" class="social-icon">Facebook</a>
      <a href="#" class="social-icon">Twitter</a>
      <a href="#" class="social-icon">Instagram</a>
    </div>
  </div>
  <script>
    /* Scroll animation script (same as before) */
  </script>
</body>
</html>
