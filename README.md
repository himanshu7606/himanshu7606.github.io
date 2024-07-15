# himanshu7606.github.io/
* Reset default styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body styles */
body {
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;
    color: #333;
}

/* Header styles */
.header {
    background-color: #6a0dad; /* Purple background */
    color: #fff;
    padding: 1rem 0;
}

.header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
    margin-left: 2rem;
}

.nav-links {
    list-style-type: none;
    display: flex;
    gap: 1rem;
    margin-right: 2rem;
}

.nav-links li {
    padding: 0.5rem;
}

.nav-links li a {
    color: #fff;
    text-decoration: none;
    transition: color 0.3s ease;
}

.nav-links li a:hover {
    color: #ddd;
}

/* Main styles */
.main {
    padding: 2rem 0;
}

.products {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
    justify-items: center;
}

.product {
    background-color: #fff;
    padding: 1rem;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    text-align: center;
}

.product img {
    width: 100%;
    border-radius: 8px;
    margin-bottom: 1rem;
}

.product h2 {
    font-size: 1.2rem;
    margin-bottom: 0.5rem;
    color: #6a0dad; /* Purple color */
}

.product p {
    font-size: 0.9rem;
    margin-bottom: 1rem;
}

.product .price {
    font-weight: bold;
}

.product button {
    background-color: #6a0dad;
    color: #fff;
    border: none;
    padding: 0.5rem 1rem;
    border-radius: 4px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.product button:hover {
    background-color: #4d087b; /* Darker purple */
}

/* Footer styles */
.footer {
    background-color: #6a0dad;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

.footer p {
    margin: 0;
}

/* Container styles */
.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
}
