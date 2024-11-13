<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Movie & TV Show Website</title>
    <style>
        /* Add all the CSS code here */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            padding: 1rem;
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
            margin: 0 10px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
        }

        h2 {
            text-align: center;
            margin-top: 20px;
        }

        .movie-list, .tv-show-list {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        .movie-item, .tv-show-item {
            background-color: #fff;
            padding: 15px;
            border-radius: 10px;
            width: 250px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .movie-item img, .tv-show-item img {
            width: 100%;
            border-radius: 10px;
        }

        button {
            margin-top: 10px;
            padding: 10px;
            background-color: #333;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }

        button:hover {
            background-color: #444;
        }

        .trailer {
            display: none;
            margin-top: 15px;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to Movie & TV Show Zone</h1>
        <nav>
            <ul>
                <li><a href="#movies">Movies</a></li>
                <li><a href="#tv-shows">TV Shows</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="movies">
        <h2>Popular Movies</h2>
        <div class="movie-list">
            <div class="movie-item">
                <img src="movie1.jpg" alt="Movie 1">
                <h3>Movie 1</h3>
                <button onclick="showTrailer('movie1-trailer')">Watch Trailer</button>
                <div class="trailer" id="movie1-trailer">
                    <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </div>
            </div>
            <!-- More movies go here -->
        </div>
    </section>

    <section id="tv-shows">
        <h2>Popular TV Shows</h2>
        <div class="tv-show-list">
            <div class="tv-show-item">
                <img src="tvshow1.jpg" alt="TV Show 1">
                <h3>TV Show 1</h3>
                <button onclick="showTrailer('tvshow1-trailer')">Watch Trailer</button>
                <div class="trailer" id="tvshow1-trailer">
                    <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </div>
            </div>
            <!-- More TV shows go here -->
        </div>
    </section>

    <footer id="contact">
        <p>Contact us: email@example.com</p>
    </footer>

    <script>
        /* Add all the JavaScript here */
        function showTrailer(trailerId) {
            const trailerElement = document.getElementById(trailerId);
            if (trailerElement.style.display === "block") {
                trailerElement.style.display = "none";
            } else {
                trailerElement.style.display = "block";
            }
        }
    </script>

</body>
</html>
