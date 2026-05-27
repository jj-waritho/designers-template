[index.html](https://github.com/user-attachments/files/28290370/index.html)
# designers-template[style.css](https://github.com/user-attachments/files/28290371/style.css)[index.html](https://github.com/user-Shoe Shop
Men
Women
kids
sale
Step Into Summer
View Collections
Casual Shoe - $125
Sportwear Shoe - $159
@ 2026 Shoe Shopattachments/files/28290420/index.html)<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shoe shop</title>
    <link rel="stylesheet"href="style.css">
</head>
<body>
    <header>
        <nav>
            <h1>Shoe Shop</h1>
        <ul>
            <li>Men</li><li>Women</li><li>kids</li><li>sale</li>
        </ul>
        </nav>
    </header>
<main>
    <section class="banner">
        <h2>Step Into Summer</h2>
        <button>View Collections</button>
    </section>
    <section class="products">
        <div class="card">Casual Shoe - $125</div>
        <div class="card">Sportwear Shoe - $159</div>
    </section>
</main>
<footer>
    <p>@ 2026 Shoe Shop</p>
</footer>



  :root {
    --primary: #1A73E8;
    --secondary: #FF6F00;
    --text: #212121;
    --background: #FFFFFF;
}

body {
    font-family: Arial, sans-serif;
    background: var(--background);
    color: var(--text);
    margin: 0;
}

header{
    background: var(--primary);
    color: white;
    padding: 1rem;
}

.products {
    display: grid;
    grid-template-columns: 1fr;
    gap: 1rem
}

.card {
    border: 1px solid #CCC;
    padding: 1rem;
}

/* Breakpoints */
@media (min-width: 601px) {
    .products { grid-template-columns: 1fr 1fr; }
}




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shoe shop</title>
    <link rel="stylesheet"href="style.css">
</head>
<body>
    <header>
        <nav>
            <h1>Shoe Shop</h1>
        <ul>
            <li>Men</li><li>Women</li><li>kids</li><li>sale</li>
        </ul>
        </nav>
    </header>
<main>
    <section class="banner">
        <h2>Step Into Summer</h2>
        <button>View Collections</button>
    </section>
    <section class="products">
        <div class="card">Casual Shoe - $125</div>
        <div class="card">Sportwear Shoe - $159</div>
    </section>
</main>
<footer>
    <p>@ 2026 Shoe Shop</p>
</footer>
</body>
</html>

@media (min-width: 1025) {
    .products { grid-template-columns: 1fr 1fr 1fr;}
}



:root {
    --primary: #1A73E8;
    --secondary: #FF6F00;
    --text: #212121;
    --background: #FFFFFF;
}

body {
    font-family: Arial, sans-serif;
    background: var(--background);
    color: var(--text);
    margin: 0;
}

header{
    background: var(--primary);
    color: white;
    padding: 1rem;
}

.products {
    display: grid;
    grid-template-columns: 1fr;
    gap: 1rem
}

.card {
    border: 1px solid #CCC;
    padding: 1rem;
}

/* Breakpoints */
@media (min-width: 601px) {
    .products { grid-template-columns: 1fr 1fr; }
}

@media (min-width: 1025) {
    .products { grid-template-columns: 1fr 1fr 1fr;}
}
</body>
</html>
