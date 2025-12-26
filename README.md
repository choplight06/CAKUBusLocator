<section style="
  max-width: 800px;
  margin: 40px auto;
  padding: 32px;
  background: #0f172a;
  color: #e6eefc;
  border: 1px solid #1e2a47;
  border-radius: 16px;
  box-shadow: 0 4px 24px rgba(0,0,0,.3);
  font-family: ui-sans-serif, system-ui, sans-serif;
  line-height: 1.6;
">

  <h1 style="font-size: 2rem; margin-bottom: 0.5em; color: #6ea8fe;">
    CAKU Bus Finder
  </h1>

  <p>
    <strong>CAKU Bus Finder</strong> is a lightweight, client-side web application
    that helps users quickly find the next available bus between two stops on
    Camp Arifjan / Camp Buehring routes.  
    The app is fully static and runs entirely in the browser—no backend required.
  </p>

  <hr style="border: none; border-top: 1px solid #1e2a47; margin: 24px 0;">

  <h2 style="color: #60a5fa;">📁 Files in This Repository</h2>

  <h3 style="margin-top: 16px; color: #93c5fd;">index.html</h3>
  <p>
    The main application file containing:
  </p>
  <ul style="margin-left: 20px;">
    <li>All UI elements and styling</li>
    <li>JavaScript logic for loading and filtering schedules</li>
    <li>Route evaluation and next departure calculations</li>
    <li>Feedback button and UI state handling</li>
    <li>Full browser-only execution for fast deployment</li>
  </ul>

  <h3 style="margin-top: 16px; color: #93c5fd;">schedule_with_pickup_dropoff.json</h3>
  <p>
    Structured data file containing every bus route, including:
  </p>
  <ul style="margin-left: 20px;">
    <li>Route names and active/disabled flags</li>
    <li>Ordered stops and their departure times</li>
    <li>Pickup and dropoff permissions for each stop</li>
    <li>Normalized fields for consistent app logic</li>
  </ul>

  <hr style="border: none; border-top: 1px solid #1e2a47; margin: 24px 0;">

  <h2 style="color: #60a5fa;">⚙️ How It Works</h2>
  <ol style="margin-left: 20px;">
    <li>The page loads the JSON schedule file.</li>
    <li>Stops are normalized and added to dropdown menus.</li>
    <li>The user selects an origin + destination.</li>
    <li>The app determines eligible routes and next departure time.</li>
    <li>Results display in clean, card-style panels.</li>
  </ol>

  <hr style="border: none; border-top: 1px solid #1e2a47; margin: 24px 0;">

  <h2 style="color: #60a5fa;">🚀 Deployment</h2>
  <p>
    Because the app is entirely static:
  </p>
  <ul style="margin-left: 20px;">
    <li>Upload <code>index.html</code> and the JSON file to any static host.</li>
    <li>Ensure they remain in the same directory.</li>
    <li>The app will run instantly on GitHub Pages, Netlify, or Vercel.</li>
  </ul>

  <hr style="border: none; border-top: 1px solid #1e2a47; margin: 24px 0;">

  <h2 style="color: #60a5fa;">💬 Feedback & Future Improvements</h2>
  <ul style="margin-left: 20px;">
    <li>Route visualization or map UI, to include location detection to identify nearest stop to user and allow user to pinpoint on the map where their end goal is.</li>
    <li>User location detection to find nearest stop.</li>
    
    
  <li>Expand across Centcom bases</li>
  </ul>

</section>
