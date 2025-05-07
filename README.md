/my-portfolio/
│
├── index.html
├── style.css
└── /images/
    ├── img1.jpg
    ├── img2.jpg
    └── mbby1.jpg

<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <title>Моя Візитка</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Привіт!</h1>
    <h2>Ім’я Прізвище</h2>
    <img src="images/img1.jpg" alt="Фото" class="avatar">
    <p class="quote">"Короткий девіз або цитата"</p>
    <nav>
      <a href="about.html">Про себе</a>
      <a href="interests.html">Інтереси</a>
      <a href="future.html">Плани на майбутнє</a>
    </nav>
  </header>
</body>
</html>

 body {
  background-color: #f0f0f0;
  color: #333;
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  text-align: center;
  padding: 20px;
}

.avatar {
  width: 150px;
  height: 150px;
  border-radius: 50%;
}

nav a {
  margin: 10px;
  padding: 8px 15px;
  background-color: #007BFF;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}

nav a:hover {
  background-color: #0056b3;
}

.quote {
  font-style: italic;
}

<h2>Про себе</h2>
<p>Дата народження: 01.01.2007</p>
<p>Школа: Ліцей №1</p>
<p>Клас: 11-А</p>
<p>Улюблені предмети: Математика, Інформатика</p>

<form>
  <p>Напрям, який цікавить найбільше:</p>
  <label><input type="radio" name="napryam" value="tech"> Технічний</label>
  <label><input type="radio" name="napryam" value="human"> Гуманітарний</label>
  <label><input type="radio" name="napryam" value="art"> Мистецький</label>
</form>
