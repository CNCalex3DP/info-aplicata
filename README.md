<header>
    <div class="logo">
        <h1>Filme Online</h1>
    </div>
    <nav>
        <ul>
            <li><a href="#home">Acasă</a></li>
            <li><a href="#recomandari">Filme Recomandate</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<!-- Secțiune principală -->
<section id="home" class="carousel">
    <div class="carousel-slide">
        <img src="https://upload.wikimedia.org/wikipedia/en/1/11/Mac_%26_Devin_Go_To_High_School.jpg" alt="Film Number 1" width="300" height="350"
         class="overlay">
            <h2>Mac & Devin go to HIGHschool</h2>
            <p>Un film captivant de comedie și aventură ft. un reper popular "Snoop Dog"</p>
            <a href="https://www.imdb.com/title/tt1870425/">Dă click sa vizionezi</a>
        </div>
    </div>
    <div class="carousel-slide">
        <img src="https://m.media-amazon.com/images/M/MV5BMTMxNTMwODM0NF5BMl5BanBnXkFtZTcwODAyMTk2Mw@@._V1_FMjpg_UX1000_.jpg" width="300" height="350">
        <div class="overlay">
            <h2>Batman The Dark Knight</h2>
            <p>Un film de actiune cu Patrick Bateman în rolul principal</p>
            <a href="https://www.imdb.com/title/tt0468569/">Dă click sa vizionezi</a>
        </div>
    </div>
    <div class="carousel-slide">
        <img src="https://m.media-amazon.com/images/M/MV5BNGQ0YTQyYTgtNWI2YS00NTE2LWJmNDItNTFlMTUwNmFlZTM0XkEyXkFqcGc@._V1_FMjpg_UX1000_.jpg" width="300" height="350">
        <div class="overlay">
            <h2>Spider man 2</h2>
            <p>Un film fantastic cu Tobey Maguire în rolul principal</p>
            <a href="https://www.imdb.com/title/tt0316654/">Dă click sa vizionezi</a>
        </div>
    </div>
</section>

<!-- Secțiune Filme Recomandate -->
<section id="recomandari">
    <h2>Filme Recomandate</h2>
    <div class="filme-lista">
        <div class="film">
            <img src="https://m.media-amazon.com/images/M/MV5BNzA1Njg4NzYxOV5BMl5BanBnXkFtZTgwODk5NjU3MzI@._V1_.jpg" width="300" height="350" >
            <h3>Blade runner</h3>
            <p>Acțiune, Aventura</p>
            <a href="https://www.imdb.com/title/tt1856101/">Dă click sa vizionezi</a>
        </div>
        <div class="film">
            <img src="https://m.media-amazon.com/images/M/MV5BYTFmNTFlOTAtNzEyNi00MWU2LTg3MGEtYjA2NWY3MDliNjlkXkEyXkFqcGc@._V1_.jpg" width="300" height="350">
            <h3>Drive</h3>
            <p>Film de actiune cu Ryan Gosling in rolul prîncipal</p>
            <a href="https://www.imdb.com/title/tt0780504/">Dă click sa vizionezi</a>
        </div>
        <div class="film">
            <img src="https://m.media-amazon.com/images/M/MV5BZjM3ZDA2YmItMzhiMi00ZGI3LTg3ZGQtOTk3Nzk0MDY0ZDZhXkEyXkFqcGc@._V1_FMjpg_UX1000_.jpg" width="300" height="350">
            <h3>Transformers 2007</h3>
            <p>Film de Acțiune</p>
            <a href="https://www.imdb.com/title/tt0418279/">Dă click sa vizionezi</a>
            

<!-- Secțiune Contact -->
<section id="contact">
    <h2>Contactează-ne</h2>
    <p>Dacă ai întrebări sau sugestii, nu ezita să ne contactezi.</p>
    <form action="#">
        <label for="nume">Nume:</label>
        <input type="text" id="nume" name="nume" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="mesaj">Mesaj:</label>
        <textarea id="mesaj" name="mesaj" rows="4" required></textarea>

        <button type="submit">Trimite</button>
    </form>
</section>

<!-- Footer -->
<footer>
    <p>&copy; 2024 Filme Online. Toate drepturile rezervate."NU sunt piratate de pe filelist"</p>xx
</footer>
<style>/* Stiluri generale */
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        line-height: 1.6;
        color: #333;
    }
    
    header {
        background: #222;
        color: white;
        padding: 10px 20px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    
    header .logo h1 {
        margin: 0;
    }
    
    header .logo span {
        color: #e50914;
    }
    
    header nav ul {
        list-style: none;
        margin: 0;
        padding: 0;
        display: flex;
    }
    
    header nav ul li {
        margin: 0 10px;
    }
    
    header nav ul li a {
        color: white;
        text-decoration: none;
    }
    
    .hero {
        background: url('hero-bg.jpg') no-repeat center center/cover;
        color: white;
        text-align: center;
        padding: 50px 20px;
    }
    
    .hero .btn {
        background: #e50914;
        color: white;
        padding: 10px 20px;
        text-decoration: none;
        border-radius: 5px;
    }
    
    .movies-section {
        padding: 20px;
        background: #f4f4f4;
        text-align: center;
    }
    
    .movies-container {
        display: flex;
        justify-content: space-around;
        flex-wrap: wrap;
        gap: 20px;
    }
    
    .movie {
        background: white;
        padding: 10px;
        border-radius: 5px;
        box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        width: 250px;
    }
    
    .movie img {
        width: 100%;
        border-radius: 5px;
    }
    
    .about-section, .contact-section {
        padding: 20px;
        text-align: center;
    }
    
    form {
        max-width: 400px;
        margin: 0 auto;
        display: flex;
        flex-direction: column;
    }
    
    form input, form textarea, form button {
        margin: 10px 0;
        padding: 10px;
        border: 1px solid #ccc;
        border-radius: 5px;
    }
    
    form button {
        background: #e50914;
        color: white;
        border: none;
        cursor: pointer;
    }
    
    footer {
        background: #222;
        color: white;
        text-align: center;
        padding: 10px 0;
    }
    </style>
