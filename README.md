# SafeCity Pulse – Women Safety Companion

A web application for reporting and visualizing safety incidents using Firestore and Google Maps.

## Project Structure

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SafeCity Pulse</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      display: flex; /* horizontal layout */
      min-height: 100vh;
    }

    /* Sidebar (features on left) */
    .sidebar {
      width: 220px;
      background: #6a1b9a; /* purple */
      color: #fff;
      padding: 20px;
      height: 100vh;
      position: fixed; /* stays in place */
      left: 0;
      top: 0;
    }

    .sidebar h2 {
      margin-bottom: 20px;
      font-size: 20px;
    }

    .sidebar ul {
      list-style: none;
      padding: 0;
    }

    .sidebar ul li {
      margin: 15px 0;
    }

    .sidebar ul li a {
      text-decoration: none;
      color: white;
      font-size: 16px;
    }

    .sidebar ul li a:hover {
      text-decoration: underline;
    }

    /* Main content */
    .main {
      margin-left: 240px; /* space for sidebar */
      padding: 20px;
      flex: 1;
      background: #f4f4f9;
    }

    .main h1 {
      color: #333;
    }
  </style>
</head>
<body>
  <!-- Sidebar -->
  <div class="sidebar">
    <h2>Features</h2>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="profile.html">Profile</a></li>
      <li><a href="contact.html">Contact</a></li>
      <li><a href="report.html">Report</a></li>
      <li><a href="awareness.html">Awareness</a></li>
    </ul>
  </div>

  <!-- Main Content -->
  <div class="main">
    <h1>Welcome to SafeCity Pulse</h1>
    <p>This is your SafeCity Pulse project main page content.</p>
  </div>
</body>
</html>
