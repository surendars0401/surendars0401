<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Portfolio</title>
<style>
  .flex-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
  }

  .flex-item {
    flex: 1;
    min-width: 250px; /* Minimum width of each flex item */
    text-align: center;
    margin: 10px;
  }

  /* Add styles for icons and images as needed */
</style>
</head>
<body>
<div class="flex-container">
  <div class="flex-item">
    <h3>My Tech Stack</h3>
    <a href="https://skillicons.dev">
      <img src="https://skillicons.dev/icons?i=arduino,raspberrypi,bash,c,cpp,opencv,linux,py,fastapi,aws,html,css,bootstrap,js,mysql,docker&perline=4" alt="Tech Stack Icons">
    </a>
  </div>
  <div class="flex-item">
    <img src="https://leetcard.jacoblin.cool/surendars0401?ext=heatmap" alt="Leetcode Stats">
  </div>
</div>
</body>
</html>
