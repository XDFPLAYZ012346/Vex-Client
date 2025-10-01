<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vex Client Downloads</title>
  <style>
    body { font-family: Arial; background: #111; color: #fff; text-align: center; }
    .download-btn { padding: 10px 20px; background: #ff0066; border: none; color: #fff; cursor: pointer; margin: 10px; border-radius: 5px; }
    .file-content { margin-top: 20px; background: #222; padding: 15px; border-radius: 5px; text-align: left; max-width: 600px; margin-left: auto; margin-right: auto; }
  </style>
</head>
<body>
  <h1>Vex Client Downloads</h1>
  
  <!-- Download Button -->
  <a href="https://drive.google.com/yourfilelink" target="_blank">
    <button class="download-btn">Download Vex Client</button>
  </a>

  <!-- File Contents Section -->
  <div class="file-content" id="fileContent">
    Enter File Contents Here
  </div>

  <script>
    // Agar aap JS se dynamically file content dikhana chahte ho
    const fileContentDiv = document.getElementById('fileContent');
    fileContentDiv.innerHTML = `
      Version: 1.0.0<br>
      Release Date: 01-10-2025<br>
      Features:<br>
      - Skins Customization<br>
      - Mods Import<br>
      - Multiple Minecraft Versions Supported
    `;
  </script>
</body>

</html>
