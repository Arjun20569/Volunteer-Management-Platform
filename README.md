<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
  <h1>🏥 Hospital Servlet Application</h1>
  <p>
    A web-based application for hospital management, utilizing Java Servlets, JSP, and a MySQL database. This project facilitates user registration, login, and management of hospital-related data.
  </p>

  <h2>📋 Features</h2>
  <ul>
    <li>User authentication (registration and login)</li>
    <li>Dynamic user data handling using JSP and Servlets</li>
    <li>Robust input validation on both client and server sides</li>
    <li>Modular and clean code structure following best practices</li>
  </ul>

  <h2>📂 Project Structure</h2>
  <pre>
<code>
.
├── src
│   ├── com
│   │   ├── hospital
│   │   │   ├── controller
│   │   │   ├── dao
│   │   │   ├── model
│   │   │   ├── util
│   ├── resources
│   ├── webapp
│       ├── WEB-INF
│       │   ├── jsp
│       │   ├── web.xml
├── pom.xml
</code>
  </pre>

  <h2>🚀 Getting Started</h2>
  <h3>Prerequisites</h3>
  <ul>
    <li>Java Development Kit (JDK) 8 or higher</li>
    <li>Apache Tomcat server</li>
    <li>MySQL database</li>
    <li>Maven build tool</li>
  </ul>

  <h3>Setup Instructions</h3>
  <ol>
    <li>Clone the repository:</li>
    <pre><code>git clone https://github.com/Candbury/Hospital_Servlet.git</code></pre>
    <li>Navigate to the project directory:</li>
    <pre><code>cd Hospital_Servlet</code></pre>
    <li>Configure the database in the <code>db.properties</code> file.</li>
    <li>Build the project using Maven:</li>
    <pre><code>mvn clean install</code></pre>
    <li>Deploy the <code>.war</code> file to your Tomcat server.</li>
    <li>Access the application at <code>http://localhost:8080/Hospital_Servlet</code>.</li>
  </ol>

  <h2>📸 Screenshots</h2>
  <h3>Home Page</h3>
  <img src="https://github.com/user-attachments/assets/0cb7ba1d-03d0-4927-b828-8571f715a169" alt="Home Page">
  
  <h3>Search Page</h3>
  <img src="https://github.com/user-attachments/assets/e37c28c8-6806-471f-a211-79af539e60fd" alt="Search Page">
  
  <h3>Login Page</h3>
  <img src="https://github.com/user-attachments/assets/8dfbf30c-14d9-433c-a730-3c247c6b4f4e" alt="Login Page">
  
  <h3>Register Page</h3>
  <img src="https://github.com/user-attachments/assets/3b4eac63-4831-4ba2-a53f-fe492ae87f23" alt="Register Page">


  <h2>🛠️ Technologies Used</h2>
  <ul>
    <li><strong>Backend:</strong> Java Servlets, JSP</li>
    <li><strong>Database:</strong> MySQL</li>
    <li><strong>Frontend:</strong> HTML, CSS, JavaScript</li>
    <li><strong>Build Tool:</strong> Maven</li>
    <li><strong>Server:</strong> Apache Tomcat</li>
  </ul>

  <h2>🤝 Contributing</h2>
  <p>
    Contributions are welcome! To contribute:
  </p>
  <ol>
    <li>Fork the repository.</li>
    <li>Create a feature branch: <code>git checkout -b feature-name</code>.</li>
    <li>Commit your changes: <code>git commit -m "Description"</code>.</li>
    <li>Push to the branch: <code>git push origin feature-name</code>.</li>
    <li>Open a pull request.</li>
  </ol>

  <h2>📜 License</h2>
  <p>This project is licensed under the terms of Chaman and his team.</p>

  <h2>📬 Contact</h2>
  <p>
    For inquiries or issues, please reach out via the <a href="https://github.com/Candbury">GitHub repository</a>.
  </p>
</body>
</html>
