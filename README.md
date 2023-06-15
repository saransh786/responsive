<!DOCTYPE html>
<html>
<head>
  <title>Responsive Page</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <style>
    html, body {
      height: 100%;
    }

    .container {
      background-color: orange;
      min-height: 100%;
      display: flex;
      flex-direction: column;
    }

    header {
      background-color: red;
      padding: 20px;
    }

    main {
      flex-grow: 1;
      background-color: red;
      padding: 20px;
    }

    footer {
      background-color: red;
      padding: 20px;
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1>Header</h1>
    </header>

    <main>
      <h2>Main Content</h2>
    </main>

    <footer>
      <h3>Footer</h3>
    </footer>
  </div>
</body>
</html>
