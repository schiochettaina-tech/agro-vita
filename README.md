<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<title>AgroVita</title>
<style>
body {
    font-family: Arial;
    margin: 0;
    background: #f5f5f5;
}

header {
    background: #1B5E20;
    color: white;
    padding: 20px;
    text-align: center;
}

nav {
    background: #4CAF50;
    padding: 10px;
    text-align: center;
}

nav a {
    color: white;
    margin: 10px;
    text-decoration: none;
    font-weight: bold;
}

.banner {
    background: url('https://images.unsplash.com/photo-1500382017468-9049fed747ef');
    background-size: cover;
    color: white;
    padding: 100px;
    text-align: center;
}

.banner h1 {
    font-size: 40px;
}

.produtos {
    display: flex;
    justify-content: center;
    gap: 20px;
    padding: 40px;
}

.card {
    background: white;
    padding: 20px;
    border-radius: 10px;
    width: 250px;
    text-align: center;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

button {
    background: #C8A951;
    border: none;
    padding: 10px;
    color: white;
    cursor: pointer;
}

footer {
    background: #1B5E20;
    color: white;
    text-align: center;
    padding: 20px;
}
</style>
</head>

<body>

<header>
    <h1>AgroVita</h1>
    <p>Força que vem da terra</p>
</header>

<nav>
    <a href="#">Início</a>
    <a href="#">Produtos</a>
    <a href="#">Sobre</a>
    <a href="#">Contato</a>
</nav>

<div class="banner">
    <h1>Mais produtividade começa no solo</h1>
    <button>Comprar agora</button>
</div>

<section class="produtos">
    <div class="card">
        <h3>NitroMax</h3>
        <p>Fertilizante de alto rendimento</p>
        <button>Comprar</button>
    </div>

    <div class="card">
        <h3>BioGrow</h3>
        <p>Biofertilizante sustentável</p>
        <button>Comprar</button>
    </div>

    <div class="card">
        <h3>Raiz Forte</h3>
        <p>Estimulador de raízes</p>
        <button>Comprar</button>
    </div>
</section>

<footer>
    <p>© 2026 AgroVita - Todos os direitos reservados</p>
</footer>

</body>
</html>
