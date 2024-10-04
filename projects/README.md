Use the following template inside new project folders to redirect to your project

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta http-equiv="refresh" content="3; url=https://link-to-your-project.com" />
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Redirecting...</title>
  
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f5f5f5;
      color: #333;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      text-align: center;
    }
    
    .redirect-container {
      background-color: #fff;
      padding: 40px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    h1 {
      font-size: 2em;
      margin-bottom: 20px;
    }

    p {
      font-size: 1.2em;
      margin-bottom: 30px;
    }

    .gif-container {
      margin-bottom: 20px;
    }

    .gif-container img {
      width: 150px;
      height: 150px;
    }

    a {
      text-decoration: none;
      color: #007bff;
      font-weight: bold;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="redirect-container">
    <h1>Redirecting...</h1>
    <div class="gif-container">
      <!-- Replace this with any GIF URL you'd like -->
      <img src="https://media.giphy.com/media/3oEjI6SIIHBdRxXI40/giphy.gif" alt="Loading GIF" />
    </div>
    <p>You will be redirected shortly. If not, <a href="https://link-to-your-project.com">click here</a>.</p>
  </div>
</body>
</html>

```
