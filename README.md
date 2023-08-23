<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix Clone</title>
    <style>
        
        body, h1, p {
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Arial, sans-serif;
        }

     
        header {
            background-color: #000;
            color: #fff;
            padding: 20px 0;
        }

        .logo img {
            width: 100px;
            height: auto;
        }

        nav ul {
            list-style: none;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
            font-size: 18px;
        }

       
        .hero {
            background-image: url('netflix-hero.jpg');
            background-size: cover;
            background-position: center;
            color: #fff;
            text-align: center;
            padding: 100px 0;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 1.5rem;
            margin-bottom: 30px;
        }

        .hero button {
            background-color: #e50914;
            color: #fff;
            border: none;
            padding: 10px 20px;
            font-size: 1.2rem;
            cursor: pointer;
        }

        .movie-list {
            padding: 40px 0;
            text-align: center;
        }

        .movie-list h2 {
            font-size: 2rem;
            margin-bottom: 20px;
        }

        .movies {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }

        footer {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }
    </style>
</head>
<body>
    <header>
    
       
      
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Netflix Clone</title>
    </head>
    <body>
        <header>
            <div class="logo">
                <img src="netflix-logo.png" alt="Netflix Logo">
            </div>
            <nav>
                <ul>
                    <li><button id="homeButton">Home</button></li>
                    <li><button id="tvShowsButton">TV Shows</button></li>
                    <li><button id="moviesButton">Movies</button></li>
                    <li><button id="latestButton">Latest</button></li>
                    <li><button id="myListButton">My List</button></li>
                </ul>
            </nav>
        </header>

        

        <main class="main-content">
            <div id="imageContainer"></div>
        </main>

</body>
</html>


    <main>
        <section class="hero">
            <div class="hero-content">
                <h1>Welcome to Netflix</h1>
                <p>Unlimited movies, TV shows, and more.</p>
                <main class="main-content">
                    <div id="imageContainer"></div>
                    <button><a href="your-watch-now-link.html" target="_blank">Watch Now</a></button>
                </main>
            </div>
        </section>

        <section class="movie-list">
            <h2>Popular Movies</h2>
            <div class="movies">
                <img src="adhipurush,jpg.jpeg" alt="Adipurush">
                
                <img src="WEDNESDAY.jpg" alt="WEDNESDAY" width="300" height="200">

            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 Netflix Clone by Gayathri.Vura</p>
    </footer>
</body>
</html>
