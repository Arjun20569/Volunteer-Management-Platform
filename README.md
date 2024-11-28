<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Medicare App</title>
</head>
<body>
  <h1>🚀 Medicare App</h1>
  <p>
    A comprehensive healthcare application designed to connect patients with doctors, manage appointments, and provide feedback. The app consists of a full-stack setup using Node.js, Express, MongoDB, and React with Tailwind CSS for styling.
  </p>

  <h2>🛠️ Features</h2>
  <ul>
    <li>User authentication (register, login, protected routes)</li>
    <li>Doctor profiles and services listing</li>
    <li>Booking and managing appointments</li>
    <li>Reviews and feedback system</li>
    <li>Responsive design with Tailwind CSS</li>
  </ul>

  <h2>📂 Project Structure</h2>
  <p>The project is divided into two main folders:</p>
  <ul>
    <li>
      <strong>Backend/</strong>
      <ul>
        <li>Contains the backend code, including API routes, controllers, and database models.</li>
      </ul>
    </li>
    <li>
      <strong>src/</strong>
      <ul>
        <li>Contains the frontend code built with React.</li>
      </ul>
    </li>
  </ul>

  <h2>🚀 Getting Started</h2>
  <h3>Prerequisites</h3>
  <p>Ensure you have the following installed:</p>
  <ul>
    <li>Node.js</li>
    <li>MongoDB</li>
    <li>Git</li>
  </ul>

  <h3>Installation</h3>
  <pre><code>git clone https://github.com/Candbury/medicare-app-main.git</code></pre>
  <pre><code>cd medicare-app-main</code></pre>

  <h3>Backend Setup</h3>
  <ol>
    <li>Navigate to the <code>Backend</code> folder:</li>
    <pre><code>cd Backend</code></pre>
    <li>Install dependencies:</li>
    <pre><code>npm install</code></pre>
    <li>Create a <code>.env</code> file with the following variables:</li>
    <pre><code>PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret</code></pre>
    <li>Start the server:</li>
    <pre><code>npm start</code></pre>
  </ol>

  <h3>Frontend Setup</h3>
  <ol>
    <li>Navigate back to the project root:</li>
    <pre><code>cd ..</code></pre>
    <li>Install dependencies:</li>
    <pre><code>npm install</code></pre>
    <li>Start the frontend development server:</li>
    <pre><code>npm run dev</code></pre>
    <li>Visit <code>http://localhost:3000</code> in your browser.</li>
  </ol>

  <h2>📜 Scripts</h2>
  <p>In the project directory, you can run:</p>
  <ul>
    <li><code>npm run dev</code> - Starts the frontend in development mode.</li>
    <li><code>npm start</code> - Starts the backend server.</li>
  </ul>

  <h2>🔐 Environment Variables</h2>
  <p>
    The backend requires a <code>.env</code> file with the following variables:
  </p>
  <ul>
    <li><code>PORT</code> - The port number for the backend server.</li>
    <li><code>MONGO_URI</code> - MongoDB connection URI.</li>
    <li><code>JWT_SECRET</code> - Secret key for JWT authentication.</li>
  </ul>

  <h2>📂 Folder Structure</h2>
  <pre><code>.
├── Backend
│   ├── auth
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── .env
│   ├── package.json
├── src
│   ├── Components
│   ├── Dashboard
│   ├── Hooks
│   ├── Layout
│   ├── Pages
│   ├── Routes
│   ├── Services
│   ├── assets
│   ├── index.css
│   ├── main.jsx
├── package.json
├── tailwind.config.js
└── vite.config.js</code></pre>

  <h2>🛠️ Technologies Used</h2>
  <ul>
    <li><strong>Backend:</strong> Node.js, Express, MongoDB</li>
    <li><strong>Frontend:</strong> React, Tailwind CSS, Vite</li>
    <li><strong>Authentication:</strong> JWT</li>
  </ul>

  <h2>📸 Screenshots</h2>
  <h3>Home Page</h3>
  <img src="https://github.com/user-attachments/assets/0cb7ba1d-03d0-4927-b828-8571f715a169" alt="Home Page">
  
  <h3>Search Page</h3>
  <img src="https://github.com/user-attachments/assets/e37c28c8-6806-471f-a211-79af539e60fd" alt="Search Page">
  
  <h3>Login Page</h3>
  <img src="https://github.com/user-attachments/assets/8dfbf30c-14d9-433c-a730-3c247c6b4f4e" alt="Login Page">
  
  <h3>Register Page</h3>
  <img src="https://github.com/user-attachments/assets/3b4eac63-4831-4ba2-a53f-fe492ae87f23" alt="Register Page">

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
  <p>This project is licensed under Chaman and team.</p>

  <h2>📬 Contact</h2>
  <p>
    For any inquiries or issues, please reach out via the <a href="https://github.com/Candbury">GitHub repository</a>.
  </p>
</body>
</html>
