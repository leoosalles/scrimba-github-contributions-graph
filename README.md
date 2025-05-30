# scrimba-github-contributions-graph
A <strong>dynamic, CSS-styled contributions graph</strong>, inspired by GitHub's contribution tracking. This project uses <strong>JavaScript to generate the graph</strong> and <strong>CSS Grid for layout</strong>, providing a visually appealing way to display activity levels.
<h2>✨ Features</h2>
<ul>
  <li>
    <strong>Automatically generated contribution graph</strong> using JavaScript
  </li>
  <li>
    <strong>CSS Grid-based layout</strong>, perfectly structured for weekly tracking
  </li>
  <li>
    <strong>Color-coded squares</strong> based on contribution activity
  </li>
  <li>
    <strong>Lightweight and responsive design</strong>
  </li>
</ul>
<h2>🔧 How It Works</h2>
<h3>HTML & JavaScript Structure</h3>
<ul>
  <li>
    The graph consists of <strong>7 rows (days of the week)</strong> and <strong>52 columns (weeks of the year)</strong>
  </li>
  <li>
    The JavaScript code randomly assigns <strong>contribution levels</strong>:<br>
    🔹<code>0</code> (no activity)<br>
    🔹<code>3</code> (low activity)<br>
    🔹<code>5</code> (medium activity)<br>
    🔹<code>10</code> (high activity)<br>
  </li>
  <li>
    Each square is assigned a <strong>data-value</strong>, which determines its background color
  </li>
</ul>
<h2>CSS Techniques Used</h2>
<ul>
  <li>
    <strong>CSS Grid</strong> for organizing squares efficiently
  </li>
  <li>
    <strong>Attribute selectors (<code>[data-value]</code>)</strong> to style contribution levels
  </li>
  <li>
    <strong>Color transitions</strong> for visual hierarchy
  </li>
  <li>
    <strong>Flexbox for graph positioning</strong>
  </li>
</ul>
