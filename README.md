<h1 align="center">🎟️ Serverless Online Ticketing System</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Serverless-GCP_Cloud_Run-blue?style=for-the-badge&logo=googlecloud" />
  <img src="https://img.shields.io/badge/PHP-Fullstack-purple?style=for-the-badge&logo=php" />
  <img src="https://img.shields.io/badge/Payments-Cashfree-green?style=for-the-badge" />
</p>

<p align="center">
  <b>A scalable, serverless ticket booking platform with integrated payments</b>
</p>

<hr/>

<h2>📌 Overview</h2>

<p>
This project is a <b>serverless online ticketing system</b> designed to provide a seamless
booking experience for multiple transport modes and events.
</p>

<p>
The application is built entirely using <b>PHP</b>, deployed in a <b>serverless environment
using Google Cloud Run</b>, and integrates a secure <b>Cashfree payment gateway</b>.
</p>

<p>
A <b>MySQL database</b> handles persistent data storage, while <b>Docker</b> ensures consistent
runtime environments and simplified deployments.
</p>

<hr/>

<h2>✨ Features</h2>

<ul>
  <li><b>Serverless Architecture</b> using Google Cloud Run</li>
  <li><b>Secure Payment Integration</b> with Cashfree</li>
  <li><b>Multi-Booking Support</b> for buses, trains, flights, and events</li>
  <li><b>Admin Panel</b> for managing users, bookings, and payments</li>
  <li><b>Responsive UI</b> across desktop and mobile devices</li>
  <li><b>Dockerized Deployment</b> for portability and consistency</li>
</ul>

<hr/>

<h2>🛠️ Tech Stack</h2>

<table>
  <tr><td><b>Frontend & Backend</b></td><td>PHP</td></tr>
  <tr><td><b>Database</b></td><td>MySQL</td></tr>
  <tr><td><b>Payment Gateway</b></td><td>Cashfree</td></tr>
  <tr><td><b>Cloud Platform</b></td><td>Google Cloud Run</td></tr>
  <tr><td><b>Containerization</b></td><td>Docker</td></tr>
</table>

<hr/>

<h2>📁 Project Structure</h2>

<pre>
serverless-ticketing-system/
├── app/
├── config/
├── public/
├── admin/
├── Dockerfile
├── database.sql
└── README.md
</pre>

<hr/>

<h2>⚙️ Installation & Setup</h2>

<h3>Prerequisites</h3>
<ul>
  <li>Docker installed</li>
  <li>MySQL database configured</li>
  <li>Google Cloud account with Cloud Run enabled</li>
</ul>

<h3>Local Setup</h3>

<pre>
git clone &lt;repository-url&gt;
cd &lt;project-directory&gt;

docker build -t ticketing-system .
docker run -p 8080:8080 ticketing-system
</pre>

<p>
The application will be available at:
</p>

<pre>
http://localhost:8080
</pre>

<hr/>

<h2>☁️ Deployment (Google Cloud Run)</h2>

<ul>
  <li>Push Docker image to Google Container Registry (GCR)</li>
  <li>Deploy the image to Google Cloud Run</li>
  <li>Access the app using the Cloud Run service URL</li>
</ul>

<p>
Cloud Run automatically handles scaling and infrastructure management.
</p>

<hr/>

<h2>🚀 Usage</h2>

<ul>
  <li>Browse available transport and event bookings</li>
  <li>Complete secure transactions via Cashfree</li>
  <li>Admins can manage bookings, users, and payments</li>
</ul>

<hr/>

<h2>🤝 Contributions</h2>

<p>Contributions are welcome.</p>

<pre>
git fork
git checkout -b feature-name
git commit -m "Add new feature"
git push origin feature-name
</pre>

<p>
Submit a pull request with a clear description of the changes.
</p>

<hr/>

<h2>👤 Author</h2>

<p>
<b>Vishal Soni</b><br/>
Cloud & DevOps Engineer<br/>
Email: <a href="mailto:vishalsoni6350@gmail.com">vishalsoni6350@gmail.com</a>
</p>

<hr/>

<p align="center">
⭐ If you find this project useful, consider starring the repository.
</p>
