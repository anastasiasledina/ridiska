# ridiska
git init
git remote add origin <URL-ВАШЕГО-РЕПОЗИТОРИЯ>
echo "<!DOCTYPE html>
<html lang='en'>
<head>
    <meta charset='UTF-8'>
    <meta name='viewport' content='width=device-width, initial-scale=1.0'>
    <title>Обо мне</title>
</head>
<body>
    <h1>Привет, я Анастасия</h1>
    <p>Я занимаюсь IT и дизайном. Здесь будет моя профессиональная информация.</p>
</body>
</html>" > index.html
git add index.html
git commit -m "Создан index.html с информацией о себе"
git push -u origin master
