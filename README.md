<h2>⚽ Football Records Management Application</h2>

<p><strong>Technologies:</strong> Node.js, Express, MongoDB, React, Axios</p>

<h3>📌 Project Overview</h3>
<ul>
  <li>Developed a full-stack web application to manage and maintain football data records.</li>
  <li>Implemented RESTful APIs using <strong>Node.js</strong> and <strong>Express</strong> for robust backend operations.</li>
  <li>Built a dynamic and responsive frontend using <strong>React</strong>, styled with Bootstrap for an intuitive UI.</li>
  <li>Utilized <strong>MongoDB</strong> for structured data storage and Axios for efficient client-server communication.</li>
  <li>Focused on code modularity, using reusable components and clean architecture for scalability and maintainability.</li>
  <li>Performed rigorous testing and debugging to ensure a smooth, reliable user experience.</li>
</ul>

<h3>🎯 Key Outcomes</h3>
<ul>
  <li>Exhibited strong full-stack development capabilities with REST API integration.</li>
  <li>Demonstrated UI/UX proficiency and advanced problem-solving during testing cycles.</li>
</ul>

<p><strong>🔗 GitHub Repository:</strong> <a href="https://github.com/a-uddin/Football_Data_management" target="_blank">github.com/a-uddin/Football_Data_management</a></p>

<h2>📂 Full-Stack Application Overview</h2>

<p>This project is a full-stack <strong>Football Records Management Application</strong> built with <strong>Node.js</strong>, <strong>Express</strong>, <strong>MongoDB</strong>, <strong>Mongoose</strong>, and a <strong>React</strong> frontend. It showcases modular API design, robust data management, and interactive UI, serving both CRUD and advanced query functionalities via a clean RESTful architecture.</p>

<h3>🧩 Backend Overview</h3>
<ul>
  <li><strong>Data Source:</strong> CSV file imported into a MongoDB collection called <code>FootballData</code>.</li>
  <li><strong>Mongoose Schema:</strong> Defined in a separate JS file to structure fields like Team, Games Played, Wins, Goals, etc.</li>
  <li><strong>MongoDB Connection:</strong> Handled in a dedicated config file for secure database integration.</li>
  <li><strong>REST API (server.js):</strong> Express-based server implementing the following routes:
    <ul>
      <li><code>POST /add</code>: Add new record to MongoDB.</li>
      <li><code>POST /update</code>: Update a team record by team name.</li>
      <li><code>POST /delete</code>: Delete a record by team name.</li>
      <li><code>GET /summary/:year</code>: View total Games Played, Draw, and Wins for a given year.</li>
      <li><code>GET /top10/:wins</code>: View first 10 teams with Wins greater than the specified value.</li>
      <li><code>GET /average-goals/:year</code>: Show teams where average 'Goals For' matches the year input.</li>
    </ul>
  </li>
</ul>

<h3>🎨 Frontend Overview (React + Axios)</h3>
<ul>
  <li>All components are built using React functional components with routing support via React Router DOM.</li>
  <li>Axios is used to consume REST APIs securely and efficiently.</li>
  <li><strong>Features:</strong>
    <ul>
      <li><strong>Add Team Record:</strong> A form component to input and submit new football records.</li>
      <li><strong>Update Record:</strong> A form to update any field for a given team.</li>
      <li><strong>Team Summary:</strong> A component to display total Games Played, Wins, and Draws for a selected year.</li>
      <li><strong>Delete Record:</strong> A simple form to delete records based on team name.</li>
      <li><strong>Top 10 Results:</strong> List of top 10 teams with wins greater than a specified threshold.</li>
      <li><strong>Average Goals Query:</strong> Component to show teams with a matching average 'Goals For' by year.</li>
    </ul>
  </li>
  <li><strong>Routing:</strong> All components are wrapped in a central React Router App with intuitive navigation.</li>
</ul>

<h3>🧠 Technical Highlights</h3>
<ul>
  <li>Separation of concerns: Schema, DB connection, and REST endpoints are modularized.</li>
  <li>Uses MongoDB Atlas for cloud-based persistence and real-time queries.</li>
  <li>All backend operations validated using Postman and frontend UI interactions.</li>
</ul>
