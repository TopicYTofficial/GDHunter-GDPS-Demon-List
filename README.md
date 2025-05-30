<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Демонлист</title>
<style>
  body {
    background-color: #1e2630;
    color: #ddd;
    font-family: Arial, sans-serif;
    margin: 20px;
  }
  .container {
    max-width: 500px;
    margin: 0 auto;
  }
  .item {
    display: flex;
    background-color: #2c3440;
    border-radius: 12px;
    padding: 10px;
    margin-bottom: 15px;
    align-items: center;
  }
  .thumbnail {
    width: 120px;
    height: 60px;
    border-radius: 8px;
    object-fit: cover;
    flex-shrink: 0;
  }
  .info {
    margin-left: 15px;
    display: flex;
    flex-direction: column;
  }
  .title {
    font-weight: bold;
    font-size: 1.1em;
    margin-bottom: 5px;
  }
  .author {
    color: #a0a0a0;
    font-size: 0.9em;
    margin-bottom: 3px;
  }
  .id {
    color: #888;
    font-size: 0.8em;
  }
</style>
</head>
<body>
  <div class="container">
    <div class="item">
      <img src="https://via.placeholder.com/120x60?text=1" alt="#1 thumbnail" class="thumbnail" />
      <div class="info">
        <div class="title">#1 - UnMaded</div>
        <div class="author">от royalGG</div>
        <div class="id">id - 257</div>
      </div>
    </div>
    <div class="item">
      <img src="https://via.placeholder.com/120x60?text=2" alt="#2 thumbnail" class="thumbnail" />
      <div class="info">
        <div class="title">#2 - uaua factorial</div>
        <div class="author">от ExactZ</div>
        <div class="id">id - 212</div>
      </div>
    </div>
    <!-- Добавьте остальные элементы аналогично -->
  </div>
</body>
</html>
