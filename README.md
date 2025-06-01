<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Burger AR</title>
  <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script>
</head>
<body style="margin:0;">
  <model-viewer 
    src="burger.glb"
    ar 
    ar-modes="scene-viewer quick-look webxr"
    auto-rotate 
    camera-controls 
    style="width: 100%; height: 100vh;">
  </model-viewer>
</body>
</html>
