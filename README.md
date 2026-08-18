<h1 align="center">🍽️ Food Delivery Chatbot</h1>

<p align="center">
  <b>Python • FastAPI • Dialogflow • MySQL</b>
</p>

<p align="center">
  A chatbot-based food ordering application with backend logic,
  database integration, and order tracking.
</p>

<br>

<h2>📌 About the Project</h2>

<p>
<b>Food Delivery Chatbot</b> is a chatbot-based food ordering project
developed using <b>Python</b>, <b>FastAPI</b>, <b>Dialogflow</b>, and
<b>MySQL</b>.
</p>

<p>
The application processes chatbot requests through a FastAPI webhook
and manages food orders using Python backend logic and a MySQL database.
</p>

<h2>✨ Features</h2>

<ul>
  <li>🍔 Add food items to an order</li>
  <li>➖ Remove food items from an order</li>
  <li>🧾 Complete an order</li>
  <li>🔢 Generate an order ID</li>
  <li>💰 Calculate the total order price</li>
  <li>📦 Track order status using an order ID</li>
  <li>💾 Store order information in MySQL</li>
  <li>🔄 Maintain ongoing orders using session IDs</li>
  <li>🔗 Process Dialogflow webhook requests using FastAPI</li>
</ul>

<h2>🛠️ Tech Stack</h2>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/Dialogflow-FF9800?style=for-the-badge&logo=dialogflow&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
</p>

<h2>🏗️ How It Works</h2>

<p align="center">
  <b>User</b>
  <br>↓<br>
  <b>Dialogflow</b>
  <br>↓<br>
  <b>FastAPI Webhook</b>
  <br>↓<br>
  <b>Python Backend</b>
  <br>↓<br>
  <b>MySQL Database</b>
</p>

<h2>📂 Project Structure</h2>

<table>
  <tr>
    <th>File</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><code>main.py</code></td>
    <td>FastAPI application and chatbot request handling.</td>
  </tr>
  <tr>
    <td><code>db_helper.py</code></td>
    <td>MySQL database operations.</td>
  </tr>
  <tr>
    <td><code>generic_helper.py</code></td>
    <td>Helper functions used by the application.</td>
  </tr>
  <tr>
    <td><code>extra.py</code></td>
    <td>Additional project functionality.</td>
  </tr>
  <tr>
    <td><code>pandeyji_eatery.sql</code></td>
    <td>SQL database script.</td>
  </tr>
  <tr>
    <td><code>index.html</code></td>
    <td>HTML interface.</td>
  </tr>
  <tr>
    <td><code>style.css</code></td>
    <td>CSS styling for the interface.</td>
  </tr>
</table>

<h2>🔄 Order Processing</h2>

<ol>
  <li>The user interacts with the chatbot.</li>
  <li>Dialogflow identifies the user's intent.</li>
  <li>The request is sent to the FastAPI webhook.</li>
  <li>The Python backend processes the request.</li>
  <li>Order information is stored or retrieved from MySQL.</li>
  <li>The chatbot returns the appropriate response.</li>
</ol>

<h2>📦 Order Management</h2>

<p>
The application supports an ongoing order workflow where food items
can be added or removed before the order is completed.
</p>

<p>
Once an order is completed, the system calculates the order total,
generates an order ID, and stores tracking information.
</p>

<h2>📊 Database</h2>

<p>
The project uses <b>MySQL</b> for storing and managing food ordering
and order tracking data.
</p>

<p>
The repository includes the SQL database script:
</p>

<p>
<code>pandeyji_eatery.sql</code>
</p>

<h2>🧠 Concepts Practiced</h2>

<ul>
  <li>Python backend development</li>
  <li>FastAPI webhooks</li>
  <li>Dialogflow integration</li>
  <li>MySQL database integration</li>
  <li>Session-based order management</li>
  <li>CRUD/database operations</li>
  <li>API request and response handling</li>
</ul>

<h2>🎯 Purpose</h2>

<p>
This project was developed to practice building a backend-driven
chatbot application and integrating conversational interfaces with
Python and a relational database.
</p>

<hr>

<p align="center">
  <b>👩‍💻 Shrutika Dubey</b>
  <br>
  Computer Science Graduate
</p>

<p align="center">
  <i>Python • FastAPI • Dialogflow • MySQL</i>
</p>
