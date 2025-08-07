<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>360 Photo Viewer</title>
  <!-- Include A-Frame from CDN -->
  <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
</head>
<body>
  <!-- Create the A-Frame scene -->
  <a-scene>
    <!-- Add the 360-degree image as the sky -->
    <a-sky src="https://iili.io/FiMNjnt.jpg"></a-sky>

    <!-- Optional: Add a camera so the user can look around -->
    <a-entity position="0 1.6 0" camera look-controls></a-entity>
  </a-scene>
</body>
</html>
