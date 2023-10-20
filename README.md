<!DOCTYPE html>
<html>

<head>
    <title>My Music Streaming</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1E1E1E;
            color: #d34a4a;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #000;
            padding: 10px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            padding: 0;
            font-size: 36px;
        }
        

        main {
            padding: 20px;
        }

        .playlist {
            display: flex;
            flex-wrap: wrap;
        }

        .song {
            width: 200px;
            margin: 10px;
            background-color: #333;
            border-radius: 5px;
            padding: 10px;
            text-align: center;
        }

        .song img {
            max-width: 100%;
        }

        footer {
            text-align: center;
            background-color: #000;
            padding: 10px;
        }
    </style>
</head>

<body>
    <header>
        <h1>Gaana</h1>
    </header>
    <main>
        <h2>Top songs this week</h2>
        <div class="playlist">
            <div class="song">
                <img src="C:\Users\it-8\Pictures\dieforyou.jpg" alt="Song 1">
                <h3>Die for You</h3>
                <p>Artist: The Weeknd</p>
            </div>
            <div class="song">
                <img src="C:\Users\it-8\Pictures\blackswan.jpg" alt="Song 2">
                <h3>Blackswan</h3>
                <p>Artist: BTS</p>
            </div>
            <div class="song">
                <img src="C:\Users\it-8\Pictures\softcore.jpg" alt="Song 3">
                <h3>Softcore</h3>
                <p>Artist: The Neighorhood</p>
            </div>
            <div class="song">
                <img src="C:\Users\it-8\Pictures\d-day.jpg" alt="Song 3">
                <h3>D-day</h3>
                <p>Artist: Agust D </p>
            </div>
            <!-- Add more songs as needed -->
        </div>
    </main>
    <footer>
        &copy; 2023 Gaana  private limited
    </footer>
</body>

</html>

