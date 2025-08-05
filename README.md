# akash3spn.github.io<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>আমার অনলাইন দোকান | My Online Shop</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>আমার অনলাইন দোকানে স্বাগতম</h1>
        <nav>
            <a href="#">হোম | Home</a>
            <a href="#">পণ্য | Products</a>
            <a href="#">প্রোফাইল | Profile</a>
            <a href="#">সেটিংস | Settings</a>
            <a href="#">লগইন | Login</a>
            <a href="#">সাইন আপ | Sign Up</a>
        </nav>
    </header>

    <main>
        <section class="product">
            <h2>পপুলার পণ্য</h2>
            <div class="product-card">
                <img src="https://via.placeholder.com/150" alt="product">
                <h3>প্রোডাক্ট ১ | Product 1</h3>
                <p>৳500 | $5</p>
                <button>কিনুন | Buy Now</button>
            </div>
        </section>
    </main>

    <footer>
        <p>© 2025 আমার দোকান | MyShop</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: #f2f2f2;
}

header {
    background: #2a9d8f;
    color: white;
    padding: 20px;
    text-align: center;
}

nav a {
    margin: 0 10px;
    color: white;
    text-decoration: none;
}

.product {
    padding: 20px;
    text-align: center;
}

.product-card {
    display: inline-block;
    background: white;
    padding: 10px;
    border-radius: 8px;
    margin: 10px;
    box-shadow: 0 0 5px rgba(0,0,0,0.1);
}

button {
    background: #e76f51;
    color: white;
    border: none;
    padding: 10px;
    border-radius: 5px;
    cursor: pointer;
}

footer {
    background: #264653;
    color: white;
    text-align: center;
    padding: 10px;
}
