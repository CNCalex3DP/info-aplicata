<!DOCTYPE html>
<html lang="ro">
<head>
    
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site de Filme</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header -->
    
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
            <img src="mac.jpg" alt="Film 1">
            <div class="overlay">
                <h2>Mac & Devin go to HIGHschool</h2>
                <p>Un film captivant de comedie și aventură.</p>
                <a href="#">Vezi acum</a>
            </div>
        </div>
        <div class="carousel-slide">
            <img src="cheech.jpg" alt="Film 2">
            <div class="overlay">
                <h2>Cheech & Chong's animated movie!</h2>
                <p>O aventura animata ce te va face sa razi cu lacrimi.</p>
                <a href="#">Vezi acum</a>
            </div>
        </div>
        <div class="carousel-slide">
            <img src="purge.jpg" alt="Film 3">
            <div class="overlay">
                <h2>the purge</h2>
                <p>un film horror care iti va da cosmaruri.</p>
                <a href="#">Vezi acum</a>
            </div>
        </div>
    </section>

    <!-- Secțiune Filme Recomandate -->
    <section id="recomandari">
        <h2>Filme Recomandate</h2>
        <div class="filme-lista">
            <div class="film">
                <img src="film4.jpg" alt="Film 4">
                <h3>Film Recomandat 1</h3>
                <p>Acțiune, Aventura</p>
                <a href="#">Vezi acum</a>
            </div>
            <div class="film">
                <img src="film5.jpg" alt="Film 5">
                <h3>Film Recomandat 2</h3>
                <p>Comedie, Dramă</p>
                <a href="#">Vezi acum</a>
            </div>
            <div class="film">
                <img src="dijointed.jpg" alt="Film 6">
                <h3>Film Recomandat 3</h3>
                <p>Thriller, Mister</p>
                <a href="#">Vezi acum</a>
            </div>
        </div>
    </section>

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
        <p>&copy; 2024 Filme Online. Toate drepturile rezervate."NU sunt piratate de pe filelist"</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>                </title>
    <style>
        
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f4f4f4;
        }

        
        .hover-effect {
            display: inline-block;
            padding: 20px 40px;
            background-color: #3498db;
            color: white;
            text-decoration: none;
            border-radius: 10px;
            font-size: 18px;
            font-weight: bold;
            transition: all 0.3s ease; 
        }

        
        .hover-effect:hover {
            background-color: #e74c3c; 
            transform: scale(1.1); 
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2); 
            color: #fff;
            text-decoration: underline;
        }

    </style>
</head>
<body>

    <a href="#" class="hover-effect" /a>

</body>
</html>
