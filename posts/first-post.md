<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>{{ page.title }}</title>

  <!-- Link to CSS file -->
  <link rel="stylesheet" href="{{ "/assets/css/style.css" | relative_url }}">

  <!-- Optional: If you're using SCSS -->
  <link rel="stylesheet" href="{{ "/assets/css/main.css" | relative_url }}">

</head>
<body>

  {{ content }}

<a href="https://example.com" class="badge" target="_blank">
  <img src="/assets/images/jane.svg" alt="Badge Image">
  Example Badge
</a>

</body>
</html>

