<html>
<style>
  background-color: black;
</style>
<head>
  
<style>
  .container-lg { max-width: initial; }

html, body {

  overscroll-behavior: none;
  
}

.header {
  background-color: black;
}

.bgImage {
  width: 100vw;
  position: absolute;
  left: calc(-50vw + 50%);
  margin-top: -32px;
  z-index: -1;
  
  /* The image used */
  background-image: url("/Water_place.png");

  /* Full height */
  height: 100vh; 

  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

</style>
</head>

<div class="header">
  <p>
    Hello this is a test!
  </p>
</div>

<body>
<div class="bgImage"></div>

<p>This example creates a full page background image. Try to resize the browser window to see how it always will cover the full screen (when scrolled to top), and that it scales nicely on all screen sizes.</p>

</body>
</html>
