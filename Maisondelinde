<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Maison de l'Inde - Restaurant Indien</title>
<style>
:root {
    --saffron: #D97706;
    --green: #0F3D2E;
    --red: #7A1F1F;
    --ivory: #FAF7F2;
    --dark: #1c1c1c;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: "Segoe UI", sans-serif;
    background: var(--ivory);
    color: var(--dark);
    line-height: 1.6;
}

/* HEADER */
header {
    height: 90vh;
    background: linear-gradient(rgba(15,61,46,0.6), rgba(15,61,46,0.6)),
                url("https://images.unsplash.com/photo-1604908177522-040ff3f8b1c3") center/cover no-repeat;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
}

header h1 {
    font-size: 4rem;
    letter-spacing: 2px;
}

header p {
    font-size: 1.3rem;
    margin: 15px 0;
}

/* NAVIGATION FIXE */
nav {
    position: fixed;
    top: 0;
    width: 100%;
    background: rgba(28,28,28,0.9);
    padding: 15px;
    text-align: center;
    z-index: 10;
}

nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
    font-weight: 500;
}

/* SECTIONS */
section {
    max-width: 1400px;
    margin: auto;
    padding: 80px 30px;
}

h2 {
    font-size: 2.5rem;
    color: var(--green);
    margin-bottom: 30px;
    text-align: center;
}

/* LIVRAISON */
.delivery-message {
    background-color: var(--saffron);
    color: white;
    font-weight: 700;
    text-align: center;
    padding: 18px 20px;
    border-radius: 8px;
    font-size: 1.1em;
    margin: 40px 0;
}

/* MENU */
.menu-section {
    max-width: 1000px;
    margin: auto;
}

.dish {
    display: flex;
    justify-content: space-between;
    border-bottom: 1px solid #e9d7b5;
    padding: 10px 0;
}

.dish:last-child {
    border-bottom: none;
}

.dish-name {
    font-weight: 600;
}

.dish-desc {
    font-style: italic;
    color: var(--red);
    font-size: 0.9rem;
}

.price {
    font-weight: bold;
    color: var(--saffron);
    min-width: 50px;
    text-align: right;
}

/* CONTACT */
.contact {
    background: var(--green);
    color: white;
    text-align: center;
    padding: 60px 30px;
}

.contact p {
    margin: 10px 0;
    font-size: 1.1rem;
}

/* FOOTER */
footer {
    background: var(--dark);
    color: white;
    text-align: center;
    padding: 20px;
}

@media (max-width: 768px) {
    header h1 {
        font-size: 2.5rem;
    }
    .dish {
        flex-direction: column;
        align-items: flex-start;
    }
    .price {
        margin-top: 5px;
        text-align: left;
    }
}
</style>
</head>
<body>

<nav>
    <a href="#accueil">Accueil</a>
    <a href="#menu">Menu</a>
    <a href="#contact">Contact</a>
</nav>

<header id="accueil">
    <h1>Maison de l'Inde</h1>
    <p>Restaurant Indien – Spécialités du Nord de l'Inde</p>
</header>

<section>
    <div class="delivery-message">
      📦 Livraison dans un périmètre de 15 km<br/>
      Du lundi au jeudi : horaires habituels<br/>
      Vendredi & samedi : matin seulement
    </div>
</section>

<section id="menu">
    <h2>Menu Complet</h2>

    <!-- ENTRÉES -->
    <div class="menu-section">
        <h2>Entrées</h2>
        <div class="dish">
            <div>
                <div class="dish-name">Entrée Mix (viande & légumes – 2 pers.)</div>
            </div>
            <div class="price">20 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Shammi kebab</div>
                <div class="dish-desc">Croquettes de viande hachée parfumées à la cardamome</div>
            </div>
            <div class="price">10 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Onion bajia</div>
                <div class="dish-desc">Beignets d’oignons</div>
            </div>
            <div class="price">8 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Vegetable samossa</div>
            </div>
            <div class="price">9 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Raita</div>
                <div class="dish-desc">Yaourt au concombre parfumé au cumin</div>
            </div>
            <div class="price">7 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Crevette pakora</div>
            </div>
            <div class="price">11 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Fromage pakora</div>
            </div>
            <div class="price">9 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Beigan pakora</div>
            </div>
            <div class="price">9 €</div>
        </div>
    </div>

    <!-- GRILLADES -->
    <div class="menu-section">
        <h2>Grillades</h2>
        <div class="dish">
            <div>
                <div class="dish-name">Poulet tikka</div>
            </div>
            <div class="price">12 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Poulet tandoori</div>
            </div>
            <div class="price">12 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Seekh kebab</div>
            </div>
            <div class="price">17 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Poisson tikka</div>
            </div>
            <div class="price">17 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Gambas tandoori</div>
            </div>
            <div class="price">24 €</div>
        </div>
    </div>

    <!-- AGNEAU -->
    <div class="menu-section">
        <h2>Agneau</h2>
        <div class="dish">
            <div>
                <div class="dish-name">Agneau baigan</div>
            </div>
            <div class="price">19 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Agneau tikka masala</div>
            </div>
            <div class="price">19 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Agneau madras</div>
            </div>
            <div class="price">19 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Agneau moghlai</div>
            </div>
            <div class="price">19 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Agneau curry</div>
            </div>
            <div class="price">19 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Agneau saagwala</div>
            </div>
            <div class="price">19 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Agneau hyderabadi</div>
            </div>
            <div class="price">19 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Agneau dal</div>
            </div>
            <div class="price">19 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Agneau shahi korma</div>
            </div>
            <div class="price">19 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Agneau seekh masala</div>
            </div>
            <div class="price">20 €</div>
        </div>
    </div>

    <!-- CREVETTES / POISSON -->
    <div class="menu-section">
        <h2>Poisson & Crevettes</h2>
        <div class="dish">
            <div>
                <div class="dish-name">Poisson masala</div>
            </div>
            <div class="price">19 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Poisson goa curry</div>
            </div>
            <div class="price">19 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Poisson madras</div>
            </div>
            <div class="price">19 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Poisson hyderabadi</div>
            </div>
            <div class="price">19 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Crevettes biryani</div>
            </div>
            <div class="price">21 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Noix de Saint-Jacques masala</div>
            </div>
            <div class="price">25 €</div>
        </div>
    </div>

    <!-- BIRYANI -->
    <div class="menu-section">
        <h2>Biryani</h2>
        <div class="dish">
            <div>
                <div class="dish-name">Agneau biryani</div>
            </div>
            <div class="price">21 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Poulet biryani</div>
            </div>
            <div class="price">19 €</div>
        </div>
        <div class="dish">
            <div>
                <div class="dish-name">Vegetable biryani</div>
            </div>
            <div class="price">17 €</div>
        </div>
    </div>
</section>

<section id="contact" class="contact">
    <h2>Contact</h2>
    <p>📍 60, avenue du Général de Gaulle, 68300 Saint-Louis</p>
    <p>📞 09 53 41 65 14 / 06 27 57 44 13</p>
    <p>📧 contact@maisondelinde.fr</p>
    <p>🌐 www.maisondelinde.fr | Instagram: @maison_de_linde</p>
</section>

<footer>
    <p>© 2026 Maison de l'Inde – Cuisine Indienne du Nord</p>
</footer>

</body>
</html>
