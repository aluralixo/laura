# laura
/* Resetando margens e preenchimentos padrão */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 1rem;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

nav ul li a:hover {
    text-decoration: underline;
}

section {
    padding: 2rem;
    margin: 1rem auto;
    max-width: 800px;
}

h2 {
    margin-bottom: 1rem;
}

article {
    margin-bottom: 2rem;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}

