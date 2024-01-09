<p align="center">
  <img src="Hello, (2).png" alt="Hello World">
</p>

<table align="center" width="100%">
  <tr>
    <td align="center">
      <h3>My Tech Stack</h3>
      <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=arduino,raspberrypi,bash,c,cpp,opencv,linux,py,fastapi,aws,html,css,bootstrap,js,mysql,docker&perline=4" alt="Tech Stack Icons">
      </a>
    </td>
    <td align="center">
      <img src="https://leetcard.jacoblin.cool/surendars0401?ext=heatmap" alt="Leetcode Stats">
    </td>
  </tr>
</table>
<p align="center">
  <!-- Use an empty container to dynamically add SVGs -->
  <div id="svgContainer"></div>
</p>

<script>
// Assuming your SVG files are named from "svg1.svg" to "svg58.svg"
for (let i = 1; i <= 58; i++) {
  // Create an image element for each SVG
  const img = document.createElement('img');
  
  // Set the source and alt attributes for each SVG
  img.src = `I am suren_000/svg${i}.svg`;
  img.alt = `SVG ${i}`;
  
  // Append each image to the container
  document.getElementById('svgContainer').appendChild(img);
}
</script>
