# Prototype
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

.hero {
    height: 100vh;
    background: linear-gradient( rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url("https://images.unsplash.com/photo-1501785888041-af3ef285b470");
    background-size: cover;
    background-position: center;
    color: white;
    https: blue;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 60px;
}

.logo {
    font-size: 24px;
}

.logo span {
    color: #00c3ff;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline-block;
    margin-left: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 14px;
}

nav ul li a:hover {
    color: #00c3ff;
}

.hero-content {
    height: calc(100vh - 80px);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.hero-content img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 4px solid #00c3ff;
    margin-bottom: 20px;
}

.hero-content h1 {
    font-size: 40px;
}

.hero-content p {
    font-size: 18px;
    color: #ccc;
}
