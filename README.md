<h1 align="center">👩‍💼 Employee CRUD Admin Web App - Prodigy FS Internship Task 01</h1>

<p align="center">
  A secure and simple web app for administrators to manage employee data with full CRUD functionality, authentication, and validation.
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#tech-stack">Tech Stack</a> •
  <a href="#setup">Setup</a> •
  <a href="#api-endpoints">API</a> •
  <a href="#screenshots">Screenshots</a> •
  <a href="#postman">Postman</a> •
  <a href="#security">Security</a>
</p>

---

<h2 id="features">✨ Features</h2>

<ul>
  <li>Admin registration & login (JWT authentication)</li>
  <li>Create, Read, Update, Delete employee records</li>
  <li>Input validation (express-validator)</li>
  <li>Protected routes</li>
  <li>MongoDB + Mongoose integration</li>
</ul>

---

<h2 id="tech-stack">🧰 Tech Stack</h2>

<ul>
  <li><b>Backend:</b> Node.js, Express.js</li>
  <li><b>Database:</b> MongoDB, Mongoose</li>
  <li><b>Auth:</b> JWT, bcrypt</li>
  <li><b>Validation:</b> express-validator</li>
  <li><b>Tools:</b> Postman, dotenv, nodemon</li>
</ul>

---

<h2 id="setup">⚙️ Setup Instructions</h2>

<ol>
  <li>Clone the repo:
    <pre><code>git clone https://github.com/your-username/employee-crud-app.git</code></pre>
  </li>
  <li>Install dependencies:
    <pre><code>npm install</code></pre>
  </li>
  <li>Set up your <code>.env</code>:
    <pre><code>
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/employeeDB
JWT_SECRET=yourSuperSecretKey
    </code></pre>
  </li>
  <li>Run the app:
    <pre><code>node app.js</code></pre>
  </li>
</ol>

---

<h2 id="api-endpoints">🔗 API Endpoints</h2>

<h3>Auth Routes</h3>
<pre>
POST   /api/auth/register     ➤ Register new admin  
POST   /api/auth/login        ➤ Login as admin
</pre>

<h3>Employee Routes (JWT required)</h3>
<pre>
GET    /api/employees         ➤ List all employees  
GET    /api/employees/:id     ➤ Get employee by ID  
POST   /api/employees         ➤ Add new employee  
PUT    /api/employees/:id     ➤ Update employee  
DELETE /api/employees/:id     ➤ Delete employee
</pre>

---

<h2 id="screenshots">🖼️ Screenshots</h2>

<p>
  <b>✅ Register Admin in Postman:</b><br /> 
</p> 
  ![image alt](https://github.com/Neha-20-bit/Neha-20-bit/blob/main/screen%20shot.jpeg?raw=true)


---

<h2 id="postman">📫 Postman Collection</h2>

<p>Import the included Postman collection to test all endpoints easily. Here's how:</p>

<ol>
  <li>Open Postman</li>
  <li>Click <b>Import</b></li>
  <li>Select <code>employee-crud-app.postman_collection.json</code></li>
</ol>

---

<h2 id="security">🔒 Security Notes</h2>

<ul>
  <li>All passwords hashed with bcrypt</li>
  <li>JWT-based authentication with 1 hour expiry</li>
  <li>All sensitive routes are protected with token middleware</li>
</ul>

---

<h3 align="center">📌 Project by NEHA — <a href="https://github.com/your-username">GitHub</a></h3>


