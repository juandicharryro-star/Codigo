<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Res y Sabor | Sabor que enamora</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    font-family: Arial, sans-serif;
    background: #fff9f0;
    color: #351b16;
}

header {
    background: #651c24;
    color: white;
    padding: 20px 7%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 15px;
}

.logo {
    font-size: 27px;
    font-weight: bold;
}

.logo span {
    color: #ffc857;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 18px;
    font-weight: bold;
}

nav a:hover {
    color: #ffc857;
}

.hero {
    min-height: 440px;
    background:
    linear-gradient(90deg, rgba(35,12,8,.88), rgba(35,12,8,.25)),
    url("https://images.unsplash.com/photo-1544025162-d76694265947?auto=format&fit=crop&w=1500&q=85");
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: center;
    padding: 60px 8%;
    color: white;
}

.hero-content {
    max-width: 600px;
}

.hero h1 {
    font-size: 52px;
    margin-bottom: 18px;
}

.hero h1 span {
    color: #ffc857;
}

.hero p {
    font-size: 18px;
    line-height: 1.6;
    margin-bottom: 25px;
}

.btn {
    display: inline-block;
    background: #ffc857;
    color: #351b16;
    padding: 13px 22px;
    border-radius: 8px;
    text-decoration: none;
    font-weight: bold;
    border: none;
    cursor: pointer;
    transition: .3s;
}

.btn:hover {
    background: #f0ad26;
    transform: translateY(-2px);
}

section {
    padding: 55px 7%;
}

.section-title {
    text-align: center;
    font-size: 32px;
    margin-bottom: 12px;
    color: #651c24;
}

.subtitle {
    text-align: center;
    color: #765d55;
    margin-bottom: 35px;
}

.products {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 25px;
}

.card {
    background: white;
    border-radius: 14px;
    overflow: hidden;
    box-shadow: 0 5px 18px rgba(70, 30, 20, .12);
    transition: .3s;
}

.card:hover {
    transform: translateY(-6px);
}

.card img {
    width: 100%;
    height: 190px;
    object-fit: cover;
}

.card-content {
    padding: 20px;
}

.card h3 {
    font-size: 23px;
    margin-bottom: 10px;
}

.card p {
    color: #765d55;
    line-height: 1.5;
    margin-bottom: 15px;
}

.price {
    color: #651c24;
    font-size: 25px;
    font-weight: bold;
    margin-bottom: 18px;
}

.card .btn {
    width: 100%;
    text-align: center;
}

.about {
    background: #f3e5d3;
}

.about-content {
    max-width: 850px;
    margin: auto;
    text-align: center;
    line-height: 1.8;
}

.values {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 12px;
    margin-top: 22px;
}

.value {
    background: white;
    border-radius: 20px;
    padding: 10px 18px;
    font-weight: bold;
    color: #651c24;
}

.contact {
    text-align: center;
    background: #651c24;
    color: white;
}

.contact .section-title {
    color: #ffc857;
}

.contact p {
    margin: 14px 0;
    font-size: 18px;
}

.contact .btn {
    margin-top: 15px;
}

footer {
    background: #351b16;
    color: white;
    text-align: center;
    padding: 22px;
    font-size: 14px;
}

@media (max-width: 600px) {
    header {
        justify-content: center;
        text-align: center;
    }

    nav a {
        margin: 5px 8px;
        display: inline-block;
    }

    .hero h1 {
        font-size: 38px;
    }

    .hero {
        min-height: 400px;
    }

    .section-title {
        font-size: 27px;
    }
}
</style>
</head>

<body>

<header>
    <div class="logo">🥩 Res <span>y Sabor</span></div>
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#productos">Productos</a>
        <a href="#nosotros">Nosotros</a>
        <a href="#contacto">Contacto</a>
    </nav>
</header>

<section class="hero" id="inicio">
    <div class="hero-content">
        <h1>¡El sabor que <span>te encanta!</span></h1>
        <p>
            En Res y Sabor preparamos deliciosos alimentos
            con sabor, calidad y una excelente presentación.
            ¡Ven a probar nuestros productos!
        </p>
        <a href="#productos" class="btn">Ver nuestro menú</a>
    </div>
</section>

<section id="productos">
    <h2 class="section-title">Nuestro menú</h2>
    <p class="subtitle">
        Deliciosas opciones preparadas para disfrutar.
    </p>

    <div class="products">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1626700051175-6818013e1d4f?auto=format&fit=crop&w=700&q=80"
                 alt="Burrito">
            <div class="card-content">
                <h3>🌯 Burritos</h3>
                <p>Una deliciosa combinación de ingredientes envueltos en una tortilla.</p>
                <div class="price">$10.500 COP</div>
                <a class="btn" href="https://wa.me/573224295787?text=Hola%2C%20quiero%20informacion%20sobre%20los%20burritos">
                    Me interesa
                </a>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1544025162-d76694265947?auto=format&fit=crop&w=700&q=80"
                 alt="Picada">
            <div class="card-content">
                <h3>🍟 Picada</h3>
                <p>Una opción deliciosa para compartir y disfrutar de buenos sabores.</p>
                <div class="price">$14.000 COP</div>
                <a class="btn" href="https://wa.me/573224295787?text=Hola%2C%20quiero%20informacion%20sobre%20la%20picada">
                    Me interesa
                </a>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1552332386-f8dd00dc2f85?auto=format&fit=crop&w=700&q=80"
                 alt="Tacos">
            <div class="card-content">
                <h3>🌮 Tacos</h3>
                <p>Una preparación llena de sabor, ideal para disfrutar en cualquier momento.</p>
                <div class="price">$10.600 COP</div>
                <a class="btn" href="https://wa.me/573224295787?text=Hola%2C%20quiero%20informacion%20sobre%20los%20tacos">
                    Me interesa
                </a>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1513104890138-7c749659a591?auto=format&fit=crop&w=700&q=80"
                 alt="Arepas">
            <div class="card-content">
                <h3>🫓 Arepas</h3>
                <p>Una opción deliciosa para disfrutar con una buena combinación de sabores.</p>
                <div class="price">$11.200 COP</div>
                <a class="btn" href="https://wa.me/573224295787?text=Hola%2C%20quiero%20informacion%20sobre%20las%20arepas">
                    Me interesa
                </a>
            </div>
        </div>

    </div>
</section>

<section class="about" id="nosotros">
    <h2 class="section-title">¿Quiénes somos?</h2>
    <div class="about-content">
        <p>
            Somos <strong>Res y Sabor</strong>, un emprendimiento
            dedicado a la elaboración y comercialización de alimentos
            a base de carne de res. Nos esforzamos por ofrecer productos
            deliciosos, con buena calidad, higiene y precios accesibles.
        </p>

        <br>

        <h3>Nuestra misión</h3>
        <p>
            Ofrecer alimentos de buen sabor y calidad, brindando
            una atención amable y una experiencia agradable a nuestros clientes.
        </p>

        <br>

        <h3>Nuestra visión</h3>
        <p>
            Convertirnos en un emprendimiento reconocido por nuestros
            productos, servicio y compromiso con los clientes.
        </p>

        <div class="values">
            <span class="value">⭐ Calidad</span>
            <span class="value">🤝 Respeto</span>
            <span class="value">🧼 Higiene</span>
            <span class="value">💡 Innovación</span>
            <span class="value">❤️ Buen servicio</span>
        </div>
    </div>
</section>

<section class="contact" id="contacto">
    <h2 class="section-title">¡Contáctanos!</h2>
    <p>📱 Teléfono: <strong>322 429 5787</strong></p>
    <p>📅 Feria empresarial: 28 de octubre de 2026</p>
    <p>⏰ Hora: 8:00 a. m.</p>
    <p>¡Te esperamos para compartir el sabor de Res y Sabor!</p>

    <a class="btn" href="https://wa.me/573224295787"
       target="_blank" rel="noopener noreferrer">
        Escribir por WhatsApp
    </a>
</section>

<footer>
    <p>© 2026 Res y Sabor | Sabor que enamora 🥩</p>
</footer>

</body>
</html># Codigo
