# Lab1_web_development
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <style> 
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        .container {
            display: flex;
            height: 100vh; /* Make the container take the full viewport height */
        }

        .column {
            flex: 1;
            text-align: center;
            overflow: hidden; /* Hide overflowing content */
        }

        .bgimgs {
            background-image: url('https://media.istockphoto.com/id/1182450718/photo/happy-family-watching-movie-on-a-laptop.webp?b=1&s=170667a&w=0&k=20&c=Yr3JFMrAo6zibV34RapYuPXumRKDe4MIX_yTvVutQEM=');
            background-size: cover;
            background-position: center;
            color: red;
            padding: 20px; /* Add padding for better readability */
            box-sizing: border-box; /* Include padding in the total width */
        }

        .content {
            margin-top: 30%;
        }

        .image-container {
            overflow: hidden;
        }

        .image-container img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
    </style>
</head>
<body>
    
    <div class="container">

        <div class="column bgimgs">
            <div class="content">
                <h1>We Work</h1>
                <h3>We Are Opening Soon</h3>
                <h4>You can rent offices at affordable prices</h4>
            </div>
        </div>
        
        <div class="column image-container">
            <img src="https://media.istockphoto.com/id/184103864/photo/clouds-on-sky.jpg?s=1024x1024&w=is&k=20&c=n09_q789C4LPvey3op74SGkt3-OgmR8r-giT5jiEWeA=" alt=" ">
        </div>
        
    </div>
</body>
</html>
