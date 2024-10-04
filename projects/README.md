Use the following template inside new project folders to redirect to your project

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta http-equiv="refresh" content="3; url=https://link-to-your-project.com" />
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="stylesheet" href="../styles.css">
  <title>Redirecting...</title>
</head>
<body>
  <div class="redirect-container">
    <h1>Redirecting...</h1>
    <div class="gif-container">
      <!-- Replace this with any GIF URL you'd like -->
      <img src="https://i.pinimg.com/originals/43/23/e9/4323e9a710bb6c8973346125892c845c.gif" alt="Loading GIF" />
    </div>
    <p>You will be redirected shortly. If not, <a href="https://link-to-your-project.com">click here</a>.</p>
  </div>
</body>
</html>
```
