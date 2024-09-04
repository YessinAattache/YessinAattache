<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Confirmez Votre Bonus de Fin d'Année</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e0f7fa; /* Soft background color */
            margin: 0;
            padding: 0;
        }
        .container {
            position: relative; /* Position relative to position the dinosaur */
            max-width: 600px;
            margin: 100px auto;
            padding: 20px;
            background-color: #f4f4f4;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        h1 {
            color: #333;
            margin-top: 60px; /* Add some top margin for space for the dinosaur */
        }
        p {
            color: #555;
        }
        .btn {
            display: inline-block;
            padding: 12px 20px;
            margin-top: 20px;
            background-color: #4CAF50;
            color: #ffffff;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .btn:hover {
            background-color: #45a049; /* Darker green on hover */
        }
        /* Dinosaur styling */
        .dinosaur {
            position: absolute; /* Absolute positioning to animate over the container */
            width: 50px; /* Adjust the size of the dinosaur */
            left: 50%; /* Center horizontally */
            transform: translateX(-50%); /* Center the dinosaur */
            bottom: 180px; /* Position the dinosaur above the heading text */
            animation: jump 2s infinite; /* Jump animation */
        }
        /* Jump animation */
        @keyframes jump {
            0%, 100% {
                bottom: 140px; /* Start and end position, just above the text */
            }
            50% {
                bottom: 200px; /* Highest point of the jump */
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Dinosaur Image placed above the heading -->
        <img src="https://github.com/YessinAattache/YessinAattache/blob/main/dinosaur.jpg?raw=true" alt="Dinosaur" class="dinosaur">
        <h1>Confirmez Votre Bonus de Fin d'Année</h1>
        <p>Vous êtes éligible pour un bonus de performance de fin d'année. Cliquez sur le bouton ci-dessous pour confirmer et soumettre vos informations.</p>
        <a href="https://docs.google.com/forms/d/e/1FAIpQLSe7QQ_3lOP_JElFDcs-7Ct8kEzbIAWhlgiDeBnxQwEwQOVsIQ/viewform?usp=sf_link" class="btn" aria-label="Réclamer votre bonus de fin d'année" rel="noopener noreferrer">Réclamer Votre Bonus</a>
    </div>
</body>
</html>
