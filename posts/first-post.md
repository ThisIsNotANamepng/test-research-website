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
<style>
.badge {
  display: inline-flex;
  align-items: center;
  padding: 5px 10px;
  background-color: rgba(0, 0, 0, 0.1);  /* Semi-transparent background */
  border-radius: 5px;
  text-decoration: none;
  color: #333;  /* Text color */
  font-weight: bold;
  font-size: 16px;
}

.badge img {
  height: 20px;
  width: auto;
  margin-right: 8px;
}

.badge span {
  font-size: 14px;
}
</style>
</head>
<body>

  {{ content }}

<a href="https://example.com" class="badge" target="_blank">
  <img src="/assets/images/jane.svg" alt="Badge Image">
  Example Badge
</a>

</body>
</html>

