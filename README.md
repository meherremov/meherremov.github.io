<!DOCTYPE html>
<html>
<head>
  <title>My GitHub Clone</title>
  <style>
    body {
      margin: 0;
      font-family: Arial;
      background: #0d1117;
      color: white;
    }

    .top {
      background: #161b22;
      padding: 15px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .container {
      display: flex;
      height: 90vh;
    }

    .sidebar {
      width: 250px;
      background: #161b22;
      padding: 15px;
    }

    .main {
      flex: 1;
      padding: 20px;
    }

    .repo {
      background: #21262d;
      padding: 10px;
      margin-bottom: 10px;
      border-radius: 6px;
    }

    input {
      padding: 6px;
      border-radius: 5px;
      border: none;
      width: 200px;
    }
  </style>
</head>

<body>

  <div class="top">
    <div>MyGit</div>
    <input placeholder="Search..." />
    <div>Profile</div>
  </div>

  <div class="container">
    
    <div class="sidebar">
      <h3>Repositories</h3>
      <p>lnxvex/project1</p>
      <p>lnxvex/site</p>
      <p>lnxvex/test</p>
    </div>

    <div class="main">
      <h2>Activity</h2>

      <div class="repo">📁 Project 1 - HTML site</div>
      <div class="repo">📁 Portfolio website</div>
      <div class="repo">📁 Test project</div>

    </div>

  </div>

</body>
</html>
