<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CET Engenharia | Campinas e Região</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Poppins', sans-serif;
    background: #0a1f33;
    color: #fff;
}

header {
    display: flex;
    justify-content: space-between;
    padding: 20px 50px;
    background: rgba(0,0,0,0.4);
    position: fixed;
    width: 100%;
}

header h1 {
    color: #d4a95b;
}

nav a {
    color: white;
    margin-left: 20px;
    text-decoration: none;
}

.hero {
    height: 100vh;
    background: url('https://images.unsplash.com/photo-1503387762-592deb58ef4e') center/cover;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
}

.hero div {
    background: rgba(0,0,0,0.6);
    padding: 40px;
    border-radius: 10px;
}

.hero h2 {
    font-size: 40px;
    margin-bottom: 15px;
}

.btn {
    background: #d4a95b;
    padding: 12px 25px;
    text-decoration: none;
    color: black;
    font-weight: bold;
    border-radius: 5px;
}

.section {
    padding: 80px 50px;
    text-align: center;
}

.services {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
}

.card {
    background: #112b45;
    padding: 30px;
    border-radius: 10px;
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-10px);
}

.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
}

.gallery img {
    width: 100%;
    height: 250px;
    object-fit: cover;
}

footer {
    background: #081521;
    padding: 30px;
    text-align: center;
}
</style>
</head>

<body>

<header>
    <h1>CET Engenharia</h1>
    <nav>
        <a href="#servicos">Serviços</a>
        <a href="#sobre">Sobre</a>
        <a href="#contato">Contato</a>
    </nav>
</header>

<section class="hero">
    <div>
        <h2>Excelência em Engenharia</h2>
        <p>Soluções completas em Campinas e região</p>
        <br>
        <a href="https://wa.me/SEUNUMERO" class="btn">Solicitar Orçamento</a>
    </div>
</section>

<section id="servicos" class="section">
    <h2>Serviços</h2>
    <br><br>
    <div class="services">
        <div class="card">
            <h3>Projetos Estruturais</h3>
            <p>Segurança e precisão para sua obra.</p>
        </div>
        <div class="card">
            <h3>Regularização</h3>
            <p>Legalize seu imóvel com facilidade.</p>
        </div>
        <div class="card">
            <h3>Laudos Técnicos</h3>
            <p>Análises profissionais e confiáveis.</p>
        </div>
        <div class="card">
            <h3>Reformas</h3>
            <p>Execução com qualidade e acompanhamento.</p>
        </div>
    </div>
</section>

<section class="gallery">
    <img src="https://images.unsplash.com/photo-1581091012184-5c1d9b1e7c66">
    <img src="https://images.unsplash.com/photo-1503387762-592deb58ef4e">
    <img src="https://images.unsplash.com/photo-1590650046871-92c887180603">
</section>

<section id="sobre" class="section">
    <h2>Sobre a CET Engenharia</h2>
    <br>
    <p>Atuamos com excelência em serviços de engenharia, oferecendo soluções modernas, seguras e eficientes para clientes em Campinas e região.</p>
</section>

<section id="contato" class="section">
    <h2>Contato</h2>
    <br>
    <a href="https://wa.me/SEUNUMERO" class="btn">Falar no WhatsApp</a>
</section>

<footer>
    <p>© 2026 CET Engenharia</p>
</footer>

</body>
</html>
